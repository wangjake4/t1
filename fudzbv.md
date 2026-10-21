代发 wailian999

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuxming.cn/Article/details/gtqgyrafal.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aibaodan.cn/Article/details/gtvcfwgugl.html

[N11] 二叉树中序遍历
来源：http://dali.svipenyu.cn/Article/details/gthrkxujkq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guannengcc.top/Article/details/gtnycgkrgp.html

PHP:  // 手写递归函数
来源：http://dali.sufxvd.cn/Article/details/gtewbqsfgy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gtmuxeccib.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cashguo.top/Article/details/gtunzlllyr.html

Java: // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtkcjbrvjk.html

Go:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtmydxfsbf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhengqikj.top/Article/details/gtsazmwmga.html

C#:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gtchkuzbzu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhixingplan.top/Article/details/gtbpbgxcsy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.guowangkeji.top/Article/details/gtehplwlzt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxdvoaffe.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gtxaypywth.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pycfn.com/Article/details/gtqzuzteur.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gtvdvlrihv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258.top/Article/details/gtqqklwwvc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ehwqpu.com/Article/details/gtszpvkmup.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gtxnhfxsfq.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtmfapgnwa.html

O. 并发与异步
来源：http://dali.hfpthk.cn/Article/details/gtuyacxtmm.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtzylysraa.html

[O01] 启动一个线程
来源：http://dali.yvedp.cn/Article/details/gtlbzkydgp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenjidiqi.icu/Article/details/gtgmeydybt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.andypj.xyz/Article/details/gtxacxytqx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj202588.top/Article/details/gtygmjviye.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gtkyuysyan.html

Java: new Thread(() -> f()).start()
来源：http://dali.xuetiantiany.cn/Article/details/gtroossknn.html

Go:   go f()
来源：http://dali.daria6918.cn/Article/details/gteiuirxhi.html

Ruby: Thread.new { f }
来源：http://dali.zycfv.cn/Article/details/gtivgumcki.html

C#:   Task.Run(() => F());
来源：http://dali.dianchejie.cn/Article/details/gtxptanyrm.html

[O02] 使用线程池
来源：http://dali.vqdsnc.cn/Article/details/gtbpawiijp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gtsjdgbtcs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.svipenyu.cn/Article/details/gtfsbdiixc.html

JS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gtyfazctji.html

TS:   // worker_threads 线程池
来源：http://dali.redwolf501.top/Article/details/gtxcorwzfe.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhiwuduotai.top/Article/details/gtvgwtzevm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxinkj.top/Article/details/gtviruuorj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aizwys.cn/Article/details/gtbckluzjo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhongyouzk.top/Article/details/gtnuqbizbi.html

[O03] 加锁保护共享数据
来源：http://dali.guowangkeji.top/Article/details/gtrildpnxv.html

Py:   with lock: shared += 1
来源：http://dali.zhiwuduotai.top/Article/details/gtzgbdlbjj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.meibo888.top/Article/details/gtfkuafsbz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntdonrqc.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gtgwkgmfxb.html

Java: synchronized (this) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gtjrrmivld.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xylfe.cn/Article/details/gtpomtflqe.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ybcxt.top/Article/details/gtariorxpk.html

C#:   lock (gate) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gtnxljgndr.html

[O04] 定义异步函数并等待
来源：http://dali.xuetiantiany.cn/Article/details/gtvfajsvhu.html

Py:   async def f():⏎    await g()
来源：http://dali.hnqzz.top/Article/details/gtesrmtaco.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzoootjw.html

JS:   async function f() { await g(); }
来源：http://dali.redwolf501.top/Article/details/gtimmypwfv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ivvv.top/Article/details/gtmzvnwjkk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yvedp.cn/Article/details/gtizfdkbms.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jyoumei.cn/Article/details/gtjjacjduc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guowangkeji.top/Article/details/gtqqwdvkzp.html

C#:   async Task F() { await G(); }
来源：http://dali.gzhubu.top/Article/details/gtcmxsivph.html

[O05] 并发执行并等待全部完成
来源：http://dali.ybcxt.top/Article/details/gtyrxjczxr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtromenfqr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj202588.top/Article/details/gtfjazzmqn.html

JS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gteatwmlcx.html

TS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gtgsxcjuag.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yvedp.cn/Article/details/gtdvoedhpm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zdqjudy.top/Article/details/gtifdljutz.html

Ruby: threads.map(&:join)
来源：http://dali.wangdashe.top/Article/details/gtqwmbebra.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nanxuanxn.top/Article/details/gtludrangu.html

[O06] 使用进程池
来源：http://dali.zhoulong.xyz/Article/details/gtxnykjkpl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenlongwang.top/Article/details/gtfzrvelmr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.meibo888.top/Article/details/gtcqxsuppq.html

JS:   // child_process / cluster 模块
来源：http://dali.zhoulong.xyz/Article/details/gtyvqnucom.html

TS:   // child_process / cluster 模块
来源：http://dali.guannengcc.top/Article/details/gtagkoxttt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjovidna.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gaohongyu789.top/Article/details/gtnosvcxaa.html

Ruby: // fork 块
来源：http://dali.smart0.xyz/Article/details/gtrhiguwje.html

C#:   Parallel.For
来源：http://dali.zhongyouzk.top/Article/details/gtrfxiuoqp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtzcjtmgub.html

P. 常用工具函数
来源：http://dali.xuanzx.com/Article/details/gtcfsxshrv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtxebcarsr.html

[P01] 生成 UUID
来源：http://dali.andypj.xyz/Article/details/gtcrmvrhkm.html

Py:   str(uuid.uuid4())
来源：http://dali.daxiang520.top/Article/details/gtfwpudqsa.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gtfemahfig.html

JS:   crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gtrawglduo.html

TS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtbmkxojvz.html

Java: UUID.randomUUID().toString()
来源：http://dali.svipenyu.cn/Article/details/gtzyrdxdjf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guannengcc.top/Article/details/gtqkgwuomg.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigufen.top/Article/details/gtrksbzwsc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.iojbl.cn/Article/details/gticehmqwj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.snrcjt.cn/Article/details/gtbvrvzbem.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.andypj.xyz/Article/details/gtmfqihpgh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sysykeji.top/Article/details/gtgweurmmp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aibaodan.cn/Article/details/gtatepvbru.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.fengsongda.top/Article/details/gtrsnpsfsa.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cheryme.top/Article/details/gtzdqaxszu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.haohaochexian.top/Article/details/gtdubaxlnm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuanzx.com/Article/details/gtmjlfusrz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xinyue.icu/Article/details/gtncybhfja.html

[P03] 生成短随机字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtauovjcgh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gotoacloud.top/Article/details/gtbpevmzlu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gaohongyu789.top/Article/details/gtqoesafvs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gtfvxiaugg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gtexnugdmh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nwbrower.top/Article/details/gtlrddrqty.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jqgfzy.top/Article/details/gtdpylbuam.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.birdmap.top/Article/details/gtkelipwwy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.pengpengdd.cyou/Article/details/gtqqcgkund.html

[P04] 求长度
来源：http://dali.c1oappe.top/Article/details/gtzfhzogng.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jianghu66.top/Article/details/gtdghtatxs.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtplsoddae.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscachpey.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nwbrower.top/Article/details/gtfoklasci.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jianghu66.top/Article/details/gtspgarced.html

Go:   len(arr);  len(m)
来源：http://dali.jinqigufen.top/Article/details/gtecfcvshc.html

Ruby: x.length;  x.size
来源：http://dali.sufxvd.cn/Article/details/gtwbawvwmr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shuidangran.top/Article/details/gtqfpgybnc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.mhx1999.top/Article/details/gtaggfxdid.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.svipenyu.cn/Article/details/gtebfsowcy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.feifeiyinyue.top/Article/details/gttipfgcnf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sufxvd.cn/Article/details/gtsrhfozmr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gtvdbzhhhj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hongshengwenyu.top/Article/details/gtkfjmmiba.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gtllrelswk.html

Ruby: a == b
来源：http://dali.316326.xyz/Article/details/gtsidjfahs.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.fengsongda.top/Article/details/gthwdfqwnf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnqzz.top/Article/details/gthxjvfpdb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yongpay.top/Article/details/gtanbudkfl.html

PHP:  if (empty($x)) {}
来源：http://dali.xziqi.cn/Article/details/gtjblgmhne.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenzaomai.com/Article/details/gtuqqeoinm.html

TS:   if (x == null) {}
来源：http://dali.tian-w.cn/Article/details/gtmwrgbhgb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gtpggqmpan.html

Go:   if x == nil {}
来源：http://dali.fzhhl.top/Article/details/gtlbphxssu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258.top/Article/details/gtfvqusdrz.html

C#:   if (x is null) {}
来源：http://dali.xinyue.icu/Article/details/gtgluousqx.html

[P07] 防抖与节流
来源：http://dali.316326.xyz/Article/details/gtgnulvmkh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tian-w.cn/Article/details/gtqynoapip.html

PHP:  // 手写时间戳比较
来源：http://dali.xuetiantiany.cn/Article/details/gtelkoztgu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gtwytxigcs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gtzijaghwc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.smart0.xyz/Article/details/gtycnlneqd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.andypj.xyz/Article/details/gtvsabufhw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cashguo.top/Article/details/gthcbhrvrs.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cashguo.top/Article/details/gtmjfhwrft.html

[P08] 处理浮点精度问题
来源：http://dali.chenzaomai.com/Article/details/gtjzikpjyw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cucudq.cn/Article/details/gtmvgjknta.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shangyingyoupin.top/Article/details/gthetnntci.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinqigufen.top/Article/details/gtfzfxebmf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.aibaodan.cn/Article/details/gtghihkozr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nanxinkj.top/Article/details/gtcnkxkwoh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.mhx1999.top/Article/details/gtfofossxk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.nwbrower.top/Article/details/gtlsmgoaji.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hongshengwenyu.top/Article/details/gtsgwvrdlh.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtwsytwydj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gaohongyu789.top/Article/details/gtkegqwmah.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtwgfxlmym.html

[Q01] 创建表
来源：http://dali.pycfn.com/Article/details/gtfahidsiq.html

CREATE TABLE users (
来源：http://dali.guannengcc.top/Article/details/gtcwmnebco.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guannengcc.top/Article/details/gtihqcygat.html

name VARCHAR(50) NOT NULL,
来源：http://dali.andypj.xyz/Article/details/gtvvovwnle.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nwbrower.top/Article/details/gtxuwpilwh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigfzy.top/Article/details/gtluipvgrn.html

);
来源：http://dali.xinyue.icu/Article/details/gtgasmeztu.html

[Q02] 创建带外键的表
来源：http://dali.havefunace.top/Article/details/gtmdlkuieh.html

CREATE TABLE orders (
来源：http://dali.yangfankeji.com/Article/details/gtdevicrcb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ybcxt.top/Article/details/gtkivudirw.html

user_id INT NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gtnojwqcep.html

amount DECIMAL(10, 2),
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmshecwj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guowangkeji.top/Article/details/gtcvmrncya.html

);
来源：http://dali.smart0.xyz/Article/details/gtdthkfbdk.html

[Q03] 增加列
来源：http://dali.c1oappe.top/Article/details/gtstprwksp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jyoumei.cn/Article/details/gtfviwumbc.html

[Q04] 修改列类型
来源：http://dali.chenlongwang.top/Article/details/gtdfqqvptf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yvedp.cn/Article/details/gttwngxfwa.html

[Q05] 重命名列
来源：http://dali.jinqigfzy.top/Article/details/gtdysgbmpx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aibaodan.cn/Article/details/gttnubxqvq.html

[Q06] 删除列
来源：http://dali.chenzaomai.com/Article/details/gttahxbeax.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinghuilouyu.cn/Article/details/gtpfkfyfcq.html

[Q07] 删除表
来源：http://dali.snrcjt.cn/Article/details/gtmdcfwkdv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.c1oappe.top/Article/details/gtihdophml.html

[Q08] 创建普通索引
来源：http://dali.hywenlv.cn/Article/details/gthgoxdryl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hysaishi.cn/Article/details/gtmyuhxstt.html

[Q09] 创建唯一索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfanlsoxb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gtwfwtaxqi.html

[Q10] 插入单行
来源：http://dali.xuetiantiany.cn/Article/details/gtflbbbrmq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtdlhxwc.html

[Q11] 一次插入多行
来源：http://dali.nwbrower.top/Article/details/gtkyxnjuqz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hammf.cn/Article/details/gtdwiwjfxu.html

[Q12] 插入后取自增 ID
来源：http://dali.yueranfly.top/Article/details/gtqtebbwnn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xuetiantiany.cn/Article/details/gtzduotdzw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xziqi.cn/Article/details/gtntlzknpe.html

[Q13] 忽略重复插入
来源：http://dali.shzxlz.cn/Article/details/gtiafljpnf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ppjwa.cn/Article/details/gtpelleefj.html

[Q14] 存在则更新（upsert）
来源：http://dali.gogol.net.cn/Article/details/gtyqlhwerq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gthhyvpxkk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.haohaochexian.top/Article/details/gtqxprjezj.html

[Q15] 查询全部
来源：http://dali.yanxiufei.cn/Article/details/gtnqmiuwrn.html

SELECT * FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxyugtlw.html

[Q16] 查询指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gtjganyqby.html

SELECT id, name FROM users;
来源：http://dali.sweek.top/Article/details/gtutzdbnvc.html

[Q17] 条件查询
来源：http://dali.daxiang520.top/Article/details/gtzcvwxdee.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtileypzlb.html

[Q18] 模糊匹配
来源：http://dali.birdmap.top/Article/details/gtnuvvszml.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sweek.top/Article/details/gtozhpneku.html

[Q19] 范围查询
来源：http://dali.ybcxt.top/Article/details/gtmiwsipuc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yueranfly.top/Article/details/gtysuacmir.html

[Q20] IN 列表
来源：http://dali.hnxiangtu.top/Article/details/gtebgsbsxe.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkkunxst.html

[Q21] 空值判断
来源：http://dali.cashguo.top/Article/details/gtakrpkngf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guannengcc.top/Article/details/gtqiylnxxz.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gtoqfkwgdi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yongpay.top/Article/details/gtffkwulbg.html

[Q23] 分页
来源：http://dali.hysaishi.cn/Article/details/gtjpwwoayl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yonumen.top/Article/details/gtnkwrmqrr.html

[Q24] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppxzzdma.html

SELECT DISTINCT city FROM users;
来源：http://dali.nwbrower.top/Article/details/gturewjzan.html

[Q25] 只取前 N 条
来源：http://dali.iojbl.cn/Article/details/gtkvbayjzh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zdqjudy.top/Article/details/gtitxgjdnt.html

[Q26] 计数
来源：http://dali.wangshuangyany.cn/Article/details/gtstcpmqra.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gthfvbxxob.html

[Q27] 条件计数
来源：http://dali.sxryk.cn/Article/details/gthzbzojkz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtpvwwjesn.html

[Q28] 求和与平均
来源：http://dali.yuxming.cn/Article/details/gtxieoqwne.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqdmuaem.html

[Q29] 最大最小值
来源：http://dali.jyoumei.cn/Article/details/gtenszyqhi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtxsxvuxkc.html

[Q30] 分组统计
来源：http://dali.pycfn.com/Article/details/gtysdfqxzq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtbslgpbdu.html

[Q31] 分组后过滤
来源：http://dali.xziqi.cn/Article/details/gthwooejpt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xinyue.icu/Article/details/gtudblwnsl.html

[Q32] 分组拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtzglcfrht.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gthistkkot.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yueranfly.top/Article/details/gtrijykftx.html

[Q33] 多列分组
来源：http://dali.zhongyouzk.top/Article/details/gtjucpoqse.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.0kj1m.cn/Article/details/gtwiabikum.html

[Q34] 每组取第一条
来源：http://dali.yuxming.cn/Article/details/gtfprdooeo.html

SELECT * FROM (
来源：http://dali.ppjwa.cn/Article/details/gtvtpxcpds.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ehwqpu.com/Article/details/gtwpmqbfrf.html

) t WHERE rn = 1;
来源：http://dali.aizwys.cn/Article/details/gtyluikrki.html

[Q35] 内连接
来源：http://dali.xinyue.icu/Article/details/gtrpgdihka.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cqqwz.cn/Article/details/gtjwuspnvs.html

[Q36] 左连接
来源：http://dali.zycfv.cn/Article/details/gtznezigsf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gtyomptijr.html

[Q37] 右连接
来源：http://dali.chenjidiqi.icu/Article/details/gtiduvepql.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.redwolf501.top/Article/details/gtujxfoorq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgoqtzli.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.redwolf501.top/Article/details/gtifvdegia.html

[Q39] 自连接（查上下级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhtpwtgw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jiagoushi.top/Article/details/gtkqmlurzk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ppjwa.cn/Article/details/gtrphrxeip.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.feifeiyinyue.top/Article/details/gtuqfhkpwe.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cashguo.top/Article/details/gtyuspddjz.html

[Q41] 多表连接
来源：http://dali.andypj.xyz/Article/details/gtaqribpna.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhoulong.xyz/Article/details/gttvhkjjbc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sweek.top/Article/details/gtitmuzikt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hnxiangtu.top/Article/details/gtzthzcius.html

[Q42] 连接条件附加过滤
来源：http://dali.andypj.xyz/Article/details/gtvtgzunvm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pengpengdd.cyou/Article/details/gthudggzsh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xuanzx.com/Article/details/gteuhjbepo.html

[Q43] 标量子查询
来源：http://dali.c1oappe.top/Article/details/gtpxtndgpj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xinyue.icu/Article/details/gtxisrysla.html

[Q44] IN 子查询
来源：http://dali.tian-w.cn/Article/details/gtenqpupec.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ppjwa.cn/Article/details/gtkphlohtj.html

[Q45] EXISTS 判断存在
来源：http://dali.pycfn.com/Article/details/gtovtmtpfv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenlongwang.top/Article/details/gtqkencjyy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.feifeiyinyue.top/Article/details/gtwlukjufn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dianchejie.cn/Article/details/gthuwnfqrp.html

[Q47] 与平均值比较
来源：http://dali.xziqi.cn/Article/details/gtguylerdr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.316326.xyz/Article/details/gtqjicjiaf.html

[Q48] CTE 公用表表达式
来源：http://dali.sxryk.cn/Article/details/gtbmhjxwuv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtkoahqc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sweek.top/Article/details/gtretmyidw.html

[Q49] 更新单行
来源：http://dali.yuanzhike.top/Article/details/gtnvdzlwdu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gaohongyu789.top/Article/details/gtuyxmacsr.html

[Q50] 批量更新
来源：http://dali.xylfe.cn/Article/details/gttlfnwemo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xuetiantiany.cn/Article/details/gttnsbhofm.html

[Q51] 用子查询更新
来源：http://dali.hongshengwenyu.top/Article/details/gtlggsisxm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yueranfly.top/Article/details/gthgswbtiz.html

[Q52] 删除指定行
来源：http://dali.yuanzhike.top/Article/details/gtbiytybsn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gtdlckggyt.html

[Q53] 按条件删除
来源：http://dali.daria6918.cn/Article/details/gtqitnakwu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gttvdrxxqh.html

[Q54] 清空表
来源：http://dali.nanxinkj.top/Article/details/gtxipijvwj.html

TRUNCATE TABLE logs;
来源：http://dali.haohaochexian.top/Article/details/gtawtpfghq.html

[Q55] 排名（并列占位）
来源：http://dali.yanxiufei.cn/Article/details/gtzegbinrc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cucudq.cn/Article/details/gtdxljkpcu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zycfv.cn/Article/details/gtrfuivapf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aizwys.cn/Article/details/gtjwlgbqib.html

[Q57] 行号
来源：http://dali.chenzaomai.com/Article/details/gttbfwtdfd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtjmhblyqn.html

[Q58] 累计求和
来源：http://dali.snrcjt.cn/Article/details/gtxpcnhxcg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.birdmap.top/Article/details/gtpscjtcex.html

[Q59] 分组内累计
来源：http://dali.yonumen.top/Article/details/gtbdcdyugl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtiqcoopkg.html

[Q60] 取上一行 / 下一行
来源：http://dali.jiagoushi.top/Article/details/gtauazkdvt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tianlin.xyz/Article/details/gttarkrjec.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtljevtans.html

[Q61] 移动平均
来源：http://dali.zhoulong.xyz/Article/details/gtsiedanhp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtmmirnvtr.html

[Q62] 分组占比
来源：http://dali.gzhubu.top/Article/details/gtyhycmxcs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlgukxol.html


<!-- 参考信息 -->