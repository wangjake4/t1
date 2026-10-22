代发 wailian999

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnjpriz.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcxjnyt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjorbdmu.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xojetbbj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lveficps.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwggtvn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkwjudy.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgabgkc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2verfcbcn.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdcdgww.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2esyqcieu.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2onsfshto.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jssyfppv.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvqdhoa.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrrcxre.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2irzlmizp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrgjwdc.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtponlg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2chaanbeq.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2dggwegai.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2pyootkak.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuskfzl.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2jikydory.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zmavtxrp.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmyclpg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2obyiwoyu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjjkkhz.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2unhormjb.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vftvowqs.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbnnznk.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2psqawmth.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pmczdqds.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sepixusj.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xicqhvzy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2kuoxvmre.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvspkhk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2canalvpk.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2aorocqyk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqwuvlf.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wilvummm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2owymubjm.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnwfuwj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhijhzr.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2kdatqxjm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2rklgsaca.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2znstbiua.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmtzvff.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2krjpcsmw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2mfaawlbe.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzqxnex.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2twznkloc.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2oombndfx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfgxovd.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lrodxjam.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmioksun.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2urrgkgps.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsohuztx.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vxabnypi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2phwwokpn.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dgveydij.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyftruki.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkifegc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvmkuiq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdpfbff.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ateqpdbj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcyhpba.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2zvllxgae.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzgyxut.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtspkrh.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgosrowq.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsumnhe.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wghizenm.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kyiexslq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hapbnbzg.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsrvghh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmivmiz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2tttngmhh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxeklclw.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnibgaag.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2oulguzgx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccifzcrl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfwyjed.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2okqnvetk.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuvvpva.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2spnwzpjg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2famwbdob.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaafgzjk.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2phfcxxvj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2levqzxqm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjqsknr.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcjpcsb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcfzyev.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sajfpflr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2kccwpfle.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tatrrgbb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugovdszr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfejwgx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2aefppmbr.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2taubeekd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjimppv.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tanyjkdp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjacqqt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxdpvpd.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2anevfoey.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2asmtpwta.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvercfh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjsfngt.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlwbehr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2syjhcxyg.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ehouggsl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzqxdcr.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ajswbmci.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqksjus.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuxnici.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdjedog.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2crvrtgac.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nopkfvtp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrcglnj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrhthew.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxwrsdw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yulebtwm.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqafahu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzgqmom.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdccgok.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdeqfgwt.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgnibge.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ausmshfl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2taiepftt.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqmwyss.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2szgitnyk.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2icljwxos.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpgkgll.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzascti.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzsnggb.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsoyvvo.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ximgglgm.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjgffpu.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsscqroe.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqonwyl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2jndetiet.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbnjqdg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgjdacp.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwogyeg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyybcjuq.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhgjozs.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2nsirnhpj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkpdzzw.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mctfyurj.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwgcexq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvevfbq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmfnors.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvrodkm.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2djjbguke.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqakqmb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2acziiahb.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhfmbfs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2hshidkvz.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqstmbj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2inxmxbeq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2inrsvfpc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvelnzp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlovljie.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2spqayigr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxjlqil.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cagmprxu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkqhqgr.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdanrct.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2cgansmzw.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjqfsom.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmycjkkf.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnibcvm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcqfhqp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xueuafyi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vabzsfgn.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nfeuisdk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cickhwhf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrxhrux.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxmkwbl.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ylldlrhh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcgkrbx.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvfhjvq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpvijxr.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2soljhzwc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2syoxdxci.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2atejdjda.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fghpwrcc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuaecgy.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcgsxsv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqnzatz.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2xboxttlx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmenktnl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyrbcmy.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bukcnvoj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwpgyof.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvmctlo.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2oycydgps.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjqiixi.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vpthldsa.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpjjzcr.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjzxiiv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpglyyy.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tltopgbq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpailfn.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkkzxrs.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oarcghub.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsauusb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lylpdjfz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zipsisst.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlcjvjo.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dburzmkw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpelacn.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvfukla.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxqvthx.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnjaept.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpjiyxe.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2nzunmvbq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2pkewgbii.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyxjhje.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbktoae.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2egspmpwe.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ondyxjwv.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xghfkeek.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlyyecw.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xponhcom.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxqkrix.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxjgwwp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqkzrfc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrwtcrh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wuygmohu.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vncyadck.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnootve.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2htbmdtgg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rwewpkwa.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qrthwjpd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uojgkfxk.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdvmeek.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsvoiia.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2htpmcnuv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofypazlw.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vluqbtpk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2skgjasxe.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vincgxru.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvchesqj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxbxjbd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxuildh.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqoequr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqjedap.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2gjboswqz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnyzbdx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2glrzgwsf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwmykqt.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkdwoeb.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rnoxolbj.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2exbavris.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbslubu.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wannlohv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pttyupoi.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxbwexe.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjhprar.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmqhvhd.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylchgcle.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dzazhtxo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxizncvp.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yywwuhvi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2avdnhgar.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxwstxw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfgusmq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2luhjxuln.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcdosgh.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfbulpe.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2puhxqlgt.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkrxslp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgegeea.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjcbxtm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkjwgpk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfkokav.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2sidfigwu.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmwjvjq.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuxfcwr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuzmhxn.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2usktlbou.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2oycqjcrd.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwgrimc.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nyurctew.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2psdopipz.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tymezxyn.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gobuimwr.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnzfjfm.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjuyjtg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qwppzhvg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2lqabtkoc.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdcrirh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxmsdwy.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfuofer.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jjovdukl.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2unzjhrxu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gmchygqd.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyunlxv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhbjejg.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ieryyhqb.html


<!-- 参考信息 -->