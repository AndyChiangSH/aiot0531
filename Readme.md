# aiot0531

物聯網 - hw05

## 步驟

1. git clone

```
https://github.com/AndyChiangSH/aiot0531.git
```

2. 安裝所需套件

```
pip install -r requirements.txt
```

3. add an heroku postgredb

* register heroku account
* go to dashboard
* new an app
* go to resource and add-on an Heroku postgredb

4. login to heroku pstgredb using HeidiSQL

到 Postgresql >> Settings >> Database Credentials 取得資料庫資訊

![](https://i.imgur.com/1mAEzBF.jpg)

![](https://i.imgur.com/zlLuIs5.jpg)

5. import postgredb (in `db/postgre.db`)

![](https://i.imgur.com/u2fJ0qI.png)

6. setting db in `app.py`

```
myserver = "<fill-in-Heroku-Postgredb-DB-sever>"
myuser = "<fill-in-Heroku-Postgredb-DB-user>"
mypassword = "<fill-in-Heroku-Postgredb-DB-pwd>"
mydb = "<fill-in-Heroku-Postgredb-DB-db>"
```

7. testing locally by running python app.py
9. deploy to github

```
git push origin main
```

9. Connect Heroku with github

![](https://i.imgur.com/DnGsJrE.png)

10. Finish

https://aiot0531.herokuapp.com/