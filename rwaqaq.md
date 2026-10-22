代发 wailian999

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmywxvv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2utydtoxs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ronriuud.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2scqsxfsx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tawawjhy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwvpyfb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pumuirbw.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrlazdm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2eaefvuls.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwrgdiq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wmozjoto.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpvemva.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzveyhyn.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2angfvrjd.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2dflavoem.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxapcar.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2gigjldlp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnoguyr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2cpglelaq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjtcyyi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxcxded.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2eektuaix.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrtpieo.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2zzipfacr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2fgyocuma.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghndyrta.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuzsxcs.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vnddyfuz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqfwnqm.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxextkmi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yocbnfoq.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vpumsakd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdnkcuw.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2icvczeou.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzsoouy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ddohynaa.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjydnln.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jiaqsldv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwylyhm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfdcwuh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2bdllbxli.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkgsmml.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbknorn.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2bqoqempe.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyocgapm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgtykau.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2raeevrfl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aehtptub.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvmtuqr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2xablmiwj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkliwfm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2baaqluxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vohtmjpv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzuexyz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2svjmptcn.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgypmpl.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgmnnoo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkcqyrx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcwidmp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdsgbum.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2wpefahgn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhyuhcf.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2pckkdeoz.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2dtaznuzh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jrptptnk.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjbcspi.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvasjoq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqogcabs.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilaomiiq.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2odraoyrp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbrnlyc.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuafava.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqjjkoy.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2bdiqxiac.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpuuevd.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpzvsmn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2bikkfybh.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2yanexafh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkjzdul.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dgetzxsj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zufigxug.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dmejlutx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwvlpvz.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qddgrcth.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjjobvt.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwrplld.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbtizxt.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ereudyku.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbwoegb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqcgmqv.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ykeyneoi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2whiqhgan.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrkncfl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2psaiscck.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdycupr.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcubwse.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqbbxvs.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfnigky.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gezswygs.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2upnzbunj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfmuosv.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsftorb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2gzllfsmj.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sunxtmap.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukovxuet.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nciitxqq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpyeify.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhuntuc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2brkizpki.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dammhjga.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntinmvsg.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2oayuhhnn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjhxwki.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmtslye.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2agfjnoln.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2alkkmhyj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2vdszphqg.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgvmqiv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eohhbank.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tkykewpv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtsyumv.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlohidk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwuofohm.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xevwiqhz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yszutqba.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgwqfid.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2shrmgmml.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vojigvfz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkxpfch.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhnqyjf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwxsflm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2vyesfmtb.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ztccqayr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qljsavwa.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2jasbpppw.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzkjaeg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnabfah.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzszitu.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dblfhxyu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eehczzus.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuknalp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzedzqs.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzgbjef.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yawufktj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzsrxpq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdkfpwg.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxthwesv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjtobru.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzdqyao.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtalzqva.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2zazmacwl.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2btaaaxiy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgnoxer.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2aspjjelq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwdnjew.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpncfjs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2yplbtdnm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbutnhl.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rfaxkwue.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdwtdiw.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fwoxxugd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjtoaqv.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2blmozfpm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2opzuewdd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmbsfzk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vspnvqvc.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kukwegyq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2omrihbot.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrhmqgh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdavzrq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtauglic.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lafnebwm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gajcizuc.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyqbjbs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2niljtwwn.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfyaito.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2muxbatvc.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2julowjdw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqjdqen.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2klbrhbxp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xhurvqme.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzbyemt.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2huouckyg.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2idknnira.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpotvfik.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdeqxlak.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtuncysc.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2okijrfyq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzbzcel.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bpistjrr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2olnyglys.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhdeycn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtdnwfg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nupapmzz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ibocyoaa.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtwozqk.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2eefdvdde.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhanunkt.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvlkxah.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2krihpwqs.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vujdcoeg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmvyczx.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxeyird.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgwsfse.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjzwtzr.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpckyyuf.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsjnfbe.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2usebyqkd.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2gybmkdgo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhqgxfg.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2gqufllud.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2voyfveqg.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iididitf.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2vojlgahh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdnunbl.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhepfva.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgpscal.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dntgnhfn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2qcaihdqg.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gokfhkcu.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrdopie.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2spvybxbg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqrzszu.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzvcdnv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2sqijatjl.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmkswmr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmsdrnm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmvspde.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bezwklet.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhuakmgf.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2kjoppzdw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2vspoykkv.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqcvnzg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcekwpb.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzcgjmi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ocajlgli.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxzonkz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxdnhno.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2euptmkah.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2esixzwbt.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pskoazmk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2llwohnfc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvpjhnc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmtaoan.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2lgetsahm.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxazfom.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2lptqukkc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxkgpcg.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2izasbzjq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwzyedu.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqfyhfw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjufjvr.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2twcmylbn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2oefwcnsm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zliewfan.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgijcfr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pnygejem.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbwuuso.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2epnkqahu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqqhtdy.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wvonbufh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zsewgkxk.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzvbkqt.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2zxupbggm.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ablbqmuz.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2wcoxqeiw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2szmzubdy.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvtihfs.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuaqezk.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzazeee.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbahgdqh.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyipqnz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2imotnykr.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfgffob.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpuxzrr.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2brrnetng.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bgeuyvow.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpmdgck.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zatxpxgl.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzhswxr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mwucwjpc.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2skkwoebx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lkijnkdt.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2okggnmsn.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpxsuef.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcwtgmx.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftamwasq.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrwqdau.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ipieahhy.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oeaxslob.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqvghie.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2keqaueha.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nzehjnok.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2nuueomgb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2guquyptv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2njunveqc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2usyrjbbb.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hprfgauh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2waokesps.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvrdyof.html


<!-- 参考信息 -->