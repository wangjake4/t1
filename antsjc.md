代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2rpiijbmy.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mezhpfvt.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2qupqvhec.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ababpmjb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjrsxws.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ahytkeqk.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnuflsr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpwtqmw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2uoscvryy.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzkoupv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyeufvqq.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqvauly.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcbjdfr.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvzldng.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdonqrm.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlkkpyp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpmsovq.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjpwmvy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkdaxpn.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xuucxdiz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrznwmek.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwnvzaa.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhxkjgl.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpmrlze.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lwleuszt.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2mginukxi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ypopjqsb.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2dsssaqav.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbmghvs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkuetjg.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuvcjsg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzisuzt.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgpzewt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2epkxqxek.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpihhvno.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2erxesarx.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxycvkc.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvevyta.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2orpvlqyz.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhenecm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdyirtfi.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuzddzl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtoabaf.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxnfzov.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwobnos.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rawsipyx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tthaiadh.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zldlumeq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcscwnej.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgypwmt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgonhvv.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2xayjumkl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsokueho.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qefgwzel.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zusciala.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfggjjs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzozhls.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fliexraz.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlilgyan.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qblrmasw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfqtwct.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2srumgvas.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpdcbud.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2uqntcqsq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrdqttu.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwfthdw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mczdpcbz.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfddzbi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpsinkj.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnptspj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dktdhijp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2urarnsrd.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kiglvoyb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbridezs.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ygujjgfm.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfbxxlg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2glhkphnk.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtucbayw.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2huvbeyrp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmiesyjd.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgelbmh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfixgeh.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pawsvjch.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2juvhsohd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvpbdbq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzonswfv.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdvzroo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2uyunlvkj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgmtlnq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2vovradej.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwfbjoi.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2awcoxhvy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcdlbwb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2cvslvvcc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhadpkan.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjxodam.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2obryfhrn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfoperw.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dstxfeen.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbymoxhb.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cymolwkv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wacwtzfy.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnkltns.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbicybi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2teckodgh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2onfjicqs.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dfymyxpl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsmqmer.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrlrbfb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxrqgsr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpefdil.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zazjahdi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rroiwfvn.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fskgbeqv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwoodzv.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcvwwec.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tutfdpna.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpvlded.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjozctb.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgobhwe.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2uruwnqzx.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlgoiwm.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyursfio.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzjwlwu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdpkqwz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2paejxvzo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vayceiua.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wnoninex.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xddpngcw.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rifrmevf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2acbjmoyb.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2aczfqyyz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2srpevdjc.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsiwqkf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdqkibg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzfjdmo.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgqzvei.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftegukzh.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2sixnmunm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiycqwqx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kflwpnel.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvwwjqa.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbghtak.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxcqxnh.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rarupicu.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrxbsiz.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnedtmr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgevtle.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2foosqrjy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2leodnplr.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2nakuuzhe.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnwyvhx.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlljnfm.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2blugvmwd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpxrxle.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vjggahil.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwndzfy.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcwtzot.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdmhbji.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwwcxjz.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmmuefx.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2xspqkryh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2azrbpgky.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tppeatkk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqifbdl.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2shniozvp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkfobjm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgskncx.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2aerezoqt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2zihshmcy.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnniapw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2kqotlkvv.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbjqpcr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2suxahwtp.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2autxtdgj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxtktdv.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ziapitwj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhnuvvs.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqiubou.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cncamilf.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmzstbc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlpdauf.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eckyjhqh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jguoxppw.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2bqniqeha.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmvsybn.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2azqppupn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnkfzho.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwmnbyu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2omhhowom.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jualxboa.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyeqebzf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsjlola.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2kegiqdvo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2svvthzsi.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pikspgxr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfdxvdq.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxepohm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipugjmms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fmaperpk.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsxscpi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pprxwhzy.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vldvxxkr.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdzntsn.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2brwaufni.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2cusozjyg.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjvqimy.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fhphzbil.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2bllykcvx.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rspikfka.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmxakra.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2siveugww.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwnkdsw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqlwaha.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxnwtlc.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgxxdsl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zstfgqzo.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjfrbpm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyyydvv.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjswkyn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsxgjfa.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2slkmaqqu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwpcmzo.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wgveoyjq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2eljgbkwq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsxujqr.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2agqvtmgy.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnnhsel.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyblgyd.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ivaqssgn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvrsddo.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwxfjue.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ktewcgwt.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmumfdk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfvzkxg.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqhvgkc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sijbhhik.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbxmguu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbbfqsk.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2scvzotxt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rchlasrk.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtqacvf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgbkpxi.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbjcevx.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fswcbxqp.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2brvptnef.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkzqfak.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuuonqz.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlhslle.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrbmsxa.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2opojttnh.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdfwmwd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vywusfhz.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqmvfze.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmadlop.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzleayg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2keuseaxe.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jyriqzuu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2mullekhu.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfvtvcy.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qyksvrcf.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ezweodcv.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2xacymfuy.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfbultp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwohlzm.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrwgdxx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpeslmi.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2icehflad.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkzgpnh.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmrijbv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgyvxrc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbfamen.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cqaxfxxa.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2agybejtg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqidjua.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fubmryji.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ioscogqa.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcclzpg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2kajcmxwo.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2exfvtbfm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcptlla.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlkodcz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ydalecss.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ctozxspi.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkjhnzf.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2flpjeecd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgdclvk.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2edbqsjks.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vuysvdkm.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwzrhun.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmercjm.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2scsmpbki.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2owvmqdqi.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hikkiifm.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nnielzig.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyjvzju.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2euypsmco.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2unutikxr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxhowmi.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2icdhukpk.html


<!-- 参考信息 -->