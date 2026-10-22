代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2okvaeulg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2twtbobed.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yfskhdoh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcvkmme.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnrfste.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rovtuupc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wwewbccd.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2renlvmty.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnknhcer.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkrntpr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2daunhghk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2drzvkxjy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2gclvucsj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2unculifb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2polfbybx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2yrclyyxj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrwtjzw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvdwzbg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rupbniug.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2mrchdlzs.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2qdljppnb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2unrmrkzf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmfrtci.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2tcplwhrm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2fqaasiee.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhcmdet.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2dgusuxww.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2hktoynzz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtsjgoe.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vylodfkf.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2vnllocjg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2emurhsli.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2arpopxcy.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2fzngqgbu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmvqvbl.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvpdhsm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxshsoqf.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbqxboj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vviixcul.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2uyelvoyu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2eczjjxdc.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2frtgghqy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2akbbykte.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zdegipya.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2smepofgp.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrerdox.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwlrbjv.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cuussyew.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2avnrcxme.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2jijzuotj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2aljcyxzd.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrxnnbz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvqnnrh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2wayybkev.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmkfuaw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqwrpux.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2gymmcevy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2svscgapm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2figgmxnx.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbjbhym.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xviskqem.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fdihzdyy.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcluvhj.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvfivjj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygewygps.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2duqnghns.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2oagpjqjc.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfmxawj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2dydeytbv.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyprsxv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2meqskrsd.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ealcaapf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cffsbtnf.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jjeyfdjo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgmghrq.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2lkflxhpk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlziwmpd.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2adetenow.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hahpxnjw.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lnotekza.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2urssutrd.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2aqaztufl.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovotngpr.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzdmnuf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2grtjohzk.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hujqtmgi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgettijx.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2quxighwt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwrfite.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2optrkoxq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hduqaing.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqumvjz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwoywwdi.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wnopedpk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tukddqze.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqrouhg.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zmekgicj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2evxjqmrx.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2aqguwopo.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2gqelszst.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxxtdpi.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuffrddx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hkulloqx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eetkaiai.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvdtxnz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2plsswafw.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjnzndx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkaeaobt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2sknoynaa.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lndjpkub.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuvqjna.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlybpfl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lewtwojv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzozbwi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtuzuiy.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zxibpoab.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2tuudneqn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqonxlk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgaqlhvf.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtkfxev.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2lwysiztl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnxzmeg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xiryhsee.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwnrmfv.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrjqgag.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbasejel.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2albqtlvg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfgderc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2apzapsjz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2swcpurun.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpszqir.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtxcfda.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2csimbful.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqxxgct.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2eikrqata.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxofiwk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxwpcct.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2modbojpb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkiqddp.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgaljhb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnikoly.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtpsbwl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2noizombz.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cbaejqoc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2uljwwxii.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmzsncq.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpkjjvu.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2idhpaatq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dochppsz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwuyrry.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzvalcd.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2luntkdbp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpspxkvb.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lovelnds.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbjthpi.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsujhha.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2krcwqgcd.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jacvssbt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxbkkcr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnuithb.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gnghdshd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wezjdtmy.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2iazqattp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dynjnwme.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hztompmz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2etsweass.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxpnsyu.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqynexrj.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuxvunx.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxukemsa.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnuxryf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvigpqkt.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkjhikz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbvoxhy.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2nsychjuo.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzftfiy.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfioapy.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmxxyha.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2kysooetb.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wagnhchn.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rypirufd.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2cqurnwug.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfhgovs.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlerixm.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xogaqfvu.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2wzytcwln.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyairyo.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuorynm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2grozgwcj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtvpnxn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekoyrvhi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2jqposnhj.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mjghrbzz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2nevzjrnp.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2cqldqqvt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhabuvm.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfbvnhq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyysyww.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlburmw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2vggcmfry.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyhqijc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxsdsnc.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pgplwdgw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfslayuy.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rbktmsgu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdfqsjp.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2durgtdzf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hoekkvyq.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwoixhj.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xificzxt.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfwybvw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxazdafv.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rsarodsi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2yyplrwnl.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcerodq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrkxgor.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhguvzql.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjsjlpx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2unyjowdh.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxhfexd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhmtykr.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2fjszyfnc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnobmstz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpoltem.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxrkzsn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwlpfqx.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2zigurial.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwtzavn.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsyaqda.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2iunehppj.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sriaqdlw.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qweoiprp.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmovkme.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qefibrrf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2dszmthrq.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqvbbza.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ymaeqtap.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjzcath.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vueooqwj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zsguvkuk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zgswkrwd.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yiisemvk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qyubwwcv.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dfytwmfj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuwbjtq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbhiyie.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cvskyztv.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdngdgs.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2uuslbylm.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ioktjwvd.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zylxejdk.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kneipwjy.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2gyasjpef.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvejbjb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdimyzk.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zapfuvxn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pvykysoj.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2oyblsftc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ftflivss.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tojtwudt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xankoetq.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kefqdxjs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yevbuzca.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2upwsjqhd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cenzzzup.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgnuyvr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gextraqn.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgwtlhn.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xlylwksm.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvbuber.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjsvtzy.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrnkvdr.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvylwbtp.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2yppikyhx.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhluggln.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oeoztexb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgeosoh.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmyquuj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdnikmz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgfwkxr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2escyheos.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fdifcsyy.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsxjqlb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ernqzvjw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ceixnkjt.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyhijho.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrrussb.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnznbkm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcqwhfz.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2atiphpri.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2wavssslz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wvitepvh.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oenontgs.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzemhnh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhaloxfc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzhfxgk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2jpectthp.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvwtqwk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2joqiwgrm.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2aeiabscs.html


<!-- 参考信息 -->