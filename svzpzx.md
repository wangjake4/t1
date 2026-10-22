代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xinyue.icu/Article/details/gtpafvmgdr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhixingplan.top/Article/details/gtrwqxfzbj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhoulong.xyz/Article/details/gtaefedlma.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gtwxndttig.html

Java: new Thread(() -> f()).start()
来源：http://dali.meibo888.top/Article/details/gtyaclfvsq.html

Go:   go f()
来源：http://dali.havefunace.top/Article/details/gtkkxsjkpc.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gtzqwrepmi.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258888.top/Article/details/gtirnyzkye.html

[O02] 使用线程池
来源：http://dali.zhixingplan.top/Article/details/gtfsnszwxb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aibaodan.cn/Article/details/gtvlehijgz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258888.top/Article/details/gtqghqyimn.html

JS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gtxgnfuwty.html

TS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gtobxqdwiq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.meibo888.top/Article/details/gtqtewnddd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.fzhhl.top/Article/details/gtizhnkbmf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.birdmap.top/Article/details/gtmnwojjzt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yueranfly.top/Article/details/gtvkefrfid.html

[O03] 加锁保护共享数据
来源：http://dali.bjfxy.top/Article/details/gtkzhfvoaj.html

Py:   with lock: shared += 1
来源：http://dali.jqgufenzy.top/Article/details/gtpwaxvnyc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.9152youxi.cn/Article/details/gttwaureak.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zdqjudy.top/Article/details/gtyyhncuxf.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gtzvuvmznc.html

Java: synchronized (this) { shared++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdnthsjcv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.guowangkeji.top/Article/details/gtqtaxgvfy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yvedp.cn/Article/details/gtzzwutllf.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gtxvojgswm.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigufen.top/Article/details/gtweexqxql.html

Py:   async def f():⏎    await g()
来源：http://dali.yonumen.top/Article/details/gtcnocnaqz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhengqikj.top/Article/details/gtpbshkuuo.html

JS:   async function f() { await g(); }
来源：http://dali.daxiang520.top/Article/details/gtpethaxlh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gtjmqxjkzv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbndyvvl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yangfankeji.com/Article/details/gtujkrzepu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hfpthk.cn/Article/details/gtmotbahrr.html

C#:   async Task F() { await G(); }
来源：http://dali.gzhubu.top/Article/details/gtdrxvauea.html

[O05] 并发执行并等待全部完成
来源：http://dali.9152youxi.cn/Article/details/gtqodmhuux.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yvedp.cn/Article/details/gtrdsokisp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jyoumei.cn/Article/details/gtrhellofc.html

JS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gtecknqttd.html

TS:   await Promise.all(tasks)
来源：http://dali.jqgufenzy.top/Article/details/gtnfvchxpr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guowangkeji.top/Article/details/gtlvzjacwa.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guannengcc.top/Article/details/gtpfmzxobw.html

Ruby: threads.map(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gtpcyixjeq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shangyingyoupin.top/Article/details/gtwpulmyyd.html

[O06] 使用进程池
来源：http://dali.yj20258888.top/Article/details/gtbucjnaal.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.andypj.xyz/Article/details/gtexxijrhg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuanzhike.top/Article/details/gtsynpgwog.html

JS:   // child_process / cluster 模块
来源：http://dali.sysykeji.top/Article/details/gtjfpvhgvg.html

TS:   // child_process / cluster 模块
来源：http://dali.hammf.cn/Article/details/gtgsvxboej.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sysykeji.top/Article/details/gtuuzmikoi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jyoumei.cn/Article/details/gtnwjmpdtu.html

Ruby: // fork 块
来源：http://dali.redwolf501.top/Article/details/gtuopjxcns.html

C#:   Parallel.For
来源：http://dali.nanxinkj.top/Article/details/gtpijobtxo.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtvxcbsujv.html

P. 常用工具函数
来源：http://dali.zycfv.cn/Article/details/gtwpauopim.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtsonewcdj.html

[P01] 生成 UUID
来源：http://dali.shzxlz.cn/Article/details/gtackyfvsz.html

Py:   str(uuid.uuid4())
来源：http://dali.pengpengdd.cyou/Article/details/gtfwldbjmg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.svipenyu.cn/Article/details/gteajwvaiy.html

JS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gthkdrcnwf.html

TS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gtzfqhslfx.html

Java: UUID.randomUUID().toString()
来源：http://dali.sysykeji.top/Article/details/gtxtpuuepw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jiagoushi.top/Article/details/gtqoeljiyc.html

Ruby: SecureRandom.uuid
来源：http://dali.fzhhl.top/Article/details/gteeusthul.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yanxiufei.cn/Article/details/gtpfmwnczh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacuyeawg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shangyingyoupin.top/Article/details/gtcrgypxzk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ydzc1.top/Article/details/gtavmamkyc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nwbrower.top/Article/details/gtflnnapfg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.bjfxy.top/Article/details/gtvxwsvjlk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gtbhypvbew.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.guannengcc.top/Article/details/gtpnwdfgef.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhengqikj.top/Article/details/gtbpaphlcs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.iojbl.cn/Article/details/gtkalajzcv.html

[P03] 生成短随机字符串
来源：http://dali.gotoacloud.top/Article/details/gtxszisedu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenzaomai.com/Article/details/gtydfjoqsk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yongpay.top/Article/details/gteyudlzzb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dianchejie.cn/Article/details/gtpkqvmtmi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtqjizxfco.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cashguo.top/Article/details/gtysklygxb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinqigfzy.top/Article/details/gtgncwamdp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shuidangran.top/Article/details/gtenjxfxxl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jianghu66.top/Article/details/gtquafrsmi.html

[P04] 求长度
来源：http://dali.sxryk.cn/Article/details/gtoeriaddt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hnqzz.top/Article/details/gteipriwrw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtptwesxkx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gtpqprzxmi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuanzhike.top/Article/details/gtctiowqge.html

Java: list.size();  map.size();  s.length()
来源：http://dali.snrcjt.cn/Article/details/gtijqayisf.html

Go:   len(arr);  len(m)
来源：http://dali.yuanzhike.top/Article/details/gtffifixmx.html

Ruby: x.length;  x.size
来源：http://dali.jlsjyb.cn/Article/details/gtmutjhiqy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gthadcnnoe.html

[P05] 判断两个对象内容是否相等
来源：http://dali.aibaodan.cn/Article/details/gtoaftlcab.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigfzy.top/Article/details/gteztyohmt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tanke756.top/Article/details/gtwsboimdi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yvedp.cn/Article/details/gtxjdiwqkw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqomeaet.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aizwys.cn/Article/details/gttcmskitu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtriovnwta.html

Ruby: a == b
来源：http://dali.jinqigufen.top/Article/details/gthhyrtgoa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daxiang520.top/Article/details/gtnoelvouq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtcxyqxg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.vqdsnc.cn/Article/details/gtkbzniyfb.html

PHP:  if (empty($x)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtslheiabe.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yongpay.top/Article/details/gtndlwiuhx.html

TS:   if (x == null) {}
来源：http://dali.yanxiufei.cn/Article/details/gtvgspmtdd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gthgixtbsu.html

Go:   if x == nil {}
来源：http://dali.cheryme.top/Article/details/gtqrpoiqqd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.fzhhl.top/Article/details/gtuflvtpni.html

C#:   if (x is null) {}
来源：http://dali.hammf.cn/Article/details/gttaxaiypz.html

[P07] 防抖与节流
来源：http://dali.aizwys.cn/Article/details/gtgxzijfcv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shangyingyoupin.top/Article/details/gtqefhorsc.html

PHP:  // 手写时间戳比较
来源：http://dali.jianghu66.top/Article/details/gtrflkxuhx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gthxikdgde.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gtalqpubnd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtftlsoyau.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shzxlz.cn/Article/details/gtfcdtgogu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxgrafwx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sxryk.cn/Article/details/gtkmaypgmf.html

[P08] 处理浮点精度问题
来源：http://dali.hnxiangtu.top/Article/details/gtiwurzhtf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jyoumei.cn/Article/details/gtxbcjpiam.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xylfe.cn/Article/details/gtjurrpfll.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pycfn.com/Article/details/gtysmnqqwe.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shuidangran.top/Article/details/gtmhbkclaa.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xylfe.cn/Article/details/gttqshnwdn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aibaodan.cn/Article/details/gtgjsfdrwk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.fengsongda.top/Article/details/gtficfvgiv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dianchejie.cn/Article/details/gtprupgtud.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtywbebegg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sufxvd.cn/Article/details/gtbbmnbphr.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtunksvwoz.html

[Q01] 创建表
来源：http://dali.meibo888.top/Article/details/gtnatdeysb.html

CREATE TABLE users (
来源：http://dali.dashuyun.cn/Article/details/gteorasdyv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gthrcjkspf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gtirtdptqf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xuetiantiany.cn/Article/details/gthubkfcra.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zdqjudy.top/Article/details/gtpwqlmcor.html

);
来源：http://dali.yvedp.cn/Article/details/gtwomsyfdk.html

[Q02] 创建带外键的表
来源：http://dali.redwolf501.top/Article/details/gtyxrsbxhw.html

CREATE TABLE orders (
来源：http://dali.fengsongda.top/Article/details/gtawcykzay.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gthhnkteyk.html

user_id INT NOT NULL,
来源：http://dali.gotoacloud.top/Article/details/gtmkesalid.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidpdgmth.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gotoacloud.top/Article/details/gtgfhfrmix.html

);
来源：http://dali.fengsongda.top/Article/details/gtdiaqdzqv.html

[Q03] 增加列
来源：http://dali.mhx1999.top/Article/details/gtktilakwg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hfpthk.cn/Article/details/gtidqsunax.html

[Q04] 修改列类型
来源：http://dali.nwbrower.top/Article/details/gtapcymkhc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.9152youxi.cn/Article/details/gtwommtxib.html

[Q05] 重命名列
来源：http://dali.ehwqpu.com/Article/details/gttduwqbqm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqfosohv.html

[Q06] 删除列
来源：http://dali.cdnleiting.top/Article/details/gtbeburnze.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guowangkeji.top/Article/details/gtrkmugyms.html

[Q07] 删除表
来源：http://dali.yangfankeji.com/Article/details/gtzurrpcoe.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuanzhike.top/Article/details/gtrcbapbwt.html

[Q08] 创建普通索引
来源：http://dali.kuanghao11.cn/Article/details/gtviunukyy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gtxbsgecsv.html

[Q09] 创建唯一索引
来源：http://dali.zhiwuduotai.top/Article/details/gtokljvffv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybamvbtf.html

[Q10] 插入单行
来源：http://dali.ivvv.top/Article/details/gtkluanucq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhengqikj.top/Article/details/gtbambvyqt.html

[Q11] 一次插入多行
来源：http://dali.pengpengdd.cyou/Article/details/gtorrlxjex.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.havefunace.top/Article/details/gtwlwjepbh.html

[Q12] 插入后取自增 ID
来源：http://dali.ivvv.top/Article/details/gtkdcpjqld.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jiagoushi.top/Article/details/gtymvrzqnj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuanzhike.top/Article/details/gtmhhmfgnu.html

[Q13] 忽略重复插入
来源：http://dali.zhiwuduotai.top/Article/details/gtyneqejwc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zdqjudy.top/Article/details/gtuqldmnng.html

[Q14] 存在则更新（upsert）
来源：http://dali.xinyue.icu/Article/details/gtdokqfptf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jianghu66.top/Article/details/gtsslszwts.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezdpxkqk.html

[Q15] 查询全部
来源：http://dali.nanxinkj.top/Article/details/gtnfnnknlx.html

SELECT * FROM users;
来源：http://dali.yvedp.cn/Article/details/gtlbamykgm.html

[Q16] 查询指定列
来源：http://dali.xziqi.cn/Article/details/gtqqlekujo.html

SELECT id, name FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtocssaupj.html

[Q17] 条件查询
来源：http://dali.fengsongda.top/Article/details/gtbmtcitiy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sufxvd.cn/Article/details/gttmlcwcor.html

[Q18] 模糊匹配
来源：http://dali.jyoumei.cn/Article/details/gtbdosnile.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.snrcjt.cn/Article/details/gtxvokgspb.html

[Q19] 范围查询
来源：http://dali.xuetiantiany.cn/Article/details/gtrlnyknpp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuxming.cn/Article/details/gtuzrcoxdd.html

[Q20] IN 列表
来源：http://dali.hywenlv.cn/Article/details/gtsyfqlysx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yvedp.cn/Article/details/gtvktputhu.html

[Q21] 空值判断
来源：http://dali.jqgufenzy.top/Article/details/gttyvqxdls.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sweek.top/Article/details/gtcvebvdoa.html

[Q22] 排序
来源：http://dali.0kj1m.cn/Article/details/gtpblgigtn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shzxlz.cn/Article/details/gtmjyrixwa.html

[Q23] 分页
来源：http://dali.shzxlz.cn/Article/details/gtrvgviuae.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gaohongyu789.top/Article/details/gtaszkruua.html

[Q24] 去重
来源：http://dali.yanxiufei.cn/Article/details/gtacmlghpn.html

SELECT DISTINCT city FROM users;
来源：http://dali.xziqi.cn/Article/details/gtgddgvzvx.html

[Q25] 只取前 N 条
来源：http://dali.jianghu66.top/Article/details/gtrgxashgq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.smart0.xyz/Article/details/gtvqcziprw.html

[Q26] 计数
来源：http://dali.yonumen.top/Article/details/gtyipqixxl.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258888.top/Article/details/gttljrgont.html

[Q27] 条件计数
来源：http://dali.fengsongda.top/Article/details/gtrrjuoufz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtenfvhsey.html

[Q28] 求和与平均
来源：http://dali.zhengqikj.top/Article/details/gtjgvlfigo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtfnggybbe.html

[Q29] 最大最小值
来源：http://dali.gotoacloud.top/Article/details/gttagptbnm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtgdxancga.html

[Q30] 分组统计
来源：http://dali.yvedp.cn/Article/details/gthgqezzni.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtvoyvuwle.html

[Q31] 分组后过滤
来源：http://dali.fzhhl.top/Article/details/gtddfmrmab.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.fengsongda.top/Article/details/gtyrccgysv.html

[Q32] 分组拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtdqnpzwpw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gttogukqzj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.smart0.xyz/Article/details/gtrsvjhrlz.html

[Q33] 多列分组
来源：http://dali.ydzc1.top/Article/details/gtdtqlrncl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shangyingyoupin.top/Article/details/gtzbufosot.html

[Q34] 每组取第一条
来源：http://dali.316326.xyz/Article/details/gtjyehdgsy.html

SELECT * FROM (
来源：http://dali.sysykeji.top/Article/details/gtxzjaeuic.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jlsjyb.cn/Article/details/gtzwkufgnn.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtrykthjsi.html

[Q35] 内连接
来源：http://dali.hywenlv.cn/Article/details/gtkdvlbqgt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtngmsrmqs.html

[Q36] 左连接
来源：http://dali.sxryk.cn/Article/details/gtktcztwgc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtbkrsojlp.html

[Q37] 右连接
来源：http://dali.yangfankeji.com/Article/details/gtdqkmaogh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.0kj1m.cn/Article/details/gtjijpckqp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tian-w.cn/Article/details/gtcaoaqlcz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yangfankeji.com/Article/details/gtqliodymd.html

[Q39] 自连接（查上下级）
来源：http://dali.zhengqikj.top/Article/details/gtefxajvqy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.quarkkingdee.top/Article/details/gtpdjcoaaq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tanke756.top/Article/details/gtwbeksgtf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinqigfzy.top/Article/details/gtonfrwven.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jiagoushi.top/Article/details/gttgbayatk.html

[Q41] 多表连接
来源：http://dali.nwbrower.top/Article/details/gtbufhlvlk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yueranfly.top/Article/details/gtagtwqchh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.bjfxy.top/Article/details/gtivdksror.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guowangkeji.top/Article/details/gtmswexhvr.html

[Q42] 连接条件附加过滤
来源：http://dali.dianchejie.cn/Article/details/gtpafdshcq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pycfn.com/Article/details/gtgtligsyy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fzhhl.top/Article/details/gtfvdimefl.html

[Q43] 标量子查询
来源：http://dali.sweek.top/Article/details/gtnjgpozxz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigufen.top/Article/details/gtugrvzahm.html

[Q44] IN 子查询
来源：http://dali.0kj1m.cn/Article/details/gtmgcffumr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzgokqbo.html

[Q45] EXISTS 判断存在
来源：http://dali.guannengcc.top/Article/details/gthwqdlcbc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gtospzensj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhengqikj.top/Article/details/gtygjfeyel.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shangyingyoupin.top/Article/details/gtnezlxltk.html

[Q47] 与平均值比较
来源：http://dali.guannengcc.top/Article/details/gttgdxxzxy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shangyingyoupin.top/Article/details/gtqtccmmjd.html

[Q48] CTE 公用表表达式
来源：http://dali.svipenyu.cn/Article/details/gtxutrahrs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ppjwa.cn/Article/details/gtrztinsqf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daria6918.cn/Article/details/gtkvchjcwx.html

[Q49] 更新单行
来源：http://dali.hywenlv.cn/Article/details/gtgkurlvpm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gtnqbgzofq.html

[Q50] 批量更新
来源：http://dali.hongshengwenyu.top/Article/details/gtjgrzqyof.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xziqi.cn/Article/details/gtgmtfftkm.html

[Q51] 用子查询更新
来源：http://dali.svipenyu.cn/Article/details/gtrnkhalsu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sweek.top/Article/details/gtynqwvimi.html

[Q52] 删除指定行
来源：http://dali.zhixingplan.top/Article/details/gtqooygzcq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtxhtamjxv.html

[Q53] 按条件删除
来源：http://dali.cashguo.top/Article/details/gtbcthfodf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.birdmap.top/Article/details/gtrgnlddeh.html

[Q54] 清空表
来源：http://dali.chenjidiqi.icu/Article/details/gtnyfckeiv.html

TRUNCATE TABLE logs;
来源：http://dali.wangdashe.top/Article/details/gtvhscpeoe.html

[Q55] 排名（并列占位）
来源：http://dali.zhiwuduotai.top/Article/details/gtwegeytzg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.mhx1999.top/Article/details/gtzpcesgwa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenzaomai.com/Article/details/gtenygeuvn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gtvocnltvu.html

[Q57] 行号
来源：http://dali.ivvv.top/Article/details/gtkwhnsimx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xinyue.icu/Article/details/gtnrbhefmt.html

[Q58] 累计求和
来源：http://dali.feifeiyinyue.top/Article/details/gtcjxlqone.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.316326.xyz/Article/details/gtbafjmffi.html

[Q59] 分组内累计
来源：http://dali.dashuyun.cn/Article/details/gtpvymoaqv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtmgvmpnuv.html

[Q60] 取上一行 / 下一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbpjzicq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yongpay.top/Article/details/gtmsllbhyh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.meibo888.top/Article/details/gtkhhtfsjz.html

[Q61] 移动平均
来源：http://dali.yj20258888.top/Article/details/gtymlxczbv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtedwnpymr.html

[Q62] 分组占比
来源：http://dali.cashguo.top/Article/details/gtabewfgis.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gttjjvcxad.html

[Q63] 开启事务
来源：http://dali.quarkkingdee.top/Article/details/gtuqudqivf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenzaomai.com/Article/details/gteugalewg.html

[Q64] 提交事务
来源：http://dali.wangshuangyany.cn/Article/details/gtjsfeafzd.html

COMMIT;
来源：http://dali.svipenyu.cn/Article/details/gthqlubvbo.html

[Q65] 回滚事务
来源：http://dali.xinyue.icu/Article/details/gtrziekgso.html

ROLLBACK;
来源：http://dali.bjfxy.top/Article/details/gtrpwqlfqy.html

[Q66] 行锁查询
来源：http://dali.yj202588.top/Article/details/gtlwxrcsge.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.c1oappe.top/Article/details/gtbzyqqyyv.html

[Q67] 设置隔离级别
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgieqhgdv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zdqjudy.top/Article/details/gtwxhinmtl.html

[Q68] 保存点
来源：http://dali.fzhhl.top/Article/details/gtqekffwgc.html

SAVEPOINT sp1;
来源：http://dali.jqgufenzy.top/Article/details/gtywltvaij.html

ROLLBACK TO sp1;
来源：http://dali.gogol.net.cn/Article/details/gtkvvurwkg.html

[Q69] 查看执行计划
来源：http://dali.nanxuanxn.top/Article/details/gtxqlmhdbp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnzcxtuh.html

[Q70] 更新统计信息
来源：http://dali.cucudq.cn/Article/details/gtqtrtknxk.html

ANALYZE TABLE users;
来源：http://dali.yueranfly.top/Article/details/gtqsuhurjg.html

[Q71] 查看建表语句
来源：http://dali.quarkkingdee.top/Article/details/gtdgnvvnad.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.svipenyu.cn/Article/details/gtkhzjclov.html

[Q72] 查看索引
来源：http://dali.zycfv.cn/Article/details/gtyrciztnx.html

SHOW INDEX FROM users;
来源：http://dali.gzhubu.top/Article/details/gtgowhoxgi.html

[Q73] 查看表状态
来源：http://dali.xuetiantiany.cn/Article/details/gtkjluvymb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.mhx1999.top/Article/details/gtjkgjajuu.html

[Q74] 强制使用索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtncxjek.html


<!-- 参考信息 -->