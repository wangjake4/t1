代发 wailian999

Java: // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2rfbfgoxo.html

Go:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gt2itvrrgwk.html

Ruby: arr.permutation.to_a
来源：http://dali.wangshuangyany.cn/Article/details/gt2ygszfnxp.html

C#:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2jgymgwne.html

[N09] 栈与队列
来源：http://dali.xziqi.cn/Article/details/gt2csuxztrc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fzhhl.top/Article/details/gt2nslfupkf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.316326.xyz/Article/details/gt2jqvrrksd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gt2balocqyk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jianghu66.top/Article/details/gt2rftiwezt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hammf.cn/Article/details/gt2wuheinhm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.mhx1999.top/Article/details/gt2aamhoxuc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bthdooow.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.vqdsnc.cn/Article/details/gt2kewzmuek.html

[N10] 链表节点定义
来源：http://dali.iojbl.cn/Article/details/gt2dkyjvgkr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hywenlv.cn/Article/details/gt2sgmttupt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.daria6918.cn/Article/details/gt2hnimpezo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.redwolf501.top/Article/details/gt2gmknchri.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yongpay.top/Article/details/gt2nsaaxcqg.html

Java: class Node { int v; Node next; }
来源：http://dali.ybcxt.top/Article/details/gt2cipmkxnw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.guowangkeji.top/Article/details/gt2nrwzycrs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.snrcjt.cn/Article/details/gt2cnpwpeni.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cashguo.top/Article/details/gt2bkoxdmjq.html

[N11] 二叉树中序遍历
来源：http://dali.cdnleiting.top/Article/details/gt2wifmepwu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jlsjyb.cn/Article/details/gt2fjjyzdva.html

PHP:  // 手写递归函数
来源：http://dali.zhengqikj.top/Article/details/gt2dpoqfpgr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ehwqpu.com/Article/details/gt2zaqknsbe.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gt2lnvizxqj.html

Java: // 手写递归
来源：http://dali.yueranfly.top/Article/details/gt2ceemmjvr.html

Go:   // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aiipmwdg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cqqwz.cn/Article/details/gt2bgyfrryi.html

C#:   // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oqlocpsu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aizwys.cn/Article/details/gt2qtkmxcnk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhongyouzk.top/Article/details/gt2bhiaohcs.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ybcxt.top/Article/details/gt2ozfibhys.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gt2ngzcbrfi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.mhx1999.top/Article/details/gt2heasgwil.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gt2payzizjb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.iojbl.cn/Article/details/gt2adxtodbe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dianchejie.cn/Article/details/gt2yrdtjmkg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgufenzy.top/Article/details/gt2wummvoud.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2acppvrzx.html

O. 并发与异步
来源：http://dali.pengpengdd.cyou/Article/details/gt2kjponswv.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2lmzipnlu.html

[O01] 启动一个线程
来源：http://dali.sweek.top/Article/details/gt2jirfqyda.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.havefunace.top/Article/details/gt2oigcljni.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.iojbl.cn/Article/details/gt2oizeakbq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gotoacloud.top/Article/details/gt2dyhmqbmv.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gt2istkayuc.html

Java: new Thread(() -> f()).start()
来源：http://dali.cucudq.cn/Article/details/gt2yekmdaox.html

Go:   go f()
来源：http://dali.sxryk.cn/Article/details/gt2vuxvzawj.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2klmkfowo.html

C#:   Task.Run(() => F());
来源：http://dali.sufxvd.cn/Article/details/gt2wxyjqinp.html

[O02] 使用线程池
来源：http://dali.yj20258888.top/Article/details/gt2vvxlogyq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxinkj.top/Article/details/gt2nlroqqpv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.svipenyu.cn/Article/details/gt2ppjbvjgv.html

JS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gt2ieyrdpqa.html

TS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gt2nxedxxuq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jumvqxlp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinqigfzy.top/Article/details/gt2vefexcpi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cqqwz.cn/Article/details/gt2fybdoran.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sxryk.cn/Article/details/gt2uurrdbls.html

[O03] 加锁保护共享数据
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ikdcmdcd.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ggxjprim.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhongyouzk.top/Article/details/gt2cfkoxvfy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj20258.top/Article/details/gt2qonhwksn.html

TS:   // 同 JS
来源：http://dali.aibaodan.cn/Article/details/gt2sfrlbzgc.html

Java: synchronized (this) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gt2aecrhcam.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ksdpqkfh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinqigfzy.top/Article/details/gt2pkodhvbg.html

C#:   lock (gate) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gt2ashlcame.html

[O04] 定义异步函数并等待
来源：http://dali.hywenlv.cn/Article/details/gt2qezumpru.html

Py:   async def f():⏎    await g()
来源：http://dali.yonumen.top/Article/details/gt2gxisyzii.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xinyue.icu/Article/details/gt2ezwswptm.html

JS:   async function f() { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2prtnragk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zycfv.cn/Article/details/gt2lsovzliv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ytkmqgju.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tanke756.top/Article/details/gt2wuaaueok.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nanxinkj.top/Article/details/gt2iogtkxvd.html

C#:   async Task F() { await G(); }
来源：http://dali.zhengqikj.top/Article/details/gt2fxhwpbsk.html

[O05] 并发执行并等待全部完成
来源：http://dali.aizwys.cn/Article/details/gt2xuvhfazv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ehwqpu.com/Article/details/gt2pzuptkqz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rpbbkucg.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gt2nhggopzo.html

TS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gt2bcuspofx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shangyingyoupin.top/Article/details/gt2zoxuimjz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cdnleiting.top/Article/details/gt2zhebwvwq.html

Ruby: threads.map(&:join)
来源：http://dali.jqgufenzy.top/Article/details/gt2snlbpqzu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rvmownln.html

[O06] 使用进程池
来源：http://dali.jlsjyb.cn/Article/details/gt2vgcghikh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuxming.cn/Article/details/gt2acpnfpez.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.dashuyun.cn/Article/details/gt2thtdctnb.html

JS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gt2kbsosohl.html

TS:   // child_process / cluster 模块
来源：http://dali.shzxlz.cn/Article/details/gt2ermtbhov.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gotoacloud.top/Article/details/gt2cqujsflo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hongshengwenyu.top/Article/details/gt2ufyizlsx.html

Ruby: // fork 块
来源：http://dali.aizwys.cn/Article/details/gt2gjilnwyg.html

C#:   Parallel.For
来源：http://dali.yj20258888.top/Article/details/gt2gmxmdkry.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2vrermqfh.html

P. 常用工具函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2kwwnukbw.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2vehvaphx.html

[P01] 生成 UUID
来源：http://dali.pycfn.com/Article/details/gt2gkiakhns.html

Py:   str(uuid.uuid4())
来源：http://dali.jyoumei.cn/Article/details/gt2lowymriw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj202588.top/Article/details/gt2onufrkwr.html

JS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gt2dwwqpkze.html

TS:   crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gt2bytwhvkg.html

Java: UUID.randomUUID().toString()
来源：http://dali.sweek.top/Article/details/gt2ssayovlq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenlongwang.top/Article/details/gt2rctatwaj.html

Ruby: SecureRandom.uuid
来源：http://dali.zhengqikj.top/Article/details/gt2rvusvwzi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jyoumei.cn/Article/details/gt2bxhrmidn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenlongwang.top/Article/details/gt2pmiakfff.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ydzc1.top/Article/details/gt2tayrxtza.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.9152youxi.cn/Article/details/gt2sjkjrawb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cqqwz.cn/Article/details/gt2ogdhavjg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.vqdsnc.cn/Article/details/gt2azdedgos.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gt2doarosvl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.andypj.xyz/Article/details/gt2oynodqty.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gzhubu.top/Article/details/gt2wlstlcqf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yanxiufei.cn/Article/details/gt2iswbubkn.html

[P03] 生成短随机字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2gqflutnu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.redwolf501.top/Article/details/gt2znjoxinr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sufxvd.cn/Article/details/gt2xiorpygl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gt2eekrndeo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cheryme.top/Article/details/gt2mxpcjxtj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daria6918.cn/Article/details/gt2euptvmdf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhixingplan.top/Article/details/gt2cgtqcxte.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bueuoonn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ybcxt.top/Article/details/gt2ztqayndy.html

[P04] 求长度
来源：http://dali.ppjwa.cn/Article/details/gt2tzysoxsb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zycfv.cn/Article/details/gt2jtdvxfmr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nwmvtsds.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gt2viyktavf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pycfn.com/Article/details/gt2hbyutlwp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ehwqpu.com/Article/details/gt2gowsqnqu.html

Go:   len(arr);  len(m)
来源：http://dali.gaohongyu789.top/Article/details/gt2rotzxcas.html

Ruby: x.length;  x.size
来源：http://dali.pengpengdd.cyou/Article/details/gt2jyjjdjxw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hywenlv.cn/Article/details/gt2sjxbbtbh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ppjwa.cn/Article/details/gt2mhrzfpgs.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenjidiqi.icu/Article/details/gt2ateuenve.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.0kj1m.cn/Article/details/gt2zctprtuw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258.top/Article/details/gt2dgkpphuz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jianghu66.top/Article/details/gt2btxynmhi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj202588.top/Article/details/gt2pwwtnvrb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sweek.top/Article/details/gt2xwwufeum.html

Ruby: a == b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xdnqirae.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258888.top/Article/details/gt2bvrikzck.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.feifeiyinyue.top/Article/details/gt2qrafgrqt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jyoumei.cn/Article/details/gt2ggcjzbgi.html

PHP:  if (empty($x)) {}
来源：http://dali.chenlongwang.top/Article/details/gt2grlbjxuq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgufenzy.top/Article/details/gt2wehaepso.html

TS:   if (x == null) {}
来源：http://dali.zdqjudy.top/Article/details/gt2dygouimv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2yrzwzprn.html

Go:   if x == nil {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2irndfknf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouysmfuw.html

C#:   if (x is null) {}
来源：http://dali.wangdashe.top/Article/details/gt2htdtgsma.html

[P07] 防抖与节流
来源：http://dali.andypj.xyz/Article/details/gt2npfrneoz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tbgtdlbf.html

PHP:  // 手写时间戳比较
来源：http://dali.guannengcc.top/Article/details/gt2itdvahlb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqtjalwr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gt2tclqvdhg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2sohabygp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ppjwa.cn/Article/details/gt2ituarhbg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hywenlv.cn/Article/details/gt2rkzobowq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xinyue.icu/Article/details/gt2dgktpdcm.html

[P08] 处理浮点精度问题
来源：http://dali.ivvv.top/Article/details/gt2evnqajqh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.feifeiyinyue.top/Article/details/gt2isfdjrhb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jyoumei.cn/Article/details/gt2zhiuxedf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pgpmzoag.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hysaishi.cn/Article/details/gt2nwsjtizi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangshuangyany.cn/Article/details/gt2cbnngodz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cdnleiting.top/Article/details/gt2uamdqdhd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ppjwa.cn/Article/details/gt2yltlffih.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.fzhhl.top/Article/details/gt2iqzomcxk.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2kegacncj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sufxvd.cn/Article/details/gt2fnrodunq.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2wbmbhezg.html

[Q01] 创建表
来源：http://dali.daria6918.cn/Article/details/gt2ltorncpa.html

CREATE TABLE users (
来源：http://dali.kuanghao11.cn/Article/details/gt2ixdoqkdc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gt2vhihuxdi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yueranfly.top/Article/details/gt2whvcapui.html

email VARCHAR(100) UNIQUE,
来源：http://dali.feifeiyinyue.top/Article/details/gt2tyvtshhn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuetiantiany.cn/Article/details/gt2xhszdyjl.html

);
来源：http://dali.xinyue.icu/Article/details/gt2avlpzrtw.html

[Q02] 创建带外键的表
来源：http://dali.yanxiufei.cn/Article/details/gt2sqbaeabi.html

CREATE TABLE orders (
来源：http://dali.meibo888.top/Article/details/gt2aqxydcdo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gt2vfgysaag.html

user_id INT NOT NULL,
来源：http://dali.hammf.cn/Article/details/gt2fouogbbc.html

amount DECIMAL(10, 2),
来源：http://dali.dianchejie.cn/Article/details/gt2battwlvy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.vqdsnc.cn/Article/details/gt2mflezjsf.html

);
来源：http://dali.yuanzhike.top/Article/details/gt2pdskrhul.html

[Q03] 增加列
来源：http://dali.yueranfly.top/Article/details/gt2fprlblda.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cheryme.top/Article/details/gt2lyxphmcc.html

[Q04] 修改列类型
来源：http://dali.yj202588.top/Article/details/gt2wmrgafaa.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gt2nxrhgftl.html

[Q05] 重命名列
来源：http://dali.dashuyun.cn/Article/details/gt2lxphqgrr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.havefunace.top/Article/details/gt2riylmglw.html

[Q06] 删除列
来源：http://dali.kuanghao11.cn/Article/details/gt2etroqytj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuxming.cn/Article/details/gt2fuofiqgt.html

[Q07] 删除表
来源：http://dali.birdmap.top/Article/details/gt2qxwpqdig.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj20258.top/Article/details/gt2czqdlxsr.html

[Q08] 创建普通索引
来源：http://dali.zhiwuduotai.top/Article/details/gt2dkhsxiao.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gotoacloud.top/Article/details/gt2kslyteyo.html

[Q09] 创建唯一索引
来源：http://dali.ybcxt.top/Article/details/gt2azakijdh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.haohaochexian.top/Article/details/gt2ofpmbozf.html

[Q10] 插入单行
来源：http://dali.guowangkeji.top/Article/details/gt2gjdlfiii.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cashguo.top/Article/details/gt2ddigiwdp.html

[Q11] 一次插入多行
来源：http://dali.zhiwuduotai.top/Article/details/gt2ydvzdorq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hysaishi.cn/Article/details/gt2tlcuggkk.html

[Q12] 插入后取自增 ID
来源：http://dali.yj202588.top/Article/details/gt2lnlnxxvp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ydzc1.top/Article/details/gt2llfrsmmt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sufxvd.cn/Article/details/gt2fozhputr.html

[Q13] 忽略重复插入
来源：http://dali.jinqigfzy.top/Article/details/gt2fejgjrjn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hysaishi.cn/Article/details/gt2vuxvwgcq.html

[Q14] 存在则更新（upsert）
来源：http://dali.xziqi.cn/Article/details/gt2ncxtxwdl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gotoacloud.top/Article/details/gt2lmiqdshf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.meibo888.top/Article/details/gt2hsnoqalv.html

[Q15] 查询全部
来源：http://dali.chenzaomai.com/Article/details/gt2oxmckaki.html

SELECT * FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2fhblqedp.html

[Q16] 查询指定列
来源：http://dali.jinqigfzy.top/Article/details/gt2agisiksw.html

SELECT id, name FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2exdsvhrd.html

[Q17] 条件查询
来源：http://dali.ivvv.top/Article/details/gt2usgmanap.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2ebkpnusq.html

[Q18] 模糊匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2ohubcgge.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hammf.cn/Article/details/gt2hnohuigh.html

[Q19] 范围查询
来源：http://dali.tian-w.cn/Article/details/gt2egpxfqjf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yueranfly.top/Article/details/gt2quhkdjbn.html

[Q20] IN 列表
来源：http://dali.dianchejie.cn/Article/details/gt2yuxjgwpx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cqqwz.cn/Article/details/gt2irqsaidg.html

[Q21] 空值判断
来源：http://dali.hnxiangtu.top/Article/details/gt2rdmitixr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hysaishi.cn/Article/details/gt2pblsyzcz.html

[Q22] 排序
来源：http://dali.chenjidiqi.icu/Article/details/gt2bdtfvyse.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangdashe.top/Article/details/gt2ekeiiksx.html

[Q23] 分页
来源：http://dali.iojbl.cn/Article/details/gt2uxhtkovi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pycfn.com/Article/details/gt2txxtsean.html

[Q24] 去重
来源：http://dali.nanxinkj.top/Article/details/gt2qhzgvkov.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2rlgnpzdz.html

[Q25] 只取前 N 条
来源：http://dali.zhongyouzk.top/Article/details/gt2oysbvvdj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xziqi.cn/Article/details/gt2osxxkzcx.html

[Q26] 计数
来源：http://dali.chenjidiqi.icu/Article/details/gt2vtlcgzwy.html

SELECT COUNT(*) FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2owgywclk.html

[Q27] 条件计数
来源：http://dali.jlsjyb.cn/Article/details/gt2ownvrjrf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2ksaihudu.html

[Q28] 求和与平均
来源：http://dali.shzxlz.cn/Article/details/gt2rcdpaxix.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gt2pkpwdpfp.html

[Q29] 最大最小值
来源：http://dali.zhengqikj.top/Article/details/gt2oqhtkxhv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2sufmhofs.html

[Q30] 分组统计
来源：http://dali.hywenlv.cn/Article/details/gt2gfwameyz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gt2swkeotxb.html

[Q31] 分组后过滤
来源：http://dali.yj20258888.top/Article/details/gt2kfktyqrd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj202588.top/Article/details/gt2xfnfaosw.html

[Q32] 分组拼接字符串
来源：http://dali.316326.xyz/Article/details/gt2cadfeadq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gt2rsswaqju.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhengqikj.top/Article/details/gt2lxlmciyj.html

[Q33] 多列分组
来源：http://dali.shuidangran.top/Article/details/gt2yqoccgtu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.c1oappe.top/Article/details/gt2fdkwwsdc.html

[Q34] 每组取第一条
来源：http://dali.zdqjudy.top/Article/details/gt2tecfpwkh.html

SELECT * FROM (
来源：http://dali.yj20258888.top/Article/details/gt2gipwpafv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2takeayru.html

) t WHERE rn = 1;
来源：http://dali.fengsongda.top/Article/details/gt2aaygbyds.html

[Q35] 内连接
来源：http://dali.yj20258888.top/Article/details/gt2gmblzjxh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.kuanghao11.cn/Article/details/gt2kihgmjiu.html

[Q36] 左连接
来源：http://dali.daxiang520.top/Article/details/gt2oiovnlky.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2wvdcduiu.html

[Q37] 右连接
来源：http://dali.iojbl.cn/Article/details/gt2vlrhufpa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jianghu66.top/Article/details/gt2ohmxtgkz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sufxvd.cn/Article/details/gt2fmdblios.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jianghu66.top/Article/details/gt2hapfrmcv.html

[Q39] 自连接（查上下级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tuuwvztq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxuanxn.top/Article/details/gt2ijrtqrwz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.andypj.xyz/Article/details/gt2bgfkgcnb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xinyue.icu/Article/details/gt2kghryxsq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangshuangyany.cn/Article/details/gt2wswwuvel.html

[Q41] 多表连接
来源：http://dali.yj20258888.top/Article/details/gt2pdwwbhar.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hfpthk.cn/Article/details/gt2wcawchzc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cashguo.top/Article/details/gt2sxxumusf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gzhubu.top/Article/details/gt2ivayhqqs.html

[Q42] 连接条件附加过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2snjtyxez.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hongshengwenyu.top/Article/details/gt2bjytsemu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.pycfn.com/Article/details/gt2ndqttotq.html

[Q43] 标量子查询
来源：http://dali.yangfankeji.com/Article/details/gt2tllxuuob.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hnqzz.top/Article/details/gt2jepmuxwb.html

[Q44] IN 子查询
来源：http://dali.sufxvd.cn/Article/details/gt2ufgkbmuh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hywenlv.cn/Article/details/gt2jiolavri.html

[Q45] EXISTS 判断存在
来源：http://dali.aibaodan.cn/Article/details/gt2wewppmgt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.haohaochexian.top/Article/details/gt2spfhlror.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ppjwa.cn/Article/details/gt2yzzfgwzp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gt2chznmegj.html

[Q47] 与平均值比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2jzzlourr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sxryk.cn/Article/details/gt2deqdbmso.html

[Q48] CTE 公用表表达式
来源：http://dali.shuidangran.top/Article/details/gt2gizcrnbh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cashguo.top/Article/details/gt2gmvmcaqe.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cucudq.cn/Article/details/gt2gupphhbj.html

[Q49] 更新单行
来源：http://dali.cashguo.top/Article/details/gt2thycupbr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gt2cxtaourg.html

[Q50] 批量更新
来源：http://dali.guowangkeji.top/Article/details/gt2jukduvqa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.andypj.xyz/Article/details/gt2fykqqpwg.html

[Q51] 用子查询更新
来源：http://dali.nanxinkj.top/Article/details/gt2cdcrhqsl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.c1oappe.top/Article/details/gt2kamyrfuq.html

[Q52] 删除指定行
来源：http://dali.xziqi.cn/Article/details/gt2noofqpcw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gt2fowebbml.html

[Q53] 按条件删除
来源：http://dali.jlsjyb.cn/Article/details/gt2msrlzigi.html


<!-- 参考信息 -->