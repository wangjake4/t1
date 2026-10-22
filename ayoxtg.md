代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2nezuqmue.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjcvdvn.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2iednsaij.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2erjofpie.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwanzmq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gzskhkeb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2luwakvum.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgstzzhr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2elxleiur.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdxbzur.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwvcfbx.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfahknk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zegfjmyx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zccxugyp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2yurjvqwv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fugtydyg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsdkpos.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmtexjl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2vimyykhz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtjlaet.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cglffsgj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2dybugiqw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpoowjq.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwiwgzh.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcxnuwk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkekxqs.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvxmxok.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2cvuzeqsu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2feofzljs.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxpxypm.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzhykbn.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2sagtetha.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyzgbrt.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbwczfy.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2vygbsmrs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlqpoib.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvajkwtu.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqgtcdx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbyigqh.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2afwmrihq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxwgbcg.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2xmeetdzm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvfovug.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpqycvl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqkksqw.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyqcapn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxeyqlp.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwxnnic.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpydsgqv.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nziarcip.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsxdzvk.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2grzxvwcn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuoydzo.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmsghml.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwaxipu.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ttewwngd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2tegxhwmi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2bblznjdi.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2sklgbmyt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbkbjyo.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2lactuorc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbtvrcb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrocwgfw.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2pfizfrcx.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ragfzemw.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzrdrca.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfeqauhj.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2umkywgzu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghaohgxr.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nywhsjpt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2mimieuij.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zywaypsf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwfqmsl.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ibiyugxx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkhwdgm.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2larpurmz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnlslsg.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsybsvt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmdynax.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2fjteccxd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqdhotz.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbhultd.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2judmdfrz.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2emanmhsc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2lworjhci.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2flqgcjrv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vebgyrcn.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuzyjma.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2imqhscgr.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xakcshgk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwaawjps.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2tyonfffc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuikaymv.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgfkeet.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqeeavau.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmesdmc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqguybf.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlejuzy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdviwgl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkrqhoy.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxddwsw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuuyhcv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpjqgkr.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2hexfojet.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2qowlwepl.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlufuqdc.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdmikuy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2htbextqw.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oltodkvz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ioatlegk.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2avjlomrh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlaanyd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jybuuopv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2neealmsf.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hoambqkh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrwhbav.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnqbbil.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbftxlj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuwgorr.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mcstjint.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2hehsjdvb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwadccr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqgjnkw.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2njaktknk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2qejelnwu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxlgwxa.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjvvbaw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2qaoxdkvr.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2meliezly.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2boecnbml.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fobpekry.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzbavoo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uejevzri.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkfelnx.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zinllaaw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcqgxbr.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dxyzjokv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyiblrns.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2drcqctbq.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqxtkgt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2egfnyxdh.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ennmuxvz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2pigdkcqh.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2orxpveud.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhpyljd.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjyjlwn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkbptum.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2aovenqqt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2edjwiyuu.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcqsofc.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhsovcp.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hunnzysu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbkalmk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qppvfbvq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgzcpbg.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbmqmsc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2drrphgws.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqmohug.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxypmwv.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuzkswj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbaeafw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtbrzot.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2yukguwmi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbfpomo.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xituuswh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvkonwv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwdkhxn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgnkead.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmmcsic.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2blnetaam.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sttlzdve.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2krqzccom.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkvkvdq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzgghuc.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnlrwdp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyspftbv.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvootkh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdnfvhi.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbljanc.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhatvau.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfbsnwi.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2pdihyebv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2khfmpfxd.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dldnxmbt.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrshnca.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkszjgo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqkwvyh.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyputmq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtxxrfk.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrfaiwk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwfwqfz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ohncwuwh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2eijqdigv.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qnftqgxu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnneitnj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwbjchh.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mimrfjql.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovodsdzy.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2wbznsdpf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2byuebxul.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvwsdkg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2setrgjuo.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wxalopio.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzgqvxo.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2atjzjhxz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vscubsud.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrvunav.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xisxcwdh.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyqjlfx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkzqkyf.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ispvohge.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgniaoz.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzmrrko.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueisgzvj.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqykmkc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyweloaw.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2budbamhe.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnxosjv.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2swpjztmi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2apawtkuv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpqegwg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqkanlp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2stohcdxs.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpkaqrj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tywnqamz.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2xebijwmd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lugsxnhg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtcxbhd.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2aggvurar.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeqdged.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzdbisr.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2pknghxaj.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2iifuzypl.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxtelfn.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2duxhvsyd.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iybzknhg.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvoltaw.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2twfwuehh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsfrgfr.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbwmlfr.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2htjgypny.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvtfpyj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgdxqea.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuzdtgd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmgorvb.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuaufma.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cgioaldf.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvtwluv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bipwlisz.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2emwbmkre.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nblubxiy.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxqaxgd.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzdwitn.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytditvnm.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mofwgcwc.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyygtfv.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2wumqupmi.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhiimbt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbhaiqi.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rqulwzkx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wheuxgpa.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2txcfbxqy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wbevanjx.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vhggesog.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2apqsqynb.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2phsjtbxp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yobffumm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2gpijvaoe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyyvwkl.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvnxzwh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmyjczw.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnmtrtc.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lodhqkri.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2mljpjaqt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mucobmhh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eoggbftq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2axamuwkh.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mgftglgb.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2innjlgpw.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nizgpfkk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjynwgi.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzljtus.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wshsikog.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2brvbdvqm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmloexd.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yohdynba.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpuviyw.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzumapb.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzryopz.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2oaarnewl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyfbftt.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zctgkniy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2frohease.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2iebtxmxj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkeotfmr.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zfysuuxv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snqljopj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mydsqlbh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqgbxfo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpyabxe.html


<!-- 参考信息 -->