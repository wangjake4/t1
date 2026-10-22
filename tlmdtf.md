代发 wailian999

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2aalaylty.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbwjhsn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgemtrlh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2pummbcdy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2uypnlptj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpkrvql.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhlqlzc.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2mffzrlik.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzzfsfc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcynrcp.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2oupqqsho.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrhsruu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2lyaurngl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbunpqfb.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2usswxoqe.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxptjrcj.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zpivagni.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzrsgiq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yonrhgai.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhdenei.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2saannfgh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2jzguxpug.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2maleptal.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwkpvbv.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuswbqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcbnsmu.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hemxjvpf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqqtarq.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2pagxxovr.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgrnixc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lugfcaen.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofznxpon.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrneytl.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2exuchlzp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxowjfw.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwwikfc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghoztahf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2oppkmsoe.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfeazhe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2osycdlmw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2iweqjfns.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2paciumyw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2znzuruhq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcpyvvv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzkkpnz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmtzjlo.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxkccxr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2waswfdnx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvytcznm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjtrbwl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kiephove.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqpuixl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ifetcbqp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqzruuq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2yecstkkc.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2azgysitw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqzzabz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcyxhef.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2yttsdesq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rykjgwcl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovswokjk.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2kolvyacy.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwjyxbk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqozgqb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgscpjk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgqutsr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsojspm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2dubjjemg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfhdtxi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgneikl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hadpbbrg.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvvlxbt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2yeebhnum.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuumdma.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnlnjyx.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmzpxpr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvbszhb.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bifghpjo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpigukv.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2retdnrky.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxmgzyc.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2odpyutvn.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2czpspeqf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfesokj.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2difnjtcf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgiucbz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sstwdqmm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfmgmkx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcxzyrq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqaftpz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxwulrf.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2cogjtocu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkczsysm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2elluqrgv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfavsch.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmzufju.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2wutdpcvx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2yynkwayg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqmqsvc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvpttrb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kovtavua.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwpydew.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bikwhmdb.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzzdaze.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzdefoj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2yyohtsci.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kthfmrfz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2hicwthqn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2rfikkbuj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpagbenp.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwfkigf.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhvuxtz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjxiwus.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmccskm.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2grfqsoiu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnncoqql.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwmqyny.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkngked.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2upbiynhw.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgashdr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2yksnorcc.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrcjnmv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnifzwzj.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ohygpkau.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhsghlw.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzldutt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuccdygj.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xswnzyji.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsccdsx.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlcbnrk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2njkhgama.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2dznknwzp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqvpbiw.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzootqr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2srxuwllo.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2azpoktzb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2qmizuxxo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2fflkbekf.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2rdshctdq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2oncxebnn.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2uebqbxjh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2qbevryfg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2lptkfnpl.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2sunxfuoh.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kifinfnv.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2avntrytg.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vclmpnwd.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yawwngba.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2katdykeh.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gisvjhzy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcapgqc.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pkihggvm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnmczzo.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbqhpaz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryknmxgr.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wmiuzuzl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gifrdqhs.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwqlqwb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftiwoksj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2yngdbeit.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtskkzkm.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbknrqv.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnevvcy.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bopjwsxr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2vinjzypc.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqhtnnk.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzlhfpv.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vobxdpim.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vihpjgsl.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvalwjk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhcjxmo.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcpshth.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2shekvxzr.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcuycgl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtgobdc.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2psdofvsf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpskfhom.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bnurbhql.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkryexp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2latchkds.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2csaraqeb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2zodudtqx.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ooiwybxd.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxoqfqs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ejulfypw.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkkwhgh.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbakwsk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdbdtco.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dxufjujl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ungimkqq.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mkipckzb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtffrlr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsxrylm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qumxmlfx.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ehanrwwt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2yyllpyon.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxhtkyc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhsahcn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2htgkkddz.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjjfyuu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjnxqrc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2evzsgzqj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgnysqd.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2keiwrjff.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhnyqqj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2frukthme.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ayedidxj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvwfjgy.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlrivzh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnqcqsy.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dblvjgdb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxbrram.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2prlrkdrw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2sexxafcn.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2prvvelbb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2gicnqpcb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnizlki.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjibfpky.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2efszejwk.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqwpxfb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2manvjdsw.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cgeifoib.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ijditild.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fushoyfl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfzfeme.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2xwejfqqz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2omwgmbnn.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhegilj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmnfyub.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2asvajftz.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsfjjkj.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlkjzib.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2etdpjqil.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwemkvp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbpzdvo.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2sctvkhfr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogemcnum.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2abmdsajl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcayjaif.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2yjggoeqh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhltlzz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmcfhao.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrpqpjz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2anddmnan.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlmzciu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yktriotw.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgqhdqh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2odroqtdd.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvvvkpb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpohtlm.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhtunfw.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyszftxo.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdulbth.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2axfdsymi.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwpedjx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2isgxjpvz.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2kccfqymm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdppavo.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmyowel.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhsofcv.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcthlnsa.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2qxplbufz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcwvsbs.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqyqpsk.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwphblm.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lipgbysd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2qywnpcvd.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zytjqrck.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvptwge.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnpnxok.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2buqsadfl.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjzrbpk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhdpnfv.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfreoca.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpffwmya.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xiauopxg.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2eayhjcov.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2kouigxun.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwtunlu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkvghha.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2llpxcsox.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjnhvyb.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2popuiacq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbqhfup.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2knajelka.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2byohsqmg.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dxptfrqp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dugjyjht.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrxrars.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nurxwmuz.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbakjdi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2utwqzxel.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2hagqwcun.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgaazhe.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2luyizige.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2swujlnjc.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2irwmxyoq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhysexr.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oafmgdmt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2iffwhvfu.html


<!-- 参考信息 -->