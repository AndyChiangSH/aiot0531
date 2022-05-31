# aiot0531

物聯網 - hw05

## 步驟

### 1. Clone這個專案

```
https://github.com/AndyChiangSH/aiot0531.git
```

### 2. 安裝所需套件

```
pip install -r requirements.txt
```

### 3. 建立 APP & 使用 HEROKU postgres

* 註冊HEROKU帳號 (我本來就有了)
* 新增一個APP
* 新增外掛功能 heroku postgres

![](https://i.imgur.com/CiBtM8e.png)


### 4. 使用 HeidiSQL 連線至 postgres DB

到 **Postgresql >> Settings >> Database Credentials** 取得資料庫資訊

![](https://i.imgur.com/1mAEzBF.jpg)

![](https://i.imgur.com/zlLuIs5.jpg)

### 5. 引用資料庫 (`db/postgre.db`)

![](https://i.imgur.com/u2fJ0qI.png)

### 6. 將資料庫資訊加入 `app.py`

```
myserver = "<fill-in-Heroku-Postgredb-DB-sever>"
myuser = "<fill-in-Heroku-Postgredb-DB-user>"
mypassword = "<fill-in-Heroku-Postgredb-DB-pwd>"
mydb = "<fill-in-Heroku-Postgredb-DB-db>"
```

### 7. 在本機測試

![](https://i.imgur.com/CZhBw6t.png)


### 8. Push到GitHub

```
git push origin master
```

### 9. HEROKU連結到GitHub

![](https://i.imgur.com/DnGsJrE.png)

### 10. 自動部署

### 11. 完成!

https://aiot0531.herokuapp.com/


## 成果

### 1. Random vs. AI

* Random
![](https://i.imgur.com/1iAelnS.png)

* AI
![](https://i.imgur.com/81135Pd.png)

高 -> 綠色
低 -> 紅色

### 2. 額外顯示溫度和濕度的數據

![](https://i.imgur.com/x6DQw62.png)
