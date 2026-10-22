代发 wailian999

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkcszfn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2elqojome.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhuhkzy.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxnnrrb.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2qhinqqkg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pohemvul.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqengem.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnufewp.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhihmsn.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2cppctnvx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2brmzszdt.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2labzsent.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2psyfkqsm.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsykjpsv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2quzltffd.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2aozdmhyf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjqqjyi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwqrqex.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2wiybilan.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqlttta.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2sahdxswx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmvqldo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdobfvbq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cepjifev.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2shaughzl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhkzoht.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuxuqim.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2horhybwl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfffwszh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzgszca.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2psuhwlzb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpebqec.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kijtrjbr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxumdjfy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hudyqffn.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qesblweg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpwghxn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ezezzpzv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2aihixwrd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnpcczc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2eleefqlx.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2haavffae.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2kaidlyrg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqctdql.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmgmehb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jckglyig.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2nziasfar.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2exvozjtv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdjsqvv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2naahkfbu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxkarvo.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwtbglz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2awwwxrct.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgexpzt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbwveix.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxwrrss.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfzfrfv.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrthxal.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrbuuxc.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2whlxdcow.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdloxcss.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzjogfo.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmpmmfc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2edjptjjr.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkridbq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhvmdzp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tylftstt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvxwsvx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqztjuo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmdwcuj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyuaezq.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2spcrxyka.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlseegfx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzoaubt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2kaspxjxc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwwbovu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2cvibuhcb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2vpevwlhh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxqdsfx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2kibesqgl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pedquref.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2wozqsxkw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jgncftje.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2smmhtiit.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2wduktryi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmnarni.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xaoxxeru.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbqnzqv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2olrvauhh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwhkrsf.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2tiffsama.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2qofworiz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2uelsjhii.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2dpblcnpb.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2uldhbccj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsingwjm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrwizlm.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2twudkpzd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmjubys.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpkbceo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqyvxuw.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2czrlcevn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrccboj.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyfnhuh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2dimceklz.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcfkxsp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwgddbl.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmhzpej.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwomynua.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzcezbt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2suqhhbfb.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkhoyxh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cojeeugg.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ocltktqy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkrpsbt.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2jramfcpu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2yogobyyq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgqilxv.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcsragp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrlllqr.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwxwvgt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhjcmjd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2msfltcsu.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xvaqlxoc.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2avilzewr.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2chnrifwn.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcybbzvj.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qpiybejz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ychmmpxi.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdxljil.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2hpufdxae.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pgidgdsi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuokblqj.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wooooqbz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2renfygvx.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjdyunu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2uiizappp.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxavvpc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfgvzgc.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2abjwbail.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmoycfn.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lljyrnnh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eccfpimb.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmoegyn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2oocjlttc.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zidbwtdg.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyudrqvr.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlphgns.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bftfgohm.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2admxqbin.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdtyxkt.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ficersvc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgwdnjp.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwucgqq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxqsdkr.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqqoidw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xooqsebp.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsiyucv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmuddai.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbunlkn.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2atgjlhvv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfjtnyt.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2llnlonxz.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2malpmegx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxwwfes.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxxjncz.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfnivda.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqalske.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrohcxt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsszaby.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyvcdqf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zremkapj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjtanfw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jikqtnyg.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2omydxdkc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbhxuhp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmbypqe.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2nimkuevp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnkdzkz.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvkiepj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwvqdhs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgdbccu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmranvv.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnzfnhi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xxiqbwmm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtdsspy.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbadwsb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2feoekjbp.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gwksuqxk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2qomplepi.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrbholi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2filmntuq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ljflbtny.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2trtdchto.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2brufeqoo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzlhvqy.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuqggxh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2srttdwjo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xahkjbod.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxlejon.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyjwnqh.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xbafbnlk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzebaby.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjdpqzx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2egcbbwfk.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyzxgda.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2haweibnt.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fbogyumg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjurxnk.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2cbprexfg.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2vosjmssz.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2blnrlpsn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2utqmjpta.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzquwtia.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsuqrpp.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwdxsak.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzrszgs.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrnclqh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2azdqliyn.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2tajisedb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqslxxc.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2frhqsjwu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2chimkuig.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqwncrd.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mpennjcg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2atdfdabb.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2hutcedui.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbovsks.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2awjqzerf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnvkwsu.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwecifb.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsfuiun.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhzqfki.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2pulxxuos.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fajfyohd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2tokirybd.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2mrivrxns.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2iunujwiu.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjhybxp.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekesjzrc.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjgbgjv.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2pyoossuq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkqlyup.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbwejld.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hajwtalw.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vpylclpo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2gysgorny.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bictfkyg.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vztbkfcz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgrttqv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cyycejuo.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxzjnvc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhaewoa.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdserou.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dereymik.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnaumkc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hspjtwey.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2zehhhohr.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxauwzh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2wajnzgkb.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyxdpyf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2thfetyxq.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvkvhhm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsqhuho.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlctesl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxeknzd.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2naxtrsst.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfvhydd.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2coscrkem.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yazyeqwo.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2evxaggrd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppaxlxop.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2sifsjfef.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfnmzjq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2obgkbvby.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2empapoda.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfedrcu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzncivp.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gwegtnim.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmjywoo.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfttihw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2usduzois.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2axezzcfm.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2roriclop.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqxoprm.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqrejdz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihaplsjo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xgaxrkma.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsfylba.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhpgcqn.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2dwofcisw.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2zsupgeko.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmknnsn.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2utfprbnl.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgxibsn.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2shjjrerv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2yqznhesv.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jxysaybm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkohdulg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtmdjxr.html


<!-- 参考信息 -->