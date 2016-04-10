把OrderFood.zip、order_system.sql放到一個資料夾裡 -> 
解壓縮OrderFood.zip -> 
把order_system.sql匯入資料庫 -> 
打開connect.php把帳號、密碼、資料庫名稱換成自己的(檔案root，無密碼) -> 
註冊一組帳密登入系統使用訂餐系統 -> 
主機為host10 

-----------------------------------------------------------------------------------
OrderFood 網站介紹
login.php -> 登入頁
sign.php -> 註冊頁
index.php -> 首頁
menu.php -> 各店家的菜單
cart.php -> 購物車，不同店家的餐點會放在同樣的購物車，但最後會存成不同的訂單
check_address.php -> 填寫取餐方式，若要外送則需填寫地址
check_order.php -> 確認訂單，送出後不可更改
order.php -> 確認後的訂單，訂單開頭字母八個店家分別為A~H，可以匯出pdf或csv
select_order.php -> 查看所有訂單
order_detail.php -> 每筆訂單明細
download_csv.php -> 下載csv
order_pdf.php -> 顧客訂單pdf

管理者帳密：
後倉：ID -> hauchang
穿停：ID -> chuanting
低逼：ID -> db
res1：ID -> res1
res2：ID -> res2
res3：ID -> res3
res4：ID -> res4
res5：ID -> res5
密碼一律都是abc123
manager_menu.php -> 管理者頁面(顯示菜單)
manager_uploadmenu.php -> 上傳菜單
manager_update.php -> 更新菜單
manager_orders.php -> 查看所有訂單，可匯出訂單表
manager_order_detail.php -> 訂單明細，可在此頁將訂單設為出貨
manager_order_download_csv.php -> 下載訂單csv
manager_order_pdf.php -> 訂單pdf

手機版 >> 開頭為mobile_，使用與網頁版相同
