代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhkayzt.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuxnxkr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxposfr.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2zgscvuvh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnapsrq.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2twcfliwe.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlihbhr.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yiaqbzzi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiunpzey.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tjburphc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jglhjowr.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxxlnav.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqhumne.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnjsupd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnzqixd.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyjkyjx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2stmovlyf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2rakezpmp.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkgdjum.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjtgibb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjigpdab.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrurluw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2buhevjti.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2iylwfofn.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkjomti.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzegyxy.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxewrddq.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nxonguof.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrdimgu.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eerjafgi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdpvuxl.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mficjend.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbrjlky.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmdpxpj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuryrec.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyzmpco.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlptxbph.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sflzlzad.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjiukzd.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2gergfuwn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqoonadk.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrtgigr.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2igaubzxi.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2feagktxz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ehedjcdj.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkouzwf.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjukmhwv.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmqyndb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqycvzc.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kukazpcr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddylinpy.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mliirfrl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbupsby.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlwqpsa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoywpqgt.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ujngyzrx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbdvrzk.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oboacmdu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2biwtstei.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxnfwzt.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wzblnetx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhsqhee.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2dftscbnt.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvdrnva.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2xsyrcrcq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqsdawz.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzulggb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ystcufov.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wiroftyt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfwakaj.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2owtayjnc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuizjuki.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqypiyo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmmdsqs.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2eewjyfcu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2brsaikpt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgusibhc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtmsjtj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2smefuuca.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mslqaias.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2eelcwxgm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqphnbc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdymadde.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvpsiwj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2zgztmijs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfaftsrt.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhcgjzg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvleetz.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqgzmre.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2xovapzov.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mybbkryi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2uorofemd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsmqmxj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkewrjh.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkunyxe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2juifmkkg.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2apmcocoo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrcnkse.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzpntsz.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjgbodc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfxhoym.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dznqhrju.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hlumapaf.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gayrdhjq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjlriev.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtuncxd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnkdmyu.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkjiyvi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnendwy.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2heutbyzv.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvqqauy.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmlrhrz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2evrlfcwj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2knosomiu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kornmpwr.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2uoehilym.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2omazqbgb.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cdigjrzo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2judfpdds.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2duexozuk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjtvium.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2edagresl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2spcyzbgv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2evyuxrhm.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ndexywms.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqnufnr.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2paajawrk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhkcozh.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzccfyo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2phzzlpgy.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2shlkhjkz.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqanhjgm.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnsmlpe.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjalfbq.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yhabafxd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrmjdxm.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2mktaufcc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcowomz.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2giiqckkn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqiqupil.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxvfqxp.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2utpqewgf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2uajrbcnc.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvvykbg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrdbfxe.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnefkmx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2xcovjnck.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhtigui.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjfftqa.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2anhgrxde.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqudabd.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2orvfjfau.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgwxhms.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gncamuyo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfrbtma.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2eplqbpvm.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2msxvlpds.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgrfgqv.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2fafyhmen.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ordndpcp.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2miumcukm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2dddxuggw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zuubkvzf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwhacbx.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2nisyygxz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxvqooh.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fliwnagg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mswkidqc.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbsmyog.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlefpkm.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqubdjb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zboztodw.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2muizwimx.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkurqexx.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnkqwhq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqjracd.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvqfkyj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2vgaczrbs.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2apshciex.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpdtpzp.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjxmtkf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjwffkw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmctweoj.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hkiceril.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2elafsahv.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2comswxyf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyrwqyj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gscxbzsn.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdezdxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2slzvfquf.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2uupgtjgb.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2kyevujxl.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2iirdfdyz.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlpyfqx.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wippruvf.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nyljircv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2biinlmgz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdpmsvq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2kuaabjke.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkimxlf.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvzwads.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuyiovk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yaucogyu.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2psjhiemo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpiplyc.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgcbdqp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2borupzcf.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbcztkr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmnipge.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvobdke.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdtmqqw.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpbvmut.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdyzami.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pexmrias.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pptlfwfp.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2flizndps.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbyuxat.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhbtlhj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2otwspdyw.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlctbng.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lhiumvxe.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzxdrdp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2djfsomrx.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhhhmmh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uasqjoag.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvefzhyn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2botjofii.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbeekty.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzkwvnf.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gogxtbrx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2capdjqfj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfwjexg.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2flhogcen.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2caozyhet.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkmgtse.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkqhyzf.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjabhxax.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mehbvezf.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iudxfhtk.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eittnfjk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbkxbqh.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrinjvq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2trwhjrko.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsbclwz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yubpdbff.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ioymgixj.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2omankegh.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzwlbbm.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjglqpa.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2qsepacah.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzpjizp.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jshjjgdd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjgzxuo.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnxrkqy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpowaiei.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuflquk.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jspawxln.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyyixfp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elzwumdx.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjsgwyk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hookxvod.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbygsru.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2getmdwen.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2aoumwrea.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkodkilm.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcxduvq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2utjytxnq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pczykszl.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ussxnzyw.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2fwybpygz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pvztapcc.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ahetbtew.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxwkqen.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqdfbro.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbbgyom.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jlofvrlu.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbzxoxc.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnnvuul.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2urxkttsq.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zdidvljx.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqtqhvj.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhwhoep.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wehplrqa.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gzuhvigt.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2uitchxaa.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hytdvalg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2rbiqmbrt.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2slqfderu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhkurzq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2aqziuwpo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdcehou.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mttpcvzv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2evagbbih.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaerfqd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qxugcirq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyfpzpb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qomicgrh.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcezbut.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyibadd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mkiqcxsg.html


<!-- 参考信息 -->