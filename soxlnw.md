代发 wailian999

);
来源：http://dali.zhijiandao.cn/Article/details/gt2azcrdhbe.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqjxpck.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2docxrslz.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iywdvbfh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2szlqkhlz.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2twfhearm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wosvlihf.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwhpqmd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjgjzac.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2wwukplsd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnphugum.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2loxgvqei.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtktlgm.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2awmyyppj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvrakng.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lihpyhcj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2urcrqngy.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjszrxr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgzcved.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2mznxyjtv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2toioself.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzqcbrt.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsfvakc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dasvxfkb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhswbun.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2npwxtcrg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2koblapwl.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rdncygtz.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzakopey.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzwyhoi.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqqmjxp.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wibrhjpm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jirpsoka.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhcxteh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwrdjle.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kyriqkey.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlahlbdi.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2emokgakk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2almpryab.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuntmkv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2eljdpylv.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvaqety.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfefbtk.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ndphnpic.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2sszlnbmj.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtfptou.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eybgjrtm.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbjdmve.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2auzzpfoh.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2anxgkmfz.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfbfasi.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2oceanfzg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2snwwqixr.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqbulyp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayaeylev.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2oihgoleu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzveprj.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2llbhgtkg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nemdtwjj.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pksqgcsh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bueuwxrv.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcuuvzv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydefsspi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2gthylity.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhqiwve.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzuwywdw.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2apaqzduf.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2vdowrikf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsjbtxb.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzpwmoa.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjcazar.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxggyino.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2toembhjp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxjralu.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fuupvnls.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuofkmc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzjtitd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kafsjovs.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2sssdvhja.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zfayrkne.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhrsqqi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2elstklao.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2udotlabh.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pciillhu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrocjps.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgtxgrx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvxxbby.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yamkuxsl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fdiiuurs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxilzzg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqffrbp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzubrbtj.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2khzalefq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2plwdfcoj.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjoyctp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ectiepwg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpjslrz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgysmgvf.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlrazhi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehoumhvt.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtscgbx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijoifvwj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2oowtpvgc.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwmkrhz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgwyqoh.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbnafcx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gilzdctz.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pgiwwiov.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdehnjro.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxkzdbt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmdxgqe.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2flbahcns.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2aouupodv.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2admtqnqm.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrvagff.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtbetfx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2suzzuvnt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkwyhgk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wesfnmuf.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lajjmwnd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsbbzfx.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2flkhtpgx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2djyacrxr.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqwasgj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyfzuct.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjykdut.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2smifpcls.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsykisq.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2pwoxwokj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhirkkq.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2epnvxhgl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2evxrqikl.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2funjjbqz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2nuknlqzb.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmkuprs.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2elarwonq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkddhsp.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfijovb.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wulshsdv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxlvagu.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsdjnet.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfalwezq.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkfmjfv.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uygqfvlv.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovoygraq.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvyaefr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzwivuw.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2jnufqeyv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2omlzevze.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lveychwt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmtjhou.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2farcjxwr.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2glyajwbf.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2wktbetqo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uzuhremt.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kidnsoid.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwgzzvm.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qiptyikt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wthqbfie.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2sezxemcq.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2aljrovmt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2klylcoys.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2uhyovkjc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvykqgt.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnugzat.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2jgiqkscg.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kydxwoiv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwtvhsu.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbygmfn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwadfyxn.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdzhhnz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmufpprh.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmoymfe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifocpgdy.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfctvxg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaivtwhh.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qptjgzcu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sltdytrx.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2svyeebpk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddywpitv.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2megoxcys.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2thklymoq.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcbqjax.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2gntwnewr.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfkbeqy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwuujxr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgbohqh.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2acpmeath.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxcovwq.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2hcynkpyr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2chfzujya.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjqwbst.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gvceflwa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmgshuk.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmgxjug.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmfyxou.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zouruhhh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2thcclaqh.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfgndyu.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2enamzfqb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjifrxm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hpprsizg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2orbdmyks.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2moeaubcf.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iezyzbbg.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqhhpdi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gninszyn.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxycakw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lsutsddf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2huexufou.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyleixy.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2niyhaisv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oxozeyiy.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gtimecip.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nydckdim.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcwrzyq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2naowtgmm.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlptqsqg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kntlkbwj.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxnhlvh.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2opacrjfi.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2defcuidh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsxueix.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxshdum.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qexpveku.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2odbzynji.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vacixwcu.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmuajsm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2amdlnuwn.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvczatt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jykffgcf.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2thqwpssu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2imaclkir.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fiixrpxy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2blhlisyg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2insxosec.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfiwbpd.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2expjnvkj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbnrxvw.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbfqdae.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2adjheamy.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsykmom.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtyvczb.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzgxacx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yckibktu.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrztgwf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwclroz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ipflxrth.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhsfwok.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2destmgui.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjacbols.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxjrsko.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjphpge.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jyidifsa.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzbqogm.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtnlyhj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xgplybxd.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tuffjarh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcvrvvb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oynsviih.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxpacjc.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtqlzsg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iztsyodz.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbzwvco.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xoacphkt.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2acsvnrzq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2amiahidp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gtufaabk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzojfqxw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yaznfdbh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcdeafu.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cifjtdup.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrcrvbv.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2gywzdobi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hvosaccr.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkfqydx.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wysaclza.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yorhjums.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnmyzpa.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2trimtrca.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwkdoou.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgiszml.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tozgvmvm.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2csmiqfez.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nksmtaii.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ofranbgg.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gobggvgz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tvaodpmv.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhljkvw.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wnteyqtd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrmebcq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tujjtjre.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2efxcclhc.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kimiutuz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ltoqvnsy.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjvkcmm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhtxglt.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2homcndfm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nslmkjte.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2npgcgxhx.html


<!-- 参考信息 -->