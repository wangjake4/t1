代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2omgwwlcd.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oedehopw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwltaxgz.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uoiflfcf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwtxbbq.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkqlowk.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2clydsgxb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwszkmm.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxsphss.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cibdtrim.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2quohzkpc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mykotskq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2wleeowla.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ogloqpqp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2kawioect.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhxctjb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2digbrvwg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlchmfn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2kjriwisc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtvbyzb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhrimlj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2clmcvlie.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrrhzqf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2cizhsmgl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdyrmlg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqlmoca.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzgqhug.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkalvje.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhhapju.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2lquecnif.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvorpbo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2yaoybzgd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2cqacxzml.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2oukjjfxo.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqdboei.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqtbjay.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ntddqvki.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2disntjfr.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2glpdxpri.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmzfnxn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjffanbo.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbvkklg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mstddrnx.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rniymzqu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2agbgnkzs.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2voaoqzpb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrunlyf.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2rcilsamr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2pynolfdp.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbilqgf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftikklil.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lcryzjif.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2htayzhcw.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfdnsdw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvujdipk.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zudqmizg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kprtvjhs.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ecohatwa.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2welpurxm.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2haryvohq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2thcdxyof.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2gotmjoga.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2gipcjynr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdvmahr.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfuilxw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpsrmwy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsulxbjz.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfczshk.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvufswqj.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jpacleji.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlshlglk.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdaqkwd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2slnydfel.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pabnbrfm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyzntxk.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2frkmoduy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjebtww.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2iqspivwg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjdlyjz.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xuchwtnd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mulrsqot.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkjzpkl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhytsqv.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxrlffe.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2obqutlep.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2akqrhuag.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhibjfa.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqhvikr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hunkvyui.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2peqzesiv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmssrrjf.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqbtskr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwjckpz.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wqeaequc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxypcul.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lhekwtgo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2arhhqhua.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2aytacqqv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwiozbs.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nljchppg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2phqmsglk.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dilpouyx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhfbyzr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuaccay.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2inybwpay.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2whwwseci.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2cwiscaab.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2aowlqpoi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2yllqsrab.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpyfzpj.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2emvjokjr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pauirxfe.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkchrfc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqvvinl.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgcieem.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lycxxhlt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2hysqjjmu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrrztzo.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpdkurn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxcmlzq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyghibfd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2unpxwpkw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdcoooj.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsokzdt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtunxwk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyewnoc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eusnbwhh.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmmwtuq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2reflanxf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fadkpqxv.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wghhzuda.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2eograwvm.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ocshkole.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfbxdhc.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2azgcijkq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlnmwzm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzbtgzo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2uncsiuwg.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdwawbd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbxodus.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zpiwhngg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2vydvxokd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfuyzrs.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xamkyzwn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuqcvkm.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhcstcr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlzfvau.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcnzrcf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqzjjom.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2upowltri.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2irgegrgx.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmtjucs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgbphln.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2pylotqpl.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxfexrp.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2frzltriz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkqaale.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ueygxsdr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjesbttl.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2etxumkuk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2akjnehdx.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfcllay.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqndygh.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsbphmh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2omgnkjoz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrsczyf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2swtijbwu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmsgeit.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjgeluv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmjpruq.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtcfizx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2runjnequ.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vfisshpu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2bavgqiro.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyexgng.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2sixsugzh.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fuddjlaw.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjqbzmu.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsitupb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgdczur.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwccshx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwjzyrr.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ylodkuml.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbryecw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2syveluqz.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2biwejrcd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcnxegu.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnvtldm.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2clsaddjk.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjzbodl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfalrjt.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrtbszr.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdserta.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2laevarfa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2utwgropc.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mracrwcs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2emgiynnt.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2aofqxggq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwnoztb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwcpjaq.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmllbha.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2hglkfuzr.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2bensdxxv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxhflqg.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2snkxjkrj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2apktmcmy.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2frtncdgg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjwyiot.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpyyltb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmplfyxs.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tumkiwrr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2izibstuc.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyixrtn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rehgspch.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2avvvgvnw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2emqpyquj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2npvdqubx.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmvjglx.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2fignvazz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjxanqi.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gndgjjbt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ifaigwwq.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xeobacdh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkolmoba.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhwnyiv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuajmyp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzewycqm.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nswrprxo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uqthfdfr.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2fblmaqwu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zytfbfoc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kyowtzjc.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdadyrf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpgajha.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jfptefoj.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xmetpssm.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlztvqs.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwufobs.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsjbgqp.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnxhzyn.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxlkmuo.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iciiekdu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsiykjim.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rwiqmuxq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2anzwocrb.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzxcjar.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ueeubgbw.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ukptwtxf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2upmytsqp.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxsllvi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlaxzow.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvuelxm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtqehqk.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjnygdu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zwycquvm.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2uescnmxj.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2lukhyamq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwkmqdq.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwvtarz.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2raewxwpw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vvripekr.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yecmyttl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uizpwnzt.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2llygnizf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxvyewv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpqvxqg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdxuypz.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fhebhibh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mdospfod.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfazuoq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2axebqbcu.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrlokpf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2erldrfmr.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbpounh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2idwpvumu.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhjzjgj.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2plnoaibz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2yohvctcs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbueqhc.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmwtfzi.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbawwmm.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjyppjs.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mavhjozb.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvhfifr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzrnlby.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2slcmokvl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsajmvfd.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2duvzhgnq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oofeodme.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbnuxte.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqntvmqb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2lepimgmw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfnliqy.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ribdengv.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2bswneyfc.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxmjwfs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2djzigynb.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bqitrvpt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnqarzq.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2doqyhnso.html


<!-- 参考信息 -->