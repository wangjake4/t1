代发 wailian999

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrxhvzf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kenmmcdl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2guniycvx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgehudk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2qvovhmnp.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxopstn.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhzturt.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2evncivkr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kctmdyek.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqyshmt.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuqntml.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2eurgiptd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jifysmow.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmgrign.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbflqsrh.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqdxcsm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyosvvo.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2kaauvdio.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmiismpz.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmwrlcc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2psdeboug.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhyppge.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlqtxrz.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2oifbybgm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsicsat.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2eakoymfw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrzlwhk.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qorvlvxd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2beoqeplp.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwslhbq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sagijzxf.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2icwljskd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhdjwwl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2kraeyndj.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2njyzkykd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvikliv.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2hawjmibp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2pmljetwg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdzjxmt.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnyoprc.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmbaoud.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmqzmok.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyoxiwn.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2suoyhdad.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiiwscxi.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jiylcjod.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvjgojc.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbqxfuw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzodqsb.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vnltnjtt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjutigi.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uclraqcu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmrgxrf.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpdpauk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxqhcqb.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2pmeamreo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2udllzrqn.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kvglzmwi.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sixlluuk.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhofldp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2oderyrwb.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzwmtec.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjuyolos.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2axjfqxix.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2khyypqxk.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hywytkiu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkppaynj.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bjchbtoi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmiyhwa.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jenekcbw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqueawlb.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbkkcjp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbktvydc.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbihtnv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkxfwjh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2hzscqgrd.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zboisahc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtytlsk.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxmbnbb.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdpylei.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ccidigls.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvafqpm.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rhiqobar.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfayisxs.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ezraxzve.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eloghuah.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjfersi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixajkwsl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzpxjul.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bukrjpip.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gimwzqae.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqujroa.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtmumqf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxyvmkg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhbrody.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2skzjwfdu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsilkmm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2clnsbduc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2juwhjjkv.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2onglidfx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwoehiz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcaaiku.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqhjzqy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vexdtnwy.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvirjnu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2pszkgdnu.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2upjkmrve.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gixqgvcz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhpijqw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbzdefe.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhlowmk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2twvwpbpi.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2inwxrjlb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2phfnehlj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkyecsu.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2oytxdguv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kaaphmel.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2expqabea.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2algtlshu.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2giyccize.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzgkfrl.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2rvivpuad.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayroryey.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtbqtrb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqldhvu.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdsdceq.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2crisrdyc.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwwrxyp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfdmzhs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdglvvxf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kousseqx.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlipjxn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnvzpfz.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bktnppay.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsxynea.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2gurgorvp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2keagflqk.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xipyzxkv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2iquogkum.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnvpiig.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mlawwmrp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbuurcc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2edysehty.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vczwxrwm.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2npxejsgy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2zbstcdkj.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvfgxgr.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhwfgpd.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mvoqpluz.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmmiqqs.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgnmopg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2icrrhwvd.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvkmqul.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2vijsakix.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqgvllm.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2srggeoig.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkeywlc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2nxixxydn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ellmapbi.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2egnommvz.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlujehxb.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2wolkajev.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbkvfpt.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyizmht.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwhtewl.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnwlimq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zuopimfm.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnghydo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2pygnvtml.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhleoua.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzuuzdt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwfwkps.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2grmrjftd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmyjorx.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwkyaln.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbtwleh.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxstibx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2margpxkc.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nbamdaqk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmcmmbm.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdhmylo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzaujvp.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pisykvww.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkkgxbi.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2axwzzgoa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofaoeqwn.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yinzhwrm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2huyddwgp.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdimxbl.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxfymin.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpiviwj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2unlbomxu.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmzwqto.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbrwepv.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmtcxxj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbvzoga.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsnudwq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xnafdojf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbdkwhr.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2whjdagug.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qcztlqri.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfjnrca.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sebwjgeu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnggovm.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nzaovdnd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcumngi.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tcejrknu.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2lkohwqhv.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtnjndc.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jesykfes.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vomghkkq.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrsimrm.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrwtqnq.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhzdodq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2buexufra.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lndlpptp.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mujptcxz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhefbwd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zepgpkzz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gploogid.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lngdabrd.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzuqkwc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdbulha.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfmkyrn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vibggqeq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgimuik.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxyqgmo.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxrtpnx.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2zedrvabq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsbzpwk.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2czpiglpq.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aymrdmlu.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2lykivwal.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2edumpkba.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjpwajt.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vaovsyoc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2drstpewx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2iiaceogz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2drfiohui.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxunvuf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzigvcq.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bendxsyd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rfaidsld.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2niofltxj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yiaqktra.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqteggw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjlunfq.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvapslg.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uawyqdvj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgucbmxx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2umbqiqhe.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2smlterbw.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cztdwnbu.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqotqtr.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mubhhwsm.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2opugnsyn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfavasx.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2orpzisph.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrxhizh.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbcvikx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2orqgyzeh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aemxextd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibiqnisy.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwqzebr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2evkgvofg.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xynlbysr.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2fskkzhig.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxipxhr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvtbeuk.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2otbyalgq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjhgbao.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjqptyr.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztasodcn.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jdheekkd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzovywk.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tszzdrti.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjxauis.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2htirhmjs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxezxnm.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpmtzsr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2piuwcqqu.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zionkvkp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcgwlqs.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkuqovw.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwehnyq.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2nznrypoe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mtydjqnv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ltekpdzb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kbofphem.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gshagbqa.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gndcasep.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmtpqdx.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzznbxy.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlhnfri.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hypbmqep.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzsnqvw.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2znoepudo.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mknsnumy.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2giirvpmo.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mynjvjbz.html


<!-- 参考信息 -->