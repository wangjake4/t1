代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdsefag.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqdzoaq.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2aislblgz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzwzyek.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2tzppxgrj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqhyxqq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2tearqwih.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtfvgus.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuoghywh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsjzlzt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lddgbyif.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmrtwja.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzotsyz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hielxzgw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2kokkpihz.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oiefrsso.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2trjdamjr.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2supzzawk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxlakip.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2filpfizs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnfgrna.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpduokf.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hovfjyyd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2rornmvhr.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuzkrug.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvpnotv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjlyxpj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2doeznnrg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2afiizsfq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2riovnkxg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ngoctxkr.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2blfghhos.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlphkywj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxuquao.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtlkjfc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2scqjsbmv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhvdlah.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxcgzqa.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2yriqnxyq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbcsrtj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2opvavzxa.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2bykeyvwm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2appsdcyc.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2pttxtcnd.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdklbju.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nebrupfe.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jsporkcd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzuogaq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2trwflpte.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2eatiwhqq.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2juljcmpl.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwmpouz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrbwhjq.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdoasqw.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2pzunuwyr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvhgiga.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzxjtxd.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2scoobmsa.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsytdxfe.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uhshmtmz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2odxihxkq.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzbdpbx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmlkesq.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfioumr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2omdvzydp.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhwjppl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxuinqot.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnkscfh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxogmfwe.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzebcks.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjklybbf.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpynmwm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvsxosq.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwwzbhl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ihuiieaj.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtogzmy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2itbiliuw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpctpdm.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbokptw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuawvue.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqybjofy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2psahpiar.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvgnzah.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tijcnojv.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgiqnnmc.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zyoduvft.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqvjyup.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xjihkxcf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2abryqdyp.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmsyvqt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2alqtofjh.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bybgrxgc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjswueo.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2racvbaek.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2trcrmqxi.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvnqykn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2sihakhkm.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2olvzldwz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhrrodj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmczmsa.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2grrrsqfc.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxemcvi.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkahsmm.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zcojrwsb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqqucjf.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyucmps.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxcottv.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkuefgx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbarxko.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmuvjfp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnyelie.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpjvcks.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzemfull.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2alkdvaze.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcumwre.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gwuzhqvm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjedzzop.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jljfdqwo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkmifmv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2qepupiwh.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyhviiu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2pebscjrb.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2yzeutgbx.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbpkrmd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2heijsdao.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nezepfdk.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sqonltep.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoouhfi.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbgpyne.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqyeypx.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uhunwecm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqndrrfs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2neranzhc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kenvndqv.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xacejqtu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2razpqtxi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tadbgwyi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvwnsvn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2epztoeon.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2urxccqgx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzdfnfp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2esptkgei.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbydkqb.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhailrq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2roaqdrzz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xboecajw.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tshapehw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2bghpanos.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyrnutm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdlyfom.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjkpvfn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2flmogurf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpisepv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjujbev.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wrloykot.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmystmj.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fmumgugk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2iumqblsd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnpdmfk.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzntlyk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmznjzv.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnzwsjj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwjmnkp.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bnczruyh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjhxzpd.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2rffoyvmy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2whqkxddz.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2azssfofo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrewpnn.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjohkjd.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxydffvf.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgiqiwm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbheejt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2osmmnimd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2etfkxtqb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zaukyobe.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xohfryiu.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yuizqjsn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxgmiwu.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2lyoloumy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqkulqg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rovcwgfj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnmkvvz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmmzqpy.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2haoasnfa.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2amkgbvdh.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwrjwhd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxnoect.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnijufk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpxrviu.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2afodfpou.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyugfli.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcymxwx.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxphnin.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvfihhf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxkunla.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2bupeofjv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkwtgcc.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2kawbpqsy.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gulxeepo.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wytxgdvu.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvgpfsa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2asvuddeu.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcyctig.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yztmyqeu.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnsxurd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuyjcef.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdewfld.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mslksarn.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2wxscunbu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jmahjbzx.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yptzgqyn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2qocqwlgn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pilwkzgs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqqhmtp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2amjhyfgq.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2guvygacy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtevqri.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2iymovucd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2kalqkgap.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zlaaveix.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2unwzoriv.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzgauau.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2pabwgxlu.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwpicpo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtpldtr.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aflpdrwr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vprggnpx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbzogdf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsvmjxv.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvzdaod.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqqgcrg.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxhbnsf.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtdrdgt.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2rojezcqn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkdffgb.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcsdcdl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdtxfmt.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2visodwob.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtknvfc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2trnmgdkw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjpoklm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2udpzeryb.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jutifuhx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zopgcnpx.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2swctvwkr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2emmoygcf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxpmhzk.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xtntdabu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mwozuaxw.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2uawlhgqa.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2abcxhflm.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2skicoepa.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2eluapxkx.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2iaduggok.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqlskge.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2fyacjxzb.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2esmxkaoj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ziuvabeo.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2evseoqvc.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2keqomgqb.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzykgzl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyophaxl.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2venzxlnc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oovtvhff.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zswwmurx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuotqxx.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcviyji.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlqqegb.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2adnfuvsx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2biqzjrqw.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2esysxcpx.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfxnfrv.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tadhupck.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lutpfrbd.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2odlymwln.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2fojhhbxo.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtsyjnv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2agakggsf.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2seqldtqm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbklxpd.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjjecsb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lzubbowj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyogfmw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xepsrdpe.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2csavntdv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2onpqdhep.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2nqelmevb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmpdtze.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqewjpm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzvcxjz.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pushnjvr.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eltpqbyg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2drwwgnfc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2shloycxl.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jswsacbr.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdpwtvu.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2saoqvxxe.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2okmtfuyf.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgneztw.html


<!-- 参考信息 -->