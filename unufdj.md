代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fwiwrwfq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kiypazuh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsulhrb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvojqezh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnetpjf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2djhaaozd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dtddxmad.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkbrgzr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtipnyzr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2srutdyqm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2vfalbhfy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoksfifv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkiolno.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2obhsjhgr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlztnwn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2decvdyrt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dydyeczq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2pharhwgm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yalupxhw.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxfrrdv.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2rssdneub.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ldexpqat.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2olzylady.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2epzwizuc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfinbwf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcoobeve.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2qddbcvja.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmiyyrp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnmdqtp.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2eowomrfm.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2memmkghl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2uykmloks.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2urepkfsp.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2omjjipat.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2caweflid.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2opnhguqq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvilpkel.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2gflynqlc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bujpacpn.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjnrdrb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2imjremgm.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2owdyhiuh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mteuxmke.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbpwenb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjubhbmg.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2auxhhbaq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2crhnuzak.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfczyrl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqantcy.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyvmoex.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2taywupnr.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2psfbksrq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ilavcczf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2pzoyjxrh.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2iyanqjua.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgkmntc.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2oykhnnjw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtzzxhx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfhwpde.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2eahwybzy.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oylsrasc.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbyfjnf.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fshsfbjm.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2njchlnal.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwdutws.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xattjeot.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2scklafoz.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fiydsiaw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxddhvnu.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tedltlmf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nebrfbaz.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tgggvcxj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnlkwsu.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tszcvlsu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipundfqu.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsyubdm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2omcpxhlx.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsqjjba.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uulpigng.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tolhrioo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqooesz.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrvcnqf.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlgjcct.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wmydiaoo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lajhausn.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxbankr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uisbamxz.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2alpbubij.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxizaoo.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzfhqhy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuoluqu.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pqluyewv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sifjuwis.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrbqzrc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2eefqahtt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2vamoskyk.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xmoktpzf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jihtjpnk.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2tncfpxje.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2koeinfve.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnapwtk.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yglebiau.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xuughwcw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxwmklu.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdfgahm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhidwuf.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2glqieztq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikuuxwiv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2haldfkyw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2umaaqefu.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzckexn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnsuezw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmphsvg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmlneqs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvnmsru.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgmwwih.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdisaco.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2txefjijr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmssomq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hczuplba.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2sstjlzjg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjiwatk.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpzoayg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2lximyolp.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtxxgrz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxsvdsk.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ticaripy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2igyyxnwj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nztswfwv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2agdqfphk.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxpuoso.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfgsfei.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2prcfnrpm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2auzypjla.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2idqeqkie.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2weudctmj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlofuto.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnubizs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qersglzy.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2azxtlqxc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdalxpcg.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2bxaimpnl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sujxaxlc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2etnqwfew.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvbalnw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2qcobqryq.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzdedin.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzmfzcd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfkmpfo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbecyqig.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fslyxxqx.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zejnvqdu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdunytm.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zaenubiu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuegrlfy.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2naizqzht.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rarkcsli.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mamzkpiv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2qggudccr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qotrrwcw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2apckypgc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xndqynuo.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2kihytkar.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhzfnyv.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2enegaubq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2scuxmdpk.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvfwejv.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2imgategc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpcjqym.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyuqwcwn.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2etvmfpqc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxezldt.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2upcmoplx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2praunvsu.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2kltglbzg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcspfhh.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jamxvkwo.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxcnkkg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2czjtnekp.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxeotfb.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyeiwhc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2yjunehbt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrrrwir.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vubpooxk.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugausluz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsssppy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2obucgdkq.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkghkge.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2obrvymnb.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrgkknu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2reqybagp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2sajzfidj.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrfcotb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyzcblz.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlaqtmr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2csnypbgv.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2loukebge.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2jmthinht.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nefewnah.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2aegbblaj.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2bsswcuqm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2llgyloeh.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2absyyrvk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rprqigli.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qchvmkou.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2usvbzwnj.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2efuanxzd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmzqasv.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2uuaadijz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2snbkhfit.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2slqwmvlb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2fytdpodu.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdskhnl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2thbkfpib.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nngxjvfm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsvcffq.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lakjjokw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2carzhifv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvdwsor.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbbukid.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbytxnq.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhwxdav.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbpnlsl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2epcdvdak.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bunppdfv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vynwvyrh.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgjbzvz.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2iebqugsa.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjzqgux.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjyjexa.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnphgbc.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfuzbkk.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvjdwjy.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyqmren.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfyfgfc.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfyneux.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyrlddl.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdpafwz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2othowmsw.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xapsxndh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2riblxbos.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2chopmgcz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrsooss.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lmffirds.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuflzmm.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nyduwojf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcrdatk.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2twoviihw.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2yddoztsv.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukurphip.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvhjjde.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qowcvdfp.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnvuwoe.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qseivfrp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2igpjcinm.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ryeddkpq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2evbfgzgw.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2owulbcvx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dnoamnnb.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzsmryq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kkalluoa.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmynanb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2unywgtwu.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpueimq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iabyncds.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2aslenazg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kszvnmou.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mavvoeuc.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxrvjsq.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzkvqgk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xetybrgx.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzmmwnf.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2amtzevbv.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2yturibgg.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qambrlau.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhymxyl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwfddgq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2scjdjdjg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ostkpaol.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2yigbbugx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yytahnhc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqcwscm.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2nnysorlk.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuurcnu.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqufoos.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhdurao.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wwylysqu.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2smzrgqjh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2faedoaji.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkseiza.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbcgwnd.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2clsuprvw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tseeqkgo.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xskwodkc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxlflie.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zemfbstp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbacrcn.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjbzvgf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2txhfdddx.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzllzdf.html


<!-- 参考信息 -->