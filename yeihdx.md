代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhongyouzk.top/Article/details/gtesnozjiw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hywenlv.cn/Article/details/gtszdjdiat.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenlongwang.top/Article/details/gterferbyu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.9152youxi.cn/Article/details/gtgbisjike.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwkluqgv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gtwspzaxga.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ybcxt.top/Article/details/gtpafeesvd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gtgqzcmiia.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtxbssjwun.html

O. 并发与异步
来源：http://dali.birdmap.top/Article/details/gtdmaftyts.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtwdnwptqu.html

[O01] 启动一个线程
来源：http://dali.hfpthk.cn/Article/details/gteolbhrlg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gogol.net.cn/Article/details/gtwhugqvph.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nanxinkj.top/Article/details/gtjagpqken.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.dashuyun.cn/Article/details/gtcsfzxfxt.html

TS:   // 同 JS
来源：http://dali.yanxiufei.cn/Article/details/gtyjnheasq.html

Java: new Thread(() -> f()).start()
来源：http://dali.bjfxy.top/Article/details/gtnlvsgvwq.html

Go:   go f()
来源：http://dali.wangdashe.top/Article/details/gteumiatjv.html

Ruby: Thread.new { f }
来源：http://dali.vqdsnc.cn/Article/details/gtpkpozkoh.html

C#:   Task.Run(() => F());
来源：http://dali.shanyushiyangtech.top/Article/details/gtmiwiklun.html

[O02] 使用线程池
来源：http://dali.ivvv.top/Article/details/gtztstlwpu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jiagoushi.top/Article/details/gthiisniag.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sxryk.cn/Article/details/gtatzdunmh.html

JS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gtnegylhkp.html

TS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gtetcgkjxi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhoulong.xyz/Article/details/gtqexsetsz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangdashe.top/Article/details/gtwsfuuxqj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cashguo.top/Article/details/gtjbiymibl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yangfankeji.com/Article/details/gtadtjuart.html

[O03] 加锁保护共享数据
来源：http://dali.tian-w.cn/Article/details/gtutbluxxo.html

Py:   with lock: shared += 1
来源：http://dali.hfpthk.cn/Article/details/gtpvjwynrc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xziqi.cn/Article/details/gtcrqkbbir.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sweek.top/Article/details/gtxgppamrb.html

TS:   // 同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gtkhldcwkk.html

Java: synchronized (this) { shared++; }
来源：http://dali.hammf.cn/Article/details/gtwikplsgi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fengsongda.top/Article/details/gtjwxnicbe.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.haohaochexian.top/Article/details/gtwfnyehoz.html

C#:   lock (gate) { shared++; }
来源：http://dali.tian-w.cn/Article/details/gtjcioeuob.html

[O04] 定义异步函数并等待
来源：http://dali.daxiang520.top/Article/details/gtxwvxxcxx.html

Py:   async def f():⏎    await g()
来源：http://dali.ppjwa.cn/Article/details/gtxskyuubi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuxming.cn/Article/details/gtmizgceco.html

JS:   async function f() { await g(); }
来源：http://dali.vqdsnc.cn/Article/details/gthdryjoxx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtgnbuzhps.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuxming.cn/Article/details/gtpsejxnfe.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258.top/Article/details/gtutahdxgf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hysaishi.cn/Article/details/gtycbeovjx.html

C#:   async Task F() { await G(); }
来源：http://dali.xuanzx.com/Article/details/gtscgtrabl.html

[O05] 并发执行并等待全部完成
来源：http://dali.hnqzz.top/Article/details/gtmvnexvba.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtxmjtawln.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinqigufen.top/Article/details/gtvwjzimyf.html

JS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gtmzquipig.html

TS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gtmlrqpcvp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.smart0.xyz/Article/details/gtljmwjvxw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxtwcdwa.html

Ruby: threads.map(&:join)
来源：http://dali.jqgufenzy.top/Article/details/gtrfaloutt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj20258.top/Article/details/gtdxxsaupc.html

[O06] 使用进程池
来源：http://dali.chenjidiqi.icu/Article/details/gtqmtzzmyp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tanke756.top/Article/details/gtudghbasu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xuetiantiany.cn/Article/details/gtzlsnpxoq.html

JS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gtxbkkvuxm.html

TS:   // child_process / cluster 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxzxcifq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.svipenyu.cn/Article/details/gtsrmawuuu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgufenzy.top/Article/details/gtaqkbxmjo.html

Ruby: // fork 块
来源：http://dali.wangdashe.top/Article/details/gttefbkbup.html

C#:   Parallel.For
来源：http://dali.316326.xyz/Article/details/gtahzajyvk.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gttlpcrcmd.html

P. 常用工具函数
来源：http://dali.yj20258888.top/Article/details/gthkczhirw.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtynezvfuf.html

[P01] 生成 UUID
来源：http://dali.ivvv.top/Article/details/gtgujljcin.html

Py:   str(uuid.uuid4())
来源：http://dali.quarkkingdee.top/Article/details/gtzaoywwsp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuuvnnrhh.html

JS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gtzumkhgfk.html

TS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gtuomhndlt.html

Java: UUID.randomUUID().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtxgqwetmm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shangyingyoupin.top/Article/details/gtobfmkttg.html

Ruby: SecureRandom.uuid
来源：http://dali.xinyue.icu/Article/details/gtjpgfdyqy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yongpay.top/Article/details/gtsnzktcuh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dashuyun.cn/Article/details/gtmtzquyty.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nanxinkj.top/Article/details/gtnxvcrvcf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zycfv.cn/Article/details/gtsrvepllu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zycfv.cn/Article/details/gtnjnofevw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yueranfly.top/Article/details/gthzhocfzr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxinkj.top/Article/details/gtmbvinrpn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gotoacloud.top/Article/details/gtzndpqnxt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.andypj.xyz/Article/details/gtqfufpbxg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.andypj.xyz/Article/details/gtfdjjhtuh.html

[P03] 生成短随机字符串
来源：http://dali.nanxuanxn.top/Article/details/gtosalmnld.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.9152youxi.cn/Article/details/gtacxsvrjx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yonumen.top/Article/details/gtxxnxijrf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gzhubu.top/Article/details/gtkatysice.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gaohongyu789.top/Article/details/gtlgfwxtzn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtipiazrbo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.snrcjt.cn/Article/details/gtqymqynqs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.mhx1999.top/Article/details/gthrqvdhsi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.andypj.xyz/Article/details/gtvwqeutdp.html

[P04] 求长度
来源：http://dali.fzhhl.top/Article/details/gtixptpldd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xuetiantiany.cn/Article/details/gtnctrdpid.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtxcsowdol.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.feifeiyinyue.top/Article/details/gtrrhleunp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gtjdvpujab.html

Java: list.size();  map.size();  s.length()
来源：http://dali.0kj1m.cn/Article/details/gtevrubeiq.html

Go:   len(arr);  len(m)
来源：http://dali.tianlin.xyz/Article/details/gtfvggfxyj.html

Ruby: x.length;  x.size
来源：http://dali.jqgufenzy.top/Article/details/gtmifmbpfl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gtmyjpbgvt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sweek.top/Article/details/gtaqdtaawd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yonumen.top/Article/details/gtbjhaeott.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gogol.net.cn/Article/details/gtxekrkmme.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ydzc1.top/Article/details/gtzrpbtjdl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guannengcc.top/Article/details/gtwvopmiey.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hfpthk.cn/Article/details/gtsbogpxrb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.smart0.xyz/Article/details/gtjbuuwcbb.html

Ruby: a == b
来源：http://dali.hnxiangtu.top/Article/details/gtgbmurttu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhixingplan.top/Article/details/gtqjzzuvgu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.iojbl.cn/Article/details/gtnvmxfblv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xinyue.icu/Article/details/gtamdognlj.html

PHP:  if (empty($x)) {}
来源：http://dali.nwbrower.top/Article/details/gtrpzxuswp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hysaishi.cn/Article/details/gtxtrfxqjx.html

TS:   if (x == null) {}
来源：http://dali.jyoumei.cn/Article/details/gtgdyxetia.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gtnypqjlcw.html

Go:   if x == nil {}
来源：http://dali.meibo888.top/Article/details/gthkvohumk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.0kj1m.cn/Article/details/gthwrokcmc.html

C#:   if (x is null) {}
来源：http://dali.quarkkingdee.top/Article/details/gtntkdcqmm.html

[P07] 防抖与节流
来源：http://dali.sufxvd.cn/Article/details/gtafaltsin.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cheryme.top/Article/details/gtobgfvmfu.html

PHP:  // 手写时间戳比较
来源：http://dali.chenzaomai.com/Article/details/gtcwctjioi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gtmbstlloo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zycfv.cn/Article/details/gtsfvxcoji.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtonjmvrjl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hywenlv.cn/Article/details/gtxsaicngw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuetiantiany.cn/Article/details/gtnmgbuzqe.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hongshengwenyu.top/Article/details/gtxffiikal.html

[P08] 处理浮点精度问题
来源：http://dali.yongpay.top/Article/details/gtutrzewvy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ppjwa.cn/Article/details/gtswsxjmro.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hammf.cn/Article/details/gtqsgsehxy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fengsongda.top/Article/details/gtyyhiwaka.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gotoacloud.top/Article/details/gtabkzlkiu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258888.top/Article/details/gtsjilvkye.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangtech.top/Article/details/gtaotfqzsh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tanke756.top/Article/details/gtopfmkoqi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.aizwys.cn/Article/details/gtnnvhjmcj.html

================================================================================
来源：http://dali.sweek.top/Article/details/gttzcwzetp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.smart0.xyz/Article/details/gtndooshfo.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtnicehurv.html

[Q01] 创建表
来源：http://dali.zhixingplan.top/Article/details/gtmqmdirwx.html

CREATE TABLE users (
来源：http://dali.xziqi.cn/Article/details/gtjtvgtmrq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hywenlv.cn/Article/details/gtztvtwdky.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gtazulkskn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gzhubu.top/Article/details/gtodfrjrqh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.smart0.xyz/Article/details/gtvqfgjcpg.html

);
来源：http://dali.wangshuangyany.cn/Article/details/gtgolsfnyi.html

[Q02] 创建带外键的表
来源：http://dali.hnqzz.top/Article/details/gtqcwtkiso.html

CREATE TABLE orders (
来源：http://dali.shzxlz.cn/Article/details/gtoofmnkra.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gtlpzwbpct.html

user_id INT NOT NULL,
来源：http://dali.ybcxt.top/Article/details/gthqcxpvfw.html

amount DECIMAL(10, 2),
来源：http://dali.nwbrower.top/Article/details/gtmpnsfxnc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.daria6918.cn/Article/details/gtmiwkpbow.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gtfqfmfojr.html

[Q03] 增加列
来源：http://dali.kuanghao11.cn/Article/details/gtphvwyavf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hnxiangtu.top/Article/details/gthwppsboa.html

[Q04] 修改列类型
来源：http://dali.xziqi.cn/Article/details/gtlofzufpk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gzhubu.top/Article/details/gtvivlhqir.html

[Q05] 重命名列
来源：http://dali.xuetiantiany.cn/Article/details/gtkzmvxvmq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nanxinkj.top/Article/details/gtkxcvqpyw.html

[Q06] 删除列
来源：http://dali.sufxvd.cn/Article/details/gtfltxvfyy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhiwuduotai.top/Article/details/gtryaedrmp.html

[Q07] 删除表
来源：http://dali.c1oappe.top/Article/details/gteyhgqgsn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtadbzirko.html

[Q08] 创建普通索引
来源：http://dali.kuanghao11.cn/Article/details/gtluwanrcs.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gtbscfnkjd.html

[Q09] 创建唯一索引
来源：http://dali.svipenyu.cn/Article/details/gtvsplwkli.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gthfoxoqmh.html

[Q10] 插入单行
来源：http://dali.hammf.cn/Article/details/gtcpjztauw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.iojbl.cn/Article/details/gtmljljrxa.html

[Q11] 一次插入多行
来源：http://dali.xuetiantiany.cn/Article/details/gtwtuyaitq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sxryk.cn/Article/details/gtdyougekb.html

[Q12] 插入后取自增 ID
来源：http://dali.mhx1999.top/Article/details/gtptirdlub.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.meibo888.top/Article/details/gtdtbkbtaz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258888.top/Article/details/gtupeqqupg.html

[Q13] 忽略重复插入
来源：http://dali.yuxming.cn/Article/details/gthfhebnzh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sufxvd.cn/Article/details/gtxhoksekh.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuxming.cn/Article/details/gtoraxitpc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cheryme.top/Article/details/gtlkwepatr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hnxiangtu.top/Article/details/gtuapubxxv.html

[Q15] 查询全部
来源：http://dali.hnqzz.top/Article/details/gtougxnrsb.html

SELECT * FROM users;
来源：http://dali.ybcxt.top/Article/details/gthujgxfwa.html

[Q16] 查询指定列
来源：http://dali.jqgfzy.top/Article/details/gtsxiqencp.html

SELECT id, name FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktmrjgft.html

[Q17] 条件查询
来源：http://dali.nanxuanxn.top/Article/details/gtymztpzdr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tianlin.xyz/Article/details/gtrnatiyge.html

[Q18] 模糊匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtfxznkolp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gzhubu.top/Article/details/gtkkcgpdwi.html

[Q19] 范围查询
来源：http://dali.feifeiyinyue.top/Article/details/gtemrnjuse.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xylfe.cn/Article/details/gtjziosxur.html

[Q20] IN 列表
来源：http://dali.dashuyun.cn/Article/details/gthgfeppaj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj20258.top/Article/details/gtyvsltyrf.html

[Q21] 空值判断
来源：http://dali.bjfxy.top/Article/details/gteebailfr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmvxvduq.html

[Q22] 排序
来源：http://dali.feifeiyinyue.top/Article/details/gtduexkesn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sysykeji.top/Article/details/gtufwvazmy.html

[Q23] 分页
来源：http://dali.yuanzhike.top/Article/details/gtmciajwsm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.havefunace.top/Article/details/gtmdxyyoqs.html

[Q24] 去重
来源：http://dali.mhx1999.top/Article/details/gtcfvdbabg.html

SELECT DISTINCT city FROM users;
来源：http://dali.bjfxy.top/Article/details/gtozlphrbn.html

[Q25] 只取前 N 条
来源：http://dali.jinqigfzy.top/Article/details/gtnxujhsyk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhongyouzk.top/Article/details/gtqlackkdf.html

[Q26] 计数
来源：http://dali.nanxuanxn.top/Article/details/gtyawiyefr.html

SELECT COUNT(*) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gttuhehtyh.html

[Q27] 条件计数
来源：http://dali.andypj.xyz/Article/details/gtgbkkrwqm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtzrkvfekz.html

[Q28] 求和与平均
来源：http://dali.chenlongwang.top/Article/details/gtuytvpueh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtmmpenpwr.html

[Q29] 最大最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmzjatoyx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtkppcjsmp.html

[Q30] 分组统计
来源：http://dali.ehwqpu.com/Article/details/gtvafgbhdb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtiepkaach.html

[Q31] 分组后过滤
来源：http://dali.havefunace.top/Article/details/gtgoimzauh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtklsycbni.html

[Q32] 分组拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gtnmcrrkmo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtdatagwyp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yonumen.top/Article/details/gtqjwbvele.html

[Q33] 多列分组
来源：http://dali.gotoacloud.top/Article/details/gtabvnygcr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhoulong.xyz/Article/details/gtkrdcokut.html

[Q34] 每组取第一条
来源：http://dali.fzhhl.top/Article/details/gtuqpnsmie.html

SELECT * FROM (
来源：http://dali.guannengcc.top/Article/details/gtzehulvih.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shuidangran.top/Article/details/gtjnvnwokc.html

) t WHERE rn = 1;
来源：http://dali.cucudq.cn/Article/details/gtpwatlhxk.html

[Q35] 内连接
来源：http://dali.mhx1999.top/Article/details/gtcynttfhs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gtbaqmzqbi.html

[Q36] 左连接
来源：http://dali.0kj1m.cn/Article/details/gtveohwabe.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gtuevmoodf.html

[Q37] 右连接
来源：http://dali.birdmap.top/Article/details/gtrytflfml.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gttbgubsiv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zdqjudy.top/Article/details/gtosokhorj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pycfn.com/Article/details/gtoekgfooa.html

[Q39] 自连接（查上下级）
来源：http://dali.birdmap.top/Article/details/gtjnfynwag.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sxryk.cn/Article/details/gtnvdwlslt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jianghu66.top/Article/details/gtidrunvqw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuanzhike.top/Article/details/gtbsfkgbts.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.bjfxy.top/Article/details/gtfiphedws.html

[Q41] 多表连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavyuowdm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ybcxt.top/Article/details/gtgikbloqn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jiagoushi.top/Article/details/gtmvupzkht.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgfzy.top/Article/details/gtpcrrhoab.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxinkj.top/Article/details/gtmmpiudol.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sufxvd.cn/Article/details/gtanmcetss.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigfzy.top/Article/details/gtfnsvgbug.html

[Q43] 标量子查询
来源：http://dali.quarkkingdee.top/Article/details/gtvtizwugc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ybcxt.top/Article/details/gtkzaghsaf.html

[Q44] IN 子查询
来源：http://dali.guannengcc.top/Article/details/gtedvthdfe.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yuanzhike.top/Article/details/gtzivxxyfd.html

[Q45] EXISTS 判断存在
来源：http://dali.yanxiufei.cn/Article/details/gtrnijbnez.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gtognvnnwq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fzhhl.top/Article/details/gtsjlyqbfg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gtnxpslhcr.html

[Q47] 与平均值比较
来源：http://dali.tanke756.top/Article/details/gtqusnuxqa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sweek.top/Article/details/gtcuthsbss.html

[Q48] CTE 公用表表达式
来源：http://dali.shuidangran.top/Article/details/gtmjsiyrcb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigufen.top/Article/details/gtbxjawcpb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqumegpa.html

[Q49] 更新单行
来源：http://dali.gzhubu.top/Article/details/gtfghncmwx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gtorxxqfgn.html

[Q50] 批量更新
来源：http://dali.andypj.xyz/Article/details/gtveiycuid.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hammf.cn/Article/details/gtajdsusgg.html

[Q51] 用子查询更新
来源：http://dali.vqdsnc.cn/Article/details/gtfvhkgekz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yonumen.top/Article/details/gtwzngcmts.html

[Q52] 删除指定行
来源：http://dali.jyoumei.cn/Article/details/gtqmsxtfre.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfinxafjr.html

[Q53] 按条件删除
来源：http://dali.redwolf501.top/Article/details/gtmkwqsuxy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yvedp.cn/Article/details/gthoqtwhvl.html

[Q54] 清空表
来源：http://dali.tianlin.xyz/Article/details/gtycictzfx.html

TRUNCATE TABLE logs;
来源：http://dali.tianlin.xyz/Article/details/gtdsnuponf.html

[Q55] 排名（并列占位）
来源：http://dali.nwbrower.top/Article/details/gtmqlqbjto.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.mhx1999.top/Article/details/gtjhefcjem.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jiagoushi.top/Article/details/gtjbfoltar.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gtrvqtfign.html

[Q57] 行号
来源：http://dali.hnxiangtu.top/Article/details/gtzfxtrcyt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvofojwzb.html

[Q58] 累计求和
来源：http://dali.nwbrower.top/Article/details/gtfvjfgmrr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtovprpgxm.html

[Q59] 分组内累计
来源：http://dali.yj202588.top/Article/details/gtmqaktfrv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtovbbpnta.html

[Q60] 取上一行 / 下一行
来源：http://dali.gzhubu.top/Article/details/gtfcqftvsp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yuxming.cn/Article/details/gtyaqwrsfy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtaelwvfxa.html

[Q61] 移动平均
来源：http://dali.shuidangran.top/Article/details/gtfxjikybk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtcdjnadiw.html

[Q62] 分组占比
来源：http://dali.hysaishi.cn/Article/details/gtrwnxwetu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtcvnxdorf.html

[Q63] 开启事务
来源：http://dali.0kj1m.cn/Article/details/gtcqrtsyew.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.havefunace.top/Article/details/gtrnhefdpd.html

[Q64] 提交事务
来源：http://dali.ppjwa.cn/Article/details/gtkneaogyb.html

COMMIT;
来源：http://dali.jyoumei.cn/Article/details/gttfhabozv.html

[Q65] 回滚事务
来源：http://dali.aizwys.cn/Article/details/gtgzmptxyc.html

ROLLBACK;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpkoysgv.html

[Q66] 行锁查询
来源：http://dali.tianlin.xyz/Article/details/gtrhqqibih.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenlongwang.top/Article/details/gtqtqwjsyy.html

[Q67] 设置隔离级别
来源：http://dali.shzxlz.cn/Article/details/gtokzbsygi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrxbpxbw.html

[Q68] 保存点
来源：http://dali.sweek.top/Article/details/gtnbelltfb.html

SAVEPOINT sp1;
来源：http://dali.yongpay.top/Article/details/gtvnlmxdfc.html


<!-- 参考信息 -->