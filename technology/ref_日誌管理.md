# 日誌管理

```
Apache Flume - Ingesting log data into Hadoop and Kafka
Detailed workshop about using Flume to ingest web server logs into live Hadoop and Kafka Cluster.
4.2 (10 個評等)  2472 名學生註冊  建立者： Durga Viswanatha Raju Gadiraju, Sunil Abhishek  上次更新 9/2018
https://www.udemy.com/apache-flume-ingesting-log-data-into-hdfs/
```

```
Penetration Testing with Metasploit & Analyzing the IDS logs
Learn to conduct PenTesting / White Hacking using Metasploit plus Analyzing the Intrusion Detection System (IDS) events
4.6 (39 個評等)  2320 名學生註冊   建立者： Ismail Eltahawy  上次更新 5/2017
https://www.udemy.com/penetration-testing-using-metasploit/
```

```
走進計算機取證分析的神秘世界
https://read01.com/3Q88.html#.W6VW-3szaUk

Win8作業系統取證特性分析
https://read01.com/aAJ0gMA.html#.W6VXQ3szaUk

【22款受歡迎的計算機取證工具】
https://read01.com/DOmkgB.html#.W6VXfnszaUk
```
# 日誌管理軟體Log Management Software

```
Log Management Software  
https://www.capterra.com/log-management-software/


4 Good Open Source Log Monitoring and Management Tools for Linux
https://www.tecmint.com/best-linux-log-monitoring-and-management-tools/
1. Graylog 2
2. Logcheck
3. Logwatch
4. Logstash

3 open source log aggregation tools
https://opensource.com/article/18/9/open-source-log-aggregation-tools
ELK== Elasticsearch, Logstash, and Kibana
Graylog uses Elasticsearch, MongoDB, and the Graylog Server
Fluentd
Fluentd was developed at Treasure Data, and the CNCF has adopted it as an Incubating project. It was written in C and Ruby and is recommended by AWS and Google Cloud. Fluentd has become a common replacement for Logstash in many installations. It acts as a local aggregator to collect all node logs and send them off to central storage systems. It is not a log aggregation system.

Best Log Management Tools: 51 Useful Tools for Log Management, Monitoring, Analytics, and More
https://stackify.com/best-log-management-tools/

Monitor Server Logs in Real-Time with “Log.io” Tool on RHEL/CentOS 7/6
https://www.tecmint.com/linux-server-log-monitoring-with-log-io/

How to Manage System Logs (Configure, Rotate and Import Into Database) in RHEL 7 
https://www.tecmint.com/manage-linux-system-logs-using-rsyslogd-and-logrotate/
```

```
Datadog
Centralized Log Collection and Management
Easily collect and manage logs across your environment, from apps to hosts, and all of the services in-between.

https://www.datadoghq.com/
```

### 實戰
```
Open Source Log Management With Nagios
https://www.nagios.com/solutions/open-source-log-management/

https://assets.nagios.com/downloads/nagiosxi/docs/Monitoring-Windows-Event-Logs-With-NagEventLog.pdf#_ga=2.2797683.23390529.1541725418-528815875.1541725418

```

# Windows 日誌管理

```
https://read01.com/meP0AK.html#.W6VJVHszaUk
```
### Winndows 事件日誌 Event Log

```
Windows事件日誌文件本質上是資料庫，其中包括有關係統、安全、應用程式的記錄。
記錄的事件包含9個元素：日期/時間、事件類型、用戶、計算機、事件ID、來源、類別、描述、數據等信息。

Windows事件日誌共有五種事件類型，所有的事件必須只能擁有其中的一種事件類型。
1．信息（Information）
信息事件指應用程式、驅動程序或服務的成功操作的事件。

2．警告（Warning）
警告事件指不是直接的、主要的，但是會導致將來問題發生的問題。
例如，當磁碟空間不足或未找到印表機時，都會記錄一個「警告」事件。

3．錯誤（Error）
錯誤事件指用戶應該知道的重要的問題。錯誤事件通常指功能和數據的丟失。
例如, 如果一個服務不能作為系統引導被加載，那麼它會產生一個錯誤事件。

4． 成功審核（Success audit）
成功的審核安全訪問嘗試，主要是指安全性日誌，這裡記錄著用戶登錄/註銷、對象訪問、特權使用、帳戶管理、
策略更改、詳細跟蹤、目錄服務訪問、帳戶登錄等事件，例如所有的成功登錄系統都會被記錄為「成功審核」事件

5．失敗審核（Failure audit）
失敗的審核安全登錄嘗試，例如用戶試圖訪問網絡驅動器失敗，則該嘗試會被作為失敗審核事件記錄下來。


五種事件類型中，最為重要的是成功審核（Success Audit），所有系統登錄成功都會被標記成為成功審核。


每個成功登錄的事件都會標記一個登錄類型： 
登錄類型	描述
2	交互式登錄（用戶從控制台登錄）
3	網絡（例如：通過net use,訪問共享網絡）
4	批處理（為批處理程序保留）
5	服務啟動（服務登錄）
6	不支持
7	解鎖（帶密碼保護的螢幕保護程序的無人值班工作站）
8	網絡明文（IIS伺服器登錄驗證）
10	遠程交互（終端服務，遠程桌面，遠程輔助）
11	緩存域證書登錄


Windows XML 事件日誌格式
系統事件日誌主要保存的類型為：.evtx，.xml，.txt，.csv。

系統內置的三個核心日誌文件（System，Security和Application）默認大小均為20480KB（20MB），
記錄事件數據超過20MB時，默認系統將優先覆蓋過期的日誌記錄。
其它應用程式及服務日誌默認最大為1024KB，超過最大限制也優先覆蓋過期的日誌記錄。

原文網址：https://read01.com/O3j4KJz.html


事件ID	說明
1102	清理審計日誌
4624	帳號成功登錄
4625	帳號登錄失敗
4768	Kerberos身份驗證（TGT請求）
4769	Kerberos服務票證請求
4776	NTLM身份驗證
4672	授予特殊權限
4720	創建用戶
4726	刪除用戶
4728	將成員添加到啟用安全的全局組中
4729	將成員從安全的全局組中移除
4732	將成員添加到啟用安全的本地組中
4733	將成員從啟用安全的本地組中移除
4756	將成員添加到啟用安全的通用組中
4757	將成員從啟用安全的通用組中移除
4719	系統審計策略修改
```
### Winndows 日誌分析:事件檢視器(Event Viewer)

```
如何查看Windows 7系统事件日志
https://jingyan.baidu.com/article/86112f13793929273797878a.html

如何查看Window 8.1/10系统事件日志
http://esupport.trendmicro.com/solution/zh-TW/1114512.aspx

1.打開 本機
-> 按右上角的 管理

Event viewer command line使用指令:eventvwr

```
### Winndows 日誌分析:Windows 事件命令列公用程式 wevtutil.exe
```
可讓您抓取關於事件記錄檔與發行者的相關資訊、安裝與解除安裝事件資訊清單、
執行查詢，以及匯出、封存和清除記錄檔。

使用方式:

您可使用簡短 (例如，ep /uni) 或完整 (例如，enum-publishers /unicode)
版的命令與選項名稱。命令、選項及選項值不區分大小寫。

變數以全大寫表示。

wevtutil COMMAND [ARGUMENT [ARGUMENT] ...] [/OPTION:VALUE [/OPTION:VALUE] ...]

命令:

el | enum-logs          列出記錄檔名稱。
gl | get-log            取得記錄檔設定資訊。
sl | set-log            修改記錄檔設定。
ep | enum-publishers    列出事件發行者。
gp | get-publisher      取得發行者設定資訊。
im | install-manifest   從資訊清單安裝事件發行者與記錄檔。
um | uninstall-manifest 從資訊清單解除安裝事件發行者與記錄檔。
qe | query-events       從記錄檔查詢事件。
gli | get-log-info      取得記錄檔狀態資訊。
epl | export-log        匯出記錄檔。
al | archive-log        封存匯出的記錄檔。
cl | clear-log          清除記錄檔。

命令選項:

/{r | remote}:VALUE
如果指定，會在遠端電腦上執行命令。VALUE 是遠端電腦名稱。選項 /im 與 /um
不支援遠端作業。

/{u | username}:VALUE
指定其他登入遠端電腦的使用者。VALUE 是使用者名稱，格式為網域\使用者或使用者。
必須指定 /r 選項才適用。

/{p | password}:VALUE
指定之使用者的密碼。如未指定，或如果 VALUE 是 "*"，系統將提示使用者輸入密碼。
必須指定 /u 選項才適用。

/{a | authentication}:[Default|Negotiate|Kerberos|NTLM]
連線至遠端電腦的驗證類型。預設值為 Negotiate。

/{uni | unicode}:[true|false]
以 Unicode 顯示輸出。如為 true，會以 Unicode 輸出。

若要深入了解特定命令，請輸入:

wevtutil COMMAND /?
```
### Winndows 日誌分析:使用powershell
```
Windows 中提供了 2 個分析事件日誌的 PowerShell cmdlet：
一個是Get-WinEvent，超級強大，但使用起來比較麻煩；
另一個是Get-EventLog，使得起來相當簡單，可以即時篩選。
https://www.sysgeek.cn/use-powershell-parse-shutdown-events/
http://blog.51cto.com/gaowenlong/1189463
https://www.dayexie.com/detail45083.html
```
```
如何使用PowerShell查看Windows Update更新歷史記錄: wmic qfe list
https://www.sysgeek.cn/list-windows-update-history-powershell/

如何使用PowerShell查看Windows 10 Build升級歷史記錄
https://www.sysgeek.cn/list-windows-10-build-upgrades-history/

如何在Windows 10上徹底永久禁用Windows Defender防毒程式
https://www.sysgeek.cn/windows-10-disable-windows-defender/

如何在Windows 10中使用PowerShell格式化磁片
https://www.sysgeek.cn/windows-10-format-hard-drive-powershell/
```
```
Windows作業系統中的事件檢視器，有三個較為重要之日誌檔，請問此三個日誌檔分別為下列何者？
(A)	連結性日誌、系統日誌、應用程式日誌
(B)	安全性日誌、網路日誌、應用程式日誌
(C)	安全性日誌、系統日誌、本機防毒日誌
(D)	安全性日誌、系統日誌、應用程式日誌
```
### Winndows 日誌分析:Log parser(2005很舊)
```
Log parser is a powerful, versatile tool that provides universal query access to text-based data such as 
log files, XML files and CSV files, as well as key data sources on the Windows® operating system 
such as the Event Log, the Registry, the file system, and Active Directory

https://www.microsoft.com/en-us/download/details.aspx?id=24659
```

### Winndows 日誌分析:Log Parser Lizard GUI (最佳視覺化 LP 工具)
```
https://blog.miniasp.com/post/2012/03/26/Useful-tool-Log-Parser-Lizard-GUI.aspx
```

### Winndows 日誌分析:Event Log Explorer 
```
https://eventlogxp.com/essentials/windowseventlog.html#EventLogFiles
https://medium.com/elkplus/event-log-explorer-%E4%BA%8B%E4%BB%B6%E5%88%86%E6%9E%90%E5%99%A8-704468e12231

Home license
FREE personal license is available for HOME NON-COMMERCIAL use. 
It doesn't allow you to connect more then 3 computers. 
Free license never expires, but you may need to renew the license when you upgrade Event Log Explorer.
```

### 自行架設LogAnalyzer日誌管理伺服器
```

```

```
http://lic.nkuht.edu.tw/files/archive/1328_5126a7e4.pdf

Windows Events轉Syslog
 工具：eventlog-to-syslog(evtsys)
 下載網址：http://code.google.com/p/eventlog-to-syslog/

```

Python取證技術(3): Windows 事件日誌分析 原文網址：https://itw01.com/V49XGEV.html

實戰：淺談安全日誌分析系統建設 原文網址：https://itw01.com/FGTMBEM.html

Graylog | Enterprise Log Management   https://www.graylog.org/

https://itw01.com/FW2GOE4.html



# Linux

### Linux根目錄
```
原文網址：https://read01.com/mAKQOg.html

/bin 二進位可執行命令[執行檔]
/ bin 目錄包含了引導啟動所需的命令或普通用戶可能用的命令(可能在引導啟動後)。
這些命令都是二進位文件的可執行程序( bin是binary - -二進位的簡稱)，多是系統中重要的系統文件。

/sbin 系統管理命令，這裡存放的是系統管理員使用的管理程序
/sbin目錄類似/bin ，也用於存儲二進位文件。
因為其中的大部分文件多是系統管理員使用的基本的系統程序，
所以雖然普通用戶必要且允許時可以使用，但一般不給普通用戶使用。

/dev 設備特殊文件

/etc 系統管理和配置文件
etc目錄存放著各種系統配置文件，其中包括了用戶信息文件/etc/passwd，系統初始化文件/etc/rc等。
linux正是因為這些文件才得以正常地運行

/etc/rc.d 啟動的配置文件和腳本

/home 使用者主目錄的幾點
/root 系統管理員的主目錄

/lib 標準程序設計庫，又叫動態連結共享庫

/tmp 公用的臨時文件儲存點

/mnt 系統提供這個目錄是讓用戶臨時掛載其他的文件系統

/lost++found 這個目錄平時是空的，系統非正常關機而留下「無家可歸」的文件就在這裡

/proc 虛擬的目錄，是系統內存的映射，可直接訪問這個目錄來獲取系統的信息
/proc 文件系統是一個偽的文件系統，就是說它是一個實際上不存在的目錄，因而這是一個非常特殊的目錄。
它並不存在於某個磁碟上，而是由核心在內存中產生。
這個目錄用於提供關於系統的信息。

下面說明一些最重要的文件和目錄(/proc 文件系統在proc man頁中有更詳細的說明)。
1. /proc/x==>關於進程x的信息目錄，這一x是這一進程的標識號。每個進程在/proc 下有一個名為自己進程號的目錄。
2. /proc/cpuinfo==>存放處理器(cpu)的信息，如cpu的類型、製造商、型號和性能等。
3. /proc/devices==>當前運行的核心配置的設備驅動的列表。
4. /proc/dma==>顯示當前使用的d m a通道。
5. /proc/filesystems==>核心配置的文件系統信息。
6. /proc/interrupts==>顯示被占用的中斷信息和占用者的信息，以及被占用的數量。
7. /proc/ioports==>當前使用的i / o埠。
8. /proc/kcore==>系統物理內存映像。與物理內存大小完全一樣，然而實際上沒有占用這麼多內存；
                 它僅僅是在程序訪問它時才被創建。(注意：除非你把它拷貝到什麼地方，否則/proc 下沒有任何東西占用任何磁碟空間。)
9. /proc/kmsg==>核心輸出的消息。也會被送到syslog。
10. /proc/ksyms==>核心符號表。
11. /proc/loadavg==>系統「平均負載」； 3個沒有意義的指示器指出系統當前的工作量。
12. /proc/meminfo==>各種存儲器使用信息，包括物理內存和交換分區(swap)。
13. /proc/modules==>存放當前加載了哪些核心模塊信息。
14. /proc/net==>網絡協議狀態信息。
15. /proc/self==>存放到查看/proc 的程序的進程目錄的符號連接。當2個進程查看/proc 時，這將會是不同的連接。這主要便於程序得到它自己的進程目錄。
16. /proc/stat==>系統的不同狀態，例如，系統啟動後頁面發生錯誤的次數。
17. /proc/uptime==>系統啟動的時間長度。
18. /proc/version==>核心版本。

/var 文件系統
/var 包含系統一般運行時要改變的數據。
通常這些數據所在的目錄的大小是要經常變化或擴充的。
原來/var目錄中有些內容是在/usr中的，但為了保持/ usr目錄的相對穩定，就把那些需要經常改變的目錄放到/var中了。
每個系統是特定的，即不通過網絡與其他計算機共享。

/var/log
各種程序的日誌(log)文件，尤其是login (/var/log/wtmp log紀錄所有到系統的登錄和注銷) 
和syslog (/var/log/messages 紀錄存儲所有核心和系統程序信息)。
/var/log 里的文件經常不確定地增長，應該定期清除

/usr 最龐大的目錄，要用到的應用程式和文件幾乎都在這個目錄。
其中包括：
/usr/x11r6 存放x window的目錄
/usr/bin 眾多的應用程式
/usr/sbin 超級用戶的一些管理程序
/usr/doc Linux文檔
/usr/include Linux下開發和編譯應用程式所需要的頭文件
/usr/lib 常用的動態連結庫和軟體包的配置文件
/usr/man 幫助文檔
/usr/src 原始碼，Linux內核的原始碼就放在/usr/src/linux里
/usr/local/bin 本地增加的命令
/usr/local/lib 本地添加的庫根文件系統

通常情況下，根文件系統所占空間一般應該比較小，因為其中的絕大部分文件都不需要經常改動，而且包括嚴格的文件和一個小的不經常改變的文件系統不容易損壞。
除了可能的一個叫/vmlinuz標準的系統引導映像之外，根目錄一般不含任何文件。所有其他文件在根文件系統的子目錄中。
```
### /var/log
```
/var/log/messages — 包括整體系統信息，其中也包含系統啟動期間的日誌。此外，mail，cron，daemon，kern和auth等內容也記錄在var/log/messages日誌中。
/var/log/dmesg — 包含內核緩衝信息（kernel ring buffer）。在系統啟動時，會在螢幕上顯示許多與硬體有關的信息。可以用dmesg查看它們。
/var/log/auth.log — 包含系統授權信息，包括用戶登錄和使用的權限機制等。
/var/log/boot.log — 包含系統啟動時的日誌。
/var/log/daemon.log — 包含各種系統後台守護進程日誌信息。
/var/log/dpkg.log – 包括安裝或dpkg命令清除軟體包的日誌。
/var/log/kern.log – 包含內核產生的日誌，有助於在定製內核時解決問題。
/var/log/lastlog — 記錄所有用戶的最近信息。這不是一個ASCII文件，因此需要用lastlog命令查看內容。
/var/log/maillog /var/log/mail.log — 包含來著系統運行電子郵件伺服器的日誌信息。例如，sendmail日誌信息就全部送到這個文件中。
/var/log/user.log — 記錄所有等級用戶信息的日誌。
/var/log/Xorg.x.log — 來自X的日誌信息。
/var/log/alternatives.log – 更新替代信息都記錄在這個文件中。
/var/log/btmp – 記錄所有失敗登錄信息。使用last命令可以查看btmp文件。例如，」last -f /var/log/btmp | more「。
/var/log/cups — 涉及所有列印信息的日誌。
/var/log/anaconda.log — 在安裝Linux時，所有安裝信息都儲存在這個文件中。
/var/log/yum.log — 包含使用yum安裝的軟體包信息。
/var/log/cron — 每當cron進程開始一個工作時，就會將相關信息記錄在這個文件中。
/var/log/secure — 包含驗證和授權方面信息。例如，sshd會將所有信息記錄（其中包括失敗登錄）在這裡。
/var/log/wtmp或/var/log/utmp — 包含登錄信息。使用wtmp可以找出誰正在登陸進入系統，誰使用命令顯示這個文件或信息等。
/var/log/faillog – 包含用戶登錄失敗信息。此外，錯誤登錄命令也會記錄在本文件中。

 
除了上述Log文件以外， /var/log還基於系統的具體應用包含以下一些子目錄：
/var/log/httpd/或/var/log/apache2 — 包含伺服器access_log和error_log信息。
/var/log/lighttpd/ — 包含light HTTPD的access_log和error_log。
/var/log/mail/ – 這個子目錄包含郵件伺服器的額外日誌。
/var/log/prelink/ — 包含.so文件被prelink修改的信息。
/var/log/audit/ — 包含被 Linux audit daemon儲存的信息。
/var/log/samba/ – 包含由samba存儲的信息。
/var/log/sa/ — 包含每日由sysstat軟體包收集的sar文件。
/var/log/sssd/ – 用於守護進程安全服務。
除了手動存檔和清除這些日誌文件以外，還可以使用logrotate在文件達到一定大小後自動刪除。可以嘗試用vi，tail，grep和less等命令查看這些日誌文件。
```
### Linux系統日誌
```
原文網址：https://read01.com/QA8E4E.html
在Linux系統日誌中，有三類主要的日誌子系統:
◆連接時間(connection)日誌: 由多個程序執行，把記錄寫入到/var/log/wtmp和/var/run/utmp，
                 login等程序會更新wtmp和utmp文件，使系統管理員能夠跟蹤誰在何時登錄到系統。
◆進程(Process)統計: 由系統內核執行，當一個進程終止時，為每個進程往進程統計文件（pacct或acct）中寫一個記錄。
           進程統計的目的是為系統中的基本服務提供命令使用統計。
◆錯誤(error)日誌: 由syslogd（8）守護程序執行，各種系統守護進程、用戶程序和內核通過syslogd（3）守護程序向文件/var/log/messages報告值得注意的事件。
          另外有許多Unix程序創建日誌。像HTTP和FTP這樣提供網絡服務的伺服器也保持詳細的Linux系統日誌。


https://read01.com/NyEzaa.html#.W6VLGHszaUk
在Linux中,系統日誌就是記錄系統歷史信息的日誌,
一般有錯誤日誌,二進位日誌,事務日誌,中繼日誌,一般日誌,除了事務日誌以外,其他幾乎都是歷史日誌.

日誌又根據其嚴重程度分為8個級別
一)debug:調試級別
二)info:正常輸出信息
三)notic:注意
四)waring:警告
五)error:錯誤
六)crit:比error嚴重了
七)alert:很嚴重了
八)emerg,panic:不用看了,系統已經掛了


2-5.日誌記錄信息格式
2-6.syslog和rsyslog
2-7.配置日誌信息
```
### Linux /Var/log 日誌文件
```
日誌式文件系統(journalling filesystems)

https://read01.com/Q3MOOO.html
https://read01.com/mEnD3K.html#.W6VJW3szaUk

```

### logstash快速入門
```
https://read01.com/3a8Djk.html
Logstash是一個接收，處理，轉發日誌的工具。支持系統日誌，webserver日誌，錯誤日誌，應用日誌，
總之包括所有可以拋出來的日誌類型。

依賴條件：JAVA
Logstash運行僅僅依賴java運行環境(jre)
```

### 系統被黑不要慌，十個步驟來排查
```
https://read01.com/E8456z4.html
安全人員在日常工作中通常要手工排查 Linux 伺服器的安全性，

對於中馬的伺服器，我將其歸納為4個階段：
木馬如何傳播到伺服器上 （Eg：暴力破解系統用戶）；
木馬的目的是什麼（Eg：挖礦、DDOS 攻擊）；
木馬怎樣清除痕跡（Eg：刪除日誌和歷史命令）；
木馬如何保持連接（Eg：通過啟動項和定時任務）。

本文將從檢查用戶、日誌、文件等十個步驟，通過相關具體命令來講解如何手工排查 Linux 伺服器的安全性。

Linux 常用命令
du -sh * ==>查看當前文件夾大小

head -n 100 1.log ==>查看一個大文件的前100行

grep -ri "nameseve" --include="*.php" / ==>查看文件字符串

free -m==>查看系統內存大小

cp 原始文件 目的文件;
cp -r /root/* 目的目錄;==>複製文件及文件夾
tar -cvf a.tar 原始文件;==>壓縮文件
tar -xvf a.tar;
tar -xvfz a.tar.gz;
unrar e a.rar;
unzip a.zip==>解壓文件

lsof -p pid==>查看進程
lsof -c 進程名==>查看進程所打開的埠及文件

scp root@x.x.x.x:原始文件夾 目的文件夾;==>在當前伺服器，將遠程伺服器文件拷貝到當前
scp 原始文件 root@x.x.x.x:目的文件==>把當前文件傳到遠程伺服器上

tcpdump -i eth0 -w eth0.cap -c 100000==>本地抓包

kill==>殺死進程
chmod==>改變文件權限
Sed==>本身是一個管道命令，主要是以行為單位進行處理，可以將數據行進行替換、刪除、新增、選取等特定工作，刪除某行
Uniq==>用於報告或忽略文件中的重複行，一般與sort命令結合使用。
Sort==>將文件進行排序，並將排序結果標準輸出。


Linux伺服器應急常用命令及思路

1.檢查用戶及登入情況
last
last -x reboot==>查看重啟的記錄
last -x shutdown==>查看關機的記錄
last -d==>查看登陸的記錄

lastb==>這個命令用於查看登錄失敗的情況，本質就是將 /var/log/btmp 文件格式化輸出。

相關參數：
lastb name（root）==>查看root用戶登陸失敗記錄
lastb -10（-n）==>查看最近10條登陸失敗記錄

lastlog==>這個命令用於查看用戶上一次的登錄情況，本質就是將 /var/log/lastlog 文件格式化輸出。
相關參數：
lastlog==>所有用戶上一次登陸記錄
lastlog -u username（root） root==>用戶上一次登陸記錄
lastlog –help==>命令幫助信息

Linux不同的用戶有不同的操作權限，但是所有用戶都會在 /etc/passwd、/etc/shadow、/etc/group 文件中記錄。

less /etc/passwd==>查看是否有新增用戶
grep :0 /etc/passwd==>查看是否有特權用戶（root權限用戶）
ls -l /etc/passwd==>查看passwd最後修改時間
stat useradd==>查看該命令的時間變化，來判斷是否有新增用戶
cat /etc/passwd | grep -E "/bin/bash$"==>查看能夠登錄的帳號



2.查看日誌信息

/var/log/message==>包括整體系統信息
/var/log/auth.log==>包含系統授權信息，包括用戶登錄和使用的權限機制等
/var/log/userlog==>記錄所有等級用戶信息的日誌
/var/log/cron==>記錄crontab命令是否被正確的執行
/var/log/lastlog==>記錄登錄的用戶，可以使用命令lastlog查看
/var/log/secure==>記錄大多數應用輸入的帳號與密碼，登錄成功與否
/var/log/wtmp==>記錄登錄系統成功的帳戶信息，等同於命令last
/var/log/faillog==>記錄登錄系統不成功的帳號信息，一般會被黑客刪除

檢查日誌時一定要查看下 root 用戶是否有被暴力破解的情況：

grep -ri "Fail" /var/log/secure*==>查看失敗登入情況
grep -ri "accept" /var/log/secure*==>查看成功登入情況


3.查看歷史命令

cat ./bash_history

history n

通過用戶的歷史操作命令來排查主機的安全性，可以關注以下四個方面：
wget 遠程某主機（域名&IP）的遠控文件；
嘗試連接內網某主機（ssh scp），便於分析攻擊者意圖;
打包某敏感數據或代碼，tar zip 類命令
對系統進行配置，包括命令修改、遠控木馬類，可找到攻擊者關聯信息…

4.查看進程(process)

一般被入侵的伺服器都會運行一些惡意程序，或是挖礦程序，或者 DDOS 程序等。
如果程序在運行中，那麼通過查看進程可以發現一些信息。

*查看普通進程

ps -aux ==> 查看進程（注意uid為0的用戶）
top==>提供了實時的對系統處理器的狀態監視 （尤其是一些挖礦程序會消耗大量資源的）


如果進程中沒有發現異常，那麼可以看看有沒有開啟某些隱藏進程。

*查看隱藏進程

ps -ef | awk '{print}' | sort -n | uniq >1

ls /proc | sort -n |uniq >2

diff 1 2

通過以上3個步驟可以檢查是否開啟了某些隱藏進程。



5.查看文件
攻擊者入侵成功後，會將木馬上傳到一個合適的文件夾下，要求具有可寫可執行的權限，/tmp / 文件夾通常是合適的選擇，所以可以重點看一下。
被入侵的網站，通常肯定有文件被改動，那麼可以通過比較文件創建時間、完整性、文件路徑等方式查看文件是否被改動。

可以重點查看下相關配置文件，比如 /etc/init.conf。

find / -uid 0 -print ==>查找特權用戶文件
find / -size +10000k -print==> 查找大於10000k的文件
find / -name "…" -print==>查找用戶名為…的文件
md5sum -b filename==>查看文件的md5值
whereis 文件名==>查看文件路徑
stat 文件名==>查看文件時間修改等詳細信息
du -sh 文件名==>查看文件大小
find / -atime 2 > /tmp/1.txt==>查看最近兩天訪問的文件
find / -ctime 2 > /tmp/1.txt==>查看最近兩天狀態改變的文件(比如文件的權限 所屬組信息等)
find / -mtime 2 > /tmp/1.txt==>查看最近兩天內容改變的文件

註：find -mtine 2 表示兩天以內，find +mtime 2 表示兩天以前。


6.查看計劃任務
當我們嘗試 kill 惡意程序時，往往會遇到被 kill 掉的程序自動啟動的問題，那麼就要檢查下計劃任務（cron）了。

查看root用戶的計劃任務==> crontab -u root -l
                         cat /etc/crontab

查看cron文件是否變化的詳細信息
ls /var/spool/cron/
ls -l /etc/cron.*

7.查看啟動項
系統開機後，此目錄下的文件會被啟動
ls /etc/rc.dl
ls –alt /etc/init.d/

8.檢查網絡
檢查網絡的目的，是查看黑客是否通過篡改網卡類型，進行流量嗅探等操作。
ip link | grep PROMISC==>正常網卡不應該存在promisc，如果存在可能有sniffer
netstat -nap==>查看不正常埠
arp -a==>查看arp記錄是否正常
ifconfig -a==>查看網卡設置

9.檢查常用命令
有時攻擊者會替換掉 ps，netstat 等命令，需要查看下相關命令的大小以及修改的時間。
可以使用stat進行創建修改時間、訪問時間的詳細查看，若修改時間距離事件日期接近，有線性關聯，說明可能被篡改或者其他。

10.查看系統路徑==>echo $PATH-->分析有無敏感可疑信息
```
# Apache伺服器日誌分析

### apache日誌
```
http://codestandup.blogspot.com/2010/12/apache.html

apache官網的手冊:
http://httpd.apache .org/docs/2.2/logs.html
https://httpd.apache.org/docs/2.4/logs.html
```
```
如果apache的安裝時採用默認的配置,那麼在/logs目錄下就會生成兩個文件,分別是access_log和error_log
1.access_log
access_log為訪問日誌,記錄所有對apache服務器進行請求的訪問,它的位置和內容由CustomLog指令控制,LogFormat指令可以用來簡化該日誌的內容和格式
2.error_log
error_log為錯誤日誌,記錄下任何錯誤的處理請求,它的位置和內容由ErrorLog指令控制,通常服務器出現什麼錯誤,首先對它進行查閱,是一個最重要的日誌文件
```

##### access_log日誌分析
```
服務器配置: CustomLog "| /usr/sbin/rotatelogs /var/log/apache2/%Y_%m_%d_other_vhosts_access.log 86400 480" vhost_combined

-rw-r--r-- 1 root root 22310750 12-05 23:59 2010_12_05_other_vhosts_access.log
-rw-r--r-- 1 root root 26873180 12-06 23:59 2010_12_06_other_vhosts_access.log
-rw-r--r-- 1 root root 26810003 12-07 23:59 2010_12_07_other_vhosts_access.log
-rw-r--r-- 1 root root 24530219 12-08 23:59 2010_12_08_other_vhosts_access.log
-rw-r--r-- 1 root root 24536681 12-09 23:59 2010_12_09_other_vhosts_access.log
-rw-r--r-- 1 root root 14003409 12-10 14:57 2010_12_10_other_vhosts_access.log


通過CustomLog指令,每天一天生成一個獨立的日誌文件,同時也寫了定時器將一周前的日誌文件全部清除,
這樣可以顯得更清晰,既可以分離每一天的日誌又可以清除一定時間以前的日誌通過制,LogFormat定義日誌的記錄格式

LogFormat "%h %l %u %t \"%r\" %>s %b \"%{Referer}i\" \"%{User-Agent}i\"" combined
LogFormat "%{X-Forwarded-For}i %l %u %t \"%r\" %>s %b \"%{Referer}i\" \"%{User-Agent}i\"" combinedproxy
LogFormat "%h %l %u %t \"%r\" %>s %b" common
LogFormat "%{Referer}i -> %U" referer
LogFormat "%{User-agent}i" agent

隨意的tail一個access_log文件,下面是一條經典的訪問記錄

218.19.140.242 - - [10/Dec/2010:09:31:17 +0800] 
"GET /query/trendxml/district/todayreturn/month/2009-12-14/2010-12-09/haizhu_tianhe.xml HTTP/ 1.1" 200 1933 "-" "Mozilla/5.0 (Windows; U; Windows NT 5.1; zh-CN; rv:1.9.2.8) Gecko/20100722 Firefox/3.6.8 (.NET CLR 3.5.30729)"

一共是有9項

```


##### error_log錯誤日誌分析
```
tail error_log=====隨意摘取一個記錄

[Fri Dec 10 15:03:59 2010] [error] [client 218.19.140.242] File does not exist: /home/htmlfile/tradedata/favicon.ico

```
### linux安全-系統記帳

```
https://read01.com/08oLRg.html#.W6VWo3szaUk
系統記帳主要非為兩類 連接記帳和進程記帳:

主要涉及到的命令：last、lastlog、w、who、ac、sa、lastcomm

```
##### 攻擊檢測和防範方法之日誌分析
```
https://read01.com/RRkgn0.html#.W6VWgHszaUk
```
##### Apache log檔備份與管理
```
http://blog.xuite.net/kind671029/twblog/165434597-Apache+-+log%E6%AA%94%E5%82%99%E4%BB%BD%E8%88%87%E7%AE%A1%E7%90%86
```

### apache日誌分析
```
http://codestandup.blogspot.com/2010/12/apache.html
了解日誌的各種定義後,這里分享一下從網上淘來的一些對日誌分析的腳本

1.查看apache的進程數
ps -aux | grep httpd | wc -l

2.分析日誌查看當天的ip連接數
cat default-access_log | grep "10/Dec/2010" | awk '{print $2}' | sort | uniq -c | sort -nr

3.查看指定的ip在當天究竟訪問了什麼url
cat default-access_log | grep "10/Dec/2010" | grep "218.19.140.242" | awk '{print $7}' | sort | uniq -c | sort -nr

4.查看當天訪問排行前10的url
cat default-access_log | grep "10/Dec/2010" | awk '{print $7}' | sort | uniq -c | sort -nr | head -n 10

5.看到指定的ip究竟乾了什麼
cat default-access_log | grep 218.19.140.242 | awk '{print $1"\t"$8}' | sort | uniq -c | sort -nr | less

6.查看訪問次數最多的幾個分鐘(找到熱點)
awk '{print $4}' default-access_log |cut -c 14-18|sort|uniq -c|sort -nr|head

```
### apache日誌分析工具:使用awstats自動分析日誌
```
https://awstats.sourceforge.io/
AWStats — 多功能記錄檔分析工具 https://www.openfoundry.org/tw/tech-column/8277-awstats-
http://blog.faq-book.com/?p=5415
在 Windows 主機設定 AWStats 流量分析軟體  
https://blog.miniasp.com/post/2007/11/30/How-to-install-AWStats-traffic-statistics-software-in-Windows.aspx


AWStats LOG 檔分析系統安裝設定
https://blog.xuite.net/beavisliu/blog/15008889-AWStats+LOG+檔分析系統安裝設定

How to use AWSTATS  https://www.youtube.com/watch?v=EcK52iYDTvA

```
```
awstats是一個基於perl的web日誌分析工具,
功能很強大也支持IIS等服務器
下載地址 http://awstats.sourceforge.net
安裝配置見 <安裝配置整理之 awstats>

AWStats is a free powerful and featureful tool that generates advanced web, streaming, ftp or mail server statistics, graphically. 

This log analyzer works as a CGI or from command line and shows you all possible information your log contains, 
in few graphical web pages. 
It uses a partial information file to be able to process large log files, often and quickly. 
It can analyze log files from all major server tools like Apache log files (NCSA combined/XLF/ELF log format or common/CLF log format), WebStar, IIS (W3C log format) and a lot of other web, proxy, wap, streaming servers, mail servers and some ftp servers.
```

```
AWStats — 多功能記錄檔分析工具 https://www.openfoundry.org/tw/tech-column/8277-awstats-

支援跨平台作業系統：您可以在 Windows 或 Unix-Like 作業系統上輕鬆建立分析記錄檔的運作環境。
報表支援多國語言：AWStats 所產生的分析統計報表支援多國語言，使得閱讀分析報表的管理者不會因為語言而產生困擾。
支援分析多種服務記錄檔：AWStats 支援相當多的網路服務記錄檔。
網頁記錄檔：支援 Apache (combined/ common log format XLF/ ELF/ CLF)、Microsoft IIS (W3C log format)…等。
快取記錄檔：支援 Squid (common log format, CLF) …等。
串流記錄檔：支援 Darwin Streaming Server、Windows Media Server…等。
郵件記錄檔：支援 Postfix、Sendmail、Qmail、Mdaemon、www4mail…等。
FTP記錄檔：支援 ProFTPD、VSftpd…等。
詳盡的統計報表：AWStats 產生的分析報表具備非常詳盡內容。例如，週期性網路流量、來源國家、來源 IP 位址、參觀網站時間、參觀網頁、訪客作業系統、使用的瀏覽器、連結網站的來源、連結網站的關鍵字…等。

使用者透過 AWStats 可以分析網站記錄檔，或企業相關網路服務記錄檔。AWStats 提供詳細的分析統計報表，企業的網管或行銷人員得以輕鬆分析網路使用者瀏覽企業網站的流量、以及在網站的存取行為，接著以 SEO 為目標，改善網站內容及方向，進而提升企業的品牌形象，並為企業帶入龐大網路商機。以下介紹 AWStats 的主要功能與安裝技巧。

定期產生網站記錄檔

為何需要定期產生網站記錄檔？那是有原因的。目前使用最多的網路伺服器軟體 Apache，其所提供網頁服務套件會自動產生存取記錄檔，但它的預設記錄方式是持續將來訪記錄及瀏覽存取行為，寫入單一個檔案中。然而隨著網站經營時間增加或網路流量增大，這樣的記錄檔產生方式會使 Apache 記錄檔愈來愈大。單一記錄檔過大時，會增加系統讀取資料需要的時間，且因為 Apache 記錄檔預設存放路徑為 /var 掛載點，預設情況下分割空間小，掛載點分配不當的話，還可能導致系統運作出現問題。

因為以上問題，比較好的方式是設定 Apache 網頁服務定期每天產生一個記錄檔。這樣規劃使 Apache 不必長期持續寫入單一記錄檔而造成記錄檔日漸肥大，也提昇在記錄檔進行細部查詢的效率，例如某天的訪客行為，或抓取網站被駭客攻擊當日的訪客及其行為記錄。對這個問題，我們可以安裝一個小而美的 cronolog 套件，來與 Apache 網頁服務搭配，依序產生單日記錄檔。
```

```
https://dotblogs.com.tw/grayyin/2016/09/13/161658
```

# apache日誌分析工具:apache log analysis tools


### PHP 日誌記錄工具:Monolog
```
Day 22. PHP教學: 使用 monolog 來追蹤問題  
https://ithelp.ithome.com.tw/articles/10196317


http://hao.jobbole.com/monolog/


```


# 滲透技巧——Windows日誌的刪除與繞過
```
http://www.4hou.com/penetration/5998.html
```
# 
```
配置Tomcat的日誌系統
https://read01.com/mQOP7g.html#.W6VKwHszaUk

【Mac】日誌文件結構與提取分析
https://read01.com/7xgyPL.html#.W6VKj3szaUk
```
