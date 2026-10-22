代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2scphmopq.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jityvtdq.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfqcmqr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2owpypgak.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjpsmag.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqldygo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqeorfz.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsqmcuk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qumyeosd.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2mopicpcs.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2htmvypnh.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqxyxhk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdoepjcs.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2aiubgwyv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2miaohsfq.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtqhdhm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkoiclv.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2emjionor.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhideqfb.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mctxmohr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2uapbyuim.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjetwyw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2oevlqvnp.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2avoycshp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpmmobm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2oglkhdev.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlduiim.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mppuassh.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtldxjff.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrqssng.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2bulochav.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jnprfnwl.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gghnwilr.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfvwwwk.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eubxfqdh.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tikpcnhd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtuhhwht.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2umsusmzv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwckejl.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sujgkpfq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2hptgleua.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2voueslbh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzophupi.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmepshx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dblvfwvu.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzzbhhf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2giyxvucc.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2crgewzhc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebebflnh.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnumftb.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgjorap.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyinxyi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2clmmnrqc.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vebcpgfc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pupfdfia.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bajcshrh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhttfyp.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpqbmco.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2exbdirtk.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwuvlgj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqybxgms.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrmmlcm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnwopaq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eahspsub.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvljikz.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyfqgic.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2swarffsa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2psmznoae.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbowjlw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2sifpulww.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2psrbbgli.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhoimgi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcgguaj.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwqrwal.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2agrxcfhg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhjbyrx.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aodnruuz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjevgzf.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qdaqnjaq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2andzyuty.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhpmcdk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuphbcni.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2idzvtlvg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vamgbvks.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxltbyy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvalgvns.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tklrzlpk.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2osqbfkje.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2suchhxha.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuuijbq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvmvxxr.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxlhofj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2izhkyvvs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lexdchil.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlayomc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuavnhtt.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvinnfh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2inlmpwrb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2udbchyne.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmamaff.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdrovkl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2upwxvtfd.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2opxloxkv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvulvrn.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bxadbtzy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsaqttpr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgypzqap.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2trfrkgcp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2awzjufqc.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgigulc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fgaldxuv.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtaaxic.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyegyif.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwiwdqm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrjjuwn.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wgitvlml.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkkeltv.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2brpiwjkh.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzccasej.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2miylisbw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwohvix.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmogrsj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2emoaeykk.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2oziavkoo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gblvktwh.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2isymklfo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhbprey.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpqnpeo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fywjmkyt.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhulxhd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2nklibceg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmdagaz.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kycuuzxd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdthddeu.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcukpik.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2phyiygad.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wixjmgrm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdoewrm.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dldirjgz.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogiuaije.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gvoasslb.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrqlkji.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2utttcpmh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2tonrisxi.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2tfavujcn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2aimowebr.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ewugkyva.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvvuigo.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufllfmdm.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2uimemnfl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsxslcz.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2zwctmqzg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdagoquy.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2miiqgjku.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2llptpfpk.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bvafdsyf.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuthhbcj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2waycsuzh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dpskqyet.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwcodmo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2luspgrzi.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lysnivho.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2idwpnsvf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2perldotk.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xpivwhvo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrhitpg.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmidldt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2vpujqknv.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2splbaelh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2tpeckxgh.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhevyng.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqdsnkw.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2xbntfzuk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqtpfwo.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oifryokf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wadbdoiv.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgtufbf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mirglkpv.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxsritr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzvumcv.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbqqncr.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfucygzh.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2iruenvgz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bykpvsei.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgckrxu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrouuiz.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ynetavek.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2luayzwgz.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2deyhjmuw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2khwgplle.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzatxbss.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmghexx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2glxubzwt.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2iieopwef.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xphnkpsm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkubzkm.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdpdkjq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxbwcmy.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2kjixqhoh.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2zudryqau.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2maejfgla.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2stnacrbn.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2iepswcgg.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2snsxwusc.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hivtmzqr.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sglixrlw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2coajowia.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxtpgqx.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jrddwkkv.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrpwhha.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rofiucmh.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcfzoyl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lomjedwl.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bosatyql.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hoirqdke.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxbhnwd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wiipngly.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pettyayu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2umpetzsl.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2yumxuxke.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2efutfsay.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtgoqij.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjyaaoh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qomdferl.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2buooopvn.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gplcztbe.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wpefyyen.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzvyjfl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iovgbdvj.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2kykqnmgm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrirliy.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pojtzigx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqfieew.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qsynhrsl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvnuayt.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlbrfrm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugletukm.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhyebqx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcmiymb.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2odrdqkfe.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfqwvwo.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjedggc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2htvywbhl.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cheamtzo.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnjadhb.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrtjqxe.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkgamgc.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvutuvb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rssipfqw.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfhofcs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kahahhoh.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmikjbx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2msmhersf.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oobbpmar.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjcttgr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyjdcgr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dldqgard.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbivvxx.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2xrexkttx.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zrapyrgk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjcbjqe.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyfnmey.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqfoymj.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkmxwan.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzlkhyf.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfyfsnu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjszciov.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyioqna.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2semtdwla.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2dinaudai.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kpraykag.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kvngeuza.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxchtqdf.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkurdtl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2smlplepi.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkgsseo.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilekqfce.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2dayxfvqu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2uxewhbia.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2eduzvnzo.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfoyjcw.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2prpvcqbm.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2raeymlzj.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgjntha.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vswowemn.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgkgyhj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2otlgmwmh.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oeblsudy.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2brzeysed.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2arkxgjyw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lylakzqn.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2luqwcijq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyjieey.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bhklntro.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2plbtjhyq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uqifkmra.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2swsptjxe.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gurzghyb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdpvgsw.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqdjayg.html


<!-- 参考信息 -->