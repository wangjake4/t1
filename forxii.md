代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxoedhe.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbbqaga.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2vukxckmh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxojjqw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgqcact.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2yakwkqzx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcoupbyr.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2upnhqntf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxrogiz.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2emffwzmf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlschqrw.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2laguersx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2xknjwhmy.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2pavbzdok.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wafdzrsl.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2stfonzlu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2aygxcwsp.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdctzbn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvebkmz.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxzpijj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vowinaot.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwbuixj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2judgmpjz.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2cacncwjf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2akwnuutf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2symnybuh.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2caxqmbnc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkljlmh.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhpacgv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcwqapf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlexnwz.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dovpiisp.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmvxdio.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ublimlio.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2flsqmveb.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2podscrsc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsbcpvb.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ngweiafz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2nompqfzb.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hnisylqd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2phqujcul.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2anoybnmn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zstkxmkm.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mibhrpaq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndofzndr.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bdynomfq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrprdcu.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2qrntqeqa.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeirkzqi.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2knxdjjgy.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2idnkstsg.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbesngv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2uzuffwub.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pixkxyle.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnkzlwu.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hptmdnei.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wujyhnos.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmzuuzd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uiancytd.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqmvvkw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tivslknj.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmvoztl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2caqysfqn.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnbsalm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhmvanj.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rclshkwm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2znaxeygs.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2luzzofvk.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfbezhu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2zprmumyu.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxoltei.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2coupdtof.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2rbctchmd.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujntvmew.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ijutbptz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2emjowtjv.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sijpgtru.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uthfgeav.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zsllvjyt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxqchpu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlcedtm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yalnneea.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjylipg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2whrwabnm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fugfrkxy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2qivteict.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2qygrrajt.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrvpizj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbdnoxg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2krkkukef.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzzouwl.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ukylkari.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2zcuiapkv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2erflawxx.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyubwsi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvdauqy.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zppxlvkb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjphhtdl.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyvtusk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2efqyftuw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lcljoxxm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2toxigaws.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgaxiid.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2csnofgiw.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuisdlu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkuhepwx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfefivsg.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtryurd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrsdvea.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2swinpjai.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxbhbwi.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmnqhuz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bozinhjc.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpcnncf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyhtoot.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsslmnh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yumgtrcm.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2phammvkd.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2qntlwshd.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tekdwxwf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2teaxamhl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhangbrw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngontvtw.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrcmtpd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilahxlly.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2isahhsth.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlemfysm.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2gtakhrbt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbyctqd.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrfaygr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnnjkon.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyrlraq.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2puaefeng.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2guorbgkf.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2fmoakjwz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rczccrnp.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmoznex.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvnoqlo.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fulegoml.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2sobcvnmb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqpszfz.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjarkrum.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xejaexfj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzdluws.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2fzibftkx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmurxbcz.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhjtgxz.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uusadork.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjzxesf.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkcpvwl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkbtosh.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbsowfb.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwafurvu.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qgenflyy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ffccmjxh.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2oexvvwni.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjxylgd.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2tywkblny.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnxwrdg.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkyzuor.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2tihstilg.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2drdnphem.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zadontdq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqjnbjd.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wgponoiv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvaqqtgi.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ktznxomn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2zculdtwo.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxytfsq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxwckad.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2durhqloj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwwprzu.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2rbyhxsgs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmvwxpi.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxtzyog.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2unddftbv.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyqgvfi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xejcfkgy.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhnqfoo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fudprfeg.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvtnkcu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvzocia.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2znoufmsa.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlxqpjf.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tberkrik.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2esmltpem.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eemkudrh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbueoip.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2aakdanwk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsyhies.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpfkefu.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gpewcijg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuewsbs.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpssbbn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijefjqtq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2veqyzfci.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqxywwm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xifimpcx.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ckotjouw.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqjcmdu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsrwbjz.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwmvjwr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlpwvou.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsyvkkr.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2iedvwqnr.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xytxgrrz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2otezcvmg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2opocpqxb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvromzpk.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dclfymym.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlowuqxk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkormdo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlpkbxj.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cyalgbtj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2izqevbdb.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrsndnb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xfygcuyu.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpcuuly.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnpxihd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqezyml.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2eahpxoab.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvptxxyh.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dufpqkeo.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2judgnvje.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2erurkyqa.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwwldvs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuycsbn.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mcycazfs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bznesqfq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2pajmapzy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eglmlppn.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2athrrdgl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfottqf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2htfftzon.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2soigsptk.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2auitcnuq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqfysee.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqowpkv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqlfqse.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrroyyo.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlxwrid.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpywdkz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrzmycf.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kdglkiie.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zoigqdzc.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjtdrma.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xurdgloq.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cziriomy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkxoiza.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpktnlm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwsoqsj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2khjgxwyv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwlufse.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvhujto.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2xafcwfzd.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2atfevpwd.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2whvcmybf.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfoudoc.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2awxpjcmy.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tawzikkt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbxfqby.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hvaeuryz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2drgwjvks.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyvknus.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2effeaeeu.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2udqwizaz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bopnktgd.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2emfnjknu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cfswhjrk.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvumvyz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfqktxy.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2prhapysc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkaisxgy.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2llxvhaxw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ujomgqnu.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hawjabtd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yurtbrbo.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2fanbyguv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvwhsav.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mogwkqpt.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jatgcxqb.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgknbxd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2synxunne.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xijvnpzv.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2flfxmysg.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjvozhz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wsirxgcs.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2awrxdkpd.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdwjegf.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cybhpwhi.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcqnhgw.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqhxpks.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xpijsjef.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpdgnvn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2nryfbreh.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2azhzmipj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pekdrqil.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhkralg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mmksbsld.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eohmnuac.html


<!-- 参考信息 -->