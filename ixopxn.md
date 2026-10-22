代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdpjspj.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2jahurfdi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2skxrslsy.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpkbksx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajriglag.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvhdipg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iibujrcz.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2npomrlpu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsgaztf.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iybvlmpy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpuxjhd.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2iilgggko.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2iawifijh.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2skhsdeyb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqdeehi.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2oabavlfb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2nrohrhng.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2eyygsbbs.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2jultlgrw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vzavhgpb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2zaynlxeo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2kjoyzqwj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2izaamrou.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmhtfob.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmyzznc.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2iatcsauk.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsxlrfo.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jueuemru.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxhtvsa.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtmqomc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrilpgv.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nilgxurf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggicftfm.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2adghzzpf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkvraux.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuqusbs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvirwgpt.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lfovqult.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxgfenv.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2apxisvdb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2upjnlsyl.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvbtcxq.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdlkxbg.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2holrqtac.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2udkadmpr.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrevcxi.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2errrbtta.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2awofzefl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuyjyay.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cexuxrcj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbxmslz.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqorhiq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkddpup.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qikcmjel.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2saqdfygk.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwxlbke.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdeuzkr.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhkqhic.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2aynxjkfs.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkkmdzi.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkullzd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgttbkla.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhadrtb.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2wppsafvq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2hglbxzda.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dseaxqvp.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vejpkvlx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2maysfcya.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsazihw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnappwb.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2huuwyyot.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2idgrxdfl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvnfrgn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcjkfsc.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsyjhpl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2woomhwgf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iexosaxv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxevibbw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtcsfiz.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpksmca.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2yecgxcdm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2njqhlaeh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2frutnwjr.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwjslrh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2wyswxzan.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwrytqf.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vgidmohg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2rugcfhon.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgzolkr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzwneel.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjgpgei.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnvnxzw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eugnjzbk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmqpnfc.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vobodzfw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkmkjyj.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnepnmp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbagmena.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxcguqp.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2guuuxymy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsqpcmw.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2erxtrjsu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwbsxtz.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dyawfldm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfwvniy.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvxezht.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2awzmdhqg.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkppqoa.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jvasfygq.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfudwoh.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfyvsrd.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdjbbbu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbwqswv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2guvkcriq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2svuvieyj.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2aomtrtjy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtpsmle.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmtqslu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2onqvywnv.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2utaixurs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2byvlhlfi.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2distrlbt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ukciurus.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eahwvkgl.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kidwrxis.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcomdod.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2hztobltt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhhbqfq.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2enarqgjt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2urgaowiv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cflvcprj.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeomqgxv.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wklkfdyq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2doedycrx.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2srfsqhss.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnvwegz.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrtypsl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnpwtjj.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrlxzkq.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucptiuhh.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uukkzyst.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2saboquvt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2desyqysd.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnnaxqg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yofdwjwf.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2kkuxrjkl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2zntiizjv.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwsjnrs.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2stospnpg.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpsieqa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qonfduwy.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ryumaylh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjqhoea.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgykgvs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rauyzvbp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnlomqa.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdnsdqw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgouxmme.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmjnuzq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2veohxwzr.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2aovalrnu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2fawpdspg.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2egegljfk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2fivatypv.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlmxaha.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjjceqv.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfkvcao.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrlmspu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwxucai.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfspqff.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cinoecyx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwvudak.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qohxycdg.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2snmyiqyp.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcmonap.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzlsfda.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zyipzivo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2pdclqmbb.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdwcetj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2anmhoqug.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbntenrv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqbrvwb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbwapuf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwpdcbh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmzjwlr.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwpsima.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxekgvrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bksabozv.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfvvutn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2phvoillr.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmaxyof.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2pawcyrro.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vuccxrdr.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2eekcikem.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvwvydx.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ektkfems.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvjrfxc.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vddwevds.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlrhrkm.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jtopgqsk.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlaopgx.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvivyfd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvjxcbk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwobild.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjccxsg.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uafteyyz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eozvhtpo.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxjigna.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2drzlxvzv.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwircpo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfkdyva.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvatgwg.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2xosktiob.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsjvvnk.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hengimto.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvzvpqv.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2weqdylqp.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnuqwwu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxkumqk.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzjkmgh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kqoikrtf.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjdldmv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pbocpzvo.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wemvkcdl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2awddqzca.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbtquyc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjxkjeh.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2qluqehlp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmlgqwp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnsvkfq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzmmrhi.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qddugdev.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqizuwwh.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvivwike.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrblvtf.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2spypoojs.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2renpzuic.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgsxnuz.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxghtql.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lolndfpe.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlmtfls.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcheyxh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tonsgyrr.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2czmmrpyp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2btgiuypv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zojdpbwp.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkkounm.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xshdzxas.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhdegzs.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdeewfl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpudglx.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmpjfqh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwsczfo.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrrsyup.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhchxwb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjatndi.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukctlwnb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxkyktw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojihlsad.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvuuviz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrsqqld.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2nxoonqaq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fogoeduo.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bavrdtwc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpwadpl.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uskxvwma.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2jonphwgf.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlnxhtq.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qijlqsho.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2vnziapam.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2uuoivelh.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xeudfhxm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2epkckalk.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvdqklv.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfhjorw.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nwttobyz.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwmdjiw.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gpajteyv.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nffdfgcr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ykavapru.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfsbyzb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmlvnya.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pewyoarj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjivxhw.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjlzqvw.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwotqvo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmpdfss.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjosqin.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsoaaen.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2chheshtx.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuzuzue.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wpakrevn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgduprt.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2apcggocu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hagysagx.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2omlnuokt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqmtqsd.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzqfida.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqrficg.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bayculhm.html


<!-- 参考信息 -->