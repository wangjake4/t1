代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkiptoq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbskuhs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rkslneik.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqolsrw.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2gcppitmi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nzypxwwy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zcixtgzj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsdflwf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2qofrhsyt.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ullfdfpr.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2jznbljvn.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2fgomqapb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2iicsbkla.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2gyisknng.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2djwvaeds.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqrtppj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxnzfes.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmfjrfg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbqyuap.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pgulhkbw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjwoylu.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2kixmhjya.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2grtwgmon.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnrkvhl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbkzhew.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvngygg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2alvetnad.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2glwmmuht.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeslbia.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hlaygfuj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxsmsfx.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgapgbb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2usmdxjmw.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2slmknuhq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pktqakdw.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpulqfo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2uuziorbn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2vpeolgwg.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2cjevqgae.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyjaixl.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlzbpsj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsbitya.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2hofqfmbo.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjojjfp.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xanlmkgh.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xarspeqw.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzpnjnp.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvmvqja.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpofqvc.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xhiydiad.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqxekpr.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2esqxtpxv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgvgzgo.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2snwiijwa.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzvtoro.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mldzrejt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2znfoihod.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnnvgkn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2unnymwss.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcuxnyb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2hruqqxde.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ppeilojq.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jymdcheu.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrzmoye.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnjhohx.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkpzxbk.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjkhgsu.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2szohmwjo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2khlffhai.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jkicdzoi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsdemwe.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hdoarebl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmuwhwl.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jgryznll.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2icbqtjxo.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2osaeoazx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnwfzze.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2osvifsej.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgucewb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqfygbd.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjainpf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfhmkmh.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2kefrliqt.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfmutvm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmosuqv.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyvvrej.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmpunzi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvdcrib.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ennkthdp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvwxfux.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lpksogpc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrubgncu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2accydant.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dozivggd.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bruiilyk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpgtvej.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2buewkots.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxowuhkt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfjrygh.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2flpaliqa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ooazlnab.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtylqhv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwribxcw.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbrjsln.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdebwjj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdtaqno.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tmswdaxg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbcvvjl.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eoovwaoe.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2pphozylq.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lbeepkuy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2awfedijn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iwulbxgh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzyacmv.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qkimnxog.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrdmuot.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fthexkuo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2gephpsfv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgamzog.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cjoilgfp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2puipuaxr.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrcccvj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ixksupni.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlikwse.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2csrtgxdp.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2skjmgwhi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2edicolvc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jxefnmit.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2caarhezn.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyjrmlw.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpwkbrz.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzimoka.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrjbyzc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vayobpzn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2koklegoy.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2obyfgemk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuppglu.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tciywxcr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbutmhc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmdjsdd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qimnzvla.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvmdler.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2tevhddrz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2imbymxir.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzzqcig.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tanoqmwe.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbsbzqs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjweiiug.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgpwyys.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2gmesskhr.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bktatfuc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjzuxxp.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xyousiau.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkkwnsi.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ipduimts.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkpjtfj.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqhsaag.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2mooolcvo.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmrusam.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqibgww.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyowcdvk.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jkedxksh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyjcdpj.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzxsjrl.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbewimeo.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqmoxge.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbblfak.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jomeotcq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2owbowrov.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2tzatfmfa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdqhstq.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbvrpci.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkwnfdg.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcxlblp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyjcigt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2qpeimcha.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mvelclnt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyubbnvu.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2zotqkemh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkaquyx.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyfrxjw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2mbitgwwf.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2panhqbdp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2sanozyak.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzbfais.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vugnlxsf.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqpsqor.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tithauwm.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mtebtpag.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzhkalw.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbfgygz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlszxvdp.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2pimpapcx.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxappxj.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2tekfmlnc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkglpxyh.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tzotqdvh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmebuuc.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqrtwge.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2pppurswi.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqppbch.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmdeucb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfamrdr.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tpinfmyy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tminklxh.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2gskldezm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrsbhde.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnzdzeo.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dgydohvp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yyglfddc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2lixcesgl.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuwytvd.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyjwcgb.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2boysllrr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tptmfxui.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yticvvls.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2noavcpay.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hyecglxg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2tzviysnb.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wuquzbtd.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fofchhbk.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dozmobsf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcapbabt.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcvkwoj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuathht.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2flifskvx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wklwptwb.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rfenpzto.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdnvbnx.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjortpa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrshbsn.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2kypkylum.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfmxsgf.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlaokzs.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpfvxlf.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrnhpez.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vxticyll.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2euibulcw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fippcayt.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjbiwng.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdtotsh.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwpkrqx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2poltcldr.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvvvyhx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2invweepz.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwebgeg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjclisd.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2edddalxq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bzukkhkp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xjshvdsk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2quagmmld.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjdgqqa.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkbdkfy.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2krmzocgo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvvbwlj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iezacqkl.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2atdleoxs.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmiqtgk.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmyvlkn.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xheyamnq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lugippbh.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgiiebb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyldorn.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdxfakx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcrliho.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrscvxk.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbipsvzg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzqdmrx.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxsubla.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxzhnbd.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtkddgn.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tbaewsrg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kymardal.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcsiqlm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbceslj.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rsakwdfu.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtgwjrc.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgrfjak.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsimhbv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjrsabn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdcexgl.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjkaewc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrhxops.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhjuyst.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2frbkhall.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hclrzmao.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2nntehgzs.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rmohhyao.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsnxesa.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxoiref.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2svskuzqw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2sufuhegm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qxthprjf.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sekqxtue.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gztgwthr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2whfrfpow.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xlysckvr.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxglgkf.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iuidwuqc.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2scsodfpt.html


<!-- 参考信息 -->