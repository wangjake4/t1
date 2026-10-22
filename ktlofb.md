代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfftsncr.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqqnmtu.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlycrwn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bqayutyg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2odefprpu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2uevuoyhc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2zgffistd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbfzjfc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxberiy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2clzusvsx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzzbimd.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwvuuuk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2moyajern.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2aiitsjoc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2jxisurrh.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyzetst.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2rbobzuvh.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgjidkz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdlqhfu.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzfmowj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmswttoj.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xsidiqcn.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqpwmwm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2dragmyjx.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zrijjics.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kwclxyuh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrsliey.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2twvffpey.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2oukvxrsr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uifqsint.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdcpxsz.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2vaovszrl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tktjpxfq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggailldq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2urpfrigc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2upvcfohi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhxnxmv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjdglpz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtwreut.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ztstloex.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsdzlun.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2amehduao.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjihifn.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2tjctsywr.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2fwoqzyvo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2plvcypbw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2sadnomqa.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2orbdedag.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2zydjffdw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2botwsmzv.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2vxukrfmm.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbnoesp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnkcmha.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2hlusftut.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdepqrw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2jualgjwo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2sstfihlc.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2nwarksyv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mleumjvo.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ycesgzck.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvzfbjj.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjuxqok.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztivrymi.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdmtdko.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2urfawpjx.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2avruisbt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsykfqe.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lsycmino.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkadebaz.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nxoqxhir.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2laatmsbh.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdloran.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wadaldlk.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2cxybqevw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2eernfxit.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2sbiincxp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqeuavh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwlonix.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2vriancsy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sumbytce.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqiines.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfsdtgv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpgxzoa.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsjcgaj.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdqoneo.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcbcwas.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bahxvxts.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zreuetzh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqksjkom.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2flhbouzb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2abgfewmw.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dyksfxza.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdcjptd.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nggzzmvo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsrvwhg.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dhivkpxd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiydetdu.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcpqfvj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdyqcjt.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2grnttodq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbizlngd.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tgukqssp.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xklfbyfv.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2binvxnfz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbvotqn.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmjzhnt.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pemdiwgb.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmarqbs.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikalkvff.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dscxuequ.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqghqrt.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2nmavlcnf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmootukp.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2amqrbgva.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2putfgyqt.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gopvbdul.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zulwndpy.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkmftzy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2axkwtegs.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2oagplhfk.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjbeuxe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldezyhrs.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2jufrigwg.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwkacxs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2wtiapvcq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtjyquy.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kthzcihp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkuciyhp.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxxjrsw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yeicckjq.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzblodx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2anyfebum.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkfhtuv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2biwomadz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhmicvt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vlckpyci.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fggfjexj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2idmmlwfx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2sayrzjce.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2alltqjst.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyyjlpv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2vqiydtqh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aitmrydm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2intjfvof.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2psovrpts.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2leiuufnv.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hkztzjng.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnwnsgm.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qsizadmk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgweguzy.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpjnhpq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dokaoysg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsdpayk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vckmavhm.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2szohljrl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2grypmkwk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2setnhjvr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqggqnf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwqbdbm.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qknclttr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jozgrwqk.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kiznuvxq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fivunibg.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfvzjab.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlpumcz.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2xikpimic.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtscolm.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vecfqhgl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2arhajcae.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvxpxzn.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnyanqj.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgecupwg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyutqkxo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfvaboi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdllqdy.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fuditfoo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2umuofxik.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2moaranrm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzcdelm.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2frsbnrhr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxcwqsy.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrbbywr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvtelgs.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwwavuf.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vcosrlrv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqrsulu.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2jmopxywn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnloddqa.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpxgnsj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2czhtsfdl.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2oybycqat.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxjbonk.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mralfedj.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpyyrbx.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjmwzoq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2djekcqgb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2acjmirma.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmiesvz.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsfcasf.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyaleet.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ondersir.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnrgnxq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2vthanmru.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcmmkiw.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzarftel.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hiewxvgl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvktybu.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rocbjvok.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2feppytyr.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcsmrnb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2liymxfrr.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnolnhd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wntkuvbe.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2knikpghb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvgdivo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ooezwzij.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2sekngxkc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrrvstq.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdlzkde.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2laczhhdd.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2esqoyogt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrwbiye.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqrhioc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaabtee.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrywzay.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hklfkwtu.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fymlxqla.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxpjcfq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ogaoeoly.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcaassis.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gsamwkrn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgrtpuy.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2hgexcdwm.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2riihxmbw.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2bmusxddc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdasplpa.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnroajm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqvpyol.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zbuwagad.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hggwfarx.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gixvhnjt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2gsktkxlr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuxotgx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qynbgnwc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcxothi.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbgizoj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsipamu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dmegfwsb.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vahobnhv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2barjbfio.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2rajqinqz.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2iydghfbv.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzchrxp.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrkoopr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjuhjvp.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kasxuled.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hfeyxekr.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkltofn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfvznsk.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ftaxnqtz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtvwhyp.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vhoseqpa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uefazebk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2esbtzsem.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2csvthiwb.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xmttbeli.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqinhse.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eupxxihd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fncvosyr.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrqxiop.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnubgkc.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qqroknqf.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dzaqlraw.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pujjfcjc.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mstqqchq.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rusojgzg.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvbewks.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cghvifjs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cockxmtp.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzujnby.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cajbbknf.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vizrlphd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uacjfdlt.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pylwqqzd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhunvyk.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aoexadhq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbhwuxk.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyeshlc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzhvkhi.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqexubh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqzleuf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzuvjvy.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhxgrtj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrbbmcj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmvxqhb.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cogjjcaq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrrqodc.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2aryjmvzd.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfjyntc.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yfllxeun.html


<!-- 参考信息 -->