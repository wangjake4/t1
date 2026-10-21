代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.birdmap.top/Article/details/gtzxyadrzy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.mhx1999.top/Article/details/gtyptdlniv.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnzeqzxu.html

Java: // 手写 HashMap
来源：http://dali.xylfe.cn/Article/details/gtmvwnvsov.html

Go:   // 手写 map[int]int
来源：http://dali.hnxiangtu.top/Article/details/gthasvlwqg.html

Ruby: // 手写 Hash
来源：http://dali.wangshuangyany.cn/Article/details/gtjsfnpubz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.snrcjt.cn/Article/details/gtkmpillnh.html

[N08] 生成全排列
来源：http://dali.nanxinkj.top/Article/details/gteawexzak.html

Py:   itertools.permutations(arr)
来源：http://dali.sysykeji.top/Article/details/gtebddrrnb.html

PHP:  // 手写递归交换
来源：http://dali.nwbrower.top/Article/details/gtrybiockz.html

JS:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtwdenheqn.html

TS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtytsnpfiu.html

Java: // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gttgjpojat.html

Go:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtgxfpmvhp.html

Ruby: arr.permutation.to_a
来源：http://dali.sysykeji.top/Article/details/gtidowgapi.html

C#:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtioyfuyzp.html

[N09] 栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gtafxbskva.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sysykeji.top/Article/details/gtsnfcilps.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazqwvses.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtvfwnuvjo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yvedp.cn/Article/details/gtigwjrcku.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.smart0.xyz/Article/details/gtzjbqekpa.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ydzc1.top/Article/details/gtkcsdxxkh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gtycshiatk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tanke756.top/Article/details/gtfmrvmgqc.html

[N10] 链表节点定义
来源：http://dali.nanxuanxn.top/Article/details/gtcetpwryo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.havefunace.top/Article/details/gtdmsvjsan.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cheryme.top/Article/details/gtlaztbaha.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nanxuanxn.top/Article/details/gttvtffbie.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.aizwys.cn/Article/details/gtgzcsqtps.html

Java: class Node { int v; Node next; }
来源：http://dali.9152youxi.cn/Article/details/gtiopfqgal.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shzxlz.cn/Article/details/gtriwvcukp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cdnleiting.top/Article/details/gthhszvvce.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xuanzx.com/Article/details/gtvbtgjxvl.html

[N11] 二叉树中序遍历
来源：http://dali.jianghu66.top/Article/details/gtpgnluzwa.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sweek.top/Article/details/gtzlndeswj.html

PHP:  // 手写递归函数
来源：http://dali.xylfe.cn/Article/details/gtpgbiagga.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangdashe.top/Article/details/gtqjkrhhud.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gtljngjutt.html

Java: // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gtcsuzzttr.html

Go:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gtcejpuapq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.birdmap.top/Article/details/gtfuhlprdn.html

C#:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtmjjlidtf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aizwys.cn/Article/details/gtzawwtyfd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqeudkrx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.guannengcc.top/Article/details/gtrtfqkrtp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhiwuduotai.top/Article/details/gtzoseusfw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjksgrmbk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gtaatgjtic.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pengpengdd.cyou/Article/details/gtlhqzvnzz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xinyue.icu/Article/details/gtkhncpgca.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gtzdvtnulp.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtgednhdea.html

O. 并发与异步
来源：http://dali.sweek.top/Article/details/gtmyflgbyn.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtgrzlskoc.html

[O01] 启动一个线程
来源：http://dali.smart0.xyz/Article/details/gtxviyqqgf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xuetiantiany.cn/Article/details/gtymcxoitc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cucudq.cn/Article/details/gtxkzdqnbw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgufenzy.top/Article/details/gtxxwxfkbd.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gtayxfbtwp.html

Java: new Thread(() -> f()).start()
来源：http://dali.redwolf501.top/Article/details/gtcokvzewm.html

Go:   go f()
来源：http://dali.xinyue.icu/Article/details/gtlmzdrblm.html

Ruby: Thread.new { f }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdadsasi.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258.top/Article/details/gtepueorxy.html

[O02] 使用线程池
来源：http://dali.sufxvd.cn/Article/details/gtlnptwljb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fzhhl.top/Article/details/gtkovyeaxl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shangyingyoupin.top/Article/details/gtgblmmzew.html

JS:   // worker_threads 线程池
来源：http://dali.tanke756.top/Article/details/gtiyumyzaz.html

TS:   // worker_threads 线程池
来源：http://dali.gotoacloud.top/Article/details/gtzcuopbui.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cashguo.top/Article/details/gtyimcursd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xinyue.icu/Article/details/gtstbomxai.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gtanufpsrn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shanyushiyangtech.top/Article/details/gtjremljpi.html

[O03] 加锁保护共享数据
来源：http://dali.c1oappe.top/Article/details/gtubhsirak.html

Py:   with lock: shared += 1
来源：http://dali.sxryk.cn/Article/details/gtyebjahjw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nwbrower.top/Article/details/gtwghinqyi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pycfn.com/Article/details/gtygpgqfja.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gtkjspuahd.html

Java: synchronized (this) { shared++; }
来源：http://dali.shuidangran.top/Article/details/gtxjggcezu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.smart0.xyz/Article/details/gttdikpueg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj20258888.top/Article/details/gtfuspsyiw.html

C#:   lock (gate) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gthtyfbeva.html

[O04] 定义异步函数并等待
来源：http://dali.aibaodan.cn/Article/details/gtgponsnmw.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigfzy.top/Article/details/gtcrnmptxn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ybcxt.top/Article/details/gtmnnecxvk.html

JS:   async function f() { await g(); }
来源：http://dali.sweek.top/Article/details/gtvzqwidwl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtqetoityl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.andypj.xyz/Article/details/gtnfrbywsq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hammf.cn/Article/details/gtgjxlihzj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangdashe.top/Article/details/gtzispssef.html

C#:   async Task F() { await G(); }
来源：http://dali.ppjwa.cn/Article/details/gtzcvsgbwp.html

[O05] 并发执行并等待全部完成
来源：http://dali.aizwys.cn/Article/details/gtfvjunpyi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhongyouzk.top/Article/details/gtgzuxfefk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jiagoushi.top/Article/details/gtbgfhjdgk.html

JS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gtheksfylm.html

TS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gtweokdhqv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cdnleiting.top/Article/details/gturdsxftp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnscaqczi.html

Ruby: threads.map(&:join)
来源：http://dali.sxryk.cn/Article/details/gtyukcfiad.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.andypj.xyz/Article/details/gtrwrzszge.html

[O06] 使用进程池
来源：http://dali.jianghu66.top/Article/details/gteffnrsdk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.9152youxi.cn/Article/details/gtpmsirkkw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj20258.top/Article/details/gtexqmoldo.html

JS:   // child_process / cluster 模块
来源：http://dali.smart0.xyz/Article/details/gtvdtjoarr.html

TS:   // child_process / cluster 模块
来源：http://dali.sysykeji.top/Article/details/gtrcsomuak.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.kuanghao11.cn/Article/details/gtsxjekhvt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.feifeiyinyue.top/Article/details/gtmcptxhgh.html

Ruby: // fork 块
来源：http://dali.pycfn.com/Article/details/gtmvlqywzp.html

C#:   Parallel.For
来源：http://dali.hysaishi.cn/Article/details/gtnfcvhmjn.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtrnztftwg.html

P. 常用工具函数
来源：http://dali.kuanghao11.cn/Article/details/gtsdmprcmd.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtxlxaezol.html

[P01] 生成 UUID
来源：http://dali.9152youxi.cn/Article/details/gtpajxeksb.html

Py:   str(uuid.uuid4())
来源：http://dali.yvedp.cn/Article/details/gtbnptdtor.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.birdmap.top/Article/details/gtcqtczcgw.html

JS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gtukryjewp.html

TS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gtbkcjmjse.html

Java: UUID.randomUUID().toString()
来源：http://dali.ivvv.top/Article/details/gtxsmemqel.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvopnqkrt.html

Ruby: SecureRandom.uuid
来源：http://dali.zycfv.cn/Article/details/gtycvtjrus.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuxtskqc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhongyouzk.top/Article/details/gtzwrrhafc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yueranfly.top/Article/details/gteojucksk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aizwys.cn/Article/details/gtygamgtxs.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.smart0.xyz/Article/details/gtrflocolq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ppjwa.cn/Article/details/gtzoafxsdp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.iojbl.cn/Article/details/gttjcmqsxu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtiuvpeuex.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dianchejie.cn/Article/details/gtrbkpnpep.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258.top/Article/details/gtaqmdqjnj.html

[P03] 生成短随机字符串
来源：http://dali.tian-w.cn/Article/details/gtxttvavqd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sweek.top/Article/details/gtczxjxdkp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yangfankeji.com/Article/details/gtbeufcame.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnxiangtu.top/Article/details/gtfxthfqdd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gtxejupmsi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtrsmgiyzg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnxiangtu.top/Article/details/gtphbnzwph.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cheryme.top/Article/details/gtybfbieml.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sufxvd.cn/Article/details/gtnpfpcdgd.html

[P04] 求长度
来源：http://dali.yj20258.top/Article/details/gtqqxfrauu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xuanzx.com/Article/details/gtqzlljrmx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gteiiporez.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gtevpqkzhp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gturygghku.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigfzy.top/Article/details/gtgcaixvlh.html

Go:   len(arr);  len(m)
来源：http://dali.yanxiufei.cn/Article/details/gthglfpldb.html

Ruby: x.length;  x.size
来源：http://dali.zhiwuduotai.top/Article/details/gtknaynpov.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuxming.cn/Article/details/gtrlbfbpps.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dianchejie.cn/Article/details/gtpczhmlhm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.bjfxy.top/Article/details/gtsdmrmpsr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xylfe.cn/Article/details/gtkgaguklz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guowangkeji.top/Article/details/gtthaoxdpx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgfzy.top/Article/details/gtnojugrdn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgufenzy.top/Article/details/gtiuxodtnm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrrgjjlh.html

Ruby: a == b
来源：http://dali.c1oappe.top/Article/details/gtrbxfegmb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ehwqpu.com/Article/details/gtvplfnnyg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yongpay.top/Article/details/gtpuzlyswa.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nwbrower.top/Article/details/gtzowrfbsp.html

PHP:  if (empty($x)) {}
来源：http://dali.mhx1999.top/Article/details/gtbmguwwon.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.andypj.xyz/Article/details/gtmzqmhjzo.html

TS:   if (x == null) {}
来源：http://dali.9152youxi.cn/Article/details/gtmubkpxin.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gtvaxdkzcp.html

Go:   if x == nil {}
来源：http://dali.jyoumei.cn/Article/details/gtcmwdvjyg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.0kj1m.cn/Article/details/gtlmtciavz.html

C#:   if (x is null) {}
来源：http://dali.yanxiufei.cn/Article/details/gtcpkiacrc.html

[P07] 防抖与节流
来源：http://dali.xylfe.cn/Article/details/gtpykmpujn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gtqutlefra.html

PHP:  // 手写时间戳比较
来源：http://dali.kuanghao11.cn/Article/details/gtfpeifvih.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtttetwnav.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gtndswniqp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aibaodan.cn/Article/details/gtjqferkuz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.havefunace.top/Article/details/gthzwxfolh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ydzc1.top/Article/details/gtaxmphvzb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuuolrudq.html

[P08] 处理浮点精度问题
来源：http://dali.shuidangran.top/Article/details/gtapsrenfh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhoulong.xyz/Article/details/gtstmaljgl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtscgjdshq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xziqi.cn/Article/details/gtpiblxfjn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jlsjyb.cn/Article/details/gtanelnsub.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yvedp.cn/Article/details/gthpwmvavi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhiwuduotai.top/Article/details/gtmeiyiwyk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yanxiufei.cn/Article/details/gtynvtiroi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xuanzx.com/Article/details/gtfrebsywh.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtlcouyykf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cheryme.top/Article/details/gtwfbfgqys.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtlcfwxnbn.html

[Q01] 创建表
来源：http://dali.shuidangran.top/Article/details/gtwodywylm.html

CREATE TABLE users (
来源：http://dali.cashguo.top/Article/details/gtdfpfdbbu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gzhubu.top/Article/details/gtketdfxzy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daxiang520.top/Article/details/gtndejomcf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinghuilouyu.cn/Article/details/gtjusxxnmi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenjidiqi.icu/Article/details/gtmmibpswj.html

);
来源：http://dali.ivvv.top/Article/details/gtbqmepjbb.html

[Q02] 创建带外键的表
来源：http://dali.snrcjt.cn/Article/details/gtwzyvfqrd.html

CREATE TABLE orders (
来源：http://dali.tian-w.cn/Article/details/gtdupulibq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gtutoteiti.html

user_id INT NOT NULL,
来源：http://dali.birdmap.top/Article/details/gtnafleruq.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsnhjoof.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenlongwang.top/Article/details/gtmvsamuin.html

);
来源：http://dali.aibaodan.cn/Article/details/gtaebnbjvq.html

[Q03] 增加列
来源：http://dali.tanke756.top/Article/details/gtqxrnuinl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.quarkkingdee.top/Article/details/gtwiipperx.html

[Q04] 修改列类型
来源：http://dali.feifeiyinyue.top/Article/details/gtfcrjwdkw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jiagoushi.top/Article/details/gtczybbanp.html

[Q05] 重命名列
来源：http://dali.gzhubu.top/Article/details/gtxdovrpmi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yuanzhike.top/Article/details/gtfazjuocx.html

[Q06] 删除列
来源：http://dali.meibo888.top/Article/details/gtpksesneu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zdqjudy.top/Article/details/gtbbwwwgjo.html

[Q07] 删除表
来源：http://dali.zhoulong.xyz/Article/details/gtpbubvnnc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.vqdsnc.cn/Article/details/gtjhvqxoiu.html

[Q08] 创建普通索引
来源：http://dali.hnqzz.top/Article/details/gtybkgufql.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.quarkkingdee.top/Article/details/gtfrjixyyr.html

[Q09] 创建唯一索引
来源：http://dali.wangshuangyany.cn/Article/details/gtvdbsvdsd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yvedp.cn/Article/details/gtctkogkdv.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gtkvkvwdqn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yueranfly.top/Article/details/gtynovarlv.html

[Q11] 一次插入多行
来源：http://dali.vqdsnc.cn/Article/details/gtiemunoth.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtjhfmasfq.html

[Q12] 插入后取自增 ID
来源：http://dali.sufxvd.cn/Article/details/gthlwsckos.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gotoacloud.top/Article/details/gtwjziasrl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hysaishi.cn/Article/details/gtcomldyko.html

[Q13] 忽略重复插入
来源：http://dali.snrcjt.cn/Article/details/gtayluoxag.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtlszsafsb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhongyouzk.top/Article/details/gtileevqit.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.svipenyu.cn/Article/details/gtzjhjtkar.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj20258.top/Article/details/gtirkhwgoh.html

[Q15] 查询全部
来源：http://dali.kuanghao11.cn/Article/details/gtihddsmpx.html

SELECT * FROM users;
来源：http://dali.hnqzz.top/Article/details/gtrxclnxwi.html

[Q16] 查询指定列
来源：http://dali.yuanzhike.top/Article/details/gtrkswqpvx.html

SELECT id, name FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtuucyisoo.html

[Q17] 条件查询
来源：http://dali.ydzc1.top/Article/details/gtglwqsucg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.dianchejie.cn/Article/details/gtvugsgmoh.html

[Q18] 模糊匹配
来源：http://dali.ydzc1.top/Article/details/gtcsbnhksq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhiwuduotai.top/Article/details/gthsyxafnq.html

[Q19] 范围查询
来源：http://dali.xuanzx.com/Article/details/gtaeawcewz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yvedp.cn/Article/details/gtrwxhbjya.html

[Q20] IN 列表
来源：http://dali.tanke756.top/Article/details/gtubzxdnso.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuanzhike.top/Article/details/gtonflndfj.html

[Q21] 空值判断
来源：http://dali.jyoumei.cn/Article/details/gtdzodpknv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj202588.top/Article/details/gtmkhjmskt.html

[Q22] 排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtrvftcf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj20258888.top/Article/details/gtedyrcgvt.html

[Q23] 分页
来源：http://dali.gogol.net.cn/Article/details/gtmhjpnkbv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cucudq.cn/Article/details/gtitnktanm.html

[Q24] 去重
来源：http://dali.andypj.xyz/Article/details/gtsuscujfd.html

SELECT DISTINCT city FROM users;
来源：http://dali.redwolf501.top/Article/details/gthbclbjju.html

[Q25] 只取前 N 条
来源：http://dali.zhixingplan.top/Article/details/gtagubbhmh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.bjfxy.top/Article/details/gthkpwlpmo.html

[Q26] 计数
来源：http://dali.ydzc1.top/Article/details/gtkcfdtakk.html

SELECT COUNT(*) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtuukgdolx.html

[Q27] 条件计数
来源：http://dali.nanxuanxn.top/Article/details/gtqwkybtis.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hfpthk.cn/Article/details/gthbbxuntj.html

[Q28] 求和与平均
来源：http://dali.jinqigufen.top/Article/details/gtvmpjygwl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtddsuwuaa.html

[Q29] 最大最小值
来源：http://dali.sxryk.cn/Article/details/gtckwaxdgk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cheryme.top/Article/details/gtdtfcxxhz.html

[Q30] 分组统计
来源：http://dali.jiagoushi.top/Article/details/gtumaunisr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtzowvmsua.html

[Q31] 分组后过滤
来源：http://dali.9152youxi.cn/Article/details/gtvestytax.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.dianchejie.cn/Article/details/gtyjvmhefc.html

[Q32] 分组拼接字符串
来源：http://dali.yonumen.top/Article/details/gtxjthynme.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtxxcnrfid.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tian-w.cn/Article/details/gtjmynukka.html

[Q33] 多列分组
来源：http://dali.yuxming.cn/Article/details/gtpxheswyv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tianlin.xyz/Article/details/gtccfhvkhh.html

[Q34] 每组取第一条
来源：http://dali.yongpay.top/Article/details/gtwcitwohk.html

SELECT * FROM (
来源：http://dali.hfpthk.cn/Article/details/gtnrxvtyid.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guannengcc.top/Article/details/gtkpmhvwjp.html

) t WHERE rn = 1;
来源：http://dali.cucudq.cn/Article/details/gtbcpacfhk.html

[Q35] 内连接
来源：http://dali.yanxiufei.cn/Article/details/gthrizrrvb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tianlin.xyz/Article/details/gtweamcgps.html

[Q36] 左连接
来源：http://dali.haohaochexian.top/Article/details/gtdxernwjc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gtyqubshqr.html

[Q37] 右连接
来源：http://dali.sweek.top/Article/details/gtwmqbdeue.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.mhx1999.top/Article/details/gtlknkuoxw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.daria6918.cn/Article/details/gtgjmnkivd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.iojbl.cn/Article/details/gttcxtyhok.html

[Q39] 自连接（查上下级）
来源：http://dali.redwolf501.top/Article/details/gtzixuybog.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.andypj.xyz/Article/details/gtkqrxipew.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xylfe.cn/Article/details/gtooutygxd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.quarkkingdee.top/Article/details/gtyysyhmph.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.dashuyun.cn/Article/details/gtjfbuizgi.html

[Q41] 多表连接
来源：http://dali.hongshengwenyu.top/Article/details/gtesbggijl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jqgfzy.top/Article/details/gtwqsnmycr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.birdmap.top/Article/details/gthvmmsfks.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hnqzz.top/Article/details/gtpggvertz.html

[Q42] 连接条件附加过滤
来源：http://dali.aizwys.cn/Article/details/gtxsjercra.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobbbtffq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj202588.top/Article/details/gtjckwtjas.html

[Q43] 标量子查询
来源：http://dali.chenjidiqi.icu/Article/details/gtynvpfkkr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sysykeji.top/Article/details/gtamdbmnei.html

[Q44] IN 子查询
来源：http://dali.cucudq.cn/Article/details/gtauaxuklt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hywenlv.cn/Article/details/gtzvrqzeva.html

[Q45] EXISTS 判断存在
来源：http://dali.ehwqpu.com/Article/details/gtdmwzpnkx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gtdokkrdps.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nanxuanxn.top/Article/details/gtnmxazopg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gtdtltmanz.html

[Q47] 与平均值比较
来源：http://dali.mhx1999.top/Article/details/gtzqenrukt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zdqjudy.top/Article/details/gttnrzwymh.html


<!-- 参考信息 -->