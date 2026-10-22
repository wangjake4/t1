代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhzuavc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2auaqckmg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnduqaw.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2lzznracj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqudohm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dothftoq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjfnjto.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jyasoqsr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2aimkjdra.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2shmnsspj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwaayyw.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcjgwtl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtimhlu.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2humveimf.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2arjywmca.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2yphfvvoj.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2utawrsbp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmxtexg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tpiojjka.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2veidailq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdxqsmo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jsieqtdc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnddooq.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpoglon.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpjcakl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmufcxyq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsjqysd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbcmaoe.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxibnjj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlqevuw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubplnkay.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyjvhey.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tlneadqr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojspxiot.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvdwafy.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2fodmldhu.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2cecjzqoj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpaibds.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwwuzbg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvhukvv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqhalsd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkagfsrh.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrcyiaj.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdldwqb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ripmpqgm.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2sneoglcb.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjhozdm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2thqkwvxl.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xetemaoo.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmteall.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyeqvcum.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2koebowur.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2yctjtaqj.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2lbesgobh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zonbihan.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2kjywutrm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfpfitz.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2xobvvlyh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2etrfvozl.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2omjquewj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdbltep.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfbfcyx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lawlpgvp.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pdeziatl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxbjnag.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwsztxt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqptgmu.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmvbkxm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtcixri.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvrbjwg.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcbqngq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2glnmmwjj.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2izwrdmcg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsufame.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbtwfbt.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zshpqhsc.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgishfef.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kojtpmtb.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wepntytu.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtbjxyi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmtfrts.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdebxby.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmdtnob.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2alnjknbv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsnwcuq.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gspklzkc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkjvkkn.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnczxuz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2boqmadjk.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrumtko.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzpfxvb.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2gldiagyl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvjrwem.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bopokqwy.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfjmnyn.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdbdczj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhahakw.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrchedn.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2muhfqelw.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxpfsbn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmepted.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyzykkc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdqvbdu.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2toxysbms.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnxehal.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wcithywc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxppkce.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2odaojgia.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pssqgyme.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wedhmikv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xeyrwwpe.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdfyopp.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2swksyzrc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvewrxi.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2epohiikn.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2zctpjmvy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2aeahueua.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpdziie.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzcywbe.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjalhpzn.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrshmkb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2paumpzev.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzknlff.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxteyza.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2gosqmnth.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2elcijmsl.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2aiakqtdh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2hziqpquq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2effuxknu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvhdnru.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfkbkqc.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfjddys.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfrujih.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcdkpzj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2krcervpk.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdtmjbo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgudlvy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjgkupq.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2csbnowxc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2dexbkczf.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrntzqt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuqmwfh.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fomwdzlu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2klrpbgcl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzeorqu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcniuzn.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2owdisufs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuqnube.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnuzicp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2yywklbux.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdenahg.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcqpuce.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gspphype.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2oeoclaoq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xyyazuhb.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nlahbaai.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2omqymlzy.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2adcslepa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkviflhu.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gtylaavu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jakpnlqn.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfhwgty.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhbaoez.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqduszbt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnjglze.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdoofup.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcphhoq.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jjijrbda.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2utpesjgt.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwpjtvf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbnqmjc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxqygny.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwdwpnp.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnlfngy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtyeegj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjivjvq.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsfivxn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjennwon.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrnyqhr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2butnpscu.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2avblkatw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnfyniu.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcckftv.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzeciyh.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2urckzmxu.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmkkblk.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rlepbrhr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjugmky.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2juxtkhyr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmqcgnl.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpxuzqt.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2omenrgxg.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhipohz.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rigryevk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjfcklv.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xeldihbq.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgpkkgm.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2mjoxfllj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvdrgoz.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqwmcvl.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxlscxz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2esfzutyb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrmkkpj.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2abisbpek.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2hafehxkj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxivbfw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrbsxvd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyzutlu.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2feizcysl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpkrtzk.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgtqidj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2msxqpnpe.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkksmsx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2duftddck.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hoocweev.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzvfvyi.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qksvqkbm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxgztga.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqvgmrn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rddstahf.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxhbgjt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2npspgjgh.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bghwetyb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkefnvk.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlztufo.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbuyhwjk.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxipfar.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvljxcrz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zohtmtxn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgkzlke.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwlnfps.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjavbvtu.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtzfxbc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlydztb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2stwoxwqg.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2llbyjbxc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2shguqjtl.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2dchenitr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rteovpmz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqwccna.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvimtll.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpeqlky.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2dptfaoty.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2hreuxvln.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2oipwwknx.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsuembc.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghovhgia.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gureatjv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhfbaxf.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gllrvkmk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2fptbhzuq.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhqgknb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxqboak.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmrxknq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmkprew.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2egojsvby.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqdqqnk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fclndsun.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aaexloqh.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwoacre.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tonqqplq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbtxmzd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rundyqmk.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2glxduuxe.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcpvsip.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkezsbkw.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctusihsa.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxzhpab.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrjdgbe.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uohdcgog.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tqiblxfk.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qssdifvt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2icbwxoju.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2qbltemtn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqiscql.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjykwnj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmusyvw.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fziwplaj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuckuhv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnffhny.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlylixf.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2emlfimov.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bazbnioo.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iapknlfs.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2byzjkgxt.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2cglcvgxs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bexdrwdx.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hfougaaq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvoazkpp.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcabnle.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqluwopo.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhvxtmv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzctnwx.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zuicujqb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xshfpbvw.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxuhadq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbcevai.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ievklmvt.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvbpyfv.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2thpoycpn.html


<!-- 参考信息 -->