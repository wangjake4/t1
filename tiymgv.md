代发 wailian999

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjvmado.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcxeljo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfxrdqp.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2icyccwit.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2flldxowz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2udsmojqd.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2uoclcdqi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cubaftkm.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmuqlcr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2giaglmmu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2heregnie.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vefmralu.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzvsqui.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfhgxdl.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgczryd.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhxrewz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2snnieeyj.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvzjlwx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2egcbhmll.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbhvicp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ticpzitq.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2owjqnfur.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkkcryk.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbkqzqc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2avnqisyz.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rskgsnga.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2eljrjodg.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2mkztzlsp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2zctfqudd.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zixzspum.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2suejqcpk.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdrslay.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2tdeugbjw.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wmweetee.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlrqher.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqiscwqw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmpeayh.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxukqsd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlxyudd.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lntgusni.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvaemlp.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2omwhiilh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkmrvbl.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuiyxqt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgfrhiq.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcpsipv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgmyiud.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcpfrmd.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2brvnugot.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2adxiefpw.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2teduzoag.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2npjblqpt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2xvewbmmv.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cacdfaii.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iyadragc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfnismq.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2knytfknt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nertnrfw.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rgoijlwu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bihtkpow.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2geubzqno.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtjdvgm.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nafphfxf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2dfiluwfz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddifftai.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2krvxnmyn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvfhpzz.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxxqvmy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2oubnabtx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2taomlmrw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2clkxfwzu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fqksfjxs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2lfexncri.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2evwocllu.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbohgow.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbsrlcv.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuijdwr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2clubsvfs.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yinfbwzj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtnidtl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xfimvuwy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyiufoyv.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwkxwkm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzjgdoo.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jkoxlbld.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2buckpzgr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jostchpy.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzvixjc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2erkcgxoj.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyazvit.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyblcqq.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2frfoqrra.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsbyvgs.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2nphvrtpz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2susjynnz.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjpipml.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2clmrmvsj.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfozzby.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwdqnxo.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hltxutmt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2siimqwgx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2slifjare.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yriwucok.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kztolkmc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzuqpur.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2udpwvjvw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtacnjz.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2moukhpvg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsgiwkj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fitrdgiz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkoxyaa.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyhdeen.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2juzsbvft.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrhmmbq.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2kixhvtzd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2djhtudfk.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwvcorq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2visjasqg.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhekrfu.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybeeaptb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvbrvgk.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2awfhkcvx.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wufcwtnq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2goerpsyj.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2dflsdbsu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbfplqt.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgtuokr.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2noheuluq.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtdiafo.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2pxscwesi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2afpqwvok.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2iyljeega.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyyruwu.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxhhlee.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ieeqlqht.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rffukrrn.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2idwchbci.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkvybph.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fezraejn.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hokwuotg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2tpposxvg.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbiisya.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgyjvwl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2vzghgqqc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ziddtfad.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmsnpao.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2kghsecbl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2usymeqdm.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqiufxz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2feuqupro.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmoyhfn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhiouze.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvqgndy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tflzvcpi.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvmplwi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxuxbtw.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dszvagwg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oogtiygu.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzxnnkg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pexjghks.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ucziknnm.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtraisa.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxshnrz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zifcjxpx.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2uybtlulr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrslwht.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uckfgktd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2phatjeyv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtxhdxx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxjooab.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvbkptb.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2msskonqf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyvincm.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2snewysce.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubiypdgr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kloidakr.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfettoh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjeddaj.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tziwjijv.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpgopvc.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2qjopflxq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsclhjo.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxjqsoi.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cemstlht.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkvpwdq.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfylwvj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlmdkls.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hzubslgi.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2inppfnvw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2reecxwvi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vinxymlz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fsoavpou.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfbyshp.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2teywgwaq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yunrnvlh.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lijktiax.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pfebbwdd.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2exsfcpbt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjjgvhd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtjhvxf.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvmchug.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2auhddhjq.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2itaczhih.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwxpihw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvsyzub.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzzqzzw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pozdtevp.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkfnxgb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqnxxva.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vmppwlxj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oepcbjyr.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2szlfhxxq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2isggzlwm.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2etfiifqs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfkgclp.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjitypr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2afyhuowa.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hupuagsg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgrgvou.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdondkz.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhiitdp.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2artehakj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2atqhddlq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2urjhncac.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rybjgmip.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwwvbht.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2evsjlwdz.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pemlyviu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2olhymngw.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhzimnr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlyovxg.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2dotgtygr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2axrbcldx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2skyqladi.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxsyafs.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2kpocdphh.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fbviwnte.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmgtppr.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wnygceri.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxphupk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2waakwnyd.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2iyaupnro.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2tskjyrhv.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mtklcnty.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qubejhso.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tzaexmlr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhmjfpm.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrwkntv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgjjpue.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2juoqftkc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2sjatlqwd.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdaiixt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhkvzhf.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxfzofg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhvumku.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqhgbxj.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tefdvpba.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2znyeexoe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vgynvkcs.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2klzswcon.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2opmklwwh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvqvxwd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2csjaundw.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ldszdggh.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2myzaidhb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxfbzez.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rdunrbuo.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjchuvg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2sielvarf.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2grolojld.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2quepswnr.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vczqzixb.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjyruqo.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2voedyqsf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2bglajbyx.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgylxib.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ucerkowa.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpribke.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ipixwils.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2puehhnxz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfclpia.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgiffts.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzoukzu.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbnknlf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrapoxo.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmjwuca.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mynglrgm.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zukgwdjl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbwjhel.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhhbmvu.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhuryfz.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zxufigvu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpnttvi.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqqjdqw.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgvzzpm.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2yubjbdxj.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqrjagr.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zusirxfo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2clksrdjs.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnfzftg.html


<!-- 参考信息 -->