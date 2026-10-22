代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2oztgrpaj.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgsjnbc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmkljam.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyxddfv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2efezuxbk.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2oimkdqwi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2oaamcemj.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcpsamn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2svvjckte.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2wecxgaxx.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2jclnvedn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpkxbbs.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmojjwp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2xshmtacx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jiubnzen.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2drdmpibm.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2newvkxbg.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jlonyzfg.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iszakaef.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkrsrll.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpluxtot.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrvnioh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrrjhri.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2peujmbdt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpmgtef.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrksrsg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhgpzfq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2clwdkyop.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgwesof.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2stfugfih.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2zeczbbbc.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2onhxxgut.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdltwyia.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tstkfvpi.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvddxdi.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wxziqzrz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2troywqcm.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzsrdso.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuihulmr.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnvaipu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2phntlvuv.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlmlyfo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsodigge.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqxwnoq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsulfcll.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlzwzth.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2amovcerv.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2snjpaafd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2muxbikmg.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vyeeympy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxovqfi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvksaux.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwodypt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2basokfgl.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2advnvjah.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnzehdb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2rdylfugx.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqfzctk.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpcvgkp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2devjhann.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tckoejhs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2twfbahcb.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxkjatw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnssreg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2gntpilyq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcvuzvu.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pizghbdv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjsuedr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sohdvlni.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivifveyn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2cscqornf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rkskbtuc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrrbyak.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuasorh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzmrsnt.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbelyay.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2mfosxqyr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtilkgne.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xeepxfrg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnctgqu.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2honabptv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbayijwh.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xdssyelx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqoiwjly.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgkamyh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vipcvjhr.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvcgohd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuzfhso.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvezjbo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlwckzu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2skfqodrk.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2sumuplxz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrvsfnk.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2visfosdt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2abflqlgr.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkkpica.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpahlhrq.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2voexjaln.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbpaaod.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqwgmfa.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqpsplo.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjoatrv.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2gflgtahr.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqsavnz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2witmdyhd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijquiujw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqrtsga.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpkqvih.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuucjjm.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2htybqwir.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtvxnih.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2epcwwlgg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxldliny.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdtbvgm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2otozswbg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvrwfgo.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ktapaaub.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2anqcqdlf.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2szfffkki.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2apkhkmad.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dksajzep.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvvntna.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hwppffga.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2opkockvq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mjysbusi.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2indbymvu.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrzapxk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2dflwqhpi.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2yylfpodx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxedhtk.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2oktbxtbj.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxshdgh.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuxxahn.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtefdpf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2fcffdbip.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pauykgko.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aartolnx.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qrljrqeq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2etlixmte.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxpeuwb.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zppkskmx.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2giskogqq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfgswdp.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gxphxxxp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2unyvukbr.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhqwnau.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2brezgjzk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2gysrnimg.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzciowl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2uivgssrv.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2gzakdpsz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqftcsf.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yklnvqyf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2gkclhztw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmwqcpt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2kczaxlxd.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhwhpqy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ampglqnk.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vovvpppb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2akcamujv.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxdwxqz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxirjhv.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvcekrx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2atifbucb.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqrmijq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzjnfys.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvtcydh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzwotyg.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmcentl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zdstnatd.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jxoxlyoa.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzjvvjp.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtydjsn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2miwsaqua.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvffrnak.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pamsucdv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rqixgauc.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vejmumyu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyqrbzx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lulygosx.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mntpnppc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqqzlpb.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvduyvw.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfjqgbt.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zwofbufe.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2smqgpnfr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2byrzsebe.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cempgcfx.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2izqmbogn.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ruykcnfe.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcnkwav.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2clavljmk.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvnyvki.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2weyeoqtw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zerflufp.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2clhavlnj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bcafzdub.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lygvxpar.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2urkgtwal.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhauojb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hasfrynj.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2plsxzoql.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2avjpwbbv.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjdptaa.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbqwxpt.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhshpnoy.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hoaiayof.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dthtphyx.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhfbwie.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pomrbmki.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqfwfdq.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jezejgrl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcarrgy.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2sezshrhc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjdhcgp.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wspmfulf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cdizfpcs.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mliczdyq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2citgwhsm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2smsqyxxz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2koeuvemv.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2aabyrser.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2quujpdnt.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ypeaowiq.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlgjnhl.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbyfxwv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlhdlpa.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2irifjmhd.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygatckcr.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2pulaxgcz.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsoplgp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkjmxet.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsrdgbw.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfkfhmq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zazxugwy.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2rfymgtvh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2azekwdqb.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ocklzehf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgrfgto.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjmivqi.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2yptkwfdg.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hexkisvx.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ywizapmy.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtwrvqi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bbswernl.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvriymt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2nyihdgbo.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrjwbyv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmohxyl.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vuaeoazz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtfdoer.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsamojx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2vnonuewp.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2frjdjiwr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2eqffwuel.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcnujlo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyvndfw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pwofxasv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcnommm.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xchoyven.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2okqtefsf.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ajoksnhx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsuzzmu.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ichmxkue.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrpghsc.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zckarrxj.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2avtzvozb.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpdhcye.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ozawjtmk.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2luomkzrc.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2omyodlgf.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bafstmsq.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2swmwwwmr.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kxechlrg.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgbbkay.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ottdfady.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqmimdb.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2owahqkju.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqryetc.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtogbvy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlnmxjd.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wexndtyg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqknvkm.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tlglpxhx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2sissjiag.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcahcni.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrujtnr.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2fdchvopd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdahvjb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2vontwxjc.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2adgabsmg.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rylwbvgc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkthxpk.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfeywms.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrexikt.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgyustm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2aklaginn.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2orlvoyzl.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvajnno.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbkwlti.html


<!-- 参考信息 -->