代发 wailian999

JS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtgtxnscxi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtgqmwezlx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnesrcnlq.html

Go:   // 双指针从两端比较
来源：http://dali.guannengcc.top/Article/details/gtjblmbnil.html

Ruby: s == s.reverse
来源：http://dali.cdnleiting.top/Article/details/gtyxjyftrt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gtycmfyknc.html

[N07] 两数之和（返回下标）
来源：http://dali.ehwqpu.com/Article/details/gtozzghvdi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnxiangtu.top/Article/details/gtjwwqjaiw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.quarkkingdee.top/Article/details/gtyyzttebl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnbdjzee.html

TS:   // 手写 Map<string, number>
来源：http://dali.fengsongda.top/Article/details/gtpoyocfva.html

Java: // 手写 HashMap
来源：http://dali.zhixingplan.top/Article/details/gtjnjrdyhx.html

Go:   // 手写 map[int]int
来源：http://dali.ppjwa.cn/Article/details/gtpeznqixy.html

Ruby: // 手写 Hash
来源：http://dali.andypj.xyz/Article/details/gtxrofhlgc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cucudq.cn/Article/details/gtqvfbsxcd.html

[N08] 生成全排列
来源：http://dali.fzhhl.top/Article/details/gtasnaqflx.html

Py:   itertools.permutations(arr)
来源：http://dali.yangfankeji.com/Article/details/gtehsumdzo.html

PHP:  // 手写递归交换
来源：http://dali.yonumen.top/Article/details/gtadfqyiih.html

JS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtmbgqrmat.html

TS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtumdwrylh.html

Java: // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtaffzubbd.html

Go:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtanisigzm.html

Ruby: arr.permutation.to_a
来源：http://dali.birdmap.top/Article/details/gtlhbxszxc.html

C#:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtvntrhonm.html

[N09] 栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gthvtkgdsc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xziqi.cn/Article/details/gtdotigwei.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtavshscfx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtiwzhswvs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tian-w.cn/Article/details/gtlqjqlujo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aibaodan.cn/Article/details/gtastzysme.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.dianchejie.cn/Article/details/gtllgqwtjv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gthpbextlb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.kuanghao11.cn/Article/details/gtcntadpxc.html

[N10] 链表节点定义
来源：http://dali.xuanzx.com/Article/details/gtuhpjbpij.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenjidiqi.icu/Article/details/gtkzjqotez.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sysykeji.top/Article/details/gtfqguaxrb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtldagcfjk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.fengsongda.top/Article/details/gtbkvmywuy.html

Java: class Node { int v; Node next; }
来源：http://dali.meibo888.top/Article/details/gthwppqlcr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhongyouzk.top/Article/details/gtkttufrmq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guowangkeji.top/Article/details/gtxxntwlfg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuxming.cn/Article/details/gtkgqusnlb.html

[N11] 二叉树中序遍历
来源：http://dali.316326.xyz/Article/details/gtkffnektj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.birdmap.top/Article/details/gtakpyieiy.html

PHP:  // 手写递归函数
来源：http://dali.daria6918.cn/Article/details/gttuqkolvv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenlongwang.top/Article/details/gtrwubwwwg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gtwjirrcen.html

Java: // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtuqpllpgi.html

Go:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gtqdmqabsv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guannengcc.top/Article/details/gtafquigdw.html

C#:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gtzplynysw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daria6918.cn/Article/details/gtgkcjiioy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhixingplan.top/Article/details/gtuecvfssh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.guannengcc.top/Article/details/gttgepvkqa.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzmvafit.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gthahvtjfw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpdsehgx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigfzy.top/Article/details/gtfqhiqshv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258888.top/Article/details/gtslenaqlg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gtxlpljqlb.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtemwygvez.html

O. 并发与异步
来源：http://dali.guowangkeji.top/Article/details/gtfbhxgtjw.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtdgxgeadc.html

[O01] 启动一个线程
来源：http://dali.pycfn.com/Article/details/gttpjzbxcb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.meibo888.top/Article/details/gtkwcpjglp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.c1oappe.top/Article/details/gtcdmefera.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sufxvd.cn/Article/details/gtmclcobyr.html

TS:   // 同 JS
来源：http://dali.nanxinkj.top/Article/details/gtpiyvejlu.html

Java: new Thread(() -> f()).start()
来源：http://dali.c1oappe.top/Article/details/gtbqnedznq.html

Go:   go f()
来源：http://dali.wangdashe.top/Article/details/gtmzkyixya.html

Ruby: Thread.new { f }
来源：http://dali.chenlongwang.top/Article/details/gtwmoecglm.html

C#:   Task.Run(() => F());
来源：http://dali.aizwys.cn/Article/details/gtzkaewvwy.html

[O02] 使用线程池
来源：http://dali.nanxuanxn.top/Article/details/gtxoulpxvh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hongshengwenyu.top/Article/details/gtmsdfgpwc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenjidiqi.icu/Article/details/gtiqtbyyim.html

JS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gtxmwevuyf.html

TS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gtjulevxip.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzqbnrgt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.iojbl.cn/Article/details/gtsjbwdias.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cdnleiting.top/Article/details/gtiyxkcbrd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jlsjyb.cn/Article/details/gtsnhyxvpq.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigfzy.top/Article/details/gtpnzsivws.html

Py:   with lock: shared += 1
来源：http://dali.dianchejie.cn/Article/details/gtlqmqdcwt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zycfv.cn/Article/details/gtthhlgdpd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.meibo888.top/Article/details/gthsfqhlwa.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrgurxid.html

Java: synchronized (this) { shared++; }
来源：http://dali.zdqjudy.top/Article/details/gtfgzbglck.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ppjwa.cn/Article/details/gtpnhpnkls.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jiagoushi.top/Article/details/gtvcgoglpk.html

C#:   lock (gate) { shared++; }
来源：http://dali.cheryme.top/Article/details/gtchgtsrhe.html

[O04] 定义异步函数并等待
来源：http://dali.hnqzz.top/Article/details/gtxeibhtrd.html

Py:   async def f():⏎    await g()
来源：http://dali.hnqzz.top/Article/details/gtitudsfas.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tian-w.cn/Article/details/gtfzxjulfa.html

JS:   async function f() { await g(); }
来源：http://dali.aibaodan.cn/Article/details/gtjyuipnoc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jianghu66.top/Article/details/gtyxxulkot.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.aizwys.cn/Article/details/gtkgaaqzow.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hongshengwenyu.top/Article/details/gtqxyudmqo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnxiangtu.top/Article/details/gtwwjohaen.html

C#:   async Task F() { await G(); }
来源：http://dali.cdnleiting.top/Article/details/gtelxamrnm.html

[O05] 并发执行并等待全部完成
来源：http://dali.vqdsnc.cn/Article/details/gtkdvekqaz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ybcxt.top/Article/details/gtnauwkrff.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cashguo.top/Article/details/gtpmoiotgi.html

JS:   await Promise.all(tasks)
来源：http://dali.jyoumei.cn/Article/details/gtznsnlxju.html

TS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtrrugxsrv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhongyouzk.top/Article/details/gtodnnvcuw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dashuyun.cn/Article/details/gtwxqjquze.html

Ruby: threads.map(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gtnkhruawj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yangfankeji.com/Article/details/gtrleimags.html

[O06] 使用进程池
来源：http://dali.yvedp.cn/Article/details/gtlioymifz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xylfe.cn/Article/details/gtktkxituo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nanxinkj.top/Article/details/gtiosyospp.html

JS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gtlynbxsac.html

TS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gtpwqpiajy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nanxinkj.top/Article/details/gtdxfsgmph.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jianghu66.top/Article/details/gtfolnbhcd.html

Ruby: // fork 块
来源：http://dali.zhongyouzk.top/Article/details/gtonvxskfw.html

C#:   Parallel.For
来源：http://dali.shuidangran.top/Article/details/gtrlkqrfuk.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gttxdkkiyl.html

P. 常用工具函数
来源：http://dali.jlsjyb.cn/Article/details/gtqpqtfsxe.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtnzolgjrx.html

[P01] 生成 UUID
来源：http://dali.zhoulong.xyz/Article/details/gtiqydydoe.html

Py:   str(uuid.uuid4())
来源：http://dali.wangshuangyany.cn/Article/details/gtxvvrqmmx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ppjwa.cn/Article/details/gtbetvkmcd.html

JS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gthbhnevse.html

TS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gtmlxyfqgr.html

Java: UUID.randomUUID().toString()
来源：http://dali.c1oappe.top/Article/details/gtmlbmotag.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hysaishi.cn/Article/details/gtqfnpixky.html

Ruby: SecureRandom.uuid
来源：http://dali.quarkkingdee.top/Article/details/gtewhhhxle.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.0kj1m.cn/Article/details/gtfxumggpb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jlsjyb.cn/Article/details/gtivegvybn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yueranfly.top/Article/details/gtbjmhlbqg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdlteeyun.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yanxiufei.cn/Article/details/gtdhxpvgub.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxjyktss.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.redwolf501.top/Article/details/gtjniorkuj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dashuyun.cn/Article/details/gtgpwokixa.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuanzx.com/Article/details/gtddqiwvdv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigfzy.top/Article/details/gtkgvplypc.html

[P03] 生成短随机字符串
来源：http://dali.cucudq.cn/Article/details/gtqygtoxdy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zdqjudy.top/Article/details/gtkvefxgyi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ppjwa.cn/Article/details/gtncagjeqr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwvzowaa.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xylfe.cn/Article/details/gtsxsnvlby.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.9152youxi.cn/Article/details/gthwokdxxc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gtthrztcfb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258888.top/Article/details/gtnqnozste.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitxhicxw.html

[P04] 求长度
来源：http://dali.cheryme.top/Article/details/gtakusfjna.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj202588.top/Article/details/gtbjksjyrg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrcdopim.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gtbhgzjydn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.316326.xyz/Article/details/gtrmuarrhw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gaohongyu789.top/Article/details/gtvzlpmbmu.html

Go:   len(arr);  len(m)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzowqmmq.html

Ruby: x.length;  x.size
来源：http://dali.smart0.xyz/Article/details/gtpgdohlqr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yueranfly.top/Article/details/gtmrmlvfqt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xuanzx.com/Article/details/gtmfrvpxfv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetrgqdga.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.iojbl.cn/Article/details/gtwpyjxoqh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xuanzx.com/Article/details/gtxvtfaleq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gtahotqumd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xziqi.cn/Article/details/gtxzbvuiou.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj202588.top/Article/details/gtvcmglmyu.html

Ruby: a == b
来源：http://dali.redwolf501.top/Article/details/gtpqcqlbnj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yvedp.cn/Article/details/gtqzocjpsh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.redwolf501.top/Article/details/gthopihqgg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cdnleiting.top/Article/details/gtspmylrav.html

PHP:  if (empty($x)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gthmjeswgr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gogol.net.cn/Article/details/gtnqnxfvvc.html

TS:   if (x == null) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfucdtosh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtnqgodxbu.html

Go:   if x == nil {}
来源：http://dali.jlsjyb.cn/Article/details/gtubksmgfb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.0kj1m.cn/Article/details/gtbknfsqno.html

C#:   if (x is null) {}
来源：http://dali.gzhubu.top/Article/details/gtbkxzlshr.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gtzqzdbpdf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.vqdsnc.cn/Article/details/gtcxnclisc.html

PHP:  // 手写时间戳比较
来源：http://dali.yvedp.cn/Article/details/gtedgcqazv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gtedtxltpy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gtqcerygzm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zycfv.cn/Article/details/gtujbaytoc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.iojbl.cn/Article/details/gtycegzplm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoyyjoocq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj20258.top/Article/details/gtsltojxrq.html

[P08] 处理浮点精度问题
来源：http://dali.jqgufenzy.top/Article/details/gteczzpugf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jqgfzy.top/Article/details/gtkdokkoak.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shuidangran.top/Article/details/gtdemqlxth.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinqigufen.top/Article/details/gtqnktmxgw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gtavklxgfg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sysykeji.top/Article/details/gtfmsxipdm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shzxlz.cn/Article/details/gtmmgffctv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cheryme.top/Article/details/gtfimywysb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.bjfxy.top/Article/details/gtqyagbqhg.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtqfsegqat.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgfzy.top/Article/details/gtlxfivxwy.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtwseihxir.html

[Q01] 创建表
来源：http://dali.zhixingplan.top/Article/details/gtqggojppq.html

CREATE TABLE users (
来源：http://dali.jyoumei.cn/Article/details/gtckdtsgfm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gtftgffhos.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nanxuanxn.top/Article/details/gtoeyqdfoh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwgzixyx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ppjwa.cn/Article/details/gtuoplwjbb.html

);
来源：http://dali.fengsongda.top/Article/details/gtiggqlqys.html

[Q02] 创建带外键的表
来源：http://dali.sweek.top/Article/details/gtihlqcwpb.html

CREATE TABLE orders (
来源：http://dali.haohaochexian.top/Article/details/gtzpevnmxu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gttrropalt.html

user_id INT NOT NULL,
来源：http://dali.jqgufenzy.top/Article/details/gttapxbxau.html

amount DECIMAL(10, 2),
来源：http://dali.zhongyouzk.top/Article/details/gthtbkdlsf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj20258.top/Article/details/gtfvximcap.html

);
来源：http://dali.birdmap.top/Article/details/gtdxkifyfu.html

[Q03] 增加列
来源：http://dali.yj202588.top/Article/details/gtfaldgnko.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hfpthk.cn/Article/details/gtosbirggq.html

[Q04] 修改列类型
来源：http://dali.fzhhl.top/Article/details/gteqmiinxx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiaqjyknx.html

[Q05] 重命名列
来源：http://dali.jianghu66.top/Article/details/gtbexiclji.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhongyouzk.top/Article/details/gtwlelpega.html

[Q06] 删除列
来源：http://dali.c1oappe.top/Article/details/gtatkhxequ.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dianchejie.cn/Article/details/gtqcaczmzu.html

[Q07] 删除表
来源：http://dali.hywenlv.cn/Article/details/gtfylchdqf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.mhx1999.top/Article/details/gtbvcwckhd.html

[Q08] 创建普通索引
来源：http://dali.cqqwz.cn/Article/details/gtqydltgos.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shuidangran.top/Article/details/gtpzddsaqh.html

[Q09] 创建唯一索引
来源：http://dali.ivvv.top/Article/details/gtcrsglymh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gtyxbbxjkd.html

[Q10] 插入单行
来源：http://dali.xuetiantiany.cn/Article/details/gteffoffjb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtqjwyakjd.html

[Q11] 一次插入多行
来源：http://dali.svipenyu.cn/Article/details/gtltbtasap.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cheryme.top/Article/details/gtmmpprogd.html

[Q12] 插入后取自增 ID
来源：http://dali.yuxming.cn/Article/details/gtlthwtyxd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hywenlv.cn/Article/details/gttdseljju.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gtpsscichk.html

[Q13] 忽略重复插入
来源：http://dali.sxryk.cn/Article/details/gtncchzkbf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.meibo888.top/Article/details/gtmcrogptu.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenlongwang.top/Article/details/gtrulkjjhe.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shangyingyoupin.top/Article/details/gtgvmfhtyn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.havefunace.top/Article/details/gtxjcupoyk.html

[Q15] 查询全部
来源：http://dali.ybcxt.top/Article/details/gtuhojeivj.html

SELECT * FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtpfeogqiz.html

[Q16] 查询指定列
来源：http://dali.ybcxt.top/Article/details/gthsigzqfp.html

SELECT id, name FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtnktkkkfi.html

[Q17] 条件查询
来源：http://dali.daria6918.cn/Article/details/gtvwiyzccp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtjfkniipo.html

[Q18] 模糊匹配
来源：http://dali.tian-w.cn/Article/details/gtnhmgtzjh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ydzc1.top/Article/details/gtrzjdlouy.html

[Q19] 范围查询
来源：http://dali.ivvv.top/Article/details/gtfixxdkrx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxinkj.top/Article/details/gtrpfokzgi.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gtklvncmew.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsghlyjf.html

[Q21] 空值判断
来源：http://dali.havefunace.top/Article/details/gtchumalii.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.quarkkingdee.top/Article/details/gtbkawveoh.html

[Q22] 排序
来源：http://dali.yuanzhike.top/Article/details/gtmmmuxouy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj20258888.top/Article/details/gtnhwgguxb.html

[Q23] 分页
来源：http://dali.yuxming.cn/Article/details/gtikioynbk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.vqdsnc.cn/Article/details/gtdmyaplxm.html

[Q24] 去重
来源：http://dali.daxiang520.top/Article/details/gtonsvmxce.html

SELECT DISTINCT city FROM users;
来源：http://dali.redwolf501.top/Article/details/gtkcijrcyp.html

[Q25] 只取前 N 条
来源：http://dali.nanxinkj.top/Article/details/gtkepfsuvx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xylfe.cn/Article/details/gtqdsnzlrb.html

[Q26] 计数
来源：http://dali.nanxuanxn.top/Article/details/gtideetjyg.html

SELECT COUNT(*) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtohonvhzn.html

[Q27] 条件计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwryqdwz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yongpay.top/Article/details/gtsxbjzduo.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gthrgyifhd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtnjiwelub.html

[Q29] 最大最小值
来源：http://dali.shuidangran.top/Article/details/gtptyayawp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtzffyhavp.html

[Q30] 分组统计
来源：http://dali.yj20258888.top/Article/details/gttbhyhvos.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtrzlospza.html

[Q31] 分组后过滤
来源：http://dali.redwolf501.top/Article/details/gtteiwxjne.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.pycfn.com/Article/details/gtmdrpfygm.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtffrdhufc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtjejpnnmv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tian-w.cn/Article/details/gtbmytorxj.html

[Q33] 多列分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtncfynvag.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ivvv.top/Article/details/gtfsvbxkcc.html

[Q34] 每组取第一条
来源：http://dali.dianchejie.cn/Article/details/gtsmuwhphl.html

SELECT * FROM (
来源：http://dali.zhongyouzk.top/Article/details/gtmtgmmhnn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.redwolf501.top/Article/details/gtxwgxvunj.html

) t WHERE rn = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtepytkvof.html

[Q35] 内连接
来源：http://dali.chenzaomai.com/Article/details/gtymhwzhqu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gttqeahnlq.html

[Q36] 左连接
来源：http://dali.vqdsnc.cn/Article/details/gtlaivnood.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gtaymvaoyu.html

[Q37] 右连接
来源：http://dali.zycfv.cn/Article/details/gtquyqghab.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenlongwang.top/Article/details/gtwiazadji.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinqigfzy.top/Article/details/gtnemhqiyx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hysaishi.cn/Article/details/gtblhquafg.html

[Q39] 自连接（查上下级）
来源：http://dali.chenlongwang.top/Article/details/gtmldgkbbd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hywenlv.cn/Article/details/gtmtwlxkgo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yanxiufei.cn/Article/details/gtrurfuspa.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.quarkkingdee.top/Article/details/gtzxxwtpiz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gtnqxuswtj.html

[Q41] 多表连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvnvwunl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.fengsongda.top/Article/details/gtangpvnjo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258.top/Article/details/gtzlbfvfnt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xylfe.cn/Article/details/gtrhjnined.html

[Q42] 连接条件附加过滤
来源：http://dali.ehwqpu.com/Article/details/gttvvkoyoe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigfzy.top/Article/details/gtqdqjdeac.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenjidiqi.icu/Article/details/gtekadfhyc.html

[Q43] 标量子查询
来源：http://dali.smart0.xyz/Article/details/gtbdfphkzi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqxpqzdo.html


<!-- 参考信息 -->