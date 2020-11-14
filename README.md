# app11_2mongo_post

 Version: 0.9.1

 Author  : Kouji Nakashima / kuc-arc-f.com

 date    : 2020/11/14 

 update :

***

node/express( es6 ) + mongoDb ,  POST data sample

***
* CRUD sample ( /tasks )
* POST sample: /tasks/import_task

***
### ■　mongo登録速度の測定値を、追記しました。
1,000 件で。 0.89 msec 

(１件あたり、0.00089msec / 0.89ナノ秒)

・redisが、同件数で。 35msec程できたので。

　mongoが高速のようです

***
mongoDb : 3.6.3

### npm
* mongodb: 3.6.3
* express : 4.16.1
* ejs : 2.6.2

### npm install

* npm install mongodb --save

* npm install express-session --save
* npm install express-flash --save
* npm install moment --save
* npm install csrf --save
* npm install bcrypt -save

***
### setup
express app1

cd app1

npm install

npm start

***
### npm

npm i @babel/core @babel/node @babel/preset-env --save-dev

***
### more

https://note.com/knaka0209/n/n062a0bf8ca9b

***

