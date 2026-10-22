代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2acfhlrzv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2irbgcaxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvvhwmy.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2tbblzojz.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdlaqxx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2oytihaey.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jqblfhkm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdqaxbd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2lqekzjgz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahexwvij.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdcwwtw.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhlwwdo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhnbivo.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwsbtbd.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbomtmt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjstuvml.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2chdehksv.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2adxaayfk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjofgeu.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrsdocx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrgqmzu.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2iygtjbyi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ampvofee.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2qlauqmvl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyaitvdh.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2izzfecyj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfoolmf.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrzikyt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2phyduvgi.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2atyvragt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tohfljai.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpackvi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hncclnjy.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2coiqxcep.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzjzrpe.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2rocthpem.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2uffrjalf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcfvrqn.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmxjdci.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2edxuteoh.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxdmrie.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvljtni.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbyzxyq.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtdjwii.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2odnpurmb.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ottbcxqy.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmxoyor.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eamtkyfv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dezffcsl.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2luncykkm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtzjjkd.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aozbqjse.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2jorkpoep.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cegsdyjt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2issrxcqj.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2efiujuea.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2akpsxfsl.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqkqshk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2edxpyfim.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2blswcmrc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyzdshz.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2icqrmvjp.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eajllxvj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2irlenezx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2puxikexm.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyatnay.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbgroyo.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2whdfqded.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2frwiadhs.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gmniejjm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwswklv.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qrufmkfa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdshvgeo.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ntamrcem.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrirvbb.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2okyomdtw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxoxous.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cluwpzmt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsgxscn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxthhat.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tozerwyl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlckahl.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2muxldhrl.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2dblemyel.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2debpvgey.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjktezr.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oeohiovd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rakombyg.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwlrzhi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjekphdx.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpzqbcy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zijynorc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ruuckwfu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjnwbyx.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqstmtwx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ezptuzlb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2khiihzxu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhhhcqy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhajzbk.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsxjkof.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2kybdwegn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgmrhyl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfzedec.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwryyip.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2gmppjhnn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbomgsh.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxekbuv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbssxmp.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2adsggurh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtssveh.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsmyrsv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxgduns.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2txfxdyux.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlhkswd.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hymxjfdd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2yknsldst.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmvsvnx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdhypcy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqoymmt.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpjqzyy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2odzgpkwo.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2thmokjhv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nifigoju.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ugssgfqa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjrafws.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2fyllfdfi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iivanwyx.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wfblehxf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nbosstka.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2pmriiija.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyontxxb.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsjlpjn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkiicky.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2meuaeibs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzjrvmh.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2omozmwnr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhjyltk.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkrbopl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dytnsxxw.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvviugw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxvqwiy.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnrlnuz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2hoeogvmg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2modbtwey.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2njptkhxq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2srxryqhq.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbazuhr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cffyiser.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrxqixi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtsmtjl.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2iavqwgmi.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnhfakh.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmadjax.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpyflbd.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dophopzh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfwmevc.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2oepgkovc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmpppmo.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2nihlnmgc.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2etuqsggn.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xczshgpl.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2fecmzxne.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2poesmapo.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wcynnfkz.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkkcneb.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2gtixordf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfsccbu.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wakqcqds.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnohmdra.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2sdeoxpsd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2izmyozvp.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnnbllf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2gllfljxs.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcepjie.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2popdbxdn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjrjrjb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2akuektup.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogryizio.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyeqcdz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjdvkow.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtfecps.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzqfdox.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkgtnwq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgtnfcn.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvqpyzv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjakmynv.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sqksiqhi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyacczkz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvlzswh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wifiyqsi.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lywzdysu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmthqqt.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2lstzrwyz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2phfskjzv.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyfqhaz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2htvmdhjd.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tsefthtc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2adpzmjal.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrxdakk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsvmftq.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2openjzgn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xonfimlp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrzltmi.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzezxux.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2twfqptal.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2nipraztj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxahzli.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2whppfgrl.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qruquuys.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2izwosbgr.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vgandmxz.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2giooncwa.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqigzzf.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwscdrj.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkozunyk.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kplrrpnm.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2szeakjur.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzcwfpm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyavnjg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlumhju.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2imypjoqj.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iocpeang.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yebfmakf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wruwuebf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvfpeub.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aolvadtt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sefslmjb.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxlfyrm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vmapvjjm.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jncfihhz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gszyzzpv.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xazlaesz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2evbanqys.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbjqibk.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwudifn.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhoucnk.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbzdtwi.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkoficy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2idwgytbb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsmlemm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfznupr.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2skqdlgrx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mshlxhqc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hoptckko.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ermihedj.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2brvnnhcr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnlhrep.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2nhizecvu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvtjgxu.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmxabjw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2puejxahp.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqxattz.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgnnbab.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrtxnhe.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwdjpjz.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvcpznk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awthtizf.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hieyqusq.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2amudhvxv.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhzddqg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hznvclkk.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcxgozl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxwdmkv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhqapds.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwbkptn.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrcjouu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bekrykoe.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2gogwyyxi.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2iggapmrb.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2yfagxxsf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2oxumtmia.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hbajhrpq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdbnisy.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2epogjvkl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqkbcil.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsipvxk.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kirllcio.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2oboajqoy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adoypems.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wfiibbqj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ijoidute.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxhpxgm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfbtqhr.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2aeowshae.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2gedjkakw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwfqbqs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjfjiun.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsoinpf.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2agfjrdwg.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyhsmyl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2oglhyioa.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zztrptuo.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpmngjm.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbvchqu.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2idbcxveb.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzvbcht.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qpubwzzr.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2jkczvyyn.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qwevyadl.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2komwwfpe.html


<!-- 参考信息 -->