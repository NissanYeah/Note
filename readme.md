
## Notes

My notes about software development 
我的軟體開發筆記（持續更新）

## JavaScript

- [JavaScript Foundation](JavaScript/Basic.md)
- [JavaScript Prototype](JavaScript/prototype.md)
- [Object destructuring, Array destructuring, Spread Operator, Mapping, Arrow Functiom, default parameters,rest parameters  ](JavaScript/praticalSkills.md)
- [ForEach, Map, Filter, Find, join, for in, for of  ](JavaScript/praticalFunction.md)
- [Enumeration: Objct.keys(), Object.getOwnPropertyNames(), Object.propertyIsEnumerable(),for in](JavaScript/enumerationProperty.md)
- [error handling: Try catch](JavaScript/errorHandling.md)
- [Constructor：function Constructor, Class Constructor, Object](JavaScript/objectConstructor.md)
- [Promise](JavaScript/promise.md)
- [RegularExpression](JavaScript/regularExpression.md)
- [Expression and Statement](JavaScript/expression.md)
- [What is `this` ? ](JavaScript/this.md)
- [Question](JavaScript/Question.md)
- [實用的JS算法](JavaScript/實用.md)

## Programming Foundation

- [Linux: Command line](Basic/commandline.md)
- [Shell Script](Basic/ShellScript.md)
- [Git Intro](Basic/git.md)
- [installation](Basic/install.md)
- [Browser](Basic/browser.md)
- [Web Secrity](Basic/webSecrity.md)

### Database & MySQL : 資料庫管理

- [ER模型的繪製技巧](資料庫管理/ER_model.md)：介紹如何繪製ER模型，還有認識什麼是Entiry、Relationship、Attribute
- [基本SQL語法](資料庫管理/mysql.md)：介紹mysql的基本操作
- [實用技巧](資料庫管理/實用語法.md)：複製schema / 插入primary key重複的資料 / 字串轉時間 / 根據時間列出資料
- [資料庫機制](資料庫管理/資料庫機制.md)：資料庫架構、機制（鎖定機制，鎖定機制）
- [資料庫倉儲](資料庫管理/資料倉儲.md)
- [交易（Transaction）& ACID、例程（Routines）、自動觸發（Trigger）](資料庫管理/交易.md)：如何保證交易（Transaction）執行不被中斷？什麼是ACID？怎麼樣可以做自訂的SQL組合技？怎麼樣自動觸發SQL指令？
- [巨量資料與數據分析](資料庫管理/巨量資料與數據分析.md)
- [實用SQL練習](資料庫管理/mysqlQA.md)：一些練習題目
- [Greater China catering market entry strategy（大中華地區市場進入策略數據分析）](資料庫管理/作業/菜系分析.md)：Analyzed Greater China all restaurants data crawling from mainstream apps with SQL and delivered solutions to market entry.
- [RDBMS資料庫淺談](資料庫管理/資料庫淺談.md)


### data analysis：數據分析

- [如何安裝Juypter?(資料分析的好工具)](Python/Juypter.md)
- [如何處理MySQL無法正常匯入CSV檔案的問題？](資料分析/如何處理mySQL無法import的問題.md)
- [如何利用Python和jieba進行中文斷詞?](資料分析/如何進行斷詞.md)
- [如何利用Python和jieba關鍵字萃取與關鍵字共現熱圖？](資料分析/關鍵字萃取.md)：jieba斷詞/關鍵字出現頻率統計/TF-IDF關鍵字萃取/關鍵字共現熱圖（輸出共現矩陣matrix、熱圖套件）
- [如何用Python讀取與寫入csv檔案？](Python/如何讀取與寫入csv檔案.md):readlines(),read(),csv.reader(),csv.writer()
- [如何用Python把資料寫入MySQL？](Python/如何用Python把資料寫入MySQL.md)
- [如何用Python把csv轉換為多對一字典？](Python/如何把csv轉換為多對一字典.md)
- [文字探勘概覽](資料分析/文字探勘.md)
- [Python Numpy](Python/numpy.md)
- [Python Panda](Python/panda.md)
- [Python matplotlib](Python/matplotlib.md)

### Linux : 臺大Linux系統訓練班（筆記）

- [基本介紹](作業系統/linux基本介紹.md)
- [實用指令](作業系統/linux實用指令.md)：如何列出所有檔案？如何寫shell script？如何檢查網路連線？
- [實用技巧](作業系統/實用技巧.md)：如何找檔案？如何下載檔案？
- [帳號管理與權限管理](作業系統/權限管理.md):chmod
- [程序與程式](作業系統/程序與程式.md):prgrame和process
- [套件安裝]](作業系統/套件安裝.md)
- [Apache伺服器架設](作業系統/伺服器架設.md)
- [網路](作業系統/網路.md)
- [雲服務介紹](作業系統/雲服務介紹.md)
- [shellscript](作業系統/shellscript.md)
- [VM](作業系統/linux其他.md):vm 
- [找不到指令怎麼辦？](作業系統/找不到指令.md)：設定環境路徑 

### Computer network: 台大計算機網路課程（筆記）

- [基本名詞介紹](計算機網路/基本網路概論.md)：ISP、Router、Host、Packet 09/18
- [封包傳遞的方式](計算機網路/網路傳輸.md)：Circuit switching, Packet switching 09/25
- [網路架構(Network Architecture)](計算機網路/網路分層.md): 網路架構的五個層次、介紹 Application layer(HTTP), transport layer(TCP,UDP)
- [程式架構(Application Architecture)與常見的關係](計算機網路/P2P&CS.md):
Client-Server 和 P2P 架構是 host 常見的兩種互動關係
- [域名系統(DNS)](計算機網路/DNS.md): DNS是hostname 尋找到 IP 的方式
- [可靠資料傳輸(RDT)](計算機網路/RDT模型.md): rdt1.0～3.0的 State Machine？以及 Pipelining Protocols是什麼？
- 考試會設計state machine去設計ACK/NAK的內容

## Python

- [Python Foundation](Python/basic.md)
- [Python Advance](Python/advance.md)


## 實用技巧

- [如何把csv檔案轉換為多對一字典？](Python/如何把csv轉換為多對一字典.md)
- [如何寫google sheet script？](tool/googlesheet腳本.md)


## Side Project

- [Data analysis: Dcard Online Shopping Board Keyword Analysis（Dcard購物版的關鍵字分析）](資料分析/Dcard購物版的關鍵字分析.md)：Analyzed 'Dcard' (Taiwan's largest anonymous communication platform) online shopping board data for keyword analysis with SQL, Python and observe consumers' evaluation of various shopping platforms
- [Data analysis: Greater China catering market entry strategy（大中華地區餐飲市場進入策略數據分析）](資料庫管理/作業/菜系分析.md)：Analyzed Greater China all restaurants data crawling from mainstream apps with SQL and delivered solutions to market entry.


## Fronted End 

- [token ,localStorage and sessionStorage](Fronted/token.md)
- [CSS選擇器](Fronted/CSS.md)
- [命名問題收集（更新）](Fronted/Naming.md)


## Back End 

- [Database Basic](Backend/Basic_Database.md)

### Django 

- [Django Setting and Base Connection](Backend/Django_setting.md)
- [Model, Serialization and View](Backend/Django_basic.md) 

### Python Django 網站設計: 臺大資訊訓練班（筆記）

- [基本介紹](Backend/DjangoClass.md)


### Charts
- [Chart Survey: ApexCharts、ECharts、Hichart、ChartJS](Fronted/ChartSurvey.md)
- [ChartJS](Fronted/ChartJS.md)


### Vue 

- [Props and emit](Vue/prop.md)
- [RWD with Vue](Vue/Rwd.md)


### Operating system : 清大作業系統開放式課程（筆記）
- [作業系統歷史](作業系統/作業系統歷史.md)：Batch, muti-programing and time-sharing 
- [同步與阻塞(Synchronous與Blocking)](作業系統/同步與阻塞.md): 什麼是 Process 的 Synchronous v.s. Asynchronous 以及 Kernel 的 Blocking v.s. non-blocking
