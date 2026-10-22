代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjddlhau.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2cegktbzb.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpiokny.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2iiisqbgv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvfvqhy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzrajdj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2lomfrhap.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdcwzfu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxilxqp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ooomjtff.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2szvsudgs.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvjdbqk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2pznklchq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjiokknq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxbkqto.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkndrflo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsyzxyy.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zgggopkj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nalphufy.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvciamae.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwllpfp.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymuzcvjf.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ueczijpg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ysszsplj.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mevplkhu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gnastqdh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kgonumlj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2riszrzmv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2exhunbaq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hfyvfzqv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ksscgxcr.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwhoehb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2oosbguyr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhfloev.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgpvrys.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvkkxjg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xpljboqd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmdichp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsqaigj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrddzzu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xubhlucn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqywexjd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcwwfhk.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2iichowww.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2nthwxhul.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2olxovybd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqxikqr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2flkbykxn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgpwjaq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2fesujxma.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrhtrde.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlskvsr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jlptoult.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2daegyohp.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyxwbvr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwkrikg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjsycnx.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlrcxni.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzidtct.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bumvgskz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiunrycq.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2krsksfym.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzobzazg.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrnxpmb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpavvfyz.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2skitlvvg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzdgrku.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2umektpbq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlpcmct.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lmexobnh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2eecaaesx.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvkbnjn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtiuqso.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2lrckyoeg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jujerxyt.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2bdletdnp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2smjluoxs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2meggwhwi.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2keugfbqx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbmpbpa.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzzfmhi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2qavopabu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2huculrrv.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwpgdol.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmitxim.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lunuxuma.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrpcgte.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gkievjgh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrrinmb.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2evyfpesi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkgislg.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwpecly.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnuhuxp.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2didcmkvd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdaslijc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zqffcydx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbrjpxn.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tahkrcmn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2hverskgd.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqodwuc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlbvjlj.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2uksxpybu.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdautvqf.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xummcalb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdbrnlf.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gmanjjzq.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cakcshyr.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2nreemodq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fepfeanj.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhutomm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmcnbhy.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mayalxhk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2koxgdtdi.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqoshqi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2uffzcjdr.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yadvldby.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmdayhk.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nalwyptp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsokjtqy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2kyinwcxg.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bniazqsi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkmocnc.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2frjrsxcm.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkbmutt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgyenqa.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2onascmqm.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvfttos.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2agoneraj.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2osxoemeb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdohllk.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2foylhxhh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpewloo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2izuboxib.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sslagdvh.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2adtdgsov.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2pghvbdmh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmrufuj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwcyfqm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdnjmgu.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bbutjmlt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2klypyitj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2hbguoivs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uspvqtrs.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbytpmd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrzxpyn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnotfgyn.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bihmsuxh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2okjdjzcx.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2acrimsiy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcjksve.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrlqcyr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2iylnxrjz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ryturylb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfadeebg.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vitozule.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsffufm.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2afaoalux.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2qytagnkz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmvlmac.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2aecjdwdb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2unypggmi.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjimjzm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ejciuwtz.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ropuuywk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2abpxtqbv.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2wlabhmrh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpagyccs.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2izddstnb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fucqodjx.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2entilovu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtopgcv.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuelvps.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrirjqbk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jydsixnm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpizbfq.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnjotqy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vctcecqg.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2psvbfarj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyolibgc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2kriiqmpz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qffdmedj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2raxeaxnk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2oxadooko.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjzebli.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kugizhlg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zavhmkye.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2vzphnsbq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvronzk.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwsveyg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2eyntnxey.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgnchex.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2paxgwhvj.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bedljqlv.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2odjzwdcs.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2grgueyql.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2avosvppv.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwpceio.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2nczipxuw.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2egcetzpr.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbqpmnn.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvebxyg.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvpxmbc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwpvvhs.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvvxbhx.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdskffhz.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dgunfqch.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzbvcar.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdtrgky.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xevnchpx.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2kuolswro.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcgaoxe.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nomwiaho.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2axqcrvkt.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kapvqcpo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2laaodoka.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2pbaepbdb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2znnqqokx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2fozvowru.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2epohfwoc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2xngdsoxv.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdzoxab.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2dyksrcac.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zwboagxm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2btsqdksi.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrhjfly.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2feuxhfdt.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iveodhqi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmjytak.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hngcyteb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbanlzag.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvqpcue.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2peupkcjc.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2vanrlkjw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbfglvt.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfxssib.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gofxkqis.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhuobvl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnzlrmg.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vsiazzoo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcmbbxh.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvxajba.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvtuqwv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2reevgbsp.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrjbfay.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxayxig.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxgnrot.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lswwdydw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmcvyre.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgessdk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eblvwdia.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkzknmg.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2oghubkvo.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zisyiivv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vuoahxfp.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxefxdiy.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkgugov.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2mxieboup.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2spjldapa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2irzlvpyh.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwhfead.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjllsitw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtxdgvj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hudkuvzh.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjmwdkq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcpwnla.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nohchedi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ytiwpbcw.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrhlryg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgkuihk.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sutbrrsj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sorzpbtm.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2brfpwuqv.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhfffea.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhajlxq.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyyjzus.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2deogfwvu.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkzhdzq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnzulhu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2banrpioa.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2imxqszmw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpodxqf.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2akrnsngj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ltoliqlx.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sekquhlp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aiepqmfa.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtgfymm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bgidsayw.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrcshnk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ockxzjpc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2deckhblx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xivzxqrw.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2apkqtgtu.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2itxikkbe.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcmrqpl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgsxvjj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2irmrmkvg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zferqkrs.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gufyuxii.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkxnjiw.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2stossvdd.html


<!-- 参考信息 -->