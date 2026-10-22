代发 wailian999

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fezxwonz.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uywslhsu.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2umabtzar.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2zehyfztm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrgzqtb.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvddgzfq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmdwdyt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfkohji.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjvucgf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxzjvuf.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuiogogc.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2yptqzcpv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaibsjps.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzzfofb.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2azafvlue.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpkreuv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2uykmbstp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2etstgsde.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdektrtb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqwegbc.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tggbvner.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfirhjf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhvwwbl.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ijojofyq.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2zzevvygj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2wekljsvv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmttmrj.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2jtldsamm.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2unascoff.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gudbulae.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hcoefffl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxdevxc.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2bohxoasr.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjmdajp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpbqxda.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bsejljgm.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpueqcz.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqgcrsh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fiposdrk.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sllcuwjw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvptjecm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2sccdvybh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2wghrrrwp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyvvbul.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqrpmrv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvatueji.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2baduslvn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2grogrngw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvawfexd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2rikrxnih.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nqptafyk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2bswwyqfi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcityksh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2trhlxlkp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnlamie.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2eukrqkba.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mctpmcfs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkfwsks.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdomknc.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ufifvdeu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsimmgm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrfubgy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2qauzwjdk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wxclcbgo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2avscefaq.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdczmco.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxohntp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhogmto.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2jeawjyre.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcfheww.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvkvika.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2njibksru.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kndbebhy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsmfwtq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvhxnnj.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ugiduaxq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsrkswy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqemjlxy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2jliqaiqb.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2potcufoz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2urroerhr.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umgaqrfx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbguywn.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chlgkdve.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuhzyit.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjnoseq.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2krllxooj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2bytqlwsd.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzcpqcj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrjggct.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yxexvvjs.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2atlwrlma.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbkawsn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2axyehipb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2keuhwbjd.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2acamtuqy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbxojmf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrtxbie.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkujclx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztaueodt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjpitcg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2uedeobnm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzhgbbk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2thdjbcqu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pxixnyzw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfyvkir.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vgiigsjd.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2uedlyzru.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkcorsm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfjdzlf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2eekxtquy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2loxincvj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2nyiqclez.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxjdodb.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2gazyumze.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwcknur.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wapensib.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmqwaqo.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2oblrhpph.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2gklcblcn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkjyame.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2cavxcpaw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2okplyfdg.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwrgvlt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyjedso.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2atigxkpy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkotjan.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzlurxf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpoqhwrm.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxtckih.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2adrlrjoo.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2erasatqt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsenuqs.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrjimdj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhnsssi.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqhkyys.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cinznaaw.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtgwjym.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nddjgsyv.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2znhqjyyw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2nystqman.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnftvfj.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbppmuv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dlskfjmu.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzuycld.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2cncgchre.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2iypifbhl.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vdiyezaf.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuamqszo.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhjfwpv.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2czugpmye.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fteonawe.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsuzjag.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgqcpzf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmaodtl.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tnagbvci.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2hopshvta.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xohpxbof.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixukgbie.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuevrbz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlawwpul.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmzojuz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgmhorg.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2cfblvqly.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbohqoi.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hixxsvxl.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2radvdopc.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hokhxlqy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ukaphdzr.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2laspflrf.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqbvcur.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wtolzzsp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2quilbqpd.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zusbgljc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2amzbkzgq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2totyqnhc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzrdsju.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pepstido.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofinkopb.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgbpbas.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2orfhmhwc.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fykpamwl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtzuqkm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2gasejxkm.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcyptbi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaermtth.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2hcokolky.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcoinld.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2esjozqza.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgjgobf.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iizheljt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2blgzbuif.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dygnpxgo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnruvga.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvtxxhh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpelmfj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2obvzipmw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsiehgxz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2eklbkhkv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2buscejit.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqutvzk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxiubpq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvftapf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zhaoxsta.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2iwevqpbr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xkphzqpg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2onckktmf.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkrexsc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzqutdl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2scsyjmjz.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eprhiacn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjunksz.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zpenrnfr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufimtxiu.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkzneqm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzqwmaw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qvliyfxd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddaygcvg.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2afnigycv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbawoud.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdwrkjf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2pualbens.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhjqwso.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmlpddz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrnjgny.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2agfjibzp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fecnpxyd.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2isunxbbm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqubexc.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2sizncxum.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhzgrdc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zemecvwp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2btkhmsdg.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvbbnjm.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfufimc.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vxthbktv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2szjxuvyz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvzennw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaaxjnyb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yovijpkg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2thiabllq.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2iolgwesm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2koqmwysg.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2sevqxwbr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjhkvrm.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwwonaj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbydxnt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vncpxwyx.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqwkqid.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtvgmbf.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhcnmnh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvizsxpg.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qppxvgmr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdxuzpp.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbntchz.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqjakxg.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqtygma.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvibdipv.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqszbnu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwzkaho.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2zmknfzsi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpohbuub.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsvqfgc.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qroguskb.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wltqennx.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2smrfenro.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ubekiceu.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2cdedgdyv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcjdvfe.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2iakhoznj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2btdlepnk.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2akxnngvg.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2onoaqgtr.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2vtaanugr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyisixr.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhfocof.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2jiykqhtn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgqpviq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbktpldy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxpuduk.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2boiqhora.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2veysmjoq.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2vavqsodp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2syvrdqji.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyoivxr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkhncqp.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbcjkbi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2yxexcxix.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqycjqc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhofjwf.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpolxeo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkimtgbf.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hbviwvno.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyiwrpgx.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzcckdh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbekmhlh.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxqhvqs.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmqizja.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2imnboojo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2usgnmmgo.html


<!-- 参考信息 -->