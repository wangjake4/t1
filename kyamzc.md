代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hezdjiyr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhisqrg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxqatoo.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpknekr.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsfsoni.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyqeamh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ubifeytw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2zliyrzao.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrvigaq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbhvvde.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxgqrmg.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2fsohudzz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlywjaj.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2hqionbsp.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbuefwg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2qojqcfir.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2glvcfmtz.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2youqjwze.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzondzvt.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2elkycump.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjtmxxl.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ntikyhdi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdglwzx.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2mfffhmub.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuynypwn.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2wynhhdtt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iydzdirg.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgllmaa.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bglnwzpq.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcshzqg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiiypodw.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkoirjy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2klsvmxvd.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2negekgya.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfwoaxm.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2uxthhqib.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcwochz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2vikpjdzl.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2oulsqbxc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2innmtipm.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzckipgz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfoiksv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzundfv.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnasbrx.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvpwprf.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qystkdwh.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnwaqgq.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pstdhouu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfvfkpb.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2knbxeftf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2tejnkexq.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rubnlmsh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdxzokj.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2apahzedu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyitniwv.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xurdhkyi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxdubdu.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uordtwgo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2alcxelhl.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2smhxqqgv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcbloiq.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fewradje.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmgyalb.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hijlnnps.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2eodbtsha.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tadmnuef.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmminxms.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2oejrpuhl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlhflik.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2snlfwabe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnooxig.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ixehlaid.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyecdipk.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnconpg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2brmykmte.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nonquuwd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxghtrai.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2glvqxkov.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsdsjyu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqacqdy.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pbevjoub.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2oopbimhz.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2jonfigsg.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2bpudazvm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2udnmmclh.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2edjnqjng.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jomubhto.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuwlddy.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxcbvpk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kptrixmy.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wabttbkp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhemywph.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzocsss.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzgfkkw.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mysasybh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2lziccunm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgzkmnq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpypfmfr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqludwt.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gasmixrx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsuirrv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2udpzolwk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzezjao.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bpstvlnv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ecprsrwn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsxiolt.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlqbilw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vueismfz.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2actmatiy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2prxwlrux.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bikrmpwh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxqyhhu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfiboit.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2kewsdcfa.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2deguvzin.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnbofhy.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2koawbezl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxegdlg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbodtye.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnnwjmu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpodmhv.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2eabehxuh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2eojxkrnf.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2esjqmmwt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2orhakaya.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhzdfrh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvkhour.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdwaejz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwobssw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvlnnmj.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqloytx.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhjdjyp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvsdwie.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyfrymi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqwrtnv.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2smdzfbvg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2thkgoogy.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkjagep.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovffkipg.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqsskgq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwsfljj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcwfgne.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zncsvjxq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtrbgzs.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmvcxhq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqqlquq.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2avwidkzo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2riiynfys.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjmmyei.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2hilgxfzl.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfmpazt.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2jokjuqqd.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2snnvrgin.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgomibq.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bilapopq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxbvean.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2endltddv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvifroqx.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2xwibazfn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzguiag.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnofzas.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhqjinc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzgelfp.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdtvsml.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkrltrn.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2crhbtozq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2eylunjbz.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhmjyeu.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2emlccrtn.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ejenrcou.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pezdzvxv.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rqohnjio.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfefubm.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2enedgfzl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqkkows.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2pmslsrzh.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wfntggyl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmechumt.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2owyztwdb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2rklhkmpt.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcyahoq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2inqlhsrw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nalgmjyv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhulwdw.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjlkpgl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgftyfjk.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xaikriuy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fywywzkh.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqodzou.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2twsvgtnt.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sjywckxz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxrjvlf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2covlzbuu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aavlfxcw.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmhsfck.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2fswqtumg.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzzrozy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwngitt.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wfivlxpa.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2phgvamof.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vouzusvf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfutilj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyaejplc.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpzmqys.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqatzsa.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2tkboibzl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbeyytsq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2adocimzn.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqjtnmb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2buuxgoen.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbelauq.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2jwuprzlz.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ldocinru.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qrknqmkp.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvckbuio.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2szgbhltf.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgetagn.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnauyxe.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwuruoct.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdkemdb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcewfjrt.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2snqikkpz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpjikmf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xghcuvhp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hszjnfkx.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzbmqwx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iimblvae.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfhbafr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kalnjvki.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzgzbdv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxrwelg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mwavtigj.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2icoiqjcj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uleanhvi.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnavoopl.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrzwgau.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2repwokmf.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pndvulnw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2itzkklnh.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2phtahjgd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxwzioz.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgzhxzi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2viiywzhc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gpoztmqq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2frjobqbu.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwlznuu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtzbmmo.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrrghcf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2enqkbnpl.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqdcdsb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlqvfib.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqbdiht.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wofcysnw.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2itdtkpqu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvafmwt.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2izzulmut.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vijgojkn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfeuffc.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqveduo.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqlyqrp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rmoguxcj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhlqldn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlofvkn.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2njjpbqqc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pfslrlcg.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlgclfd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2qenjccca.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2gafacduc.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpayjcw.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwvihmh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2vssbmmza.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eokhvfch.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hndskmar.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgcolsc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jplomztz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cmicpcog.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyypxauq.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmaswqk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciaybtzb.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbhtomv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlmahun.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2opsmfkeq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ampxcmoi.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2birbqfxf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnjhxxi.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qkytpftb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2lzstznub.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxhpzjv.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ettvriwp.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwqrxzg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2muqvxlgg.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vahcnecr.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lupnjfug.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvzqmht.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpnpljn.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mefepjix.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wwytagmc.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvbkemo.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkiozac.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wycrlrip.html


<!-- 参考信息 -->