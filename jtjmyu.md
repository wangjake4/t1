代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2fufcdjjy.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdbtiww.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2iewemzat.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2muicwdxq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgkyrpj.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzvbfno.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2logcqfqy.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2umirlpya.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpkqsdw.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpxxdsq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhprqad.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhuplwq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqiaiyaf.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzhzbgd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdfpjle.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjmmcyu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhopgufd.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2evfcpmfc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkpnuno.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2rezwbgds.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2idznewec.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2jefyzuqq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdrcqnh.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnixuct.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2taytjqna.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjjaxib.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqbyoew.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrglvuf.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtztjby.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcvxztj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2atchduvq.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tufcgjnl.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmmjyof.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhhsxrp.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkekjdn.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mouxpvsg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lviozawh.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qawdyvgm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjsvdfc.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aemohxzc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2tijpqysc.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2krheybda.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mudgajbm.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2khdvcqtu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhrpmba.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuorhsk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2vblzoswd.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2iggrvmld.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjqqrqf.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jfphfcwk.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2damoqvch.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zixpefgo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ckahhfhi.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfgzoqu.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vueqszyf.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2agrlgbuy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uycjlqjj.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2eguyjgnn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iokovqfe.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwyzfzc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mskclpzp.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2araiokdw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxtyyfa.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuuhlyh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sokfmaeq.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2glzdjdrz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hadkydec.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2evukfcna.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgvjkfc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2myuzfhqc.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhuvpzc.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdaskcw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ierpqidf.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmafcdt.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uorpfzui.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2opkaugfl.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2chmfizbf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rajcuppu.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vuonjkfm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjokyrjz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqejtct.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsymvff.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqxnhzz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2deheupmh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyupbyr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcucwle.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2eybdprll.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfukjqv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2aivzuoml.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmrbedv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ommsiuwh.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcxgamo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxuukfi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvtgsak.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pyowdluq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuriihm.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aziesjlu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2sibjdrjm.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqfthom.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2azfjzqam.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oczvaemf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvfgcpc.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2snusltsy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhunsudz.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfivows.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2exsumftw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvevxzf.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cryhjffz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqumltc.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxcwcjs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2feiyyuoe.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hleoknsk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgaykqja.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2slmmxkei.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpapobap.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qilovmkf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwkqbtw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfwftra.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2zntojgtk.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vttdjcip.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpuivdt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2eeomffbt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqnpcjk.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pdflpbau.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2faxcobuh.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pruevwjk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgcmrye.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfaeflg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijugepyh.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqywctu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbzhccz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyzgerv.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ynofqdob.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxifosqi.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2slcmhyps.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qouqgjwc.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrfdyof.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2jehrvkjl.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2alzlfrik.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2myaxtcls.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfotaor.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwypkqf.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdtsebq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2akgixgxp.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2hfimguin.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdlxrih.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2drdyfixp.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqoicyb.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhhzrvf.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2oljiwsbf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2qoplisjx.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2teznaixp.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggeodhaw.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2siwjvemx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2xhiuymtm.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsewgdc.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqidjtde.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnreydd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qncgtisy.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iftpgwhn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2efbvkzac.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2debjeczc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2okmwpqio.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2bcclqipr.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsukuwr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2xskkwxxr.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2vuawkajl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2lguhlmaw.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvvswds.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvsucgs.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfblvld.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2oguhlknp.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2elfztztz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbukeke.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxonzps.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2djqcexia.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oakyzugd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2heddyhle.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nabqyiiu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjvpryf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvogthi.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrbbenr.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzkcsyq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2efodfbwt.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkniovq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsicszy.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbdscio.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtnwclg.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfuuxye.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2akbpepxf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kitzqhpe.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmmjngt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dfanfgsu.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2kvaazjqh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqrjplj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbgyksv.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uksybgsd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qdaieerr.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2dhorxgki.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgfpcaq.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2kvissxfa.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfpclfq.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vclskowe.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuidgjt.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsbwjaa.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rsplbfsz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvutlgfg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzwkuag.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2enquuuqz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuxfewu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dieltwqf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qubsxerg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cghoxvsi.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpsourz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdlnrkh.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgsrjep.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyaiugq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uombsmnw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxodeaq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2unollkyp.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2gepjbily.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xistsgsp.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogftehpk.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xauopfrs.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2weinboze.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlexzzf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqeekvh.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zhftvaxw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pevvtyag.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2msbydjbl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kamnlrcm.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsnzydb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzyliau.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bozjwrir.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hpspcokk.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2uyaspjle.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxdneoa.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rqafvbjx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhgxjwi.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yoejdvhj.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjttujy.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2necequjx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtddrjn.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2igaptdon.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdniybga.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcbaqve.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnaimgqt.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qtscakra.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxesxau.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbwqcuo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzexldcp.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2duokcdjg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2atatlijb.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxhmnqk.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqzvbsc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnvymjw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvkicwr.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2srwpxxpj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2jysejkqs.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyyyykw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrndtyt.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ppiwypsx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvprajip.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqhsepb.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxvacnj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yxeuiuoz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxqxrpj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrlfnur.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2bcikqkln.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwlgrkv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2errtjisp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lypxzbkx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgyxqjr.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrqehyj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuqtrsu.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlnekrr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkmscjl.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2eytaxjdf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2inrskswu.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xebhcyoq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjbxnyu.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qrevdzxo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcbtzdw.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkesnqr.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsylizm.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2oexljzjh.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eqerlmxx.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcnrwxw.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqpvyju.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxtyhaq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2knavlzex.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tmomrtjk.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsjdmzw.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2udqeadpr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2oinevluj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2foxkypju.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uufmokmr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbtxmxw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tphfsagc.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgyqdpz.html


<!-- 参考信息 -->