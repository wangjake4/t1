代发 wailian999

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsnuask.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrjusro.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vvibyqck.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2dountfjg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2gcegqrwd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2rsffoqcu.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2awlicrhy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xeilivfy.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2sitnmbnv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2rnudraiu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfgukio.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgeauvw.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyndpeqj.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpyldve.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2clqlsbgo.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhpsghg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwosxhh.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ntifpkug.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2dstduklp.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgxvtaq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2feaccxxc.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjkgzid.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2czrvgpfx.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2saeqblqg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vebgwnwn.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgwgvmw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2sytwkpyy.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgskzec.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2otsmntgm.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kytdfqvx.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwspmosn.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2iegvoonh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2fctqfxsk.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2keyieaqs.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgctpdt.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hsybptpn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xddxbrco.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2budjtxkn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdszcxpn.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mefwqgaj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aubgpnjn.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2msncneyp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocufyhsm.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zovyxuzp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyshfljx.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqminhh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjrsrjs.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyjdodj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcwzmcn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbywtyn.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuxkztl.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2adfyoliw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2iuklrohl.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2itbxqgiv.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kiifupef.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hunwurdd.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fveditco.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjlkuyc.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnvepwt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jntykusv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxgycez.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2txwoydlo.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hyedxxyd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmnsaot.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qixpypqi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmexygo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsbobnb.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kriqujdw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2udebnsmd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2kinudzeq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgilmwo.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2syarqyhk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2bekethvq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkpobdn.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvzjyfx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyybdxok.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtrlmxn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2baykscvi.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2flxcfesz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2netmqisg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtuwydf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlnyjti.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmtliqf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdgogrl.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnxyhbu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2clcisbgz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2eupiakyw.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyhvwbo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgpyodd.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xokwxljk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnqbmiy.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrikedr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgpuogu.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsvqixg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2imfadxeo.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2apdakhvm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2iobhvwwv.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpaopyu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2xukkytbt.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2njmqxqjn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pficmnbh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjobgcqa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuokggj.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbjxxsa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2betzuphi.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnxzjwj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdaelov.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqnavin.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqjgrvg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nlccdrgp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2hauqcnhn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlywyijf.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jufqchzv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyosqtwj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvgtmgi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2goopeprc.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vxglzify.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjqzpdq.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qpupnqai.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgbaemq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlakfox.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmauizz.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bheqcxgs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxiwrzff.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2vteakyvo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcbwdrl.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2hyozgtyc.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqlnrvb.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxmbtwc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2krhfjrsc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2kelfebgl.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2yetrwovi.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kckuvfro.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2apcddglt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2huokgnkb.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2huuhbrzf.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvtysbp.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbjdzhq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnlqsej.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zlugdjoy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wgubhjfv.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nitydfyo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwaeppj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2kegpcosr.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2migbzcfz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqoqubly.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2zwadnqik.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsgtuwa.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpzudkq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ycomqnvj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lfediyuc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2aftlsrer.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbzdkuj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2youlnueb.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zivydfhr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzbncwq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbmqjut.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmzzvby.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lohlpofd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtbtwib.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2tqaruopy.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iucctiqk.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2lcldqeqe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgtmzah.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pfucypmc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2piwzmubd.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxftvgr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2qytgeqwe.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kirnsfwz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdpsqhz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jainpeas.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dmabijsz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbwdkil.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwypwbr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqthpdla.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2adzehvrz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2adwgmjoj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvxczsp.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwwuqca.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ityzqhvu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2mmiqczwu.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2gikmugsd.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvubtkj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ybexnqzd.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2upcogmzq.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jzounirw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2wledyymy.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhwdnlo.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gttcglzn.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wriazhpi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqnpqgd.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjovspci.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bcswarxx.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fkogwcpm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyqpdwg.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjoksfk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2izzpwlyy.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhtwsen.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2egrzagwx.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2iqybdinp.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2iubjowod.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbshywlx.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2oayxnosy.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2odictdgd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xseqsxdw.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfydcep.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2acnenziq.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjwfxln.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrydltv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2anvwtzsy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hdatphrs.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzmuvhv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2idudkgda.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fapkvnzf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eonuimgi.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xedqyjwb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uiofjzvv.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtollbe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ytynrgwl.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hixkfdqk.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqjgzmj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbjktkw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnigxzfr.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkzhywa.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2piamtykb.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2orbjezrp.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oykptcst.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hgobfmis.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfvsgxj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2szimblqa.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2viwodwiw.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vphahjuw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxxddrw.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oyenhwyb.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxggnoqp.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzimwjz.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rznsrfbg.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xdeharnw.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyymwfb.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2comckvle.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wcheeeff.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2axfbzhrx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmczwwfo.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcongtx.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bixmrwon.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2eeobshjq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnibwfir.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcnfupi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2uopqyztg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2slngroli.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsgygyz.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvquehb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqpaeoe.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzgqabh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2eytntalk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhtnbfo.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmreuop.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qdutveds.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2utpobrid.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzeafxi.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2boktguit.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzmajgw.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kzaztyeu.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dzikcrjz.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zcldugcb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2wvowfhdu.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ewoekunn.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lksgoyis.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxbmwxc.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hzolhclt.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bnewgiud.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnbvlpu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2htmujufl.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hokzaobn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbkqoml.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yezjzmcs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uarxjakd.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pidwzqoo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbztkzr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pvduayjp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqsqdrt.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzsvotq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2absptqbk.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqcduuf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2nxetdjbt.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2oiufoirb.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjjplma.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwbixjx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2algjnmlb.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2girdpoef.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjxtwzu.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2arbijdsg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2jafqumea.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2itillhkh.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyfgipu.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2piodccse.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgzwqiv.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvmbokx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2amcwelay.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqxrcuw.html


<!-- 参考信息 -->