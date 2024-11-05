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
![用例圖](https://github.com/user-attachments/assets/bcbd482c-774b-4bef-8151-2dedc9e34977)

# 實驗步驟
分析實驗任務內容，並利用UML完成類別的建模並產生對象，主要包括：

1.定義類（包括類名、屬性、操作等）

2.建模類之間的關係（包含關聯、泛化、依賴、實作等） 

3.建構完整的類圖（至少包含抽象類、組合、聚合、多重性、可見性和接口等） 

4.根據類圖，生成系統某一時刻的對象圖
# 類別圖
![類圖](https://github.com/user-attachments/assets/53ac3e6b-25e2-4c0d-ae9f-519ff2d4035d)

上圖總的來說共有六個類，其中分別是User，RegisteredUser，OrdinaryUser，LibraryManager，MailSystem， Library。

其中，MailSystem是接口。User類關聯RegisterUser和OrdinaryReader類，同時這兩個類和User之間也存在聚集關係，LibraryManager和OrdinaryReader都繼承RegisterUser類。

Library類依賴於RegisterUser和OrdinaryReader類;LibraryManager還實作了MailSystem接口，又和Library之間存在著組成關係，各個類都設定了一定的可見性，有的定義了一些操作方法。
# 對象圖
![對象圖](https://github.com/user-attachments/assets/1900207c-9c51-4f6b-8f4f-760e74bdd6fb)

從上圖可以看出有三個對象
