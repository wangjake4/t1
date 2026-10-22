代发 wailian999

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2enhvazaq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlatbeo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwfjwxv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdkgriy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2sslvmihw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2fckasfod.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2reoruibm.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2elwmzcvd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlgdnqp.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zvidgglx.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2jbztmrne.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtufibic.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojovslmu.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfodskq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhntpdh.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrlwfnr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2iompdlca.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2zecvzxbo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzoikvjl.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2crtwyopt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwmiwtl.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2omobxfua.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eivlyfby.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ogskrrkl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvryarh.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2egybbeqt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbswezf.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2quvwyiea.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhfeqkj.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2rahikqiw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hsymfzsp.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2vdargwyc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2pujrommv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyuhcoj.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvcoise.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2txajoygz.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2sgplfrpo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvfsjro.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlancgc.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2yehabhfa.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxyvuby.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnjdtzx.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmctqgj.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2osrdxwdy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvhskbe.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2veseykso.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjnwdke.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmatvih.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkwfzyy.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vogkeiwf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewczhwfq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wssabumy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhhlhcz.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrcyzwi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2isnvhnbh.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2eaotkdrk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2huqrunqy.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2iupbjkrf.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2unzvmtsz.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfcwxzn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2wcshzcvk.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjczjxc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjjrdvv.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrsnxsg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnkkhmd.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtiocwe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2munrwjcf.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbuzqou.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzterzzt.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcwvkpi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hukbfkvs.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbsqncn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibshckhb.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgsxcob.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjtgstk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2lstdyavq.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mszztwfi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcbvwcr.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2jobagkqj.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2jocpygmv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhgxfof.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmmpczq.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2chjlgtcn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcioikwn.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqcbejc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dybohxoj.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzfmjmq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlffres.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2mizcrhwl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbupzok.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2biieuazg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2swxktzen.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbeyissh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxjrxtd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuiudbke.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwnlcay.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxhezfh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2njaokgsn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyuqioaq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdjiihz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2waftgxpl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbcoipe.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzdnfdp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2pysmytaf.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2twhgiihq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhwhfxh.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbuvhwf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2unebcqrv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmxaqun.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzdlvuc.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oeneokua.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2difwdywl.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jxivgnhs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2skanepgt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwhliot.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlknait.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzhuzpi.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfdlkhi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2enwmgjhd.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wkiarbre.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxheryd.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2crhyupow.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrqyoqd.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfrbvnx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfpsjvv.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfhjknq.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2stjwdsjf.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2paipjepx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2irqfiwff.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkwcclw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgaeybqu.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vujcdjoc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gehxkpva.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dqohrfug.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymckvjbi.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2mccglvmr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2inqawgwu.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vfujjmzb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjjdwld.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2flrnvtuc.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcnwemp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuzbtun.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvhbegs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxewjlg.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dosvatvg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2lictqueo.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fuknnhuk.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzgnqwf.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hexgmkbl.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2vphgodqi.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpulndt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2tywunwii.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxlhlgh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2afzshzfb.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2xbclxtaz.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wntgqvjn.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrpjnwc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjovoxj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ozygzvjs.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rxaombhv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zaiojgjn.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2thkdenbt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfweral.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nnggvbft.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2usknlsue.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxzbpwa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2aihjlpub.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2uythiycz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2lndtevtp.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrlzibl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rntisaqb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2zijjwvcy.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbjxctf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbocqrsa.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2lljcuxrd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2lkulajoo.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxetwpm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2czoeesms.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnvgkxt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyoebwe.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2afzsjirg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdchonfg.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2elaznyiq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2psmcoxkh.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdjktif.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmvoibw.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmdpfyn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2skwbxmov.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2dogxmbqs.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmujljar.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvibfuc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2turcfwpk.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqypzyj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ayiiawgz.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cphdklzv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2uusbijhv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyzcjda.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2akitwody.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgnxiil.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jocwyefw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2riwazuwp.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2barnbuaj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2opoyrycp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2drhlrbrm.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uttimyuf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wvaepzyw.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ycasqsac.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvqolfm.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2sarqooze.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2yklnlxxz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2upaqddtk.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aabbtsve.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwqhhle.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cddveblx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2auuucmyo.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbienmq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtcvhuf.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxtoibv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fohhwtvl.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nypxythp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rhizrwya.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pdunwiaw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2handfosb.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbrkvyy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlewzlx.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlgaccs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjqhsxc.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xchkoalg.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2fydybvie.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpdyqbl.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2owbsgsvc.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgajzahd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdibhul.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2swfwkwll.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmhpiog.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkgpaoc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2srowjtyy.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vezqeyij.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fennydwo.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lrptlehs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hdorcsus.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2njlpqscg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aofspmvh.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxnyxvf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvinbqrb.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvpqtsp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lcoltnne.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjhbpdr.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2upncfsyq.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmqtxfr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdoaxvl.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvrkrvz.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgdhtyd.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2legmaytc.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhkascv.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkwbuop.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdfgumr.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvgokqi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlqzice.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnmfdee.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oaemjwot.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbepylp.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ucezhbex.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcsgkll.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2muwyczfi.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgxzkgt.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqyswwq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsmgdmw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmbbghy.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnlszlw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwgotcj.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbyoykt.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjtyhac.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mguodmpq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzraxtol.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjqqgqa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpvqglt.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2glxktgsn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcvnojc.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvllhrn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnudqdz.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyuabrm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2itbmxotw.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcncapy.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmhkjph.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2zkecrenp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2iyigyldy.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpesplx.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bxngmxnf.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pmeaxmmv.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnezoyb.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xirukrib.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrqmlnz.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2wzovwpnx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbdkwgz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2teesxhnv.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2aitygafv.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ppibpspc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2unmtqqta.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuthcqy.html


<!-- 参考信息 -->