代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2khclpygi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nscdlswc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wiugokng.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fnldjjgp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2iegsajem.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnwgawm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ipairfjq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2pjopamsp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2abhaxhvd.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlifndez.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqyjubf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyfcrbx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrundgc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lmujtlnu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2wakltrll.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2snpwqexs.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcorchh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2aptiuoos.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyhceon.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2bigiqsup.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhmjzem.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvyaqfe.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2cisvdzck.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ayozpmbs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2frzkhtcj.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cvoqwlmh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkgnynt.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwzcqga.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2vshyfyln.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxuxdfv.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zukjkyqt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfezwfx.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2voidlylo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyccusj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kjesgbah.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oliyfevr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2mknhxvwg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxtnqat.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjuqwaz.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2uqogemrg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rauqhavs.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtuvqxg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxcroaj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrtlxfm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2igycudrz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmpnbcy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2shwymivv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfticng.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdnlvgz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2dnayggzo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmibcsa.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvambvc.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2qxoephda.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hurtqpzb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2plqqxjak.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjovbfl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2zytvaxnn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmemlkhx.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqqlnyn.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyklwwf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqotevb.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2axlfucrc.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkgncjr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgxjcjv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qantprhg.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwcmlmw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2majbbdup.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtqkbds.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnrwiqs.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2apkflbyu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyiaecf.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2xahvpami.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntspbwqj.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2kdefjthd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2voikvono.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ztztcljx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzfjovf.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdhwarg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2waapmgof.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtnjllh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hltzgmgb.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpilorr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2uvyefhyt.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkjhtgg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfocpmw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoyrwjo.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyvukek.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zklqflzt.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2tavcabjr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuhrpbh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyroexpm.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcfwoye.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2stvsatde.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjdpkyo.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjfdnhj.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2djtprgqz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yggluvfz.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxjykak.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpgqyhd.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsavpwx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfyysbr.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vszytvgm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dztxltyl.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wyselmod.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxozlzfz.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxkljcu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2fghgctmy.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbuyhkh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkvsuth.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqkhmhn.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfjzixq.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzgkwsd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjdetoa.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2yespamfn.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tthxwyak.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkqjyrj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2umvnjrip.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ozylqojk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzajsyn.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jkoskzap.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2owvysnvb.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kddjfyyb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2trwkqzre.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2thhlroxl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2htpbqytq.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2msahhsvs.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmentbtj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmdeurs.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lgggegbb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2xegjoxbz.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyttylf.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ddugntvf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2yondullf.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2akzrsfyl.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnramzb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuswagaf.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2urcyrpmi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zurvackv.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfrhusj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhryhql.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpgumge.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdidcwmq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjqnclw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2pryanzdt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrfzsye.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxplnlwg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjziopge.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fxddvcpt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdugynn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkaouwd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqxdbry.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcbgfeu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2tpycamyw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsybmeoq.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cdefycyj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlastye.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfszfum.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wotpjnwh.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iookqfbc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ooaivpqm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2juuisiya.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdrjyza.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2moyahiox.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2izsuqxzz.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmclycw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltejgntq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsacoihw.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjhfpzt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxskkil.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2aujsayqd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdbkqyn.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yojclast.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxklpixn.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmkiosw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgkkqqg.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgycgia.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ssljnfaj.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkbykxj.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuikztlr.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ullsehmi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkelaufv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zmeylftd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcdzpje.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdbqiwd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uidjjdfp.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ahekujll.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddotiuzc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzckems.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdtkgqp.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2laqoclqp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2cxiwhcer.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkuynfp.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqhpmwv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyeoxyfj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2lerumxwk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jorzhidv.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xccynouh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnlevcu.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwmjdvx.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjwbbwy.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfpmodw.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvnutyb.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kryzmixl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2nozxfoad.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcebhit.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrapywgc.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2gqngpjfi.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnqzobd.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qusukfof.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzztrxk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmuqziy.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2yymjdhdf.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtqmimh.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmohqfz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrymrus.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2shkfuncf.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcapeqv.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2cubjomoi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxfvnkr.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jcytfcin.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2prhrnqxm.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsobhcr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsktdhi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyzdkgr.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtirser.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2secljjpx.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2njyvmojk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2idzxtbjf.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqrwcgw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2oplcplie.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkdvplv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2cojjuovx.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvqpsta.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdofwsg.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ywepvicp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oemqotzp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfvxnci.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuamyvf.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnpvndv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2klxsuwzi.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxltxkb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwiigqcz.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2vczeufwb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzkvgda.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxynxid.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2fumvfgzy.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqoozxf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2viczrpid.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhxngeu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvhezlk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxkbikc.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkcvzvm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpicknh.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgolvks.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhizvti.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyugkzx.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfstvzn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2glwmpzxu.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2yzevzlbv.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqabdec.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2agxiwzlr.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2bujtfmvn.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qvokjmxt.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2upxlisuh.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmckoog.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuuglke.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2aythlsuy.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kosowdvu.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfepvvwv.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ykakokqs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvnexys.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrpdwhl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aahqervc.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2btnzyqod.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wfniggzn.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgpoupv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqhzhjd.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqebztg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2focacyfd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdoktwr.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfaysfo.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqacjtv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjncqwyu.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnaqfldz.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2apwrbycd.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2krymfvxf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgrshwp.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2krsnxvzz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpkdpzw.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgvsttx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nuumzndg.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2asjpluki.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bgftwwcm.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vahywqbz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ivywkbks.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrvqoqe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gemjpech.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xokwqtqo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2taoackfv.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tawgxrei.html


<!-- 参考信息 -->