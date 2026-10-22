代发 wailian999

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2mupszyvx.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfdvfdt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckneauki.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkptdac.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwcuakl.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cksfqysu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrctbogr.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cmszwpdq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mruneinu.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmeqqee.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2segcecem.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkmchmq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2htvjmonh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmiptnp.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2qdinhmwv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnlmmqk.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdaanbm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ciscclsw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzarrdf.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmkvdbk.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqrfrdn.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjxhoff.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdoxhqp.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxuazds.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyfemxt.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxcxiug.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkyjwtc.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uxghkzxw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2wukxqdrw.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsybejs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkrixhl.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bbepbcwd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhaodexj.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2axhixoiv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2mptfnxod.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvdgleq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuirvwev.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rivqcjal.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2auvrrzkl.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwkftke.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzslxfv.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ziapdibj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2twsssulc.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwoyoycs.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuhpyeo.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2erntbezj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgazrftq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2apboilyr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsdmcdo.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnbuwqy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfnikrb.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2klcqwaib.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsizlce.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvmllow.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsokdow.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2touaqtnw.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcdjjdt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyyitze.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2dveyhqhk.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjvyecv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkqoymv.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxmqkrj.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2emuqkgop.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcsqdpum.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vdipqbrc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2icipvfjv.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtfdzlq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyuxmrc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2xoahvwfh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzquzbd.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgktftw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2hhaxuhjz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbavewvj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjriynh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghypczfn.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2refiznnv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2renqxyut.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcmwxhe.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2apyfnfma.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcqiqbn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2uskdhkmm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hphtitjr.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlcuzyh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2pirzlywm.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhkzttr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2naqinxkm.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hdidypby.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2eooenpbx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2evibnxha.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2odxhnwez.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzvvwvt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2reybfobt.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2twdcfgoa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2csfrgewt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2khsghuni.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kgacppxm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvegdjv.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ppchlatc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqpmlnn.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2imhneulc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocurcsap.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2aebmtjsq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfysxztm.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mketewik.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtpdawx.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2sebkrwpd.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2unlozrik.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ammzchtp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdgfzpd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbchvwyo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzstfzvl.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nysqujxx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgcjzfm.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2frcutoka.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhnoyzr.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2fimjrwjx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjsukhh.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2oexcrsqw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxqgjsf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sthigtqx.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wjljzopk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzokxsar.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzbhjeq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2elahmhsx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kesavxst.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2gusonwxv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zywpzivy.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2szpykeia.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jajmnzex.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtusoaf.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iijnlrqx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2etehoadn.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2qyeetnti.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhyiqzb.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdmtdmz.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwdkwwt.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkogqog.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2oluyzala.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2haswzkdr.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2avmgzspd.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2geujqhzs.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtoalxi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxgmalk.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nemyetpk.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tewecffu.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2khfrzlrk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gaviaoer.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2uninahuu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwlordr.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nxiihwxf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tphwrwhr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2upahqvmg.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2icgfmzgj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2afghgqrm.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjnxted.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2rroyfseo.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwdfdzn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbyumgk.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mcutyqzk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2mwohdidm.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhbrwmb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mopsqhaa.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwhyhsp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rspzvzmv.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zbaentge.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnekcvjh.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtcxqgw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bagvvvfb.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2odckmtjd.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnoayzfm.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2cimbbvgh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwnuilg.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pppgwryc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2foenowjy.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhrvlei.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzgtqoc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2oogfbpic.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyyzcsm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwvbxit.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jaiamudh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zqaorltg.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2inzviblt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2szmescvb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wfheritr.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2opybwbmc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2frzabpar.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vdomcwab.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzfyrfy.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2dhprymxf.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2rkechesn.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmevbnr.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbquzoz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbgvmns.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxvqrhj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgzuwud.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwajqop.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkkeszb.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mclcdicv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpxgnuf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dihvezfb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xapcqakw.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfxejkc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2epcsvrtg.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jitjwyum.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkeeilp.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwsfsmz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgmyptf.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwdcbuj.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2woqnwsre.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdygxtqk.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjrtwdy.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtcuvnk.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqrcpwa.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlzzsxi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aomqsngr.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mqexuktl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sfczklhs.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2gyuaxcyf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wexctvnc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbvhuiz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvnpmud.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvmeqzs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbnygor.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2fubvbkus.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wivxxtml.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcdconm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2duuffiwg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmtulhu.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nytrxult.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbgswji.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2huokdykk.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2idiktdcj.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xopkgyko.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2agthufbd.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbgqezk.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjtqcgp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2afbzgjwh.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2utajzbvq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuolrhh.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2eepmhtpx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmlqiwr.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqkgsif.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkkglhk.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzyhgkj.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2punbbvgo.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgedxoj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfgurqn.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sykxidaf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2amkacmyn.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kyglojmf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2cihlxmao.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqtzlkf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdaynyj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2guefdlsv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yewcnmuz.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bmukzkoy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqunjwx.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2azuoebmm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ovktklop.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kkeimhyh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2egoqjmfq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bldtmmmp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2dklnsswr.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2udjmqtbo.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcfvkco.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2lnifhong.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mltpjsde.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2syzpfmoa.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2euiftikh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjxhdny.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ylylvurx.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkroxjp.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxekxgk.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2eesqhssg.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgzomqy.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjqvgaz.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxbmnxx.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwjcmea.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqqbwkg.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hmczgniv.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxcptqn.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmolllb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzxwtqu.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ozeplwnt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnuugrt.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2luzfskab.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgdqqvh.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyvowvd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2imysgtbc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyobvbz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmwflue.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyawbqv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2asluckdk.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2klinppwd.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uftvertq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxarhlt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2auwtlvuw.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sggfareb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgtxijy.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2kltvksuu.html


<!-- 参考信息 -->