代发 wailian999

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2szyvtujl.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2wltzqaep.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kjceqgeh.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfpprox.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcnupwi.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kucximur.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfbdjtq.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgfuluj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbbsjrh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2bcocelrp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2plgpwzmj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bavcdfru.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyndfza.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrrpruq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpskctjj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwwdyzp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfvjjah.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2dciwpldc.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bulydvhl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvxjxic.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxbesvn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2livccevu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xylqgnuo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpupayru.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2puioeeeu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pycvqpyy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdkziwa.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2angltsuj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsutukx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2urjnngwa.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcyghxk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wedahpuo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2qeiauusv.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrojrbp.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxgpwbe.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jouvuhqt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjomexp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ihuuxgqs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzjdiiq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcrieca.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjmimpp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2gsiiklwj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lacnvmrn.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2koefldbr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgfuxph.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2aemwsspq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2wddnkzsp.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjwyofb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2zawryhbb.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxmkxxp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzfgmrx.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrpxozk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2vciraqjl.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdfmpvm.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnewqus.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbwzzcb.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2twfowcqv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dklljblx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vfekfidm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrikueqz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzsvuqi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkffvlb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqbfwon.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlddlyg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cabrzaaa.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvafgxyb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2hvexfptn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjmhswk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2zvukrtyh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwmothv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2toiebgmq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2aflvqwzq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xhulfhfd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2fievmxgy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlyaxam.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwdxden.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2gugpfodx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rawauvqe.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxgjsve.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxaqdjv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ecchvhpq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2yithvmas.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfhqacv.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2yupzwita.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyoyyts.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfozhjm.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2avaralpl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjvhoeb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgmrakl.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2szqpvomr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiorknwl.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2idcfunlv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2iugpxqdr.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2itlfocwf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyknjvcm.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrfhrdw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2jswphdve.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlfbuwm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxblkcxt.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2czwxaoci.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2topqpubj.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iostjbng.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktiphszf.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ebroahlj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ogynlhmj.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2rghmarjc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tyclgrql.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2uvypgxty.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2qokqzctr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2itnsppnr.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvwcjjd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ahghjpzp.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgtiaix.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqkeapf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmijyahe.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2favvgszb.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpevtatq.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmmmutm.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkiedae.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gqptpoxt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uooqwuwh.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2royagxlm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2meqsawge.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tfffnuuj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuxxmvs.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgipvcz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kejtgzra.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rozjokdi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgwhjwh.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdxfvhd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2czdspjyv.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ifteutfy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtxoqck.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2akxjczlf.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nelxfghy.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nruxwmby.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfvlwck.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpblquf.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xltsigpy.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ztluqiig.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbbpsmo.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmozonx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsgxplu.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhntvuo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aytlxlos.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kffkhisb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2iflpsxfu.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mhaxrbxt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2eflkbykz.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wckudovz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtcwbvs.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzoaham.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fgevydyu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2zztbdhjt.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ojujplhc.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2xbaehlvt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2emsqhvcc.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqcauxb.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsjdmhl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgowbqhc.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2itcxjlaa.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcyzlmz.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzxdgkl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uboghnfq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfclcae.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhttpvdi.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2irkteqkp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdmlgje.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2innuaxxz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjclveag.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwokhxna.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nottqbbi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2irpjioyr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2kckvdadj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmcekbu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrjozqt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjiyqpk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2brxcydww.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xojijikv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvniywpn.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxmhjos.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2yremlbvl.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cpeyirmw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkpmikt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwscada.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtjjxiz.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ivekuodx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlaqicmp.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2swbnmset.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmgqpdd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkoswyb.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2eowpledf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gspyldcu.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhcjczt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2omygupcx.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ldieievj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpdpctk.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2czymmiey.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtcpxmq.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2chqvutxi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjdipfm.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlscgix.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzejfph.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbagssf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqecpzu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrfkvaj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhkquvt.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mlafqhtz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzpewma.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxqtrtr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyxmizq.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdvosfm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vygxdfgg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrxolth.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2exwcwarc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tscmkoxr.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsoaeah.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2myzybtcv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdngnpy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwlidjd.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqswxpf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2flvztrea.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jikmminq.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2euxqdiiy.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiqyeyr.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2crnucnmv.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mqijtuyb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2llevoezx.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2clqnfdcw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxplqisa.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhrssjs.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2brqsxbsm.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbztvfbv.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2cylwbnpl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ienyesyp.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbilzro.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybocpfzn.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2mxehzqet.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2udysfvyg.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzlmxps.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tskhudpq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2rojykakh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdksxjy.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2eupqsgxl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2czqircdz.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbutltf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjrkuym.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpyulun.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2haryrrfh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2akdnxqex.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2nirfyiqv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2rttzcurf.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hcupyomm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2wyofgmit.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdxqkkc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2yknywsss.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyfjtor.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjhizrd.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2udmxcjaw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsalbkp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tjluwntj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuaiqyw.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhayhtn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lojxecyw.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzmwjxt.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjhvdjt.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2labmoffj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntagxqjx.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvxxtgm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2usxlcnpi.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbamkyf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzumlath.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2irzzhhxu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpvijcv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2euvbwxgt.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2suiptnyu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgfoghu.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2knclczml.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlewopjs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkkoqzv.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxeehly.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2piovrkew.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvobief.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2htrjymyb.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfsrjnd.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2twkjspkw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhbfdzq.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmldxiz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2gvluaxiz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjpabiz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijeyoiut.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fpexxsmg.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2budsmzez.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsoxbxa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aujvmlcf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zntwsrxr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wyeosdtw.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdtcsbi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fadcbzpo.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gvoqmkkh.html


<!-- 参考信息 -->