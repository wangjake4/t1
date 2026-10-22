代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrohjor.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2qfailfky.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceifiktk.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2zkekejlb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzfhxwp.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2zreunjir.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpexwsw.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyrhklj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qddhtoyr.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhceihs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2cskvoebw.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfbmkfe.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2busrycom.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmawjsw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2oniwqtyx.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2slwrjxad.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvovslr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdgflka.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjifngy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nznaitdu.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2opkwagpl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxysxqc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyovlgz.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fsejhbjr.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2julkqzzs.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjvilep.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvqvcrb.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2caiufkbn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjbrdbl.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bepubfrc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2khosnnds.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfkllxf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwjvfun.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uknvtveb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbelzqtz.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxvnfny.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mekxasdf.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmnqsns.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxmfomz.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgxjhyo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaivonfz.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyhjmkb.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnkcypo.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nesutyww.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2msuojerz.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrkfgdb.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gedpqsev.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlegony.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2miyijjrl.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjqahzd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2runlmzzq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgnhlog.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdlbdng.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyflrqb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhelbeb.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfgpwhh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxgratj.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ldizquju.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2twozjfgt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2hdleidef.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtgqicl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qekkkbro.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtouapw.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2efouqdam.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2nphwwdkj.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2edybfxvo.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iaagwizh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqcmzxe.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgqnopk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmiegmz.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrhdlsl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyykmrbm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdyyuyz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbginqxi.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zklrsagf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvnaffp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkvvuzn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjjbsgh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xueoxplk.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hkazclei.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjlekbr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ilufugoj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxubzuzi.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwxjooj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2kusfoyvi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsrzggx.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qgknxbvd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxlmtuc.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eopyxvgt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2lojvjqdj.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrjmxcr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwiihdou.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwlsaah.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqftxnfq.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zbojteiy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrqtrev.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nbruuzdx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwqcfwy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykizcxqn.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgtidrt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhznxaj.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzrjbfp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kpghcvnf.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmdehvv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmpnidm.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2dghnatxm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxstpmy.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2uiifpvdw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjwqijf.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpgstbn.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlrojlp.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fswqkemu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2syiuekkt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2omvkcype.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbqrfae.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qceqltmm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxtbsle.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2anyyfmdd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dstbfuws.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwxdmug.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2glxwmhuj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwachxn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhmnkpn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjbshid.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2czgkrdgm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xaujtwtf.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzwpauc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdajxbqt.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpohnyh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwxmxrw.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhpanbk.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvpywrx.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyjsqii.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwcbqhc.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvurcbl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfixypg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwoxize.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbmwmnm.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2lbiznrhw.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwijbio.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjaugxur.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2fmglqptx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjxkokk.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgvvwsd.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdsrfti.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ryizcquo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2exmvtvbx.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2prvkpmpl.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtjdcmq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2amzvzddy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkkrkxf.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nqizvbko.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2lpymcpuq.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vknmkxja.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuomzhnq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrsoubx.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgbtifp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcbzplo.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfyfslr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2rvldgzgk.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zefaiknb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2etnbesnk.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ixysxqbs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2adyzffws.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2vpidgbhy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mssysqvv.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qruloadq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2glcvpyqa.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwmempx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ektzpzro.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2muihdhby.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcuhqiwn.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlgkict.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyymkidi.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2hubdruuy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfakqqtd.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqwekol.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jjoguekx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tehtqitx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhjyoqc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvwoptp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqctfhk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyzntxr.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2avrteeaw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wvoldssd.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2esrljavl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrsytls.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtyyzzv.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hggumzda.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jsncgsvd.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2akogthci.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfitbwy.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2youbywsn.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2krpyhlge.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxiozreo.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oleorknf.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbuedpn.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdzvism.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvcjeda.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvvknxe.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxdzeln.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aqahyefn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iumlkzed.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xjufasfx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ropxsihu.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vpobhgyp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpctoye.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2orrvdggu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2spytbowm.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zjynqwcy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gdaodguv.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2sskbjxbc.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmnlngz.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uauxzmem.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkflqpt.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2arzqjwpt.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwrdsvm.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlkrzkc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kecliyzg.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vilmqfuq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bddrnihg.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmqenbd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2thfvvcln.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqlntvh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bifhwtuc.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zbadhayc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnirhhq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2sstqjbqj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtchric.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gzovgqfz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjfbmtg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2esjodvrf.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pepoijsn.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2abghwnwa.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnownqtn.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvvylbp.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2csfxjlne.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmjmnne.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkpnkyz.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bbivylhx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmbzgrs.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mievjryv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrveipxa.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2sznquscj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsvcxzz.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwnhqmu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2kllnvnpn.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2akipdyyt.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2auubnbsz.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2fywixbyz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgknlyw.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qochuxlc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdadhdv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxecejc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyuaofn.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyttzpi.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfkdwuj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgaricf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjksvvrq.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwklkgv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2fdavaluc.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfnmzgj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlaptfp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2siilcsli.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgheenp.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcdvqmb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2eexpdaxp.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qypxgcfa.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvjwyoj.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcxypfb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdilbrx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2meihusvc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpnrfkw.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cynjpxjn.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfmnqyr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rtchjvnc.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbggspl.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2havpprjz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gqibskoi.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2phnbfjmy.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvbkptt.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hnifvkar.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnkbwty.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfumdld.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcurhay.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdytqpe.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2otwwqegq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjmxzbv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvbfjbk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ktepzraa.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lztgyyqz.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmrbwma.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nsircrkj.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hnljvjeq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcvvqmk.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2edhehlwh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2xnikctrl.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaililw.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2waelrore.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxytpdv.html


<!-- 参考信息 -->