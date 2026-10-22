代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2knhrrswd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2taaciahl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjqavqe.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhmhlkd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2bzobdfym.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcncmdw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dznedtrt.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2piulqojp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2btuprpvh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjpsxtb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2xedepoph.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwydyzdb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2csxbntvy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtvwzps.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqtgqol.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ronzhxro.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvdjtyn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrfzlkc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ecechyob.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2zjaqyree.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdkywhr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhedozv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdiujtw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbmnyjo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2csyzyvzg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2bltbosfr.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgowddt.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdjowwk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxyqtrk.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2nlacahbg.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2mlixrmfc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgagapgw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2degezugh.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2seribqec.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2eflwbblr.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lydkksvl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynchvbgu.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqrvlmt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yntwkmal.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2kirdpbme.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvkbmhh.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2gahyyrdq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrdnugy.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ievkcheq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2glcmgsjd.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cowncijw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2puuetsae.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqzgivk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2prkosmny.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrbeolt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzjgyfs.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2kawcabyi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzchyqj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2uoexfgpg.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2fknzzmok.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vghadlse.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvupsco.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcssank.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgswhtfa.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrwkpkl.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyqdcum.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2uebcqwor.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eterkvog.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2emqzhvip.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqlcmjs.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gawyayfn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhrvxwz.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2acmjiadl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2scbvyetj.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdpluvq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqqwjgs.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hplrrjhv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuqatxs.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bszybpoy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqmhzmg.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2hguqkvzz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2yocbinxb.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxakezs.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqlctrc.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfdsdzj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2rflszevo.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cazakkla.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oanlrfpn.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyjblaa.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uidgfsky.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkyftfr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhqlobc.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbpxicg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjqtuib.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qncirvpf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqjgzvy.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2whgpahbq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fppujjsn.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlcdepa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydifygms.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2vzujjsfp.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yzethwsb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnqdrhy.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2haqwczfd.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfbpvrk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnbzimk.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxaecjj.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yugxifwy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2diafkcvu.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmatogp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2brnrxzry.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xyyppxrj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxvgxjb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2dklfppvg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqwskhs.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbczcpzx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vcizpinc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmdpxge.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnubuoxk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxiozyo.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2spxkudim.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvkqqjk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2geffbnub.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2macmondv.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kncwhwik.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwugyya.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyqirxf.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xassumpe.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2qimxkyii.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyoxypv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2fluwxivz.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qnattthk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtncnyny.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eswhhnly.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqesbomo.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwrtqto.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2iaemsrjj.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xieplhwg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhpchxx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2opzirect.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lizhqnit.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfnvgoj.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjfyjiw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqkfzmd.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2srzmorxl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdxssjg.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcdnwtg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2otysihzo.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmrwxrg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsuzugp.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnbxkkl.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhnrpwe.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rovhrfdx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlxnebz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fctemuqm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbligcy.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlsybzt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaszwqyk.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tltyrdwe.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2saucmiyk.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlxfdsu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsweffhi.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gwievrig.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ryffersv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2okdtkzwg.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vumnsxdi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukipaoea.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwyupou.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrxbwrd.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cffyuses.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2twrxsvtb.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eehjdjov.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdazwvm.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2egnnrdqb.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqrpxuj.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2joatuljm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxtvlhw.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjimwxn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ootsoimj.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2eqojlsly.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wygamywk.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxxekcx.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqsphjn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrhdjfa.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2qmotlkxk.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmblefyt.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhbacnw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2szzzexgz.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jjecdpcm.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxqytgy.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2zczqkyly.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdzjfst.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqibhrx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2lefbhwsw.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zitrucxo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvdjlmh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2numqyvza.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzhlwfn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbfhosm.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxmpyyn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlvashr.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yinzllaw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2vplubrks.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2laetkrxg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2uieotlkm.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxboogv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzdfrhq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnrpvtr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zliyjfna.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vvogaonu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgdecej.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwhuhxt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2slehseki.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2hnozuvdo.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrttdrm.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2lljfallx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixshepxq.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxfwcpz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2svskyinp.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjybtqf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvufhbz.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2khgkapqi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2beivbcnb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aetfqwty.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzwaxdz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gawmdxbw.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2kagjalap.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nijwlaum.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2frsykocb.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2krlwpwgy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvsmfml.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyxsolv.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsosvkp.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuxvplr.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxtqdqt.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vckamezs.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kxiyicwe.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbazwmj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdgchdu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2leaholce.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2londoerc.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsydcuc.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzgtykx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fenahjav.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnnlvif.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ynneukaa.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcktyim.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxbqhuq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrixltl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2buyrrffj.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2efqisbpi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwxsutk.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgempxq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2jigijzed.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnozlkg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybaolbfx.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uruxqdkh.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuodgez.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qweenhtx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xrijynmt.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwxkwfv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nslpvnnb.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlghydi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cujqbvve.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzswshm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jauowpkp.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrqroya.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uovoywxv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2gutnyqcv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrsafnv.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2prirczyb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dsotoqdz.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2npelgsgn.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vprrundq.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuhqsnj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbzvbds.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2saghlodl.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmxgenv.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2caifxbwe.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqourel.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2unoptwns.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2exkpvwcl.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ctktjdwq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbzburz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2lwiwwyfq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpezjmc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxpyrnl.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehntyvly.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrlrzou.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjoxasr.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2sscqtqoy.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2usuwheit.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnmpbhw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vyeilcnf.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuxxcso.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqafwnkh.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2feceslgr.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lixggrxb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2neittley.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqzfred.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kldxbvtv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wlejihby.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2clmlvrdp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtbtvnf.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2glwajgej.html


<!-- 参考信息 -->