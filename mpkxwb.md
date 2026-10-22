代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2feavmrof.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzwrjdv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxcncvw.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhkrsox.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlbzxry.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiavgrk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mtalqbus.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdqiykl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnaxpul.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2kejgjpiu.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvdsukv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2iklrnhkd.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2vyucaaaw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrotubb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyezhsu.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwdsyjl.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pysypeag.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kttnwbeh.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcikqht.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jkheohxg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsylact.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2echsprxm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2eogxogcg.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzwzmje.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsglphdm.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ewullhrt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzoxych.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jewfxztb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gejyikxf.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2faftiamh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2mchsmsgu.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzccxzo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvybyli.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2enucpuer.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xomdadle.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoglfpa.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqykfkm.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvyotiu.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmjkewj.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjdafth.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvnxgsz.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tlenpvol.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsemcnm.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2brrzdaol.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvmxnti.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cyakiuxo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzidtfus.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ilaipwcv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmofamu.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqqdjcn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyfbmrh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsvflmx.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhmpwkp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2msuiruhi.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2msqtphrt.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2btcciaxa.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2siurhiar.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkigtqu.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fqumxvyy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nskxwwtf.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jjuahghn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjthxmr.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqzfvwp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgztrvt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqmmfto.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoprimnq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzfsqdy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2amqfvhlz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2faljzymi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2aunaxqte.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2hixqxnje.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2peiufwdn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsrehvr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfplisf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2swusxqwy.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgyynqa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2btoilscu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcyjfhg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2npufsvak.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybufckyb.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2heulsqpm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2vczkbqfl.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfegyve.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkrarrg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2muyoduun.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xscjukfz.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvklplw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdjfrkc.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2skhntpda.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2kemgnurl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbjmuaw.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tpngjtyc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjlqwwy.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjlsrte.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zarvoqmo.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjaktyg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qekwolkh.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwhbttt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvcwnot.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2eadfosgb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yzanzbsm.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpqzxhu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2yogswqhf.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwunnap.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuanzsyv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgaejzk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2upnvqtns.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2brvnptpb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iixlwrsg.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2znlqygwe.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iibbpyxq.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2zbittlkj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvmtepl.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2waytfbpb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2nazqeywr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuwsihl.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvphpbg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhmsdrq.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyklpeb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpoowiqd.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tdphdoue.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcxfigx.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmshoou.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2obcsungn.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2seizuwor.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgfdzzb.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bilxmlwc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbecztlw.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2axdsvzvk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkhalpq.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2bztglksc.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpmmcru.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhtkhgb.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkfjrur.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyabaet.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ypryfvbg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjgvktg.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlwsnas.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkwclch.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvsrogc.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jktsqxui.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkcrgmt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fahshnfa.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzjltac.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqotytg.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2adbjopue.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yydvnqsj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2tjeeljna.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2krzqmnjr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijuomlyl.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqkbzan.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2mcirwbjj.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvzbesd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2narheudq.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nywnqcrm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqjvsys.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2gptgwezg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yygvsxtn.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ikeuvsbz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmuttzs.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ptewmxiu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2choxwerf.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmivhgl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgexxhgw.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkqbjxn.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2agygwxud.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiwwvdn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwucadoz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvetxgg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzafoau.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2osyvdczm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2imajihsn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrdfaht.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2hydkndmx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqrtusc.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhtfqtf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2khbnbvck.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzpivvp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvungtse.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exxucooj.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2scbsfcsy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqslmhv.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xardeheq.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdossos.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2hoeuxvqh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2uenvoopx.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2iaewxciu.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcloojt.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2pizzcvmk.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtwaolg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2wszbqqei.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ssozynjb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xstpvjkl.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fswktabf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxvxrds.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2smkqacob.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqdjvft.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lykvdsnv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2srjftyww.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzzrkyv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2irsbzfzq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2egbitaqn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yngzagie.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgldcxn.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2numvlzdm.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2odhctpte.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdxdhkk.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjztjzq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2dranzjtg.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljaaimtj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2auevcpqb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdlzyjx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxtoihp.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxlbidn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qerokzvn.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjaqhat.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdkiamo.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2agssoazb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vurmxljk.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqsrmft.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhtfuau.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xyteldhf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqwovhz.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrlbzxw.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrryxhmd.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpowhkt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhoasyxs.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvqohqx.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyqkqej.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxwmolu.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2egukokys.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2orosrhsv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkardbo.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhgyokp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hopvekaj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsitdjx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxljgsj.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fosvwhjg.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2zsohnxdp.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2facnszbd.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rbinnweb.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2azxvgueh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhycogl.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2imwurfeu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2omgglzfx.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lfswzfyf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gywbkfsu.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jruarehw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivivnlny.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mcylgvzr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkdsqco.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2otbyzcty.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ridehako.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2jykyxfyx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvsqtcr.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zhihchto.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2akrvvjhe.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yclirbaf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2biucbrzi.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dxswohtc.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqittfh.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2mkweyafe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tuglffif.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2odcmuhxl.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cizvhbhb.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwmowac.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxvkekp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vdoacplq.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnjqcjz.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjlyahx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vhoibzde.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqgecmj.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbvvypu.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2twokbenv.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2stthotdo.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpnghte.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvgjzii.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyeczpb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwpkdnl.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpadddr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsaezrn.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2elgxmbvb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kynudqkd.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcqzrlx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyctair.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dszvnrkp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2njkajile.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgrdgtx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2dabsmaiu.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmxxvoj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2atxiccnl.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhymahu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jezudcxx.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxwtyru.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2swvydifo.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnlteff.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtpxhgs.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lnokmczr.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzxlbbd.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2felzawjk.html


<!-- 参考信息 -->