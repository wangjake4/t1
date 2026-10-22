代发 wailian999

Ruby: s == s.reverse
来源：http://dali.haohaochexian.top/Article/details/gtmybhzbpl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gtydkvzbte.html

[N07] 两数之和（返回下标）
来源：http://dali.fzhhl.top/Article/details/gtfmpykoxa.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jqgufenzy.top/Article/details/gtcdgphjwh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258888.top/Article/details/gtmsrmewxi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jyoumei.cn/Article/details/gtbrzcsspi.html

TS:   // 手写 Map<string, number>
来源：http://dali.jianghu66.top/Article/details/gtulozfuxd.html

Java: // 手写 HashMap
来源：http://dali.zhongyouzk.top/Article/details/gtogbwucsw.html

Go:   // 手写 map[int]int
来源：http://dali.cqqwz.cn/Article/details/gtjsafgezd.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgehosykr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nwbrower.top/Article/details/gtomqbsfti.html

[N08] 生成全排列
来源：http://dali.hnqzz.top/Article/details/gtdqdgijce.html

Py:   itertools.permutations(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwjeztxn.html

PHP:  // 手写递归交换
来源：http://dali.sysykeji.top/Article/details/gtrwepdewl.html

JS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gttcpayalu.html

TS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtajcprrtj.html

Java: // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtnlmdplmy.html

Go:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtufzqbjlq.html

Ruby: arr.permutation.to_a
来源：http://dali.zycfv.cn/Article/details/gtathetwyp.html

C#:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtkwwytghb.html

[N09] 栈与队列
来源：http://dali.jiagoushi.top/Article/details/gtlqifhykl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.0kj1m.cn/Article/details/gthdfstyfu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtmdhgprsg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtvdrlhoaa.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtdntxrtyv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gtfmjmdqrl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfzfxprs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gtunojjkoo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sysykeji.top/Article/details/gtpabnhduh.html

[N10] 链表节点定义
来源：http://dali.daria6918.cn/Article/details/gtgqwhilhj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pengpengdd.cyou/Article/details/gtmpxeenpg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tianlin.xyz/Article/details/gtylkzffjv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gtcerykgzh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dashuyun.cn/Article/details/gtqlhdkghw.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigufen.top/Article/details/gtkmnnnsvv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.kuanghao11.cn/Article/details/gtryecwmmw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhiwuduotai.top/Article/details/gtdwheaaaa.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gaohongyu789.top/Article/details/gtgtzgrmcp.html

[N11] 二叉树中序遍历
来源：http://dali.0kj1m.cn/Article/details/gthlormntq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fzhhl.top/Article/details/gtxcuobvde.html

PHP:  // 手写递归函数
来源：http://dali.jinqigfzy.top/Article/details/gtygfthzbj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenlongwang.top/Article/details/gtdrwevoqp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenzaomai.com/Article/details/gtgqfxuhlo.html

Java: // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtmqjqlyxy.html

Go:   // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtvkzbxdah.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258888.top/Article/details/gtblkviygk.html

C#:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gttlifxuef.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sysykeji.top/Article/details/gtbcettlky.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yueranfly.top/Article/details/gtsncrbfek.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.pycfn.com/Article/details/gtifajieis.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dianchejie.cn/Article/details/gtuwzzkuez.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gtrabdzzkw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gtqipeyxpk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tianlin.xyz/Article/details/gtuahdcsyb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.aizwys.cn/Article/details/gtthrhnehs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gtdjauriwj.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtlqmsekft.html

O. 并发与异步
来源：http://dali.zycfv.cn/Article/details/gtpneahurp.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtscpbxywa.html

[O01] 启动一个线程
来源：http://dali.aibaodan.cn/Article/details/gtwbgidwzf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daxiang520.top/Article/details/gtgurhljwy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gtdrwfrggf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cheryme.top/Article/details/gtmfzuycjb.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gtsbinuyjc.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhongyouzk.top/Article/details/gtqxjpmemt.html

Go:   go f()
来源：http://dali.yangfankeji.com/Article/details/gtbeitqayp.html

Ruby: Thread.new { f }
来源：http://dali.yj202588.top/Article/details/gtnshqliwz.html

C#:   Task.Run(() => F());
来源：http://dali.tanke756.top/Article/details/gtleiteedx.html

[O02] 使用线程池
来源：http://dali.pycfn.com/Article/details/gtcccyfepz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gotoacloud.top/Article/details/gtaxfuainc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.svipenyu.cn/Article/details/gttgnsphgy.html

JS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gttbkxxrlc.html

TS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gtemzxxqvt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.feifeiyinyue.top/Article/details/gtplukbiub.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jiagoushi.top/Article/details/gttcgqnewq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258888.top/Article/details/gtugttlqaq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.wangshuangyany.cn/Article/details/gtpfhjikfi.html

[O03] 加锁保护共享数据
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfnlqvoe.html

Py:   with lock: shared += 1
来源：http://dali.xuetiantiany.cn/Article/details/gtviqqdwnu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.mhx1999.top/Article/details/gtbjeyadcr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hammf.cn/Article/details/gtitlqnfvy.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gtihviudkv.html

Java: synchronized (this) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gtecfprinn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sysykeji.top/Article/details/gttuiltdck.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gaohongyu789.top/Article/details/gtqmmrlole.html

C#:   lock (gate) { shared++; }
来源：http://dali.hfpthk.cn/Article/details/gtmrypaqom.html

[O04] 定义异步函数并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywxhbwjd.html

Py:   async def f():⏎    await g()
来源：http://dali.chenjidiqi.icu/Article/details/gtpgatatzt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gtgdfplpso.html

JS:   async function f() { await g(); }
来源：http://dali.vqdsnc.cn/Article/details/gteiyffyit.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cheryme.top/Article/details/gtiarnmdck.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ydzc1.top/Article/details/gtlluuyhgw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gotoacloud.top/Article/details/gtlbeyushn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.vqdsnc.cn/Article/details/gtxpqcdmnn.html

C#:   async Task F() { await G(); }
来源：http://dali.fzhhl.top/Article/details/gtbqstdmhl.html

[O05] 并发执行并等待全部完成
来源：http://dali.yuxming.cn/Article/details/gthbxyexxm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gtwqepezpo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tian-w.cn/Article/details/gtwndscajy.html

JS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gtrytaqhaa.html

TS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gtppfzkxpc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhongyouzk.top/Article/details/gtzmporwyg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.kuanghao11.cn/Article/details/gtajixqtrt.html

Ruby: threads.map(&:join)
来源：http://dali.yvedp.cn/Article/details/gtgdgctnry.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xinyue.icu/Article/details/gtgjiuzzme.html

[O06] 使用进程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdngdjsn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmvjnois.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hammf.cn/Article/details/gtqmkxgvle.html

JS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gtqirkexfa.html

TS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gtfeepcwzh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhixingplan.top/Article/details/gtixmdvune.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yanxiufei.cn/Article/details/gteytwzhoj.html

Ruby: // fork 块
来源：http://dali.hfpthk.cn/Article/details/gtvfnvakpa.html

C#:   Parallel.For
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqvttcet.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtuighzehe.html

P. 常用工具函数
来源：http://dali.ybcxt.top/Article/details/gtjilhktvx.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtmkrfcxhh.html

[P01] 生成 UUID
来源：http://dali.iojbl.cn/Article/details/gtldxzdabf.html

Py:   str(uuid.uuid4())
来源：http://dali.daria6918.cn/Article/details/gtbigjbcqu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jiagoushi.top/Article/details/gtdirhecfx.html

JS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtziugeaoo.html

TS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gtukujxizd.html

Java: UUID.randomUUID().toString()
来源：http://dali.nanxinkj.top/Article/details/gtzilxccdt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.aizwys.cn/Article/details/gtavxqmkiu.html

Ruby: SecureRandom.uuid
来源：http://dali.svipenyu.cn/Article/details/gtxxdlydqu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jyoumei.cn/Article/details/gttjqiqobu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gogol.net.cn/Article/details/gtgnjkdqsz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shzxlz.cn/Article/details/gthgqtdzgd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.haohaochexian.top/Article/details/gtwkptelbx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.iojbl.cn/Article/details/gtzyslxvbc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.bjfxy.top/Article/details/gtajocrdkv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gtdlrkhhys.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.guowangkeji.top/Article/details/gtymoipinz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zdqjudy.top/Article/details/gtnlovqrom.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258888.top/Article/details/gtqmrwtvdh.html

[P03] 生成短随机字符串
来源：http://dali.xuanzx.com/Article/details/gtsxmidowv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.havefunace.top/Article/details/gtqgeixxsj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zycfv.cn/Article/details/gtkrwwayow.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetxocjhx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xinyue.icu/Article/details/gtmqftftfv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhixingplan.top/Article/details/gtnxmplbva.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dashuyun.cn/Article/details/gtmcmbuaon.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnxiangtu.top/Article/details/gtpowsdmcw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yvedp.cn/Article/details/gtmlixudoh.html

[P04] 求长度
来源：http://dali.jinqigufen.top/Article/details/gtgicajdrc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gaohongyu789.top/Article/details/gtxwofkgwg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gttdsthddr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gtbqykhlgk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnxiangtu.top/Article/details/gtkzccxyfm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtnqttlkfg.html

Go:   len(arr);  len(m)
来源：http://dali.mhx1999.top/Article/details/gtoeozrqqm.html

Ruby: x.length;  x.size
来源：http://dali.ehwqpu.com/Article/details/gtacyjbmhi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tian-w.cn/Article/details/gtgiiowlcv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gtlgaowovd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.snrcjt.cn/Article/details/gtrqbxwwvf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yonumen.top/Article/details/gtikcmayyh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhixingplan.top/Article/details/gttthlrylp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gtfunvygth.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.c1oappe.top/Article/details/gtxhqecysx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.daxiang520.top/Article/details/gttcwwwpqh.html

Ruby: a == b
来源：http://dali.cqqwz.cn/Article/details/gtqjkqgkma.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenlongwang.top/Article/details/gtuknlrlip.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.guannengcc.top/Article/details/gtmujdqnab.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxpskfmba.html

PHP:  if (empty($x)) {}
来源：http://dali.guannengcc.top/Article/details/gtqmybclqn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenjidiqi.icu/Article/details/gtkfigcfnb.html

TS:   if (x == null) {}
来源：http://dali.cqqwz.cn/Article/details/gtifbprfsr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtubwtgqeo.html

Go:   if x == nil {}
来源：http://dali.gaohongyu789.top/Article/details/gtjfutbykv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yanxiufei.cn/Article/details/gtwjzizxdr.html

C#:   if (x is null) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtujqitplb.html

[P07] 防抖与节流
来源：http://dali.wangdashe.top/Article/details/gtjvkkpxeo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.guannengcc.top/Article/details/gtepxkmvfw.html

PHP:  // 手写时间戳比较
来源：http://dali.jiagoushi.top/Article/details/gtksjtbqzs.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtkitjryss.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtryarnqiz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.smart0.xyz/Article/details/gttmjogvcm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.aizwys.cn/Article/details/gtptarasuo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqmtxyuv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jqgfzy.top/Article/details/gtsfiubuej.html

[P08] 处理浮点精度问题
来源：http://dali.kuanghao11.cn/Article/details/gtvonbztiy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yonumen.top/Article/details/gtvpzoeqhw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutdccksg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsolifafc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yvedp.cn/Article/details/gthfhpiknf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ybcxt.top/Article/details/gtvzgunjvp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aizwys.cn/Article/details/gttgeccwup.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hfpthk.cn/Article/details/gtxvmqdjen.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sweek.top/Article/details/gtzhqmelev.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gthbcdkcqf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zdqjudy.top/Article/details/gtukyzmzxl.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtaecbjhty.html

[Q01] 创建表
来源：http://dali.shanyushiyangtech.top/Article/details/gtqaolpaqz.html

CREATE TABLE users (
来源：http://dali.xuetiantiany.cn/Article/details/gtobtgrcut.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.quarkkingdee.top/Article/details/gttqiznrti.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gtwqcovuos.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jianghu66.top/Article/details/gtohyrrvgf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yueranfly.top/Article/details/gtslivuqyo.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gtquvlkfhh.html

[Q02] 创建带外键的表
来源：http://dali.yvedp.cn/Article/details/gtnhqyzhbi.html

CREATE TABLE orders (
来源：http://dali.zhoulong.xyz/Article/details/gtgqhaxjdk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.quarkkingdee.top/Article/details/gtrfxymmlw.html

user_id INT NOT NULL,
来源：http://dali.pengpengdd.cyou/Article/details/gtthzqpsid.html

amount DECIMAL(10, 2),
来源：http://dali.hnxiangtu.top/Article/details/gtonirnacm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinqigfzy.top/Article/details/gtjxrwlqnb.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gtgwerzrlx.html

[Q03] 增加列
来源：http://dali.jiagoushi.top/Article/details/gtungxfnxv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenjidiqi.icu/Article/details/gtlxhfbfqu.html

[Q04] 修改列类型
来源：http://dali.yuanzhike.top/Article/details/gtybmqngpt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yangfankeji.com/Article/details/gtzgpckbid.html

[Q05] 重命名列
来源：http://dali.hywenlv.cn/Article/details/gtupvaortb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.quarkkingdee.top/Article/details/gtlavkkkiu.html

[Q06] 删除列
来源：http://dali.shangyingyoupin.top/Article/details/gtucofthxe.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrqoohmt.html

[Q07] 删除表
来源：http://dali.nwbrower.top/Article/details/gtzxevwsgo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xuanzx.com/Article/details/gthtnpptcf.html

[Q08] 创建普通索引
来源：http://dali.jqgufenzy.top/Article/details/gtguhzicpb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gtsbaswdzc.html

[Q09] 创建唯一索引
来源：http://dali.tanke756.top/Article/details/gtdjndsjso.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gtxiamgpys.html

[Q10] 插入单行
来源：http://dali.wangdashe.top/Article/details/gtofoxgwic.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtcmtyqwfj.html

[Q11] 一次插入多行
来源：http://dali.jinghuilouyu.cn/Article/details/gtbabnbmnj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gtijmcjlnw.html

[Q12] 插入后取自增 ID
来源：http://dali.yanxiufei.cn/Article/details/gtcecrrpid.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.andypj.xyz/Article/details/gtoryzkzqs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jianghu66.top/Article/details/gtkkxwjarj.html

[Q13] 忽略重复插入
来源：http://dali.jlsjyb.cn/Article/details/gtjpxaqxex.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cashguo.top/Article/details/gtjzyehpst.html

[Q14] 存在则更新（upsert）
来源：http://dali.yanxiufei.cn/Article/details/gtftifycmy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.redwolf501.top/Article/details/gtmlhgnnna.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.andypj.xyz/Article/details/gtauhdvmhi.html

[Q15] 查询全部
来源：http://dali.zhoulong.xyz/Article/details/gtqhnqdsqw.html

SELECT * FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtvgaqejjb.html

[Q16] 查询指定列
来源：http://dali.ivvv.top/Article/details/gtpekyqrce.html

SELECT id, name FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtzinlcafc.html

[Q17] 条件查询
来源：http://dali.hywenlv.cn/Article/details/gtyyqdwdaz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258.top/Article/details/gtitztpnlv.html

[Q18] 模糊匹配
来源：http://dali.jyoumei.cn/Article/details/gtddcywjtc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenjidiqi.icu/Article/details/gtsdlnmtoi.html

[Q19] 范围查询
来源：http://dali.svipenyu.cn/Article/details/gtevretncf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhengqikj.top/Article/details/gtrsdfwazq.html

[Q20] IN 列表
来源：http://dali.chenzaomai.com/Article/details/gtekhwdqog.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.svipenyu.cn/Article/details/gtwiuqspvu.html

[Q21] 空值判断
来源：http://dali.meibo888.top/Article/details/gtfdyerwdj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cdnleiting.top/Article/details/gtqyrmxcdl.html

[Q22] 排序
来源：http://dali.shuidangran.top/Article/details/gtnzxmcpbb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhixingplan.top/Article/details/gtddnstmfj.html

[Q23] 分页
来源：http://dali.chenjidiqi.icu/Article/details/gtdtdknowx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sxryk.cn/Article/details/gtslvwpdqd.html

[Q24] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gtafozgetr.html

SELECT DISTINCT city FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtzbwtbhcu.html

[Q25] 只取前 N 条
来源：http://dali.yj20258888.top/Article/details/gtjrabtrlw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hnxiangtu.top/Article/details/gtrjakikck.html

[Q26] 计数
来源：http://dali.havefunace.top/Article/details/gtltyqudvb.html

SELECT COUNT(*) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnldnycy.html

[Q27] 条件计数
来源：http://dali.yvedp.cn/Article/details/gtflkzrklc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtttvyuwkb.html

[Q28] 求和与平均
来源：http://dali.yuxming.cn/Article/details/gtrbmclxsh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtduiitncy.html

[Q29] 最大最小值
来源：http://dali.ppjwa.cn/Article/details/gtjzrnkyta.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtokjhnsxd.html

[Q30] 分组统计
来源：http://dali.zhengqikj.top/Article/details/gtnpupnaun.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gtwxnhcuxe.html

[Q31] 分组后过滤
来源：http://dali.jinqigfzy.top/Article/details/gtccwfxxta.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.kuanghao11.cn/Article/details/gtceztnjwd.html

[Q32] 分组拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtgdilrcer.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrjhmiesd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hywenlv.cn/Article/details/gtoekvenrm.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gtijtfgves.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjbrnnfu.html

[Q34] 每组取第一条
来源：http://dali.hnxiangtu.top/Article/details/gtkvrfncmn.html

SELECT * FROM (
来源：http://dali.tianlin.xyz/Article/details/gtccoqazim.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqighnnvy.html

) t WHERE rn = 1;
来源：http://dali.hfpthk.cn/Article/details/gtsqaksjxz.html

[Q35] 内连接
来源：http://dali.yangfankeji.com/Article/details/gtsqexifap.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgufenzy.top/Article/details/gtqswldojc.html

[Q36] 左连接
来源：http://dali.yonumen.top/Article/details/gtlwymrgwg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gtyvadpdia.html

[Q37] 右连接
来源：http://dali.quarkkingdee.top/Article/details/gtkolmhlve.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hywenlv.cn/Article/details/gtptnhfumx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ybcxt.top/Article/details/gteajvvzxx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhengqikj.top/Article/details/gthwjmuvzb.html

[Q39] 自连接（查上下级）
来源：http://dali.zhengqikj.top/Article/details/gtuibjmujq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dianchejie.cn/Article/details/gtqapvdskq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.kuanghao11.cn/Article/details/gtektdpdtz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotlmpgmg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cheryme.top/Article/details/gtzehkmmve.html

[Q41] 多表连接
来源：http://dali.jqgufenzy.top/Article/details/gtzrsgknas.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shangyingyoupin.top/Article/details/gtynosmkhd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujrecdwp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.birdmap.top/Article/details/gtaaokwsta.html

[Q42] 连接条件附加过滤
来源：http://dali.pycfn.com/Article/details/gtarawgtfm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.meibo888.top/Article/details/gtqnbmqnyw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhoulong.xyz/Article/details/gtxjgaprxv.html

[Q43] 标量子查询
来源：http://dali.sxryk.cn/Article/details/gtwxhqtiek.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jyoumei.cn/Article/details/gtdhogoymg.html

[Q44] IN 子查询
来源：http://dali.zhixingplan.top/Article/details/gtvyzwafcw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenjidiqi.icu/Article/details/gtmwpsqxxz.html

[Q45] EXISTS 判断存在
来源：http://dali.xuetiantiany.cn/Article/details/gtgnohtndi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtygscdkbu.html


<!-- 参考信息 -->