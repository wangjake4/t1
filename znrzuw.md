代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnnhrrj.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2foprbdmj.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2syauxvbj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfxgmsw.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yojqukat.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxehbso.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqqwpxy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyyhicz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2uciobeqg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyutdjf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cvebpjvp.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2odtvctuq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2znzfoivh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdqdhlm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2knaegksn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbauufoo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2huicagiw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2yxutofgu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2npqybrlb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2srknzjoz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bayntrpq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbkqsdm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kleqzrhi.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcvkkbp.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2aauakznx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2crvvjjcg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2wualkrst.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsuqxfd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2krghdneo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2joltqytq.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyzyuls.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzmaqhw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2frutbsdx.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2heqeqgxj.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbhphrs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdifoyd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtchkbib.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqezboo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjilaldo.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2varijcql.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyioywl.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlhcypu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhuhtbzw.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlfrzua.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfzbruj.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2kirwwhcg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2haizzrez.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dblftzro.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mloxdhoy.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cujaeuuc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpxgkxu.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjqjcwi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cnahzkvx.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2btjmzdly.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvkacth.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ipahbelz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2jaoddnan.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2yskkaggx.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2uweftxfk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2okmvyqsy.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcrtljs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkujcfk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2klryrteq.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2sigmjlpn.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2alpqxqqw.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2epfcerqx.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvigowx.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aryiyoir.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdkqbko.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzwncaa.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgcqemy.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ejahkjca.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmklgkg.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvswdkw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqycidw.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdkbigc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuzqxns.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwmtdjn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2borwekqd.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpxqmqb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkszazai.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmqmwms.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sznkkyfx.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yitgcgaq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2qguueuot.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bcarklli.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbbmqup.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvuxkkq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwjqrih.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvpjrwc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lygxrinj.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2icbqxsex.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2izaivvho.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2sthzfupd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwmcpwj.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzcjsyl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbavcfzg.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tugkyzde.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wntozksa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqjxdcs.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hklsmigk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxazcfbq.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2daznvzvd.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpkkwep.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhweocm.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2saurlbmr.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfbkabj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyixznx.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ropynpcs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvdqnmb.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lskjhfhz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2teywsoop.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgutage.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddydwoew.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqlvqaa.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtkniwa.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfippcwc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2aohiuxpr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiempkd.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kliadyxm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyfltti.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2akqnjggh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydacvmgi.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmxxhbe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjksiry.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2brirpoiv.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bayrjqbi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwznjdxi.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ryatqhvd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvjotsd.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2temqsefa.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcpjisx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rdezvaxs.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyormsfa.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uttuyezz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2dssyymvc.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wknaucgv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhkgoig.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgplzll.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qndlothv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkrouee.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfadzxk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2faoaxeds.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyplyzm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hepgcdbs.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2kkshudtz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwvokbp.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcjibjx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjzsofn.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwqirjg.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttghgrig.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2moowpxcb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vntcjajt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2imqnumjj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmktget.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ytowlocc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkyrdnm.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqlczbm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2swwyhoeh.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2zatxlffl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2trofjdhw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgytqxn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ynavbmkr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2afulkagu.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2blxfqjzs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kttisnws.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkiaafr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbiawnc.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvseqof.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ksujixox.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2aupevtyt.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2krcmensi.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eiublsgi.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2vunefnbp.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tydopjgy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2aezwhluj.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwffxdu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2opobtuto.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2kqplqnuq.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbteknj.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwgvjcg.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2cupluptv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2atisgddv.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2qeetxqjo.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtioyumd.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwtxqmg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2lystciky.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2prqrsflz.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dppvyuqs.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2notpnvnd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2krpfjbxj.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqdpgsx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wetwfilm.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmqykpb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfueuzje.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2jtecciwr.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2iayvcmgb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgptynez.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ralecnrx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2lzipxzva.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwhspge.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2gosyhqtm.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2juweywtt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2uotpzvua.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2geymsjuq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcjvruc.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyyuxyf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iflvskdb.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dionjxyy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgpywkg.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ybouxati.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcexbfm.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2gagitsvm.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2riergdsp.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2sxccdvzy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwtwlia.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjpkvmp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2cajvjeve.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgepnguu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmshzen.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnwvdac.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2yuygcbya.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbzxlbu.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gxijuwxd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kectoqik.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2owfzegel.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvrghjm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hvihnxol.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxcrcbv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwccqym.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgbvunj.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2osfztbig.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2nkyagkug.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2derrjvnc.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmgdnwq.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qydetfsf.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxwcbew.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsgvcrx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgoqmxxv.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmyqxoc.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uglaqqep.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2viixtbqy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjdekbt.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdkwcrp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rwemsuew.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zurxfywk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cthjtigc.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkvkhjw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kckxtyuv.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmlaqrr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ockvkjxm.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvmlfze.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2igjsjrki.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2icagzoiu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tufmpoah.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2akkyghjw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpewdtq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzkqxtz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzqebgt.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxohdjx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqhptws.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqbwymt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbokknw.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sfggotvg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvgzndm.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyffpfe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtrtouo.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2dipzwkjf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttastmwg.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mfiscqbt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2skqpilku.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjrftja.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvyxzzb.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkskwxev.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkxjaym.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2loluxqqp.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxndxzxl.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmkljfe.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdenvqh.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uiayyrsj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2djwvodxp.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gclaqbbr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sepdooey.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpvlibp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rchktsrd.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rybhdpqv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdbnrrw.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgjhxrf.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2baqkofve.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2fgoznsdj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2mqizhtos.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwucvyyk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2klafoddr.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvxnsac.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2kvthibxf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2acpxooiv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emlwyzgp.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jikssabx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfpftzj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdsidhz.html


<!-- 参考信息 -->