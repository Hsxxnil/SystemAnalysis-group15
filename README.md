# 電商訂貨系統
### 說明
1. 電商透過拍賣平台取得消費者的訂單，將每日產品需求統整並填入此訂貨系統，且填單者填完後由另一位同事審核，確認無誤後，向上游廠商進行訂購。
2. 系統每月依據使用者回報的訂單完成狀況，自動產生報表讓使用者與上游廠商進行核對，確認無誤再進行付款。
### 目的
減少電商倉儲成本，達成及時訂購、出貨。
***
### 分工
| 職位 | 學號 | 姓名 | 任務 |
| :---: | :---: | :---: | :---: |
| **組長** | C109118201 | [邱有妤](https://github.com/Wendy30418/2022-3b/blob/main/README.md) | 研擬計畫、系統測試、撰寫計畫書 |
| 組員 | C109118211 | [林姿穎](https://github.com/abcdefuuuu/2022-3b/blob/main/README.md) | 研擬計畫、前端開發、撰寫計畫書 |
| 組員 | C109118221 | [顏采如](https://github.com/0808jessie/2022-3b/blob/main/README.md) | 研擬計畫、前端開發、撰寫計畫書 |
| 組員 | C109118215 | [李怡萱](https://github.com/bovcu13/2022-3b) | 研擬計畫、後端開發、撰寫計畫書 |
| 組員 | C109118250 | [林宜璇](https://github.com/Hsxxnil/2022-3b/blob/main/README.md) | 研擬計畫、後端開發、撰寫計畫書 |
### PERT/CPM
![pert](pert.jpg "pert")
### 甘特圖
```mermaid
gantt
    title 電商訂貨系統
    section 研擬計畫
    研擬計畫:a2, 2022-11-05, 10d
    
    section 任務分配
    任務分配:a1,2022-11-05, 1d
    
    section 前端開發
    前端開發:a3,after a2,20d
    
    section 後端開發
    後端開發:a4,after a2, 30d
    
    section 系統測試
    系統測試:a5,after a4, 5d
    
    section 撰寫計畫書
    撰寫計畫書:a6,after a5, 15d
```
