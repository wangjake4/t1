代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbbclhh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqabqlf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fewpljxx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dxynpekk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnwoyfo.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtzazdi.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2erapkjno.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jckrgeuh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbswbaw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kaspvjeb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2huigvnby.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvxkjgd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfbrdqa.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjgpvnu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlpzotu.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2fepykbth.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2tnilicny.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xiidjter.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlaikln.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpuabso.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjitmwu.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfgmzfr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uemtizbf.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vearmzlp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2xupxbcdr.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbbidih.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2uucvuquo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkgyrim.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnmjjoy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhnibpo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kznhwvis.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksllnycc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgmbrda.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkojzqb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmujirm.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2vfckdjta.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjinbfig.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgiqayz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2obyhpzze.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqaiabl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2lthqiqtg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2jiddwdmz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkyyoywi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2nuojgkqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnzgkvz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcuptqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvnquhe.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2iunhxyzm.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwyyvan.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nadsyixh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2isakryqm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvhkkqi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2kunqjzcb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldutgeic.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhvpqop.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrcydtq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vimxbndm.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qebvuluf.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2nfveexbq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvofjatf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdabdiwn.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnvhvlo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwctchxm.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lprirzsx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrayztiq.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzappwn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfsorcd.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmaxeyw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2abphkpzo.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbtflzo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uewffuun.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kixcqtsx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gozykrao.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2exnwvejm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tirnmmsg.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdnsbxu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnndnck.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuztkny.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhweglr.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ijchagvq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlfviqd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjxecmq.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2aahyngvp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2iunyluil.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2wipjsczg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2seescbev.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2luaudpir.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlwamfu.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hywlakar.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzvcves.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2geqophar.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oaudfurp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtybpnk.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrhgcpw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2gefqomdk.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cqeepckv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvlpzwd.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjvxrep.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgjorrg.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2htzkpasl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfvuint.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yuygxaiw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2imrygphh.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtgedzz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyxosnb.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bphcwxki.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzoipnk.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpjaoql.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2afmcftms.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdssndul.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtwopjj.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtfkocb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjipjwj.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2olxkhvlp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxidlcg.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgklhzu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmotppqn.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ituinrlf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvqmmsk.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsficvw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2skynndej.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqshdlu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lywvtbey.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqhrxse.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hrljyuov.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2eirymnwe.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2dmprvtzw.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsitdig.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2oazvinyz.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uowdltst.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmiuhbt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2evvwlvce.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sggxpnos.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2njalalmi.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2socjdutd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dylipyli.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfldxvid.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qopqcxjz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2obzsxvki.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2nreuqvri.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2shrazsry.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjsabnu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2afimxokj.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aoznzyeo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmwejtq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2wsaaxgms.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2khkdrnnb.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjhkyun.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrhwmay.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2llruhadz.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jupcjlgt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkquftfx.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yonfsetj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwaqjyo.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ndainfac.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfjwxpx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmwshdq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjedbub.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ifthketj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltttyzxe.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlvwxof.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2peysllgc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlymfokt.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnuxaxb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmimgaqt.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2elipwozk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ranwggkm.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvktvef.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zptxnhts.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2yevuxmmd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gubpvzoi.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bclktqhf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvmmwpc.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2eoatqbol.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnynysuq.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kftovhvo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nddujthp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyxiswy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqidsti.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbahgfk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uumjldwl.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ijuivvbv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2avsszvnb.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2fapjrbie.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2peapioks.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkuxcbu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxltojf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzncghz.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlqmpha.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvimxzr.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2iszwsocu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjdwgaf.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyecyjj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvhjufd.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxqmquj.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcjdrcz.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uvolxweu.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkzbbxd.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrakiwu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnyyhrh.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnqypcw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlxzffj.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyzgrqh.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmghwwzw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sscgdbgx.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzhhavj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcbvffp.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtrficg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhquyhi.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnmxhfv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2tozhbsjm.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jdarmlxa.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2obhrfgrv.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2qlamdlxp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpjjmaq.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgdmdyg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2jfweuqsu.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcdwegy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzlytml.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhwlhvh.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2uzypfiwg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlesmvo.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcwqows.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyacduc.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2unhxevxu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhztydc.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ldinccqo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2sehzkaey.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qlltusso.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvngeeym.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vvszbopc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzobfovp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kygyfqzq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygydavyh.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jyiaanot.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdcbfno.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfiumgj.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yanrgggs.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnoggzo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2uejylhwa.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wkiavmxq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ioulailn.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2siaqpqiv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrkyiat.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2moexuown.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2evcyqlea.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qecnsvyt.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yilpexja.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2myoaharz.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2cyutnfbe.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fohquxsc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qufqqhwo.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzzrgnv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpleaya.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpajeyd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmfwbom.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvolhwm.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxmhaxh.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2svqtpaeu.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2crbhevms.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jrghvfoy.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxosswdr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2dabafvmq.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ooplllwu.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2avmrrbrm.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2heycdjvf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqeqjrp.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdzfnxh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdsqixp.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyyqrxs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbrmbda.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rycjtnoh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2emrkdodn.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqsktnv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwgsavf.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwveyqj.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2snfypxwv.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwhrzik.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvioehrj.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qscwsbem.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvdleni.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qqghqgod.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mzirkigz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxqqrxy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhgyuow.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wchkcmhw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nffmbysg.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuvoyfh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2chvqvzzv.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzlhszs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcewwkz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2yosejhxb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgwizjv.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nkteqcdd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsrdmmz.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmotwiq.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2utdezfkj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2muuvpjna.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnvvpmt.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjxmzdk.html


<!-- 参考信息 -->