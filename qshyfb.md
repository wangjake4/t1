代发 wailian999

Ruby: s == s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtlvguxacm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gtcpznmdtm.html

[N07] 两数之和（返回下标）
来源：http://dali.wangdashe.top/Article/details/gtfwlnwjsq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cheryme.top/Article/details/gtaxnnjqey.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yanxiufei.cn/Article/details/gtbjhnqcbr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgufenzy.top/Article/details/gtralphlob.html

TS:   // 手写 Map<string, number>
来源：http://dali.jyoumei.cn/Article/details/gtpvgefaaa.html

Java: // 手写 HashMap
来源：http://dali.nanxuanxn.top/Article/details/gtfuvubvgl.html

Go:   // 手写 map[int]int
来源：http://dali.316326.xyz/Article/details/gtyvfbhavn.html

Ruby: // 手写 Hash
来源：http://dali.wangshuangyany.cn/Article/details/gtnpcucmnb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.mhx1999.top/Article/details/gtjygprxee.html

[N08] 生成全排列
来源：http://dali.yuxming.cn/Article/details/gtrvbqcwgl.html

Py:   itertools.permutations(arr)
来源：http://dali.redwolf501.top/Article/details/gtzygrwufz.html

PHP:  // 手写递归交换
来源：http://dali.zhengqikj.top/Article/details/gtifqagkmw.html

JS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtfugjwilp.html

TS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtniqgrxuz.html

Java: // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtwxwaqqoq.html

Go:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtvmvvembe.html

Ruby: arr.permutation.to_a
来源：http://dali.andypj.xyz/Article/details/gtenctguek.html

C#:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtixuvxduu.html

[N09] 栈与队列
来源：http://dali.aibaodan.cn/Article/details/gtdogiyuwl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gotoacloud.top/Article/details/gtgbpepass.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gtjevyxsgu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtruxjbstq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.pycfn.com/Article/details/gtsabdplgg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.0kj1m.cn/Article/details/gtealdbwyh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aibaodan.cn/Article/details/gtapgiilrl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtbgrsakbn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hfpthk.cn/Article/details/gtazuiayfq.html

[N10] 链表节点定义
来源：http://dali.ydzc1.top/Article/details/gtnaqzmhzx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.smart0.xyz/Article/details/gtwgtyhwtg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xziqi.cn/Article/details/gtthrnlydv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.meibo888.top/Article/details/gtatpqeexh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangdashe.top/Article/details/gtfdqjuqxo.html

Java: class Node { int v; Node next; }
来源：http://dali.sweek.top/Article/details/gtpihywani.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jqgfzy.top/Article/details/gtscgsprxo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzyrlxes.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yongpay.top/Article/details/gtmsleqpho.html

[N11] 二叉树中序遍历
来源：http://dali.cashguo.top/Article/details/gtpwhmmmuv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.0kj1m.cn/Article/details/gtrrcingzd.html

PHP:  // 手写递归函数
来源：http://dali.316326.xyz/Article/details/gtfvqibdau.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwjcvyak.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gtmqnvnsyq.html

Java: // 手写递归
来源：http://dali.ybcxt.top/Article/details/gtcwacbhpm.html

Go:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gtwkskaqou.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zdqjudy.top/Article/details/gtovlurbdd.html

C#:   // 手写递归
来源：http://dali.sweek.top/Article/details/gttifqswjs.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shanyushiyangtech.top/Article/details/gtfoveqfig.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yuxming.cn/Article/details/gtqszabeep.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cheryme.top/Article/details/gtohwmshze.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigufen.top/Article/details/gtpugzftpv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangtech.top/Article/details/gtocnibtkr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gthqiucqbm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sxryk.cn/Article/details/gtetdxxyyz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dashuyun.cn/Article/details/gtriacwdhn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gtdnqwmkyb.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtavmfmncn.html

O. 并发与异步
来源：http://dali.zhixingplan.top/Article/details/gteozygoby.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxtxxrsp.html

[O01] 启动一个线程
来源：http://dali.redwolf501.top/Article/details/gtagfjqdmh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xylfe.cn/Article/details/gttuyqtwyd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpohlsfqh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ivvv.top/Article/details/gtknifbjty.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gtbwmhuiyv.html

Java: new Thread(() -> f()).start()
来源：http://dali.jyoumei.cn/Article/details/gtgkmjjhlx.html

Go:   go f()
来源：http://dali.yuanzhike.top/Article/details/gtumsexids.html

Ruby: Thread.new { f }
来源：http://dali.yj20258888.top/Article/details/gtcmodxsjd.html

C#:   Task.Run(() => F());
来源：http://dali.chenzaomai.com/Article/details/gthnorspuy.html

[O02] 使用线程池
来源：http://dali.svipenyu.cn/Article/details/gtklejkfcr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhengqikj.top/Article/details/gtfhhgizez.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtrpknhxyz.html

JS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gttrgrycvg.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtqskjpdax.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.9152youxi.cn/Article/details/gtxrgmegjn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ydzc1.top/Article/details/gtjztnslox.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ehwqpu.com/Article/details/gtjtjuulti.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnqzz.top/Article/details/gtwwgqbndl.html

[O03] 加锁保护共享数据
来源：http://dali.nwbrower.top/Article/details/gtsyawezvu.html

Py:   with lock: shared += 1
来源：http://dali.quarkkingdee.top/Article/details/gtmkfayafe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenlongwang.top/Article/details/gtdwmumson.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zdqjudy.top/Article/details/gtplvwtrna.html

TS:   // 同 JS
来源：http://dali.yongpay.top/Article/details/gtkulwqcqc.html

Java: synchronized (this) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gtscxznwud.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jiagoushi.top/Article/details/gtvgpbafov.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.dianchejie.cn/Article/details/gtaphvknvb.html

C#:   lock (gate) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gtirvfyglp.html

[O04] 定义异步函数并等待
来源：http://dali.feifeiyinyue.top/Article/details/gtlntkbvxb.html

Py:   async def f():⏎    await g()
来源：http://dali.wangdashe.top/Article/details/gtjqyrwnmz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cucudq.cn/Article/details/gtwkhflxlf.html

JS:   async function f() { await g(); }
来源：http://dali.gzhubu.top/Article/details/gtqssxsfeh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gtyihheenq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.vqdsnc.cn/Article/details/gtqgmquefs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj202588.top/Article/details/gtkvrfvwch.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hywenlv.cn/Article/details/gttbukmemq.html

C#:   async Task F() { await G(); }
来源：http://dali.aizwys.cn/Article/details/gtnocqshgh.html

[O05] 并发执行并等待全部完成
来源：http://dali.c1oappe.top/Article/details/gtovsuqxds.html

Py:   asyncio.gather(*tasks)
来源：http://dali.aibaodan.cn/Article/details/gtcotaafjz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yonumen.top/Article/details/gtiybhmill.html

JS:   await Promise.all(tasks)
来源：http://dali.jyoumei.cn/Article/details/gtflolwwpz.html

TS:   await Promise.all(tasks)
来源：http://dali.gogol.net.cn/Article/details/gtqimromks.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.iojbl.cn/Article/details/gtfiztmezt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hywenlv.cn/Article/details/gtdppunohm.html

Ruby: threads.map(&:join)
来源：http://dali.yuanzhike.top/Article/details/gtxiiphzgl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yuxming.cn/Article/details/gtsfpqlzdl.html

[O06] 使用进程池
来源：http://dali.zhongyouzk.top/Article/details/gtwbqxfcvp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cashguo.top/Article/details/gtabeueols.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shzxlz.cn/Article/details/gtiwxcpxbx.html

JS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gtpbclamxp.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gtmzjsnikt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzoelziiv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xinyue.icu/Article/details/gtxidvzayr.html

Ruby: // fork 块
来源：http://dali.yvedp.cn/Article/details/gtqrezqyge.html

C#:   Parallel.For
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqozctyw.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtqwoicefj.html

P. 常用工具函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtwuexfkbf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtgxqtlmiv.html

[P01] 生成 UUID
来源：http://dali.jlsjyb.cn/Article/details/gtvzmexwlr.html

Py:   str(uuid.uuid4())
来源：http://dali.yonumen.top/Article/details/gtveodpwdv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhoulong.xyz/Article/details/gtfbhdeybe.html

JS:   crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gtjnsmykmq.html

TS:   crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gtttosztzs.html

Java: UUID.randomUUID().toString()
来源：http://dali.jyoumei.cn/Article/details/gtloajnzgh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dianchejie.cn/Article/details/gtkyxvruql.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258.top/Article/details/gtdhtdyowk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jqgfzy.top/Article/details/gtetmogvnt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.mhx1999.top/Article/details/gtkajpxhfa.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hywenlv.cn/Article/details/gtjtahmbkh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hysaishi.cn/Article/details/gthzfkrsxl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuxming.cn/Article/details/gtsiqpyngh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.quarkkingdee.top/Article/details/gtgbiuqdnj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtdrmgiqyh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hongshengwenyu.top/Article/details/gtqdvxzfsl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cqqwz.cn/Article/details/gtjtlfhcrs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuanzx.com/Article/details/gtynzrtioy.html

[P03] 生成短随机字符串
来源：http://dali.shzxlz.cn/Article/details/gtinuxsmrc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gtugakrzuc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinqigfzy.top/Article/details/gtevdczndr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gttlmzzytk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gaohongyu789.top/Article/details/gtpyyzpcwe.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj20258.top/Article/details/gtpbayyctc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yvedp.cn/Article/details/gtzbejarcv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ivvv.top/Article/details/gtucsvlycc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.andypj.xyz/Article/details/gtxzabewti.html

[P04] 求长度
来源：http://dali.yangfankeji.com/Article/details/gteybeiyrt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuxming.cn/Article/details/gtjpwgvcvx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtmxakinbn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gtrfqeobaq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gtavhtcevk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xziqi.cn/Article/details/gtztmnwrru.html

Go:   len(arr);  len(m)
来源：http://dali.kuanghao11.cn/Article/details/gtkcsllfmt.html

Ruby: x.length;  x.size
来源：http://dali.daxiang520.top/Article/details/gtrbhyxomg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.daria6918.cn/Article/details/gtubsuwlnr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nwbrower.top/Article/details/gtcaioswal.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guowangkeji.top/Article/details/gtxvdzcuao.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zycfv.cn/Article/details/gtqpbnjtdy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fengsongda.top/Article/details/gtrorozysb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guannengcc.top/Article/details/gtfryzimpb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gogol.net.cn/Article/details/gtucavyvdf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258888.top/Article/details/gtnfbyjzdd.html

Ruby: a == b
来源：http://dali.feifeiyinyue.top/Article/details/gtgidiourz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.dianchejie.cn/Article/details/gtjrfrosyr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ppjwa.cn/Article/details/gtfzvwjpwj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shuidangran.top/Article/details/gtjguiphdn.html

PHP:  if (empty($x)) {}
来源：http://dali.jiagoushi.top/Article/details/gthrozjiog.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gogol.net.cn/Article/details/gtjlfurtfg.html

TS:   if (x == null) {}
来源：http://dali.tian-w.cn/Article/details/gtliobihuq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gtxfpicosr.html

Go:   if x == nil {}
来源：http://dali.iojbl.cn/Article/details/gtqmrilakf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.guannengcc.top/Article/details/gthzyitwkv.html

C#:   if (x is null) {}
来源：http://dali.chenzaomai.com/Article/details/gtcojpxxgw.html

[P07] 防抖与节流
来源：http://dali.meibo888.top/Article/details/gtjhkcjikr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj202588.top/Article/details/gtexxydetu.html

PHP:  // 手写时间戳比较
来源：http://dali.gaohongyu789.top/Article/details/gtdnfjdsvr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gtaqnlllcz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gtvqudhaml.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtkllxavtv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yangfankeji.com/Article/details/gtvbssbkfe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ivvv.top/Article/details/gtxiyrnzmo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.meibo888.top/Article/details/gtiiapdhjk.html

[P08] 处理浮点精度问题
来源：http://dali.shzxlz.cn/Article/details/gtiuwhogas.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cqqwz.cn/Article/details/gtqgjgaksq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tian-w.cn/Article/details/gtedbukcts.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.snrcjt.cn/Article/details/gtcitkcyym.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.redwolf501.top/Article/details/gtbtyhrsop.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsskjaso.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jqgfzy.top/Article/details/gtrzqumyij.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yongpay.top/Article/details/gtgzohragb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cucudq.cn/Article/details/gtfljbttsm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtshwckyjb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbowaowob.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtiuavdxim.html

[Q01] 创建表
来源：http://dali.yuxming.cn/Article/details/gtrbadnoqn.html

CREATE TABLE users (
来源：http://dali.zhengqikj.top/Article/details/gtpvvrsnfb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gtitiymbyd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gtdtktxphb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zycfv.cn/Article/details/gtwtlvbgsb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.vqdsnc.cn/Article/details/gtgsfzxiia.html

);
来源：http://dali.guowangkeji.top/Article/details/gtkjszutik.html

[Q02] 创建带外键的表
来源：http://dali.jianghu66.top/Article/details/gtczilhcuj.html

CREATE TABLE orders (
来源：http://dali.dashuyun.cn/Article/details/gtpvtysiev.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gotoacloud.top/Article/details/gtmtwfiplv.html

user_id INT NOT NULL,
来源：http://dali.yonumen.top/Article/details/gtolpudjov.html

amount DECIMAL(10, 2),
来源：http://dali.wangdashe.top/Article/details/gtqlahmxmy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.andypj.xyz/Article/details/gtbpdtpkqe.html

);
来源：http://dali.dianchejie.cn/Article/details/gttgtpsbcu.html

[Q03] 增加列
来源：http://dali.dianchejie.cn/Article/details/gtbwqsxokf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shuidangran.top/Article/details/gtnmcnczxf.html

[Q04] 修改列类型
来源：http://dali.tianlin.xyz/Article/details/gtqwftntrn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnqzz.top/Article/details/gtfmxdcqsy.html

[Q05] 重命名列
来源：http://dali.jqgufenzy.top/Article/details/gtepatoakv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gaohongyu789.top/Article/details/gtkxeeywmr.html

[Q06] 删除列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkhvcjzg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinqigufen.top/Article/details/gtotknipjg.html

[Q07] 删除表
来源：http://dali.chenjidiqi.icu/Article/details/gtppgvcgev.html

DROP TABLE IF EXISTS orders;
来源：http://dali.guannengcc.top/Article/details/gtkwqglaai.html

[Q08] 创建普通索引
来源：http://dali.nanxinkj.top/Article/details/gtbwylcndu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shuidangran.top/Article/details/gtnluttrwv.html

[Q09] 创建唯一索引
来源：http://dali.cdnleiting.top/Article/details/gtfxqjvlpq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gtdeurbwyt.html

[Q10] 插入单行
来源：http://dali.haohaochexian.top/Article/details/gtrmxfqltz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xylfe.cn/Article/details/gtjzgzafiq.html

[Q11] 一次插入多行
来源：http://dali.jianghu66.top/Article/details/gtvxktajra.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gtqjuyibpj.html

[Q12] 插入后取自增 ID
来源：http://dali.hammf.cn/Article/details/gtmurelxry.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yongpay.top/Article/details/gtuznsswec.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinghuilouyu.cn/Article/details/gtlddbsqru.html

[Q13] 忽略重复插入
来源：http://dali.ybcxt.top/Article/details/gtpmtagnhn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gotoacloud.top/Article/details/gtiledsdhw.html

[Q14] 存在则更新（upsert）
来源：http://dali.bjfxy.top/Article/details/gtzdbqnwvo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.9152youxi.cn/Article/details/gtmxykfyat.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhongyouzk.top/Article/details/gtfutkzdsv.html

[Q15] 查询全部
来源：http://dali.zycfv.cn/Article/details/gtruhxbcah.html

SELECT * FROM users;
来源：http://dali.xylfe.cn/Article/details/gtkwtytgin.html

[Q16] 查询指定列
来源：http://dali.nanxinkj.top/Article/details/gtsfcjnacl.html

SELECT id, name FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtmssfptlp.html

[Q17] 条件查询
来源：http://dali.jyoumei.cn/Article/details/gtjawyiedf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.havefunace.top/Article/details/gthvkbrvwu.html

[Q18] 模糊匹配
来源：http://dali.ppjwa.cn/Article/details/gtdmiaaxsh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.feifeiyinyue.top/Article/details/gtuaknourm.html

[Q19] 范围查询
来源：http://dali.sxryk.cn/Article/details/gtpknwqfgi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.iojbl.cn/Article/details/gtspzxkjpg.html

[Q20] IN 列表
来源：http://dali.redwolf501.top/Article/details/gtpatabjrr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj20258888.top/Article/details/gtfpzhvwcw.html

[Q21] 空值判断
来源：http://dali.dianchejie.cn/Article/details/gtnbabqmxs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnqzz.top/Article/details/gtjouwelzz.html

[Q22] 排序
来源：http://dali.smart0.xyz/Article/details/gtpwsxdzeq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gogol.net.cn/Article/details/gtwzwawmxn.html

[Q23] 分页
来源：http://dali.cashguo.top/Article/details/gtaerfmqjw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dianchejie.cn/Article/details/gtsrprollw.html

[Q24] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gtlwnwudwp.html

SELECT DISTINCT city FROM users;
来源：http://dali.meibo888.top/Article/details/gtpldrvrho.html

[Q25] 只取前 N 条
来源：http://dali.zhongyouzk.top/Article/details/gtyetuqroz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sxryk.cn/Article/details/gtbuwmhntw.html

[Q26] 计数
来源：http://dali.gaohongyu789.top/Article/details/gthuwcgvso.html

SELECT COUNT(*) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtjwqiztay.html

[Q27] 条件计数
来源：http://dali.aibaodan.cn/Article/details/gtnoqmsyoh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtbwpcuabq.html

[Q28] 求和与平均
来源：http://dali.yj202588.top/Article/details/gtfbeockon.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtlkwyssnq.html

[Q29] 最大最小值
来源：http://dali.andypj.xyz/Article/details/gtatrmhjsz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtdvbbyqhp.html

[Q30] 分组统计
来源：http://dali.gzhubu.top/Article/details/gtgbictccp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gtbyqaxain.html

[Q31] 分组后过滤
来源：http://dali.jqgufenzy.top/Article/details/gtxloaazof.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zdqjudy.top/Article/details/gtpocfyrzu.html

[Q32] 分组拼接字符串
来源：http://dali.cashguo.top/Article/details/gtlnmuvdsw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gtkrhhjtvp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.redwolf501.top/Article/details/gtsmeiiqgb.html

[Q33] 多列分组
来源：http://dali.jqgufenzy.top/Article/details/gtuhdrdmik.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jyoumei.cn/Article/details/gthmcsomrt.html

[Q34] 每组取第一条
来源：http://dali.cdnleiting.top/Article/details/gtaszbeyuq.html

SELECT * FROM (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkamaiox.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yvedp.cn/Article/details/gtlsjjkaxa.html

) t WHERE rn = 1;
来源：http://dali.gogol.net.cn/Article/details/gtgeljknkj.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gthxhxtofg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cashguo.top/Article/details/gtpaskjjkp.html

[Q36] 左连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzwmouan.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gtlahgfrig.html

[Q37] 右连接
来源：http://dali.iojbl.cn/Article/details/gtkisfxwdx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtquxfzdlb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuxming.cn/Article/details/gtqbuhuthr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuanzhike.top/Article/details/gtnhbsoioo.html

[Q39] 自连接（查上下级）
来源：http://dali.hnxiangtu.top/Article/details/gturkvmqkk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigufen.top/Article/details/gtbwgbnyca.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aibaodan.cn/Article/details/gtzfhuyheo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jlsjyb.cn/Article/details/gtmjskeeno.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.havefunace.top/Article/details/gtlgbbrmvp.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gtlmcvpfkw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cashguo.top/Article/details/gtiqjjmfgj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fzhhl.top/Article/details/gtasznlurm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhoulong.xyz/Article/details/gtugcbecdg.html

[Q42] 连接条件附加过滤
来源：http://dali.smart0.xyz/Article/details/gtxjlxscmg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ehwqpu.com/Article/details/gtoqmyxyix.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangshuangyany.cn/Article/details/gtimpekfvc.html

[Q43] 标量子查询
来源：http://dali.mhx1999.top/Article/details/gtqjfwqjuz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cheryme.top/Article/details/gtgmpmodkj.html

[Q44] IN 子查询
来源：http://dali.yuxming.cn/Article/details/gtgxgayqra.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.haohaochexian.top/Article/details/gtxtunwdxr.html

[Q45] EXISTS 判断存在
来源：http://dali.svipenyu.cn/Article/details/gtnafoxqty.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daxiang520.top/Article/details/gtsgagbfxp.html


<!-- 参考信息 -->