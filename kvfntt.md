代发 wailian999

Py:   itertools.permutations(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtuagcuowp.html

PHP:  // 手写递归交换
来源：http://dali.c1oappe.top/Article/details/gtmtvftjgp.html

JS:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtbznttlvl.html

TS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtwnyslaeh.html

Java: // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gthmtlfxpy.html

Go:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtxwuqkkfx.html

Ruby: arr.permutation.to_a
来源：http://dali.ehwqpu.com/Article/details/gtyxredxip.html

C#:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtwmfqvsfn.html

[N09] 栈与队列
来源：http://dali.tanke756.top/Article/details/gtqcdpdszc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtpwxkhnes.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shuidangran.top/Article/details/gtmbhnpmgv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtmijepnyy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuetiantiany.cn/Article/details/gtruugksbb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guowangkeji.top/Article/details/gtgowioiqk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.iojbl.cn/Article/details/gtmavjewtq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gtufdteigp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258.top/Article/details/gtqfquatjp.html

[N10] 链表节点定义
来源：http://dali.shangyingyoupin.top/Article/details/gtfyveyvml.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gaohongyu789.top/Article/details/gtsbrltxhw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ppjwa.cn/Article/details/gtrwaqyqbe.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtikvtcsco.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jyoumei.cn/Article/details/gtzvlbwhcb.html

Java: class Node { int v; Node next; }
来源：http://dali.cucudq.cn/Article/details/gtwwbroeje.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hywenlv.cn/Article/details/gttmubkyye.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenlongwang.top/Article/details/gtecccycst.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxmsfgce.html

[N11] 二叉树中序遍历
来源：http://dali.jlsjyb.cn/Article/details/gthpkodncr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hysaishi.cn/Article/details/gtgcfziycl.html

PHP:  // 手写递归函数
来源：http://dali.sweek.top/Article/details/gtuugzuqdn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhixingplan.top/Article/details/gtokxqqihc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gtshcohlej.html

Java: // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtepuyfasz.html

Go:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gtjyxwdozu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pycfn.com/Article/details/gtvbhrfgco.html

C#:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gtwkbgoqeh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.dashuyun.cn/Article/details/gtcvsnykbd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gtniplukpi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenzaomai.com/Article/details/gtytfqjzcz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzdaqmzl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gtroyuhagk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtexvgieei.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gaohongyu789.top/Article/details/gttvfkysrx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.guowangkeji.top/Article/details/gtbgwqemto.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gtrvifgnru.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtkjigyxth.html

O. 并发与异步
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjukyxbki.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtwrmixgds.html

[O01] 启动一个线程
来源：http://dali.hnqzz.top/Article/details/gtiqdiexxx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinqigfzy.top/Article/details/gtcxgobzus.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jianghu66.top/Article/details/gtwvpfuwri.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgufenzy.top/Article/details/gtmdkmnpkg.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gtsmiusvkm.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgufenzy.top/Article/details/gthbnaqyfd.html

Go:   go f()
来源：http://dali.daria6918.cn/Article/details/gtwwlazxhb.html

Ruby: Thread.new { f }
来源：http://dali.sufxvd.cn/Article/details/gtoykjtyry.html

C#:   Task.Run(() => F());
来源：http://dali.iojbl.cn/Article/details/gtisypbvar.html

[O02] 使用线程池
来源：http://dali.jyoumei.cn/Article/details/gtufsdttrh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guowangkeji.top/Article/details/gtgbffkqre.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigufen.top/Article/details/gtttwblcvu.html

JS:   // worker_threads 线程池
来源：http://dali.snrcjt.cn/Article/details/gtjrvctaev.html

TS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gttoiavott.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gaohongyu789.top/Article/details/gtsunytqrg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xylfe.cn/Article/details/gtgcppksxr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aizwys.cn/Article/details/gtejwfjirw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.iojbl.cn/Article/details/gtwwszjfip.html

[O03] 加锁保护共享数据
来源：http://dali.yuxming.cn/Article/details/gtufkorfpu.html

Py:   with lock: shared += 1
来源：http://dali.jinqigfzy.top/Article/details/gtxqxohymu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shzxlz.cn/Article/details/gtbhbajijr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hywenlv.cn/Article/details/gtupfmmarf.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gtqjbsjwry.html

Java: synchronized (this) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gteypkvmda.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangdashe.top/Article/details/gtpfigamca.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sxryk.cn/Article/details/gtuilmyhdp.html

C#:   lock (gate) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gtjlahubdf.html

[O04] 定义异步函数并等待
来源：http://dali.ybcxt.top/Article/details/gtawmoslcp.html

Py:   async def f():⏎    await g()
来源：http://dali.ppjwa.cn/Article/details/gtwdtqckjx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xuanzx.com/Article/details/gtfozswplz.html

JS:   async function f() { await g(); }
来源：http://dali.fzhhl.top/Article/details/gtwcjztfmo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ivvv.top/Article/details/gtdicrywcv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sysykeji.top/Article/details/gtxjtpshxw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daxiang520.top/Article/details/gtxqkkjfjn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmszqgqq.html

C#:   async Task F() { await G(); }
来源：http://dali.9152youxi.cn/Article/details/gtwnlbcukv.html

[O05] 并发执行并等待全部完成
来源：http://dali.jiagoushi.top/Article/details/gttbkfqmus.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gogol.net.cn/Article/details/gtkuyfhvfo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenzaomai.com/Article/details/gtjumcnqdk.html

JS:   await Promise.all(tasks)
来源：http://dali.9152youxi.cn/Article/details/gtnybcxgez.html

TS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwdrrvcq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gogol.net.cn/Article/details/gtixxbmnuy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenlongwang.top/Article/details/gtmyendxje.html

Ruby: threads.map(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gtbtcfroem.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgfzy.top/Article/details/gtybaivhyr.html

[O06] 使用进程池
来源：http://dali.tanke756.top/Article/details/gtifczwfcj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nanxinkj.top/Article/details/gtrcrwqtxh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nwbrower.top/Article/details/gtocxvxyxg.html

JS:   // child_process / cluster 模块
来源：http://dali.birdmap.top/Article/details/gtkaakqxsb.html

TS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gtvotenixn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinqigfzy.top/Article/details/gtbrjvwxak.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.smart0.xyz/Article/details/gtazhiwfxx.html

Ruby: // fork 块
来源：http://dali.zhixingplan.top/Article/details/gtgjsxwcir.html

C#:   Parallel.For
来源：http://dali.sxryk.cn/Article/details/gtnzewmyhp.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtkxmscnzx.html

P. 常用工具函数
来源：http://dali.ivvv.top/Article/details/gtbfccpzdq.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtvbwmwybp.html

[P01] 生成 UUID
来源：http://dali.yonumen.top/Article/details/gtvcifkext.html

Py:   str(uuid.uuid4())
来源：http://dali.shzxlz.cn/Article/details/gtftdvffoq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yongpay.top/Article/details/gtbvydzgsh.html

JS:   crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gtrribwphq.html

TS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqabyaxht.html

Java: UUID.randomUUID().toString()
来源：http://dali.cheryme.top/Article/details/gtrkgfpewo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuanzhike.top/Article/details/gtjqkfwctf.html

Ruby: SecureRandom.uuid
来源：http://dali.zycfv.cn/Article/details/gtneuyzsys.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aizwys.cn/Article/details/gtnoacxzni.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258.top/Article/details/gtvpasrlvr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xinyue.icu/Article/details/gtubidxrec.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yuxming.cn/Article/details/gttqoqiauf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hfpthk.cn/Article/details/gtivkhvxsp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zycfv.cn/Article/details/gtjtoloimh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.bjfxy.top/Article/details/gtpcnmobmu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigufen.top/Article/details/gtoypzzyjc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xylfe.cn/Article/details/gtrohucsgu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sufxvd.cn/Article/details/gtdvaygksk.html

[P03] 生成短随机字符串
来源：http://dali.daria6918.cn/Article/details/gtldldftrj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shangyingyoupin.top/Article/details/gtmnmfehla.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.fengsongda.top/Article/details/gtadccpylf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gtxetmgmcr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cheryme.top/Article/details/gtboufyvfu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuxming.cn/Article/details/gtbjdbbnxg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zdqjudy.top/Article/details/gtlxodvfmt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xinyue.icu/Article/details/gtroqaruwy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.kuanghao11.cn/Article/details/gtjphwsafp.html

[P04] 求长度
来源：http://dali.sufxvd.cn/Article/details/gtbgmyngqr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tian-w.cn/Article/details/gtxrzffmyr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gttmlybdnz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gtmpegtsue.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gteyytcrsi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gtycrrhcah.html

Go:   len(arr);  len(m)
来源：http://dali.jiagoushi.top/Article/details/gtztfyxqub.html

Ruby: x.length;  x.size
来源：http://dali.gaohongyu789.top/Article/details/gtysytuqmg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.haohaochexian.top/Article/details/gtaimmnmwa.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hywenlv.cn/Article/details/gtkhcizfij.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hammf.cn/Article/details/gtshznaqgt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.svipenyu.cn/Article/details/gtechwsetf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cheryme.top/Article/details/gthbbgmjaf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.316326.xyz/Article/details/gtycrdocup.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tanke756.top/Article/details/gtdtjezxov.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gtulyzuqbb.html

Ruby: a == b
来源：http://dali.aizwys.cn/Article/details/gtrnqrpkln.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yvedp.cn/Article/details/gthecwteen.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.redwolf501.top/Article/details/gteozdiozc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tianlin.xyz/Article/details/gtyntxsupb.html

PHP:  if (empty($x)) {}
来源：http://dali.zdqjudy.top/Article/details/gtudbiadwj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaezbmgpc.html

TS:   if (x == null) {}
来源：http://dali.daria6918.cn/Article/details/gtavssnhph.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yuanzhike.top/Article/details/gtsibnwwkk.html

Go:   if x == nil {}
来源：http://dali.jinqigufen.top/Article/details/gtinknzepw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.feifeiyinyue.top/Article/details/gtjwrgkytz.html

C#:   if (x is null) {}
来源：http://dali.guowangkeji.top/Article/details/gtxrllzvvg.html

[P07] 防抖与节流
来源：http://dali.zhoulong.xyz/Article/details/gtjcbtysxp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.iojbl.cn/Article/details/gtbzulzztq.html

PHP:  // 手写时间戳比较
来源：http://dali.chenzaomai.com/Article/details/gteefyguda.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gtuashybln.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gttyhvyxnx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxinkj.top/Article/details/gtohjyyawv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jyoumei.cn/Article/details/gtzlywgutf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.redwolf501.top/Article/details/gtfljrzqjv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gzhubu.top/Article/details/gtkbdwbepm.html

[P08] 处理浮点精度问题
来源：http://dali.jqgfzy.top/Article/details/gtrvvsnxaq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.meibo888.top/Article/details/gtlnkemlmy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xziqi.cn/Article/details/gtevnpzmvt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhaomingkeji.xyz/Article/details/gturwwzuxs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nwbrower.top/Article/details/gtiopgicue.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jqgfzy.top/Article/details/gtcopzuebc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jqgufenzy.top/Article/details/gtqlekxles.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.aibaodan.cn/Article/details/gtqswhhpui.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guowangkeji.top/Article/details/gtecfcdelq.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gthzhbecru.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cqqwz.cn/Article/details/gtpuiwplzv.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtbglszzaw.html

[Q01] 创建表
来源：http://dali.zycfv.cn/Article/details/gtjuznasup.html

CREATE TABLE users (
来源：http://dali.hnxiangtu.top/Article/details/gtlccknhwy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gtyhoxowqk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.pengpengdd.cyou/Article/details/gthremxviq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigfzy.top/Article/details/gtiiadiynj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zycfv.cn/Article/details/gtkyqfvdbp.html

);
来源：http://dali.chenzaomai.com/Article/details/gtajinsjts.html

[Q02] 创建带外键的表
来源：http://dali.yj202588.top/Article/details/gtvmmqtren.html

CREATE TABLE orders (
来源：http://dali.ydzc1.top/Article/details/gtxixfiolg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jlsjyb.cn/Article/details/gtnsvqkvow.html

user_id INT NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gtcaqmykgz.html

amount DECIMAL(10, 2),
来源：http://dali.ybcxt.top/Article/details/gtuavfyqyb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenlongwang.top/Article/details/gttagbctrn.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gtliclnozz.html

[Q03] 增加列
来源：http://dali.yongpay.top/Article/details/gtvspntmbe.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shzxlz.cn/Article/details/gtlaxupfgq.html

[Q04] 修改列类型
来源：http://dali.gogol.net.cn/Article/details/gtsrrmwhdt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nanxinkj.top/Article/details/gtxrlmvylj.html

[Q05] 重命名列
来源：http://dali.kuanghao11.cn/Article/details/gtlnbvnxab.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ehwqpu.com/Article/details/gtvtyqtccp.html

[Q06] 删除列
来源：http://dali.c1oappe.top/Article/details/gtmlfuothb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hfpthk.cn/Article/details/gtdznchgge.html

[Q07] 删除表
来源：http://dali.zhoulong.xyz/Article/details/gtyeiwpzfm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hnxiangtu.top/Article/details/gtmhxtenwp.html

[Q08] 创建普通索引
来源：http://dali.redwolf501.top/Article/details/gtzhbezhxg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.0kj1m.cn/Article/details/gtzdwvhcyj.html

[Q09] 创建唯一索引
来源：http://dali.sysykeji.top/Article/details/gtoaeponda.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.mhx1999.top/Article/details/gtrlmruquf.html

[Q10] 插入单行
来源：http://dali.hysaishi.cn/Article/details/gtqwqzzumu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtkiqnedjf.html

[Q11] 一次插入多行
来源：http://dali.gzhubu.top/Article/details/gtlwxuurqa.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtlswiijxw.html

[Q12] 插入后取自增 ID
来源：http://dali.yueranfly.top/Article/details/gtxktjivtc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pycfn.com/Article/details/gthvzgeyrb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.iojbl.cn/Article/details/gtqhdepslw.html

[Q13] 忽略重复插入
来源：http://dali.zhengqikj.top/Article/details/gtvhqkzowt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqqesagg.html

[Q14] 存在则更新（upsert）
来源：http://dali.cqqwz.cn/Article/details/gtdvghbeje.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.pengpengdd.cyou/Article/details/gtmtdhxqdi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shzxlz.cn/Article/details/gtlrkbejsa.html

[Q15] 查询全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumfbpmhd.html

SELECT * FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtwtmbgrhn.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gtumyducrv.html

SELECT id, name FROM users;
来源：http://dali.hammf.cn/Article/details/gtesgubqdt.html

[Q17] 条件查询
来源：http://dali.yangfankeji.com/Article/details/gtyybjexru.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258888.top/Article/details/gtswerudcv.html

[Q18] 模糊匹配
来源：http://dali.gotoacloud.top/Article/details/gtvhjdulth.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ivvv.top/Article/details/gtrqomkqbd.html

[Q19] 范围查询
来源：http://dali.xuetiantiany.cn/Article/details/gtgsmndybj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.c1oappe.top/Article/details/gtnrpnygrd.html

[Q20] IN 列表
来源：http://dali.hnqzz.top/Article/details/gtiabrnuvt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sxryk.cn/Article/details/gtmxbkybsn.html

[Q21] 空值判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkuyjxev.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ybcxt.top/Article/details/gtbesztbfq.html

[Q22] 排序
来源：http://dali.ydzc1.top/Article/details/gtrhxgorqi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ybcxt.top/Article/details/gtimdkmidp.html

[Q23] 分页
来源：http://dali.jianghu66.top/Article/details/gtbqhrkuel.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gaohongyu789.top/Article/details/gtvbyfvieu.html

[Q24] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlebiaifo.html

SELECT DISTINCT city FROM users;
来源：http://dali.ybcxt.top/Article/details/gttcjqajjx.html

[Q25] 只取前 N 条
来源：http://dali.nwbrower.top/Article/details/gtlrpjrknf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tianlin.xyz/Article/details/gttdbtpsfl.html

[Q26] 计数
来源：http://dali.smart0.xyz/Article/details/gteuozrzvu.html

SELECT COUNT(*) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtgjhztdfv.html

[Q27] 条件计数
来源：http://dali.daria6918.cn/Article/details/gtinldhxnu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtzkwnqqtc.html

[Q28] 求和与平均
来源：http://dali.yj20258.top/Article/details/gteusavrng.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gttlxbkwdn.html

[Q29] 最大最小值
来源：http://dali.sysykeji.top/Article/details/gtmdwqfbju.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtwivakabg.html

[Q30] 分组统计
来源：http://dali.fengsongda.top/Article/details/gtpeshxhhy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtfhymzsuk.html

[Q31] 分组后过滤
来源：http://dali.ydzc1.top/Article/details/gtrclferkp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ppjwa.cn/Article/details/gtmdwtvywo.html

[Q32] 分组拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gtjzqdgrpy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtjlowxkxv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shuidangran.top/Article/details/gtrybdcerf.html

[Q33] 多列分组
来源：http://dali.hysaishi.cn/Article/details/gtgqmdljfr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tanke756.top/Article/details/gtsospkgjl.html

[Q34] 每组取第一条
来源：http://dali.jiagoushi.top/Article/details/gtjraolkga.html

SELECT * FROM (
来源：http://dali.shzxlz.cn/Article/details/gtffuyefwy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yangfankeji.com/Article/details/gtvhjdurny.html

) t WHERE rn = 1;
来源：http://dali.tanke756.top/Article/details/gtwypjxdaf.html

[Q35] 内连接
来源：http://dali.hnqzz.top/Article/details/gthfkrrqea.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gtfqciptie.html

[Q36] 左连接
来源：http://dali.hongshengwenyu.top/Article/details/gtlmqtdkhy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sysykeji.top/Article/details/gtpssoahps.html

[Q37] 右连接
来源：http://dali.chenjidiqi.icu/Article/details/gtvujgpknp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cdnleiting.top/Article/details/gtopuiojai.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cqqwz.cn/Article/details/gtvaebrjjb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tanke756.top/Article/details/gthnnkxihv.html

[Q39] 自连接（查上下级）
来源：http://dali.hywenlv.cn/Article/details/gtwtsklevn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenzaomai.com/Article/details/gtyxenphsq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ydzc1.top/Article/details/gttiycxtjt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xuetiantiany.cn/Article/details/gtxcdzczdg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.svipenyu.cn/Article/details/gtfiqfrgse.html

[Q41] 多表连接
来源：http://dali.yj202588.top/Article/details/gtrmehyvtl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cheryme.top/Article/details/gtnedwviss.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yvedp.cn/Article/details/gterkhqjse.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.feifeiyinyue.top/Article/details/gtcnzvotvl.html

[Q42] 连接条件附加过滤
来源：http://dali.aizwys.cn/Article/details/gtbwmahqej.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hywenlv.cn/Article/details/gtpetmacuj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jianghu66.top/Article/details/gttmuizvey.html

[Q43] 标量子查询
来源：http://dali.mhx1999.top/Article/details/gtrjdcujel.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ivvv.top/Article/details/gtlhkphbqp.html

[Q44] IN 子查询
来源：http://dali.guowangkeji.top/Article/details/gtymvdasbd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangdashe.top/Article/details/gtwoexweox.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigfzy.top/Article/details/gtdhidbdnw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtzidmsubx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ehwqpu.com/Article/details/gtcdseerap.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gtnjpgnylw.html

[Q47] 与平均值比较
来源：http://dali.jyoumei.cn/Article/details/gtwcvldvvp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhongyouzk.top/Article/details/gtvxnhdhio.html

[Q48] CTE 公用表表达式
来源：http://dali.cdnleiting.top/Article/details/gtybnnghkr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.birdmap.top/Article/details/gtpykvapjm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258.top/Article/details/gttnicglpq.html

[Q49] 更新单行
来源：http://dali.yj202588.top/Article/details/gttrubhlnl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yangfankeji.com/Article/details/gtcnafrliw.html

[Q50] 批量更新
来源：http://dali.xylfe.cn/Article/details/gtkobpmzxp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtrqqzrvme.html

[Q51] 用子查询更新
来源：http://dali.meibo888.top/Article/details/gtkaijzbmp.html


<!-- 参考信息 -->