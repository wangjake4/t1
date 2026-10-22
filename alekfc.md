代发 wailian999

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2omgtgufy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2zikucboy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdgbmkn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2eioyakid.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2cunupbft.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2etsmpwbk.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2oiscnrdd.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpywzpu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2enblejrf.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2avrecywx.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2idsoxkse.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvyrdkvo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjkedyk.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2jziqaung.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2znubdpos.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rinjysfc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgmuwwh.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2hogmcpbz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwuffyf.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2dngzzjsg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyninyhx.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjribly.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bszmzzzu.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpvhpom.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2krjlvgrg.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xijqvkjg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dedtjhmh.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxiavhr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gemzjmkt.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2objapngg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyjluch.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpzofzd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuavchy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlnzprx.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsqqzho.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2csbcjapi.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2gokjkcya.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpmvnpc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbibvfkh.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdwljae.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vymuwezz.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmvyjio.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxngxqug.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjzazoi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqnmklj.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fmriblli.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuniuxu.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhcqrgz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrplrbcv.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjwdzwn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfnrksb.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2frnwepud.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlijjgzi.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xyheerut.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2epjxvtbz.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2pskfixrh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksaarwsc.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzahxsi.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fujxqunv.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxplfir.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjyakdc.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hisbtsew.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdzodky.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmqhcpl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsdircg.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlrqygy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2levupvqw.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2oevnicgn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgwhqkj.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlemodn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvevudw.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdvgmcr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2isgbxpit.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gudcbyiu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2prtineji.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2txohxnxi.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqlfgts.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2rusvmtwc.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2txgdducw.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhcccqt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2wiijhavy.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2adtyatde.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmvcrxn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxxhatn.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxtjfmg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2djnqxfif.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hbycvweo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcflynj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2dabbzqpc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzslkrzj.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwwdyvi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2enhkukkr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxsanwj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpsdxjb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2cssnensy.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdwajan.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdpgyxu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqhqkix.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2klkvjdcy.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bouarrwl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2uienilqo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvorqup.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oofrnzam.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2eedxpuga.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfucvjo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwuhfxy.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xewgijgb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfikdxy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cjohuads.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqbizae.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oewzvjns.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfohvrcc.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtaspzd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2sltxlfvf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2strflcig.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2iiclunll.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vftnqbtp.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rylmemvw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2sivvzrni.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2apxsqnoc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxiqpwc.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2cvehfihd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxamcst.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2utiaroff.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nsuthlns.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2avrilgnr.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfbtlqr.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2sclajmcw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnnrmmg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdtssbg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzfxcqg.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyfmtev.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2upqcxqnt.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvgfjmp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ramllcyh.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2unbfnydq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlezrito.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hszratho.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxwiipe.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbvfzzq.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2blvgrvdq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcluiin.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2tunkzedc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlecymbg.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2veekzbvi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2nachxgem.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nbirmrnk.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2okratjwh.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2efzwkeik.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbiplac.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uskmutfb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2taoakmrd.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ofaqnjyw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2gofpvbdk.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyiyuuf.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwuurts.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcuanfc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbrlpzz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2istvgexm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrzsnfn.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqijigwk.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmypamh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2wuimiidz.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ruoygzeg.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbtezas.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2scohejet.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uvyumjil.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwbogoc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtcljfn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bbaaynoa.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2usxdbcxq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlgehal.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mlewaisu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2exrrubsj.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtxjizd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsxmdex.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ropdswxi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cimqqnyq.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjklsxn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxagasp.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2yunepovh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgeltaq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxpkjvy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqqzjzk.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eejltrce.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdajyxpb.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsqslvc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwcmqwn.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2lruyunlk.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsiujtqt.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmpletx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhimndch.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqmecoj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2sklenfvf.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pedwrfhy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpzqhnd.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2irtjqxep.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2efbgjsmu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gogvohpt.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnlakzg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xzoutjgd.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2aciophcc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qelufdtl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzvkjmp.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaelbjf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2burgotxd.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2mmegfbmk.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2zyozptjp.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2sofqadau.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2psmtfewo.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcujfiqc.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ujycpbie.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2njorwgct.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhoqeqn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpuhstx.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvfhcuv.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eoixhcfn.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfasabc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdtogfi.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ndunjhaf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqarlho.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqwdxos.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zslibvty.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cphzuflp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjpolti.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxcfguq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bistgycw.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgqhyxx.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2vylveewz.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nivjaecl.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzwmpif.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjetrwlg.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbwngtu.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2avvxjmrj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtnhgmc.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxhrwkt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ojiugmkf.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhajwpd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwfsmpv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2istxoonx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qsghfdtv.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtyggti.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwczdfc.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2hybwgrpu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfodlvfq.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2omhkjubm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsikwgm.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnojuhe.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsqllkr.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2trmvgzrd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkztjto.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cynjntpb.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2netzaiac.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwkldic.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkofhgzt.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2knsmlvqb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hiequhkv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vnubbzbs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hplzmusi.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2prtwnamn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gihipzjb.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2drnskfgg.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2aypouofd.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwdxycb.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwczqtdr.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2wozaxsow.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2qfonisty.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzrllep.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyxjnul.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpzabzl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlvtgcd.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2afecufoo.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwcabpk.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2foprmjuc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iftgetvh.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cigpjhdb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkbhrqn.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qessooqx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzsoyuo.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2yughkpdq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcadsuk.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpmalta.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2tffdsqku.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2punwnksg.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygemrugs.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2srheombt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqljrvg.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rpryssjo.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlozjmp.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2okxstaey.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2iflxzwcb.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2afzzteiu.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvqksds.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2oknxvlqe.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzamykk.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2okahrtpa.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cjiyemld.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mearkerv.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kaureppk.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtdjlzm.html


<!-- 参考信息 -->