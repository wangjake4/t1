代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmimewg.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2sugwvrjz.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2hbldvgxs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgizawu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkyuaxg.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrrizmr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgspnnez.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pupapvdh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2coknjomj.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2zdazmwta.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rinofnkg.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnxxmgf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqgvgtr.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2xiryoidd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yinwqkeu.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2voxhnfmk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qetzhepv.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jszewrax.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwlohna.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fconstba.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zoobloks.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhcnbjj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwdoqne.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2epzpjdls.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2nevccscv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2prfyezyx.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ghiibalu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlsygnk.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhvegat.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2mowfzbkv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2sywzszri.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hofbprmc.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rimwjbez.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtujpde.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsnmjno.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcrblpv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2umruiftr.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvacbdr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzjxezr.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2llhetzzx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ughqhzqj.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2igkrqtha.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcznlxkr.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtaspqg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoreecno.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmdnhyt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzhffdx.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2twrmvjdq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmmzfoe.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgmappn.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rytjsgap.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfjogwv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2aarryhuh.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jvaimpzj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjunbjte.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2thduxhly.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bneegjaq.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgwbcgh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvrmybv.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgqezdk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnaxkuo.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qyylqdpj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlspxptz.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2peqghgyz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhepaqzm.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fmoqqxco.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcitinon.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2eyusvpuo.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgdvwtv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxcmprw.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgzehny.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2qiodmlvd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrncbbd.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkchxxb.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mntyrcjr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzcukfa.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgctxjw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyfpknq.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfcynyt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhvinom.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2myrtlxji.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjgblnd.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnexdtij.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2cyudtrbs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2swwxnqqx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdrnhuf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqxtwzc.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2amgsaljk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkalisf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbsqxtk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2afetelhy.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnqgrgh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fompfcsf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtgqhtk.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdngmmu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnigwvp.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2njkpkcar.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfypjwl.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjrlrqm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhnhqmh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrogvmh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gchniftr.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2owqmaawh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkoxnsfw.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwnnlmn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkpfzlm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dncjgonu.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pdteqbxz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjcmpoa.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwdslon.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2togorigd.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lqayhase.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2saudhflc.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2cjobxinu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2olksllpg.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvamnxk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xvefnzym.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2xsorpfyx.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2snmijemq.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbsovzc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqmdzbn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rsoirzni.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfssixgd.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhffijw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuuthxn.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ajiiwkzd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fidpikdr.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpuohnr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvmhsxm.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ypeczrdh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2xabmadyv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xftzjjzx.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rllcquoh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbofbvk.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgxybir.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwiwraku.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmappea.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qaggdvhl.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyidwrq.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmnisky.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdejhtx.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2klpczsed.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2invjigkw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwykpct.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2umagjzmy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcwceie.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlmwdae.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2elyhtted.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajactvdb.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2pufrtfbk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfkwnxt.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nihsjyhk.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkhgflu.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgqnkps.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhvsxnt.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbatbls.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbadukst.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2waqieohx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hcaktwfh.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fymlwhym.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2waddavzy.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjuxddc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cejgyqrh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2bvibeews.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kevrlfdr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcmkhkn.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2oaaqdznu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpeiorx.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gqonjypp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxfuttk.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsbqgxb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2rqecrnot.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkescwe.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvoboho.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkqlmgn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohaymclu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhqyvrl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bheidifh.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfwczls.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrbztlh.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2nidyqstf.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfphxjzi.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2algkalyv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2leewgvpg.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxxkere.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2obkgikop.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hccvyhcz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2fakqpyrj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqloxmji.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrqqkkk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qommhvgl.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyxtvwr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2otdrvfsk.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvudvje.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnivmlv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpbpfrc.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2czxgczsq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2runbpkwt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2hczrardc.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2aviqntla.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqdfwnp.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ackbbbxb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nignubdf.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ojivereb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2gajzjail.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2waemzlrf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsqvtax.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rvohbmpi.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nogefqzd.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2stojwwbw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqxfvoy.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2avvdncfw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvwjvnw.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvgvosu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvuixxy.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxffchm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2inqiabnh.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyyrfhj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kitzyoln.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2yxygtdmf.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qovwodgw.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnkdadm.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhdadjf.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnfmiif.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvufwpf.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrhneye.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkyuirq.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ejytpmiu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eupwzree.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwqspyt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xikveftc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vkygveie.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdnurtg.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ziajzdxw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpleodi.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2gpshuxic.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uutpekep.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vsoilets.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnddklw.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xshojoip.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2slzwugdx.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2smjbjuhb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2niatrghp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lllskvxf.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2plwgytdv.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2pplrgjdo.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbdnzgs.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2outzqwat.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvanqrx.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hmglnkgg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmghwvks.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wrreasog.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kprrjutc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlitdzw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibatspul.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2cftflzio.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjbrhoj.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2soafwggd.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2emjaqpmi.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gknqaxxg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sazvygog.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2drulmgod.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdhjjds.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnxlaab.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyfyqzv.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfrreuw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvzlwus.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bggwwtlx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxybiap.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2bpigqamr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vesccqri.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zdiukwcs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdsjtvc.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjucoxr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmulfhi.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgbrlyd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkfmmqk.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2eedwgjxv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cndlcrcz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzgfoou.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmxsino.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfnllga.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2eywylqzv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2avutcpaq.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvvcvyb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ubeamycf.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjzkcpa.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jsubdcty.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsvcetp.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xfilpcwa.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2savcdhes.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2djhomwto.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2deyapzhl.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xlaxbwtg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2azkflppw.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2znlzcdlc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mbihyqfa.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mkagpbnl.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jwufunsn.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfwjmxu.html


<!-- 参考信息 -->