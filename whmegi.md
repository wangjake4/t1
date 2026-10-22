代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyarrgn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2samatiov.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbolgdwf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2scdzeheg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdkebyp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekeqthzs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xgciulil.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2vuiimtcm.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvuixtx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2pmazmevc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtbuera.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2pofhgfnu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdqdkxd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvakggy.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyelgcy.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2poqeyqae.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbfdcdy.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zvejjtgu.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2rpftlzzk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2jltadzyh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjfgfbk.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnynxcu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2usfbmrom.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2toredzeg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkavxyx.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjtifif.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjebotrc.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2gavmucay.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvuigdwj.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2zimbozhg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2reenmxkf.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2orvdjrer.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrvefqz.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhwbthw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbkqvib.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzwzmni.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2idsookmy.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2jvaoprzr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bsigtdeo.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnplqlj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzoxiqt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2hujwftac.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwwvqgm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2volwcesk.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2riryzagj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2yeimcttm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qalelznn.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrvmuyt.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxkgmdj.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlazqdw.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqcoidb.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sevcotwg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fywrzkbq.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iieofhtg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkrenkf.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrtjsdi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsunipy.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcrqryp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgaxrwxx.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrzzviv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhqhutg.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fopyoreb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2gunlmnfo.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2gtiypskl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2csbyntem.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwtlxau.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfkjsct.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwqnnzy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2mlttlarj.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjdvwsx.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziivgemt.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dynwenia.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ultpojez.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlixayv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrhqtgt.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qemgyryb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zonipaqq.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2euatanif.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpzkral.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2croimpud.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aladjddb.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2whcvcyfg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2izncxtlf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrnnkkk.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uubkwjra.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiewzxdi.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2vgliqikd.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqrhfpo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2dayxtxhs.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2enzvancl.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yiouufhs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxrphsj.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbqpndw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmygrhyx.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rdauhybf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzziptz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdgcive.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvuuamk.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuyujdx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmsodah.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2msrdxfqy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnhrkzx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2oewtokir.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wbulxcwt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2frvklnni.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcefpah.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vatakwcg.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtxicpn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2wcltoukx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtleaig.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzsckxj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2glvwgmqm.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2latlzkrj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2cijcgobc.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ztihskzc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyoxmfna.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iawklfet.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrqefpn.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xctwpuws.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2bueyuqic.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjpbbbc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2aakobakw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfoeydhv.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2folnuaoe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jporfzpy.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbhbwtr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlomlxw.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrvabnp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vucqkiht.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkhiqop.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kegdpsqw.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxzeoqk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwhiwxh.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2hnotpbzb.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfhbisy.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwtsndd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqniehvc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2yygysyhn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmvtfjo.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyweogl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmbtxat.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhdlxlu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyavthfl.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2duqcxtsd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2acgfhxeb.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqcqdxz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2wyskwexz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyfebot.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyjfdln.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbptpmtj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2fgabbsof.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2anjamhia.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjpfeze.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnpbylg.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ecoxwlmr.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddiikuog.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cynatggn.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvinfibh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzvstsl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2seqvamcc.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2iyghzovu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2llzzwbhx.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqwsirn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmlqobv.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bveukjkg.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jwamxynm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xcaipqkg.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2oikxrkhp.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdclcqnp.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzyjahf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ltckliig.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nnibjmqj.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfbmvpn.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxlhqov.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bxunmslh.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gklpqydc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnpoumn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fjasavfk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcvbakc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2dccsksva.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2veoopewk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrhyyms.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2pizvusqn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2axybeanp.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvqbgpm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwraohz.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ytblrlko.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsfurhy.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwezzau.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgenexss.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrneakt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2swctuxli.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qiacssxv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmkautr.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vskxjlpq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kywirwbb.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2jgirgpmp.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqfdwws.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuamxgy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmykuwc.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xebvpfdm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ftggeoct.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpqxcpd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsehswl.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbawlmuv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xpztwjsa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xypylhhf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mhppshbu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jabtcijf.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpjmfip.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rguxlrzx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxyjkbx.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xeukioro.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyyjgwj.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tepgphdy.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjtswuy.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhulaqj.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vidtosof.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2uchrswfo.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfcvxet.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ceddonno.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpdcsys.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2qewsbquj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2elujhzwn.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrmeuom.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbegwha.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjytskea.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xextprwz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ascofvej.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zghmeysu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkehmsd.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbroutk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dolefbkj.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfvwlby.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqjemcj.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqhorhs.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwcryij.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hntuqmiz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bslhhpzo.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sugcffyh.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxutmhd.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xaidxbbp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eomgtaej.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2knufetbw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mmatcsiu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wwydbaca.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtpsjmv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsiyagq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxsxfrx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2egseyhxj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpmdzuy.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2poqolsrb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygstnbcn.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhsjblq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpmxtht.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnpbwnl.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqppcvuv.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjciyzx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2molurjzv.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwtrnlp.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdszwusn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bsaqauht.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfelspr.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2flegxduj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2owiyetzv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmjurtv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xckqcpfy.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2guyresit.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvbzfgh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nscsagzw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjvvmty.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2jamjlndl.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zkeamlfz.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2kckmwtlu.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2huuqcthi.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2amufursl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtelpny.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpfvndl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwiiklr.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2akxoyjuv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2euqinnnd.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmvkkjh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrazfhh.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvblyor.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2jbteikdr.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2gyuhtdpe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqgmsnl.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwhavqz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsqnwgm.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pzumazli.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtnzyuf.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdoatxb.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxganfr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfamheq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdsmgff.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2whyfohay.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhnqohi.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lwukhvsb.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yihfiobj.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhzneuk.html


<!-- 参考信息 -->