代发 wailian999

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ysojxuce.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnbezvz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgcxnhs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcxbdjx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbtdezo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2nskghsmj.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpculgw.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxzxopy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2synhkxvq.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mtoccocx.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhufskk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfxnwjb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrjytbf.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2uwypxehp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeziidqi.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmjgkob.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncftgedi.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2bewqcsdv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfowpnu.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkbgift.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2oduhewwr.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2vehcboyk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuzbfsh.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgrtvtv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2klxyyuav.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpnwbik.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wafipvjd.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfcmjdr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2glbqpxud.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgenooz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsccmow.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhvbyad.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqscbaz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkvpvfn.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgxbajj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2oalntktd.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwycfiix.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2emqvbsgw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vncixcvj.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dovslpht.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkguyixj.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjhkfop.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziiikuom.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhwgrug.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnobdjhx.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhxmkha.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdtfhic.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hotmajde.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpunxjr.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lblbtmme.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrdxhro.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrwncwp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbkovxa.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcxiaqh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnujtpl.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2tjncovqz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxqpboh.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwquwhn.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2syjpihvj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqvxuwx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2rifqnmxl.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fftxgbhw.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kksaryhg.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzogmvzh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbqsesu.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zidhcrqs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tujsrtgm.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvxddrw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2afxpsmky.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ixijrzmj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbohbtp.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfvouaz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnbyrhf.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqzmoch.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgumish.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2pmagmqco.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kyyjxozn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkgmjbj.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2udpvovoy.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxktkzl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2kqunhlzu.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkihvqo.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wpykwctl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlokssbi.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eigcpgvz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrglvhyi.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnuirge.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgofhooe.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdsiyrx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hijdlfvt.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wahcvety.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvkiidh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgjsxht.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfoxzvp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2txxjbzol.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eidfofhh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2usxgxvsc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2czdgftss.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwolkokg.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2idjgrhbb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ycishcph.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtphnear.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2urvwnjnd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2teqmuyoq.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyymgsz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2frruhvhw.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sndxnpuq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbtdjaw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpuzfbi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkngincv.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2obxaxdtx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdyseri.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbeagrz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkkbujp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2efotpnps.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2jdscbslm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmwzvcb.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqnurll.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrprfqv.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lygajmlg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndymmtto.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2tqturcdk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2adwrufgd.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxwhypp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhuimvl.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2spxskhwn.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqniofne.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dayzcmzp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wefsktzr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjhtlvr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qricyool.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxjldum.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsuynanp.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwsttbd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iytrhxtv.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2iibwxzhm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dshkkzvh.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjsrxik.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zusnqeik.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntosmimt.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2atcfcodf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbhagxl.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2niyuhtrz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjncolfv.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kiphmtfz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdufull.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwznbkx.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmogxmo.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2iqamlisc.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzdfoje.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsxvvpm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2imddrnug.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqaxdsx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkojcaj.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpeemmb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bidulvry.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2brbqdhtd.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2kunxbhho.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqjunqs.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2cjazshin.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ielobcwe.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2enzlodjd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2herqaeuc.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgiqvfd.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjlutnv.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzwabou.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vizjwsmj.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2snncalqv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2cryfeamp.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjxqsed.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrlhmev.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmhwyih.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhknjpo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2rikfjmhg.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmlssgb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2olseoeci.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgtihje.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsvmdpj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcmtxvi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrxpwgn.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxsttuw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvypste.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlhtwpo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfmifxk.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2luzxxiui.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnqxlwj.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjwoujv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtvepaz.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2prbmutkt.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2offmmypu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2irtzueiu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcikkqu.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kihvaejx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2xekitlef.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlumwfj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2txdxacql.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ciiiumwe.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2qraqlysd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqdjwfy.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ctybngdi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyqztkj.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrachnc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zeaqevsp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fsolojrj.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpxvkdf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cggwdgeo.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhhzmyd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2tlldkucj.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2mzotjpbg.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuuyoxt.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqulufj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwmbihz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsrqbig.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxwqqow.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2yetzffmt.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dgblvrji.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkermrdy.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmwuiam.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrnpxrf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwcpcak.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2powbfcja.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rrujrzpi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qttgmxrc.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2peatwcli.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmmfhgj.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnqogwa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtxjhhq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnxpsxq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2taojecou.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lodfnnhu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2heweitwt.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmaklpfm.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzwcmou.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvcuymy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpkzmzw.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsfigol.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oktspxyx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2fusmcied.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2suahzxvg.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rulmsjdc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2svenoeon.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pztuurnm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqzgick.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2rnoavjjr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxxeadx.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkiqkdg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvjzysr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qixxjsdr.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlfwclh.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzilsijm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmkptsk.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sjreavgr.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwghmsrw.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qotaaaqd.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2boqdtstv.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2izevhwsr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvlikbd.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ckplsbmr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dezpfnap.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2flbxtjbb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlujczq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2huvnezmb.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2axprvksd.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2cqaweteu.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyldgfw.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ongdtmva.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwrkbmh.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fijoqsrt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhzrsno.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2npxdowwo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2wizxklro.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kqaneakj.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aayzruhi.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2galjqfvm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcnbhwo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2evgvpvtt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2aybshigj.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2dpilbynj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2llgovdol.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbpmofo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2nifvbofc.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbluemz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqcdrnw.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhkeppp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgamoxkr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuwylxz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbkexmy.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ioulnipg.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrjnbmo.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jrueaonc.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhspdnp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdunyvh.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmurcda.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlvvluy.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pltmvqxc.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdybrpvn.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2suopruwy.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtozkox.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvqamam.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlrgqsm.html


<!-- 参考信息 -->