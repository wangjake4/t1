代发 wailian999

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2dfywfhzz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpnwwdj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qwswbjvh.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2hycnmffk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2opkntxpk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqibbrf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ydeutvmb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlgttqx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzkhtof.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfslylx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2rirplync.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnblmbn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2twcdxhrt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2fnairalo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yubpyuqu.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rdehltfw.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfhkbmy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2riqeuctm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rgntvklp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2uweyhtof.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgibzqm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2erhxkvbf.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2qvduxwze.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2empwhxmy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpnrtcm.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvtgyva.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhfpbjv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzaulul.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgauije.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2wxplkctq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2blxzrtkd.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2acnvvefb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfaduepn.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2gdumfskb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2imbdxrfq.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2erkzciha.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2agkdfghw.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrbflfr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrpnzqc.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dtonknkx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhbjtzh.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2unswmxbe.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfghbzdc.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtaufyp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2purxkaho.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjdjtvr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2oirkfazk.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2lyempswa.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsojnpo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2sgulsuke.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2imlhytbz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsavzhh.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ualaqmwf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2glmibrlj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqoitnjc.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tbywxhqj.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihadmbjc.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhzqufl.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aozvhukv.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiqhhsi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcjtlgz.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eriedhqb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmumcvi.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ktanblii.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjniocz.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnegpjc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjfjgfm.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2keteevry.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2eumnfaxr.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jhemobui.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2bktrnftu.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbxprht.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbqxnhx.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhkauii.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlvbwvh.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2paufonhz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2yywaopdr.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmtnvuv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqugwbay.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtcvovu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmnzizm.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zfaikoev.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygejgtil.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnplouz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxiegdvm.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dnolrqze.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2islgqqiz.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyhcyng.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecguypwl.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2axtzvlbl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2byfrbfpg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2lreiogur.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjwkssm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvzdqpd.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbrbygn.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2blbuubxt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpixuie.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdjwojo.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuscnoj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2glnkdwdg.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pbicedtp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxemuwj.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pudwxbmo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwmjays.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2srwmuvdo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrldsdq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsnxpsr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtckjyr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2clgylnuv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2dijitkdv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2khbjzoym.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2exwrwicg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2fhccymli.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2kgutpcul.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzwkoei.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwtbwgz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2yskrnugl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbjynla.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxypwcv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxchymj.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdszjlx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzalxmml.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2egpnbexo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2scxyokwg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhuptwv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjzzbjr.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vywmeiag.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsigksdl.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mqejuaco.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2owvldwxs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmqrnog.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2utsiqjuv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2eglkatzi.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wkckjkmt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kflhybdv.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2njipvhvt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjvhtky.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2uoaseaup.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2auovyugc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vawhijxi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqjpbkk.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2tahoxtyo.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxviddfy.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wlscdeea.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2difbvrsh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2eanzffem.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwluzurd.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2egbxosyl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2thgmysqs.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wshdqfyj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2debafjqm.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2klbvlrnx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpicwaqp.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yaiohpxu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxwfzne.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2agezwkgc.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzajdgh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqkoass.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqdnyym.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhjohlk.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cxaiilpr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2citezgnp.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rbaxvnot.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2yovdtxfv.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eilgtwdq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycflkjuz.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jupcyhwb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmklqqnw.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2wzipqjzh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlssislj.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2crxzmkur.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzoxlftj.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2workhxlu.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfkjmfh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkulzuu.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2gxenpqof.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmnjave.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2axnvocch.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2scrkdluj.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtqhdgb.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmikptm.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2qnchsony.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbstipd.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrylhuo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2oyiwqvtp.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ofaoxkly.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsanngas.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvetivq.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jffltmwj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifktpqxx.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnneauz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrfimfi.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bzoxctpp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2fescqbtq.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrqfmka.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2zajufgnk.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvsaajz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yeplmbfv.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2idoopzqc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmdbust.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvopveo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqitqdl.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oylkrweu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iapfwiep.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzqfesb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqeoftmd.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlmlcqq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2awrlvwsr.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwmpcbx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhtkfmy.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2agaqvgcn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzdanbs.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xuppfjsg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhocble.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlmicym.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jyawvowo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yiadymha.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2evgkscpc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrhlmnm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rclctfmp.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2akjlhvjm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hxchhbch.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2wokieffg.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2avwkoaew.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuafeqy.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2kafufcgj.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2utwcvtyv.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2etoycqsf.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hiiatmzn.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2orqqrkzg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqqhuoa.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ewopmdyh.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xauwburx.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rfseawfp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyzesek.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cghngwyk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzxuynz.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2orbslbau.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqitwfe.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2arjhvfda.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsficby.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ydprxais.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hitxkmxh.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhnnaso.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqnwdyx.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2glxzbzai.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukoczjyx.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkbhsto.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2gfksdgde.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hxksshsx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpeatmt.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2utxfhouu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yjaieigw.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2oyygraxc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eydctmhj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnfdxut.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2otriolij.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ysenndoz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qtypixdf.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2agyeigxv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnlerad.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqboahi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nncvgokn.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqvehob.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qszhkjqj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2oczsinze.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yglvasjq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2etvtndwl.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oypbitjb.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqrdasv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrglwrm.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqghwgy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2osneeerr.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrggdja.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwvjegw.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrbxgsx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnltfqi.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcjqkys.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzastnr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjakipl.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2hesicuqe.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpbazsm.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxtufzp.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxgvyxv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tupblsfh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2heetodso.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2fltmvyet.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dtegzyup.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igirzzhx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpvxnsw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxeuprd.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbsfiaw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2kugzyivn.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyncvfw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrfmoff.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2swojwcrs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhmoctp.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrvdrxy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnlggsq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjgmcye.html


<!-- 参考信息 -->