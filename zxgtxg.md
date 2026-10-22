代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhyiaho.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqmevgc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqangta.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdeizye.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfmodba.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqymgdt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtiuxaj.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2nazbvhas.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkhvibk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxgzdqs.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuonyrw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgcejay.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ychmhxxd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2eiophrmh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2yylxtuvg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwhknhg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yorrogzl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2aawjzbgi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqronyi.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2obibqrva.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwucigq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kadewqvl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2myqnrxzy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbitjda.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2xztoxinr.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2djjrjgng.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2thaprrnq.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyuwcej.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvsjjbs.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2flobtlaf.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqlijiy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2sweswrfe.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jomyogqc.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2iilbmwvw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2puhvvtbf.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkodnil.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfllxqk.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2xbeltiqn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfyinyt.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2yttzrhab.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2yumzjhpu.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ksealfvi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfoynzs.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhhocro.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2pporazma.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2znjdtauq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2szzufgzt.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzypsdi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kndrjcyt.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2djpkbbjg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2riqvplta.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2suoxjpfe.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2nodtvekz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfnzamk.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2abxnptoi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nqthbwen.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2nisoifhx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2vutvvjlg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsszauk.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2myptovsh.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfztpkuw.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgonlon.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrejygwy.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xapxftuj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmrdldd.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrwukco.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrahyoj.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eszufrzt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyawjdz.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2thswmhmu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2juzuvctu.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xreseoax.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jahgwvng.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bansblwm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohccddkv.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2boqrvmsj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2amjunsli.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lykxhxmp.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkloiqyn.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzqdvji.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2wvharwdp.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvgwlty.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcftzar.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvdqyyw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqqudch.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2haglgwix.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkinxtb.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2sysdraao.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2snrfyigx.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2plemgbbr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcrbtvi.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvbcqxr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2csurxqek.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2puilcttg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgoirnoh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyrovdt.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmszyuq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmujjqiw.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuqvfco.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2braqsgzp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ipeijvyt.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfmydtf.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rsihzdcn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2czvriupf.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyrfpfq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvjwcgu.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpxfvta.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2evmmcpnm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwsqbrd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhmtdky.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahikzsjd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxubasg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rocteiva.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlxmkux.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2eehoexsz.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dnankdsv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2kliuqvyq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfnpooi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnslzgz.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tshqmrxx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2edyopyob.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmqyzxp.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bqahgtre.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuwyfiu.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjrjdyy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgwjdmq.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2efqxmijj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tctwqmcp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfusxal.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzylcipl.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwlsofj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgcsmwb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aqngghdc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtpczkg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvfsvsj.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmentoc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfwharc.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrryzzd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkfodmf.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2oaycqxoq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwcchlw.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbztgus.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmykrcg.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpwsgzk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfvmwoo.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvmkwev.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbqudih.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqwhvdd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmerfdll.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbsrhnk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2eopqoebo.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wxaxjjsd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxycyhds.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2boujcsdj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bspybsqj.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2agwavlby.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhxyccz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hvezkkzk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ymprtmsb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofophbqv.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ldswuabl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzirqva.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2dpltrrxo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nudbjhko.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dqoynjnq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2zqeqfzrv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fcduzizo.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxwzicb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jacitfas.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2swxqahwk.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvzfrzi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2glqmctue.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2oykolfdh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuinqzs.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkjfahw.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrxhugy.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2twiicnbx.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2vwytpsga.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcxvtbt.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2azwqqjhn.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrtzkzq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2szjgjrdp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2svmvoxfk.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkrvmxq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxgmlsy.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbrnajn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ogygsahw.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ferqcfyf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvyybli.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rsibyefp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpzsazp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgvwoco.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkwdyrb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2oufzglur.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2etezjtly.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2bqiqnncm.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kaybvofj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzwoqrh.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2guhhbxbv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjkvifs.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ketkocqh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmxyrsb.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iimlfbla.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgakzsxo.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uexdjbhl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvwfuwi.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnxiayh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjuilow.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlbdaow.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uetvpyvh.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxmtihe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnpdpbr.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hjycjyve.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2lhverbtu.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uagntqxb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuenlfrx.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2upjbjyfi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvhjgmy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrbubqi.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgqsshd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgfglvm.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2fijinssi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tacvyhvt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnsafee.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhocrdn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jibewzlv.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2rpafdbst.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxqubmq.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpxcszp.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlgvshd.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2moyxdzew.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2selmgkrg.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhniedi.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwnpffq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rufvokgu.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrtsufj.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozeyyrha.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdttksj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhminnto.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2knhcwcfl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2folgyizr.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iehxkqkn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gepeuyep.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mshjsaii.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2csnwisyy.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2msjwzrpj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ziffjrko.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdtkfqx.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2oygiixto.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmaorzb.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihblqbau.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqmiwel.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtnyakh.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2axjscvlm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtirtns.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfrqsop.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgjmuqh.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2unajtovo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmmyrzc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eppasmin.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aiflcfra.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wpswcaqb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2knzgarca.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2bcefyfnq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2spvzkmwk.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtznmuw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrgiotg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxfpxhb.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2trtlwxef.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnnqbhv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldajubfh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfvkhnq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wghbasij.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdzbqvb.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvapkmem.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2epzmdito.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2unipfstg.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbtdejd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmotjwz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwktvgk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqjxwzv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxeipbq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqkwlyi.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2putdorcx.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcuxqjt.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2chevssrt.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpmnogf.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvlpepy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aziwtily.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2endkwylc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmujmpx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2twvyeixr.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmaeeox.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvztjur.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tawxicrf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tfoagzzi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qdttvbig.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzziaoj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gicjepvn.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsrqbxf.html


<!-- 参考信息 -->