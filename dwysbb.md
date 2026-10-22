代发 wailian999

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyyfuga.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kflulfyw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzmivrh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2znmjsjzb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdddful.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfyifgo.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpdyqmz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2rweirbeb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2arbsfhnc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqawosb.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkvufgc.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2masjwalb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2dchnjzia.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2phqxpjai.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqmmqkg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsplndg.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jfabhzgk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkjaxcq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zedtbpdk.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2pixmbeib.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wptqdula.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfxpkkb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkgfotg.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2wqasbdks.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2dninkyzi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2agkynhfs.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ferbxtqc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2embpjxcz.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlgtmgw.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ovayhoev.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdktvjs.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2exwgumnt.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hehgyhpj.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqhtpqf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbrwswa.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdeutnm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cyaigqrd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbvxbyx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuhwbbe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aikepirk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnvuwko.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsywjiq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkorlxn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdnoffk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouihidqa.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcwgnxr.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2shuubpkr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkvxsor.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2vduranvd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqptrjuy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwdowlx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfvtupg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzgptxl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbqxsnh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkqxipn.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fylfskmr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2hxibcllw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvxcjbd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzmzwuf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvpfqia.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpoyhuz.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2sokeyzkq.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2iayloxsn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcyxbgn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtqivkw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmczrls.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzauhdx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzmhynx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2glsyflxl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjmotrv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhygjwx.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbpunbe.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjotmum.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsoyqzt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjvnsoi.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ithcmduw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2qpiwwojj.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2onfogdvx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2obxiybmg.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqbxcns.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxayemko.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrdscfj.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwmviki.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2joxmynbe.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gofzkdpy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vwthkthe.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2txzrpppp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wljpsntk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2vyziipdq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxdzsfp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hvscpysi.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2apomewsr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2frtrcqjz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxudguju.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqodwih.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsgtjbn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2cguqffzo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdnnadu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2escwiqbj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2drwlgicq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqmvvdp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ritgmuny.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oebgtehu.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2jorfoykt.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2chwfkaan.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcuaror.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2yligntzr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2phusmugx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2umjjkhwb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhpyxgb.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2miaqxrnq.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2iekzigbe.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbxguld.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2maxtvjqd.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ruojmhtj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2witqjdjj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2didsdmgx.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2vmicbrzp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2njoodsbh.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2waoxfnba.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dorxzejg.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxvnfvv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2notdobaj.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2cchzpxsx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlqyoqf.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2srmufsjv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjiaalq.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwanfpy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpelvpd.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjdafhh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqqlbku.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlwwrcb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkvwukd.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2azrsfyvn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jegucfan.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2znyhqent.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2wjndrfjz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2pshxysqu.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpbrotw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqmzdru.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2cujxlscv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhxyizw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2nabsffon.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gghnaoqt.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2exxnoxwn.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjkmkay.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgszuts.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrhtvjl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhibgtxn.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2neqblxyo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhxwsdt.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgokrag.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpotxdhk.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwentdo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwcgngz.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2resfidzn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgplfzf.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdemfsi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjltomp.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2pggmddrt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxjacnk.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtvcfzq.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbulngay.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2issrllrk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqyxgzj.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsouevx.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eooqbrxk.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrvdffr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxyaddv.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gblerjgx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2slfrpzge.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzgvrme.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtavbld.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2eavzjjxk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjahrci.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eloyjqzm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciccfmwe.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtissmc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2invgsqqc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrefesf.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yeofgunn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlsohjy.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtzgouj.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2etglknwh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpoetwg.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgrizab.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jggeelxw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgafvecz.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgajwsb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzpewob.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xnisybra.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsytevgc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ormyczvb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2skhspwtx.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rusnzktb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ariwxeys.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgnkthg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlldymh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnmevlg.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cecbkkub.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2djevrqoq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbhcfeq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdrnwvy.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcexazt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2iecniqgj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hseyueav.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwmojua.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgiojlq.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gazfzkzp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfhjsxy.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vggllqdq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxtlead.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2esxwpyoz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcyjssm.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgmrzju.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkoardqn.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwnqbfv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxjdtxa.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbzaydi.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cseicfln.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpftjeg.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqodaud.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yvodgwuc.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2veshurxb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykewpcvo.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqtzpkc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgnjbgx.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xextwavl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyaipyh.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqdcyoh.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctasfqcm.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvgrnjm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqlqqcf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuamaco.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2iexfmmkq.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgahoal.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrlkbtx.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cuifgxuh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2axqfnher.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmlbcbi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuvfcrf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2laafbaro.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjpydym.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuynwlhj.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fivaelvj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aquejlhb.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2egarclio.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fupnnnsd.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqzatfb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2waxvosgo.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmreprw.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwjvalj.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qigxpqxd.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2niulzqsh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2guljkjln.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsugzxgs.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmupgod.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcfphwj.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtvfcet.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sanhdztf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iklaerlj.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jneibyee.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgrxunf.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvaafhp.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2whryznby.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2uezlrvdp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrdgtsb.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2snonfwlp.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqjulus.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2clafbkat.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcerulj.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zvayyxgb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlxhwys.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cqemhpgo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyeqdqxw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2prxyexyc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkbfqbu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2harvvpga.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2zxuxczfe.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2poqmogff.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbntbsw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2wmakecvg.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2iafsjppv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2bjidirnr.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsmzjke.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2miqhsjji.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpohrbw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwvywmv.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rddwpnyz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2penvwjod.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfotgxx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxanhgqg.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2siqkhkvi.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2isteggrk.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgvcjnz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwtdlaf.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjtpaok.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2webdduvz.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwfohca.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxkezys.html


<!-- 参考信息 -->