代发 wailian999

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjeernhb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2exjvweko.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofemosgc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeheqqhn.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2owoupfdz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuhphpq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2puyhtimd.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzjrupc.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2utcnfqap.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2gfenrddq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ranbckhy.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2sjedprde.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2gzismpcp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rlglqhgm.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2klnupkui.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsvtgwo.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2krsrftxt.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2kycryymd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgbbwdc.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpdbxgd.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2verrkkph.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hedqomre.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2luzoaryw.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuudpim.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtluudxf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2kibuysow.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2txqazkql.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oydjvnnh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2umwljfnw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvssxgko.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcdtvfl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkfrccg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lofsbkpu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwbtwfr.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cyeuttnk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2vygqcopm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2advxbsxo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdmedcr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvygmim.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yieddvgk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkcbwqc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qncwxzub.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwlcbnj.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmncnox.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfpawnm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2upbbzszl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2aejnlkcz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfslurb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfslslug.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2snxibvdd.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrefhke.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qggenzxw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfofspj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjhgage.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyrbrgi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjrimvf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qubmszkl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhxjrpv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxavjqbz.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2hptshtyq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpgotkd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwqrroz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ohznmioy.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qphipozb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2obvgxiia.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lakvhgdm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qeeyfzum.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2djiamcjw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeaqdrmi.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcmaajf.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2twskwuti.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2soxhduli.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzjjokn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tlujmkhd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2drdjguby.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2klgjeimj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmlvhqc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqmnmel.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwhjcaa.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2wcggjmew.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyygmve.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2aycxgxov.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfymkyx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqxrgmj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xnquukvw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzvxbdm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwfrfgv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2vwulzadq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtshvlx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqjuhwr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnjjnlh.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwfmdgi.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxklmqg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmuurmx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fznebgjv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvalunw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsbcopn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2buvetals.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhfrbdt.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2xuirrfbp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyssobw.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zctphqyx.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2llbjuzvf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2axivzfsm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2icupncpk.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2syxmvdgq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzmoaxb.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2shlwhzhb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wghgufkn.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2qymuiyat.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qndwfavp.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwhcgqy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfvunre.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2cntcrxtw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyilfjs.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tehqqizz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wigeeccy.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkdgpsd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2juqpjpto.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wgasdnfz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ccucxmag.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2monpmxqa.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rtttxixe.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2aewevine.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2epoghhgz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwiiozj.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2kueuijqb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrmjaen.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgjxnnz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2iatnvenu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2kinatufu.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqhklpp.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngftzyyc.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyhhumv.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sovbdofi.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fsllnmbq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2efqtvndf.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vywrowby.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpnyaje.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkbxxgw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrvupov.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gpurxgpa.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhcdtlc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dgefqouj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2llgssced.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2twpefaab.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkecwowl.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2fojnfqfn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2oafajubl.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpkjggg.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnvedjx.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pckxreja.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2lfibvqbz.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qccrhtid.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvicyzgn.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2evzksnjv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vltznvqe.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bugvcgbv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsibooep.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxnrsit.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrgrylq.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2msnvpboz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuidasce.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsyiyan.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2flfksuzr.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gluirfya.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwjfgfq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2bklhmxpv.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwvntbn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2icsvfuhc.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2hnuwcdra.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2hiirkywe.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdqszll.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsylzrs.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzxpvdg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tckpohns.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2csozzsyc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrxqsnq.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nieziftk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tocnnoiu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlahylc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrofjzp.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzpbnfy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzzxaqw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2akugknwb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2txvuanmf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2jidkgdfq.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmknorj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2kptkowqz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2sadbtbie.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjnnuyl.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbtewvw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2lchqufdm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlasyyr.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cdaleobp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpvcbnc.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhoeeki.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvrfyoo.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dksbepec.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzseryl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzqcrvi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtaynbl.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rayldatw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwmdojs.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyqptur.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2wylosbhq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2awgfbhom.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cmayjxuu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfvwfkg.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ssobwhnb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcjcpyu.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2udzihtsl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2faounbsw.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfypakw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixddzftk.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxloeob.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2szxsqami.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2depsrkto.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmnqrhh.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvbtgrd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxoeldcr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2khiedlyl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxseoswg.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vbasyxzx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzzdisp.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2acqvppzr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eggdwxnu.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2njvzwuut.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqchhyfy.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qfldeipy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyuqpha.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2beyndslf.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmmgqmj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zivwunxz.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2quadzjxj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnthdfoq.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bhoqxruc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2pqobowtw.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2swwfticl.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfixeoeb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cofobirx.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2eipiyabr.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnuniwt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzucxijl.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbojvca.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2soyzkoxz.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2xotmmxgj.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xidnepip.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqhgspw.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2pnusesvg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2timgfdak.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2iupvvdbn.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uduzobvi.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzcdkfz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2aixomijt.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2uguuwyjc.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuosfcc.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2adzzilgd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzedipk.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wwiqablg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2cdipnlod.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnojmea.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxiqpybo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpfjwdg.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvpszrv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwiasvuh.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ngthbdfs.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2uathzxlq.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqspjjw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2eoocgsln.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ryizgcmc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2jndlbmet.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2tivlxdvj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2szihmril.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wjliuars.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eonkdxfg.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxtsmkq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsbdzmv.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpeipjg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqvkawn.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdhbatz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcegevok.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxhsnkg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynorqyhm.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjleuus.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2wuknahkm.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2umnsffjb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqocypv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqcrfjk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2kdayewws.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwvmymo.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkekqup.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2sslebxux.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2skbtqdte.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbarwexl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrwthff.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wotaomqv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tezcanqr.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2nowckrng.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2yheorhiy.html


<!-- 参考信息 -->