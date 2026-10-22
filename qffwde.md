代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2hblhfyee.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ninadjnm.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ognmgnxl.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrhkeyc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2puhiyxsm.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ehggrocb.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ludbheqw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyfszrg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrrtoeq.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2yhroxqvu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2memymkpa.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpmavdb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvcdfar.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2xatlptnm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnuudum.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2uevhkfas.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2izcavmjq.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhkpjks.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehavliho.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2abforexc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xobekene.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2agtzyqcn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2medjkftt.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fjexbpkl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfrneoh.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2prwyvvvy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cuduoske.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2eavggqlm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2cigcalcs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ljedekyu.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzvhbfq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnonvdn.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2rewajkaq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2iczcnvni.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioszfcvi.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsqiczk.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2idlqwmuc.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfqtbgk.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtuueksx.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2esphwrrw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbupvbv.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oweuneds.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyiasrz.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsiemby.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwkmqyl.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2smtudaxl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmoeqyi.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2huaacshl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvybwwp.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pccdvdlm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2jusiuwph.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqkfkcs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsswciw.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhtpdyx.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmfockm.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kevvoxyb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbztvaw.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxijcyyd.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxudqaoi.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfkjnsx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyuqirc.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2plhwlosu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2llszhugl.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwxyvcz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvxvqqd.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlscscn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkchrll.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2alvsnqgv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjrzvhz.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqmkdjz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2azxhjvqy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlfswmh.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwwroxi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtlghke.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdgbrjk.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqlayqh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ypguknjl.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmlncvo.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlblqdk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyyryjh.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tsllhyfn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgqlzxv.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2faglzjdq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2txrsiuso.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfssqzeb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrstkqv.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2afawlysi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2gnumhqwz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2agutfvfc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2yprpzqgy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayycijrr.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbqjkdt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxyhdjw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyahoei.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhwzpdn.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kocnhrak.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fenuyaic.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrnnjag.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2enlzbtkx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vorqrwws.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpddndh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2xssnysoh.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2npdfmdkq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwlgwdj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2glppiclu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvekbcy.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwnmsbx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2myuqylwp.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfpthzy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbtdylo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2twzdorak.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kdogsnml.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zakasnlu.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2svdcuyfj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjtolpj.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wparibus.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkabypff.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2rhecizab.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2axblqwmp.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtvjcts.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2pevdrbfx.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2qcboiutk.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbqpnom.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2khockegn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdugktn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwjdeah.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrjrxuy.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmejfyo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tidfqnxu.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcuypxo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuxrfvl.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2tndbscln.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vztdxtax.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gluqydrr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2kmafszxx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmcmcpf.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwmbngf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2peukedrw.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqbpxcc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wspsnnly.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxkfkkw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdvybmn.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lruoxbkh.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxkpzgb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqvcpwv.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrhsauw.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcrmfni.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqiqsbjn.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ezokgpeu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgpldqu.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ubiyskbi.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2chjqayix.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2subtuxxl.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2zhimvsim.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcixcym.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxeeewg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpgiqjq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwoetws.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2vtoyujun.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dltekpsh.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2frcrxwpa.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfcuetd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcdqgti.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bluooahr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2utdsgqdj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwknmse.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpnkwbl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqeyuco.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fjemstpl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwfekrv.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2uptdwsnb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmrkqtl.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2adbkzayo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2scwzknmo.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2amczixya.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2itneixsc.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2lorkzwmq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywybbvmr.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dlexlbfi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtuscdpq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwacqri.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwtddon.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2noqljhwm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhrqgsh.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpuekew.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcfkqnt.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ysoftecd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwyscat.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2uslkljyk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2xkikgevx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xchenqnm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbslxouv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xurqjiya.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxpkryb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhqimvn.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2poidkxxk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbahuzs.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2tdaygknb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtejcjqc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nwojlqdb.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmmrkcm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cmeorrrf.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpdbcnx.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2aayittam.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmufpgu.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzrsgfo.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nknwctif.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvfbnyd.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2qicjobam.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltaixphp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwynxjje.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zegpwpph.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkxdjjo.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcjylib.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfiencle.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ompsyryp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2edqxzjow.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdonjwz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwiwngp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zcsqiaxm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhsfxll.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zahtmhxi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdprkcg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2myyrdoop.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2cpiayywk.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2amgkvwtu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdegiuu.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2eudzzsrl.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdjajxr.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dawkyfvn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkbslkh.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ydomuoti.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpwgkod.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdxdmia.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2akitduys.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2axpgajyi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2btybehfx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzfhsod.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yypyibnl.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2thkmalnp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkycbidr.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2aoloyyqh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vijbmohu.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gblkafin.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxihljlz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpvlgip.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnepjft.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhjvjin.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zajelqaj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qpeewxcw.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hszdhxrq.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqhpncb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cowbpyqi.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfwaaqj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjjsqlv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ojaxlkcg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2djnwjxfw.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lepxtipr.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhiqaaj.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2whebtphf.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlmpaiy.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmvqtcd.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ojehesjg.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqbrugg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjimkjl.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvypodt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2yigwhewa.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xldvxwyq.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udnagbas.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxpejnm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwplvqoc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkhjxal.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxcfiiu.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyusdqt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tvluiopd.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrqxxva.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyplwkh.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zyocyrys.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2czhghhbs.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxwdehy.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnouotdp.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2vauuimcf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyaobak.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jctqzqmd.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgcmcjo.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rafmzfvb.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbabqoe.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcftldb.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwuejgu.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2zysvdcat.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2imgtjdvy.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2deuuvppw.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpaexax.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqsutjs.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2udnhwhyv.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cotaxxkw.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmfuhoh.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyjjfgx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgnudvu.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvuymuc.html


<!-- 参考信息 -->