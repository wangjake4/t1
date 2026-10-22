代发 wailian999

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtlfntn.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxejnjq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fozrozeo.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvyecmw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjdiivm.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2pypgfhju.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2veusladl.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdoijjg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvofrqde.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2uygxdvqa.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdslrgan.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nglwvhio.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2saxkgoyk.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2msshzevf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2amhephnd.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcoswzg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2yulsvvqn.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2flgjljqv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jljyqdlx.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2rebktmti.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2qoaxjsyy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2txnaaloi.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ksahhmty.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsemncw.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrldiio.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2hggmpawv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2omkhhqhd.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kxazueww.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2raftuogi.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rnenbdvl.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yehaajtw.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2clqemfsa.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhugozf.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvmkjzv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2bigfbomm.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwgqskw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgrltih.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2svtjbnqw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxunlagm.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uqaunaeq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhaozjh.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhfgxic.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2knsrgkgu.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2kimrekxw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2cusuepaa.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyaxwat.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2opyewhpq.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2famxvzrv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfulvwx.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwjwsqj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2juzaaowo.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkdgyol.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqywdsyo.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2swxsdxnh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsytrcu.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lqitrgib.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjesfzv.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxatsvs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kueignll.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzmjdss.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdqiagz.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbpwswh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnieful.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2amzoohtu.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmnfpug.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2flgxtfii.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpbxkzd.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyrwsti.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2rgptpmyb.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpenkrz.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hunkxyjt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrreniz.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lowwrxpa.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdistaz.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ozohwxzl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggulvgqi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfjjdzk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdqwizn.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tetiibdp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ecapmttr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziepuzbi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjscuft.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvtzxqg.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwhbygt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnyfctu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvdwmqs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsbsrmb.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2osysdgas.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwbrqqi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwqpzaf.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkchkrc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2eancdskk.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyvfzqg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2enlogixt.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmyooqq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyeefzh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2psrvnmtv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzfalip.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbueblb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2caqwssyh.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vknutrlo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2qierpsgn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpuddwe.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2eeixwrcu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rambizvj.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2scvlsglh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpsemee.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lvywfcka.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqtqzfn.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2derbadvo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2orsyhvih.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2aloaggdh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2avhnvftd.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxrcegn.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvhsdxv.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2klirggup.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvalaxa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdetkaqz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaaxvpwd.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vovzdyzr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rigwxumo.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2eakffhkc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgoxrwjb.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtstayd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmehvzvv.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2twgqfmbt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvlnrin.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cglzbjnx.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hospwvvj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqntfpkb.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmidmbt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwofmcgu.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dyufpyys.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnwmyru.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2igfpmwik.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbuywnn.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyaxhdt.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxffyjrx.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlqjvht.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtegylh.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2lczopgci.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuslmht.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvjvsog.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2imfbudwi.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtsagcr.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwsryox.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2laludmjc.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvqxukm.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjtthbe.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfpfsag.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2vgptlrww.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2brytmotv.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2adfjtxbc.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzksppn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnrfsxv.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2srkpsrqq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvlsqpp.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkyeznl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpynhot.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkhtpce.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2arooufjy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2xndrbslo.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjvqsve.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2plspxbtg.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvcoxac.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvtydvv.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2obvhrnch.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzxhchy.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnootso.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dctmjtkh.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrhldjx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkxlztp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nrumwkqx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2khunwrlt.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfhxxxi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgjllwf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2aujuhjar.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2futofqzx.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbqvzyi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcraipx.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzadcck.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsyzzms.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2invpmqao.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2bexbwcvo.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmkzkdx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2didfexxz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnosvueb.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aaubahfb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpecgyg.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2gafuvmao.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2daxfzoft.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fzraumtq.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mqodofuz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjiwgymg.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2onlgflci.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2aduxubdl.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2abtefipo.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkezxup.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdakntbn.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2caetrdpn.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyajqbn.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjktzkr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2aigdepla.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xxybjlpt.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwptlyar.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnwkwwg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glpcwpml.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uvypcmpz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdvoslt.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hloeypmh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjgmxgz.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2veobbaky.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwqnqln.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2abaqcbci.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bvoixxmm.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpsnxxn.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzbcyvi.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbgdpsm.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2klsfflrp.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqvezwn.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrxtchs.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsnithr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpqbzaa.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2droevmyo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdpbipg.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hfebqboh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvoyhom.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcxbeih.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvftyrx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbaqlfr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vimzvhka.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmpqhoe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vubdkkhp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2evawniny.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpxhxqu.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrdciez.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcjzvmz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcqcmqx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgdbnec.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuvqael.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmpcphb.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkvugny.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eadfuwkp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vpigpeem.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzndsmc.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrpcyfj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qprvrdob.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2hyavlrzw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2phnnbary.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2blzqrkoi.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzdzhcz.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrwucql.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxfwndp.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2snuqabda.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2qseoyobj.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fekhfqlv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrryxlq.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2omokkeey.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyuokjg.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eryfpyoi.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqblsju.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gbiirbsq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmghaobj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbcstus.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuwsqma.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2tipwzuez.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2twibdveb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjusdbu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zojejtjz.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hknvavju.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2kgouhqar.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2apwvppjg.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtfznqz.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnlabui.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pydiltxg.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nritnwfx.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2biusrjti.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mtigezki.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ysoalmse.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhcaesy.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqatozp.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzhczix.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2frywrauz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgwgivm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxhgfqx.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqaoznx.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpdxwcd.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mcukeook.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ntaeubzb.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdoauky.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2qyndpoyu.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2shgcvbpj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qbeawcus.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2domzcqgn.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mrydtekz.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cswmhcas.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcfvkbl.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2seewxxzg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zrygoclu.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkcrvhp.html


<!-- 参考信息 -->