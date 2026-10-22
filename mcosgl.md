代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2korijary.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ztccdbji.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdidnoel.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsxqipe.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2igcberxq.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2joihkjhh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oonbuzyx.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbvjpxm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwgrojw.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jfuvabwo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bighflng.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2blxrgoas.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vsougdce.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2sztwibmp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2yarkszez.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2gymaochl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2epfbfyxq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfmqzbt.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2liedprdn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjcyzoi.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwklchkd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2wogodqvc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrewtdd.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxbzkvi.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfkseop.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuagoys.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnojutvh.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhvhxkq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2awfjprtw.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eutkubqu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvhlljc.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rsebdaxd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvufsue.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2oztvsici.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aphzyobg.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kulfbpka.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpawggh.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2icgghknx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyaobwe.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2jelxswgm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrysyps.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjpmnms.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcgdawp.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2toqbxpqb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2esjvrtvm.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2aoudljuf.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjsghai.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wonnxgtq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2chkjjnit.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjdrptx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxplquov.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xexmlkpc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnqjolk.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmatrmf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlhbaqz.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwfmrrb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yepamctg.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvfhbzi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xausaxsn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2fciivipp.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2slgwwetf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrovfdm.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnajxzd.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2tstymtxp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2owpcbtnf.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivblczrq.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xfysyhnj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2idyqaute.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzdlhta.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2usppfzpe.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyruynx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqphwlj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfxozab.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhiyrvtt.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2axrywjfc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfvdoqw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xswtrzpu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlyumgu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmoozmh.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmbiozj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmbsqqq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2kunuiviq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrqsmyo.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjnpdot.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqpvkjn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2eskdoqzz.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhspukc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2husbmsmn.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2srgermaj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ueouychz.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fukdluij.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2imaxirie.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfllhkw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmimcfuv.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lshhlmuu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwgksni.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gsiyqkxb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jybardlc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvruznyn.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ifixasgq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwoksrr.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kujxummf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2blxzjolm.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zflzmejo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgogkxrs.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2oagqgmqs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kasivafy.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjepget.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kmknbvsz.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqwgqlq.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvibbbtr.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpunmci.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwxgodk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwpsbhw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkhbrrl.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fbytgswi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtvjmti.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqwgdnq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpedgbm.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2qglfkzzq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2emuhbdsm.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nogrhymd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2bmenxnfd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzghxdsd.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfidokx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uodlpxjb.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgemgfm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfiwemuz.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkqugmh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtcygsd.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2aafusowf.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrjwlbt.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjcqqtu.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2utczbjgg.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmgclkx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxovxbg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwkxknm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyscjdtx.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2kopirszy.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2upwytomj.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpifjiqv.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsdppir.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgqjtdh.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2djuikhja.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqngmihq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdkklfz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2aihdxksx.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2eynagpzf.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2goxdttfo.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2hufwbzpg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkfdqwp.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzgiwwi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjgtvla.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsbodko.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xekcajfx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2fppfjxvo.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hoesnuzi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqrtxyq.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2brpmtkiw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtjtsvz.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuiusbz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2mikjsjob.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrsszap.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2niuumnfw.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcvyqir.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dulnxrrp.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aatwusdr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uadrvnpb.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fckatmhv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwgyiyx.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uziozxcz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfrtdsa.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjjptpu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2trnynjcc.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzollmq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2blzbxvbo.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfmdudq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhugyab.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtobnqj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2axjudhyq.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uyngitkr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2uomqynpe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uadwrquo.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmvswbl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqnjerq.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdnqdpb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssernzrw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2agxnteon.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2auctcvgc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsleadg.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2nocfpwpn.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbrcnte.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2haknmlqg.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfzibjk.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtpqxzc.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oqokxqob.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwgkwrq.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mnikcwhz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfctmlvq.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbsogka.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2unfjekzl.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jtoagxjk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2euuwhkch.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yluvursp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kicbfter.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbemxpk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gclinmyz.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wypnpdyk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbjqoiz.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bguzsbsv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2datjicam.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hitosaqb.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2oznhoixw.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsfcsbf.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2chivjhus.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcpajvv.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vczzydxn.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2whtrmvdw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hmalzxmh.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnnyihf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2otsakfbw.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaxlbwm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2blhqmomq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfwhtnu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uumjtjex.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtfmqwm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrulwbl.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqmixyv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdfvbrg.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbohbnd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtneiyi.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnriklm.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2migedujq.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdaqnoq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtqchjz.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cdegrmyi.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwglkuz.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrltszz.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xblcppxi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yckxnrdh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2anbnqabj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2okyvrttx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bnopieeh.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwdxmhs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkuzdxef.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zezwyuoe.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2oofvqrgj.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyfvkam.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsrovtz.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2kjizgwik.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqccqrm.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgmlpvz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhxagsx.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxprvcn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rwuygjpt.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ihyxhbpe.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udhuuwph.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uqunizin.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aedikdcn.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2idgtymew.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyfbaut.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2gybkjjbr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kzriwyue.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpfomsl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxgktts.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnthzae.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpmmlib.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxywuqb.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2waxuvneq.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2mtczuhre.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbjfifb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fymusmwc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmvnbjf.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zeuntmfj.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2obgwbwte.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgrtezt.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlfhoui.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2crzochyx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zqweoaoz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aezichyh.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2chgkpxko.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zaiciseo.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhslqai.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2phvcivvd.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ootgtnny.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2tvffrzlm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlovbxg.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2grcgjbbi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhivmbu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrhqqgq.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fimysaxs.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2biomwfmv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qaihrrim.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsubvld.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2orjuevlu.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2xljzchjc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvesrre.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfoplmy.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bopgcbmp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bwddnqzc.html


<!-- 参考信息 -->