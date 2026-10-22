代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrqqorj.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkpwogo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcxqjte.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qvihpavi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jovaogrd.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhknpiu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvpazql.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxcrdhz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2riwxpvho.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2akbxkvyj.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2cpflmqwi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvedhgc.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2opzqrdww.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2jngyynnj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqlbxmc.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfwmcvs.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvnzoll.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyfsufk.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mixdvsoh.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2knbmtoyy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcisihm.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgowngi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2hlihgjql.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgajlsd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyzzaik.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcyirwy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqntxnxh.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yotkrhlq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2atfwfqgy.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2prlkcmwd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqqvyjk.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ecijqeqn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhmiyro.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kuezheis.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqutxtl.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qftkecfm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjhjtma.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhvegkx.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2msmxoooc.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfzdnqb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwvkhus.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbcjjny.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmtmtfs.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2otcxlyir.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cimvobfb.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqrsgse.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2awfldwxb.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2svbxgpdn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gblctcko.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgnulyc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqjbqvj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2emcsywve.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhhmebz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2phbsixjk.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfnnysy.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ifolprpg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2fmamynly.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2knbhbvup.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmlkayy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuenqag.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrtzwem.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uamgrcpg.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpuqolu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jleqzpdk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhycfbci.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyunlbzf.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2toetizuy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwzccmj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzccdwdy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2hqngepau.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmlzdrd.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjniarb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2erjlgdjm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpgihff.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiewsprt.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ngegkaec.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfqnimp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjosnage.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ntphyghi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2crjczjiw.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gzffbkfb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxsbkns.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2crzvfaya.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfgeahj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqorqef.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcrnmgp.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tjroizgz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2seabbrih.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hahhegdw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkltpau.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyaqtura.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ubygfnmb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkilhiol.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sybqjiru.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2izupqswg.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqcqley.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2prrdfrxw.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2frwhxbjs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxirmua.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvidtsz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2naixmapf.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2bshsrplr.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvadvwd.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjpifqf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubavzyqv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmmxaiy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlueezh.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxgixnz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmlgfyf.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2evhckrhm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtufgrbw.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nicmzfuf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxibowlb.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkmzckv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2sowgbepr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrzthep.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ueofzeiz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2miiyhyvm.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyjisns.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2txsfgpnk.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2drkcussz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2dyinexbx.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmvngti.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2zggqwtzm.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2medgxpin.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnrmimg.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdevmui.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzngrll.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2esjykcdr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2rofkycfp.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkbkava.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiathwei.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrowofij.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2xuovnayk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdzqlda.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ikshdocz.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwyrizs.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hspftvac.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsimnyk.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rznnluex.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhidxeyj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvedqab.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdxatci.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lrktvvmg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsahila.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ponhjadd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzemhdog.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2lykngain.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2smqkzeep.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2toopprsa.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjdldem.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ewobhejj.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2eerkeiua.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyarptt.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xsovacld.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfnskfq.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhkzror.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2smmvvenr.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fejqiktr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqxdmur.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2byweturv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvubwkr.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqqhird.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2falinbfy.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzkwbwi.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hutiihag.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2pwztvmet.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxqbfvn.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqdkcwt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2eaaqxmta.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqomvcz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqptmkh.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhzmpdp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdlogwn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxixyeco.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjslmwo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2powxosnl.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkflzkl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvfgycd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgtsuez.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpcaxqa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxcfjjg.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2aviefufb.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2axdviffw.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2mafyudsq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2syhkmwuo.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwsyouj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkczhxs.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2qaexmgtr.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzgpazo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbspsvz.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gppnaydj.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wputqoco.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpjtpjz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fthjoyua.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmjilaw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pftmnfmj.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xujeyemv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2onvfyjuz.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqdldph.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2spnpmxlq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxcwxug.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxnuhsz.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrdpmyj.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2oavryrka.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiodvxyb.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtsovms.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2osmxbllh.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhjyodb.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2niqithhl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqcbxbf.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwrendk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbmqnfh.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2fevpguet.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2azbcbctl.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjiafnye.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hjharcwi.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkqiwdu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjgwhzt.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2uusilffw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnqgdfu.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtdjpqk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2afbeannb.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrblsgr.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgsxeqt.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjyaulj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydobgcuo.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uekahlgk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2udrhficn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmwzzbb.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2frcipnzo.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzpunzn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvucjel.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtzxycf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfvkvat.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmcelgt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eemrutab.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlkzowq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2hurahmmk.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgxrcpg.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2bubegsda.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2bsadotch.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnmhnrl.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yztrfvjy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zwspizha.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fndwfcez.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2odqzhgzo.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vwezwjii.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znthguow.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nfozkysh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcxzacc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwzzdgk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdtumsu.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqllgui.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jvynhqyg.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lpumoyez.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmscrvty.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdkiuzc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2htyztzzu.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2krvgccep.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nokilkil.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2hglrkzbh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2iycbmbpv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qkznsiko.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxglzmo.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgavcag.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjnqgdi.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kecpuxin.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2baptlixu.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ulexdvof.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgrujyv.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyzrjtb.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cepcxelz.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbmncct.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlritmr.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xchbgcvq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2qfepnwva.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2dyszewnh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsoasau.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxrpxid.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iqeouswz.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2idosakpy.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcvsudw.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbdyhuq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dayblgdr.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2upxxlkgr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vrojjkqc.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2enpgksca.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2htaleojt.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2yyshwhwr.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjwbspm.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxrcsul.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2prhlwcxk.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2srsohvzz.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uxptsaec.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2eikwovsj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2fyscqpti.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzfxqod.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzfpywc.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xokhcqgi.html


<!-- 参考信息 -->