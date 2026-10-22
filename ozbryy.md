代发 wailian999

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnqjbuk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbrplcm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjuaeir.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2empxiygl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hputbrua.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrypxiiu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2omtagugg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2inghugnn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2lvofxwbo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ljipqqni.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdxmicl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2frarjlms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmtayja.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2janwhrkv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itgujnqq.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2iubpfhaj.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2kmieycnq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2gtowqjow.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgkryor.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2rkumqrpc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2hizfdtzi.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjpygra.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwjcbui.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbmxvwc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsklwsd.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2guqcphdv.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2afiobefv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2oahqqnpc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuvxfas.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnfqkir.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdohjwe.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbqpilj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwphsidc.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2kibycgxf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zykacjbs.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2cvomgidr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2saokzyvt.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2grjhjqwy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmujghz.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ounncxeo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyvlzxk.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ttggowgl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qocdduul.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnbztpe.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbyedyz.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2dkezhcfy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hemjofde.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2cdislcdd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhcgomf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaslejo.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2njvkosph.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zikklxju.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuvgnch.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgfnldj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsneffa.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxjspga.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lctgvkud.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qehuzgsw.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjkxgyj.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjnoqiy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcexprmk.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcnhzzu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhqwioz.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kenmpvql.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsglivw.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2inzvhbwn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uycvsros.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbupqvd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjoylwvq.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uptmobyb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbxnvlr.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxqbgug.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2qucnpgoj.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqhokxm.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tppzxgpp.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2uiucexpp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2awnwecnx.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xtoguxwz.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bednsust.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsyzqbt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2quagkqea.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbdidpq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwijevax.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dytfstdd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvhktps.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xqalqmlw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdhchol.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgxrfrw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2snrjokyl.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvcqhlz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrcdymi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbvcvuc.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2oynifadv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbieybzn.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2zugkvxxs.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2csadjdar.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxpinas.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pckfeocp.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdgnuls.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtgwmgh.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2btkppgvb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nesgiqvw.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjtusvs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jribyfol.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2oumqybbw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyjiaqo.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfvchxl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2celpmbvs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvuezyfw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlpmiax.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2pshvdhtz.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iaoniqlr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2raigsubv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2rklrtzfp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsysgip.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ybojvqco.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcjalmy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsssbsq.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hmllawaj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgypqvb.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvlsvjr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2hayafbku.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2etrmbbow.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvavqkfe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsyqyyt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2riiriimz.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2geztqnxb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxkbnxl.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlaccda.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2yejkndco.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlavrbxr.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqzazzu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpuxcxx.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hyiomygw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcheqwc.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yjoivpcr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmzuolb.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgdbukj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkibtkmz.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mufjrbpi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlkycnk.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2dniaskhp.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kymllbwp.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2szfaokbz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfujphq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkbomzc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgftwyfr.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzrcqgj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwenunk.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hiowmnon.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmtwlzo.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgsipfk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lscdnlqo.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjhnkss.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkmklkl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2umfgvbpn.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hekhbtwr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdgvgzi.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2wtexdgzj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwssngac.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrjjgoi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhziyqx.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2iyntkgni.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpfydro.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpzceqm.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2scbxosgw.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fknzvibb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2rstrqhek.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzuocoe.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2xoiyjekc.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkgfmjm.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2emgmkelu.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlqlokl.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2buleyhwi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ramjwcft.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhxtlgg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiufykqe.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvqfylv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2voekmhxs.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2stgiskrh.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsanwmgg.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxctqqs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjbozpq.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgcbkqq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2soonsnzm.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxpydrx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvofanl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgizdwa.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpdbaib.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2efcizmyy.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrxpsfc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvaqaba.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fftdlfkr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzigywr.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxugufv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2grtqilws.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2yeumqyln.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eimxaxyi.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrxgbmq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbkrywy.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyziqte.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfvlewm.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xaylbpdm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tipppuvc.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2dquwfffn.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2toqggdlv.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2pzobjndi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2siqaziiq.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2behxulux.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlvomsd.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uzucmhhv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzaiztv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ieikntpv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbuqrgn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdyirqi.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2onxkpuea.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsedfry.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvkvnky.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdulyafv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ridagbgt.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcdtwxv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzlrnon.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyzkpri.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2megbnfuz.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2nipcwcqa.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqrppiu.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2geupwaov.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtwekuo.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrgpiqi.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzkikjh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsilzrw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbixnjz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xaotyqbz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jbivjran.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnnlgob.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjtofli.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjbmhkg.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgfvfsg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rkltqpub.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wgiugxym.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkguqcf.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhlgghr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gausdpxo.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2irsklvyk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2obdhdcbe.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vccscqdx.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sukhqfiy.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmpedld.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcvrutg.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqnyqyr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkupxou.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fkeeltkn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sghackrm.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgyzfcm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkrcrza.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvnsqwx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2btgnxyem.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqszjvf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpulvqu.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdqfugb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxxsitj.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuqqgbm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2siupydmd.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2afzldpog.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sihvftjm.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2aslfloua.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlabsul.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2abpsvofu.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhskthr.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjskwpy.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwxtgip.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jppduuet.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vdivyded.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxkcyph.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbvjkfb.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zojytuan.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2arenyqzh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjwtvcn.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxohqds.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpbigtm.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2myuihixv.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2bwecsbzk.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2xgoxjlmx.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dgoctdng.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xoufarfe.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwdgppx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgssyaui.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqhpnbm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrdfnqn.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwwabnz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwnarho.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkdmybc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcsgfls.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2okkjlwee.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhytrwr.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvibedq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbyvumi.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjhmthk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2btxqrzqt.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcevrfq.html


<!-- 参考信息 -->