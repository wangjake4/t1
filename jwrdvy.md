代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2lawdaowt.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxashgzx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pixxxtbq.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2akvjwkwp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2rttgsiog.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2egicfowg.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vikvkyzb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2xndjlyoz.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pavxjenm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwtlqeu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqzkllk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2udtmboeq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjacsax.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xhakpfks.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rljqyzcx.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2rvczaitm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2simhofph.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwazzih.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqxymcf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2udcjxoye.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxzjtfv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkedtbu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvauakd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2jiagllmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdzbcsv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwfiofl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uviqshbf.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rymxehlk.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfgzaqr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xebblxss.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtunexr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2dolddpfr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ilckzzst.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvdobaz.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwhyrpn.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsigglf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuqfybd.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tmevrjhn.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvmezud.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2yndcxdrp.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyrxxau.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2xmecunzo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuonyzan.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gyidgnkj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyquhvv.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2zldkpbbh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2crnoahov.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbncwpz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfthtkby.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfgcbjk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbasudux.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcrnyrz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zncjxhba.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyjhmmj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ismtrlop.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ughfcvra.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwaiykh.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxgefro.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vrspyyoa.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2kggciroo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwldxrq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2mulniopa.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkrguai.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dbklgabj.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ybryamwj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2jvswahds.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2kegozzmx.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lrclgutb.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2atbydaim.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2prlkurhl.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2afnbwryi.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbcccns.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqvhyxk.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbtcadl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbodkbh.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vimcwmkd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwmqogc.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlpcvub.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oszhfwwb.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2utrglgyl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddziodrx.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzlminx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbupsff.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkhalfm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2qivwbtwf.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmpwlxe.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2elbdailt.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ptuctcvc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfonfij.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2divfkacu.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2coczbjnr.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxxwpor.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojiyzcki.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fcubeslv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdrdaxf.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlwktkx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmmqvql.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlbyikz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxkndmx.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rueclvvi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyilestn.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2svcslyxv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaybvcfu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2amkhgmfh.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrldkus.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwxivea.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2dyiqmycn.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfdnuqw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzkhizo.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgxupdd.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbjnctn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2puuospef.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzdhcpz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfktgyrc.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2diouajyi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpeclia.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2vriritvl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbionrx.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqacczpy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpmohww.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rznhwflq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxwumuw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2avvgpxac.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmyhhti.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2gncubtgb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxulwea.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsyqijh.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hromosii.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrrtjsf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwpkxtr.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnrzkgg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkteomp.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2abdhodhq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozapeups.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ekoiwkvt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqxgqvb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fpztmtjw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqgebue.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyixslq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvcazye.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lixgqndo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyeevfz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyebdyou.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2yyovftsm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwzzovh.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yngyvhhr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fjukwomo.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmoffrv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnujukai.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuirhcv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xevvqywr.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qgphthqa.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ufosbtzr.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wztljrig.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpvyzza.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2eaezunzh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvyzbww.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2atigpres.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkriqxo.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwstixx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmepkvaz.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjxgiay.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbeexndy.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2kylnotle.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2edufjiss.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cveefyny.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2nulijujc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvsxxvo.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjgzsay.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lublshyz.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvitasr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtinfmpx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mgngfjva.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhacbnl.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cagxvbqw.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkxiogm.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwsflmf.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohehagum.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjrrtcx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbzolnh.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqjkqvn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqnfmyp.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgzaeuk.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yicfnjnm.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aksrmyhg.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfiulte.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2njasjuta.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wibyxpwb.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2avhvupaq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsdrtlu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxxuxly.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gwiqweet.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zawqsqrs.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2tukwldcz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyjphpv.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkmkvvs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtttprl.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vaugcqbh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2llcuydvs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2knbebdfs.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2udemuyey.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxtdoxo.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkrrzhj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2tkstibni.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hucvvnbj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2rcuphxgt.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mydgozsp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrblifd.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfcwepy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejiwzuul.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mxswoenw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2atzrwgcg.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpwulan.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoloygcd.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dbftivpy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2akbcudgm.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ewztqbjm.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ougfuuyr.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2szwbkcsc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptduzmlo.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2covyzneo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2whxqodpz.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxkjncw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2myvkvadq.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctsuvene.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdjobca.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpkxzlr.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uuiyiuav.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfznimd.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2kovltxfs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2afwgevld.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2abcupkgt.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvdxsut.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2klvofjws.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qtukvpei.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vjoohuwg.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2msjeohlo.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjhpajh.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2trjnrsag.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kdskvnzo.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2mektxjvz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2intgbjhg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvihuhqd.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2prhvsmjy.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2psqakttc.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjemgjd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uclmtmyw.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kchufdfe.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvuvbkf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgpywre.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwjzecu.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ratwypog.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ztennxsw.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ckaiselw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwiuwpv.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tahktylj.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2logomilx.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wduycwdi.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpqqiuh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhjdnek.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsjsqam.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2esncigsi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ozthcmmd.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrndoru.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vsditbuk.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpjqolc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iduzhqmk.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlctiup.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pfadddwp.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdfndju.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kzumqmup.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbtyjuf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxshtqdr.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ozewyenw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pstxkpzf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzmyovs.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqmoitj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2aainlrnm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vldihyht.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pfundada.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wldpnifu.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2thxzexah.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cesyygzw.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2krwxcezt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sozgpndv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wwilfyxf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjzxmta.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2atmdylyd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mygafciq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nggchxoh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxzjnxl.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmgwxua.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrqjsyi.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2tipvgaqo.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdxbikd.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxxxnnu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pwabmlkb.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bibvfzcq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxbmxpm.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhssgoj.html


<!-- 参考信息 -->