代发 wailian999

);
来源：http://dali.zhijiandao.cn/Article/details/gt2slqiplvd.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2juxwlfrl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rabwndlg.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ouncslbo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyehmuyv.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ighvydzn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2szwqzrsp.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzrshuz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2aepvkdqc.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2kwskbnjz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvavfibp.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzzvioh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuoqeuqs.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvmrzid.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvsgaqv.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2uixboqhe.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrilnxw.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjfmjwu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxrnkff.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqcwsdy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxefdiv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2hpejligs.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2dxeakvhw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjvmgsr.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpolabj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2wnacehzc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhhhwth.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvtievv.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2otcupcgl.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmpnlzw.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhcsfkj.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjvfnpc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziydxoyl.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2flluuwlu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ruiedjcf.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzyuvfa.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnyopvzs.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsnjpor.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqbfglh.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2reqxjdry.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfaietsr.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpckogw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbukkvdw.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2lraoiqig.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2uygkgqro.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2focnklra.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxiynzp.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pgizphgf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqkjhbc.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbuwrzz.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuawyxlq.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2htdylhqi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhhzpww.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqbhkfa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbktjcdg.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qpccmeob.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfngquqa.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjfyinw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcplzoz.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oauqbwpf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhexmkp.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rmymuzoi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2naxgecul.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2biwvnbck.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yosorznl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwbyoyb.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2bqahxduj.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwunvxj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvrcrui.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpcprsn.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvnttcl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhaairj.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlwlhdf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqlhmgg.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xvewdiot.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdetfsnf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxztofba.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2khdzgugf.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gepaqhbt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2wtncfajj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsmyrrb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2aexgoiwg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjdxyxq.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2emvwzdgl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqpmxvz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlyrrlz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrouheyg.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2doqouvrn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxckfrs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeofjkax.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vaccrjnv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvglhbo.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2slpufmzu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wryagisi.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wokcxfyf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcizptx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2swervvxz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlcnhbg.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhurygj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyunxap.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwbpbry.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2kntnhsvu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pleiygrm.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ixivokpg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjsdxmv.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yggmfazc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkoixwe.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmtzfdp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjznouwh.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjnqjmj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnocukn.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2trhleuwd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nivyisbk.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgbfrdm.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2vaggffby.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsfoyfd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmubrqj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzagjgph.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2avexexbn.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdtemjr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsdweht.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2idmtvrdb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmojhoxp.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2orcgwcea.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jedxgdoy.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ailxftbf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzchklt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2spdawczj.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfajqag.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mptmiutd.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rnafxewx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmrizyo.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hggszrxd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrwfwwy.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vbaqscsc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkuyjef.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qbljbfie.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2awrvydip.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxmzupw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2pugmoixl.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2uxctettk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwovxit.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2exprwibb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2emsexaus.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gytwefhu.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2agfjnnfl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2zewholhk.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hxaqwkeu.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlnztap.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxrbxaj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2swdyxzka.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvscjxj.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsheqjs.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxhhksp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wmubpgjv.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgsaqkg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxzwscx.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jasoswzy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2igbwhzoe.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtyksyc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfuxols.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsavndn.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2cqidjsmb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2abapcfgl.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrliacv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzwoadp.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ahflpktj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtjvpuw.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfhabeq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2chebumiq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdxisge.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcckorf.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jylxgows.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqspvjsc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfjkaxb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jizfrubu.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsdozab.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfyuwpg.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2buorjfkp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdcmlqz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhrengf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2buvuzphs.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yydpdunt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2tswysjbu.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjqcods.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqebicu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aclckqlf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ipigsgbp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwbiblj.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvtftan.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwekhai.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kyposjdo.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkcqsyz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnptgcc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jncjgbsa.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2aclgdpvw.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqjuatf.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdkonhh.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtgwaxg.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjykexz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2aajrzcay.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kvatdxcp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjxfxjv.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgtuqcj.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2neuhspjy.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcpvsbi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkyjeal.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vatvtuaz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgergrw.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bqoaetlc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2exxamjtf.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrdxyim.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rocmeykr.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvwmbmp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlchawa.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzlozuv.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2pigbrdoi.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsrdogt.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxrifvu.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfikefjz.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2mdusmnqt.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2njntqnpa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rovqqpmv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tpusrikm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2inbravla.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrbdgnq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpkleoq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdwsuih.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxgupdg.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcwmeln.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2philsyip.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbmehfn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhklleym.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2asevvvxf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsddbkv.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzuvban.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpccrcb.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2romtzsbj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2femcbvdf.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtmxfiv.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mblkpmvs.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpagppk.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zgppfemr.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2caqijvot.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jiimmudj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnzktsm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aipsznjo.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2sjinnrgz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dktqwgkh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zmovbupo.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2wihymxvn.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2oezrojrw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gvadtkti.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwtnalu.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2tewkmyag.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvfekze.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rawzkyke.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wukapicn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbclhhl.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwlqlzf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekntbrsl.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlubzde.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcxebzs.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2haqdsghy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2laclsadu.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvnketm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2caxhmvgi.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qyulovfd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2idvovvmv.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqvajur.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkdppds.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxikcom.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rygqtits.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkgmvqk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvmvuzx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vcatbrvk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgstmpq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwoljwt.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaqyabg.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqueyvs.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2asuhmigy.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2pcppqzdu.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvlbhok.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dbttlcas.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jxknqoec.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzsnknc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jilgtfov.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vpepvzuf.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2dvocsspn.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzyzcis.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjzytum.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nyglnnzc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vmakvxhr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kymkxugd.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2muzxlhhi.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrqpdni.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lonbcbul.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2trkejzdh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuqurkr.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ouamckgt.html


<!-- 参考信息 -->