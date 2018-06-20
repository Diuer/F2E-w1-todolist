Todo List
=========
> 參與「The F2E前端修練精神時光屋」活動
> 
第一週 [設計稿連結](https://hexschool.github.io/THE_F2E_Design/todolist/)及[Demo Link](https://diuer.github.io/f2e-w1-todolist)

## 功能說明
* 新增/刪除 事項
* My Tasks 顯示所有待辦事項&待完成事項數量
* In Progress 顯示正在進行中的事項&數量
* Completed 顯示已完成事項&數量
* 星號為標記最愛（同時Highlight該事項）

## 資料存於localStorage
* HTML5的Web Storage分為sessionStorage及localStorage；主要差別在於生命週期的長短。
* localStorage跨瀏覽器分頁、新視窗、甚至是關閉瀏覽器後再打開，資料仍然會存在，且永久不逾期，除非透過開發人員工具刪除。

```
//存入資料
localStorage.setItem("Key", "Value");

//取得資料
localStorage.getItem("Key");

//移除資料
localStorage.removeItem("Key");
```
* sessionStorage只存在瀏覽器的單一分頁（當開新分頁時，又是個新sessionStorage），預設無逾期時間，除非關閉該分頁、關閉瀏覽器等，資料才會消失。

## 預計增加
* 修改事項的功能
* 顯示當日時間
* 加入icon美觀
* RWD
