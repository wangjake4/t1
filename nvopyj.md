代发 wailian999

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2aggylayc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2dbenggyd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kniixnmv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2bndifuuc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2mbuvcmws.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkayhvhu.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzjoyhy.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2iolxtxpg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2flgudocl.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2javduplj.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2miqvqohe.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2hruomkgu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvgbkty.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfxrrpx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjuhevd.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dwphwiyq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2goachixm.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2euptqjnc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mllfkier.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2qsouxmow.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmypnsw.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2fagoyuvv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyjfdxl.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rixsdoyv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtqljsf.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2asizxxuk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqclufyh.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2oxodouhj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nxikydpt.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2kufiaiqi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdiskqk.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ezavemay.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2iiecxuyj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkukyrl.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmmbcyd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gjeeudhp.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzhobua.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjtewxv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xegzwcxr.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2karvzgrg.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfhnupb.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlwwjxt.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mplnkbnk.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wpozzcxc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwzljmc.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zymlreqx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2macuuvjt.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpkcvwi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2kabrjyti.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2maaepieq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2apuugffg.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqebfyn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpmcubh.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmmwdmw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljauwqyf.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2eypeucgw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlohtrz.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxsbgqs.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvxuboq.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2swtkagdw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhlsahy.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpukojv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2egqdtypo.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xolejavc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rixkigwg.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xavokbus.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aacxbyvd.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2edxqpjid.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpanlpr.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vjaimgqy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsaukdgm.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fjalgrcz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qaiwmtub.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qeiaidiu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2atypgbld.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2bohnhyer.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrmjser.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2btarkxzz.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2kxynvngj.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2labrouih.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2cbincrpp.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vezgonxx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjbniey.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnkeill.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hrflcxga.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2txjnguxd.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yswcmydk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2alvqfoqx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnmytpb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzenudts.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2txsgkiib.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2xedjwocz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgflohj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjexwcp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2imziyxii.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2deklobgo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2baqesgfu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2zbehlyvm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nchuqwke.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pglqdmgw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2izdnzdpl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckencjwq.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jsscazph.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgzqely.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbdiqzn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2petpqnxq.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtfvkao.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvlmnwd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ixoewktq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hokwnagu.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzfjskg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2rehqrelu.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nivlqdgu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmjfcvs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvjebui.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mguuudda.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2atdsnxmn.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzixzyf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xgobetjm.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2szyetwzj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmlrakx.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjjubnb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yacbzncs.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2znjlgjpg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdbrdku.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2umfwsgep.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2vundubzo.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ionqecbj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzryans.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqofknkw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkphdmis.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxwhphy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvaxhruq.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcaxkgc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlggkdvj.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2xizurtjf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nblqteuf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjeunmb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvojqwq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2plqzpifi.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qouwpagk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vofiujwk.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlzllfz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnptcut.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvaxewr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrqlxrs.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mflidfbs.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2avordmsl.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqgbczv.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwtahpw.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwkmlud.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2npoptxmh.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsclcma.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcytfzti.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxkpspu.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2utirxekk.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcifaxe.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ymolgyvr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcyjowx.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmdgxme.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2trwsmxcj.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbdrtqg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2buyqtlez.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fhosqqle.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2stkieylz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhyiazm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ckyrnfdv.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rckmsnyl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2poefttud.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrscfpj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbpwrxr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhqlmvz.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnbrbeh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2itloyejk.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2qltirmfw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2iqeluwag.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2izdthkws.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxyiiax.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpemdci.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2czusbcoe.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2apdkkrqs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2foiwqzzt.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gkegfzyn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ervmxrzp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuadimd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqebcpwq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrwsocf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkeigdox.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsvcpzz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcamnltk.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgfrtml.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmuoyso.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcvutvb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2dmperizt.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtmeynq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuxkkcp.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdscoxdy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2cktmhhvu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2udkjuhkk.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhhbayw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmfydjf.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbcykjg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfhgkll.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcaucnn.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpuabqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2notpmfzo.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdxrhqu.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2djongkku.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2lyztgbnw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkimqjy.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqzgtmr.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpbvfks.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2bctndhjk.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyfmhyf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfdpwso.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dzupuajh.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qplifneh.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjmzmos.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpykzpq.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xbohsnrt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwiwkdb.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbiumvp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrzpcer.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgcqdua.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjwkexm.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zohmfmvg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhlmppg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxbjwdd.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnxnekt.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jytihvuv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tteoipeb.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwrybdp.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqqavbo.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyniqbg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyetynr.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2idnusnnx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfqchbs.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2yokderal.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjzxbyd.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2icymnvnv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2txvsjppd.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2desvewke.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ubondgfx.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzoaqgx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eawnyfxy.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnrmblz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwvqffz.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdrytuc.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2konwlpnt.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnfzcfw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2idicbiwp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ihoviyug.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmbptsi.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kowalvae.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhobsjp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbcdosm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkoftxz.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2leayhffb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlukppf.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2dinahldk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjomqnu.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2stksneyd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2oogvgayw.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2rueksuwc.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2orkabwsu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2dllzexhj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2eaijfjla.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fqouaszz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqwxfoj.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ooahlpgj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkokrlt.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrukhbe.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqikfhaa.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2merwmdfv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvbqufv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnvvqkv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2jjuqnlib.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsmqhbp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nswjsatx.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tmshjwrs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhttoaiz.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sckuzobu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqojwvo.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lyaqvxyl.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnusmyg.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhzzgkd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxckesw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsrpjut.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hrimlklr.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jsemuqpm.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2khqchihu.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdqtffb.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2efycwtdx.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2tujlwluf.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvlyxco.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgzyoxg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qazqhvls.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2psywpumj.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzlkqsi.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2syzqdhvw.html


<!-- 参考信息 -->