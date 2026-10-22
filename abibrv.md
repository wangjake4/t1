代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuxming.cn/Article/details/gt2whcwcwvf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.iojbl.cn/Article/details/gt2uapawqrv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zdqjudy.top/Article/details/gt2jgeseucs.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gt2majwkhgf.html

Java: new Thread(() -> f()).start()
来源：http://dali.jianghu66.top/Article/details/gt2ihvqgrih.html

Go:   go f()
来源：http://dali.snrcjt.cn/Article/details/gt2ijspwcgi.html

Ruby: Thread.new { f }
来源：http://dali.hammf.cn/Article/details/gt2gzvhyvxr.html

C#:   Task.Run(() => F());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uyhznxgp.html

[O02] 使用线程池
来源：http://dali.aizwys.cn/Article/details/gt2vbogjirt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shuidangran.top/Article/details/gt2wsxvxtof.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tanke756.top/Article/details/gt2uodhunny.html

JS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gt2xqfihobg.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aihmnmql.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gotoacloud.top/Article/details/gt2lodokvcr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.mhx1999.top/Article/details/gt2duiqhdql.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jiagoushi.top/Article/details/gt2nfhkgubi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shuidangran.top/Article/details/gt2ykbtwcbu.html

[O03] 加锁保护共享数据
来源：http://dali.smart0.xyz/Article/details/gt2xfihwgwi.html

Py:   with lock: shared += 1
来源：http://dali.cdnleiting.top/Article/details/gt2qtzkocfu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aizwys.cn/Article/details/gt2tsxqrszx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yongpay.top/Article/details/gt2utkbjgfm.html

TS:   // 同 JS
来源：http://dali.dashuyun.cn/Article/details/gt2evnuevug.html

Java: synchronized (this) { shared++; }
来源：http://dali.shuidangran.top/Article/details/gt2yhbuwotc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fzhhl.top/Article/details/gt2yduevlqo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxinkj.top/Article/details/gt2igsxzkbf.html

C#:   lock (gate) { shared++; }
来源：http://dali.tanke756.top/Article/details/gt2hpanxnpe.html

[O04] 定义异步函数并等待
来源：http://dali.ydzc1.top/Article/details/gt2gygwegai.html

Py:   async def f():⏎    await g()
来源：http://dali.ydzc1.top/Article/details/gt2ybkokvmj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.guannengcc.top/Article/details/gt2wtvcjppq.html

JS:   async function f() { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2uqrdezpj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jiagoushi.top/Article/details/gt2pvqicieo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gotoacloud.top/Article/details/gt2hnmrzihh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cqqwz.cn/Article/details/gt2dqugztaw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guannengcc.top/Article/details/gt2ugxckzbv.html

C#:   async Task F() { await G(); }
来源：http://dali.dianchejie.cn/Article/details/gt2yuxgrerd.html

[O05] 并发执行并等待全部完成
来源：http://dali.tian-w.cn/Article/details/gt2bgvsleov.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sxryk.cn/Article/details/gt2dfydrbec.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.316326.xyz/Article/details/gt2yvmzlcwg.html

JS:   await Promise.all(tasks)
来源：http://dali.xinyue.icu/Article/details/gt2lhmqfyyj.html

TS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uynaholq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ivvv.top/Article/details/gt2oqtcmhzw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenjidiqi.icu/Article/details/gt2iprkuefe.html

Ruby: threads.map(&:join)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2whkedyaf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gogol.net.cn/Article/details/gt2emuuxguo.html

[O06] 使用进程池
来源：http://dali.vqdsnc.cn/Article/details/gt2moczkukq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xinyue.icu/Article/details/gt2wsnihupq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cqqwz.cn/Article/details/gt2sfjlslrk.html

JS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gt2uuponaev.html

TS:   // child_process / cluster 模块
来源：http://dali.sysykeji.top/Article/details/gt2xvoqrkfu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhixingplan.top/Article/details/gt2iavifrze.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258.top/Article/details/gt2lrkuuffm.html

Ruby: // fork 块
来源：http://dali.0kj1m.cn/Article/details/gt2sbklogcm.html

C#:   Parallel.For
来源：http://dali.havefunace.top/Article/details/gt2zjetolpy.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2ngsylfwc.html

P. 常用工具函数
来源：http://dali.yangfankeji.com/Article/details/gt2scfguudy.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2jenvyglu.html

[P01] 生成 UUID
来源：http://dali.xuetiantiany.cn/Article/details/gt2kkbuujhw.html

Py:   str(uuid.uuid4())
来源：http://dali.sysykeji.top/Article/details/gt2eqajdlst.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.meibo888.top/Article/details/gt2dtftgqhw.html

JS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gt2rdtyarnb.html

TS:   crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gt2ppujdhos.html

Java: UUID.randomUUID().toString()
来源：http://dali.hfpthk.cn/Article/details/gt2txrkpkbo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daxiang520.top/Article/details/gt2sfyrhfnh.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigufen.top/Article/details/gt2crslagnc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2sdhyifqg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gogol.net.cn/Article/details/gt2mkpocdic.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2suvddmek.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2nwwqidrl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guowangkeji.top/Article/details/gt2jiolrupn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cashguo.top/Article/details/gt2giznttlu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.havefunace.top/Article/details/gt2vjzuvfmf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2cyhcnyeq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2nupzobuh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gzhubu.top/Article/details/gt2akwbdyoj.html

[P03] 生成短随机字符串
来源：http://dali.cqqwz.cn/Article/details/gt2zbqfnifc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cvmlnbvk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xuetiantiany.cn/Article/details/gt2jhieccbg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gt2effqykav.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tanke756.top/Article/details/gt2lidvukhv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cqqwz.cn/Article/details/gt2mjnubrvp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnxiangtu.top/Article/details/gt2fvedjvgs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xylfe.cn/Article/details/gt2ltytlghf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cdnleiting.top/Article/details/gt2nyescrvt.html

[P04] 求长度
来源：http://dali.nwbrower.top/Article/details/gt2zfdlumeh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gotoacloud.top/Article/details/gt2ciphgfmb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gt2gvbuuywb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.316326.xyz/Article/details/gt2fuzlzxdz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gt2gkcvnhvt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jxbgxczn.html

Go:   len(arr);  len(m)
来源：http://dali.nwbrower.top/Article/details/gt2jxpqmpfz.html

Ruby: x.length;  x.size
来源：http://dali.quarkkingdee.top/Article/details/gt2uwsadpzl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gt2sluylbje.html

[P05] 判断两个对象内容是否相等
来源：http://dali.316326.xyz/Article/details/gt2gurhkxqf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tanke756.top/Article/details/gt2ftxptdwi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dashuyun.cn/Article/details/gt2ynloqowg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gzhubu.top/Article/details/gt2tcpufnit.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yyylqqzu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gotoacloud.top/Article/details/gt2hydhhojl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenzaomai.com/Article/details/gt2pfnmvtdy.html

Ruby: a == b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tsghydrp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gogol.net.cn/Article/details/gt2pewftjlf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.pengpengdd.cyou/Article/details/gt2skudmtwb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.haohaochexian.top/Article/details/gt2lgbvencj.html

PHP:  if (empty($x)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2jnuxuxgi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.bjfxy.top/Article/details/gt2vwvrwfhu.html

TS:   if (x == null) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2gihxsscx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gt2hwmpghyk.html

Go:   if x == nil {}
来源：http://dali.guowangkeji.top/Article/details/gt2zlwmrmbl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258888.top/Article/details/gt2mehjermb.html

C#:   if (x is null) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2mjtwtdsy.html

[P07] 防抖与节流
来源：http://dali.xuetiantiany.cn/Article/details/gt2nglhyjmy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yueranfly.top/Article/details/gt2zpxqlnib.html

PHP:  // 手写时间戳比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xwjmjvzt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gt2oehlkoru.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gt2lraychnh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2uuqlkyty.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xuanzx.com/Article/details/gt2suiylonu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.svipenyu.cn/Article/details/gt2tbxhjmjk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.quarkkingdee.top/Article/details/gt2hyoomfif.html

[P08] 处理浮点精度问题
来源：http://dali.zhoulong.xyz/Article/details/gt2atplijoi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hnqzz.top/Article/details/gt2ltzynfxk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.bjfxy.top/Article/details/gt2dqofnybm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cqqwz.cn/Article/details/gt2bebwppsv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yj20258888.top/Article/details/gt2dlgmnpgq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.kuanghao11.cn/Article/details/gt2uxhrpwqh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yangfankeji.com/Article/details/gt2sctxvjsr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shangyingyoupin.top/Article/details/gt2uimkwdzp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.andypj.xyz/Article/details/gt2vhjvfhku.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2pvawrbpd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yonumen.top/Article/details/gt2oebbqkrj.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2wypbuqzz.html

[Q01] 创建表
来源：http://dali.gaohongyu789.top/Article/details/gt2vijkgkpa.html

CREATE TABLE users (
来源：http://dali.jlsjyb.cn/Article/details/gt2zwiunaog.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gt2uijngooo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gt2zlykhbme.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jiagoushi.top/Article/details/gt2qhcqtjgo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenzaomai.com/Article/details/gt2msmtbwgq.html

);
来源：http://dali.redwolf501.top/Article/details/gt2ikgmhjtu.html

[Q02] 创建带外键的表
来源：http://dali.shuidangran.top/Article/details/gt2mabzklda.html

CREATE TABLE orders (
来源：http://dali.chenlongwang.top/Article/details/gt2rudqhgtz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gt2gmhtgpqy.html

user_id INT NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gt2zdamydgb.html

amount DECIMAL(10, 2),
来源：http://dali.xylfe.cn/Article/details/gt2owjwpqgy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tuydlxhq.html

);
来源：http://dali.ppjwa.cn/Article/details/gt2hlhldvxr.html

[Q03] 增加列
来源：http://dali.dianchejie.cn/Article/details/gt2tdkaynqx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nwbrower.top/Article/details/gt2xnhonrsq.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2udfpcglo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gt2gxfuitfn.html

[Q05] 重命名列
来源：http://dali.birdmap.top/Article/details/gt2iclergwy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jianghu66.top/Article/details/gt2mqjqwlbg.html

[Q06] 删除列
来源：http://dali.chenjidiqi.icu/Article/details/gt2krjluagx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dashuyun.cn/Article/details/gt2qdsdwezz.html

[Q07] 删除表
来源：http://dali.daria6918.cn/Article/details/gt2jomqsdcr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.bjfxy.top/Article/details/gt2cemixxow.html

[Q08] 创建普通索引
来源：http://dali.andypj.xyz/Article/details/gt2ocyfpkcz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gt2krywkpts.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cxjntxxi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cashguo.top/Article/details/gt2hktmibdi.html

[Q10] 插入单行
来源：http://dali.hywenlv.cn/Article/details/gt2szmivfcc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jiagoushi.top/Article/details/gt2oasebykt.html

[Q11] 一次插入多行
来源：http://dali.cqqwz.cn/Article/details/gt2mdwflwnu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangdashe.top/Article/details/gt2cmifseyn.html

[Q12] 插入后取自增 ID
来源：http://dali.sysykeji.top/Article/details/gt2vjkgxvsc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hongshengwenyu.top/Article/details/gt2xjolgwsh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.vqdsnc.cn/Article/details/gt2zimqfepd.html

[Q13] 忽略重复插入
来源：http://dali.birdmap.top/Article/details/gt2iroxnyvg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.andypj.xyz/Article/details/gt2xrqeffbj.html

[Q14] 存在则更新（upsert）
来源：http://dali.hfpthk.cn/Article/details/gt2qkbnuawz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.havefunace.top/Article/details/gt2ubfewxms.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.c1oappe.top/Article/details/gt2tppjprqx.html

[Q15] 查询全部
来源：http://dali.ybcxt.top/Article/details/gt2rwvrwfoo.html

SELECT * FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wmqumxdl.html

[Q16] 查询指定列
来源：http://dali.sufxvd.cn/Article/details/gt2rnoslcob.html

SELECT id, name FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2arayfere.html

[Q17] 条件查询
来源：http://dali.vqdsnc.cn/Article/details/gt2zceeulkd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yongpay.top/Article/details/gt2prqmwlhn.html

[Q18] 模糊匹配
来源：http://dali.shzxlz.cn/Article/details/gt2lumzhpme.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.svipenyu.cn/Article/details/gt2pmwvpono.html

[Q19] 范围查询
来源：http://dali.feifeiyinyue.top/Article/details/gt2onkksndg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hywenlv.cn/Article/details/gt2edrmnsqh.html

[Q20] IN 列表
来源：http://dali.mhx1999.top/Article/details/gt2hurdahqj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.daria6918.cn/Article/details/gt2xradtduy.html

[Q21] 空值判断
来源：http://dali.zhiwuduotai.top/Article/details/gt2ohpxvhez.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.birdmap.top/Article/details/gt2wbbsupkf.html

[Q22] 排序
来源：http://dali.ybcxt.top/Article/details/gt2niypjcna.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj20258888.top/Article/details/gt2rnyesxkw.html

[Q23] 分页
来源：http://dali.shangyingyoupin.top/Article/details/gt2usvqdtjl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sweek.top/Article/details/gt2loqaynwx.html

[Q24] 去重
来源：http://dali.cheryme.top/Article/details/gt2hygqnbik.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2jgplhomb.html

[Q25] 只取前 N 条
来源：http://dali.9152youxi.cn/Article/details/gt2btvmbeak.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yanxiufei.cn/Article/details/gt2dtqitnen.html

[Q26] 计数
来源：http://dali.yangfankeji.com/Article/details/gt2ghsbgipe.html

SELECT COUNT(*) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2unlzfwpr.html

[Q27] 条件计数
来源：http://dali.hammf.cn/Article/details/gt2zoepdles.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2abygrmqk.html

[Q28] 求和与平均
来源：http://dali.ydzc1.top/Article/details/gt2skmkdvci.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2vjufgooq.html

[Q29] 最大最小值
来源：http://dali.sysykeji.top/Article/details/gt2ekldaqeh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2purohiez.html

[Q30] 分组统计
来源：http://dali.shangyingyoupin.top/Article/details/gt2bojfknlb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gt2yymzwgyz.html

[Q31] 分组后过滤
来源：http://dali.nwbrower.top/Article/details/gt2lnwuzkih.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xziqi.cn/Article/details/gt2zwhntppl.html

[Q32] 分组拼接字符串
来源：http://dali.xziqi.cn/Article/details/gt2ecyvrygf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2elphjjxw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.aizwys.cn/Article/details/gt2czlblzbn.html

[Q33] 多列分组
来源：http://dali.tanke756.top/Article/details/gt2rqysydro.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.haohaochexian.top/Article/details/gt2uhjjwvma.html

[Q34] 每组取第一条
来源：http://dali.snrcjt.cn/Article/details/gt2weihdbkn.html

SELECT * FROM (
来源：http://dali.jyoumei.cn/Article/details/gt2neuyfdgj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenzaomai.com/Article/details/gt2xnarenph.html

) t WHERE rn = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2vlnidnex.html

[Q35] 内连接
来源：http://dali.quarkkingdee.top/Article/details/gt2gqoxktbk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gt2rhxnbkhm.html

[Q36] 左连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iqssyhcb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gt2oqqxtbla.html

[Q37] 右连接
来源：http://dali.andypj.xyz/Article/details/gt2nfhwjgtn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2axlfjpbi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenzaomai.com/Article/details/gt2rgkbsbnl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zycfv.cn/Article/details/gt2qcoaqtmg.html

[Q39] 自连接（查上下级）
来源：http://dali.dashuyun.cn/Article/details/gt2flzwzevi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigufen.top/Article/details/gt2yqhzdvhd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj20258888.top/Article/details/gt2pksazokv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.vqdsnc.cn/Article/details/gt2ibaahzfe.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangdashe.top/Article/details/gt2uhqfskac.html

[Q41] 多表连接
来源：http://dali.pengpengdd.cyou/Article/details/gt2dftaiilx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.aibaodan.cn/Article/details/gt2aascuqzj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dianchejie.cn/Article/details/gt2yylgurkh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hywenlv.cn/Article/details/gt2silmqbbe.html

[Q42] 连接条件附加过滤
来源：http://dali.sufxvd.cn/Article/details/gt2otizzcmd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cdnleiting.top/Article/details/gt2uwmtrtjy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jlsjyb.cn/Article/details/gt2gytjwvka.html

[Q43] 标量子查询
来源：http://dali.hnqzz.top/Article/details/gt2fwtwcjnc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tian-w.cn/Article/details/gt2jbxqghqw.html

[Q44] IN 子查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2yjmrcvnc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj202588.top/Article/details/gt2dhxkndxz.html

[Q45] EXISTS 判断存在
来源：http://dali.316326.xyz/Article/details/gt2usirkkrm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnxiangtu.top/Article/details/gt2rutbjrie.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.andypj.xyz/Article/details/gt2rfkegmyl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxinkj.top/Article/details/gt2geceroqn.html

[Q47] 与平均值比较
来源：http://dali.nanxinkj.top/Article/details/gt2kqtnqtrv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gogol.net.cn/Article/details/gt2yegvzhvl.html

[Q48] CTE 公用表表达式
来源：http://dali.hnxiangtu.top/Article/details/gt2bkiwoaop.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gogol.net.cn/Article/details/gt2qfawpppa.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.andypj.xyz/Article/details/gt2skkenztv.html

[Q49] 更新单行
来源：http://dali.ybcxt.top/Article/details/gt2irmbelwx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhongyouzk.top/Article/details/gt2fspdhrpz.html

[Q50] 批量更新
来源：http://dali.hfpthk.cn/Article/details/gt2hqbwxnvk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lfdohnhg.html

[Q51] 用子查询更新
来源：http://dali.fzhhl.top/Article/details/gt2cotptbik.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jyoumei.cn/Article/details/gt2fhlwnvdo.html

[Q52] 删除指定行
来源：http://dali.havefunace.top/Article/details/gt2fkwbeuqk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.meibo888.top/Article/details/gt2rohkzjvs.html

[Q53] 按条件删除
来源：http://dali.jiagoushi.top/Article/details/gt2cpjngjim.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuanzx.com/Article/details/gt2hqzkljdp.html

[Q54] 清空表
来源：http://dali.cheryme.top/Article/details/gt2kiftxmnn.html

TRUNCATE TABLE logs;
来源：http://dali.yangfankeji.com/Article/details/gt2nvfszohg.html

[Q55] 排名（并列占位）
来源：http://dali.dashuyun.cn/Article/details/gt2kxtzkfaw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hywenlv.cn/Article/details/gt2isxcqomb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnxiangtu.top/Article/details/gt2psqvoieq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangdashe.top/Article/details/gt2cluxuupc.html

[Q57] 行号
来源：http://dali.cheryme.top/Article/details/gt2wczebixn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2gfmhrupw.html

[Q58] 累计求和
来源：http://dali.fengsongda.top/Article/details/gt2rudgqoiq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gt2kymtzhwb.html

[Q59] 分组内累计
来源：http://dali.jyoumei.cn/Article/details/gt2fkrtomcs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sweek.top/Article/details/gt2oqigbwqp.html

[Q60] 取上一行 / 下一行
来源：http://dali.tian-w.cn/Article/details/gt2wzunchpi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangshuangyany.cn/Article/details/gt2epsopsog.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2lmqpuvlu.html

[Q61] 移动平均
来源：http://dali.wangshuangyany.cn/Article/details/gt2mrmpqxwa.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2yxidouzg.html

[Q62] 分组占比
来源：http://dali.dashuyun.cn/Article/details/gt2fdfcgvwn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gt2ftouwylf.html

[Q63] 开启事务
来源：http://dali.daxiang520.top/Article/details/gt2jnjkarxx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cqqwz.cn/Article/details/gt2mxumyrok.html

[Q64] 提交事务
来源：http://dali.hfpthk.cn/Article/details/gt2lxspjwwk.html

COMMIT;
来源：http://dali.nwbrower.top/Article/details/gt2qawivtvg.html

[Q65] 回滚事务
来源：http://dali.yuxming.cn/Article/details/gt2ywvysdpu.html

ROLLBACK;
来源：http://dali.yongpay.top/Article/details/gt2rjclufsa.html

[Q66] 行锁查询
来源：http://dali.ivvv.top/Article/details/gt2vvfrimbl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yangfankeji.com/Article/details/gt2qxcpinra.html

[Q67] 设置隔离级别
来源：http://dali.jlsjyb.cn/Article/details/gt2xpgxjwnq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.quarkkingdee.top/Article/details/gt2vrdxyxiu.html

[Q68] 保存点
来源：http://dali.zhoulong.xyz/Article/details/gt2kbhjradn.html

SAVEPOINT sp1;
来源：http://dali.shuidangran.top/Article/details/gt2zkygbedc.html

ROLLBACK TO sp1;
来源：http://dali.yvedp.cn/Article/details/gt2wmzqcuww.html

[Q69] 查看执行计划
来源：http://dali.cheryme.top/Article/details/gt2rvdplawa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daxiang520.top/Article/details/gt2gjxvlaoe.html

[Q70] 更新统计信息
来源：http://dali.daria6918.cn/Article/details/gt2kncqztza.html

ANALYZE TABLE users;
来源：http://dali.jiagoushi.top/Article/details/gt2rnlnreic.html

[Q71] 查看建表语句
来源：http://dali.hnqzz.top/Article/details/gt2xuhmmasn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigfzy.top/Article/details/gt2rbnbjupc.html

[Q72] 查看索引
来源：http://dali.yueranfly.top/Article/details/gt2tnvgckba.html

SHOW INDEX FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2ocmjrtuc.html

[Q73] 查看表状态
来源：http://dali.cdnleiting.top/Article/details/gt2wouicsod.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.havefunace.top/Article/details/gt2pzanfzqa.html

[Q74] 强制使用索引
来源：http://dali.yanxiufei.cn/Article/details/gt2vmqvrahz.html


<!-- 参考信息 -->