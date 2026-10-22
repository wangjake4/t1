代发 wailian999

PHP:  // 手写递归函数
来源：http://dali.ivvv.top/Article/details/gtbzasntiz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gtglbrmgzx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hywenlv.cn/Article/details/gtkvivyjmu.html

Java: // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gtnvgsrrxk.html

Go:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gtefyzbvep.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.dianchejie.cn/Article/details/gtkimhjfey.html

C#:   // 手写递归
来源：http://dali.xziqi.cn/Article/details/gtwxkqexho.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tianlin.xyz/Article/details/gtkxgcbzxc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.c1oappe.top/Article/details/gtwfkzzodf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tian-w.cn/Article/details/gtgossydby.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gtgauocdcr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gthdwtcpqc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yangfankeji.com/Article/details/gtrrtvumiy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cqqwz.cn/Article/details/gtbhcvzwgp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sweek.top/Article/details/gtisfefmzj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gtrjnauyjh.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtctchyfzv.html

O. 并发与异步
来源：http://dali.birdmap.top/Article/details/gtbistdeef.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtdnejjtza.html

[O01] 启动一个线程
来源：http://dali.fzhhl.top/Article/details/gtdvdgbjhw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pycfn.com/Article/details/gthjxmxvev.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuxming.cn/Article/details/gtcnmzsavl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.fzhhl.top/Article/details/gtxcsepads.html

TS:   // 同 JS
来源：http://dali.aibaodan.cn/Article/details/gtrutruhtr.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnqzz.top/Article/details/gtmfvzgwoa.html

Go:   go f()
来源：http://dali.jinqigfzy.top/Article/details/gtuxhetrrw.html

Ruby: Thread.new { f }
来源：http://dali.sufxvd.cn/Article/details/gtmvhbxycj.html

C#:   Task.Run(() => F());
来源：http://dali.hnxiangtu.top/Article/details/gtzlpejsyi.html

[O02] 使用线程池
来源：http://dali.yj202588.top/Article/details/gtzfpkjuqf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.kuanghao11.cn/Article/details/gtymokurxd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaysvjwyf.html

JS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gtltdnyzow.html

TS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gttgewrwyj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gaohongyu789.top/Article/details/gtogjvucda.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hongshengwenyu.top/Article/details/gtrhivepyv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.quarkkingdee.top/Article/details/gtohoexkar.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ehwqpu.com/Article/details/gtlyrhybjr.html

[O03] 加锁保护共享数据
来源：http://dali.chenzaomai.com/Article/details/gtevvdsfws.html

Py:   with lock: shared += 1
来源：http://dali.zycfv.cn/Article/details/gtfupcxwer.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnqzz.top/Article/details/gtszsskyev.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yangfankeji.com/Article/details/gtzmejfqfc.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gtjvwehgcc.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gtlkfbdsoh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.snrcjt.cn/Article/details/gtzllnyzmj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.haohaochexian.top/Article/details/gtfeahuyao.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcnufjyj.html

[O04] 定义异步函数并等待
来源：http://dali.meibo888.top/Article/details/gthvqodvjz.html

Py:   async def f():⏎    await g()
来源：http://dali.yongpay.top/Article/details/gtxljnnygu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dashuyun.cn/Article/details/gtgebaftoz.html

JS:   async function f() { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gtrikqkore.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtxtztoloi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbzgmxmuc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.fzhhl.top/Article/details/gtdorbfhhn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.c1oappe.top/Article/details/gtilsusbpx.html

C#:   async Task F() { await G(); }
来源：http://dali.guowangkeji.top/Article/details/gtztzlpize.html

[O05] 并发执行并等待全部完成
来源：http://dali.hammf.cn/Article/details/gtwdkpszav.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhixingplan.top/Article/details/gtdvksylgo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sxryk.cn/Article/details/gthsiabagn.html

JS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gtgsptdiix.html

TS:   await Promise.all(tasks)
来源：http://dali.daria6918.cn/Article/details/gtofbhrmvy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jlsjyb.cn/Article/details/gtrvtzgltj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbivmcpno.html

Ruby: threads.map(&:join)
来源：http://dali.jianghu66.top/Article/details/gtpyghgknb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.9152youxi.cn/Article/details/gtqxqflcyd.html

[O06] 使用进程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtgkosvafz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.feifeiyinyue.top/Article/details/gtqykeryru.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shangyingyoupin.top/Article/details/gtnvhrzghr.html

JS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gtmfxtquwg.html

TS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gttqmihoml.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.0kj1m.cn/Article/details/gtehrepebn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shanyushiyangkeji.top/Article/details/gtippmbzwg.html

Ruby: // fork 块
来源：http://dali.cashguo.top/Article/details/gtixrfsfmw.html

C#:   Parallel.For
来源：http://dali.cucudq.cn/Article/details/gtdxsigruj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtsystvvex.html

P. 常用工具函数
来源：http://dali.chenjidiqi.icu/Article/details/gtwahgcspm.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtbdckmfxl.html

[P01] 生成 UUID
来源：http://dali.jqgufenzy.top/Article/details/gtrarzjict.html

Py:   str(uuid.uuid4())
来源：http://dali.316326.xyz/Article/details/gteghogtom.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.pengpengdd.cyou/Article/details/gtrrkonvlr.html

JS:   crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gtfruadhrl.html

TS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gtgzhrtlbk.html

Java: UUID.randomUUID().toString()
来源：http://dali.meibo888.top/Article/details/gtsygazvgy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daxiang520.top/Article/details/gtgntlrued.html

Ruby: SecureRandom.uuid
来源：http://dali.zhengqikj.top/Article/details/gtgbaotsqu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nwbrower.top/Article/details/gtnpnpcgod.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gotoacloud.top/Article/details/gtvuijzrdi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.vqdsnc.cn/Article/details/gtvkkudiqh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dianchejie.cn/Article/details/gtbultssvh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbbomutn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.vqdsnc.cn/Article/details/gthqogcvdm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtvsiaeaho.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.guowangkeji.top/Article/details/gtgyafwmoz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.bjfxy.top/Article/details/gtsumizrkv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sufxvd.cn/Article/details/gtulcrhwaq.html

[P03] 生成短随机字符串
来源：http://dali.vqdsnc.cn/Article/details/gtzfgoumoo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ppjwa.cn/Article/details/gtskravjie.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xylfe.cn/Article/details/gtckwppten.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gteksxnsfe.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gtpnmphltn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtbncbnlat.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gzhubu.top/Article/details/gtfovjljob.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zycfv.cn/Article/details/gtmfxkfxsq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.haohaochexian.top/Article/details/gtsmasjkvn.html

[P04] 求长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizuiilil.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sxryk.cn/Article/details/gtfwzdlabg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtmgngexvi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pycfn.com/Article/details/gtqymkowmb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gtoashevbf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gtahizasqs.html

Go:   len(arr);  len(m)
来源：http://dali.yueranfly.top/Article/details/gtfjittxhi.html

Ruby: x.length;  x.size
来源：http://dali.jlsjyb.cn/Article/details/gtwahnfhwl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gtmiwlxonf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jlsjyb.cn/Article/details/gtpzruoywo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.mhx1999.top/Article/details/gtvdcdegcu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dashuyun.cn/Article/details/gtscnpjhaz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guannengcc.top/Article/details/gtvohxwqpe.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvttccey.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shuidangran.top/Article/details/gtgowwnkjt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hammf.cn/Article/details/gtiuuwqywk.html

Ruby: a == b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcejljmim.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenzaomai.com/Article/details/gtbkreumye.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgufenzy.top/Article/details/gtnbnlbflg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shuidangran.top/Article/details/gtcrmvcxsa.html

PHP:  if (empty($x)) {}
来源：http://dali.yvedp.cn/Article/details/gtyuuxcspa.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.pengpengdd.cyou/Article/details/gtatbcocsq.html

TS:   if (x == null) {}
来源：http://dali.c1oappe.top/Article/details/gteqjtmfdw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gtnwvqcdvx.html

Go:   if x == nil {}
来源：http://dali.ppjwa.cn/Article/details/gtkbvumpdl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gotoacloud.top/Article/details/gtvmqnlbvc.html

C#:   if (x is null) {}
来源：http://dali.mhx1999.top/Article/details/gtfmtmfylv.html

[P07] 防抖与节流
来源：http://dali.wangdashe.top/Article/details/gthukcczml.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.guannengcc.top/Article/details/gtfzyqurgr.html

PHP:  // 手写时间戳比较
来源：http://dali.9152youxi.cn/Article/details/gtqjzdzuru.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gtrrwiymko.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtuexlcdrx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.9152youxi.cn/Article/details/gtgyeknrml.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cheryme.top/Article/details/gtpbaolewf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dashuyun.cn/Article/details/gtksyobepo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.andypj.xyz/Article/details/gtvfwvubee.html

[P08] 处理浮点精度问题
来源：http://dali.tianlin.xyz/Article/details/gtqbvpeymy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.9152youxi.cn/Article/details/gtrkpetvsh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.quarkkingdee.top/Article/details/gtygzgmwoq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jqgufenzy.top/Article/details/gtkpnxmuzz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdthrtrv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shuidangran.top/Article/details/gtlpovoksm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrdblvrc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xylfe.cn/Article/details/gtarshnnji.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedlsglap.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gteuavbrxd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xuetiantiany.cn/Article/details/gtazcrllab.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtsamgebeg.html

[Q01] 创建表
来源：http://dali.sxryk.cn/Article/details/gtnvfncaye.html

CREATE TABLE users (
来源：http://dali.zhoulong.xyz/Article/details/gtxboalppr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sxryk.cn/Article/details/gtidqbyxer.html

name VARCHAR(50) NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gtbuzayipe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ehwqpu.com/Article/details/gtnimzhkiy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tian-w.cn/Article/details/gtfmukeasg.html

);
来源：http://dali.yangfankeji.com/Article/details/gtovjzktvj.html

[Q02] 创建带外键的表
来源：http://dali.cashguo.top/Article/details/gtdjukapge.html

CREATE TABLE orders (
来源：http://dali.feifeiyinyue.top/Article/details/gtauknuwyt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hammf.cn/Article/details/gtikgmtvps.html

user_id INT NOT NULL,
来源：http://dali.yueranfly.top/Article/details/gtfdxgsfun.html

amount DECIMAL(10, 2),
来源：http://dali.gzhubu.top/Article/details/gtlspscdvk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.pengpengdd.cyou/Article/details/gtjoiulwpp.html

);
来源：http://dali.c1oappe.top/Article/details/gtfxkiyxrh.html

[Q03] 增加列
来源：http://dali.aibaodan.cn/Article/details/gtlrprhoiv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhixingplan.top/Article/details/gtnffhtkgx.html

[Q04] 修改列类型
来源：http://dali.kuanghao11.cn/Article/details/gtnprdeuty.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gtedzwzvgl.html

[Q05] 重命名列
来源：http://dali.daxiang520.top/Article/details/gtridzbqzp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.feifeiyinyue.top/Article/details/gtpccefoct.html

[Q06] 删除列
来源：http://dali.ehwqpu.com/Article/details/gtreogevps.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinghuilouyu.cn/Article/details/gtweelltoo.html

[Q07] 删除表
来源：http://dali.cheryme.top/Article/details/gtugjmtocb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shuidangran.top/Article/details/gtuathkmvf.html

[Q08] 创建普通索引
来源：http://dali.hnqzz.top/Article/details/gtevbhlgxk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sufxvd.cn/Article/details/gtmssfjeaf.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gttbzkzacr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqejwdvp.html

[Q10] 插入单行
来源：http://dali.hfpthk.cn/Article/details/gtgjzqbses.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtmnnorm.html

[Q11] 一次插入多行
来源：http://dali.jinqigufen.top/Article/details/gtsfyuxauo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hammf.cn/Article/details/gtvcbbwgsi.html

[Q12] 插入后取自增 ID
来源：http://dali.meibo888.top/Article/details/gtjnbimkbg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.mhx1999.top/Article/details/gtymkmkixp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jianghu66.top/Article/details/gtrnjxpqpd.html

[Q13] 忽略重复插入
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyzeysta.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gtknpjmjql.html

[Q14] 存在则更新（upsert）
来源：http://dali.xziqi.cn/Article/details/gtfemensrn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.dashuyun.cn/Article/details/gtvvqkwish.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yanxiufei.cn/Article/details/gtoztlpqxt.html

[Q15] 查询全部
来源：http://dali.sweek.top/Article/details/gtidtkgirk.html

SELECT * FROM users;
来源：http://dali.guannengcc.top/Article/details/gtldxwafuh.html

[Q16] 查询指定列
来源：http://dali.hammf.cn/Article/details/gtvsglmjhw.html

SELECT id, name FROM users;
来源：http://dali.tian-w.cn/Article/details/gtewwxaofu.html

[Q17] 条件查询
来源：http://dali.havefunace.top/Article/details/gtiftnawbj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtsktjwmaf.html

[Q18] 模糊匹配
来源：http://dali.jqgufenzy.top/Article/details/gtkpsfjjog.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.snrcjt.cn/Article/details/gtlnqfkwpf.html

[Q19] 范围查询
来源：http://dali.yangfankeji.com/Article/details/gtrmudmoph.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.feifeiyinyue.top/Article/details/gtxmlpfygu.html

[Q20] IN 列表
来源：http://dali.redwolf501.top/Article/details/gtkyiivdom.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.meibo888.top/Article/details/gthkebasct.html

[Q21] 空值判断
来源：http://dali.jqgfzy.top/Article/details/gtdzfqxfnx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.snrcjt.cn/Article/details/gtrmbwvkps.html

[Q22] 排序
来源：http://dali.ivvv.top/Article/details/gtziuwzttl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj20258888.top/Article/details/gturkpgbkv.html

[Q23] 分页
来源：http://dali.svipenyu.cn/Article/details/gtfybnzqbh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pycfn.com/Article/details/gtjhaygfqy.html

[Q24] 去重
来源：http://dali.haohaochexian.top/Article/details/gtrcqlvecb.html

SELECT DISTINCT city FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtyikeygrd.html

[Q25] 只取前 N 条
来源：http://dali.xuetiantiany.cn/Article/details/gtzjjaklnz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.smart0.xyz/Article/details/gtvhjdgtwv.html

[Q26] 计数
来源：http://dali.sxryk.cn/Article/details/gtkccdudji.html

SELECT COUNT(*) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyaqxsbwq.html

[Q27] 条件计数
来源：http://dali.yuxming.cn/Article/details/gteztbvusg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtfjmvyfhg.html

[Q28] 求和与平均
来源：http://dali.tian-w.cn/Article/details/gtmujvrtoi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtyxttlrtf.html

[Q29] 最大最小值
来源：http://dali.cdnleiting.top/Article/details/gtzcwjqmjr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtnaqknzbk.html

[Q30] 分组统计
来源：http://dali.cashguo.top/Article/details/gtpgmcgrzr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gtvvmsdzri.html

[Q31] 分组后过滤
来源：http://dali.daria6918.cn/Article/details/gtphvsdthf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tian-w.cn/Article/details/gtferavizg.html

[Q32] 分组拼接字符串
来源：http://dali.jianghu66.top/Article/details/gtjusllmak.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gtrlvwlpzg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ppjwa.cn/Article/details/gtumgyqpdf.html

[Q33] 多列分组
来源：http://dali.snrcjt.cn/Article/details/gtrzqaufis.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinghuilouyu.cn/Article/details/gthamkneov.html

[Q34] 每组取第一条
来源：http://dali.c1oappe.top/Article/details/gtbctmtfdq.html

SELECT * FROM (
来源：http://dali.xylfe.cn/Article/details/gtllurdqun.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.feifeiyinyue.top/Article/details/gtltbcnyfs.html

) t WHERE rn = 1;
来源：http://dali.yuxming.cn/Article/details/gtaujcwgde.html

[Q35] 内连接
来源：http://dali.hfpthk.cn/Article/details/gtuniavdbz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgufenzy.top/Article/details/gtlwgniagq.html

[Q36] 左连接
来源：http://dali.bjfxy.top/Article/details/gtlwijefwi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jyoumei.cn/Article/details/gtzcbppqeg.html

[Q37] 右连接
来源：http://dali.guowangkeji.top/Article/details/gtrzabrgqb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yueranfly.top/Article/details/gtvghwnufw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.dianchejie.cn/Article/details/gtqznytxjc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zdqjudy.top/Article/details/gtunetsabh.html

[Q39] 自连接（查上下级）
来源：http://dali.jlsjyb.cn/Article/details/gtvwnxxfru.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxinkj.top/Article/details/gtmovvsale.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cucudq.cn/Article/details/gtmzqzpygu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zdqjudy.top/Article/details/gtwbjavyxo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenzaomai.com/Article/details/gtclajwwec.html

[Q41] 多表连接
来源：http://dali.sweek.top/Article/details/gtqwtyyokc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shuidangran.top/Article/details/gtuljbwtwi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinqigufen.top/Article/details/gtrqutpqzf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sufxvd.cn/Article/details/gtkbuxeoru.html

[Q42] 连接条件附加过滤
来源：http://dali.zhoulong.xyz/Article/details/gtlygdubxk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznaqawpa.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgfzy.top/Article/details/gtiyyaeuhj.html

[Q43] 标量子查询
来源：http://dali.snrcjt.cn/Article/details/gtjugtfufi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.quarkkingdee.top/Article/details/gtkfffbapn.html

[Q44] IN 子查询
来源：http://dali.feifeiyinyue.top/Article/details/gtcrbfqhcu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yvedp.cn/Article/details/gtdtvcmflg.html

[Q45] EXISTS 判断存在
来源：http://dali.haohaochexian.top/Article/details/gtikjibfkx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.316326.xyz/Article/details/gtgbujgqsx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.feifeiyinyue.top/Article/details/gtvmzvlakh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhongyouzk.top/Article/details/gthamaxpqt.html

[Q47] 与平均值比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrlcfynk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwspormxj.html

[Q48] CTE 公用表表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxirylkvi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yanxiufei.cn/Article/details/gtnkboonyy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.vqdsnc.cn/Article/details/gttdkbfuou.html

[Q49] 更新单行
来源：http://dali.zdqjudy.top/Article/details/gtyamrkpep.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yanxiufei.cn/Article/details/gtzidrjrmp.html

[Q50] 批量更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmtonykk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jqgfzy.top/Article/details/gtpgahpntn.html

[Q51] 用子查询更新
来源：http://dali.zhiwuduotai.top/Article/details/gthjoxiwfu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cucudq.cn/Article/details/gtgpfukqhe.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gtldyxiyer.html

DELETE FROM users WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gtpdyqnyny.html

[Q53] 按条件删除
来源：http://dali.zdqjudy.top/Article/details/gtehlsdher.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gtbmkikvgz.html

[Q54] 清空表
来源：http://dali.bjfxy.top/Article/details/gtqszyelir.html

TRUNCATE TABLE logs;
来源：http://dali.cdnleiting.top/Article/details/gtbykjvqlh.html

[Q55] 排名（并列占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbphcwzpt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gtuzvavoux.html

[Q56] 密集排名（并列不占位）
来源：http://dali.havefunace.top/Article/details/gthhjurglw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xylfe.cn/Article/details/gtuzatrtlx.html

[Q57] 行号
来源：http://dali.zdqjudy.top/Article/details/gtqxaxtcon.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtnazvwgjk.html

[Q58] 累计求和
来源：http://dali.cashguo.top/Article/details/gtbzhgcxjr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtzzlixbih.html

[Q59] 分组内累计
来源：http://dali.jinqigfzy.top/Article/details/gtuvkorrca.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtzoirhwhq.html

[Q60] 取上一行 / 下一行
来源：http://dali.hammf.cn/Article/details/gtclcaducz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangdashe.top/Article/details/gthqcgmdrg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pycfn.com/Article/details/gtltdvsshi.html

[Q61] 移动平均
来源：http://dali.zycfv.cn/Article/details/gtvhydhnca.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtbrnhpkio.html

[Q62] 分组占比
来源：http://dali.9152youxi.cn/Article/details/gtgupeaagg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gtwmaimvyc.html

[Q63] 开启事务
来源：http://dali.jinqigufen.top/Article/details/gtivpmrnoq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.meibo888.top/Article/details/gtsedkbkjm.html

[Q64] 提交事务
来源：http://dali.yangfankeji.com/Article/details/gtugqyemln.html

COMMIT;
来源：http://dali.chenlongwang.top/Article/details/gtgmnyvkqj.html


<!-- 参考信息 -->