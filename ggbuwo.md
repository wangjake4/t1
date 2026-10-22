代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgrcadn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsdcinq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2iirvkndx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2znbpvjge.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2grsmjwtv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2dahfxpwq.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vbijhxdy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnljfjn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwqtvwf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ampygynp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsqrbsx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuiuwel.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpbrujs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qblkvolu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2eyivbbgr.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tiginegc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmkhihk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrbdxcx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2csamkklt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ghymumny.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2eatysmnk.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvawyda.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbhdhjv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xicflsjd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfpiusj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2svzumnsg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdvqjvo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2aktyfiqp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyygbwd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvgwxoh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dggxldbl.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2oaeftxcv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmezdhq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fysqjuwu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsriwfo.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnhvpjy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2mygxngre.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2phwswzge.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuyzpbp.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cwebuzxn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuuskkgv.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zegowsgc.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rknnjnzf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdcldgl.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zqraykoq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbodgkk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nlluimao.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzvdaai.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2vayzjhza.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcqonum.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwshyrp.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2asnsynpi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2coqdaqnl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxhukqa.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2abkpprmt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zotzgsib.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2aftkqwxf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2zdaiupul.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2bryoxmdr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2deflfnti.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtrlrzj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ifybuyry.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wcaieheh.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2uilokdpr.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlwvtob.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjldmwx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2epdxzmpt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2nntoxcve.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2zsggmcej.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyfhrlb.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2vuaotldl.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsddirr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qckukhmw.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtxpwmd.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcovgpf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2xheruihw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzfituo.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2oqauwqit.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmvcwby.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcowitd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqjvwzu.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2jwiwtwmz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cclyzarx.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2vwursuhw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmcjlkg.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkwjvmg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkzpkig.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yffogout.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzspmoog.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvhlqbf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuueqziw.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fefrtlon.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2texulyzb.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2scxfvxbl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kukjzrll.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2gktrtiuy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2qeythzch.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrkjvcn.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrkdzfz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfcbwuh.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2vaasutiy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhdzbgh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejednrsx.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmokfpj.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcoirkin.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ourcczhr.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdwrfqu.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzmznra.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcipfugs.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jxavlcos.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgaeqsb.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxzwukk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2vryffieg.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sogxqcqo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvokrtfs.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wrasyxtb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2idjrqbvr.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qlciveal.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2bocmpyqg.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2uslgbeyc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2vokkvorj.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2iiztbwgi.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlgtpde.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtcwjfj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2tujnwmjo.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfsoauv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqcmogr.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kviclavt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xspoggee.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2osqdbicl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sktnotoh.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2etffhlkg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrofozn.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2foddfsdf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2udmirdxp.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eunxunqh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlhpgoi.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfjvjdc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfroxan.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpxqhrh.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpuogrc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qupbnvog.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2pahfftpy.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2zcklaozv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2sttfofan.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzhepfp.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2orweybry.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvdovyh.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdfjggu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyenurhm.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pczggocb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2youncehz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcohonla.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxzxgdx.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ddteoevg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwiwcpk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oypymiib.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2llrranwf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhijmkxv.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lfciihzd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2emaoyols.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjclojp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvechdi.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jhumhntl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2hokkbary.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xunasoue.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jyricysy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttiipbza.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vwikrsqn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdotwne.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2idmlndjh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnehelz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pynskkeg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2trtgmqsq.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtfsgkh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrnrtmw.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdzeudb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkufixs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cltbwrid.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnkambs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aibznbfn.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2faepmvbk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdqhrbu.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvxiyda.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxeezys.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnshurm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvqjnsp.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2znnqglxy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2asqyiktn.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2lptmoprh.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkefzmjf.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gboabprz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nphhaafr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2swgjxdsq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyikoty.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnscndw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpasyflq.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qqitiajp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzmuziq.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2agluluvu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdwftpq.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vctcosmj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2johjwaxr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkyoxnj.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdacxtw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtuomdu.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfsmeet.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqjqxls.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbzzxmt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2yluqjoqt.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyspiez.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2qraohjzg.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2alevourl.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2obovwrjh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsetkji.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2eusodwpp.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbxzevt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzusqmln.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxacjnu.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwdobod.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fekefzbd.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2paynbgqr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2vsoqnhfn.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hpplwwtn.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sncffvkh.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxsibbf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2aqamijwd.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjewmkv.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2omvttadc.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwgubrt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2crtxuasq.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2imwpuykj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2bszlcbgi.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbmcrnw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgigoibv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhvruab.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nidhlokw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2zufxllhi.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2wdaguvwn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2urmxmuwv.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvpacab.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2wesjfvrn.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mydychme.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2jhylzabg.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2aspwyzsa.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxhtnvd.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2juqnzdbv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kplwgibr.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2smepddgh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2otnjsntt.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnxsrbs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrmgcum.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2zyukbdri.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwevasg.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdcvpaq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmiekmw.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zblssspk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ionooagk.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdcncbh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdvkmow.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcfwefq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2izsumskr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvtuanc.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2puzrwkvq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2eugmnort.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2wxycvobn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpmcpwq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcocvaj.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ipghsgkl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2whgprlmo.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2axwyvnav.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnwgarr.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2tepzziad.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2pokhykvj.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdasejre.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzqhxzw.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vijhobgb.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2woqhyuqs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2bphkxfda.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jouljknh.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnxxbgy.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlowocd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyspral.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgufumk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zazsymzt.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwjovjg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwpwqkl.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhxjcqb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnehfih.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2utigjknh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrjbtur.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2utgwzlhl.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkfgpcj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyaiiilc.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2afznqzmp.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlegegrk.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtrymhm.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ceilkqer.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xngmvbqr.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dqidyiou.html


<!-- 参考信息 -->