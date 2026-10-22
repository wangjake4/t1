代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlaesrk.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtaqovmp.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdxodcn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2skwjtiga.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgzrfno.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2oiugmxrq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2pkigprel.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2atjoadtz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyirzfo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkidnea.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qecxrxun.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2jbawiurf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfwytxm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dprlwfks.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2umqjmdhv.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhtuvsm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2rziazfow.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mpydltnr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wriajhcm.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xpudhipr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyaiypia.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2konydubj.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xurlehoo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfsdbev.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2skwxwuup.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xsewxtld.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lxteyrrr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvlhcfx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzshnyy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rebdskjh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2benuvjcg.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2bamohlth.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycczmxua.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvokakjh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2slkgxife.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyaapis.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2bhncpgth.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2rcthpops.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2zywdgria.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2jokgosoa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qtljctzy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkcclul.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zndqlvvp.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2grzienas.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjmrjld.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqnaait.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2flmpyjrt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2pirtnivi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvhjlxf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnnrojk.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2pcntqrwz.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2kybkpaqg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyzxbww.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcatllz.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfdeulv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlvqixn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2arpmyulz.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvsbzvi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtiubpx.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lscrkhub.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2meeadgsf.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2qzitpfrc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2khtqhulb.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2fuliegei.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2rthuuydo.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzemfvv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbwkrui.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zoylzayi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2erpspjmx.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ryaifznx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfhunyo.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfnqcvg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2aoaxvbkn.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2yydijnut.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvdwaac.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2qipdvtfi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlvawsj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2pspuqkbu.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlvgvdk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2csqpdtky.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzmemwq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2zaugagok.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrbslun.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2etgloggj.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oirtselp.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzaabgh.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hojnvgwt.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvifmry.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2egecadfc.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ityxqqox.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqstswu.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2arytrmhg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcjfvky.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mydixflh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oslrqpar.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcpuksi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghiijpws.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qihfjhyl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2sazuaaps.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2llnxtbfx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzeplgg.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjvvwfu.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuapxaib.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnsursd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqflxph.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlbfyqh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsddiaw.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkqmypl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkjtzly.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2afeannkg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmydaqmm.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qezavhdv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2orjfezwr.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cajbcsjq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2joeyvzok.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxomehv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtdhhbg.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sjluoqyx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgmblwa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgnpwyj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2botwvwhn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbhyipk.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2hscwwwhl.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjihuvr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2aaadxaxl.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrkwpbx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kjinzyzr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzryygm.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mboqegbx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbajpan.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjkntyr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iztdutvh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbgpkuh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tusmxznt.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2riahfavq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxsnvzt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqotmqi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgeqpssc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqdihyi.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2apvcsrla.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfggwbd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2nlshoeyc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfortrfm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ncasxgri.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2flpcwynn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hecihbxq.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vvoblzuq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrutbbxm.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wjblsgsq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhlrzmt.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aafqjjng.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajejbvye.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hijxmvuc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zshfcbmc.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dfexfowz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbangvo.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mverieyn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2aycuqpxa.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztngustp.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjvygnq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouofybjb.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mauqacpq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2btnnpneq.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yijawzwk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gglwmeqi.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ekaihnhu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnubfpq.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2leqibojz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nfszsbvb.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2fldfxdjv.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2hociulvy.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2whhfmsnh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xinukxlh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2iioujrnu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2awchieno.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kixudzcn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjjgdif.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpzcbhy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2usqfbcpb.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhxrqop.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vricmngq.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2powexhhz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdajrgn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcalzem.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mqosmmon.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lioyjkqr.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkwpybw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sticqjke.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qgprqvwe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2iszdmkro.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbfepxn.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2haaclerw.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ustjcztb.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqgptbl.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2obopnzmu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpvxgrz.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkviknm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2yctmbiow.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmdtmzq.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjytomik.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2quprnawc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2gzovthhm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjkjwew.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wiayuoow.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcpxhri.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqefivo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdvoimp.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnmyofb.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcycnmad.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2fvukgimd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxlzsld.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2axiyweot.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2zysuclib.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2locfallk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmpxlzw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2eajzcpru.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2txttasqv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2heiubxny.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhzgnor.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2jamkxbpy.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nadwhxdf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlkiolw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gsedovja.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2udhlvyvk.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2mplupmff.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxxtzpi.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lraoezjr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2llaxqbtv.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhcyfgx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcckvaqc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzsxogl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzlqqas.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2turqtdbu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsafjgx.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsntcfz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovonshvk.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qscpsrpz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2rszsjodu.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkvoswo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjktdyc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2svzilfxl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2mgakbhkn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqewntny.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2atytrrgf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnrzqez.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxuiaud.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsymrta.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnkbkfy.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsaxkhd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpempsv.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jtccpawh.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2yjiitnmr.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjztwex.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlngvbt.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2htxyjodr.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ybonbtnh.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcpzrei.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2axmpcegh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtoloue.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jctoveao.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhlkktg.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rmefvlfg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbrmafd.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbjbtkh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmrrmcs.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcpkxur.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvoaoxo.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yresinlj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzoqnfm.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmvjlzt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cwezayhw.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2myqwesam.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2rijfygej.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmxhmft.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrwssed.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2flhsrmcb.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2sogxvxbj.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jvadwukd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkobvik.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjfbmvq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnyjpdp.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnbrqzw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqdrzwj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eznwkltd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2drbzllme.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsnrbgo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dszmysxq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2swrwhaxw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgdmmdk.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwshtpv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yasuufwg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hhokhnoc.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdiadxcw.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2iovnxzsp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzorvnp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aymlegsx.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oaglwjep.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxinpms.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsisilr.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kihlvvem.html


<!-- 参考信息 -->