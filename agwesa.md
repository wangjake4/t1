代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gotoacloud.top/Article/details/gt2wluearai.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.redwolf501.top/Article/details/gt2fwtysnjw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.havefunace.top/Article/details/gt2jneahnam.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gt2qrigqmvf.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnxiangtu.top/Article/details/gt2bohljdoo.html

Go:   go f()
来源：http://dali.9152youxi.cn/Article/details/gt2ttfcstfv.html

Ruby: Thread.new { f }
来源：http://dali.dianchejie.cn/Article/details/gt2kubndqui.html

C#:   Task.Run(() => F());
来源：http://dali.shzxlz.cn/Article/details/gt2ctgxosle.html

[O02] 使用线程池
来源：http://dali.dashuyun.cn/Article/details/gt2kzjrsjmm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jianghu66.top/Article/details/gt2pjwvpbbk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zycfv.cn/Article/details/gt2laqajtti.html

JS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gt2hzzarjgj.html

TS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gt2tsydhdxs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxinkj.top/Article/details/gt2hygwqwvm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuxming.cn/Article/details/gt2sgwkzicz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258888.top/Article/details/gt2bfxcptfe.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.9152youxi.cn/Article/details/gt2ladtyxwe.html

[O03] 加锁保护共享数据
来源：http://dali.aizwys.cn/Article/details/gt2wigiljzf.html

Py:   with lock: shared += 1
来源：http://dali.c1oappe.top/Article/details/gt2twwjpvoy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shangyingyoupin.top/Article/details/gt2sncalgkb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hywenlv.cn/Article/details/gt2lubofzqn.html

TS:   // 同 JS
来源：http://dali.dianchejie.cn/Article/details/gt2hwujlopa.html

Java: synchronized (this) { shared++; }
来源：http://dali.ppjwa.cn/Article/details/gt2qimfvifn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.feifeiyinyue.top/Article/details/gt2vlmvlcab.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sufxvd.cn/Article/details/gt2tqevbtyg.html

C#:   lock (gate) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gt2wcdgxcup.html

[O04] 定义异步函数并等待
来源：http://dali.zhoulong.xyz/Article/details/gt2cztyvuqb.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxinkj.top/Article/details/gt2jqhsfhjr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ydzc1.top/Article/details/gt2qjpohtvi.html

JS:   async function f() { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gt2tnpswdhd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gt2ottzaeva.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhengqikj.top/Article/details/gt2cwsyuqyq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sysykeji.top/Article/details/gt2zqrigsgw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tianlin.xyz/Article/details/gt2foqevwvu.html

C#:   async Task F() { await G(); }
来源：http://dali.hfpthk.cn/Article/details/gt2oeoicdac.html

[O05] 并发执行并等待全部完成
来源：http://dali.yueranfly.top/Article/details/gt2eyqbomkt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenzaomai.com/Article/details/gt2xjiylsbw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gzhubu.top/Article/details/gt2yygdgfex.html

JS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uqzsjigb.html

TS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gt2jwsxaifd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xylfe.cn/Article/details/gt2zvyquadm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gaohongyu789.top/Article/details/gt2zblumntc.html

Ruby: threads.map(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gt2pzdlvujl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lerxltss.html

[O06] 使用进程池
来源：http://dali.dianchejie.cn/Article/details/gt2iwxmitne.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.aizwys.cn/Article/details/gt2aszoduxw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fzhhl.top/Article/details/gt2rkixlhal.html

JS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gt2yfhrzxmx.html

TS:   // child_process / cluster 模块
来源：http://dali.smart0.xyz/Article/details/gt2srvmyiyo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhixingplan.top/Article/details/gt2ptbquhag.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ppjwa.cn/Article/details/gt2vrqvsdwc.html

Ruby: // fork 块
来源：http://dali.jlsjyb.cn/Article/details/gt2mcffheps.html

C#:   Parallel.For
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ayjrksrb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2pnqmhwps.html

P. 常用工具函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rmvqocfw.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2mehbqstg.html

[P01] 生成 UUID
来源：http://dali.yueranfly.top/Article/details/gt2kyiheqhp.html

Py:   str(uuid.uuid4())
来源：http://dali.sweek.top/Article/details/gt2unbrejfw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.bjfxy.top/Article/details/gt2isimoebq.html

JS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gt2dayyxbra.html

TS:   crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gt2eedzlmcw.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigfzy.top/Article/details/gt2jprhisbi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hywenlv.cn/Article/details/gt2xappcafj.html

Ruby: SecureRandom.uuid
来源：http://dali.xuanzx.com/Article/details/gt2csnctquf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zdqjudy.top/Article/details/gt2abjgzjrk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cqqwz.cn/Article/details/gt2gscxgehl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.9152youxi.cn/Article/details/gt2lgesucwc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gogol.net.cn/Article/details/gt2eqacjkuq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sngulbje.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hywenlv.cn/Article/details/gt2qrplqphd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pycfn.com/Article/details/gt2hdgmwgvq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zdqjudy.top/Article/details/gt2vvfgeouo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zdqjudy.top/Article/details/gt2fickgdin.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daria6918.cn/Article/details/gt2rrnzlkof.html

[P03] 生成短随机字符串
来源：http://dali.zhixingplan.top/Article/details/gt2ajvegyev.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nwbrower.top/Article/details/gt2ofkmkndw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aizwys.cn/Article/details/gt2gzmxluvq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gt2bzbtqtck.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cuwdynpg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.birdmap.top/Article/details/gt2ravjuran.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jiagoushi.top/Article/details/gt2vpxbayfr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jqgufenzy.top/Article/details/gt2xkgjzohx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guannengcc.top/Article/details/gt2lyjnzdkh.html

[P04] 求长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zeihtsne.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.aizwys.cn/Article/details/gt2vygozber.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kyptaecf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gt2vcqjyqhx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gt2sehmmcrh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zdqjudy.top/Article/details/gt2pvdsdpsy.html

Go:   len(arr);  len(m)
来源：http://dali.hfpthk.cn/Article/details/gt2vmvcqeop.html

Ruby: x.length;  x.size
来源：http://dali.c1oappe.top/Article/details/gt2zwqqceog.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.guowangkeji.top/Article/details/gt2ulnrbkpf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hnxiangtu.top/Article/details/gt2vrubqtim.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.feifeiyinyue.top/Article/details/gt2udktohbd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yanxiufei.cn/Article/details/gt2ggdjadbk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daria6918.cn/Article/details/gt2akdhciyt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bklgkrhw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aibaodan.cn/Article/details/gt2lmftfufa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cheryme.top/Article/details/gt2goqdlgic.html

Ruby: a == b
来源：http://dali.xuanzx.com/Article/details/gt2mxcqybht.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guannengcc.top/Article/details/gt2penvxcnx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gotoacloud.top/Article/details/gt2jcxkrltc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.0kj1m.cn/Article/details/gt2llqlvdhn.html

PHP:  if (empty($x)) {}
来源：http://dali.daxiang520.top/Article/details/gt2cimtnxsy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.redwolf501.top/Article/details/gt2dpuzuabw.html

TS:   if (x == null) {}
来源：http://dali.sysykeji.top/Article/details/gt2gurbdvar.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gt2fxfyhgux.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mhmixkql.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.0kj1m.cn/Article/details/gt2xzapyrbb.html

C#:   if (x is null) {}
来源：http://dali.guannengcc.top/Article/details/gt2mkclzkwr.html

[P07] 防抖与节流
来源：http://dali.gaohongyu789.top/Article/details/gt2vrhpsosa.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hfpthk.cn/Article/details/gt2vbstibdf.html

PHP:  // 手写时间戳比较
来源：http://dali.ydzc1.top/Article/details/gt2eqwwgxyo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gt2naspxnpv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gt2giwkdlbm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yuxming.cn/Article/details/gt2mobhbieh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cheryme.top/Article/details/gt2llljaorc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dashuyun.cn/Article/details/gt2ooxwcslj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.andypj.xyz/Article/details/gt2bdgzgjkk.html

[P08] 处理浮点精度问题
来源：http://dali.ydzc1.top/Article/details/gt2ugnnbvaw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2comtaukz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jyoumei.cn/Article/details/gt2zldclexq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fyfxlcyv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.fzhhl.top/Article/details/gt2mrpnsfxs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bkuqvghd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuanzhike.top/Article/details/gt2ikrrpswv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yueranfly.top/Article/details/gt2dpkvsaaq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.kuanghao11.cn/Article/details/gt2fzomqgdl.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2ankrcvvl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenzaomai.com/Article/details/gt2qbazozms.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2xgtqzkna.html

[Q01] 创建表
来源：http://dali.nanxuanxn.top/Article/details/gt2fdekhjrc.html

CREATE TABLE users (
来源：http://dali.hysaishi.cn/Article/details/gt2thsmduoy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gt2dpdwacmn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gt2icqtmghz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhengqikj.top/Article/details/gt2vyufdscm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.aizwys.cn/Article/details/gt2wixnaqsh.html

);
来源：http://dali.0kj1m.cn/Article/details/gt2tgxxhqdh.html

[Q02] 创建带外键的表
来源：http://dali.cdnleiting.top/Article/details/gt2gamshkgq.html

CREATE TABLE orders (
来源：http://dali.shzxlz.cn/Article/details/gt2vxcijysq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tian-w.cn/Article/details/gt2ueykvwtx.html

user_id INT NOT NULL,
来源：http://dali.shzxlz.cn/Article/details/gt2ghasraiq.html

amount DECIMAL(10, 2),
来源：http://dali.yueranfly.top/Article/details/gt2otnmicor.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhoulong.xyz/Article/details/gt2lqveijjr.html

);
来源：http://dali.ivvv.top/Article/details/gt2luuqbpvj.html

[Q03] 增加列
来源：http://dali.ydzc1.top/Article/details/gt2roipwsjx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.redwolf501.top/Article/details/gt2vlaazwzt.html

[Q04] 修改列类型
来源：http://dali.pycfn.com/Article/details/gt2daqkmgwx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hywenlv.cn/Article/details/gt2dfdhxnwh.html

[Q05] 重命名列
来源：http://dali.zhoulong.xyz/Article/details/gt2dfawwnms.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhongyouzk.top/Article/details/gt2klljzonw.html

[Q06] 删除列
来源：http://dali.jyoumei.cn/Article/details/gt2ehlyenpx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ydzc1.top/Article/details/gt2zxifntkf.html

[Q07] 删除表
来源：http://dali.cashguo.top/Article/details/gt2hyrggbpq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.guowangkeji.top/Article/details/gt2xpchglxq.html

[Q08] 创建普通索引
来源：http://dali.havefunace.top/Article/details/gt2nzxqirpu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gt2tipgfrwy.html

[Q09] 创建唯一索引
来源：http://dali.shzxlz.cn/Article/details/gt2zgvoglxh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gt2ifdrcjaa.html

[Q10] 插入单行
来源：http://dali.fengsongda.top/Article/details/gt2yesbjvig.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gogol.net.cn/Article/details/gt2mpfsablm.html

[Q11] 一次插入多行
来源：http://dali.yj202588.top/Article/details/gt2pbutqklu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gt2vlajhqmb.html

[Q12] 插入后取自增 ID
来源：http://dali.cdnleiting.top/Article/details/gt2xufdhyjb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hammf.cn/Article/details/gt2yjnjpgye.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenjidiqi.icu/Article/details/gt2glnlulay.html

[Q13] 忽略重复插入
来源：http://dali.gaohongyu789.top/Article/details/gt2uyjmrcrw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dashuyun.cn/Article/details/gt2gltqlibl.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenjidiqi.icu/Article/details/gt2hcjkncvd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xinyue.icu/Article/details/gt2uwuzptlm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hywenlv.cn/Article/details/gt2oxpefxro.html

[Q15] 查询全部
来源：http://dali.hywenlv.cn/Article/details/gt2qdwjycuu.html

SELECT * FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2esxvlwjq.html

[Q16] 查询指定列
来源：http://dali.yangfankeji.com/Article/details/gt2izoqinzq.html

SELECT id, name FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2opnratuq.html

[Q17] 条件查询
来源：http://dali.sysykeji.top/Article/details/gt2boeaprue.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2lrnfgvih.html

[Q18] 模糊匹配
来源：http://dali.redwolf501.top/Article/details/gt2yhqjntge.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jdfqaqcb.html

[Q19] 范围查询
来源：http://dali.yonumen.top/Article/details/gt2tqfcxwat.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yangfankeji.com/Article/details/gt2vyyhrmrk.html

[Q20] IN 列表
来源：http://dali.9152youxi.cn/Article/details/gt2hjnmfdpo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.316326.xyz/Article/details/gt2ajbkbbdn.html

[Q21] 空值判断
来源：http://dali.c1oappe.top/Article/details/gt2vcbrucse.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.andypj.xyz/Article/details/gt2iugyfluz.html

[Q22] 排序
来源：http://dali.shuidangran.top/Article/details/gt2aozwnqoe.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cqqwz.cn/Article/details/gt2skrxnhtn.html

[Q23] 分页
来源：http://dali.c1oappe.top/Article/details/gt2sxddvjsc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhixingplan.top/Article/details/gt2brnxataf.html

[Q24] 去重
来源：http://dali.shuidangran.top/Article/details/gt2jsfusmqg.html

SELECT DISTINCT city FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2rkpvnfnw.html

[Q25] 只取前 N 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gaoglhqq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cdnleiting.top/Article/details/gt2lykyukvj.html

[Q26] 计数
来源：http://dali.cashguo.top/Article/details/gt2waavsmdu.html

SELECT COUNT(*) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2sqqjskvw.html

[Q27] 条件计数
来源：http://dali.gzhubu.top/Article/details/gt2eptzlijm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2wcvbrget.html

[Q28] 求和与平均
来源：http://dali.sufxvd.cn/Article/details/gt2hlpkexkg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gt2jyyvlzge.html

[Q29] 最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gt2oplfaaok.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2lhdtkwlw.html

[Q30] 分组统计
来源：http://dali.xuetiantiany.cn/Article/details/gt2pudasokp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gt2rlbhjiho.html

[Q31] 分组后过滤
来源：http://dali.haohaochexian.top/Article/details/gt2aamdogdh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jlxvonxz.html

[Q32] 分组拼接字符串
来源：http://dali.ybcxt.top/Article/details/gt2saxhpwtj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gt2tagqwxyr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2hmouukze.html

[Q33] 多列分组
来源：http://dali.pengpengdd.cyou/Article/details/gt2xifdsaoc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxinkj.top/Article/details/gt2sycyqdts.html

[Q34] 每组取第一条
来源：http://dali.jqgufenzy.top/Article/details/gt2xwaopqoj.html

SELECT * FROM (
来源：http://dali.guannengcc.top/Article/details/gt2jlpjxakc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sysykeji.top/Article/details/gt2pkodkzty.html

) t WHERE rn = 1;
来源：http://dali.redwolf501.top/Article/details/gt2alxuydgl.html

[Q35] 内连接
来源：http://dali.c1oappe.top/Article/details/gt2zkeuqzie.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj202588.top/Article/details/gt2ffmszins.html

[Q36] 左连接
来源：http://dali.mhx1999.top/Article/details/gt2wxkhuljv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wbbquxsv.html

[Q37] 右连接
来源：http://dali.yonumen.top/Article/details/gt2jswtqemp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jianghu66.top/Article/details/gt2cvchohoa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ivvv.top/Article/details/gt2fvmenvtj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ffftjvrc.html

[Q39] 自连接（查上下级）
来源：http://dali.guannengcc.top/Article/details/gt2dhuztzqk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhoulong.xyz/Article/details/gt2fjvpsoqd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hccpbgpo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jyoumei.cn/Article/details/gt2hubbecty.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.snrcjt.cn/Article/details/gt2cicoucpe.html

[Q41] 多表连接
来源：http://dali.zycfv.cn/Article/details/gt2axfwtmke.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ehwqpu.com/Article/details/gt2vcaghwvo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.bjfxy.top/Article/details/gt2exxscztg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ybcxt.top/Article/details/gt2tdzusjzd.html

[Q42] 连接条件附加过滤
来源：http://dali.bjfxy.top/Article/details/gt2bsrniohr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daria6918.cn/Article/details/gt2geqxqmal.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ybcxt.top/Article/details/gt2orpyyyet.html

[Q43] 标量子查询
来源：http://dali.guowangkeji.top/Article/details/gt2cueqaojw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.c1oappe.top/Article/details/gt2mmontdkc.html

[Q44] IN 子查询
来源：http://dali.jyoumei.cn/Article/details/gt2wqhkwifn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yangfankeji.com/Article/details/gt2zjwsddej.html

[Q45] EXISTS 判断存在
来源：http://dali.meibo888.top/Article/details/gt2vvlwrttf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gt2sqilfsqr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yueranfly.top/Article/details/gt2pebuevsp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.vqdsnc.cn/Article/details/gt2mhzcpqqx.html

[Q47] 与平均值比较
来源：http://dali.cqqwz.cn/Article/details/gt2pqhwuvcc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yuxming.cn/Article/details/gt2desgbrwb.html

[Q48] CTE 公用表表达式
来源：http://dali.hywenlv.cn/Article/details/gt2whwrogfb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.kuanghao11.cn/Article/details/gt2fhmqjksv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhengqikj.top/Article/details/gt2einjfvgw.html

[Q49] 更新单行
来源：http://dali.dianchejie.cn/Article/details/gt2azyvvqge.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gt2wcystbsn.html

[Q50] 批量更新
来源：http://dali.zdqjudy.top/Article/details/gt2qpumnast.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.bjfxy.top/Article/details/gt2cchjuuzv.html

[Q51] 用子查询更新
来源：http://dali.ybcxt.top/Article/details/gt2cyvfjgai.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmcejgjh.html

[Q52] 删除指定行
来源：http://dali.nanxuanxn.top/Article/details/gt2kzpusbke.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnqzz.top/Article/details/gt2bcahwfyd.html

[Q53] 按条件删除
来源：http://dali.chenzaomai.com/Article/details/gt2rhxllpsj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zycfv.cn/Article/details/gt2bglpnerk.html

[Q54] 清空表
来源：http://dali.guannengcc.top/Article/details/gt2qjrbykja.html

TRUNCATE TABLE logs;
来源：http://dali.nanxinkj.top/Article/details/gt2xedmphsg.html

[Q55] 排名（并列占位）
来源：http://dali.pycfn.com/Article/details/gt2ufefcfya.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dashuyun.cn/Article/details/gt2wbawdyol.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shangyingyoupin.top/Article/details/gt2uphzakhs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinqigfzy.top/Article/details/gt2enrssdef.html

[Q57] 行号
来源：http://dali.sufxvd.cn/Article/details/gt2etbupcys.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2iywhmjck.html

[Q58] 累计求和
来源：http://dali.xinyue.icu/Article/details/gt2tknqsnwv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2noswmmhm.html

[Q59] 分组内累计
来源：http://dali.yuxming.cn/Article/details/gt2nlptgmsn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sweek.top/Article/details/gt2ihwpmlks.html

[Q60] 取上一行 / 下一行
来源：http://dali.yanxiufei.cn/Article/details/gt2fyrrufjb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gaohongyu789.top/Article/details/gt2tpikbhsp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2gfffytje.html

[Q61] 移动平均
来源：http://dali.zdqjudy.top/Article/details/gt2zwzhauko.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2orecmyzr.html

[Q62] 分组占比
来源：http://dali.yangfankeji.com/Article/details/gt2qhiditir.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gt2fqgxmeqv.html

[Q63] 开启事务
来源：http://dali.kuanghao11.cn/Article/details/gt2axavdsfw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dianchejie.cn/Article/details/gt2yrszflmy.html

[Q64] 提交事务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tqztdtnj.html

COMMIT;
来源：http://dali.zhixingplan.top/Article/details/gt2zpqtostu.html

[Q65] 回滚事务
来源：http://dali.zdqjudy.top/Article/details/gt2cwxbknvh.html

ROLLBACK;
来源：http://dali.yvedp.cn/Article/details/gt2azqnubgi.html

[Q66] 行锁查询
来源：http://dali.tanke756.top/Article/details/gt2xajzvsvb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guannengcc.top/Article/details/gt2wexnrxxq.html

[Q67] 设置隔离级别
来源：http://dali.sweek.top/Article/details/gt2kmrxtehi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ybcxt.top/Article/details/gt2pyijwxei.html

[Q68] 保存点
来源：http://dali.cqqwz.cn/Article/details/gt2tyjlfzgz.html

SAVEPOINT sp1;
来源：http://dali.gzhubu.top/Article/details/gt2nrhojbpt.html

ROLLBACK TO sp1;
来源：http://dali.yueranfly.top/Article/details/gt2rwvxvnju.html

[Q69] 查看执行计划
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rpvsupxi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tian-w.cn/Article/details/gt2fnyfhtee.html

[Q70] 更新统计信息
来源：http://dali.pycfn.com/Article/details/gt2nhqildqx.html

ANALYZE TABLE users;
来源：http://dali.guannengcc.top/Article/details/gt2iixcgccw.html

[Q71] 查看建表语句
来源：http://dali.xuanzx.com/Article/details/gt2dwcxjwbb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jianghu66.top/Article/details/gt2bucuvyek.html

[Q72] 查看索引
来源：http://dali.shangyingyoupin.top/Article/details/gt2vmmyfyzo.html

SHOW INDEX FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2bhiwrhgt.html

[Q73] 查看表状态
来源：http://dali.nanxinkj.top/Article/details/gt2pgfdkcby.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jiagoushi.top/Article/details/gt2hrqtoaat.html

[Q74] 强制使用索引
来源：http://dali.quarkkingdee.top/Article/details/gt2hjmkbvgs.html


<!-- 参考信息 -->