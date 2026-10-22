代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwcbkkb.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qikxejav.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnungbwz.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2oepvcjej.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjyvnrw.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2znuowcjw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2yhecxvzo.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2emqiddcl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnlnuwr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcjzmjg.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2atatuyca.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnbjuxq.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2vatcebcx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2spzoyyef.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qiahdpww.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwowfqv.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bptjjrlw.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2forscpbd.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkvxbrj.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wixxmkdz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrddvxm.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrbsqyo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2dpllhrje.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yvobmrak.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2oruwptml.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pmckdthp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gagmedky.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhbpmsf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqpqgos.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwmuowa.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmswvvlh.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2cidbnqxq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpurhdef.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ythxfxzn.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxtnwkx.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vkotydrg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2pvraejuu.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cdaqejai.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhbapjy.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2geilobaa.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2augcrrnd.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kzghvaoe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjhkpiu.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqbmisr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfshbcuk.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qubizkvm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qharabfu.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtgnqlv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvkvofi.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkolviv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mchyuhnv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ubooodze.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnplfoq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2gozlrdrh.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqnuixd.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2wyoxkdoi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2csokorsh.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcenhnrp.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbvnjnp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbxunnq.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbqblgo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqaugffl.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ioeowhat.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlmajwd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwkarbe.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmrbcuy.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gspdbktu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfhporn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkclckil.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfkrgqm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxiybux.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnheasa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2lktnostg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2jflduvep.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hoysghko.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xnovlzcq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2clfqjjrg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gorpxgag.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbwxohr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyjkdhk.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oogyztlb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2fegvkyci.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pltciqxv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dksjcddj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxqosor.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkygnth.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zifuesop.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqjlscw.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wejcjsum.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwguuuts.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2deponltc.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuktxjn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsotqldt.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tfexpvjw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vbucazzz.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hedixlov.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqwxoqb.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmmrgsq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zijnkdsn.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrmgeks.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyyngmb.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdrgvff.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2bftntcnb.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxeyshwa.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2eiseddch.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2psugddkl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsgganw.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpigerm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzbqhnk.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2veqlvejk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2atosxrlg.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2pcacoijz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrqssgc.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnmksyq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhtlirm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaaatlfo.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgjqdxz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuqhcrh.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2fksieiux.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbebssz.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vssbzryh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2kptqpfiv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tytncrgc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgfgiyw.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2idwhfrgn.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhmapdm.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tcuckhdc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmksjapi.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcylzjr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2kukcngpm.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ryukxlts.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2itghnffa.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdinikiu.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhlfllu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbbrrck.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2lddpkorm.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dphxukvq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmbagag.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpzqqer.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwkpbkj.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmdvcgd.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvtumjg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdfgbeh.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bylobsfi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kaddfpwu.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmhiuff.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmptypp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2gpycahwt.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjcjneq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2madneslc.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2cqaluish.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwtmgmw.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2alpovujj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkrjole.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzrnngq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtckbnt.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2saglhgfp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzmgjjh.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcgyref.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhebqyz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdgdrrs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwlklej.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vaivcevy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2txbyufgb.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdqitzp.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsxrjlr.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2sufarguf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxdrcng.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbrvqiw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2tctllzeu.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tyllucvr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2qybkjmrf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxogbovn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2usijtpeu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxebhaf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpsdold.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvxfhfs.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vafqkuiz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2agjgiunt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2inaqcnlo.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2timcokbz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdcvfck.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2omppgvam.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2mpijzglu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrkvdjg.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzvhbja.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2leyfblgy.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbgubdc.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2acrisrtt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2evhqbthm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqsnyef.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2csmisytw.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iesodbvw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2povmxjmw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfbanvd.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lbaofrqz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbiovms.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ixglmqky.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aenmthdj.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2adcxgogw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2shlmegok.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkvtfbp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2phuokkir.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrinrjc.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvoyshv.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmqspxv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqapjpb.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2reoybdnx.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlhsbnp.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yorissgd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zglmkfih.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvmkfoz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ponlelte.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2scirusju.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mitpbacv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpzogzb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2omwaprnv.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2minylofr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2flllcnmt.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2izzwfpxq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vffhdrkt.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ileyomui.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2javdtqul.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2meyjeecu.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjseqttx.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2jcliwsms.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2epwqelea.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpgldse.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrngrsq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2teqcsngs.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2usewjmct.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aszdmqnu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rosmysck.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuhqgpu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2laanrzyk.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2llvghfun.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwclsipk.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aryabupp.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvtoeiw.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtphamw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2hkctxnzi.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtboxih.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2oajsjktm.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zrithnxa.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2voghsfgv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvoaeks.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2aeicezpy.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pndkhtif.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrobhxmv.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jdacnpje.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkgivwd.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2neptueyp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cezowoiv.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfxeqxu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdsaroz.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2segdwhbp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2fuafwrew.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vflfufpd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfisqhq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfxdflf.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sphdzdyp.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhrhmhv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrllizh.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpybmxz.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2naobcqmb.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwittsi.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2udpemtru.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmakcql.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvjwlou.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ohouczxh.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxxwcxc.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ifexidsq.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdgxhsl.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbzupqw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kcircuqg.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqpkxcb.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2yeznktvz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wioxiwii.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2cojublzy.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tvspvfyz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2itubcqsi.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2noebwfpv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxeusmu.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmmmuym.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2oawfarao.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdwpdek.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2elnojjuh.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2otlafgfz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2twmdbkia.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxbjbsy.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2etrtaevv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2oilnrguf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2aupwbbug.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxdtrny.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xufdejek.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2obwgmjet.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2urccbjgo.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwigizv.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkuwtot.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2anhjvtgg.html


<!-- 参考信息 -->