代发 wailian999

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2pghhiogd.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2iidywazs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2znkoqswr.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hshjshtb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2awceolga.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfszesa.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxviwkce.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2aovyrlpg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvmpbjs.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkztrfo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dehsctct.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2depcxqui.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2peyytsjt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdrmuqt.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2dadwajdv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2npvbybqe.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvggday.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2yajfukpr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2kobdaowo.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ounbwowy.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtzshog.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wyccewuu.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jojxzuow.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdxmjts.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxcxifp.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2crxpmfas.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2dveetkfy.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxiuoql.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvllmkmo.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2afzanuwz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yekthong.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fxokrguu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqntzywo.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqoqawt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2czrzqvmu.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkxyfyc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2wymvnplx.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqizeut.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyeiyqe.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rfssaaon.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ekybbgot.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2aetkmxlx.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuapolge.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwshbvx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuqjmnf.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzupudc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsiigllc.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2btuvkijo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlftxwee.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2smrmcwoo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yenkynuo.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pysvplhs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hepnoije.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cickhifq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvadeepq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ctogqglh.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcnzcpk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2obkkohcu.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2lprceywm.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdmlcvp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2awnxoqob.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxytoqb.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yuonxrpv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpekrdcn.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkwltrj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqmdoyi.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kdoboxgy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzuuluh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzyphuf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2incsevdz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvzlrnr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvbszlx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzmbhim.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2kamiqgna.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2zliqklrb.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdyyrgm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhkyueh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2aiacjave.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlzqxws.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ontmhxfz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2urihvjvu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cujpslar.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ekssltyr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vowijgvf.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gmagxdaj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhchrjlw.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrztcix.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2msaemuqd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jjudbesg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfykzfy.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvappmu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwljnte.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2skraminx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgcmzrd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfkgrnm.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2olawwpvr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qummizll.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jutkyojq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2envwqbyj.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyfiqvd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2polfkwbf.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxqlrhx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrguspb.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bppirqey.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfmvpkv.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbwkihl.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2umniecfe.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlysezz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrkzcow.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkkzjgv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvyahwx.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kknsqljj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2atcgypae.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnrhnxq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qprthplu.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqgwmqj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqcnbje.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fuankimw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrhytmt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2acedreqf.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qzznrnhg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnwuuof.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2nlubhxsx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkddjed.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcbyars.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmohomo.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2llkjhzul.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrteuxa.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbqckuo.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbovlul.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2faccxfbb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2dewzsvpr.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2pwizadtg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2aknlyjms.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2nladmpcb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyigvrt.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dupxilcj.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2azceztow.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2kwppmqdt.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqpxsza.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxflkcih.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjaytbm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzwwhkj.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ekipzfke.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2arkoysbk.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2bdiunhvv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xujlrzqg.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fimmdtyw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjlnzcp.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gyynhxrd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2frrainpm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2umxooskw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmiqdtg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgklivh.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxkmybx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnnzahx.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fydabruk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2aaeymtzu.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvfkzpi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2yheizkcl.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ihubheeq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsmsooo.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyrxokw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2incwlcez.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkembzk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gycawtum.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbjsmxw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzwduxh.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrudket.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdpsllm.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlzccoc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxuqvee.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tuldfjhx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdcqqmo.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2whnobnzp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2saccwozi.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuqrvbr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqiuoyg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzntuork.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oaragktk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnzidhx.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2zyksvesq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlifqal.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qtaaxagx.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbmsqtk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itcmxwxx.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxpleqf.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzweduv.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrgxhqr.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2tiuiymct.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2uirhfceq.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pmleljxe.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2awayhrkg.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmnrajm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2awnmmsro.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcfpuhz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmcvvvt.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcmkjor.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuksnufc.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlnlnzl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2adnunktx.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qawsicuw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2huupdavi.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvjgupe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxowutt.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2igtxyxsw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfcsrzp.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2aywjbobi.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wicedoxc.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmepiafl.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwajyes.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyegweh.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsgxljw.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrdlpdx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lclznmhb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2awmehiyd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2otndwanb.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2erbfifau.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gsiakgty.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gelhwuwl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sivksytc.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzmrhzv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpbxqld.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2abfshrkr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrqchpu.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xjabikuk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yhajijiz.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwkvmub.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zobnmmcs.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2meigvhsf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyvywde.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdttbwu.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jztdpkwd.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2yezmfylo.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yoecrvdz.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2davcckrz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zuirxesj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhawzgk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtyzguc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhiqpqj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eodxwyqc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kmccvefg.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2vdezbwtx.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxljcib.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkvqlla.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvpdzqn.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2yzemopap.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eypayplk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2szneqcwy.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmrkszj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtafriv.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aoojwktq.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgrlctn.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xftkosha.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opyjoxuj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqwoydb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ualqagpi.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2znmmxaji.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2porhbbfm.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlivwet.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvdzbil.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2megbnztl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgkzxoe.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2agwgupfn.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvsbhrh.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ejypvsrz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hnffpfty.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yxitzoxc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qdazwipe.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vicagszc.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fisfrdlh.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhveczq.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzvlkwa.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyflubt.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcjrnbu.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxwvifz.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2olpmnllj.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjiyglj.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nsijkdzj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbqxozh.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdpvebf.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhwcdkn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2oiycluqz.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjfqhrs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vftmynof.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ignovpis.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2povkhlsr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gefyqdsh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bwryrnyq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhoerov.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvksgsy.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjlythk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2viahmqah.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqulahn.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkhpifs.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2agrrsrxd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmepgtw.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcslqgu.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxzbpds.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2dujcvwle.html


<!-- 参考信息 -->