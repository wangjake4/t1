代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2rjykywas.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjazyvyu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkoezyh.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lgaqvgjy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwhpvhl.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbqfyez.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2frofygtg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpfyoyh.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxcdgpz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2habiwbnh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2adlhnfgy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpnswff.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtnzjja.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2erjwgbpw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vqknnbzt.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2nremfyre.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxguqxyv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2irdyxxce.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhlleic.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhtxptb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzlqtyd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbazdbi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucolikau.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2sfblfcnp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yecptedf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2scefezmp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lisdimmz.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2itdcznst.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2obvpwjau.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvvfmio.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tashiawf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqboriy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2klqclpae.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrurkis.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2tuiulelp.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxlzaeo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xapdwrvq.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2eppbxhkn.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcmufmt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2rywafeqt.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvmyppy.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdevkot.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxyfbtp.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qynrhbht.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqedlima.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwvhfet.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgekyoz.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrzgcux.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxokzxtq.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2spvcbpch.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2obqieykz.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qgasxsqo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2adsqxegs.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdtiaad.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqlcfcu.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkmuequ.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnalzqi.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ghyxilps.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cysqvyra.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkilprl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjwjddm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2oucluqgj.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgumbjt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfadsgu.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2otonaoes.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvbwzzt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqprfaf.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wuleyfvr.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajawgdjd.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuzvgih.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzislchs.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ycupphvx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwlphbu.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mliioahl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxxytat.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wdacfews.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2iihrksid.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwfujkw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfelloi.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2toaorwxb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2udkhxyge.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdgksdy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2xclvsfyb.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuzcbqc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfaexgkq.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jcddhepv.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvaxxlv.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcpvfpv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfifssl.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2blvpxbcq.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbecxas.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgasvrt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2acimwaix.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nhripsrf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvqfvsm.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkldpni.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxczazdu.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gtogykqe.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhoehdgi.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2smixaoal.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hknflcli.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nalynfbr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qibyrmdi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2wannlicw.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2amsoqkzc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfxhrai.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2eeifdinx.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2avytmozo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2tzoltcfh.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsizvdma.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ohurlkys.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2akingxef.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2idqmmtjf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2phwzfkmo.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yqntuauu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2maqfgnuh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtkglug.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnjradr.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ceasuyjy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2bhprtmst.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cexfbshf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnegppzu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtdfzhf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjzupxw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgzvymd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2olwarsft.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewggsnar.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fynqjkdq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2sdflljbm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2annvirho.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uocjxzwm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrpnium.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uktgzxpa.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdojasnz.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuparaw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2clubusld.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwbvfse.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2smneozji.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsnvvse.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2sohfybia.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iarmapbi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2eofpaixu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsyuzyd.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzbaelg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2flzswpga.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwqgwwv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ygoeqxwa.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jducbdoi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2diwswqvt.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhywsef.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqlpqgm.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqzqfvd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wqoudxtb.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ektixrfl.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqspqbdq.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvsyopq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxdeezw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kximqzcy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgccdjhl.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fibrsbap.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2isbjmljz.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdqnqds.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxjkneg.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2siduwujo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvktbiu.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kszonmdt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwavthg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2goituamd.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dantypay.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mibpafge.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2npjrqbrn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzikils.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzzqfmi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzsyyge.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjqvoym.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2geydqggm.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpfbtdr.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjgenqb.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nobyxxjx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2whcxwwep.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdixlqd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjddjrw.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2mevnyhty.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2amdhvvet.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2shrbmnur.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2zwscksdq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2rjguqloh.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2yhculugu.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2acuibppr.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjclikw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2esgibvky.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2unpoiqlu.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxrehfw.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ubapaomw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjrfscj.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sidxqhuu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2mdeqrjti.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrawzzn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tooazppu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2wgljlnal.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kinkzrly.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqquhfmu.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnsxwfi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2tmadipyd.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tfykqsun.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ltljeqjl.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnhfuid.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2kjeaqfiw.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2upjgjxvi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxgtlxs.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yehlumxm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2orqcabvl.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cccmpqgb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wulvpdta.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ihojbchb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmikkjxv.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2nybfzjgm.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmouxei.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2kepoipmx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2arjinwwe.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmfjrhr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcoumxb.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gamvpmiw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2muywaplh.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqumgaai.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2dikpcihx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwyqzol.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tkapyhwv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vupylywl.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2pwiwimbs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvsgsjg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gexinfzl.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jikjxmrj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2odnocjkj.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2arqcowqc.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2mckvaosp.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2pjabsopo.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jkuuolfy.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tofqtwsi.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsvqvna.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2keyfdnlz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2usbgyohf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2cesdxgox.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvyoevo.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzoxcyu.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dfznqxrh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpfkxcx.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2otmggjzr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xqipzgnz.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfosbmb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2spdbdcha.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mmeaevbg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpkyhxe.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjipekv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrsbzbs.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhdhszt.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2thutrsnl.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzfkozu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nddqrhtu.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfjgexh.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2jqaovamf.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aicmexwj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtoqkna.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2abpiutmo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wezyxmzi.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrgmaml.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2genwpvua.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aphcaoje.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zhoifanw.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkuguay.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2anuaowej.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2atlzncif.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgtnoxz.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2eafrqdgy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jroruodb.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2buokmhpd.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qvescvxt.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdmcmdi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsssduy.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zaslovqc.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2clznzraq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lonfkspg.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjupejf.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fadbyern.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dalpyrdx.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqtwuvt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2flypyhzd.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjhhjdj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwylrun.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcobnjz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2kivpxjcg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlknjoe.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxaxnvt.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2utvdlvkb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzlodmc.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcoyxys.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvbgemn.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnsjixx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2llkardpg.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dajjqpso.html


<!-- 参考信息 -->