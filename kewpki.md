代发 wailian999

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2affvppxh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnrenpf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2lfoxkuui.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2frdxgllb.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqjetje.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2onymnuqi.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2royxtzgm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nuebzxqh.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wlombpol.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbuuqcl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kqienqkl.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmiiycty.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gaidhucw.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsejfbp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ynosuuhk.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyptdru.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhwyifl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcgxolf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2nomwswdi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfifgoes.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvyujlp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2vifnroqr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqmeppn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2glsaguzk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nycaerlv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2tnraeyhv.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhcfxlv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2awjwbyuc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfjudmf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxxyyzs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksuvgyjs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvubixiq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhexsrd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2knjlqkbl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2oavyeoba.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hbewoaoa.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzxtems.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dckhxkok.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzmmkjh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jclporwq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2lafknydn.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2byrwwoda.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rqojpoml.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yjovjecz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2uevltbmu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qerqmyor.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2vroenjqo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2wqljxwim.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdwmyxs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnbedgi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kethijog.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2cyaqlryu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2kndagklu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfovoowm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpdjkqs.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymijsazn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhqpjwx.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhodcuty.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlbeaoo.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdjmqol.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjldaivv.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdayshei.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gwiycqot.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlkmnbl.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ayukcsqy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kkeujcgn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gtewnhcl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdqupxj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2itynsovn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dygoytwx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cnomhswd.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqpzwqq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2awskwpmf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sejostji.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2yypfculr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsppmwf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2nojwqecf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2wllqxlic.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2nackrwry.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2kezczgvx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sebideqw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohctelug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdgvovn.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rijjfqpl.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2chfmkhjj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzerevo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfkvdpj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2lsguxsby.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2dgslxmlw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyltvmzr.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcqchgp.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2coznvczi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfzilya.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqrgpmn.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsuxtfk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2mptygucr.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjizypvp.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2zoshbbul.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdrswrp.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnwuyhc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwptcnz.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2uoplzdbe.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2frlizgfy.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2otacbxkc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsgiomf.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2lovpawxj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yundidmt.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wzofcpsl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyvtfjx.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxtoibr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrsxhsm.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xeotsotl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2iisuhpph.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtxcpxp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hczcogqa.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2rucofpdt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbeapyy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2aksswced.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2nxeaitro.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2iuikrolr.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyojlxi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2lwusfqxy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2lshpgeiw.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2msamenui.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxibrqvl.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2orwtgoyl.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsygrks.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ztasvwkc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdrmvkx.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhvlsvj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2aqctetrs.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjgfvla.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvimhzbc.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kbezjdmu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tztpyglu.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwuytaj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2yloetrrd.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2raernwlq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfvosjx.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpenvac.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwytnxrt.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lshzzxhu.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2peccmysq.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcilfdv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvlzlnl.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mpempbkc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nutiszbq.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cczlezkv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxntalk.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2icbehxqo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrmshqu.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2pwewynbl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2morhpssa.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2stiklfig.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2amtckwny.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqefzkl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqfshzv.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtemypw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzszhwtb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2xklzjxnx.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfiowzm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2klgfaduq.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkqkqyp.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2voqcicxt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqsfdlv.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfpzzeq.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2emxjpqux.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhezkly.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2allmogme.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pywiljsp.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrooweo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxcmsqz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2myonezog.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvjlojv.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2awgoyxjy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzpbkir.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqfynjv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvgyuip.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bowbijoh.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxwqojk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdxiqqs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrijixb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcxotvu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vumvjjzd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ordjoplz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjtrysw.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvtctpk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvwmiik.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2asvxfupc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2icnkeegx.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vghgoagj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2phgbluej.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkhxqag.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjjkfze.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyrzgut.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgdotjt.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmlgigh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqltyaya.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhmriuj.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtulkta.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zixgivcv.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgatggo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzvudav.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcxhbua.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iacnifpx.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcwvxci.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqfsrvv.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcsyubf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mczgfjyc.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2katpotdw.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwtuktp.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpywrpcq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnangnjg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfafirlx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzixopr.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fuiksgll.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2etotrsbn.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wxczfsvy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgchzlm.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrxhnso.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlultjb.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mjurtxmm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2iigwehtr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfuxfha.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2grkbghou.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvsuxnd.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2fltnbiso.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqpsdmy.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfuhjib.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2htjewqhu.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfeuxur.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsaqpjo.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmzsbpo.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2edhduprh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mcoflyvr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzradct.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ktttomrc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcflsjnz.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmzvfmq.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtwihsf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnguagsj.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtugepk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xbriuigp.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcunjqb.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuuhgwa.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2inswfghu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzsyiqx.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmkthpq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnvgimq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2uzztdlxt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2othiqaoh.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrznckz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmfmtll.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ygagfziv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcfazil.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkctada.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrgqxgs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcecatj.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2pcamjoju.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2kstyaiwe.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2klbekpha.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2falufpot.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrtcvqe.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2gftcybpj.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjcftar.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxktqdtn.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wkaqapuy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pigwjppl.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2usvdizgg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvqjxxt.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aznhrwgj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocksuuyd.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2iskqobxs.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnsjese.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2mhstbswt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkixkbey.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmurwmi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2vowngtmf.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2peajvvcz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2cidhdrqd.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvznowl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgzlwvi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2unqteuvm.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcndqbl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nfezhyif.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2dinxcthx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xeaqwcnt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2evdstnjk.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2okiyejqk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdmjjtu.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2aethqijw.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2byocmasx.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2bbskdeao.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrjyolw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvlrguv.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2suraszwk.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwdrotu.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnfvfzz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmlxiwh.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2erfefqtj.html


<!-- 参考信息 -->