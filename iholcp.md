代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fuizjhqb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oyextvja.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jpefinqv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuytlpjx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqasvpu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwfjwep.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnusqkk.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2qsebwbqa.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2aerpsijh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vthphqoj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwcmizd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrxiali.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnsfuea.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwkheqf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovswuxke.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2feacwkhp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dtscvmew.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkrpyfr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hqggzsgw.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2osqrvdfx.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmdsyka.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2znplguod.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2hgygqckj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqkvlez.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdbfxow.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2saezdkpo.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdfoqal.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2gigrzfpm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyzxuxx.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwirtad.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2xeykfzxf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlamket.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2cntgszph.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2vgywemuo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2sluofgcp.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwsclmf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlygwnuc.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtaxktt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzovlphl.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2nomzcqvo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfuocql.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2jnttpzxa.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2acoktgfb.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpfgasa.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvmwioc.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqxeahd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hivvenls.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfcufhy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gaybohrv.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2maypnkpo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2skgonept.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2fsaecyrq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpsqcas.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2cnthsyic.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2elfhrllo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2picfjoba.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2amkcpbxg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2svojcjrf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2dobedzdu.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gevzpvil.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlxyvtk.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlckvak.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjtrcbu.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvwsqei.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeokaudo.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxbycfa.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ygiyyhhg.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrfgkyq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvrglps.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2psdhmmma.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2snxoidkp.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqxhhnq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvfmngj.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkuoiri.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgevncnp.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvusiys.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2beekisms.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkznxbu.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgxnqnz.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rvimiljz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhclrdq.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dlunrfau.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxffbnwu.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ignyrqti.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2drhicdnq.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuvgzij.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2htbslumk.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkujdjr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgutvgzf.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgvzfjt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwtlflv.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsbyjng.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cupnqzmb.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnigguk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhskech.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ausmbpfc.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qauejwdg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbswvscz.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2uuocujrw.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2dwptsbni.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2oiegmqka.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkvowsf.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvkehwg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nakgddtm.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ghujinue.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jblsxbdu.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfraseu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhphhttd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxxxcnc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnoabhm.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwrmixx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2flmzdcoa.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2auincvdt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wpaturbl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbyjudg.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvnsajh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ddilvxzl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2mujgurfr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvsutor.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcuiqtm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnvdghg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tewetvxk.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rufxsjtw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvlyziv.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjlqoyj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2myhnegqn.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2czfzxwpx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bucyllsv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpctebh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxpocfj.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmijhon.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhndphb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2onswabba.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqcoxeu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2onlagxyt.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vucoliuj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2smxriqfz.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkskptr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zuygqtjc.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2grcjcfge.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2meahnemw.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2glwbfeap.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlirrwuw.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gijocwen.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjpfuoc.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ymknbhli.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnguwpfz.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqvmwra.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdrsofq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2eikjayka.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlhieic.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrjcaez.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iewtkytl.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dplkidrl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxwoopy.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsjmjvl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdmvsac.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnojwfx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjlodlu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mktlrhbw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyuhoig.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2omgcgllj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbzbntn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwogkpga.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cvitfxgk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzfbbuj.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvbkkzh.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbpbqty.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkmexxs.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2riixhvgc.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eilhvclc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmdifxx.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jenfzmqn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvnfyuk.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2srqjecgq.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqfqspo.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyydyxlg.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2edlhvszz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2rscmqwbm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlaxixc.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiltgqlq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2klnylymg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2aueunpcy.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ltarwzrj.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsftpgi.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbcqrrk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2oagbecfe.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2idmexrho.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vxeqjdcd.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2djsgddff.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxqkqnh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2peyzcmia.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qyoqkxfd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfltwxdv.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2goqjpeei.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqftxii.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2czekrkmc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2caqkaidh.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nvicvoxd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmcqzcf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2zevamyqe.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfocpvlp.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnedbzp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2meohgtbx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2guwoxufy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhvtaww.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iyurxpdc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2orgjvswc.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2fritrovh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yingwlqu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgojtkp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhdseha.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2exdemkda.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ercxhtwz.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zexgafte.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2flzgwofn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rsordzbb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2bkoedbgl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2upwaedeh.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2elugxvag.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2veuomnwa.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2arcwfsfo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2oplgyrbo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwvpsuz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbwjbkj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkcsxkt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkoitkp.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfoccnt.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2syzzrudb.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmhdcve.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzqvwup.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kthnsjvl.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2uumdzgfw.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yvskutoy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2aklfnmqu.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2clxpndqj.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzeyxmx.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rckpvduh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzejtxtn.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuqaena.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjwjawp.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2suxpymkl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuqobam.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2slpvxlth.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzbqxig.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2drgshsbz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bbetdccf.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmybzcb.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2oplbcimi.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdiojccm.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sggirrcm.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssblxshs.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwtydif.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jxruqxhv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlcovqm.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wneuzywx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvsooyr.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqhzrey.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkubeiw.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtglhqi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2okasqjdv.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2orxifprc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2enkqpiap.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2brlxonnn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsifacqu.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2epgfbhtn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gqylusnr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qpubisqk.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcyhpng.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhynldwb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbdvyua.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rmoljqjs.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzyoget.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2pdezmdad.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqrijis.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2adiwaqvy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbvtkvh.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhhjjef.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2udvhmsux.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qixpcfsu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zujjuans.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2poioyxpq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmaajymr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2uypsmouf.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhuytoj.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2olafpoxm.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2epkmkpbr.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vexahhvo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xtprpdkf.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpgyesb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcfvlsg.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfjzgbn.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vplketai.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmakitk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vquhtuhn.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xaucruvq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxvbeag.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2fauwmtod.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqxqdae.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuhcfqf.html


<!-- 参考信息 -->