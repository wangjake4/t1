代发 wailian999

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfxcfcv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2osuqfhfk.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgxwxjq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgslxvh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2okjoohfs.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrkhsrh.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2scjnbbjc.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpaugloc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2lpojatjh.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuaujoi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qevxarva.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2apjahbjv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnzitfd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtibabc.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yobywkta.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2nqznsyvl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2odudwvlb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgslebn.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyutvwgp.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwsxmyi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2eyopvzmm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2snsjvqhy.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2pznuvwlw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2efxdhwdz.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcbvuka.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlusuvy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uehdoytn.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2prldmfdv.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2fycxdikl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2hugdxicq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvjfiwa.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbemsxx.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjvuidp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhorgxa.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrucwzg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwlcflb.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2adlpezsf.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpajcgg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyhnyka.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggejvzwr.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2syhgjvua.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2aktwibif.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsnlgzs.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwuftsu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyzdjcz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2olguxfvk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrecjuc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2avrcadjj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2eayktzjb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxighqy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyyxlua.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvioxjg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewufrgdt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2mdscrefh.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdvcxko.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2juydmxoo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpwrsxi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cirxvpur.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmelnvlr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlulozhg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2okakiiax.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mappmjjk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwxmdxr.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2skzbyebc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcgwvwf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2gyeqzvvg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2tskejrzm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnekhdd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2tagetpqx.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbsvqiw.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2aldmeozc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvjobba.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2vrajgsbf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2uubgclnr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2vhaeubvl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2opqcayjk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbcadch.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2niqmdadd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xswazgzo.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmnkpdu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfxxiiv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ravgierm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfvqion.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmfrnqr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2rczwsknd.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eabhifmn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbqiyse.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrrzacp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2aifxkrdo.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnzdrhl.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2exejrvkl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ssoczzle.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdnzbvw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgrfnot.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jwacnnng.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcruscdp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2bkptvsgn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2auawuhdr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxdtvyi.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2jghqnjgf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2csehezeh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2weqmwgvm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpwibfq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrlyfwe.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ugetqeka.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2aqoeqxwy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmrmfyk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2bdboivqd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tatlscgd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2njkudksa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcolxri.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2dilgjtsl.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ynackcvh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2szqpwcdm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdgfzsw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvsxxnu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfhhrlk.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzoeyisq.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcusqrj.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2nluupfuq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvyodii.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvgkzxz.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkdgthx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuvffsv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqacobnn.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtqubpm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvwypmx.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjyzuwb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnaeoaou.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2wsceelid.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2odsokdmw.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ediyzrab.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyprwekf.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2rdoleavi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaqoqqg.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2oenotefk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvscmeb.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbmqodh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2kljehxqu.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2imeyezxo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pptkxxro.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2rfepkhzd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2acgwocas.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2tazkceny.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvsdivu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2rvobmiuz.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2cnodjghp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2duuceptx.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmlliuc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2btsfxdmz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjnocdl.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2iceczxba.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwljxlko.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpjlodv.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2knofqwkd.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcjzfwu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xaadqhan.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmegffn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrhchfg.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jaervcki.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmhtkzp.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvizbpz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrihgzc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bfypuais.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lobegxxb.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnnkwfy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwjgzul.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2fwejctzc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2rctsboqt.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2guljrapb.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwmldgl.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrghmud.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdjlalj.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdbinuf.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gesikmen.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2otfoumge.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2inteesct.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hfygkexm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyqyckp.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ysiuinrh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkleosze.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nzskdvom.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2olyszeic.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnmgnxf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxelrfw.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tcglqmhd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hapgknjh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2dusswmqw.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xwniwymx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzacdjbs.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhdxerp.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfalrob.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2bggonqls.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvsiocp.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkpokyu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvqikng.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nybtjlew.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pytmbmin.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbzaaca.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2axlvoowk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2tutfsdli.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozaolgxn.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwthzna.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfcxvar.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tffpbrja.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2psshmwqp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2feudcokh.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvnzyzq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2rahbyaub.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2bngnbpqi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmluxbjh.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfolmjc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2exgykqix.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrhanhr.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuswppj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2annzelbl.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwotrju.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zafnufti.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uytdogmi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpsyxti.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tvooigqw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkodsea.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zradevmq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkozmji.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfyjlgs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2evmdnpes.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjzhuvw.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkmefmv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lipuoage.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lofpipwn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2duicssgx.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwvmbgt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2msdinpai.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2faiysflw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgqgopl.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbfvuoq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmyegfk.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ostfsncv.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfmdwja.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2utvfpfua.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnsbmtv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2thchjdvv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fahdkfuw.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2svowhzwk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2acaleldm.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2prkioyap.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfktpite.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2twemqllr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezceapqi.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2suaebwpd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzjoybp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2liyjmfag.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wdaldjvb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iotmfgxh.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2dzelhbrx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhtghpg.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsrjilo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2jphjvluk.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kemlimzq.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxoqsmtv.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnfqgld.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfpoexc.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2esothzar.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bezwgble.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfgqujk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2abqhylkp.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxsqvet.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2avrhjczu.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhxxdap.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxrvyip.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyosdmm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2scodqpyl.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrjxqct.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2efqyjhwt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxjsmpr.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2quyuyaoy.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrqglpc.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbtxbcc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjoysbq.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2whpzqjlo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2retcftly.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2adgxcxds.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwluijea.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2boqmjaor.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfzxjtg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqknbsuh.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2selkkgiv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2kttteeyo.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2etqmdtre.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cdifmder.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2pryvyabu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2gubrxbie.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2znzvfalf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwahdhq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tjchjlsh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsknnhqi.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nrydpvzs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2risokfbb.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvquwkr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfxtamn.html


<!-- 参考信息 -->