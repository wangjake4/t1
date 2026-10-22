代发 wailian999

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aizwys.cn/Article/details/gt2cwlbqroj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yanxiufei.cn/Article/details/gt2kvlvhppm.html

Java: class Node { int v; Node next; }
来源：http://dali.aizwys.cn/Article/details/gt2ijuatsqj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhongyouzk.top/Article/details/gt2mtleatkw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.andypj.xyz/Article/details/gt2apuovnzp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenzaomai.com/Article/details/gt2rgwknqox.html

[N11] 二叉树中序遍历
来源：http://dali.xziqi.cn/Article/details/gt2pxzauuwy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenzaomai.com/Article/details/gt2mqvjlsqa.html

PHP:  // 手写递归函数
来源：http://dali.mhx1999.top/Article/details/gt2akvbufqf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gt2ixxcvlfv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gt2jlrjflao.html

Java: // 手写递归
来源：http://dali.daria6918.cn/Article/details/gt2igelmskl.html

Go:   // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gt2bmgeffqj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guannengcc.top/Article/details/gt2xnbgygxp.html

C#:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gt2tbllffaq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhixingplan.top/Article/details/gt2dympkowb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xuanzx.com/Article/details/gt2lmvisdkf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tianlin.xyz/Article/details/gt2tkekkvxo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnqzz.top/Article/details/gt2bbszcjpg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gt2mdwdwqto.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gt2tyuaeznn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.svipenyu.cn/Article/details/gt2rfklwuou.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gogol.net.cn/Article/details/gt2tyjuvgcd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zaryzuvi.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2iznoueqk.html

O. 并发与异步
来源：http://dali.feifeiyinyue.top/Article/details/gt2mvflgpuy.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2xcmryktl.html

[O01] 启动一个线程
来源：http://dali.svipenyu.cn/Article/details/gt2tjvgphja.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yueranfly.top/Article/details/gt2ojabowcf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ppjwa.cn/Article/details/gt2smebkaun.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ppjwa.cn/Article/details/gt2czkxjmrr.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gt2ffbyrfym.html

Java: new Thread(() -> f()).start()
来源：http://dali.hongshengwenyu.top/Article/details/gt2tejnntre.html

Go:   go f()
来源：http://dali.gotoacloud.top/Article/details/gt2wwvbztfd.html

Ruby: Thread.new { f }
来源：http://dali.tanke756.top/Article/details/gt2ovapktvp.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfvwywv.html

[O02] 使用线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jytesqxl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ivvv.top/Article/details/gt2qyajsvaf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.meibo888.top/Article/details/gt2jqfsyfsu.html

JS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gt2kxrmicuh.html

TS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gt2vbrpnbzb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yanxiufei.cn/Article/details/gt2dhwbrphg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.feifeiyinyue.top/Article/details/gt2dnedhciz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ybcxt.top/Article/details/gt2pbhyghvs.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhengqikj.top/Article/details/gt2hugpdceb.html

[O03] 加锁保护共享数据
来源：http://dali.kuanghao11.cn/Article/details/gt2uxvlfjof.html

Py:   with lock: shared += 1
来源：http://dali.hammf.cn/Article/details/gt2yclnfswg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhengqikj.top/Article/details/gt2xyxlrlqb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cheryme.top/Article/details/gt2jlaluwkm.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gt2spzevtca.html

Java: synchronized (this) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gt2ubkjehin.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.feifeiyinyue.top/Article/details/gt2rxjislfx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shzxlz.cn/Article/details/gt2rvepuqix.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2uzxnxhsn.html

[O04] 定义异步函数并等待
来源：http://dali.fengsongda.top/Article/details/gt2kaddmabo.html

Py:   async def f():⏎    await g()
来源：http://dali.haohaochexian.top/Article/details/gt2ubacktnx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinqigufen.top/Article/details/gt2wwfiehvy.html

JS:   async function f() { await g(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2xsjlvmod.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tian-w.cn/Article/details/gt2ahvwsglg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258888.top/Article/details/gt2ngmdgbky.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sweek.top/Article/details/gt2ojekowcf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dashuyun.cn/Article/details/gt2ajobsujp.html

C#:   async Task F() { await G(); }
来源：http://dali.tian-w.cn/Article/details/gt2xlitrhat.html

[O05] 并发执行并等待全部完成
来源：http://dali.jianghu66.top/Article/details/gt2jpcpzwfe.html

Py:   asyncio.gather(*tasks)
来源：http://dali.vqdsnc.cn/Article/details/gt2gxraywcs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tianlin.xyz/Article/details/gt2rlpvfuzq.html

JS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gt2umtpqqam.html

TS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gt2eayjpkds.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yangfankeji.com/Article/details/gt2tbtlacwh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2czddfrto.html

Ruby: threads.map(&:join)
来源：http://dali.dianchejie.cn/Article/details/gt2ncluzjbm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yueranfly.top/Article/details/gt2iatwngvu.html

[O06] 使用进程池
来源：http://dali.redwolf501.top/Article/details/gt2kpzixtni.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258888.top/Article/details/gt2jpoczjdp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fengsongda.top/Article/details/gt2mwkiftbh.html

JS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gt2ewtpyqpm.html

TS:   // child_process / cluster 模块
来源：http://dali.hysaishi.cn/Article/details/gt2ruelmnwu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuxming.cn/Article/details/gt2rqbmketm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenlongwang.top/Article/details/gt2gewndysp.html

Ruby: // fork 块
来源：http://dali.quarkkingdee.top/Article/details/gt2srgqvvoz.html

C#:   Parallel.For
来源：http://dali.yuanzhike.top/Article/details/gt2tjwbkobz.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2wzuvpdzj.html

P. 常用工具函数
来源：http://dali.hnqzz.top/Article/details/gt2gtguivkh.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2bogbvrqp.html

[P01] 生成 UUID
来源：http://dali.aibaodan.cn/Article/details/gt2fqawlkgb.html

Py:   str(uuid.uuid4())
来源：http://dali.aibaodan.cn/Article/details/gt2iircvxnl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nyxuusck.html

JS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gt2ewficgfz.html

TS:   crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gt2vesezrjb.html

Java: UUID.randomUUID().toString()
来源：http://dali.hywenlv.cn/Article/details/gt2htwfaxpy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.kuanghao11.cn/Article/details/gt2dkfbwndt.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258.top/Article/details/gt2mpgxbbfu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2clwdjlpx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cucudq.cn/Article/details/gt2khjnrdsm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cqqwz.cn/Article/details/gt2tqrejyte.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ehwqpu.com/Article/details/gt2vfqobtph.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aizwys.cn/Article/details/gt2xgjmakhb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cashguo.top/Article/details/gt2vabrqrdl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.c1oappe.top/Article/details/gt2eqcdaatk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shzxlz.cn/Article/details/gt2oolpkqpn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ehwqpu.com/Article/details/gt2eespcywp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zycfv.cn/Article/details/gt2dajfcxcf.html

[P03] 生成短随机字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2edxzpixd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenzaomai.com/Article/details/gt2vwvvakec.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gotoacloud.top/Article/details/gt2rirlzzhl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aizwys.cn/Article/details/gt2znwighsj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuxming.cn/Article/details/gt2yldyfqgf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yonumen.top/Article/details/gt2ogtnojpd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shuidangran.top/Article/details/gt2czkuljsu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yuxming.cn/Article/details/gt2cschrdct.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuxming.cn/Article/details/gt2rkvqosct.html

[P04] 求长度
来源：http://dali.hammf.cn/Article/details/gt2zsblhvsi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zycfv.cn/Article/details/gt2crhvzsnq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gt2cweuftuk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wdpvstti.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yongpay.top/Article/details/gt2jessmeqn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cucudq.cn/Article/details/gt2pmlpdlxe.html

Go:   len(arr);  len(m)
来源：http://dali.hfpthk.cn/Article/details/gt2mlufdoge.html

Ruby: x.length;  x.size
来源：http://dali.havefunace.top/Article/details/gt2fpwkkdge.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.meibo888.top/Article/details/gt2adgintuu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhixingplan.top/Article/details/gt2hrzyuvvb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fvgblrcw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.316326.xyz/Article/details/gt2xdjxqjwu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigfzy.top/Article/details/gt2sampoxxq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pycfn.com/Article/details/gt2oayrmjdt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhiwuduotai.top/Article/details/gt2qfwtyqbz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hnqzz.top/Article/details/gt2bydhqbcc.html

Ruby: a == b
来源：http://dali.xziqi.cn/Article/details/gt2imcjotlh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.9152youxi.cn/Article/details/gt2nyiftmuf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xylfe.cn/Article/details/gt2buwsiprg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zdqjudy.top/Article/details/gt2hsqjwqla.html

PHP:  if (empty($x)) {}
来源：http://dali.xylfe.cn/Article/details/gt2nfmwzjdl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.quarkkingdee.top/Article/details/gt2dxlstpjn.html

TS:   if (x == null) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2eaftuckt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zycfv.cn/Article/details/gt2wtcelfnw.html

Go:   if x == nil {}
来源：http://dali.yvedp.cn/Article/details/gt2qmoyprgr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.iojbl.cn/Article/details/gt2hhgpehev.html

C#:   if (x is null) {}
来源：http://dali.jinqigufen.top/Article/details/gt2bluixzrm.html

[P07] 防抖与节流
来源：http://dali.guannengcc.top/Article/details/gt2ntgdatpb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.vqdsnc.cn/Article/details/gt2ejnwhjzg.html

PHP:  // 手写时间戳比较
来源：http://dali.yuanzhike.top/Article/details/gt2urhokwxh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gt2ezzqxrpt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gt2ktjdittl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aibaodan.cn/Article/details/gt2jrfewgqw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.9152youxi.cn/Article/details/gt2tycldivt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nwbrower.top/Article/details/gt2bqopfvqx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hfpthk.cn/Article/details/gt2fwbgynxn.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwvtcap.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nwbrower.top/Article/details/gt2sxcuwril.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenzaomai.com/Article/details/gt2iwktcxsq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.9152youxi.cn/Article/details/gt2kzlfrfbs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guowangkeji.top/Article/details/gt2joqcccdb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuetiantiany.cn/Article/details/gt2kgxnxycl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aizwys.cn/Article/details/gt2fshqwexy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.0kj1m.cn/Article/details/gt2pfxktsbb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.andypj.xyz/Article/details/gt2ezddkacj.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2giruskyo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hywenlv.cn/Article/details/gt2uthnwbro.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2mzofldrp.html

[Q01] 创建表
来源：http://dali.yangfankeji.com/Article/details/gt2ghxffhao.html

CREATE TABLE users (
来源：http://dali.jlsjyb.cn/Article/details/gt2sxmyjsvh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gt2foxakhrw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zdqjudy.top/Article/details/gt2ucmuyzes.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yongpay.top/Article/details/gt2ascqxcpj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jyoumei.cn/Article/details/gt2xghlvoiy.html

);
来源：http://dali.cqqwz.cn/Article/details/gt2gmzxnaav.html

[Q02] 创建带外键的表
来源：http://dali.hfpthk.cn/Article/details/gt2dkhpuuve.html

CREATE TABLE orders (
来源：http://dali.nanxinkj.top/Article/details/gt2rytannwi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangdashe.top/Article/details/gt2ozlvtxci.html

user_id INT NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gt2gaslxfoa.html

amount DECIMAL(10, 2),
来源：http://dali.shangyingyoupin.top/Article/details/gt2wvacmeac.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xziqi.cn/Article/details/gt2edvscyao.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2egautapl.html

[Q03] 增加列
来源：http://dali.hfpthk.cn/Article/details/gt2bsfndcwt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xziqi.cn/Article/details/gt2kqhwydnj.html

[Q04] 修改列类型
来源：http://dali.xinyue.icu/Article/details/gt2vybwzljx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ehwqpu.com/Article/details/gt2zfettmll.html

[Q05] 重命名列
来源：http://dali.cqqwz.cn/Article/details/gt2fnzkzctz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dashuyun.cn/Article/details/gt2crclrfon.html

[Q06] 删除列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yqtvjlij.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qdnwwewd.html

[Q07] 删除表
来源：http://dali.iojbl.cn/Article/details/gt2joxkaovy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.mhx1999.top/Article/details/gt2xdahkkmj.html

[Q08] 创建普通索引
来源：http://dali.fengsongda.top/Article/details/gt2okehrmpo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gt2pycwwsnn.html

[Q09] 创建唯一索引
来源：http://dali.yuxming.cn/Article/details/gt2bvppfgmy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gt2xgnvqdqg.html

[Q10] 插入单行
来源：http://dali.redwolf501.top/Article/details/gt2tlgzqkkf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rqfbuboe.html

[Q11] 一次插入多行
来源：http://dali.tian-w.cn/Article/details/gt2vbngyzrg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.havefunace.top/Article/details/gt2jqmkakil.html

[Q12] 插入后取自增 ID
来源：http://dali.yvedp.cn/Article/details/gt2nznpiezx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhoulong.xyz/Article/details/gt2aasmcuxw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.wangdashe.top/Article/details/gt2ytzsuxxr.html

[Q13] 忽略重复插入
来源：http://dali.snrcjt.cn/Article/details/gt2kdmomknw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhengqikj.top/Article/details/gt2mlgahlsa.html

[Q14] 存在则更新（upsert）
来源：http://dali.gzhubu.top/Article/details/gt2npvdyeyw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cdnleiting.top/Article/details/gt2yijinxna.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fyjnxtlo.html

[Q15] 查询全部
来源：http://dali.haohaochexian.top/Article/details/gt2cdzkilmp.html

SELECT * FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2skjgwnqo.html

[Q16] 查询指定列
来源：http://dali.pengpengdd.cyou/Article/details/gt2ayeollmk.html

SELECT id, name FROM users;
来源：http://dali.yj202588.top/Article/details/gt2pwnyxxpg.html

[Q17] 条件查询
来源：http://dali.shuidangran.top/Article/details/gt2leybqhsf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yongpay.top/Article/details/gt2rzupbcgg.html

[Q18] 模糊匹配
来源：http://dali.havefunace.top/Article/details/gt2bgsrhflz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zycfv.cn/Article/details/gt2tygzqpzh.html

[Q19] 范围查询
来源：http://dali.gotoacloud.top/Article/details/gt2tijilqpk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ivvv.top/Article/details/gt2knlbxtiq.html

[Q20] IN 列表
来源：http://dali.yonumen.top/Article/details/gt2pqpdandm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj202588.top/Article/details/gt2hcashqaw.html

[Q21] 空值判断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tnrmceyw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.haohaochexian.top/Article/details/gt2bxcjrlwm.html

[Q22] 排序
来源：http://dali.9152youxi.cn/Article/details/gt2rmabcjip.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigfzy.top/Article/details/gt2xphihcbq.html

[Q23] 分页
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sxsulrxo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.c1oappe.top/Article/details/gt2krglaidx.html

[Q24] 去重
来源：http://dali.ybcxt.top/Article/details/gt2xlldlowd.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ptdqlisy.html

[Q25] 只取前 N 条
来源：http://dali.yueranfly.top/Article/details/gt2larrhdev.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rrszvzxp.html

[Q26] 计数
来源：http://dali.yj20258888.top/Article/details/gt2todbjmdw.html

SELECT COUNT(*) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2nsyoklks.html

[Q27] 条件计数
来源：http://dali.jlsjyb.cn/Article/details/gt2eksnganz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ivvv.top/Article/details/gt2pxscthvp.html

[Q28] 求和与平均
来源：http://dali.yj20258.top/Article/details/gt2qjpufjhk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wnkkwcul.html

[Q29] 最大最小值
来源：http://dali.wangdashe.top/Article/details/gt2xfvedrkh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2qldjqhnv.html

[Q30] 分组统计
来源：http://dali.aizwys.cn/Article/details/gt2ethiunbo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gt2xvxbhlxp.html

[Q31] 分组后过滤
来源：http://dali.yvedp.cn/Article/details/gt2weyjzuyr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.birdmap.top/Article/details/gt2euxexbif.html

[Q32] 分组拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2prywmkby.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gt2dtzdgpit.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cucudq.cn/Article/details/gt2szbjjoja.html

[Q33] 多列分组
来源：http://dali.gogol.net.cn/Article/details/gt2patgmzfn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yangfankeji.com/Article/details/gt2xcaffctq.html

[Q34] 每组取第一条
来源：http://dali.xinyue.icu/Article/details/gt2rxahsmnu.html

SELECT * FROM (
来源：http://dali.xinyue.icu/Article/details/gt2hsuiiqmu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pycfn.com/Article/details/gt2mdndscqf.html

) t WHERE rn = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2yxsvpdzp.html

[Q35] 内连接
来源：http://dali.gaohongyu789.top/Article/details/gt2wcmngpfu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.316326.xyz/Article/details/gt2qqwlthov.html

[Q36] 左连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wdnlnbvl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2xjnzeuxn.html

[Q37] 右连接
来源：http://dali.hnxiangtu.top/Article/details/gt2pemreuze.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenzaomai.com/Article/details/gt2lglznmbx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj20258888.top/Article/details/gt2ctutkeff.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ybcxt.top/Article/details/gt2bnghnkwv.html

[Q39] 自连接（查上下级）
来源：http://dali.cdnleiting.top/Article/details/gt2vvmctymu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xinyue.icu/Article/details/gt2xzbhpqtf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cdnleiting.top/Article/details/gt2zrycusqr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ppjwa.cn/Article/details/gt2pobhlazs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuetiantiany.cn/Article/details/gt2eqgioluh.html

[Q41] 多表连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2knxswkib.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yiooewak.html

JOIN users u ON u.id = o.user_id
来源：http://dali.vqdsnc.cn/Article/details/gt2ffxyoaru.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.andypj.xyz/Article/details/gt2xczaagwd.html

[Q42] 连接条件附加过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2wkcrstbp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xylfe.cn/Article/details/gt2ftnpimhx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.vqdsnc.cn/Article/details/gt2qwjjaefd.html

[Q43] 标量子查询
来源：http://dali.xziqi.cn/Article/details/gt2mxwgieay.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenzaomai.com/Article/details/gt2ziorvxox.html

[Q44] IN 子查询
来源：http://dali.zhoulong.xyz/Article/details/gt2rarzpekc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.vqdsnc.cn/Article/details/gt2xtxzjocd.html

[Q45] EXISTS 判断存在
来源：http://dali.pycfn.com/Article/details/gt2odaratlb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hfpthk.cn/Article/details/gt2riespbwc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xziqi.cn/Article/details/gt2edrzmqws.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cbytdvzy.html

[Q47] 与平均值比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2jncecjht.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258.top/Article/details/gt2smehlitc.html

[Q48] CTE 公用表表达式
来源：http://dali.mhx1999.top/Article/details/gt2dekzcrvw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hfpthk.cn/Article/details/gt2hkcrwfeo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ydsvdnzg.html

[Q49] 更新单行
来源：http://dali.daxiang520.top/Article/details/gt2xslhxiud.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gt2okpmfygn.html

[Q50] 批量更新
来源：http://dali.zhongyouzk.top/Article/details/gt2joyghjrs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daxiang520.top/Article/details/gt2ewzshoqk.html

[Q51] 用子查询更新
来源：http://dali.dianchejie.cn/Article/details/gt2mbnhaiac.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.redwolf501.top/Article/details/gt2kzhdbyeg.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cgxvegnv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gt2qejyjvim.html

[Q53] 按条件删除
来源：http://dali.zhongyouzk.top/Article/details/gt2uerzgtrn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cqqwz.cn/Article/details/gt2cgqhxdqb.html

[Q54] 清空表
来源：http://dali.zycfv.cn/Article/details/gt2wczizxtr.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cqbrcyrz.html

[Q55] 排名（并列占位）
来源：http://dali.c1oappe.top/Article/details/gt2vbglobex.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.iojbl.cn/Article/details/gt2jvvulesg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fengsongda.top/Article/details/gt2xxfomhnp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gt2gjqpqinn.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2niagoqbd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xpwmqxkp.html

[Q58] 累计求和
来源：http://dali.cheryme.top/Article/details/gt2svxtllck.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2crppmxvz.html

[Q59] 分组内累计
来源：http://dali.zhongyouzk.top/Article/details/gt2sauawmeu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2menrfiak.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkibeqtj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zeoyncok.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2xdsbtqts.html


<!-- 参考信息 -->