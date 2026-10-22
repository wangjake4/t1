代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2iaixknpk.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yniadavn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrnyjxh.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwbbtsr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zntqcbin.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2cdppqelg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2okqgaceg.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2smlymzey.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2bkboaumh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvuuuhn.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2llutrwfi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkuzifo.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeodfkb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2qunwihyd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2eawtlbrs.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2pgecbeep.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nikalzcl.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dizhaveq.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2egeucftd.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uhuffnmp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjqkhuv.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzatnes.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpoxahv.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwfbgrk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbefxbqu.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkzwxmg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jccmktqq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mpecyalb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkttzvmf.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwvvyeb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrknosr.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbsbbqy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwzciau.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcjomih.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2asuchwrv.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kcogeeoh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hktnxrkv.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2okfkvcsw.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqevdzh.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2aoigmvsz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2grcuadxo.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrlinoj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdavwgfq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2eavmylif.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwwkbwu.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzbvuzj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfecglxy.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgwnrwr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcibdgya.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2enpfzemg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwytfpaf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwjgvpt.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxldxjm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2rszemihh.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2uogowsey.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhedbxf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2bawxkkhj.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2brmcnoya.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfxykfr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgorbce.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tgklpshg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxitkkyq.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nssiazet.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yldkugxi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxzpgmr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjsvwpz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2iksdtuyd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuswfxz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfwktug.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykiudclt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2buxbuinw.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxmmvsl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyrhzrf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfhlxbl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuqjrpw.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgyxfpk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqmbuzr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbvvxeh.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzvfnwm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2upqeuutq.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkwflkz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwcwwim.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpmuybk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnjiszw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbqfhhh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjekawd.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrjmjyn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzdywqe.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2geutoifk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhyyouy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ergnstgz.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ftznkcxk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcobmrg.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kejitdqz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yhupxlzh.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2knwiqljh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oloqywdr.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2imencpme.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2btblarsg.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbzdatr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2glvwgdhw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2edvbonku.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqrnyjn.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwgvrpz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2njjhvwia.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgubchj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2krgmzbjp.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2okhsefgp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfnoxmw.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lcyvpmlf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaghoero.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbhdqav.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmtwfxy.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dclyujsl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfevmzr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmntjiou.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjlvlsl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2azpwioeq.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrikltr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2brcoevdw.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbuimys.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2blbbbkxo.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yntozpje.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2voblycxi.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwtrlii.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbrouty.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjuipik.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqveueko.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzcfruc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhxpslv.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnaquda.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2whjwuhqy.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgktgxg.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdvdngd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2skibyohk.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzjeqgo.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqbnbsg.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2fisxnkdo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ibouxsdn.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcgikux.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlaxzhpx.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkaenbe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvuvpdx.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fktfhjke.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2nkowzfvm.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rncxzboh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzdmldg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlrkcdt.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrvmpsp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvizynfi.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2pmliqmln.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2lshghksq.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrzifec.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2qlejwtsv.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkkmnaw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkuyqda.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrlhmgl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziiereeg.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eigwbmgx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rehywuqp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwzdomj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvslhhf.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpjamnh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sleiyadx.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxzljqq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2robfpjnw.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2svsbhshp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrzlejw.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xiixidhk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ukifijaz.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dovecvne.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqegfyex.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsnevsm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2sajlvpfb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2azhcrbza.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fymsthba.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wtblhesv.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdsscye.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqhvias.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjihsdt.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkktecf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdrxejt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrivniu.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqdjitx.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vzughmkr.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdwxtaf.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rakjlcho.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwrrydm.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdztxdb.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pplnxqhk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxvsvjt.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2raeojybj.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2abtdkuks.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkpsgvq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xowyxibg.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpahajo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvdykfe.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vobicqtc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjhsubz.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fuoisptv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ahywazyf.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uanjvgcc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2celycbup.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ltktnaho.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcrkjvq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2luklippo.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuuxtop.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2phjlkyrd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzejvzd.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nscmybve.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlipqcf.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bphdgtrz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2noolpeng.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2nbatqvut.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dsluzynn.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xlakqetp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wjctibxb.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkgfbbc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mrstruaq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2enqclmck.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgapfsoc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrsyyuc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxjqitr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mhayrozx.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iypfnvhy.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2koqfbgpm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzpqmkr.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyzkhxu.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyiuqgx.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqwcgad.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwvcmzj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnbvppj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvqfunl.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xuewutzv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxxsniw.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2azddribb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqanavsm.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfecrgu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2utiwqwla.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxrispu.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhtebxb.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jicmhkje.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2rhngjaet.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2luxftcxt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vhowbpux.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gqodouid.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gzasiuql.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmpgeao.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwthxpju.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2onskcflp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbhubau.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2emgyygmw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqbpvyj.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2foznbpph.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyqdprw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2uekjddml.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqeipmnp.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qahycnuv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2cstigfmk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvzmxad.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukoxtcll.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwbgjoe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2axfhhlip.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kykumyhl.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2eooqgzab.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sahcuqxw.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tysazlxc.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kkujusus.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2klhwgiqz.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2cgeknhmx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2swdkphdd.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ptziokbr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yijgaymw.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtxbqxl.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbrfjvr.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kevdvqqf.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbyawef.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vekqfdvt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2texfuxnl.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjraphu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eeiaqmgm.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cnligkru.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2djwffhqj.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsgpiyo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjzldqy.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ylthcuhr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2syqfkhag.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2vryqyrrd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2xyybuxaf.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2msnppmob.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzhpyol.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwlktwg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2khdzgolt.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jzubzdcl.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtfvkuy.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ennwjrwk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2dymukxng.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfecdei.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2utzlmtit.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qofmnhce.html


<!-- 参考信息 -->