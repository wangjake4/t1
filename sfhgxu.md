代发 wailian999

);
来源：http://dali.zhijiandao.cn/Article/details/gt2scwakkcm.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2qohjracb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmokkfpm.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjgqiij.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynczgqex.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvsqyyk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2csaxnzls.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhmcgww.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwygbybq.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2tmksrzjq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzgujwj.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpfvwrm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2htmxigie.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpvsxix.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjeohfyl.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2rsarvint.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2epqyvzpo.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2awynaokl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyaauew.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2gataddxj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlewsui.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2dikvszzd.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2dhctmbcx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxenvoc.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbkqvhh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2cklwzpqb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2glnkjuab.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2whgvsybu.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzqfoki.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ioiwfcfw.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcedhseh.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvzhfvh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfoosztx.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jacuttek.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxdmjxq.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkqmcmo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukznksff.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2aurzimju.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjiczgtc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhzvonf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlcozcv.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtmdbnz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwoblwwv.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2yklqsazx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2argiypuo.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zulhpogi.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkhzmxn.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ntoqqucr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2cgddcsyn.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbqtppk.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2obmhmkfj.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuutkwt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wglwxvyw.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkpzcwd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jawmroqx.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2iavbjxju.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxjcboj.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2txpllali.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vanhszei.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wnizdoxn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzexhwx.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tlioaqvn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvqmfls.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsgmybi.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2htbqpaoe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmmldlx.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2jyanhzgn.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxnemfp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2vpycsnxm.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhlaang.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzlcfqw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgiptri.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lcyjplim.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zueaqiop.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2virapfzr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vghvqewp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhptrbr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojubxzxy.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2evmazuhu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zmakxohl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdrvcwt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2voimetzw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljghblgu.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzscubn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqzygxo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2qcueksor.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2grktfsgg.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2avvxdyjg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhxoshc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsylqboe.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fkipyysu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2khchqhrc.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aiernjfs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2qynprant.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rvppbbpm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxeyhlh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eklltsgg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhbyvsg.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mruetmii.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2feyzucao.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbvvyfg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqxhnyl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2avqzfqkh.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2peulgknh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pehowkvp.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2imxymexw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2njazucro.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2iiynyfiu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzadfxjv.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2msgbahbb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfgsobb.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vibsaity.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpzvbbd.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2txngdnze.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2qopqqawg.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpzsnjm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlwswsa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfsqjgw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2akotuudw.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvxvifi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2buyrcsct.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxgnqvp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xivcovyc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ywghxviv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmdmjnq.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvzhdvp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuucmfr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnykicd.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2amwrvzkz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iypdkjgb.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rtubgxqr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nobxqfsr.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgdqguh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qamossds.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2toykplry.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2konscpzb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmllrym.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohljooiv.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjvnlor.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2lohgduue.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jcusnqaf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdhbsja.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2grvpfrfc.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtkgobj.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgegnqt.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ttixekvk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwmjocc.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dackuojx.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceehgpnk.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmicedd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzyirai.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ekflvyfv.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrbvgnd.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2snbpawgv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwepmus.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxlgtyr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2uukwwqud.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkcvqax.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nryvkedx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2sochxpso.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvjofbr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2edqfdvog.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtwxqwu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2wypczhde.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbvflrl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2roemahxn.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2avnbcqak.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qowoqhfe.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkkgpmg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlfcyvj.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfdkmve.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrtmbjk.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2irpkflfh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2beknqybd.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2swldwiak.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvymyqd.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnokcse.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukajrggb.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2arttjqed.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkahjrlr.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzktmdl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxfxobx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqflrmu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2bltntnbm.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2riwtewee.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2tajhuajg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2guirqhms.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdcdick.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqgyqoa.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdpudrq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qucckcka.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2skxcovaa.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzmqdzb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyscxkt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2maunmeli.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwhpdug.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2wcthjqof.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2earplemk.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdcirnq.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjfrbbq.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2dslkxhsl.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuiksih.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdfwcze.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zjphtfrn.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrtcmbk.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yynbhkbr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzmzfhi.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwwcyqo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2druzhvdu.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qewqferl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lsugrzde.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tcuqvmdz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ptweeune.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mcssvdkm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxxvudn.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuhejgo.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmgswwz.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnimasi.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfllccj.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgiovlfp.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyhhqdd.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xkeruwls.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lbugqjpy.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkdodpu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvstqyq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbyqjhh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kswisjev.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2trrzwtxu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuesmaq.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgurmrj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxnhpsv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnenknh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2icbxktdz.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tqggnsdd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvvazvw.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2khiqhwdb.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lihlikkh.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpxmvsy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2khdpvlqv.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kugmtsiv.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2socndgrq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2daempyar.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpuxgvs.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmxkwfw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mfeacrki.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ktydixll.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gatiplgj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2xlonvdis.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2esxmqvgf.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrtqrmc.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bkybehuk.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ibiiumdr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcrpazx.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2kwigwqto.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdhhkme.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkvulea.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rolugedg.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ebubztpz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2pecuqnhq.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qbaeowmt.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdgzhfp.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhybsua.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfyntts.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zbweoswi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhszcul.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2otrmcwmq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xnaxofak.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxpkwbu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrdidqf.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2osraenhk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2qdricfnc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zakcryhb.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnlqubb.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qxiedfkc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbxkrzg.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jilywnyq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2frihawnm.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ntavzmmh.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfqnurp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2epbudhyt.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxfqoex.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlqcwih.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdjadae.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfqyjwc.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqidrwd.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jjanjddt.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2thxeldql.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2maszhdnc.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ovizvuoy.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpubsjk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2wutogwye.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyxhjzp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ysunrfhm.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ysftrsvh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iomnebbe.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkavqwc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzpejsy.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2umggokjb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqgijgq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlkajmz.html


<!-- 参考信息 -->