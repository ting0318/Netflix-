##  Netflix 用戶觀看行為與訂閱方案交叉分析

## 專案概述
本專案旨在「透過數據解讀影音串流用戶的行為」。
使用 Kaggle 數據，獨立操刀從 SQL 數據萃取加工到 Python 視覺化 與 Tableau 儀表板分析，深入探究 1,000+ 筆 Netflix 用戶的消費特徵。

##  技術實作
* **SQL (MySQL)**：使用聚合查詢（`GROUP BY`），將原始資料萃取為「影片種類 × 訂閱方案」作為指標。
* **Python (Seaborn/Pandas)**：進行數據清洗，繪製分組長條圖，獨立解決畫布尺寸、中文字型支援與最新語法調校。
* **Tableau (BI 工具)**：設計互動式儀表板，提供決策者動態探索數據的良好體驗。

##  Tableau 商業儀表板成果
滑鼠懸停即可即時查看精確的平均觀看時數，一眼即可看出各階層會員在科幻片高達將近 100 小時的觀看異常斷層。



## 商業洞察與策略建議
鎖定Basic客戶，未來在推廣方案時，祭出專屬的升級誘因（例如:升級Permium或Standard方案，與家人共享高清雙螢幕追劇) 作為推廣。
<img width="1157" height="772" alt="image" src="https://github.com/user-attachments/assets/f09659d1-48ca-4dfc-820a-d487d610913a" />
