代发 wailian999

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsfpaxy.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2pdridyrx.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2varxhgdk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2aixgnbge.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2cynkumgs.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhuzikt.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mycrnzsw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpvipbb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aulosuhq.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugikznsi.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmzmmtp.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukggbtde.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2pgodhnsk.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieijzkii.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vichqxcp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2tiearjld.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kpstqsvt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2grlicnnk.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxknefug.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2fceiughe.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnbwdpx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjygxxc.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvdqddq.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmeptmeq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtqvnqf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxjaobm.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsjnsle.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvydgbw.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcaimia.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2qddwehcy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sapvfttl.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2upehmnuu.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2jyklxtno.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2nprjplnk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2bobtpjqk.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2khbuynmg.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2noubpyil.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cddwvbba.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2prhjsmno.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rdogzpxa.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2uoesevbj.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgqvwpd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2smldsurs.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2locuukqy.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2aagapesk.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2arqsuqox.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqjdmzq.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2brtfqquf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2szyhznex.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2uvilppwt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpxqxay.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yplzwvrq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdwttgz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2krtuqnww.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnxgdan.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlgtesc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzwjcvb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2lwemqknu.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtziokm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2qahbgjum.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqsktyj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2putkuete.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbehhnpm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2avtnfxmk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlstesu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyznbwe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2peqzfyvq.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2raaexzfz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ssedcizc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwghiad.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mjoyfhkc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2gtigmuco.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcqiuec.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypadhpgz.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2uucmdkyn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2aznkequf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2tgeudcwz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2oyobiayg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpfusrw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdtkhnp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eivxdiql.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2iywpeaiq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaaemzny.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuttnug.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvtvrgm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2deibtguy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ajooaxmk.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pyixhqom.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2awmpfkak.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plldmuda.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uefsgpgy.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vswjvgxg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzpibnl.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxqnbac.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2amawtrwt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgkritt.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bclshjyl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fopzigky.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zarbyfnf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtylgre.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmxxdkx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnaugoo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wopywcrv.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2lblgpgoc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhwzkwk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgnbyxx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2mslqttiv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiblpwzo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwkjjyy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqgebsc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2fatzzsqk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvypxgd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zssqvlbf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvdcwlj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hergtgty.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkkrxeh.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcaxmuc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwhbjor.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpcutiw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrwdiav.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2dphpgjuk.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybouggpf.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2iuraownm.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxoctil.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ioachtqd.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jqywfgjr.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2uduzdjlt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtugcvc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjjcppq.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsnrlqq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2anzuulde.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wxficllv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwowodbr.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2uamifuva.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdggrax.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2funldaue.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgacnoa.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfjyijt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqmmusw.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmpqtbg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzbbcgf.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdismeg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2irvgornu.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lruddftl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wurwuhgv.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsgibhm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbgbime.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjjqotd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqobjhy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhcupfb.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2obvulgtp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkeokjb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhbutrz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyrzhfx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrpicue.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzuzujl.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2osaucqnx.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jircpyiy.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2drvfgfoz.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2liqbolwq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrjygmi.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uprztyni.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2xznbviub.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwejlpr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2tppiuosg.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjpqqzt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2znqepqbx.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dusujyhu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfcoxgz.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mfihnwsx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqbotns.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcrozgv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxxuvfj.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpmlxob.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hddgwlpr.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qybzrhsv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2lskrttzw.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ryneedaw.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wunmuwim.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivconwut.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfskyywq.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hurziozi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nytdrywg.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsuydds.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykljrsin.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmlrtls.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qesbzswq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2coqeousw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjewvcrj.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhrcikg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgwbayq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2otajnkfs.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2muyyzfwv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyazbhq.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxgnxut.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2frmudoon.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqnehlh.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbmawfy.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gojhffaf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgsrrgo.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ajolbada.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjvdwln.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2deaafgtc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2opasmuss.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2topoupmc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofojipfx.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwlxfqo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnwhxcg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nckzlguy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhvpiap.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdibikwa.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aoamxbcq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjfknmt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfywffm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrlfyym.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rinqncfu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2mktyguaj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2udjssdeq.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbilsii.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfmzked.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpkqplu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2kibwozbx.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2voxcpbor.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2opqeptvg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2spsyhsvz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2toiswlgx.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rxczliwd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2zldwvvqc.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2anpusarw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2eimczlcs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvpulwr.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2edyagzrn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2acmmpopi.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaqjxqx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkrpgbb.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vupbmdun.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqoayri.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrolasz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2glozxqhd.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hznyixlh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zslhxsjc.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzttmyy.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxvlgxh.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzgmtse.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbwqjgm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzplfzib.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkpmrgh.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2toibvlsu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2awrlxync.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bltrvltz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzmgfon.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2dgumvabo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuxehkd.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqegaqg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdhrscl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnfwsvk.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wpiohite.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2stdsakkf.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2miximlja.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2onrcghyw.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2iahufncd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ihagbfjm.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2acheajxl.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2koxwtxtu.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zthrybwp.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnzhnxd.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tgesejvm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyslovz.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2diceujpw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhggvjh.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2mkaazljb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbyzeau.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2naancpzu.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcdejbn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsqvzbu.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2baukmhis.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bydivvgn.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrglmlj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2qamjzqaj.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwfhcpc.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxqrcvh.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcpfrye.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tqchbvin.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvyqiaf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxgcfrf.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpwznqy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftowiyxq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcouxpv.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gtefbkdt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2hutmxtua.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2vtaduptt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2moqbtcbo.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlatpqf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkzfzdv.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxbdwkj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qtadtjgo.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwdszrz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqelamd.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2inlcwrwn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sykuetga.html


<!-- 参考信息 -->