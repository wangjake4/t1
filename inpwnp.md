代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnyfwkm.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ituefdob.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqeflhnp.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2dczntwbr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqwqhnh.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrlqahv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2buhbbwih.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbhkrca.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzdugtc.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfpamgo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qndmljff.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfdamwl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2krslyceh.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhorqde.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdsnsug.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ytclwfxc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2jaomuiaf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdfjzel.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2lgupyofk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjlqkwu.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2jglsiniy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2uycaekor.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypimwrxm.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjxsabu.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2warfvcoj.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2yslnotcm.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvxlmqo.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2quvohuws.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uozsqjwn.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wznfvnqa.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwhfcwh.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnrddkl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnttkawk.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2guorkxjg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2arolgiex.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2eonnztob.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2shitisii.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwtnnpk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjornad.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2bggldywf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiifsjqi.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnnuyku.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkiuuoj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vscloxmz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2monretpy.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbkosml.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsngltr.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2eeztgzib.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sunbsvxj.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjtcyna.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlorpbyx.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbwidia.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiznjrew.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrqmrvd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqbastr.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxxthwf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhpzlwm.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2osnprcko.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvycgyte.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2igaqyojj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bsonpazt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2epprdmgb.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqnqeol.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwoowhc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2hvustrse.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpjogig.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tydvgmgc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfiddbm.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyqyghl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgujagwr.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qixpdnyr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dobzqwfs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrrelbt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lorewbdk.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2agefywax.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vvozhxah.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gorxvaih.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2qokajbba.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2smfictar.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dknmivtc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvkdiwp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xhohzlnf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcfmwhj.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uquuijrw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbddiwe.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2msjidaeg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2keyjpdwz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2thsuwoyz.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2anzdcsfa.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2idcltwnt.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpkjbnt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfzpxkx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2quzbaemo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2udlzdgyp.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2quswfosg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmukvguo.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzexpmk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqwiesb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnljrnuv.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fujbzdco.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uudkkybg.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kpaxeqrt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mmesfxmn.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkcxzve.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jblmddnf.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxuyiiu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiswctht.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2asdkwdzn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdctqub.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmdifnl.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2zphbomoi.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2logungxy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2svligtfn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbiurfor.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgichzay.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qtysvopj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdndjsde.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkhxdqt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlaipqo.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcwkxkc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2clztraag.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcpnvzu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ptttdzii.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgsmivh.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsaoqlj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuchxfly.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdjyrtr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrmsuwu.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2djsuxwnb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzwbsqc.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgyxwod.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2uumjejjh.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2huqnbnvt.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbyuwbn.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdgjskk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxbpkzx.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2zphcbrpt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrnaswm.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ziegfeiw.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssukyytw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jaemqzku.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyvturz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2etqsirjt.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsgvkur.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmconts.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2deoztckl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2aduslgkm.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbolhbl.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzldtgkq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2othcalkf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2swzyfezu.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxypjhs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxlhrdl.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkbfsxy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncebzjfk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2bndopdmz.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nohccsju.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbwjari.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2dprbbhxk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvsbatm.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2agovczhn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgzgkkx.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkefujp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2aytidrqh.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsxziwk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2esdcbruw.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqncqfg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfyhcqg.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jeruvuxu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ooaqbhzc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dabdbupq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuvocxx.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnnmbyv.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceikyhqp.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2iuoryxuc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwbvcav.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dntmqkaa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqpjtat.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrgvfxs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejapbvja.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxueoor.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnfpera.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2enjdqyel.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkrqcde.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hclnpkai.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2udduymsm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2setywivj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrosnpp.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxtungl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ccugywtk.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bijkixbm.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2yblquolu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2pftfzwev.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2mecncaoi.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2htewyywy.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkzxbaw.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtdygwa.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2opjqxxty.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnqeyrc.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gpufijkk.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpchzcgo.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnzgkod.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psjtbrtt.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bypwmqfn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjgdunf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwfosfo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2caxligsd.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iawvjsfm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcuhcwt.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mstsawic.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rchxivll.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hlekpqit.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2pigsoopy.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jirzxkfw.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pparnrmy.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlylmiac.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2rohsawqw.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2epppeubd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hgejacpk.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgqzscg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhsbvyy.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2whtstuof.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jarsjdxa.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdrcftm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2djytvqfw.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fipuocrh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qmplfwij.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vscanixf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pflhjpuy.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyuzqoj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2biwmsldt.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2upxvdegs.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdlqzld.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjuryvb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2motanjgt.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wprazmld.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2quuogyqf.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkjodop.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkspkgf.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpvjafz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvpfzft.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lttezruc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnargpz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2xrplkxdn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsbfztq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kgotcudp.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrjllvm.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjcrobd.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkfxxfu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2whmkuvdl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2yebicbgc.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhbyerb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvbetng.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ievsvsqn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsydztv.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2podrapzg.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbuumso.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwkpriq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeeanihn.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvlmjjr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ekahnznj.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcchsnb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkymprl.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmlcffw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhstxei.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyvkacw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2kszbwrzq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrcwsru.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgetobyw.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmrdzcz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2afvrmwpx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2geatuyxq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuvjyzj.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwvirmd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkxtdhz.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsvtbqu.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2suwqgezd.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhznhkn.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hegjhfvh.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmdxunt.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgopuuc.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vljuzbjm.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvdvrni.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcpzehf.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwwvwxm.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qnndtnqh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2itzgxfhl.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bailblke.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvuolte.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2twknizkx.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkbheux.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2laooogti.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lpetdlms.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mcovyqbj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hppgmmiz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2uoatsqsl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2welwjotn.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2eiznsqrr.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mplojhkn.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qathebkw.html


<!-- 参考信息 -->