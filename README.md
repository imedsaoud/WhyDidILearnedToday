# What did I learned today

## What is it

**wdilt** aims to:

- encourage me to **learn something new** every day
- see my progression **over time**
- become **better**

> As much as possible related to the **front-end development**

## Generate a Markdown Calendar

```JavaScript
class Calendar(year, month)
```

### Parameters

- `year` : the year of the **month you choose**
- `month` : the **month** you choose

### Run it

- **Create** a new `Calendar` with specific parameters
- Add `.fill()` **method**
- run `node app.js` in a **large terminal** to see the **results**

__Exemple:__

```JavaScript
const December2018 = new Calendar(2018, 12).fill();
```

> You can see the result in markdown below ⬇️

# Progression

## January

| 🗓 |        Su       |        Mo       |        Tu       |        We       |        Tu       |        Fr       |        Sa       |
| -- | --------------- | --------------- | --------------- | --------------- | --------------- | --------------- | --------------- |
| W1 |                 |                 |[01](#2019-01-01)|[02](#2019-01-02)|[03](#2019-01-03)|[04](#2019-01-04)|[05](#2019-01-05)|
| W2 |[06](#2019-01-06)|[07](#2019-01-07)|[08](#2019-01-08)|[09](#2019-01-09)|[10](#2019-01-10)|[11](#2019-01-11)|[12](#2019-01-12)|
| W3 |[13](#2019-01-13)|[14](#2019-01-14)|[15](#2019-01-15)|[16](#2019-01-16)|[17](#2019-01-17)|[18](#2019-01-18)|[19](#2019-01-19)|
| W4 |[20](#2019-01-20)|[21](#2019-01-21)|[22](#2019-01-22)|[23](#2019-01-23)|[24](#2019-01-24)|[25](#2019-01-25)|[26](#2019-01-26)|
| W5 |[27](#2019-01-27)|[28](#2019-01-28)|[29](#2019-01-29)|[30](#2019-01-30)|[31](#2019-01-31)|                 |                 |

----

### 2019-01-19

Today I learned how to use [wdilt](https://github.com/blyndusk/wdilt)

----

### 2019-01-20


<!--git command-->
gst | ga/gaa | gc |  gp

<!--Mysql tips-->
I learned that it's possible to have in the same BDB tables with MyISAM  and another in InnoDB for better performance 
option + shift + entrée  ---> execute 'Sql'

<!--Aide memoire sql--->
SELECT *
FROM table
WHERE condition
GROUP BY expression
HAVING condition
{ UNION | INTERSECT | EXCEPT }
ORDER BY expression
LIMIT count
OFFSET start

----

### 2019-01-21
<!--ssh-->
Today I learned how to  connect ssh with shell : ssh root@example.com

<!--Dump db--->
mysqldump --all-databases > dump.sql
mysqldump --databases db1 db2 db3 > dump.sql
shell> mysqldump test > dump.sql

<!--{start|stop|restart|reload|force-reload|status}...-->
mysql.server 

<!--Connection-->
Mysql -u root -p / mysql -u root /
Brew services start/restart ‘ex:mysql@5.7’ 

<!---Version-->
-V —v
 

----


