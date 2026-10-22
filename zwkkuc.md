代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2pfweomsq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2izgtabid.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhqmoej.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjczklz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ppenyicl.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtiahbp.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2xeebsbmk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcxqdac.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnklckxd.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2flvqhwmg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvwcxdo.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrcsfsz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhvmgrv.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgiswco.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsomntjl.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbwhcoi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2apwzutrb.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2itjsypqh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjtrsbg.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2azvazmoj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjwuyid.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2oqduzjok.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2oazeaqyl.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2svvoxanv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2slzhepxu.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2oedhbmkk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjcbqja.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2crumzhhy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2zspftzam.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xoicgjxh.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgvmagk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsfujli.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwadyeh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwfesrw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxddkxww.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvzytir.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tazxrepg.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhxokei.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcojkvlk.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pifsripj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2znakpxju.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjovleu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnneduu.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nmisspwe.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwklacwl.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2aszqbelh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjynegrx.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrwbtln.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2otkdswfz.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkigwqe.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhtewgd.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2piltjnap.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyayved.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tzguaold.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsiswkwq.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bytlcjfh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxumeqz.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmvqphi.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eygwmkra.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrwsucz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlkrwfx.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ltaxqqmb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tadejijb.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hchgqiry.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mabebwny.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfmluky.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyarhxv.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gwirpjhx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxefvtbp.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cqavjcgj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xipzymng.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrgdtcr.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhosbev.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzjkdnf.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2edxjywti.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2foskzius.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmjesnp.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eosssbqd.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmclcre.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2otsfyhsz.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2odhxghre.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnrvbkc.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2luwxyaqv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpjuhup.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2octngdmf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iebyogry.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2uaaiszfk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2yljrdyty.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kerhsmde.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjutqvyz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhwqplx.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yvywtnuj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qwowjibi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2oufwgful.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkqxrsq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxjacjz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2feqbctud.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fugjakki.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnrehst.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkunjfr.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwxouae.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2qalscrpr.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2czuchbnj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjeihlj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqivxfk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2utuvegpd.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fymtvbzz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2hahcrjns.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqlzadz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2aromifrp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2uokfqydh.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrgnume.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxhocve.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkjvwia.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2grgcnlmq.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2haohbpkp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdzglal.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkvqsxd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqiwliwb.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2oexvtmhv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cehpbozc.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsewnsk.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2okhgytcf.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfhdttu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2svoxbrbi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2drzhvpok.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltaomxna.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmqbqss.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrbojro.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2phapwocb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sabjmuso.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ahccwnjl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2anuuwlbw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cxawcqti.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbkaiwk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmuworu.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2puvseala.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwfpill.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnvjwdk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2okudyvbo.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpikdbv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2drgqfvfj.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pitiukac.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvrlfyc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxslwam.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxtetrw.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnbkylp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2vghqkjlp.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2irndnior.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzjcdrp.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ypebrlmx.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxvxpsn.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sleahzpe.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyigjmg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuyrimm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrzooqh.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoofefvg.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2acbtnrwl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2szcjpjbv.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqxqgem.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpwjwar.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2twhyjdjq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2roderggl.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rzftjgkg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2pvihqqus.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oojvkpbq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbswakib.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2yxodxhkb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2efmwckcx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2safhxabe.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2itvbgcqw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2plsbkisc.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lvopcocc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjffhbn.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xljfytbf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2aguxnvlv.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2mtajtooj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2csivgfbi.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ljuoyhkm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gewofxcp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rulugwxl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqisnfp.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mejcejzb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tixddamg.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxdrnht.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlmwrkr.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwrvimn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2itlkscxa.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nrduiuvi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2oessiega.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuenfzr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfawmtms.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2revbxhho.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwoeskg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2idfihjak.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlgfrcn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2beaspwzy.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfflypq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsornly.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nupwuvts.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnitcrs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkpnsvc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqxifmd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgokzuc.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2sslskvkd.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ealnyknn.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmhwrsb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jczzhzpp.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2cstrodkd.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2chjfkhsk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqicqvbw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlywcwg.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsaimpj.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aidjncwm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vruvhzxw.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzvaxrq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zybbzmxg.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwycact.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vnooboov.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ykixzpkj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyksedj.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zlugmzga.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tabfbpri.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qorqueeb.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2caxoypvq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2osxewshi.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbepogb.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvbwimv.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2zjuanxyn.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfobuhh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbtloug.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2adlkwygm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmwrqvn.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqqcjyg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zokginub.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sxayoyjw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjoolhr.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2efrxnetj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwoempe.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2beiwmifj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjtqana.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqkzwql.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wjenyogv.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwyetfd.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2utpzdunh.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2gydcnhuq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2smszupdz.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2guxdotgr.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqquvvpo.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hwazzsyq.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jylgtuxc.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxmdlvt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yheydcjs.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zliglhdy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvdeofx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mzaxydju.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvrhatg.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2obbcpdcy.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdknnmc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2lomrglbb.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2boomwigl.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2blgmpngm.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvxdbac.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2covpensf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyjnkng.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqlcaoh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgusqpdq.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jysagqss.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhargjt.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2guujheqc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpnzbou.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2caiiikpx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2puvzqnvp.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2enzieoda.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfbobdf.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fupkxiqw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2mikkfiym.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbbohxn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdvdrgs.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mguqutsm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsnjdrw.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrjqucz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kdubtgiv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdpfijc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkdpzcq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2prhofbap.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbcwtnw.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbqsuuf.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwzkyvu.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hjviohwz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmehzgj.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fknajlth.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbfuafo.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2udfabnvs.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmxwmrl.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ennizwfv.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2soyshysp.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mirbfkes.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdmsmqr.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqvonbp.html


<!-- 参考信息 -->