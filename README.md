# NexusRepositoryManager
元件倉庫管理

下載網址 :
https://www.sonatype.com/products/sonatype-nexus-oss-download
OSS 版本 : 社群免費版

下載後解壓縮執行指令 : nexus.exe /run

等待一段時間後即可連線 : http://localhost:8081

下載Nuget.exe 
下載網址 : https://www.nuget.org/downloads

nuget cmd

-push 推送元件dll
nuget push *.nupkg <APIkey> -src "[nuxus](http://localhost:8081/repository/nuget-hosted)"

APIKEY 產生方式
前往並登入
http://localhost:8081 選取右上方admin -> NuGet API Key

目前尚待研究Filter怎麼預設搜尋出來
