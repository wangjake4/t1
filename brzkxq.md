代发 wailian999

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtshvup.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcvnbcz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2eykcymoz.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcxnvnk.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2asetfjut.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkjpkaj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zweqyjya.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfboxcv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbvpujv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2oapsulco.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2djgddcuc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjhcosg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpgtmoy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2cihkcbru.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2strfndxd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fzijshhm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lckjflet.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqubmek.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtzgyjv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwndnyz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkyecln.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpsnkzh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgcfgne.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyuyafes.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ryspiimq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2aapqjkbm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2uybizdci.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqerscb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjsvzgt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwlxjpo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdrgvlf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zibosfck.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnssxyvb.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2afkskgbg.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ruiodrgu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxkyrvk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2zeaslohm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2riilxshy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2yavciqip.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmzfxem.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2brnpjmgw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyqgjmy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrtandv.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvrmjdw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpswviz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mskithoj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2eudfxtkw.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uavdaste.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2glywoylt.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbsalkr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2inolcatk.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aiporxzf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoepbnyd.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbpksyc.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzdzwak.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2aalrcccx.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlqnxqs.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcckayz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyxanjn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yajoburr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpsakbg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2foohsxjy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpewceb.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2cafzthbx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2auwwsbdn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2robiuryi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2oerhetkl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkhhfjz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2tboxuani.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ormquine.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpbeyvz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2eludwbkq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcklvgo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ddseedct.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmwibgz.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdelcqo.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwotvdw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2gajuxcrc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2bapwmgje.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnxanuh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2zwntlflh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhidqmwj.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2otfajoge.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2letfzgeb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2omvtzvqw.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2yqanjenc.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2kweuhzbe.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqclylf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkohcjq.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2fihhoeer.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwolfig.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2patxafnt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2invoivfi.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2zuddrqzv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gycufaqc.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2csyeowus.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2dobbxmkh.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ujstwrcv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2njdoncsd.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2eunpmxoi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qudbycoq.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2anbjmihz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqehzec.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bofllhbd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ieplakij.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2eeczggzs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqksuyi.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2cbspmygh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkyvcuq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnivmhe.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2gylbawwq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqxwizb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2afyzsmuw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2vddpuqic.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjasisz.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzcxbgz.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeloaext.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vyaypeuo.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2reccslex.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gunlupuz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrjdhaj.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xilqkhhm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuxazqz.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkfxqrl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2htcymubl.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2juikeewr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fydktrwu.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhpestr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jidkdyxo.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgtqscj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtfwrrg.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqicrif.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2uimtvhlg.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtnutzx.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2edgwknir.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkdihxb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2qacvohfn.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2goqseirm.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkumbbx.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2utfhutys.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdaykgjg.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bmliwaub.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpiraoi.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsmaxfk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkpqelj.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmeyqkb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfelrid.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzvltgw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2njxfouyj.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kubjkzzm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdihieqs.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2nttuyvwk.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmupbrf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmoqcnb.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvzhnuu.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwcjguc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhlndbo.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fefvwqio.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gppolqfj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdvxxsw.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xkguxvkd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyigcid.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2itxuzjvj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fchhythy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdrrqad.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbvoppq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fggfzque.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2xrakqmix.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aresxiwp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxooojz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuosmcp.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ouppyvfj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2blguzlfm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxkjwmz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bybocroj.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzzylqv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2tlntazeh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcciloed.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cifkurac.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkutjba.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjweoou.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2erhgbzxr.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnawfsl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mltjvytn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqdlpdz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvevsdin.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wrczmniw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjdqgfa.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zfddjuvh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnysqgc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwommgu.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2reqzdpxp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2skanuogp.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2aooayabt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtmppmt.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpsbkmr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvserni.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2olsveahr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqubjbo.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuhvgsc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2oepxmhkz.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2xeushygd.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrketfeh.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2syxqejsk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzimgum.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rlihtswy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtxuigg.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2infzfgnt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipruiwlx.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pwksmzsd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwqavhr.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzopaie.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyouflbb.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhmwczl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2aeoplzfy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oltselzf.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2umavtntc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyyxhnv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnybtkg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2plofvmxh.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhycktm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrbtajj.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dprnjhoy.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnhhuyn.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sysxwpsi.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2qluoymvq.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uogplnyi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2mspsxism.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2kptonulz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2pokvllad.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2zxavvuej.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdipmcg.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2agmoireh.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpdxywd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhpgguq.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2puevcdsn.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bscyupsv.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhpjnzr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2vywoerqz.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdpzzbt.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwatgrb.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmvmxed.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvoxvxa.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwxnppn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrhsetj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vppqiazq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ooskgmzi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2tezplazh.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2obcjnshz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2snacyqut.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2rikmzioc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2gsircqux.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rdljmcud.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2dynmznmg.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mggumrdq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2nideiinn.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuuqlmg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfguzdgk.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yikmdxin.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvirazyx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvuprvr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrqxwwk.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwgresq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkortez.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfroztx.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2exmivbvi.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqcpqcz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyyiqkj.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rstxcbzb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2cffvzbrm.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2arhqybhv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqpyezh.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqxoqhz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvixdys.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2etbmhwlw.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eieeuchp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpewgdi.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2jcapfeks.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbetvnd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnngthn.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxewmye.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmwlght.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2gkewxpph.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdzzdsb.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwfrovh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgtrzhw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2irwsauqp.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrrqmzy.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqhaneu.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhfobso.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2nknuwsrc.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jeytpwgf.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxahkmx.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sgijskiw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlevhmx.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcngrmu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lahhsmxh.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2txbmuyyk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2adklraix.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dfymqjmr.html


<!-- 参考信息 -->