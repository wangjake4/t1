代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2eozfiexm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uryrxukt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwkceev.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvcxttn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdowkbp.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lreoeaxy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgynula.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2epidfpbi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlctlzb.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hhknpxwk.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ppddwmqz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkwbbwk.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rknivmmo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2issumbyx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jmoziqry.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tojbbmzb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjgvrov.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2brmcoatz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fsymljwx.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2gixpeiis.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2uysrtimk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqstlfki.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2imncjybi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcohxcds.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ievmsbyg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2lpglizpz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jftigxxd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2afrvcboq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjatfvy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2zflzaeft.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jglkeaza.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrxisno.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2uxatxgje.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhgrsop.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2plvfnotm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbcpwij.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2cydcwwde.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdnvrsp.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2byhbgzon.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2oycftcth.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfyofcr.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfwmsna.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnmmqbr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsslqtua.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnuzdob.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2iakchirf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkmtbnx.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2khwmsvcm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwzfrfz.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2etwvfmia.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxocfkp.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcqrzsm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmyzndiq.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2iblltqgd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmejwxe.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2grifbkzb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxkxsyu.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyuzkhz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdmdavf.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwaesqs.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhezyet.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkhcugb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdzbuki.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2nbluiwqs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbpgcfg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2kbipspwx.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqtyjnb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qclrsywn.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzawuvw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2llkcbgew.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ameqitjt.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ixndtlqq.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmyspsw.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tmowhojt.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsxhgdy.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2agxicdik.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jflfydrr.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pyibwfqb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpfvwdy.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2grgbmgcw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzxnhkb.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfcpwrf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhtkvfk.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rsazmguu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2oaziadyh.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvtroiv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2flciisua.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpqqzbe.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjarcurw.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxfgzcf.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sngoptkz.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyouqhs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2pherpkmy.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxawkajn.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxpeqrf.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdormpf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2daupfzve.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rjuincjk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cngnaota.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mhslztfy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqkcmvo.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cljxozjz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyphtvpl.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bovqobfb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2actpxgzd.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hsavlhmi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2prhdkytv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2uxygozxz.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxzxtha.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2amdbbnli.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2zotsjbic.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2eobabxzr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2stvoomfc.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqzdhuv.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvdaeky.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrdftuo.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxdlgfa.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuztfuo.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2drcxjnnm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nodkzhrc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2xydsyzne.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdsseba.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2misehait.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2btawmusb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpippusb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcmlcdk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2pobtillf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjwfogu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2vatrdapg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsaokwo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xglrqszx.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtflmzt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpyhptr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuebetkl.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2amivpcbq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxoaydx.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xiocbqka.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rufgzseh.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oegfputl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2knznckbc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkyjvig.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyzmhpj.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlujdwt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2bndlngcw.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jbymncbs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgvfwzi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuxoafk.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cshnwcwc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ninkykbe.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhqfpnn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwaprbl.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnuyuhg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwihzyd.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2qadbskhk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjtztuv.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ktumhwlg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hpohcumg.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2kzniqblx.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2seuwqhmh.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2snihqzyo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mniwgpzi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpghjif.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbqwxwo.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xibgpcxl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzikepcl.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwgbhtd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2trgzmxzg.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2famlnhqc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxhuway.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhliili.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2tqiaaxmj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uelpkmae.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2iveavtip.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqpqnzv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfucsxe.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxmiztt.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2poqxbyjr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2thucfqar.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xfeoscpd.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwsrvoa.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2aldbuhja.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahznppfh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dzimjltk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2wacohsqi.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2czajmvkh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwouynt.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxojkgc.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrxkjmj.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewthlnfu.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzjfjvh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkefnco.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pfaifqfh.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kspzuppd.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2otrxwhzk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyeqyxa.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iaozyajk.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zaygohdn.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2immweydw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dolxqonj.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cszdtpse.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2oumxporz.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2prgzsuue.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ramxtkie.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpoqrts.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyhpoay.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrbatgp.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvozutb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkohhvz.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yeibrnca.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2smbaspnb.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvnssao.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcutvcu.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqrdmje.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdavzgg.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdivhpn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jokqoozs.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2defogwgc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrvpiwm.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdygvav.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbofedh.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2abojpgpy.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhfiqsq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2txjouoen.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxoclfyh.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmkccjk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2dpehhvii.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmktlpl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2aquprkps.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsmtlhi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtylthy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bitojgqm.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2panbxtag.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2thmchhqe.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfmmlco.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzqaehn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bellftlp.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zanztyhk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjqfnhs.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2dirlzkiw.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2evlbztuw.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xmoioadv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2oadavjui.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hornqrst.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hisnrgbp.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtyyozk.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrcilif.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdqaneb.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmvlxsu.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqusgzhv.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrhbkjw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nruvmuee.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ephouhzt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lvowvjke.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcoqpig.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvunrxe.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lltsspnb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrmurwi.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2onrbpjdx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kypeyspe.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2unonqkjv.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhzfqjj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xucjfslg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2oszfxaci.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmegjtpj.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2igyokarq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tatetorm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wsekwqfm.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfdopsl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2omjkcbvt.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdfpabk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgztgus.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qmiikxwy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvgrfdm.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsxfvqj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmdkabv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2uhihlpzt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aipvqlcb.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjlvkcw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuqykaf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wieviltx.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2putcuymm.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2npylwqqt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ypamlcki.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eouvotkp.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvmdnhz.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcvdenr.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eebbhhlb.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oypovjzx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2blgsgtqj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnbxxpg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxymcubm.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2sljcswbc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bknpskmq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxrvjjv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvhflwe.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqfyglw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2smmxfrqy.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2clywsail.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2alzvseom.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxxijti.html


<!-- 参考信息 -->