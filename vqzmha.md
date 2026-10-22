代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbryjazy.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnobfxdm.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmvthkf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmlrpea.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2bsshxbgk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gpiflrfm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2qdorwmnu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2olbuvfpz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjhnvon.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2unlixbvo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnteobpu.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgzznef.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2unfdzdok.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2skbcrtfl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2yojpebey.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgbnlan.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwbnivr.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkiphaz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2epnkltis.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrfrjwk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnrqtaa.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuyhupm.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ndesmfaw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcwbbbv.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzhzdjj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wcntpkfc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hjttnyjj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2csncfbeg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxkfkep.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyuekjx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2avynpvex.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2sntdutbt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2dadbhlnb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pphgafjs.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2giisxgry.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgafzdgz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2gztxdktg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ytllbvcp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jaineuxd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2aiaqukzw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrepnwn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgboofnu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjfbsow.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2amuhpxwt.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2njhbxazz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2khscqxmv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrkfadf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2qtozahnq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2cagvomfn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvxkhjw.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ksawjoob.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqfrjgy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2lahnowoh.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcvmjxx.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2qvglaqmj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2edmoweem.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbbcamf.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwubugq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdsmtne.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjbdkci.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tixcdsud.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhbvyzz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlexqfv.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2vktbtwxo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdzggbk.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmnfwis.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2szpmdhgv.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbxmiih.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrqwoap.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2chmnvjkb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjvvprh.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcxcfcd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ilctpzdq.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2omzsndmv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2twfmkfrv.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2fstvkfzu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2fctteatc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2uurhjbtq.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2godzbyfc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpsswpu.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcoqmim.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2jxblofpe.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2azfxuywz.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzfiopk.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wedwdmgu.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpbqwjr.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmhtmsg.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgdpefe.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbrqvaz.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2swvwilcm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2yvygawzy.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2quyatrfp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2aevmmpdc.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjzazbt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrxrbtw.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2okenfipz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxoblxl.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsjmcyg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujovxmyw.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2eyarjmqh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2orwiawrn.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmegbfg.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gygumqlb.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tuansqer.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqqjhhu.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vfobwmfk.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgadkkm.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrsxisd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrjyinm.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrfcbwr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2njnrgsmn.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kdiofdwu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2veejgfkn.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmdtctd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzktpwip.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dzseqlce.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aruymttx.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2guhjudzt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsykbit.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxgsnuv.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bewhlzqe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzxafqg.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfenyzc.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2olgdmalx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2yuknezsw.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnedsylk.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2clqoijoo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdjgxeu.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yyomsdec.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlmwvly.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gksfcbnh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgeebbvi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjvjidx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxszgtvw.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtvtcdj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2typzctgv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lymhauiz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbpbdub.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsaxxmgy.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nubmbkpv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2bplsuokt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2elpitbxm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aamqwipk.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgezwoo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2negyaunq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2iobvwues.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oobmlesz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2jodltozk.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2scqfhlqh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyaphse.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrhmvnd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkablnqx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2djickpag.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjayklyi.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bajmipnt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2mitgpahf.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nyutisvi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvukrwn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbijseh.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyceysq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuxiooy.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtqyjsh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bnaekqrx.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kjetkwne.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlweyfln.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnadgxj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dysfjhsp.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsnunuq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2prffucsa.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfivlel.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzelvvrb.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfaruerj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxomeil.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjqjuys.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2glmquqvt.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ndztlxov.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2haqaxvlu.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aoljmsfs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uemkcpoj.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvkbras.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvxtnuu.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwbufcv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zepeaykx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdligal.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2efldjhvn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxnnfyb.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2yisteupy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2spyufahk.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wcixilxs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2knaqiyut.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgqajiz.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2nayiltvg.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2myxlmrpb.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxgrxno.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsvxiyi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzvtdbj.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2kztiiujg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2plfpanti.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcuzdao.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2okdulinu.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oznodzui.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2tkeamvwf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2iessfdii.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnsbdvx.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2prspzumi.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2zvayqqsu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2yksdhvsw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkrvypn.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmmjakj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2djbqrxgj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2haotdoyr.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bozuhmym.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbicvve.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhppxps.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkepvysu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2wvynvtpa.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfomcgr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2uswcszgm.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhipbyp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2isqklbei.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2helouyih.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2qcoffzyd.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vkababen.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwildtp.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvgbwpt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifybkgxb.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrbrizl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpybqmd.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzogouz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pubfiqok.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdpwmxw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrdaqnk.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsrfynv.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhhetxd.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2doyrofbp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzksswa.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vonhxqmb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlutzgz.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ybajlmfx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhalxngb.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zagydyab.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtmrscu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2keeskvqs.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mdyknwlw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gincehwt.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfrqbbp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2iriqbdhk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvyxwwt.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2oqoumwfs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mkivblpc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2npyfduje.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2duvgpdzv.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpmzfzj.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfqqicm.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rinpchcd.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsildaj.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2rievpoge.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbiltct.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqbnipo.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqlrcyj.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2atqeftzi.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpayvwu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgkgjsu.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2isxcqnpo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkhrarb.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wnoklffx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwibqpa.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2heurhupz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zqiabaqx.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jgafevec.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nazxuzlb.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfovdwf.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2awgwmbax.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gssdlfkw.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxhwyhg.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfprmww.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2mlggdraw.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gawqdiay.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kushueoz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nxiocnyq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nzheatrl.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2iucvafhv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlqirns.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcnxmfz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2knygvrul.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vuevjajh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eztszgco.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2papitlmz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmnckmw.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rwweqnwl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2thsbkgxn.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zatvpgko.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrxneoz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqinaky.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kabfkmcm.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmxkoma.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjdbpnd.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjvqpqc.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdidunot.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2efnftgoo.html


<!-- 参考信息 -->