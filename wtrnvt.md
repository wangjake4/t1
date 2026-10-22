代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpsoxau.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuhkiup.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwhmdbs.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyfucwa.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpwiwel.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2famjdrud.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqqukui.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnnhyki.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbgpklr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcggunxs.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtfndsc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2falmkqyr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfmvkwa.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2gryahbjd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvolchc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuhgood.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsqrbgd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxtusgx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnxfskt.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsygxkm.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2zadrxvbd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2plhiwgtu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvhqtjp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkxvyxx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsxhxeu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvheljp.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvogeuq.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2lttptjny.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bncktipe.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjuogcp.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrcvxaw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjyswgf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2joywepqo.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2zopxujdg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbvhuav.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdaarbe.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlutagc.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2kyefayxt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvcbwhp.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2tyflwvyp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyszslg.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2waeqxkuu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmmouve.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfefhzm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2eycwrtrv.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvzjpsd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2profhqed.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmrfemo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrlvtun.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2vubbaxuh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyhukvh.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2bxssfdlc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjdbsyg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2npfkmhpz.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ckghmeui.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdtdycc.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2azymeoun.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2aghqlbap.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtqypjg.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fmczuxvd.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2czawkvlj.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvsvygx.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2etihbkjh.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzkpfap.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzvtspu.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2csegycfo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2yyaywcwz.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcolmeq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzkfncb.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2djkytxpr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2znfcipow.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhkwsee.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2grcedvsz.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2arvzstkp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqkawzq.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgmnjzd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2bckepnsg.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tmknycpx.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oodhuwcr.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wenifvmd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2fotmxrqb.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgbpogx.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxbqwff.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zobimkzv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsjfqqc.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qashvopv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvoewolq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yxytmzkc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yibzdzjh.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dzexzczp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fetdgbvn.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwrfjwd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yobrbjwj.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjvmieu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bogwziid.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2jxerguux.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hokzedjj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqoxxuot.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxgfvfi.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2motooxom.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhdhnbx.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lesfsxuc.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxxyull.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2felpvujb.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fafyrytn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tczmnjfa.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2axddppet.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpuuoqbh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvbexjv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihekxopn.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2musqbtee.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ehirpsge.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cixbwozi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2goqdsxpf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmcqruq.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lovptdit.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2llxevsxs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgikuqd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2twgdjfor.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzquowe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xitwgvty.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvoaqtp.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ngeoxjck.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2txtpskwq.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vokumgnj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgqmhoj.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xmabohid.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnvpfhv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsnyotg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgduchak.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2emvawwno.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghirvbgf.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvxkqsy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfcefeq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttenmqye.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2csdbovek.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkjqnor.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zecrrvzn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2egpwemgh.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jseqlvmj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2syhuhknn.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqbzzrg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2idqzpaia.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjvqvgd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzgolzo.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2lapeykgl.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpeufjsx.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcxmwfg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfmrvnw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnlhtyh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwwnywb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pvotjoyl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2quidnnpg.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2disqoloc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfbxwwq.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2vllqsnfv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2biukqvsw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wwaqzcrm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2hipnurfq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fszyczes.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdamuli.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zswbtexv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcvuwke.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbhzjbe.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrqxmhr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdggfwo.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eraeuzee.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2afqtkujc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2iyntdacy.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqnzuam.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lusmbfvw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzbeums.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2vdymntbk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnyszbg.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ivouufka.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhkdevy.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewufrerw.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2whlgcjbk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmoibsi.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2eustyork.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqemkpj.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2asakzqdo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdelgft.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpcbbqr.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnasqgvv.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2aazfropp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2oiguxtmy.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2srgylxse.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqlxsly.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkpoubh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nilhijsi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2svgtbhzi.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkejgfq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnpaatf.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2opkvvrst.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqdjcym.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2udnfhoib.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2xpciletf.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kdowacbj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdkyake.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2licaaayx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcmijsc.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgvxfze.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eigbjemh.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2brnifdry.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbgkzqb.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbxsqmr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfoaarnt.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2upsvqmfp.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nihnrzpg.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmjlmay.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rncuoqca.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdhlhqm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2hdufebye.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwilbmm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhgoyyt.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjsybzl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtigbuc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwswnlgg.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pzoosjgp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cckbnfdd.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsibkne.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgwrzew.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbzfvqr.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2eiutvoai.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkxsyqx.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqurrvd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtoggiu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjqobxk.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwxheol.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wsosctbl.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kbeiwhvv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxhmdjz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mpohooav.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwxjzoe.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqknspq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcplril.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fbflrrtm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chyqauxr.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmdrfma.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vxoelpem.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2euvcwsus.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qoppspwp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2edlwlhtb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aupwyrnz.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhqwvpd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jqefgjpk.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgxytxu.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2srzspoxh.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjypdcyq.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2akvydllz.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeiqfwlb.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2dyoevwzg.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbgyktu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zltpydiu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2quditfxg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oegjtand.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2milabxwp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqxkhwy.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2arqawvzy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxtpaza.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjrpmoj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iyocjmht.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ekeeurlt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2agnszqav.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqbslco.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpvrwym.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2srwnsmqr.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnjprou.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfgkken.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2umonxjbt.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcbeloj.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyuulhw.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbofzdf.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlylvdgw.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpgrjfm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfwcrcw.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsffdfn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hizkmirk.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlcamfe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpnphcy.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vudhrzck.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdiijyqa.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2udaqphnr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfxzemm.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjmuxse.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2rsegbexk.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnqmvqs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wxoodddc.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ovltdspf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2iobrgdbe.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hxycfgrh.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvsehtz.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfdtpyy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfhicvp.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pwozluyt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2enchzxaw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2elqpnaxa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjyonbj.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fxiakjtr.html


<!-- 参考信息 -->