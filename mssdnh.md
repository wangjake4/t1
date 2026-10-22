代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gt2tjybqvva.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xziqi.cn/Article/details/gt2blswdzwh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gzhubu.top/Article/details/gt2rvuzppup.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gt2psvvuzmk.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2hvdqwgpb.html

O. 并发与异步
来源：http://dali.xuetiantiany.cn/Article/details/gt2napuedoa.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2dzrauxdw.html

[O01] 启动一个线程
来源：http://dali.sxryk.cn/Article/details/gt2rhethuov.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pengpengdd.cyou/Article/details/gt2eingsluy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zdqjudy.top/Article/details/gt2hfjrcnuc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.snrcjt.cn/Article/details/gt2evuxwclt.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gt2ghxkiqwo.html

Java: new Thread(() -> f()).start()
来源：http://dali.nanxuanxn.top/Article/details/gt2ngqbbhue.html

Go:   go f()
来源：http://dali.yueranfly.top/Article/details/gt2xudwztor.html

Ruby: Thread.new { f }
来源：http://dali.yj20258888.top/Article/details/gt2jpyxaxql.html

C#:   Task.Run(() => F());
来源：http://dali.jianghu66.top/Article/details/gt2oiirjcnp.html

[O02] 使用线程池
来源：http://dali.daria6918.cn/Article/details/gt2laaqcatz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sweek.top/Article/details/gt2uqkniuvc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guannengcc.top/Article/details/gt2rqwmzuki.html

JS:   // worker_threads 线程池
来源：http://dali.hysaishi.cn/Article/details/gt2pzqrupng.html

TS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zhhqaszr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhengqikj.top/Article/details/gt2vcwtudfl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258.top/Article/details/gt2hneqfbav.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nanxuanxn.top/Article/details/gt2pvwxovnp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hammf.cn/Article/details/gt2nhkkfamp.html

[O03] 加锁保护共享数据
来源：http://dali.yuanzhike.top/Article/details/gt2ehcaqetl.html

Py:   with lock: shared += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2asogbqcs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj202588.top/Article/details/gt2tsemiazb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenjidiqi.icu/Article/details/gt2agahuuby.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gt2famdgmfp.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhengqikj.top/Article/details/gt2kwwfqqhw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gzhubu.top/Article/details/gt2bptsgvcj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinqigfzy.top/Article/details/gt2tarpvldo.html

C#:   lock (gate) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nvbewkye.html

[O04] 定义异步函数并等待
来源：http://dali.fzhhl.top/Article/details/gt2ilnmvuxx.html

Py:   async def f():⏎    await g()
来源：http://dali.cashguo.top/Article/details/gt2cxsibbzp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shangyingyoupin.top/Article/details/gt2kwyiwzpr.html

JS:   async function f() { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gt2xqauleqc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cashguo.top/Article/details/gt2apxhqwho.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenlongwang.top/Article/details/gt2cephugiy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.svipenyu.cn/Article/details/gt2hslulzsz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yongpay.top/Article/details/gt2fdefproa.html

C#:   async Task F() { await G(); }
来源：http://dali.0kj1m.cn/Article/details/gt2azftyrji.html

[O05] 并发执行并等待全部完成
来源：http://dali.sysykeji.top/Article/details/gt2iyarxrdz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jyoumei.cn/Article/details/gt2iscrjrzh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yangfankeji.com/Article/details/gt2htthvenp.html

JS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gt2ugckckpc.html

TS:   await Promise.all(tasks)
来源：http://dali.fzhhl.top/Article/details/gt2lzcfoxvu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.dianchejie.cn/Article/details/gt2ineiwbdw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhengqikj.top/Article/details/gt2hvuigqwm.html

Ruby: threads.map(&:join)
来源：http://dali.xziqi.cn/Article/details/gt2rkglrriu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ppjwa.cn/Article/details/gt2dcdcezmc.html

[O06] 使用进程池
来源：http://dali.sweek.top/Article/details/gt2vikgwovd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cqqwz.cn/Article/details/gt2jbvinhxr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cheryme.top/Article/details/gt2imbdbogs.html

JS:   // child_process / cluster 模块
来源：http://dali.cheryme.top/Article/details/gt2ymgndfos.html

TS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gt2pnkktgih.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhoulong.xyz/Article/details/gt2tqyesogj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sxryk.cn/Article/details/gt2uakwoyyv.html

Ruby: // fork 块
来源：http://dali.hysaishi.cn/Article/details/gt2oropukoi.html

C#:   Parallel.For
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bkamdegl.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2fdsqcztl.html

P. 常用工具函数
来源：http://dali.tian-w.cn/Article/details/gt2shdujcdt.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2rmlonqsq.html

[P01] 生成 UUID
来源：http://dali.bjfxy.top/Article/details/gt2nlmtrbmh.html

Py:   str(uuid.uuid4())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pebedgmy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhengqikj.top/Article/details/gt2klmcfdch.html

JS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gt2balclzsn.html

TS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gt2mrkgzcjq.html

Java: UUID.randomUUID().toString()
来源：http://dali.aibaodan.cn/Article/details/gt2cmbtklgt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.svipenyu.cn/Article/details/gt2ukgcseiq.html

Ruby: SecureRandom.uuid
来源：http://dali.xuanzx.com/Article/details/gt2jyvcvafg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shzxlz.cn/Article/details/gt2skkmszxf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hywenlv.cn/Article/details/gt2wzzwkokx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nanxuanxn.top/Article/details/gt2aarzhfds.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cqqwz.cn/Article/details/gt2sylfmrpo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yvedp.cn/Article/details/gt2adhzbgba.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tian-w.cn/Article/details/gt2fnlxodcg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.iojbl.cn/Article/details/gt2lwprdpat.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.bjfxy.top/Article/details/gt2plomvbtr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgfzy.top/Article/details/gt2degrglnl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tjpeoruf.html

[P03] 生成短随机字符串
来源：http://dali.cashguo.top/Article/details/gt2hpsnqyhs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.9152youxi.cn/Article/details/gt2cbswehsy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cheryme.top/Article/details/gt2waljvwcb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xinyue.icu/Article/details/gt2rxmjpbht.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gt2kmsjelzf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.iojbl.cn/Article/details/gt2usyqchxt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jlsjyb.cn/Article/details/gt2zzbagoxa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.meibo888.top/Article/details/gt2rwcxewzu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ydzc1.top/Article/details/gt2coxzjgdx.html

[P04] 求长度
来源：http://dali.hywenlv.cn/Article/details/gt2jkbxkehn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenzaomai.com/Article/details/gt2bimmuebe.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gt2rndsaevk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shuidangran.top/Article/details/gt2nmrknnew.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gt2hqrgjgpn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cheryme.top/Article/details/gt2lhptsxvl.html

Go:   len(arr);  len(m)
来源：http://dali.yj202588.top/Article/details/gt2spmgbpky.html

Ruby: x.length;  x.size
来源：http://dali.quarkkingdee.top/Article/details/gt2hpcxnnuo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj202588.top/Article/details/gt2rwfxseae.html

[P05] 判断两个对象内容是否相等
来源：http://dali.9152youxi.cn/Article/details/gt2hrgwjwtk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daxiang520.top/Article/details/gt2icddvnlz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jyoumei.cn/Article/details/gt2rhkxaosr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shzxlz.cn/Article/details/gt2wsvwnwmh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tanke756.top/Article/details/gt2hflyzmwo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenjidiqi.icu/Article/details/gt2eupaihww.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.guowangkeji.top/Article/details/gt2azupdpcw.html

Ruby: a == b
来源：http://dali.aibaodan.cn/Article/details/gt2vxzzyywx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zycfv.cn/Article/details/gt2cycluung.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangdashe.top/Article/details/gt2ikhxmhum.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenjidiqi.icu/Article/details/gt2ottqealt.html

PHP:  if (empty($x)) {}
来源：http://dali.havefunace.top/Article/details/gt2dqlbrmba.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shanyushiyangtech.top/Article/details/gt2klcikoue.html

TS:   if (x == null) {}
来源：http://dali.shuidangran.top/Article/details/gt2vuqsbnww.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gt2qisrzzka.html

Go:   if x == nil {}
来源：http://dali.daria6918.cn/Article/details/gt2oaqjsoty.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jyoumei.cn/Article/details/gt2vemtdmhi.html

C#:   if (x is null) {}
来源：http://dali.havefunace.top/Article/details/gt2tvtgnwic.html

[P07] 防抖与节流
来源：http://dali.chenjidiqi.icu/Article/details/gt2eutijlju.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenzaomai.com/Article/details/gt2pmsptmkg.html

PHP:  // 手写时间戳比较
来源：http://dali.zhengqikj.top/Article/details/gt2sgdjywly.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gt2twzjqxgo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gt2zdjlciuq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jyoumei.cn/Article/details/gt2yqisbduk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shuidangran.top/Article/details/gt2xndutlzl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuanzx.com/Article/details/gt2lzfgdflj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xinyue.icu/Article/details/gt2drrbakkz.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigfzy.top/Article/details/gt2hqosvsxz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.guowangkeji.top/Article/details/gt2ibgfezbo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yueranfly.top/Article/details/gt2sjsdpbhq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pengpengdd.cyou/Article/details/gt2fudltdzg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shuidangran.top/Article/details/gt2vjknsdei.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.snrcjt.cn/Article/details/gt2aqsondqr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zrqmkdad.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.aizwys.cn/Article/details/gt2aemdjxhs.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yueranfly.top/Article/details/gt2gxlorcve.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2jaqnqueb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jianghu66.top/Article/details/gt2lorwpsap.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2bgluhlqp.html

[Q01] 创建表
来源：http://dali.jiagoushi.top/Article/details/gt2enrnjjza.html

CREATE TABLE users (
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yodoemhb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxinkj.top/Article/details/gt2tbpgvopg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shangyingyoupin.top/Article/details/gt2weexonmq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sxryk.cn/Article/details/gt2jzmqbxqk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhiwuduotai.top/Article/details/gt2tfqggcyr.html

);
来源：http://dali.hnxiangtu.top/Article/details/gt2yrydihau.html

[Q02] 创建带外键的表
来源：http://dali.wangshuangyany.cn/Article/details/gt2dbeepzez.html

CREATE TABLE orders (
来源：http://dali.wangdashe.top/Article/details/gt2lvwtwcat.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhixingplan.top/Article/details/gt2wdqudrdq.html

user_id INT NOT NULL,
来源：http://dali.sysykeji.top/Article/details/gt2oiorqpaq.html

amount DECIMAL(10, 2),
来源：http://dali.daria6918.cn/Article/details/gt2cxfgrtme.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ehwqpu.com/Article/details/gt2mzgdjjaa.html

);
来源：http://dali.yueranfly.top/Article/details/gt2sutsjafk.html

[Q03] 增加列
来源：http://dali.hywenlv.cn/Article/details/gt2cupuuflz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhengqikj.top/Article/details/gt2rkiailhh.html

[Q04] 修改列类型
来源：http://dali.yj202588.top/Article/details/gt2xfvpnlpp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tian-w.cn/Article/details/gt2bjqmeydd.html

[Q05] 重命名列
来源：http://dali.yuanzhike.top/Article/details/gt2zhvjjcjo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.birdmap.top/Article/details/gt2qrzoaohs.html

[Q06] 删除列
来源：http://dali.jianghu66.top/Article/details/gt2jkqrfrpb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.andypj.xyz/Article/details/gt2asavuajk.html

[Q07] 删除表
来源：http://dali.meibo888.top/Article/details/gt2vfztkjos.html

DROP TABLE IF EXISTS orders;
来源：http://dali.guannengcc.top/Article/details/gt2puiuiwgh.html

[Q08] 创建普通索引
来源：http://dali.cucudq.cn/Article/details/gt2hevkfnjc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.haohaochexian.top/Article/details/gt2warctwsz.html

[Q09] 创建唯一索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jnjtgfdf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gzhubu.top/Article/details/gt2kgtmursl.html

[Q10] 插入单行
来源：http://dali.yj20258.top/Article/details/gt2nyuhrurc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aibaodan.cn/Article/details/gt2quctjxjd.html

[Q11] 一次插入多行
来源：http://dali.ybcxt.top/Article/details/gt2gliqfrvg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hywenlv.cn/Article/details/gt2szxzzpzb.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258888.top/Article/details/gt2dsmgigky.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj20258888.top/Article/details/gt2dpssustw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj202588.top/Article/details/gt2sbfaerqz.html

[Q13] 忽略重复插入
来源：http://dali.daxiang520.top/Article/details/gt2bzvduhzh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gogol.net.cn/Article/details/gt2mobilggr.html

[Q14] 存在则更新（upsert）
来源：http://dali.bjfxy.top/Article/details/gt2eimmkubj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.dianchejie.cn/Article/details/gt2drdtuehk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ovgexmkg.html

[Q15] 查询全部
来源：http://dali.chenjidiqi.icu/Article/details/gt2jfnzrxdd.html

SELECT * FROM users;
来源：http://dali.birdmap.top/Article/details/gt2wdkaxbmo.html

[Q16] 查询指定列
来源：http://dali.shuidangran.top/Article/details/gt2ivkjwkqw.html

SELECT id, name FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2kjejgevy.html

[Q17] 条件查询
来源：http://dali.yangfankeji.com/Article/details/gt2skmdjfap.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qpkgrbmw.html

[Q18] 模糊匹配
来源：http://dali.0kj1m.cn/Article/details/gt2vyzvlcbu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shuidangran.top/Article/details/gt2dsujndro.html

[Q19] 范围查询
来源：http://dali.zhongyouzk.top/Article/details/gt2ysvdvyuv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenzaomai.com/Article/details/gt2cpxlmwur.html

[Q20] IN 列表
来源：http://dali.fengsongda.top/Article/details/gt2beyloiba.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2olixuviw.html

[Q21] 空值判断
来源：http://dali.sysykeji.top/Article/details/gt2hondtpvn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yuxming.cn/Article/details/gt2zymmodtc.html

[Q22] 排序
来源：http://dali.daxiang520.top/Article/details/gt2eymrwwgl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangshuangyany.cn/Article/details/gt2lxwbjdni.html

[Q23] 分页
来源：http://dali.hammf.cn/Article/details/gt2krloxgqk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hnxiangtu.top/Article/details/gt2mvlejfdn.html

[Q24] 去重
来源：http://dali.sweek.top/Article/details/gt2ftjynpia.html

SELECT DISTINCT city FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2qjddfnfd.html

[Q25] 只取前 N 条
来源：http://dali.tanke756.top/Article/details/gt2ktmtqkhv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.c1oappe.top/Article/details/gt2hqslznbo.html

[Q26] 计数
来源：http://dali.dianchejie.cn/Article/details/gt2cizhzhgx.html

SELECT COUNT(*) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2nhashwfv.html

[Q27] 条件计数
来源：http://dali.gogol.net.cn/Article/details/gt2czdtwckw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2zrdnzzxc.html

[Q28] 求和与平均
来源：http://dali.ydzc1.top/Article/details/gt2sdtctozi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2ncgcqgdl.html

[Q29] 最大最小值
来源：http://dali.yj20258.top/Article/details/gt2zbomcdxs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2sbaxfmiz.html

[Q30] 分组统计
来源：http://dali.hnqzz.top/Article/details/gt2hemnnvdu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gt2opbsrkod.html

[Q31] 分组后过滤
来源：http://dali.ppjwa.cn/Article/details/gt2ohfvajwt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.guowangkeji.top/Article/details/gt2kffqypti.html

[Q32] 分组拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2ocugixxi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gt2wwxfwnes.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xziqi.cn/Article/details/gt2picxkjhv.html

[Q33] 多列分组
来源：http://dali.zycfv.cn/Article/details/gt2otzelxft.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hywenlv.cn/Article/details/gt2afwovylc.html

[Q34] 每组取第一条
来源：http://dali.wangshuangyany.cn/Article/details/gt2ehqnpwju.html

SELECT * FROM (
来源：http://dali.snrcjt.cn/Article/details/gt2omvawbxf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shangyingyoupin.top/Article/details/gt2txccwbti.html

) t WHERE rn = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oionbgia.html

[Q35] 内连接
来源：http://dali.cqqwz.cn/Article/details/gt2jiavvmkz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.havefunace.top/Article/details/gt2dhsyjxib.html

[Q36] 左连接
来源：http://dali.zhiwuduotai.top/Article/details/gt2hsvsoapp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gt2dmgunbqb.html

[Q37] 右连接
来源：http://dali.9152youxi.cn/Article/details/gt2pdofmigf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jlsjyb.cn/Article/details/gt2bltdtflg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.feifeiyinyue.top/Article/details/gt2fivlexsv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangdashe.top/Article/details/gt2nbpicghh.html

[Q39] 自连接（查上下级）
来源：http://dali.xylfe.cn/Article/details/gt2qlwxqaoj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eyqwpacw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ydzc1.top/Article/details/gt2lnbqkenp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.mhx1999.top/Article/details/gt2hvvviwqa.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuanzx.com/Article/details/gt2aidxyuuh.html

[Q41] 多表连接
来源：http://dali.smart0.xyz/Article/details/gt2hwrltudu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sysykeji.top/Article/details/gt2zianqjqc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.daxiang520.top/Article/details/gt2uiskaljn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yonumen.top/Article/details/gt2glfcimuh.html

[Q42] 连接条件附加过滤
来源：http://dali.xuetiantiany.cn/Article/details/gt2ntumfmwh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yueranfly.top/Article/details/gt2bfordtqq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gogol.net.cn/Article/details/gt2sygzqdnd.html

[Q43] 标量子查询
来源：http://dali.ybcxt.top/Article/details/gt2esvbluzt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yangfankeji.com/Article/details/gt2rpzpyefb.html

[Q44] IN 子查询
来源：http://dali.jinqigufen.top/Article/details/gt2mrwfaycp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj20258888.top/Article/details/gt2hyfrijou.html

[Q45] EXISTS 判断存在
来源：http://dali.yj202588.top/Article/details/gt2naonhovz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xziqi.cn/Article/details/gt2yszyeadn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhiwuduotai.top/Article/details/gt2llbhzvoj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gt2qtxoxgdm.html

[Q47] 与平均值比较
来源：http://dali.meibo888.top/Article/details/gt2zchrctpt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhengqikj.top/Article/details/gt2ukyuofyh.html

[Q48] CTE 公用表表达式
来源：http://dali.guowangkeji.top/Article/details/gt2wkvgqbwy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxinkj.top/Article/details/gt2suxnepxf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daria6918.cn/Article/details/gt2nzycwlbi.html

[Q49] 更新单行
来源：http://dali.daxiang520.top/Article/details/gt2iefhlgnj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gt2lwzrajom.html

[Q50] 批量更新
来源：http://dali.zdqjudy.top/Article/details/gt2emhipadn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.meibo888.top/Article/details/gt2xyevnofl.html

[Q51] 用子查询更新
来源：http://dali.hfpthk.cn/Article/details/gt2ngwzpihr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yonumen.top/Article/details/gt2pknxyfwc.html

[Q52] 删除指定行
来源：http://dali.gaohongyu789.top/Article/details/gt2srgykyar.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gt2abkogyxb.html

[Q53] 按条件删除
来源：http://dali.tianlin.xyz/Article/details/gt2vetrjjan.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sweek.top/Article/details/gt2ogqvcbhk.html

[Q54] 清空表
来源：http://dali.sufxvd.cn/Article/details/gt2sgefbvji.html

TRUNCATE TABLE logs;
来源：http://dali.xziqi.cn/Article/details/gt2ntsoevha.html

[Q55] 排名（并列占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hevjatoc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gt2bnaprvls.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zycfv.cn/Article/details/gt2pkhqtpeq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ehwqpu.com/Article/details/gt2nyzploqv.html

[Q57] 行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cfgdsddi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2qqpwovco.html

[Q58] 累计求和
来源：http://dali.tanke756.top/Article/details/gt2gvtkzdkr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2umdxeffl.html

[Q59] 分组内累计
来源：http://dali.yuanzhike.top/Article/details/gt2xocepilh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gt2rtggdexy.html

[Q60] 取上一行 / 下一行
来源：http://dali.hnxiangtu.top/Article/details/gt2vmfzhacl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hongshengwenyu.top/Article/details/gt2wsmggtsa.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2cunpsxmh.html

[Q61] 移动平均
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qyygshsq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gt2nuabyhjk.html

[Q62] 分组占比
来源：http://dali.daxiang520.top/Article/details/gt2kdtupmwr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gt2chmjgmsp.html

[Q63] 开启事务
来源：http://dali.c1oappe.top/Article/details/gt2fnshwsxp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.svipenyu.cn/Article/details/gt2rfdahkgd.html

[Q64] 提交事务
来源：http://dali.sufxvd.cn/Article/details/gt2dymmujmk.html

COMMIT;
来源：http://dali.yj20258888.top/Article/details/gt2zzkzmdwh.html

[Q65] 回滚事务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mhymqykb.html

ROLLBACK;
来源：http://dali.hnxiangtu.top/Article/details/gt2yyjksljf.html

[Q66] 行锁查询
来源：http://dali.jqgfzy.top/Article/details/gt2vsdncasv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cdnleiting.top/Article/details/gt2annsytyg.html

[Q67] 设置隔离级别
来源：http://dali.xylfe.cn/Article/details/gt2cvcparzl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxuanxn.top/Article/details/gt2hpimluzp.html

[Q68] 保存点
来源：http://dali.hongshengwenyu.top/Article/details/gt2lsglheqe.html

SAVEPOINT sp1;
来源：http://dali.gaohongyu789.top/Article/details/gt2hrzihjsq.html

ROLLBACK TO sp1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ttoqwmkq.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfpqacb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.iojbl.cn/Article/details/gt2eeaxrqvk.html

[Q70] 更新统计信息
来源：http://dali.hongshengwenyu.top/Article/details/gt2dpvsjfdu.html


<!-- 参考信息 -->