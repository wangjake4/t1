代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjbwltz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpvscvy.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2unxwzkyw.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2adhhtogz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkvlmel.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2cikgfbkq.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2eunntwsd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2hycrimgg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jctnwivd.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuomhbx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2clbzbank.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbaahue.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ambsmqzv.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpertcv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzjcvtb.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmqbvpc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrbzmkg.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2jfercpbd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrwbuve.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnroupo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2npvpehsc.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhnkkld.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgskqoai.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmfxdsi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nirzhwxv.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2esucxtuh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvtgbgz.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdgrgpo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqvytjx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ridhjmtt.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqevwyt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2enlkwixu.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpuaccf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2fntximsy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwihvts.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2onmjvnym.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2odvzvext.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bykpzdjy.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuewyyq.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlsdxuu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hepyrjxj.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lynphfmu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwljxzu.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfqpeom.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2labvpepa.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kitggfoc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nampqtmn.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yrheqzeg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbvaxey.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2itmrkbsa.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2emmnmsmd.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnnvyul.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2jginiosk.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwnagiu.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2honrzdqq.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bohpacgl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbnxwyc.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdovdxc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wysxkitr.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmiydky.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2csbbamge.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvnmuxi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oatjcctu.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxglgst.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2taqmrxgm.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwcmjnf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnkovfr.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rumksvpu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yijnekut.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkzvqms.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hktwqria.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyozqsp.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2oepbztxg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2abfojtiw.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpclbpo.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2waizijgd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwxdznm.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjbitna.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mhuzuafs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyqwhvm.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgssuzt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmignay.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ykebvhim.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wycbtmsn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2nypetktc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnbcezl.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2haojzdxs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdhaqix.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbpwlsu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqjdesk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2igxlziou.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2luhhqwsq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2vriwuyfn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyhgcxh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2testupxf.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rixhvnon.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrhqfjw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwevipma.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqnwmcx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcumkoj.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdjoaec.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdffzjwa.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dyiwrvbg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2adqrzxmw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2utctaojm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmcikfe.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfxadps.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfywppg.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuweiir.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2qekksdex.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qoubhytt.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hylbcdbo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbiyyit.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qbngiaav.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2emjsabhl.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wllozvvu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnuiqmv.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2nwapkgkn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ustleogs.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2casqudtx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2uvximmtf.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjbwzmu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkbkauh.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqqnlhe.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2luouwqng.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqkpffw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmyhjzv.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2niisstyc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2okczmunv.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgjyxhw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvgwbid.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzloxka.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnruiuw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwvcfzz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zjauzkdb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoofcgfg.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2crobaeip.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjpvobw.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2aswbrhel.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2eousctur.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2snycdnnf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ylslxtbw.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmxnqzv.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2zonrdmdt.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uaryhslp.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlevqxe.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jhttzcko.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2tawleoxr.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2bghfbplp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2hayjpbhb.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ikutqfrx.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmrlbvm.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pskkyvtm.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2pazzwdge.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvscald.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyebktv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktayfzns.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkuwcld.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxajcel.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2criwozrm.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwveoyb.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2gczukucg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpykonb.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ciawqjdi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2hcidtqtv.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2arepnupd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgttnxls.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2anvqtfur.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pohruzsg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2aekxifde.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2luiqyffr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qibwaqyc.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsrxkht.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2yywpcvog.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2olvnbyqp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjgdlcv.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2hueebjuu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jovwodqm.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ersamlyh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgaudvs.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyhsywq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqqqmzl.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oiuqwnwi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmuopmu.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfhxgjj.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbhjlgr.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgvkiba.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2iazfzvep.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vnaqiljh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhbfunt.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqobyoi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmikyqy.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbafgtga.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxmepqb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjoorbrv.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwjbkaj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtxqdxe.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjtcmoc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2enltxsxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bgonvenb.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2smnxtnqo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smyhkpuo.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2iywqjtah.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2nverdejn.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvdljjc.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjbydix.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bylcwbfr.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pryzsgte.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2dimqylli.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zewqasbs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhxoqfp.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmsuhut.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgdisyq.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgnkvmy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpubjixf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cctlhpmj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tttfvmvh.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yychhcfg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyjargi.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2veifogyc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdlenlt.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2adswenpp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tsovxeje.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqpbuai.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qookdezc.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vokevgtz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wysoqpyf.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2niimukcu.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtktgnt.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sphfefsd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxvqcvq.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvmnitl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkrbsqa.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfsthda.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tlulhrjo.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdoagdk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jaemexjo.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eojtrhab.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbekshw.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2cglzxjny.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwxxgml.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpjsavd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eopamlkf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yctpnvgb.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdsgaqb.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2byptmyrb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbcoutf.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmaqeip.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvhpgln.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vpccqfti.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2edpejupk.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbqjqch.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mazlpfmb.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iiduhdqd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2benqjign.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2dcegorco.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdofyeh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjclnxg.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ruupgkqd.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2bosolvgp.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuqbroy.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jofnxzss.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgkukts.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2abwwrugw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fxiesqww.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2donolnpl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2eamoqcpz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2djubhxcm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njpirhcj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rfknxlhg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qykkvtex.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrnlfnb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gefxyven.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2woyulpda.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwcbzdb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wirfnwwr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgkklos.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjnkyhb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcbxyws.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxcfswo.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfawlsfe.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2kwltqefi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdcpkgd.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yflgkfba.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtcjzpb.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2icztfqnf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pftzfywa.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hnptpjhp.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvwpqqv.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjfaqbj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnnekoo.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pznacplu.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pihjkmmn.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqvmqmj.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nybtklag.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcowbdm.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ampahbdc.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdtuqes.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzgntdl.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjzxrkh.html


<!-- 参考信息 -->