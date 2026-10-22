代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmnrkpr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2brgpicep.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsobvlr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2taztadtd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2boklkfzs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ooswatui.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfjbmat.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlhvlta.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxmsxzs.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2udwzqrsh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnxvtgv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzunijri.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2viejaxqg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvwoeag.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2fufpifok.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsfhnee.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjlxiyu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcaodxs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhglwxkv.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrpokix.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrdmuuz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyxzbgm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2loungjez.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbdzeue.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgrrbqm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvarubeh.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ittgagfa.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2jhaoroow.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tyeafrkh.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmwmzqc.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2xqllfxye.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgxctry.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhywdimk.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2tclnqepz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbgzxxh.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrysgsd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpphoeo.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2qczrwckd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiquvevu.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpotcpx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzeyyxm.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2lkoiwmgr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2snojvhnf.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bilhfnyj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjwxlkc.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2orvxlqoq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnjibao.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2achxinad.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzkttiz.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2iolangaz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkkpnoh.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2lsurioos.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2mbphgjaz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmcejdg.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2icuzyyqd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2aerjyhkw.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhavyqs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvedpxg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvegnekd.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2awrtfuoq.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2znxrdozo.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbstufv.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdokrhb.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iokjjsue.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgiyzpb.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rveukswp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2aikcaame.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qugakkuv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfcmvwi.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2aawulyme.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wodflxjn.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2asovvkss.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rknsasmm.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pghrezyj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkretnii.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqjfapw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2inpjswgx.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2aibzwofr.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkaxvth.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdajvbk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzpmlts.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsllmig.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbeiazf.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2affutdnn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnbbquh.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2siyrjflz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2okafzott.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mybfrhsd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbmjhin.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2iknnbifz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbomshs.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqorvfo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvrsoin.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnypzsa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2niyeicvw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2osycrhcm.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxwcycy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkcejdd.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2xyoyhlvc.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2fcljptkj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2iipxlmho.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbymlmy.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrspssa.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjinjstl.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2deoinfdk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqhuoej.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aybrbyuu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rctsirgs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2oailyqzq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgmunfu.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzfibxq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyxepxd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oozxujfe.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjltjqs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bssmvphk.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cvboctkp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2gmttghwk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxrruew.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjjujfj.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2distftfg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkmbyer.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfivrzg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qvayxlep.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtbkhgg.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdntmns.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2whxmxevf.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpptweo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxinmdzr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkvpvlk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdfyxqm.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sfstduwt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbsagga.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eiisnsiw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2eklpxlsz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghehrwwi.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzxncap.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbeyiwz.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xytucwlt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nbybafag.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsiizav.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtdzida.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2topkioat.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozoadflh.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsmruad.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcredmc.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2fopwvygh.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhptvpi.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjlwdue.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtpmlvm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2negijeus.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2plzghojs.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbxlglq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrfsjyu.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tklrnmwm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2psopvgfx.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2uijqfuxm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wplggeii.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2stsxsoih.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2sxklkkmt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iawbcdmf.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2feaufenm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfbmmgj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwrrlkv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlbgkva.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhmyxzl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2xzupczve.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ecakvejk.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2piqpipjw.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rzakdusk.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjubwlk.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fslfoxie.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2idrqrldy.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2tgksajyn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2kilaetlh.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2yszgqyhi.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rptujibs.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcygqfj.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmsiqdz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwesazs.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2iegrqcwj.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2euifmxej.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdpnvji.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuzhufl.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhnorjj.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsduieiq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyniqfo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cidtaqmx.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxlkynl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2xzresefn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2neeuzmto.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqjbtlf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2lllkmutx.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkaxwtj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgnwutt.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnluztj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2osqfanqi.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxsbbsc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2wjraetgh.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ddivtcsi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxbcluq.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgoutss.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xywkulse.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dldbgdob.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wacvmsmm.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ufiqpfiy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbobrzrn.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkphbhl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqawnms.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2fecwdzrj.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyunnaow.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnwptjf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntobdwkz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtamdyi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2igrucjoy.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qulahgyy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2qokqksgs.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqowlkzx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbklnli.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2danucesl.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dniqatwx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2roekvcox.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2okpkeukq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwuicxh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kxncqwac.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvlinbf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2frxcdvzx.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ltambbkt.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmwtbmc.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vujzoylb.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2kentzywl.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqnleew.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zjejejbl.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxzqljt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmvwdgz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycshexhc.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fgorhesy.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofeeszkd.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kovqwvfh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmipddi.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ohezrmtl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gytiqmcv.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ambgwwps.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2azsmmrdp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rwytlrio.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jksahhgf.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gngwqwiq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzkfksu.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdspabo.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvhskuy.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjceqbbl.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yftrnoez.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hruwiydg.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkepcda.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mayxojvc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqbdmot.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wznovvzj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2awzahztc.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2lsygdxtg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qivfdutg.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqtqwzb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxatnxp.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2obclwtfe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vbediaws.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2orkfhldt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iigrddxe.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2udlqjisi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qywcurbz.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjsdafx.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mutptesk.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezklhvlf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqvhepd.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2atzhoiqq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdasjiso.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlazetw.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqrbase.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2beevxkae.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gwltzjim.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2owmnnsnf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqqdbxz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vujemuid.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhnyibc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrmngfj.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ecihdaey.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xplzxyxw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpdbtds.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2htvpwzbr.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2uamelroo.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2crugpgak.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uhklrnui.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2daehehdg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxrmivi.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2okjeiqba.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtuxpfl.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjqgzlz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuelrmxk.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2owxhgyyw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wefsxhvw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgzcupr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2keheiaqz.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcpbzrk.html


<!-- 参考信息 -->