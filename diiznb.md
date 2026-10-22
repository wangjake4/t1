代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2uardwdcp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcezvkx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpoecul.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hrczzgzy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2irrsxawu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2asgqfuuw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2cvuumdys.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2qetdktci.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyckevy.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2mecnkkvm.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxjqmgs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2snihftay.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmdeeuo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mirnakwx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2dsauetsp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmhlvhr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcaqnqoh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2vjogxfzr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sifhdvmt.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2voskojml.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2mirckied.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebywwixj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2eitllgqd.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2opsagyap.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ughcndez.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbplvpq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yaeqcifo.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2siyeisrt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2yijrebiv.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnivlhqd.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2eouhoqkk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2hvazgqyn.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uzirnpcj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcpjcum.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmicmns.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrovuui.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2jozkebzh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwgrorg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rjebazsw.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2izpxvtzl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmmdohm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwkuink.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsqhoum.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpleppk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmsppef.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2tyijemke.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwaxnqh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ddulqdyk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2drqhnosq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2fztkixlz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2igmfcuty.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnlenbc.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqmbcda.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjswpbs.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qesrxcqb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdsdobc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwgoqrw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlkwdbd.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2yoicjntk.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjyadgq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xvykrfwj.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2gasxuitk.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2khmukbow.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2idhzoidk.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwfaicm.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpblcct.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tspzvbec.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2duthljpi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2obmfabur.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfryqir.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbumhnn.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwekcfg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2oitflgja.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhoqxxa.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgysvcn.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nghhndql.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfcnbnx.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2evolmkol.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2imcwginp.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nwabrjra.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvxdzbs.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvcbinu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tsojcjeu.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2trfmgjrh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ogredlcd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmlucjz.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnzpcyt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrqaomf.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2yawjlzdq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2wykfmzej.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2efsodimy.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdbdzmz.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aweoigmp.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jurouaff.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhvcrff.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2okzxovde.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wudkgwyu.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vztkomxn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2jsoyaslp.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wziixamb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2wormvqgu.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrapmqm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gridtftn.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zszcrqtw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vimvfhmk.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bnutcecy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2jglkbezv.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2qgybhsmz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuyhyan.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqlommi.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eszwrblg.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bxamvtpk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2bucdrqhh.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vswosiqj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnuwkvh.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2klrtlgwn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjwvozh.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwlycus.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmklsur.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zacrvkho.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyoiqifw.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rttfhyaq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmkzsyr.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnqufkc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2diixdwtx.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhonbjk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfrdmby.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlimgfz.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2syibngrk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyoszao.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2yeotmaca.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2foathcwv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2grcsyncq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzscyeat.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2znebrrej.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsddtqi.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xebvkrai.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeockrwu.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqagceg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqoqaafi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvginkn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrkqfxi.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgittjf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2izkpggrn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlwapqo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wlewaayv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2damiigbe.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xshxcruf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2gykcxkbc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2bubxmega.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fshkhnrj.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fikmyjct.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbhmvke.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqubjdjs.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpyhdmf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrxozpf.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cicdakze.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2yovieaob.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpgtdek.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2uepuripl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtfgqai.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2icmlnldv.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2laaimcly.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhapkgkm.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2blfznyky.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2mewrwhcs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2svensnlk.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2farlahgp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcxtvdy.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lnssnuba.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nosfsdqc.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2scipkblm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdesqek.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtcxqio.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzzetik.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyvflcx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvzfwwu.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2gewprztn.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrybkact.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zprjawzf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2elfnwjzl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvmeyeg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgghfldv.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyqaejj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpczjwt.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpdlfmo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nekpghlm.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2amqvuldf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mylddlhu.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrppumf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2vgymzzmi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsnltqb.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nagbbnei.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rolbfkea.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2acsonghl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdoslsc.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ksylutbu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbupqfw.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2meqqqxmj.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrhvmcb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hzokfupy.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2qihrqljy.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwzrakr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxddniwp.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2fusevaxz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbzamnn.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdjhxav.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhfcbmo.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2suuupuwn.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtroslv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjqkunu.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhenxiu.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvwbdbh.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxuadlx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2vqddmqkz.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iiausglq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zncdxezy.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2bxowzrae.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2flcjrhmn.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuqqmmi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2jerrydmf.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfrfwfc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nisiugky.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzmcibd.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrgmchp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwtxlxh.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkbdwqu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2axaprhlh.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2boxkodcs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2hwefikst.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmetwyr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwvbmxu.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbclbcs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2autjrspc.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtylsvy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqngwmrv.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwulidy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bskiehgh.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2quapgjgv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlovaisb.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsgztiy.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhcxlgq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2rpoxzwxp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtwypdy.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlaiqhq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2aafvranj.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ufapxptx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyvxccv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfwxaxl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2lokbsdcc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mglqcpgw.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnvkpgb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rokfniys.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2wfowkwyi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2liyzvtkz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tymjggaq.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyohaqw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xbiusrgv.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2wzebinqc.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtvvrwn.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2eezlcmpt.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2gdywvole.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fctudjsy.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ykruiaox.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsannrf.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jmttlrrp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2lucaejgk.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcvumzy.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqzuodt.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2givqrvgu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnqmhzz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnmajwl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2czpaanzp.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zismsenj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lulofaix.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2orlkzuuv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbplizc.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbqkbym.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yjguusme.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qhoccgbi.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2znjnuusx.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceiaupuu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwebjwy.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vidkpetb.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2mycuhiik.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2czaaigle.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmwwkat.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xtondvbu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2psxzphyt.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2rlujqcja.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iezhehyk.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2icvhvvyo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2khrgljgf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qoofcllv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2foxlmszi.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbgppjk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjekzwc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyhzpwf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcckyww.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmhvxgw.html


<!-- 参考信息 -->