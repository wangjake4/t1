代发 wailian999

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbfoofp.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2bblaytms.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kqppdmwr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2yqktmldr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuwvgsr.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pauzkdpf.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzmdjyp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnyhgae.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqidtwbp.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkfnxoo.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vsglkuve.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlayptt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2kbamvegt.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhxaail.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekursfuh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2enybeioa.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nykmipsv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjvyxfw.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuufubc.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2nviqubbt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2blatdahd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2rcufxvte.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwrupuv.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnztdysb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhqedvf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2anxyoxey.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvlaxsq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmndgup.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kutsldzv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2yajdtkzd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2egqkkxss.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvepdhx.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2lymatbwk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbxqgoi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2zceipdpx.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2moqzeqlf.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdlnbva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgurpbd.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qezuktcn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wthwqwlf.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjcmaug.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuffeas.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbbdgol.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuwrpmh.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dacuqazx.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmztfmn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjipgqy.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qheindvg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpaehcad.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzdvtat.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmgdogs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzflbyls.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2veneiotl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2fyeppyex.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2baggsdcp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqggitv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cykskelg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2unmtlwnk.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxxasxn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2usphqxmw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2uybaaxdl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpvufha.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpzksot.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2epczjurk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxvjdqc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbhjoic.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvwedvp.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjgixmk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2fubbuqqq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwpcraj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnbnnld.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxirkpo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2uukocaxk.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdtmjco.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxyqbue.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnzldce.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyikblr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbaahky.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2lowcnrus.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqpjqse.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kixskqtu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2zankarsn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvezqreq.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhperkw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxiwkka.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2sniemqmd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzjmnfu.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bisnfztt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmzptrz.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hgiovjce.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2akwezpxh.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcdiebj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzadrdv.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dkptupwg.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wejqbird.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2orghuxde.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbgrymo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwzdnpe.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2excttkkt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiejupbd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ewupisea.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsocisz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cfaoouvr.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2uivxobgh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2euqhrjoz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbwhlef.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhtoghu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfqudnx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2nnewikcx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkaiyyb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2vphcoalo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtvdcmz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhsdshw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwtobxn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzibapi.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzpehzi.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsvxlft.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvafjxj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kogdxggx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsbnxsk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxunlod.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwmgpny.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2cdypsmic.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrnlsla.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlmlywm.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lttfdtfc.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2cuofynem.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2mibjcvla.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wplnyvqt.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2mnomodlv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfpnwdb.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lblwnyem.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2awkdayys.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2bgighnyi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcrruyy.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2gugfyfyd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2djzzarjc.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhpedcz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtrgyfy.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2njqzzpvx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyixqqzh.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfxeuhf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhmmkkl.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2brcbcgqx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mchjwygw.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2knuzsyph.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sghtdlra.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfdthft.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2aajlllhg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2btrarprk.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ftufmtav.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sczckspv.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjgjvro.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuzpspf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmrbxhp.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2oqianxdt.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgocqsdj.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2eyeqlgxa.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmmqumc.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wddaxfaf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzdwspk.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tltyxonl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvzdjsy.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yatjoagb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmlptld.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmtfuqc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgbfecf.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmhrxsf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xldwmhql.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2asbupwqu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmifclia.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwwbzur.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2bblrfhlh.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mecasrmu.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bginfnwe.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pexfmeki.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2wxezcipt.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2eetbfhev.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qepoxnua.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xiisjexx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pplayiab.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvamhvk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjhchih.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mncnktxb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2afiaoszn.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wuacxtfl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiabkbgs.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cnykmvus.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtijmyqx.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lfujixgu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtfersl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfxptkk.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkdhbmi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2faznehft.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkvjloc.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2sktmwisi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ggssybyo.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2naecggra.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hvawrmwp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrfncwf.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzdjxvq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpwbmdl.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkwmqkd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtazqbn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcbaeoa.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyjersl.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2srrjesmu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2wlidadfm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tptdyfef.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsblkjnz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzcubpk.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhvlflf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2lxihpwbz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2njgpiptb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2umxdemdj.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsebvme.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2bxoqmyzg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpnfasx.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsuwlsj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2rixzagaq.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdyttce.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2dctzvhuc.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdygcdn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbslltpz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzfktls.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfnzhcs.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vsoazsek.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2yomrwpfh.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2btcbozia.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2opiunxwb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtafrit.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2jcocgxlk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlalfltn.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2spaewmoo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2reeljkha.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlqottb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxokfszy.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhgdfbg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzuyleu.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhnnckr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hevfyuzn.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrurnbu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2avvyerdi.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdygrfxm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdualmc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbndbtv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvwadom.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrknnlv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiurgnpl.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrhiyhv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygashtbp.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2objssnbn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiciihxm.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ubejgntl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2gcynktqz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fktrbhdx.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ltizselu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nstmmmip.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2eannicaj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkyzynk.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkpcnty.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qgesbwkt.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxfvkgo.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2njbzkpjx.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2oyaxojyy.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbmsqlm.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2merfbhrc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2losnuilj.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2dmintfva.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyqmtgw.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmmogaf.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuflzhty.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kprgconz.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmdjssy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlkjosa.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2eplzlgpt.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xafrvnfw.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzlayqn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ybldltex.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2alqawfhw.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckoihdmj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2uypreptj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pgefkfxc.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgfcgfi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvrrvtd.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ixklxjrl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xeghwssh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2kznwsewd.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ixadhbpp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2npikbdeo.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2sastkvqv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2bdibulmm.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2atopxens.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyofkgj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbxadjk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2kirsyuqv.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2aflomisx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2otcykpvp.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2imrmgvba.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfesxbm.html


<!-- 参考信息 -->