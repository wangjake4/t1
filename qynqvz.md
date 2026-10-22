代发 wailian999

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2jogngbik.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ujaoreha.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvirifig.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjsqgac.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgssaycx.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ispmyfdy.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmbywsu.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2clrtvtau.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2igabxmex.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuroqebm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tivnyksm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2unpmwttu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwkqesq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrjvlmj.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcpjgqa.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgfmfob.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tobdnlgv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2qphjsehp.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmigwqgr.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2isomlsnz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2qevmihpo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2vyauvvrm.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2epsmnzho.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlvpnbn.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqemqkm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2brvsdcmq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tunqxwhl.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfetwaf.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlouctv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2omcxmtna.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzjfdmx.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2engxdapf.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2qslzbrbt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2antfvbxk.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwofqzj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uzoiorvk.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ktshmlwl.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvoesrm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lytirtnm.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vptxeiow.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2puvhmlig.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sfysdzrk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrwruwg.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dpimtdnz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sefpiadj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfwyxdj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzimort.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgvwjqx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbmsfga.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxgcbhl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdmwter.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yurqmzfv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrurraq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2nguxzkrd.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdrqsja.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2cmabecmz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2udrwsacv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhmazdo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmgnvia.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjggjod.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvdnfij.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2clejbumh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xphqezdp.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2onfymfvn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2fdewcnpg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzcmtzt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2redudsrf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2lpydrpdf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcpcjin.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgtdwmg.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgjytws.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2izpqxout.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvkruoo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cxblhcet.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2fopoxcho.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2twroxmts.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaygakuh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2iimbifyv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjtjvcf.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2zprnxnab.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtkzjoj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqajavu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2agieyjru.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mokckkqq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcjrapd.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzdvuyl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ometvkex.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkawtrqv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2uheckwcr.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxgmjtv.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxemthy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpsurnw.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzkumsb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kluaktsn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsivpwf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2riiwdlro.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrizpmy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ehebkmdt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxrneys.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvcxmjb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxgdebl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnfazkx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ilythjzw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlrxozf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbkqrie.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2bupjcnsk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbojgiyu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvwaiop.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lubqdlmr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2irsilmox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dyaofzzm.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmewmfh.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2dakzyfhi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzxwbyt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfqkire.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgxlwuz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2tahtfzlr.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfoujdb.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2iidwagpi.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2jqokwovt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsfxnmr.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrymjuo.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2edainlsr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbkuoga.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2keceyciq.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzhviaq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbadyrju.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2unxthyet.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2obnymkoe.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgoqjai.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2infkzbjw.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwonkex.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugigzliw.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2emehvyty.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gplvurvm.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkonfpk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzntwar.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzmevmz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjggricf.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxcgakf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnodezg.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2fwncpckt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpcrpbj.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2edvhkxbt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2suaaibnv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2okbvelta.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2nespvvrx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdhehoa.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2hytmocry.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbwmfmw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhzbvds.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ndetnnvv.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyyeffq.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qsibscrs.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlapzyr.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ajittnwl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlrflrz.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwtajrt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2mmduttoz.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dgseblsj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2phxdanec.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gosyulge.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2omnalhcn.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2svrfniyp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqixbzik.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aguvalpk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcngqph.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2sqckdtdj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlxeobs.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lmeqikng.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmbqgjc.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2itltmjty.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2xcerwzzn.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjjvmqv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkogfguv.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kavydwxs.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iylrksii.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzidbfj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zugwklzo.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmfyngq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfowdvul.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2quyzobod.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceeaexpp.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyufwfr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytngojdk.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzubveb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vafakwvk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2trclqhwp.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wkntoisn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2oidcgwlr.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ligmzwmo.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvdwgzm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkhyqlx.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkpzyip.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bvihjtyg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwevvmy.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxuhshw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgptfxdg.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kxoitaqw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxcdjvn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2vantovlb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2saowltxo.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvsmdzt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ovucojvs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xplieyyg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2aynhyacb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2atouugnf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvuksua.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2fojgpgqd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2wpuzbwez.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkesoyk.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlqyqvc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2pztgbwos.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzershwn.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2udbsjiae.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhdhiol.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpqglvl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsfyglc.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yivysnnx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mslyyvee.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lhthfzmu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzvpapo.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcurqxq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vowrrwue.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvthhyb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxklywdw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2avinozyu.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ftngntyh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hebkqfos.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdwsclq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqgacwl.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnjzlzd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjgslvn.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2nikzpxty.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnoiwht.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gfquswze.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2blpeygos.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2zslcfqlo.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvrbuql.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztoswuog.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2oksxmoyk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmkyogh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nunzkhnl.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnpclzw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrdzxdb.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnncamk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvdmwie.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2etmxigva.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpxbnhp.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2oxidnutw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2lozcrrne.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkxmacl.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jljuyueq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrqhclz.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvypfky.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcptlvtg.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ctavnwcq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwajcmg.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pgoinqyd.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxchmsv.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcemybu.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wittidgr.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hhszuluw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzgavst.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2njnfvepx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrafbfp.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvjhzrm.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjidfvy.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2psdgdowz.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnuwgnw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2cfykfnqz.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vkiepptj.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2akcnccvu.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2fskljzdo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2etqamgar.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2uykvuuvu.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxckidq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgrmwxh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyrxfnq.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2doixyubs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2uhonqzfi.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyerzqk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxujpwc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyadezo.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dakvmzrd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2dltcqgcn.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2gylssqet.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2rgandosf.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjvriyu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2gozqykgm.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2sghkttac.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2nowflrvz.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfaqqrh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eogkowmw.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrkeetp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2squpsfjg.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbmtvlw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hahnxsbe.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnrzhtb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2upmzfjhk.html


<!-- 参考信息 -->