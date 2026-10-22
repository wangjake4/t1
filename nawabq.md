代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtdplok.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bneagzyp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjtqdek.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hojtkrla.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2emltjzkd.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjoeurz.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfxphya.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2nfidlveq.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsfumet.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvmsnss.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2razzmydl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqyhuvv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdntljv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zazposef.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2llfrofor.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2veyifxnr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yelsyouo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqwunyj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2hyihkqcf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfighewx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2afsufaff.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkdyase.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqwcupi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2asfezfyt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hbogglox.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2adjpfarx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwqqgbt.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2dedbfvru.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2axqmgbxs.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqybatw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmnnmsr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbjobcx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2mshljnys.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjqxcid.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzyrgjh.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2npsmxrxj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ufznizir.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxaoxmb.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2hbshhicq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhitcqjj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2eglycddd.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2jysicnpt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dprplgph.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2onjdptal.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyxliao.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ampncngi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqefkpm.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvudmiu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2luzpilxl.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2avsgiuew.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgeutzzv.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2phavgrkh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyeenuzy.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jocezlua.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2urvaalxz.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwuyfru.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pzopqcnu.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2dobhbwxk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gygzftfq.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ruadzesu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqltkyj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2wrozhwyc.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2eqehepgq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxlcuvy.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbeboacc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2epxstbkm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwyxgwh.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xesuvfgg.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqdfaak.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ttezigiv.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dubjefbp.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrgkjgg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2knldefzk.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bphsiysr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuxxfac.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2beiguhvf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmfyngm.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2aehwtwqj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyiyzsrk.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ydziqydp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2eklyoukj.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhzptmx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmhhuyx.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2masisdeq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqlwzgw.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rythjvyc.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uitdgyku.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hwghqhnp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2cejywrsb.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lsiqxvqn.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2whcotjwl.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbihsvwg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yecdgxps.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gmexbuvb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdldcsk.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcpbpaf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2otcwvwmr.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ydovkpbx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2chpelsuj.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2blvqbuip.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tueqnist.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wowhwryd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wihazakf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2jgywlcjq.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcjqgpo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2bziuneal.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpcafrm.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjihnxd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2pkloxixr.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzaqbbf.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnjlozk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aonjqexy.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsthlck.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyjpsoq.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dasbaior.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbhglrr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpdkkod.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgshtwim.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofijekca.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnglgcp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceungtjl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxlzjix.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdfogby.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gnajgsfa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2blxnbvok.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxruvtc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuauereq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mxofqfen.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvvvzlv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdemfvfx.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2plmsgwir.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdqndrg.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjabbww.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmxplmu.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2izwmaaqf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2txknvpvw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nthgfdsg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2iknzgwne.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsijgam.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2isrnkcda.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzkezpn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgpvqcg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2upeceuuj.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2muebgedi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqytuzw.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2aoawvtna.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpajlwo.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzfkjzy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fitbdvcc.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtvnyro.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkafvziu.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgqhaod.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2aowpqdne.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpoahrs.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqepqjg.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lncabywf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2capaxegd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvpzioe.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpickal.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zniuhmke.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2usvapofn.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vvllydkr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpiigye.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2khtwhlbd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cccurbrf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhzqwxi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrboqcs.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvemqfzz.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2oltmzxza.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhneengo.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqgxbnc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzyzhev.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2htowdsiz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2osqizpcq.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2emrkbuor.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlbosfz.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyzacnt.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2goeyvqfb.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdyqylg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2mohhbwgn.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmgnrvi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2gptkmtlg.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2fqihcrqm.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mldxwcmh.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwqyuun.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ltprvjzd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbyssxn.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mkghmsvu.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcjalkt.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrknsfa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2misfrsdj.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmkaewa.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjirocor.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2coxigpzc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbgdylh.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tulsfsxs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2csosmogp.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcbhogx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgqgnwb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2sacscvcr.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2toxxitwd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvveacow.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcovnos.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcnimul.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdpyxot.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2dimlprva.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vejkqctw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjgccmc.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgyqviz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2knnglgdf.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qevyqurl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzuaizh.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sflqopil.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxowjcov.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kncntjeh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2axyesunp.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpqocdb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2saxqzdvg.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2wgevtljx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvesvaau.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dhggnwmd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpzjngg.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eoirymbo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2axjxxrui.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2slcxvfsi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqsgzzu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsilisvn.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rbofzwba.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvnxkbp.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2utpubgeh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2czqnjpjf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mvoclsal.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnibicc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cmauaqqr.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2lndkicqn.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ugufmkre.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkkfnew.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrvmtgn.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhuzycqq.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2khabxxxw.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jscagmuy.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yunfnxfr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyazydt.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpihuhk.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrkbekb.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iburwmkb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kduwkyal.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iruyoeoa.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfymusx.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tohcgmfm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnusbbf.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2itlahuuc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pwucakrl.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzcewkc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jwuumwjw.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cousmldf.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wifwburr.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pitrusad.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrnmwgb.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuybbftn.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2umpephlz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjsawdt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kpneurte.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmiheot.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pwofeyvr.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2honxoobu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbniwxi.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lizpnufv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jwiuhkej.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxlotga.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdmyuwl.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfpfrbx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdtaqdc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rydmtbxc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gamnwzdj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2skvxwzny.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pslqilrt.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxxpbcw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxnyjiq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dxechhhr.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvefsoy.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjstoag.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqncvfs.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tjubkmkj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fxskfujz.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjzohjj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqghmrlh.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2raenhkxw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vazucspo.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2itrdlopn.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsextbz.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2fodnmipr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2wabjpbad.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2qijbiprp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvyuxnp.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pddhepws.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wesbhtyc.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2sljrcgdk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfetmrlh.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hisugaep.html


<!-- 参考信息 -->