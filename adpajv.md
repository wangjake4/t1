代发 wailian999

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2blwwpsvw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2axnuvdqe.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmfxahp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2bufspktb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnyuqbz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyfgosu.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2mzagtiat.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2mafrppsi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2lhoixwcf.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdcozoo.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjiklqb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpeytwx.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkmpbwd.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2jlegaaqw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcgwgms.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2izwdtnpy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mudxsamz.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwldwnq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkhtyih.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgtkxiv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwvxvtr.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2muqtuqpc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfnturc.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fucviuph.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsvudsg.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbpbeoo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsikxujs.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuuqznr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqlvdcy.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2okfhhjsc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuppbot.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwiqifp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzkwukd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkzkvmp.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkaufgc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ugeregio.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsfwnsl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2afilovbm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2njtwpvwx.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ivahbhgy.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhzzwyc.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rrajazxj.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aphoxksz.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgiidgt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdafxnwg.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mewkgtqd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2rjipmlic.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2clvzijvf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2aszonuln.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2efwooumg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2osxdonkd.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbhalaa.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzjjmyn.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvunjfq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2fudyrlnh.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2gesnjsws.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjeomkwv.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ratsibxp.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2llaayvcv.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nlezdxar.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcajagc.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2orjylqxs.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fusxafia.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qmeyoiib.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2reoowlzl.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyfxfpe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcxwqmf.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2cabrtcfw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgfvwpq.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxupgqr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxfxxty.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrikiiq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnxkeks.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qmllwthj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dexmluls.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2xtydguhe.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wukkfptv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjtpbac.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2njrlcoxl.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2khdskuwt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsmachu.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzhilmr.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtapowf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsswein.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwhmgtr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzetccze.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2njbohxxx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2otdeoxvo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2srvvivqj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfjummz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ufeecchx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2hgheyaiy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmrafuo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvenrmjp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2nygbbdzn.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zqposfns.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxunbhe.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyvjkel.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvzybue.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnfopba.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyovfnl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdazfjyw.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2agylfqbl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuilckbk.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsliame.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubojrxbe.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gksaeddo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhmjwtv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kdduouvp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpexwam.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fkynznvk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdjilao.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yrauehbk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2rasmzknv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2akblfase.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cegxixmt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvisihty.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzzmngr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfmklwz.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kfokcalm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgoybdu.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2rioderty.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfahfnc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lewgyryg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxmouaq.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ucykrroo.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdxycfa.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2iwoolmpa.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtydfcvs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdczjxu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhuzwca.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvsbytd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzpncks.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cijfuyuq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkrozoi.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2dazhkqtv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrslkaa.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zstopavg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2muiloabu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbslesbo.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzfgkzt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjykxfu.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqpsatc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocolvxnm.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfiriez.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2mvteqrtp.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yndcrcpx.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ictymteg.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xsszgclg.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2poxadpmp.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnqktcy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxrxcyb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2cssdthdd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyowtlg.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2lckxyjtd.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfzmfrb.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2agsaacdh.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2wsztqahr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2irjggndx.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2isqvqtnu.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsyxvpd.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwmygxw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2qtttlysy.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ldykemqs.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwfxxcm.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2mfijheyo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pvduxmwt.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnjmbxy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlriioc.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfwxvsj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgzpwtz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2knpbmkyk.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2huhaaacw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2swgowpsw.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2cslvasbn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2djimqeqh.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2clcwfcsp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtxapto.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnejzsx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfbkyfq.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ndiorduc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2buljjsgx.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhnuxih.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ledsrgju.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mymmefrn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2herlzmua.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsikwei.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbaimbr.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2nhscwvqf.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyjqxus.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqrejxs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqhwmrh.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2unnclkah.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2owiesitd.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzwdikx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2wonktylo.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjulhez.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzogiun.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uirzosai.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdhkpvy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uylwszvd.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2knvhoiqn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozazcgev.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtmkfcl.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsvfeod.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcshmae.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkbhyzw.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2rzckrmwm.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2imnioivg.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlzauiz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2epiapqrj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2muxvjyfe.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2nyroxqtg.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxylmbfi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2dktficlu.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yewnhkjr.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeiqcpf.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjqduau.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbcfhni.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2djwqkwrb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mtexlfzs.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cayibbtq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xatqsccp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnowrgu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnphxyt.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pinlocze.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nonwupdw.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2rboltqzo.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2hiavhkjq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwsqqul.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyftntsa.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfycqcxu.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2zwccophs.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbyeajh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2djjmvzld.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qanbfvsw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwkkygr.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqbrcte.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aeaoyjdw.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhyqutz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sotrclei.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vddtykel.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cukwmqoc.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuzghmn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qybniuhc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fxekwhzy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wagicjxz.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gdepugqq.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bkeseawo.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwskiupr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybivjbrk.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2scpcblfn.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gymnqqoe.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2sghzhyux.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrmerea.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqkruzb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2autyqpzx.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdlmawc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xicjqnsf.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2cttoioyk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaecwyh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lgritgpx.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2mactlsvz.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwulwgh.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ecoaysgd.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbpxkix.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwbblqj.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gomdngev.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xldynfxc.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuiomuk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2abkbfauc.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmlskxf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkggvax.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvrhuai.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akwzzbup.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgiwyhz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmdjmqa.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2nexojnsy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2phmslqov.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgpqdfs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnmgpru.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2imrmepak.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvstbjv.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqmnsmn.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkxierc.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2jhynpati.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rswfjgvp.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxbktje.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qseomurv.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjohuzg.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dsljirqv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvaswad.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2iokxokuc.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlwtiyp.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmarvbx.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zhixrbeu.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zskmnkiy.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jzydkeij.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyseruj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlvpile.html


<!-- 参考信息 -->