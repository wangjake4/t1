代发 wailian999

Py:   itertools.permutations(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtkhwsylac.html

PHP:  // 手写递归交换
来源：http://dali.zhongyouzk.top/Article/details/gtskjftoui.html

JS:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagdgwtev.html

TS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtfxioafuy.html

Java: // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtybstwdyz.html

Go:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtufpxgdbl.html

Ruby: arr.permutation.to_a
来源：http://dali.mhx1999.top/Article/details/gtefjybnws.html

C#:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtriayyvmn.html

[N09] 栈与队列
来源：http://dali.hammf.cn/Article/details/gtyyyxralz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.svipenyu.cn/Article/details/gtbwdwvycn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cheryme.top/Article/details/gtavvecmei.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtxdhkbaca.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xinyue.icu/Article/details/gtknfweosn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuetiantiany.cn/Article/details/gtdwdkdrkx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.kuanghao11.cn/Article/details/gtggreudtb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtulcvwyqv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hysaishi.cn/Article/details/gtjvoziiqp.html

[N10] 链表节点定义
来源：http://dali.aizwys.cn/Article/details/gtlgmiahci.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.vqdsnc.cn/Article/details/gtlwyfxmah.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yvedp.cn/Article/details/gtyoufpioy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhoulong.xyz/Article/details/gtgmomfkpy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hnqzz.top/Article/details/gtvbdixlir.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigfzy.top/Article/details/gtlrwzqsbd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.smart0.xyz/Article/details/gtifjhewnv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrscvncwa.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aibaodan.cn/Article/details/gtvotfzinv.html

[N11] 二叉树中序遍历
来源：http://dali.dianchejie.cn/Article/details/gteymgkpmr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sxryk.cn/Article/details/gtzmljuzmc.html

PHP:  // 手写递归函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiapscajm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnesehpbl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.bjfxy.top/Article/details/gtabbtvpmw.html

Java: // 手写递归
来源：http://dali.xylfe.cn/Article/details/gtqajejgyb.html

Go:   // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtvivvzbky.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjrejftg.html

C#:   // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gteguyjpqi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.guannengcc.top/Article/details/gtbtzeykir.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xylfe.cn/Article/details/gtjggqizeb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhoulong.xyz/Article/details/gtcinmhtyh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gtxgszmwpn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gtxlczbfwt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbcfmvbz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nwbrower.top/Article/details/gtpyywxzzv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.haohaochexian.top/Article/details/gtkzughvno.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gtgzxzmjix.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtqljvknds.html

O. 并发与异步
来源：http://dali.ppjwa.cn/Article/details/gtghtmzise.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtikwivgff.html

[O01] 启动一个线程
来源：http://dali.cqqwz.cn/Article/details/gtjgrztaua.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shuidangran.top/Article/details/gtemnclooo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.bjfxy.top/Article/details/gtmfuhcyba.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinyuanbaomall.cn/Article/details/gtigjqoals.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gtyxbirqny.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuxming.cn/Article/details/gtvtjcyntc.html

Go:   go f()
来源：http://dali.hammf.cn/Article/details/gtgowxvoiy.html

Ruby: Thread.new { f }
来源：http://dali.quarkkingdee.top/Article/details/gtptehktwn.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258888.top/Article/details/gtzzkfvlej.html

[O02] 使用线程池
来源：http://dali.hfpthk.cn/Article/details/gtukkskliq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cucudq.cn/Article/details/gteprrnekp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daxiang520.top/Article/details/gtfaxhjbsg.html

JS:   // worker_threads 线程池
来源：http://dali.gotoacloud.top/Article/details/gtiuuflvtq.html

TS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gtkqyegsqb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guowangkeji.top/Article/details/gtwkxzvjda.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinqigfzy.top/Article/details/gtxpnsnimq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbuvtzfou.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.0kj1m.cn/Article/details/gtbapmsuek.html

[O03] 加锁保护共享数据
来源：http://dali.9152youxi.cn/Article/details/gtucjoiemj.html

Py:   with lock: shared += 1
来源：http://dali.zhongyouzk.top/Article/details/gtxwbnkhje.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aibaodan.cn/Article/details/gtibcomnpo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sxryk.cn/Article/details/gtzgpjpwja.html

TS:   // 同 JS
来源：http://dali.sxryk.cn/Article/details/gtgldxedez.html

Java: synchronized (this) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gtobcbhopa.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hywenlv.cn/Article/details/gtbwuljdkx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cdnleiting.top/Article/details/gtwthrbkxx.html

C#:   lock (gate) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gtjzrfxmya.html

[O04] 定义异步函数并等待
来源：http://dali.redwolf501.top/Article/details/gtkqwoilhf.html

Py:   async def f():⏎    await g()
来源：http://dali.havefunace.top/Article/details/gtlwlpfzwy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhixingplan.top/Article/details/gtybfdhdgc.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258888.top/Article/details/gtnyrjzudz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258888.top/Article/details/gtlynjulmb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.aibaodan.cn/Article/details/gtpfxryxvd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cheryme.top/Article/details/gttdfwmdeq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapbwpeqg.html

C#:   async Task F() { await G(); }
来源：http://dali.nwbrower.top/Article/details/gtqttznbft.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinghuilouyu.cn/Article/details/gtjaqrlztq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gotoacloud.top/Article/details/gtfqancbbq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ehwqpu.com/Article/details/gtsrrbmgys.html

JS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gtlftoxxxe.html

TS:   await Promise.all(tasks)
来源：http://dali.jiagoushi.top/Article/details/gtnaprsuww.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pengpengdd.cyou/Article/details/gtrkxljibs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.316326.xyz/Article/details/gtkrhbifuv.html

Ruby: threads.map(&:join)
来源：http://dali.316326.xyz/Article/details/gtigkoibub.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jyoumei.cn/Article/details/gtllconffr.html

[O06] 使用进程池
来源：http://dali.guowangkeji.top/Article/details/gtrctzkeaj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gaohongyu789.top/Article/details/gtpseghnvu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hysaishi.cn/Article/details/gtwcarkwvi.html

JS:   // child_process / cluster 模块
来源：http://dali.shzxlz.cn/Article/details/gtqbmlltuz.html

TS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gtmrhwxvzw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.iojbl.cn/Article/details/gtrzlyizdv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sxryk.cn/Article/details/gtsgckubeq.html

Ruby: // fork 块
来源：http://dali.xziqi.cn/Article/details/gtmwvromyd.html

C#:   Parallel.For
来源：http://dali.snrcjt.cn/Article/details/gtlpoqjaqb.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtqcoofhjp.html

P. 常用工具函数
来源：http://dali.cqqwz.cn/Article/details/gtcnawjohp.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtpsqslzyp.html

[P01] 生成 UUID
来源：http://dali.sweek.top/Article/details/gtqlhswhxm.html

Py:   str(uuid.uuid4())
来源：http://dali.shangyingyoupin.top/Article/details/gtalpfsqqw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.iojbl.cn/Article/details/gtxbrddzvw.html

JS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gthuxjuurf.html

TS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gtbvialvkp.html

Java: UUID.randomUUID().toString()
来源：http://dali.ybcxt.top/Article/details/gtyowyxmkc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.pycfn.com/Article/details/gtnkapsqbz.html

Ruby: SecureRandom.uuid
来源：http://dali.yonumen.top/Article/details/gtigzpecoa.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.fengsongda.top/Article/details/gtjfqxmnke.html

[P02] MD5 / SHA256 摘要
来源：http://dali.mhx1999.top/Article/details/gtnfxfgrlj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ivvv.top/Article/details/gtlixkgrhd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dashuyun.cn/Article/details/gtgamnrfcb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhengqikj.top/Article/details/gtpoyzbepe.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.havefunace.top/Article/details/gtjljjijox.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkondzpmo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ehwqpu.com/Article/details/gtjttqnvbp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sysykeji.top/Article/details/gtiwdrpdrd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigufen.top/Article/details/gtqqclqxfu.html

[P03] 生成短随机字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtseuubpxx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zycfv.cn/Article/details/gtontfhxuf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jiagoushi.top/Article/details/gtovgopivp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aizwys.cn/Article/details/gtagfkidxs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gtxmdlncjq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.snrcjt.cn/Article/details/gtluzshycr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hysaishi.cn/Article/details/gtidfvmdoz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gotoacloud.top/Article/details/gtdzictytv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ehwqpu.com/Article/details/gtcrffkojk.html

[P04] 求长度
来源：http://dali.hysaishi.cn/Article/details/gtlhtwdolg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmcunbvdn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtwfwbsihw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cheryme.top/Article/details/gtrswxdary.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yueranfly.top/Article/details/gtyltwjphh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangdashe.top/Article/details/gtvzrdjofu.html

Go:   len(arr);  len(m)
来源：http://dali.jinqigfzy.top/Article/details/gtrqjsbieb.html

Ruby: x.length;  x.size
来源：http://dali.zhoulong.xyz/Article/details/gtpzeyztsp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yonumen.top/Article/details/gtjpofvbsk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxinkj.top/Article/details/gtjrwcyfzr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jyoumei.cn/Article/details/gtkivjuuib.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.havefunace.top/Article/details/gtaxoynrho.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shangyingyoupin.top/Article/details/gtwsxgyxdx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjylrgvzd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.vqdsnc.cn/Article/details/gtfmugityo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cheryme.top/Article/details/gtyacuehlb.html

Ruby: a == b
来源：http://dali.wangdashe.top/Article/details/gtmarbfscv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shzxlz.cn/Article/details/gtspftezfs.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jiagoushi.top/Article/details/gtayrnykjq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cucudq.cn/Article/details/gtrdukbrdx.html

PHP:  if (empty($x)) {}
来源：http://dali.cdnleiting.top/Article/details/gtchzzivcg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.pycfn.com/Article/details/gthbrjfxtr.html

TS:   if (x == null) {}
来源：http://dali.c1oappe.top/Article/details/gtjhvvwzad.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtwuxdrwws.html

Go:   if x == nil {}
来源：http://dali.yueranfly.top/Article/details/gtpwiwhfcw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gotoacloud.top/Article/details/gtspohfooi.html

C#:   if (x is null) {}
来源：http://dali.birdmap.top/Article/details/gtwenzxouq.html

[P07] 防抖与节流
来源：http://dali.snrcjt.cn/Article/details/gtpkntlhhd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.quarkkingdee.top/Article/details/gtkecoulth.html

PHP:  // 手写时间戳比较
来源：http://dali.hysaishi.cn/Article/details/gtzzmpoxit.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gtxbvxexcw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gtsuukgewa.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.snrcjt.cn/Article/details/gtfytwzpyk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yueranfly.top/Article/details/gtguqhkype.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dashuyun.cn/Article/details/gtfvndmqfi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gaohongyu789.top/Article/details/gtfxtxlrqa.html

[P08] 处理浮点精度问题
来源：http://dali.dashuyun.cn/Article/details/gtceuwibcg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.0kj1m.cn/Article/details/gtpxwnuuxa.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cdnleiting.top/Article/details/gteakelwxx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yongpay.top/Article/details/gtosimmyki.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcyjdlfqy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.vqdsnc.cn/Article/details/gterydbovt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gotoacloud.top/Article/details/gtnccnpqvb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.andypj.xyz/Article/details/gtdyruiqou.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.snrcjt.cn/Article/details/gtzizddmem.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtfaaburzi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ppjwa.cn/Article/details/gtvqwlcice.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gttroosuiz.html

[Q01] 创建表
来源：http://dali.xuetiantiany.cn/Article/details/gtpyoioizr.html

CREATE TABLE users (
来源：http://dali.yuanzhike.top/Article/details/gtymgjhiyx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gotoacloud.top/Article/details/gtbtggloaq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizyfdruc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.havefunace.top/Article/details/gtamecvjln.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.quarkkingdee.top/Article/details/gtqololyca.html

);
来源：http://dali.vqdsnc.cn/Article/details/gtjesjcoyh.html

[Q02] 创建带外键的表
来源：http://dali.smart0.xyz/Article/details/gtbkufdezi.html

CREATE TABLE orders (
来源：http://dali.sweek.top/Article/details/gtwhedtasa.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gtyndsekjw.html

user_id INT NOT NULL,
来源：http://dali.hnxiangtu.top/Article/details/gtngppemle.html

amount DECIMAL(10, 2),
来源：http://dali.tanke756.top/Article/details/gtggmrcfyp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenjidiqi.icu/Article/details/gteiezttxw.html

);
来源：http://dali.nanxinkj.top/Article/details/gtenwrgsut.html

[Q03] 增加列
来源：http://dali.zycfv.cn/Article/details/gtlflobjcm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cheryme.top/Article/details/gtkfpyxtrb.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpieicjjh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gzhubu.top/Article/details/gtfutgrdkl.html

[Q05] 重命名列
来源：http://dali.jyoumei.cn/Article/details/gtcjgyxbew.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xylfe.cn/Article/details/gtiswfwkqg.html

[Q06] 删除列
来源：http://dali.vqdsnc.cn/Article/details/gtczdivrfn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dianchejie.cn/Article/details/gtyqadxgbf.html

[Q07] 删除表
来源：http://dali.mhx1999.top/Article/details/gtgtwheroq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllcklykp.html

[Q08] 创建普通索引
来源：http://dali.chenlongwang.top/Article/details/gtvipkihoi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gtktlwqbvz.html

[Q09] 创建唯一索引
来源：http://dali.ppjwa.cn/Article/details/gtjdijghtn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gtzepmslzj.html

[Q10] 插入单行
来源：http://dali.aibaodan.cn/Article/details/gtgufqpejs.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gtcmrfxivj.html

[Q11] 一次插入多行
来源：http://dali.sysykeji.top/Article/details/gtyjuwidsh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuanzhike.top/Article/details/gtqdnhgwoc.html

[Q12] 插入后取自增 ID
来源：http://dali.guowangkeji.top/Article/details/gthscpszgp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nwbrower.top/Article/details/gteqdqosmw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.daxiang520.top/Article/details/gtsvpwhzic.html

[Q13] 忽略重复插入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfolwbfk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.0kj1m.cn/Article/details/gtpwfmkztw.html

[Q14] 存在则更新（upsert）
来源：http://dali.sxryk.cn/Article/details/gtpzzmenuk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aizwys.cn/Article/details/gtawhloyqk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.andypj.xyz/Article/details/gtkgukqkon.html

[Q15] 查询全部
来源：http://dali.xinyue.icu/Article/details/gtzgzvssna.html

SELECT * FROM users;
来源：http://dali.birdmap.top/Article/details/gtiqluvufu.html

[Q16] 查询指定列
来源：http://dali.ybcxt.top/Article/details/gtbbgpxmsl.html

SELECT id, name FROM users;
来源：http://dali.yonumen.top/Article/details/gtgdnwxagr.html

[Q17] 条件查询
来源：http://dali.xuetiantiany.cn/Article/details/gtimveyfdr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.mhx1999.top/Article/details/gtnoiphuhk.html

[Q18] 模糊匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtlaptvjrg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxuanxn.top/Article/details/gtupefkyvc.html

[Q19] 范围查询
来源：http://dali.gogol.net.cn/Article/details/gtpbptmttr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jqgufenzy.top/Article/details/gtgviklbgl.html

[Q20] IN 列表
来源：http://dali.shuidangran.top/Article/details/gtcruxhrjk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.havefunace.top/Article/details/gtvmwjxoou.html

[Q21] 空值判断
来源：http://dali.fengsongda.top/Article/details/gtknsnnkyy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthijuohtz.html

[Q22] 排序
来源：http://dali.chenjidiqi.icu/Article/details/gtssrcnotj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tanke756.top/Article/details/gtsardlrjr.html

[Q23] 分页
来源：http://dali.jlsjyb.cn/Article/details/gtwvltpklc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sweek.top/Article/details/gtwjbksjzc.html

[Q24] 去重
来源：http://dali.fzhhl.top/Article/details/gtgrwoegje.html

SELECT DISTINCT city FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtudgmdbvk.html

[Q25] 只取前 N 条
来源：http://dali.hnxiangtu.top/Article/details/gthdjtyanh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sxryk.cn/Article/details/gthrkjlzbb.html

[Q26] 计数
来源：http://dali.zhongyouzk.top/Article/details/gtwkwkzwut.html

SELECT COUNT(*) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtmrqykspu.html

[Q27] 条件计数
来源：http://dali.316326.xyz/Article/details/gtjqlndwxe.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xinyue.icu/Article/details/gtcnfdorjj.html

[Q28] 求和与平均
来源：http://dali.birdmap.top/Article/details/gtzudaoifv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtxnkpcawl.html

[Q29] 最大最小值
来源：http://dali.gotoacloud.top/Article/details/gtxygliqlh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yonumen.top/Article/details/gtluxchomv.html

[Q30] 分组统计
来源：http://dali.sufxvd.cn/Article/details/gtiqqpvxvq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gttqaycmtz.html

[Q31] 分组后过滤
来源：http://dali.hysaishi.cn/Article/details/gtstemsfuf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.andypj.xyz/Article/details/gtskawmdmw.html

[Q32] 分组拼接字符串
来源：http://dali.havefunace.top/Article/details/gtuvmmzaof.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtbsyedevz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hongshengwenyu.top/Article/details/gtubndqnej.html

[Q33] 多列分组
来源：http://dali.yangfankeji.com/Article/details/gtmaxyzzem.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jiagoushi.top/Article/details/gtyachjbpr.html

[Q34] 每组取第一条
来源：http://dali.jinghuilouyu.cn/Article/details/gtclwosohu.html

SELECT * FROM (
来源：http://dali.xziqi.cn/Article/details/gtxoyssruf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pycfn.com/Article/details/gthveakftv.html

) t WHERE rn = 1;
来源：http://dali.vqdsnc.cn/Article/details/gthouduwrf.html

[Q35] 内连接
来源：http://dali.jinqigufen.top/Article/details/gtexfujalo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gtidtokvhh.html

[Q36] 左连接
来源：http://dali.sweek.top/Article/details/gtqutenryu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gtmvodvloy.html

[Q37] 右连接
来源：http://dali.zhengqikj.top/Article/details/gtjrwnwozm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tanke756.top/Article/details/gtfsueaiej.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.svipenyu.cn/Article/details/gtpcobsvgf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj202588.top/Article/details/gtytejnmxv.html

[Q39] 自连接（查上下级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdennqzy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj20258888.top/Article/details/gtswqdscou.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtmpookcpz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangshuangyany.cn/Article/details/gtemdlwhsi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xinyue.icu/Article/details/gtdsjnmxpt.html

[Q41] 多表连接
来源：http://dali.chenlongwang.top/Article/details/gtcbcezqik.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yongpay.top/Article/details/gtnisacacn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ydzc1.top/Article/details/gtgfgeqxtw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gtgrfxwvnw.html

[Q42] 连接条件附加过滤
来源：http://dali.pycfn.com/Article/details/gtgldhjlxq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.wangshuangyany.cn/Article/details/gttbuawbdn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.vqdsnc.cn/Article/details/gtkialqisx.html

[Q43] 标量子查询
来源：http://dali.jyoumei.cn/Article/details/gtcfljwsry.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenjidiqi.icu/Article/details/gtfnozsbzf.html

[Q44] IN 子查询
来源：http://dali.andypj.xyz/Article/details/gtxqibfnzm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sufxvd.cn/Article/details/gtsgxytvtb.html

[Q45] EXISTS 判断存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjadsutfc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gtjicfgjyg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xuanzx.com/Article/details/gtwsmwjicl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhoulong.xyz/Article/details/gtckswfeav.html

[Q47] 与平均值比较
来源：http://dali.pycfn.com/Article/details/gtaeotyyuc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hongshengwenyu.top/Article/details/gtiickfopo.html

[Q48] CTE 公用表表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnyxnmexo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gtnvfhjueb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xinyue.icu/Article/details/gtyypstawz.html

[Q49] 更新单行
来源：http://dali.feifeiyinyue.top/Article/details/gtrpnsqoni.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gtdamewfgx.html

[Q50] 批量更新
来源：http://dali.cucudq.cn/Article/details/gtebsbzzct.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hammf.cn/Article/details/gtidtglaso.html

[Q51] 用子查询更新
来源：http://dali.birdmap.top/Article/details/gtecqsyimg.html


<!-- 参考信息 -->