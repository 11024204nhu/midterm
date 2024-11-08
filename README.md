# 軟體工程 期中報告
11024204 洪筠婷
# 實驗三、UML靜態建模之類的分析與設計
# 實驗目的
透過UML建模過程掌握類別的分析與設計方法。
# 實驗環境
starUML
# 實驗任務
針對「迷你圖書管理系統」的使用案例圖，進行分析，完成類別建模。
# 用例圖
![用例圖](https://github.com/11024204nhu/midterm/blob/main/%E7%94%A8%E4%BE%8B%E5%9C%96.jpg))

# 實驗步驟
分析實驗任務內容，並利用UML完成類別的建模並產生對象，主要包括：

1.定義類（包括類名、屬性、操作等）

2.建模類之間的關係（包含關聯、泛化、依賴、實作等） 

3.建構完整的類圖（至少包含抽象類、組合、聚合、多重性、可見性和接口等） 

4.根據類圖，生成系統某一時刻的對象圖
# 類別圖
![類圖](https://github.com/11024204nhu/midterm/blob/main/%E9%A1%9E%E5%9C%96.jpg))

上圖總的來說共有六個類，其中分別是User，RegisteredUser，OrdinaryUser，LibraryManager，MailSystem， Library。

其中，MailSystem是接口。User類關聯RegisterUser和OrdinaryReader類，同時這兩個類和User之間也存在聚集關係，LibraryManager和OrdinaryReader都繼承RegisterUser類。

Library類依賴於RegisterUser和OrdinaryReader類;LibraryManager還實作了MailSystem接口，又和Library之間存在著組成關係，各個類都設定了一定的可見性，有的定義了一些操作方法。
# 對象圖
![對象圖](https://github.com/11024204nhu/midterm/blob/main/%E5%B0%8D%E8%B1%A1%E5%9C%96.jpg)
從上圖可以看出有三個對象
