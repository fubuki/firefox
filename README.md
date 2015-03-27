## Firefox 專案結構 

#### accessible
用來支援 `Microsoft Active Accessibility` 和 `Sun's ATK accessibility API for Linux`。

1. windows 的 COM 技術
2. GNOME ATK

#### browser
Firefox 的主要原始碼。

#### build
內含用來編譯 Mozilla 專案的 script，通常使用 perl 撰寫裡面也有 makefile。

#### calendar
Mozilla 自己的 calendar app 和插件的程式碼。 

#### caps
基於 C 的介面和程式碼用來管理安全性設定和憑證。


#### chrome
chrome 的 toolkit

#### config
編譯設定


#### content
處理網頁內容存放資料結構 (HTML, SVG, XML documents, elements, text nodes, etc)



#### db
sqilte 


#### docshell



#### dom


#### editor


#### embedding
[Embedding Mozilla]
[Embedding Mozilla]:https://developer.mozilla.org/en-US/docs/Gecko/Embedding_Mozilla


#### extensions
一些內建的插件，可以在編譯時決定需要哪些插件。


#### gfx
繪圖功能，圖像和文字。

#### hal
硬體抽象層，提供各個平台特有的功能。

#### image
繪圖功能


#### intl

[international projects]
[international projects]:http://www-archive.mozilla.org/projects/intl/


#### ipc
Inter-Process Communication

#### js
firefox 的 js 引擎

#### layout
繪圖

#### media
一些影音和圖像的函式庫

#### memory
跨平台的記憶體管理函式庫

#### mfbt

WeakPtr 



#### modules
1. modules/libjar
2. modules/libpref
3. modules/zlib

#### mozglue
moz - glue 膠水，看起來是跟 android 有關的程式碼。


#### netwerk
[Necko] 是一個網路函式庫提供網路通訊，看起來是不會因為平台。

[Necko]:https://developer.mozilla.org/en-US/docs/Necko

#### nsprpub
提供類似 threads, file I/O, and socket I/O 的虛擬層

[Netscape Portable Runtime]

[Netscape Portable Runtime]:https://developer.mozilla.org/en-US/docs/Mozilla/Projects/NSPR

#### other-licenses
一些非 MPL 的函式庫。

#### parser
分析 XML/HTML 的函式

#### probes


#### profile
profile manager



#### python
[mach]



[mach]:https://developer.mozilla.org/en-US/docs/Mozilla/Developer_guide/mach


#### rdf


#### security
NSS and PSM，提供加密用的功能


#### services


#### startupcache


#### storage
提供一個基於 XPCOM 的 sqlite 包裹。

#### testing
單元測試

#### toolkit


#### uriloader


#### view
跟前台視覺效果有關。

#### webapprt


#### widget


#### xpcom
類似微軟的 COM 模型。

[XPCOM]

[XPCOM]:https://developer.mozilla.org/en-US/docs/Mozilla/Tech/XPCOM

#### xpfe
XPFE (Cross Platform Front End)

#### xulrunner
[XULRunner]


[XULRunner]:https://developer.mozilla.org/en-US/docs/Mozilla/Projects/XULRunner



