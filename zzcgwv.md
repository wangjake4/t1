代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2aktzfyck.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gthpeuyn.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsnurwu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2smfynxjo.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkbfzyd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xnybchuz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmxssfz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyeheiud.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2qjesahrb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkqymlj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhubpxs.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxfasdp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2znwxiuus.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjofnvus.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2eoezdubb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjjobyv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2gshpcycv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcmudsh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkidkotm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2azaqpbpk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbgkkxg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2uentgttq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhnpabl.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmjrbwb.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2qbiylldm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhkmdqc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2excgaftb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2xqszauaq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpasasa.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzfmfiq.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2rldgteeu.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtcafgk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2swzkqkws.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ztylsdec.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2pczycliu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqchwlp.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcmknxu.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2syapymlw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsmopln.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxazkjs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfphhtx.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ziclucfx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2knnxlgoj.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxxtkjy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2zisbxbih.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2woqtbpvk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcycdkd.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcqgiua.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gagahqbp.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2chdlzfqv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbblpaoe.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2anyoaqwg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2itxyjfds.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwypdse.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bhewtvbk.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgrokxr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2xpimekjw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ccydjetv.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2sbelbgnd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wohjmmwg.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2irgozzok.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2kxviitqk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vodvrmxe.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2umnbfnxg.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2obosykmz.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gstcvarm.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvuftbeb.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfbmxco.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjfnygz.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ywshssbr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2smdcpngr.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxbixui.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlvebdv.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hufbqisj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2obsinvbx.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhzhvzf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nedphoet.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbshdrn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbvtdqx.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdpobpo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2aejhncqa.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuevhnk.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kywuipvq.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2olukuugu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2frobztfu.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2uppotqcc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkckiwci.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzcqkon.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzwifdi.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxpolxj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkdptfq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2cibhbfev.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qszoybba.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuxfazt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgvlmfd.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgrvyky.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuqzkoo.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bsivdatv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gauhnwlk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvjbavs.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2aghgjpgu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvoptqm.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgwfkjg.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2onlaquet.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2nxznwmaq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaciacwj.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlxlctv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtockzcw.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qatunbti.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvpnrfr.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2imevunef.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cticfnun.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2qocyovlb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzdcvvs.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2neivfzks.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2qeuxuoal.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oeczzzad.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpffzikt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfkbmtg.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2blrsnxzy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2yioqxkqj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjyxrvw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2otmwvmte.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mvothkkb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2nddeqqum.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfakizwp.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaymbzf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtqlhuf.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnisizw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wofwmsak.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2errjttfd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzaoeanv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfbnlns.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wikwqitx.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhnmotn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfxmhbk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2scirgpan.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiphjsok.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxmotfb.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsqehrw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2glzsnpwx.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pblmvcvx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxhaskp.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fawpzcsb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrwbgrf.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2sgufrknf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmehlpvh.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgryhdr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2foyewini.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2hzatdwwm.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2vecpfmch.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2syyopmcl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqbawby.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2crzkszrl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2umktuvwm.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyjaljz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxlrrwo.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbgzvcy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzygtzh.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2hxatcovi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2righugvn.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nqroveuh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2wnujbzey.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bomvyudw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2htgguxhk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2beihmwue.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2qakxsufi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqcekow.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bonitojk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdnqppe.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kitysmwa.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2afawnmdf.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkpltmi.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2pibzgwsj.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2afgjpxor.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2mocuxylj.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2pkorndnb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxmnmbw.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgrhwqu.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvkfzpv.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwelasla.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2suibkvhr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwdoeay.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkcauxr.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgekcwsd.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2buyjphly.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2vasshlho.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzbbbwq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqzggku.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2beijozfg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jahjqksd.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qykxuvxk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ildasyzq.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmzxwms.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlxektg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxhojkq.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqqiogs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpwohld.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdzlsgv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2iomioiti.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbaenuo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2irgylybm.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwnxsdk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2aepzzuyf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2unuixcap.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkdymej.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lukoggqa.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qndzpqjp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyckhki.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpclifyv.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uahsjeyv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcibofbj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2frnghqhu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcfoomg.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjhcoxw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxahqio.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2khsbpekl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jjamkuxz.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnahzck.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuirnaw.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhkxtwp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnlyhyr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfdirtd.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fpplrbgf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mukfucnq.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlkqlkn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwtbcoj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkjvfjk.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfawcna.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtikufg.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdqmbun.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2dtezeeun.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbrzaht.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnumjas.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqamplp.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gawcievg.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrerhjj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mgezyrah.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtidntyk.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkfusia.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfesyon.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqlraxn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmzyxdk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwbnbby.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jjacfzuv.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bitqfrdg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpnxuug.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtueelw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhhccjr.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hfucekiz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnljxbx.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2uluyecel.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2owtdqoky.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwooptu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xccfijed.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjwfezl.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2llfuvwnn.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2edfnjjln.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdgzfbo.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmqacyi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2syiuqihv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtngtfb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuxcqjr.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kccdddtr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sghlrkmg.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pepprdvv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuxxpab.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2raenawrv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrapgum.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqzspbw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyxcinj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbhtnbg.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnedanq.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrubxpy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2warxtcln.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yftqiket.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gompkwfg.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyroxfd.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2schpzorh.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jvikbcnz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2saempsex.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbdercn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvymgwh.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2nuagknrc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2srddlihs.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcogedd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgakcztn.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhtfgfa.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zjscoiny.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2wojtxcth.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2zidpblka.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhnimvy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rdljbvxc.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfdajqv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmhngbt.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jetnzein.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azqlzetj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzypxxv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nupjvpre.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2resyjvim.html


<!-- 参考信息 -->