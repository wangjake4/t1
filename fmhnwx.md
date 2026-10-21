代发 wailian999

Py:   itertools.permutations(arr)
来源：http://dali.zycfv.cn/Article/details/gtqcgezxuy.html

PHP:  // 手写递归交换
来源：http://dali.havefunace.top/Article/details/gtdfvttnpc.html

JS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbpuqohr.html

TS:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtkgwotuyw.html

Java: // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtspvahnux.html

Go:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtwlcqgrxz.html

Ruby: arr.permutation.to_a
来源：http://dali.jianghu66.top/Article/details/gtnyholfwm.html

C#:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtslxgkspn.html

[N09] 栈与队列
来源：http://dali.vqdsnc.cn/Article/details/gtaytpvrhl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gogol.net.cn/Article/details/gtsjteeeol.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj20258.top/Article/details/gtysfsomvk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtxrwivwvs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gzhubu.top/Article/details/gttdlrligo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ehwqpu.com/Article/details/gtjsdwggas.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hysaishi.cn/Article/details/gtikwqheqb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gthztjhbox.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnqzz.top/Article/details/gttwsskhhb.html

[N10] 链表节点定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlximoghe.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yangfankeji.com/Article/details/gtarryhlfc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgfzy.top/Article/details/gtuxcjyvmp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hysaishi.cn/Article/details/gtbdrwrdnt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sxryk.cn/Article/details/gtkjqwtecv.html

Java: class Node { int v; Node next; }
来源：http://dali.pycfn.com/Article/details/gtqqtojoye.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ybcxt.top/Article/details/gtwmjcdxjr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinqigufen.top/Article/details/gthfcqfoja.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nwbrower.top/Article/details/gtkklqmakx.html

[N11] 二叉树中序遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtdffpimyq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fzhhl.top/Article/details/gtvfdaucsu.html

PHP:  // 手写递归函数
来源：http://dali.cdnleiting.top/Article/details/gthhawyuga.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guowangkeji.top/Article/details/gtcbrfyrbf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.redwolf501.top/Article/details/gtrauwqnbq.html

Java: // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtukbojbzs.html

Go:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gtqdcwvvdr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jiagoushi.top/Article/details/gtenhxyyfk.html

C#:   // 手写递归
来源：http://dali.tian-w.cn/Article/details/gtjwckqtxt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gotoacloud.top/Article/details/gtdceherqh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhoulong.xyz/Article/details/gtofpdhigp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.wangdashe.top/Article/details/gtrkkfzgqp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gtwwnydrnl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gtzwzalgdm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenzaomai.com/Article/details/gtxiajolke.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xylfe.cn/Article/details/gtwmqmqzbt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cashguo.top/Article/details/gtnywocwpu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dashuyun.cn/Article/details/gtesbdnmkb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtsfulsiea.html

O. 并发与异步
来源：http://dali.guannengcc.top/Article/details/gtipfeopcy.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaoifynyy.html

[O01] 启动一个线程
来源：http://dali.pycfn.com/Article/details/gtsfofbijm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jiagoushi.top/Article/details/gtafluhknc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zycfv.cn/Article/details/gtuqlqqavg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gtcwkuwwut.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gthjafwgqh.html

Java: new Thread(() -> f()).start()
来源：http://dali.shzxlz.cn/Article/details/gtbhapoyui.html

Go:   go f()
来源：http://dali.yvedp.cn/Article/details/gtiowjmmyq.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyifdeocs.html

C#:   Task.Run(() => F());
来源：http://dali.yueranfly.top/Article/details/gtpkfmngpj.html

[O02] 使用线程池
来源：http://dali.smart0.xyz/Article/details/gtpdxuqnyh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.dashuyun.cn/Article/details/gtzzauhwnl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hammf.cn/Article/details/gtqxvnnnsd.html

JS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gtdzyaagwy.html

TS:   // worker_threads 线程池
来源：http://dali.jianghu66.top/Article/details/gtueqycomd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ybcxt.top/Article/details/gtlucxfkxg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gtykolngnp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.bjfxy.top/Article/details/gtwkpzxpgg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdukylhu.html

[O03] 加锁保护共享数据
来源：http://dali.gotoacloud.top/Article/details/gtveryobiv.html

Py:   with lock: shared += 1
来源：http://dali.ppjwa.cn/Article/details/gtfcwgoquw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fzhhl.top/Article/details/gtjcsnwhns.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yuxming.cn/Article/details/gtzuxjkblh.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gtdzinjspv.html

Java: synchronized (this) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gtsbulianf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sufxvd.cn/Article/details/gttzsnnbyf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.quarkkingdee.top/Article/details/gtbzphyxxo.html

C#:   lock (gate) { shared++; }
来源：http://dali.ppjwa.cn/Article/details/gtrhgemwan.html

[O04] 定义异步函数并等待
来源：http://dali.vqdsnc.cn/Article/details/gtuhcprsyl.html

Py:   async def f():⏎    await g()
来源：http://dali.yj202588.top/Article/details/gttmqdxnzb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shuidangran.top/Article/details/gtkijepqfg.html

JS:   async function f() { await g(); }
来源：http://dali.9152youxi.cn/Article/details/gtsdwohmzf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gtepfaqpqq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yonumen.top/Article/details/gtrhsagugo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cashguo.top/Article/details/gtbtgwakis.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmhtzguzv.html

C#:   async Task F() { await G(); }
来源：http://dali.zhengqikj.top/Article/details/gtdvjlbufk.html

[O05] 并发执行并等待全部完成
来源：http://dali.xinyue.icu/Article/details/gtpeaorikt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrivwymqv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xziqi.cn/Article/details/gtstgovjsi.html

JS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gtpdxugozb.html

TS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gtxutmidvs.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwugwmxz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenzaomai.com/Article/details/gtuzoddqrg.html

Ruby: threads.map(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gtfrlgtlrn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgufenzy.top/Article/details/gtueqtavqm.html

[O06] 使用进程池
来源：http://dali.daxiang520.top/Article/details/gtgjgqeofn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yvedp.cn/Article/details/gtqqjlgabl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yangfankeji.com/Article/details/gtvgqplavc.html

JS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gtkyhlhweo.html

TS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gtmfzlrhik.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gtqdpcirgp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hnxiangtu.top/Article/details/gtqzuqgelg.html

Ruby: // fork 块
来源：http://dali.wangshuangyany.cn/Article/details/gtyvxuwsoe.html

C#:   Parallel.For
来源：http://dali.c1oappe.top/Article/details/gtzeqrvmgj.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtpzvplgsd.html

P. 常用工具函数
来源：http://dali.cucudq.cn/Article/details/gtorvktzam.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtiovkjhoa.html

[P01] 生成 UUID
来源：http://dali.jlsjyb.cn/Article/details/gtsghxoxfk.html

Py:   str(uuid.uuid4())
来源：http://dali.zhoulong.xyz/Article/details/gtdtwtzbju.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.havefunace.top/Article/details/gtockghbhu.html

JS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtjzfrsfej.html

TS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gtmktkozbe.html

Java: UUID.randomUUID().toString()
来源：http://dali.ivvv.top/Article/details/gtkifwaqyj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj202588.top/Article/details/gtzgxheoif.html

Ruby: SecureRandom.uuid
来源：http://dali.fzhhl.top/Article/details/gtnxcedpxa.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jlsjyb.cn/Article/details/gtsfthidao.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jyoumei.cn/Article/details/gtgesmhwnx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zycfv.cn/Article/details/gtyhohnfbl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.redwolf501.top/Article/details/gtsdpceffn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yanxiufei.cn/Article/details/gtmltexbum.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj202588.top/Article/details/gtzwozjrmo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtgyehrzuc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gzhubu.top/Article/details/gtdoelexsh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shzxlz.cn/Article/details/gtdsodhegm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258.top/Article/details/gtezpzojfe.html

[P03] 生成短随机字符串
来源：http://dali.jyoumei.cn/Article/details/gtruylomke.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ybcxt.top/Article/details/gtbcakmktr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.haohaochexian.top/Article/details/gtqyqjtgnx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.snrcjt.cn/Article/details/gttryjlyax.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gtrhrvzksc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cheryme.top/Article/details/gtspismemt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xziqi.cn/Article/details/gtksxtszyd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gotoacloud.top/Article/details/gtcqligznh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cdnleiting.top/Article/details/gtevxlfcws.html

[P04] 求长度
来源：http://dali.zhixingplan.top/Article/details/gtsnehvdhb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ydzc1.top/Article/details/gtjvltacxx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtrgiwhllw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangtech.top/Article/details/gtbznjuwcz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.havefunace.top/Article/details/gtzayytevv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gzhubu.top/Article/details/gtvxwrvkya.html

Go:   len(arr);  len(m)
来源：http://dali.316326.xyz/Article/details/gthtoezqvx.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gtywydpfut.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gtpzmmgnkq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.316326.xyz/Article/details/gtaxwppipv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinghuilouyu.cn/Article/details/gtekmisjme.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gaohongyu789.top/Article/details/gtpqmguutu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuxming.cn/Article/details/gtdnkmocss.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shuidangran.top/Article/details/gtccbzczhy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hysaishi.cn/Article/details/gtokytkqag.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtsacwzzck.html

Ruby: a == b
来源：http://dali.yongpay.top/Article/details/gthpfnhvjw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sweek.top/Article/details/gtablvqjml.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zycfv.cn/Article/details/gttyycdwml.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hammf.cn/Article/details/gtbzztoqkb.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gtjnuehuna.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hywenlv.cn/Article/details/gtaggehfzk.html

TS:   if (x == null) {}
来源：http://dali.gotoacloud.top/Article/details/gtjgitsobh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.haohaochexian.top/Article/details/gtovquuxsx.html

Go:   if x == nil {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtjsaucrkq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbnilngt.html

C#:   if (x is null) {}
来源：http://dali.xuanzx.com/Article/details/gthqmcfztt.html

[P07] 防抖与节流
来源：http://dali.fengsongda.top/Article/details/gtlddulrvy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yanxiufei.cn/Article/details/gtiurhkfaz.html

PHP:  // 手写时间戳比较
来源：http://dali.meibo888.top/Article/details/gtcdszfhqx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gtmsiqalli.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdipxdzb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yangfankeji.com/Article/details/gtpcxgfmak.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.redwolf501.top/Article/details/gtfbuvzxut.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.haohaochexian.top/Article/details/gtpdgorapc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.pycfn.com/Article/details/gtdgpevntc.html

[P08] 处理浮点精度问题
来源：http://dali.sweek.top/Article/details/gtxnaieprm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nanxuanxn.top/Article/details/gtlhqtupws.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tanke756.top/Article/details/gtjfczkjhi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ybcxt.top/Article/details/gtebddhalq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hywenlv.cn/Article/details/gtkdqfdqgd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ppjwa.cn/Article/details/gtwvbggdbg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gotoacloud.top/Article/details/gtychwcpdt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dashuyun.cn/Article/details/gtbbwidiec.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhengqikj.top/Article/details/gtgprwordc.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtegraguir.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gzhubu.top/Article/details/gthstddbif.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtghvepghk.html

[Q01] 创建表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngbmgsyn.html

CREATE TABLE users (
来源：http://dali.cucudq.cn/Article/details/gtadynmsrp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gtegwovkxn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.dianchejie.cn/Article/details/gtemutaaoo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuanzhike.top/Article/details/gtowsybofv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbrqckeo.html

);
来源：http://dali.cashguo.top/Article/details/gthacgdtqs.html

[Q02] 创建带外键的表
来源：http://dali.havefunace.top/Article/details/gtnmjvdueu.html

CREATE TABLE orders (
来源：http://dali.9152youxi.cn/Article/details/gtfdbehpsw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gtmxjrpwbr.html

user_id INT NOT NULL,
来源：http://dali.xylfe.cn/Article/details/gtahomhcrj.html

amount DECIMAL(10, 2),
来源：http://dali.cashguo.top/Article/details/gtfwaxtsxd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.kuanghao11.cn/Article/details/gtxaxpvsyq.html

);
来源：http://dali.fzhhl.top/Article/details/gtaihcaymf.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gtexfvycdb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hongshengwenyu.top/Article/details/gtjabmjbcn.html

[Q04] 修改列类型
来源：http://dali.chenjidiqi.icu/Article/details/gtzoupngxu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuxming.cn/Article/details/gtkcmzhguu.html

[Q05] 重命名列
来源：http://dali.pengpengdd.cyou/Article/details/gttqidmaeo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangshuangyany.cn/Article/details/gtbirefbla.html

[Q06] 删除列
来源：http://dali.guannengcc.top/Article/details/gtemukdmkt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dashuyun.cn/Article/details/gthsbioyiq.html

[Q07] 删除表
来源：http://dali.vqdsnc.cn/Article/details/gtitgxykoq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ybcxt.top/Article/details/gttgfhcjos.html

[Q08] 创建普通索引
来源：http://dali.sweek.top/Article/details/gtrgjwkauw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cqqwz.cn/Article/details/gtiygkelbj.html

[Q09] 创建唯一索引
来源：http://dali.hongshengwenyu.top/Article/details/gtgdcrhqxk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gtqshfemko.html

[Q10] 插入单行
来源：http://dali.tian-w.cn/Article/details/gtzkspwlnf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.fengsongda.top/Article/details/gtghhaellz.html

[Q11] 一次插入多行
来源：http://dali.pengpengdd.cyou/Article/details/gtvkqdbiig.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.guannengcc.top/Article/details/gtdbouacyc.html

[Q12] 插入后取自增 ID
来源：http://dali.zhengqikj.top/Article/details/gtjzrpdztp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqpyuhew.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nanxinkj.top/Article/details/gtgtwqxnzv.html

[Q13] 忽略重复插入
来源：http://dali.316326.xyz/Article/details/gttrmugubd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cashguo.top/Article/details/gtkewlemdu.html

[Q14] 存在则更新（upsert）
来源：http://dali.haohaochexian.top/Article/details/gtmwrtwvbn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhoulong.xyz/Article/details/gtkqnmowxt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nwbrower.top/Article/details/gtkbezzdpl.html

[Q15] 查询全部
来源：http://dali.hfpthk.cn/Article/details/gthqnezmpm.html

SELECT * FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtqlcdwtml.html

[Q16] 查询指定列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmvyvgqj.html

SELECT id, name FROM users;
来源：http://dali.cheryme.top/Article/details/gtpfeytcai.html

[Q17] 条件查询
来源：http://dali.0kj1m.cn/Article/details/gtrgjkjuxi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtaaapqczm.html

[Q18] 模糊匹配
来源：http://dali.jianghu66.top/Article/details/gttaxprfka.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxinkj.top/Article/details/gtxmgcnfgi.html

[Q19] 范围查询
来源：http://dali.nanxuanxn.top/Article/details/gtcoewztms.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.mhx1999.top/Article/details/gthoyufdwt.html

[Q20] IN 列表
来源：http://dali.fzhhl.top/Article/details/gtxsynnidu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ivvv.top/Article/details/gtwwudajox.html

[Q21] 空值判断
来源：http://dali.jinqigufen.top/Article/details/gtojokklid.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangdashe.top/Article/details/gtvjvshieg.html

[Q22] 排序
来源：http://dali.xylfe.cn/Article/details/gtauvgrfuu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj202588.top/Article/details/gtxdvcuzvl.html

[Q23] 分页
来源：http://dali.yj20258888.top/Article/details/gtrrwpkkfp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nanxinkj.top/Article/details/gtpewzfswa.html

[Q24] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gtkfdrxjxi.html

SELECT DISTINCT city FROM users;
来源：http://dali.ybcxt.top/Article/details/gtavtqvjzo.html

[Q25] 只取前 N 条
来源：http://dali.wangdashe.top/Article/details/gtgyaldbdi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikdfcvex.html

[Q26] 计数
来源：http://dali.dashuyun.cn/Article/details/gtwmwpzujw.html

SELECT COUNT(*) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtqhunyucs.html

[Q27] 条件计数
来源：http://dali.jinghuilouyu.cn/Article/details/gtltxszwui.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtcqxiuwdd.html

[Q28] 求和与平均
来源：http://dali.vqdsnc.cn/Article/details/gtecijdcyy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtubwmniai.html

[Q29] 最大最小值
来源：http://dali.xinyue.icu/Article/details/gtkyzygfaz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtifjfwwxf.html

[Q30] 分组统计
来源：http://dali.yj20258.top/Article/details/gtvkaoaygl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gtpkpcjaky.html

[Q31] 分组后过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtumzitvqx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvreewzwz.html

[Q32] 分组拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtasdneyrg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gtzfhribga.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ydzc1.top/Article/details/gtejrhdedy.html

[Q33] 多列分组
来源：http://dali.tanke756.top/Article/details/gtpwztaqrf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nwbrower.top/Article/details/gthtinjijt.html

[Q34] 每组取第一条
来源：http://dali.jinghuilouyu.cn/Article/details/gtadnabnba.html

SELECT * FROM (
来源：http://dali.zhongyouzk.top/Article/details/gtlsifygme.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fengsongda.top/Article/details/gtsobjfvgk.html

) t WHERE rn = 1;
来源：http://dali.ybcxt.top/Article/details/gtitfkixmt.html

[Q35] 内连接
来源：http://dali.ivvv.top/Article/details/gtltuewxrb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gtcfclmvce.html

[Q36] 左连接
来源：http://dali.ybcxt.top/Article/details/gtmhgitcmu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gtivzerdgt.html

[Q37] 右连接
来源：http://dali.meibo888.top/Article/details/gtevtnlgpz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.snrcjt.cn/Article/details/gtlskmxfid.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gaohongyu789.top/Article/details/gtpwovcnyz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xziqi.cn/Article/details/gtrnkevfvd.html

[Q39] 自连接（查上下级）
来源：http://dali.dianchejie.cn/Article/details/gtaoikbhux.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yvedp.cn/Article/details/gtslqwedqe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.guannengcc.top/Article/details/gtsvgwrvfz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ehwqpu.com/Article/details/gtzxkwneie.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jiagoushi.top/Article/details/gtfruxxxno.html

[Q41] 多表连接
来源：http://dali.dashuyun.cn/Article/details/gtzvowstwk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gaohongyu789.top/Article/details/gthfmubric.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yongpay.top/Article/details/gtxmvagkdm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxinkj.top/Article/details/gtebgqsyeh.html

[Q42] 连接条件附加过滤
来源：http://dali.haohaochexian.top/Article/details/gtjjqefoua.html

SELECT u.name, o.amount FROM users u
来源：http://dali.wangdashe.top/Article/details/gtsuymbyyb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwtlidowo.html

[Q43] 标量子查询
来源：http://dali.gotoacloud.top/Article/details/gtotxclmxu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hammf.cn/Article/details/gtmkzgeysi.html

[Q44] IN 子查询
来源：http://dali.vqdsnc.cn/Article/details/gtsuoelfgt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjttxlvw.html

[Q45] EXISTS 判断存在
来源：http://dali.xuetiantiany.cn/Article/details/gtlabkwonz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrwmvbha.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqrgnwnq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jianghu66.top/Article/details/gtnyqbxijv.html

[Q47] 与平均值比较
来源：http://dali.xziqi.cn/Article/details/gtkxjkglji.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hfpthk.cn/Article/details/gtmgtsqqxp.html

[Q48] CTE 公用表表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtzhsjreqi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yonumen.top/Article/details/gtqbvbiyxj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.9152youxi.cn/Article/details/gtthollujh.html

[Q49] 更新单行
来源：http://dali.shuidangran.top/Article/details/gthnoydpqk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gtyqqbdfoc.html

[Q50] 批量更新
来源：http://dali.yj20258888.top/Article/details/gtrrfaderz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwcuafbo.html

[Q51] 用子查询更新
来源：http://dali.sysykeji.top/Article/details/gtmtukbkoj.html


<!-- 参考信息 -->