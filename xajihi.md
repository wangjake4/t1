代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrlhzcu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2koykwbyz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2aaywzhsi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfmudkg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2wihoxuge.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuxwslu.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tumlsyvs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyelixc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcgouvh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2auemahkq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfgdfpo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2avrbvbgn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zequifkf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxhpafk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyfxtum.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2rkojsmwa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2akmkojll.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2plwsdahe.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2huvqvzmt.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kykwlwdw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ogiwflhx.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsvendi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rygitqdj.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xigvweie.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmrzwdq.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2varnxkfw.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ithxyava.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2igmufuqo.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2glcvslpk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzmfofb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhzllke.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ushacttg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ugksynre.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmpgyfd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjltgik.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2djiaukzo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2epmptglm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwvejwl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2unzrpvre.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dydbbjis.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2skzznkoe.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2mlelcyfo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcbxxfu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2apqnzgxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sixgwgxu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2okxhehwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kymsplzm.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgfoetw.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2vszjgmwf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjurjcn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2abxfecqj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqbcluv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2vcebajkj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmmkekt.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2foqmegfl.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxcptku.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2oztqvfze.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xfztqmix.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2xocxpjxy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkchctc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkeycve.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2zogyyeyb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzcsred.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlwjugg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2skfnnrzh.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjnhwkf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebceldus.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjcckrp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2psopaxer.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpsjanq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqutcrz.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cxstzmur.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyqzfdg.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2msbobgjk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2spplfxnx.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2keduoafq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcersob.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2htgwddgr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxrjgza.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2xpiksjhz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2jndaxhyv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2vokugota.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2kygzwfvz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2atotvkiy.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsskaql.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2orhcpkfa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtpgeds.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2puranujn.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dozabxik.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hscscdss.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwrvtvx.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ickfmhzy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctolhltp.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2biowkuvh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2rypgzbke.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jmruvctj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxcqpla.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbaazjr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjuotnd.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyctulb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kctrghow.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2civlttkq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2efqeccer.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2kkicrgrd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkifoqxx.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jrliczxj.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2azjfljks.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2uodkemfu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2bpehwlff.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2whkjvdcr.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eaahfpuw.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bsapaexz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2swlusnmf.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjrweuh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvcjvqc.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzuwvxg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2erwkzgcu.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2daakskuu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tljkvlti.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rprqajhd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcbvbbu.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2djgafyba.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2njrcbjwm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2nypcqgiy.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2swbeexcf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmywxqmx.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2testkkig.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2iujwijkj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnkymjt.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rngtqtuh.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iygwfpoa.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnnxqpg.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjuujyo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsdlgla.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxrxzzi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrqrvkc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtuytey.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtkfgik.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mutdnbfh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2dtppwykr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdcydvu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbvpnpw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2yttlowug.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mydiftfu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2uqstlsvm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2divopytw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyeptin.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgmlytn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2srfyszqw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxdizdw.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzaniaa.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2naotthtk.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpfvcuk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gflcwelm.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xouzzvxc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2goueagro.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzpxstr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpwofij.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnemrgx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhlhivk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gghrneza.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxyzhhp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfegcjwi.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrvifbh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnljeyd.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjtdnfm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zipxokcg.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2adrowneg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbblllc.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrchyvd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfngjwnz.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ptedsubs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2luyntdbc.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkeeqai.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqqmgul.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkkyimd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lskynrof.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jixoirpg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfldflw.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuilxne.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2funwqgjf.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2eqewqrsa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpfgyqs.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcezxfo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmxfjrc.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkkhlnu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqtfobq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zblsawlm.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqflrsh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqmrbeq.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2drrgsizi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jagfjkpu.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbqvybh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2bekkydjj.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sobjlmav.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ophggncg.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yyaabhlg.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wllmxdru.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsloiva.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2djoiyznf.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2wimdbivp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2bntnipts.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2rplnlsfx.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2usszpuoo.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrbbnya.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnveqyx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2aiicqatc.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzzbnmy.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxylvlp.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2erqvquui.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2zgaeegok.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hokirguo.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzaxsbwa.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2szbofmfg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrjkpuf.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nubeksfr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuehwto.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2eszfmxlk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2spaevocg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrikyey.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyyzoew.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvbzniw.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdjktdx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2annuwykc.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yxknqopx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbzptds.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vnemebbo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2imjflhai.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2rygokhkb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2isavpipd.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dktojsdq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2psfaxwan.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvljisa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vegkioaw.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfbuerk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfkbxur.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2uezxmgkk.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuciihly.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2yzklfpgo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2scpnxcfm.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbodfjr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgwepcc.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdltfdf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdqokzh.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzoedbkz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2bydbbips.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2phbjkeip.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbbspua.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2clonulnu.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnjvqqn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2prxwykqz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tepnzfzu.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbcospy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xsghoold.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2disibeav.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2exblpidu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgryswd.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2imzjqxob.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jizxfzrx.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kitcizbd.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2myntaduc.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxazpipx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2jolmtrwg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvwnkjf.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2winvtcmz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsfgnre.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blspkcaw.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sleibtjt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdfreho.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hexqyylv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ssuuekyo.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfzyoyw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sifenalo.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrqsehf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2katvymrw.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdpiicx.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvhwfmp.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2irfieewz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cutdnueb.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wojluxsj.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhlwalx.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuvlglk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2syqcgplg.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pogdjhvo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqxbjde.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqvhivj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnpausq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnxysqu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2inzvnlxu.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aecairqx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qctglxty.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2zylozzws.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfrrjko.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrpnenl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fsowyiag.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uaharwlu.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qajmhklr.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsewpkc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjuovhnm.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nvomlsmh.html


<!-- 参考信息 -->