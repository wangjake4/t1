代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjlzxca.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2acgruhoj.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2dveplbji.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ambreiip.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfzlmnd.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ckiiwcxs.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrxxrwv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfrkhkb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2asjuisnn.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2emrgbwzw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmvnnrb.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qpilgizt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2edzogbzz.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2segexdgi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xegznkso.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsybqbh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvyvqej.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfipelb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnnznfg.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpbxzfw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqsmglw.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wiftdxoe.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcimnrag.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcbuojd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qujekney.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2fowdxtjk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsxyrzc.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2jtilcmph.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqqxxqt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzgurfa.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2afquyrkd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhapyqv.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfhbrfx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2mjimhdad.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qoksoxnv.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzxwcnx.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eykowhro.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjbijun.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyfnekx.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxulblo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xiutwmof.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fzaeitby.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2gspqajuk.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvmsrnm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxvacrx.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcvnlsk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgjcoxr.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyxafsw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmjrxow.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kftycxgu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnqkcnn.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxlhsiq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlstcmbk.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hfeiqrnh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2klemnlbk.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bubhygzc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyfdvda.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2smhhxqfv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgracely.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcyxivm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oskpbtkp.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2podugqjx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfkdohm.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hywmnnsi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqluclx.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tznqebph.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2drcidvch.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cgiebxih.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdazuiso.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrhcnci.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwwetqt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ucodoxtc.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2iatxipzy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2aodgzgyv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2qikfewlr.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2eheoxenq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpytqki.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wutrooid.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxwyuni.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxklnrtk.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxnaqnm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrwbmpe.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oilevoxs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2muipzeni.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2grnaojxh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkapfzip.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fftctdgj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2yhptdltd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhvbqne.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2cddwaxef.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuwnesj.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ssryypqf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvizkad.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxocvyu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sidwwany.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vcllpgzm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2wymbaqpk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kchlfdlo.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2abzywaqz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmkdvml.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ovklecwz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzovcjh.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdbnygf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ummubmdb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjxoiru.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2oadmykit.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dmctytyn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpsmsyk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyucmfs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlirnhf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2znuqzems.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqcafai.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfdzpiw.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fesjntvl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2morglidb.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cgaekvyt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kulmzrzg.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2njaoyuay.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlhqpdj.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cuceqgcv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2curotuvy.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmvcnpi.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggolpiow.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzkvpxq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hltkfugw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbezhtdr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhtgvyb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lncqleoo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2toyksgft.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkglaiw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqgabhc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmnrivs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycadxxbs.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hghnnhpd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2omekburi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnoxdjoz.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsgfdlo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxlgslg.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwebqzq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmasbnn.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lzozmrje.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvrtijm.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zkewntdj.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjbvtco.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qesjxzrk.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnjdado.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgxiair.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyxphyv.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2xeymqrdf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvcerqj.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2bviysflk.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pagqbzdm.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjxlafw.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtsechc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqicoas.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vtphxmxg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2npabqslu.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2jwheikyt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2hidiowpi.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iogfjhnz.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bubxaniw.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2iajjvqpf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgqbgff.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjaxknt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2cavmhrvh.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dduffkmh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nupcabrj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2qpewesyt.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qqeahlvr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypruedyl.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpnowgr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvakkxy.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2orjvqwtj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2olzmdnaf.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vzahcjaq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2latysdlx.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2odxryogy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rokjyqps.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lomgceaf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgeqgyv.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvoxzhv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqkypyy.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kudmbslc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxavhxb.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2pffblaph.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktoqdjzo.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjctged.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqicmpj.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyaajfs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjhvvyl.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwerhzn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvcivng.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2spsguqdm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2lskzgmyp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjffqotb.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yozhqrxr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hbommuzp.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2gssjnjjf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dueejyoi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2onuflvbz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfibpqm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzynyxk.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnevaan.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2yflwibif.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2wrenjyte.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxunleq.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwoaticd.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtntneh.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzbwhmk.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzrccuq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2amjgwetr.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hchvuuwm.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nczaylta.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zpeiusam.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtqmbgz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2etbnsovk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxpvyyd.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2upbupjir.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eldchmur.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjrofcm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tfoevubn.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2swzxkuqc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2slyuuvca.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vhipmrab.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwpxuib.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzisrnqp.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcyulee.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2srwayyfx.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlkmvtf.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2adxagffj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcoanlp.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rioucwhv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pxypsucf.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfkaseq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkjvkeh.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyasvsh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iltmydee.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2krhxyqvp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kkefqjht.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2jzozujax.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrdxanu.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ctezyryl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eiekvjfx.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2etkgicqm.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnixapx.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjaxjqpg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmzkycu.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mwybtwlm.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jehwuzvw.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lykuvcxy.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2syawhytu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpcbmyv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdljbdg.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oitobjvj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tiugtkmt.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwgkjec.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgkuyvw.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mughzqnh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxasgli.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2jrigfwpo.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2sqykihur.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyklwbs.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjotuil.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2beeunkjx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uhucbdhe.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlaheco.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbamqzl.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvzmlkc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twlfgmjf.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nailsaqy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdsxyff.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2aovtvrea.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtzqgrs.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxfzaxa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uvatvzog.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2oajyndlf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2fchesnsn.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ealwaihq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2odmpzerr.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hegbjerx.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjjlxbi.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwjkeeq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nqinmngb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2oadjkver.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mfamizul.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzqbzvo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pbspodwr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqfqzol.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2epiujdso.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2qupbilvn.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmmcgii.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gjokgxjl.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgyiign.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxgbfcd.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpymonq.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2uojmzksv.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmwhpos.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuatavh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2loeqpavb.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwffxpj.html


<!-- 参考信息 -->