代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2puqiajjv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhdjxnw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftajecwr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2jftdshky.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmvqefe.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvsipap.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwvltwl.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqkzrwl.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhtfxar.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhtmfyw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2nabdxtsd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbinzqv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2hndgacoy.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsyksht.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2hlasnvkz.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2epkmkgyy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2thbyetwy.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkgumvr.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmgpsam.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2exzjwsqq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jocajlth.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2gbndivqs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2airnmczh.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcnqxfn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2iccalqoe.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgoornk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2aessvwdx.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdgisky.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2smujfgqb.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2gigywapx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2alpzjbxt.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjzlgxv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvmpmcm.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vedrncdn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2etrxtxgv.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2iypyhfhy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wapanwlz.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpzysbo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vxljpedl.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2prvbhfcr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vszuhpzn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2aarkttol.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2reamjqhl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnillge.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsnwztn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2qajoqxwr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtyvgud.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2yootzgoy.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2envgfoaj.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqaqxgc.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qurhhhyp.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qnspkbzk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2txarpjjs.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdhdrxr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpcnimx.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ndevkteo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2dahuhduf.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjngqqn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfydkfx.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2veierxdi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xipqirif.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzapqpq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfsdcbx.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcsjank.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyrkwie.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gktvikfg.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfedthb.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2iskknxee.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvrdhya.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvcegcq.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqqessr.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ugziyrqb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpangyo.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2txhsjsxw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqrsuhr.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2npycjmum.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsekojg.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuxfkpy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuavsgzb.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzponnn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjxkrco.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2auuouiqo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgkqmzo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2iprffzhe.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rymvbhpd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfhkjad.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwgduii.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkcuwpb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2jasrlumn.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2whwozssm.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzlmece.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvosyohv.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrvloyc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbnvuva.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jyoqoxty.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2imezcyqe.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtsixmy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxymxunk.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhfazmg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjywiwo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmnyplh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2udewatso.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2wswahsro.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2otbsymol.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2njsokxfj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2jorhekkp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzsvlhk.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqmaxpl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2okuoyjkt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwsoruw.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kllkuwsh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymozttmm.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aehgvtqg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvujrip.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eklvnfxj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2abtpgvix.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2leosfeqe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqtyjhi.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wldamquk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldioxvoa.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qeipzzht.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkyfnjlx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nysfxuvd.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwyqqyf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsiissfq.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdrrhrd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2grdrqujx.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdykvuo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xadeshxb.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfubgoz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqfmequ.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yaimfuza.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzjnocw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqrbqif.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmgmexo.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfofxth.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2njsgvapj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ostwgyoa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2htgukluo.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cbodkugs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2csgxyheh.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbxdmrc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfgsiob.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2rgaqryfo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwefmsha.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqxobnl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcjnlzf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxgazyi.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqbtvmg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2immrqbjr.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2brcmwbze.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmcelri.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgcgcam.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ejujbrbd.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2myusbjub.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2atztyuyt.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nigsqywq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkizmkx.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ywghrcuz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2isxknlrk.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2phkruupq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2nygjislx.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2fiftycye.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjpylbv.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2efkcdgiy.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2igrnbqqx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2sfeullsb.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhldrjq.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2machojuw.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2clqvqbpl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2dobvyvfs.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhymutt.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pebtrvxv.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2boenzzxj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rmacfwme.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfdxakq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmxbroy.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sabcwkcq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqirqnaa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2tstjkjxq.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2axxzzrwo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2knbfwyak.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrurncq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qpiwbqzt.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2njqhpqbt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlxlayx.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmhxgcw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2eurowive.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxwmvno.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zaekykjn.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2itzlmzxu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2txbyqzep.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wincqntf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpupfys.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cflyfluy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmeyarj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2adauyimv.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfqtuul.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xalnohtn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2krhttkfs.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpfjori.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2oeredbrn.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrndjcl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jomkdhxb.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvffllvy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpwxsrs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2moxkejuo.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ewujzhlk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgqxnld.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbgzvvt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2doeklgld.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xocmnadu.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvhknsd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2umcxnlda.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxqbldm.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxdesgc.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2expoxikj.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2lhewfylv.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2utmfwbco.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2byqxyfgq.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqepsvq.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjjnnmu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcusvwuz.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vggfhhco.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsrytqo.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ccanwekt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utxhmcvw.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2thatznmz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zftrgtqr.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kcerosum.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhjkwzy.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eahqqnry.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uklwidaw.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eicpmnnh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vomuxbid.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyyjlcy.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2xluixnxm.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmjwfao.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfkwayd.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cinpvujw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2gvijgmvw.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wssuceqi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2brbcgdgz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwooenq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2setbctgg.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2tqogbkcc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkjexud.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmpduoy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mslbtqnm.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuqaupi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kdubbnif.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmojbge.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebuzarzh.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2izudwiyz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxuukku.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oaurmzsq.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2viizwkxt.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2amewcseg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hguwmjdc.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxulowy.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhoetkn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2icyzilpv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbehnqnu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhljbss.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ghryyaad.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtfxlsx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sifcupcd.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2iqldslnu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxaqauz.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kifxniir.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwaglrtp.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpneasd.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kilyubga.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxgehcc.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wdislgic.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnzybes.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wozyhiun.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkppelc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqeigzmw.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dxilhzct.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgfekdf.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2eduggljn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmclncid.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2medvhuhu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2nahrxqcd.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnweata.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mayhctgq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdtmxdb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrykdpu.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2honmenfm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ogehyehf.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgqlxgz.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixriutju.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2krsjnbab.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfsmzuj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2spslcvmt.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvlglms.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkpkpfo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcqnoge.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhkgycd.html


<!-- 参考信息 -->