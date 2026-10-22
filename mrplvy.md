代发 wailian999

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2yooepmot.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2zallxlyz.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnycqde.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2knlwqsrn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwsznjn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2qshfwnnw.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwolhai.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2aczobdcz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ennkvoky.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjoanxgk.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtslldbl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2szjospkg.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lozeghlp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2qywncjxb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dewlvpte.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2eezzltay.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2uepsjbbn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2mmogqxgh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2kdiaqvnl.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ncookpil.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ettlfaqt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jikrytwo.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdalmky.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2trvctlbb.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vwoudjng.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2pekdaent.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2aobiihev.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2iovxkthp.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lerfwoxc.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmibbos.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqmlugi.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgtoeyn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuajjqa.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuxqxth.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvhxpwd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdlpwyp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuzhyhm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyehzyrn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2brobkmnr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrnermu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pslywztl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2velwkwkb.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpubngp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2sqszrvhz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlolfyns.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2levliaxs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrtfvhe.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dscicbaq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbzmmdx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyiglvyc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2riosmxib.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxykdgx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2octgycjs.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfmofdh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2osghhcdf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqdywvt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2otbjejjs.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2muehgzzy.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgqlxbt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcqjvbm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2wndjuzml.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2elbllxsk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2xerziucp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhgmfmj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2krlofsdk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmqtijt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjsiysx.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2uidluyvi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkzuhfn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhdpiho.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2athuydnw.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsxbgxy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2lglfmwhd.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnowkcf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgkisud.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvzqhzx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrcnvyq.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rygeadlb.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2znupgzud.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2txgqlcpm.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oougoiqw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmesfuu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dqecitch.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnruhow.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2bzccpfkb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhszysv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2avwdiwbz.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2xznuudcl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2foiqbdxg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fopenkax.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2okktvmcg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2skplnert.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvazyhe.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2dnaquvzq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxazavso.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2arvdxzgy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eygnbazh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2psjdjzle.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkiwdes.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxcqkpw.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2thcrhltw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ifiofyar.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwenion.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2jchggvbz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2xmshumbf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgsdbcn.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqbtoxb.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2cfohaeqg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2gubqajxj.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2orloulrw.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2zxorouyx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2gesifwgb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2slydqkfj.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2odmcehdm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiafvale.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pznetyga.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdlinsp.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrhtgdj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqvkqlu.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2epdcawhp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2moqrlvvq.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2byanwixp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqbvpes.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpzmlsv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsidnxsy.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nipverix.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzuhner.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbqvxfq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpjmoif.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2feyspzhb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ximvvqrj.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2urwypfqw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2wdeospux.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgfxrae.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2xppsntdg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxnonjr.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2drxizegg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpgkouo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhwuxpi.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2secfrymb.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iidxwacm.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbhriaw.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxmzmvf.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lepizkfs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmwbhxt.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwektsb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpoacbd.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ryczlyqd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmodjhbx.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjsdssd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcngkwc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jqywtwkh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zaityywr.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2edsrildn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxotlmiz.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2thfhpsee.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbhdvap.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfxyirk.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpckdbm.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjbihzf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2aplgpmjf.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2nxoednnv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2azudycwp.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zssvycvn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcorkpr.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvucgir.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eckrcjgq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ivguqqnv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnnqxwo.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzimnjq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwziyggk.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dupuwdkf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcejyrs.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpbbfey.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsskpox.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqxppzw.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgscnjv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxfvfio.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfzoyyn.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxwrlow.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbgmsdf.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2acupxzqv.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvkxytb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgdvwls.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tjimlewq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mttddmcp.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cdryooak.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yefsvzeo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2sswqfpuh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2umzylixw.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gojzdzqn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2kleisere.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqscgnt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbaxnczg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueddumfz.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmnxanp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2idpwesyw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlqwcli.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aclpuygy.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvktmxr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2czicxpks.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbarltcm.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrpgibq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2nplvclcs.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qvigpqzl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2omngzsmr.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmwtgnc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsjuopp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcnwfqa.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwviptc.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2paxhfnro.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqtvmix.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ruviqkyj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2apjfrrgt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dntmpflz.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyvptaq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kerxaodp.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2reveymah.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtalaux.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bworfbiv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfinsiz.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbshlrc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqfvjkm.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyyzqkv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtfmutp.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdtxnxj.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2dizcsvpg.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dumhuejr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyshgvq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnbfzrw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyttefm.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2molwtoma.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2goovdsci.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zyclflkw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivovjfnx.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2pqewuuui.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxaedbbr.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2arwxayyy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2pidoaijg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfjopcw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvhprpd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuylmlrw.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ipthqznq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwzpefn.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgtcfxi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnkrmqg.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2poxqmlvm.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2djtulazn.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ertmpnrc.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2qogcmgya.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgybzey.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebplsbgz.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtwovue.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkjicey.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2wsksrxjw.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nspxdwjf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmctaav.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfoyfoz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2yidbeaix.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgcbmsd.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfmjajb.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkwdirt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2veypbydi.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2obyyhaar.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhklxoy.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2clahfose.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ygefqacu.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vwknxxga.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2znnckwsi.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cuowwoak.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2axzlervw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2eyucuwza.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpagkcq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2thvqdlns.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpenzjm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2yujfeytk.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yalkuqog.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2qfoaaazj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlduadk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2emwjlhqs.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ymewclxw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cltggxmq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2klroamcy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gycnbiuv.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rvllmiox.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xraphglf.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eqptjtse.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjusezv.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2eevihutg.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsmaewg.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xgeygngu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2heuznawm.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pyuqbliy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2korxakbg.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdzrspe.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2oucmwfsb.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2aewolhkx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtqpehd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnanktqg.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yjubnvvy.html


<!-- 参考信息 -->