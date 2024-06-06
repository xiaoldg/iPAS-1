# HTML 表單中 GET 與 POST 的用法差異
```

```

```
HTML 表單中 GET 與 POST 的用法差異
http://www.wibibi.com/info.php?tid=235
```

# 表單[前端]透過 get 方式傳値伺服器接收[後端]

步驟一、HTML 表單 test_form.html（透過 get 方式傳値）
```
<form action="test_get.php" method="get">
　電子郵件: <input type="text" name="Email" />
　<input type="submit" value="送出表單"/>
</form>
```
```
[1]action="test_get.php"，此表單會把資料傳送到 test_get.php 這支程式（步驟二會寫），
[2] method="get"，此處是宣告資料傳遞採用 get 方式傳送，其中 get 必需採用小寫字母。
```

送出表單的按鈕
```
送出表單的按鈕之後，你可以看到網址欄的地方出現以下字串

test_get.php?Email=myemail

由於是採用 GET 的方式傳遞資料，所以 myemail 這個值就跟著網址參數 Email 傳送到下一頁囉！
```
步驟二、PHP GET 資料處理頁面 test_get.php（用來取得網友填寫的資料）
```
<?php
　echo $_GET[Email];
?>
```

### $_GET
```

```

### 表單[前端]透過 post 方式傳値伺服器接收[後端]
```
http://www.wibibi.com/info.php?tid=144
```
步驟一、HTML 表單 test_form.html（採用 POST 方式傳送資料）
```
<form action="test_post.php" method="post">
　姓名: <input type="text" name="Email" />
　<input type="submit" value="送出表單"/>
</form>
```



```
POST method 有資料量 8Mb 的限制，可以從 php.ini 修改。

步驟二、PHP POST 頁面 test_post.php（用來取得網友填寫的資料）
<?php
　echo $_POST["Email"];
?>
這支程式當然就是用來接收剛剛網友所填寫的 Email 資料，透過 PHP 的 echo 將資料輸出於網頁上
```


