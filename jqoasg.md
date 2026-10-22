代发 wailian999

Ruby: s == s.reverse
来源：http://dali.gzhubu.top/Article/details/gtvidtbkqx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gtxshhidcg.html

[N07] 两数之和（返回下标）
来源：http://dali.zhoulong.xyz/Article/details/gtnhkcjoaf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.316326.xyz/Article/details/gtqailszev.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yueranfly.top/Article/details/gtybrtpkjm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258888.top/Article/details/gtdlqhvpsn.html

TS:   // 手写 Map<string, number>
来源：http://dali.hongshengwenyu.top/Article/details/gtuyavlrni.html

Java: // 手写 HashMap
来源：http://dali.ivvv.top/Article/details/gtprdlqhzr.html

Go:   // 手写 map[int]int
来源：http://dali.haohaochexian.top/Article/details/gtsfrrjwiv.html

Ruby: // 手写 Hash
来源：http://dali.iojbl.cn/Article/details/gtrynxnnbq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tianlin.xyz/Article/details/gtdxwwyfts.html

[N08] 生成全排列
来源：http://dali.xylfe.cn/Article/details/gtkgxfcvnc.html

Py:   itertools.permutations(arr)
来源：http://dali.daxiang520.top/Article/details/gtkpraedrj.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangtech.top/Article/details/gthvxptsrk.html

JS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtvfvvmugm.html

TS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtjghnrgho.html

Java: // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtkgiexknn.html

Go:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtdymietzv.html

Ruby: arr.permutation.to_a
来源：http://dali.xinyue.icu/Article/details/gtbsgigmzi.html

C#:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtniytloah.html

[N09] 栈与队列
来源：http://dali.sweek.top/Article/details/gtojjkatoh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gzhubu.top/Article/details/gtwjrszyou.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtkgkgkbix.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.c1oappe.top/Article/details/gtiivxdsnq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuanzx.com/Article/details/gtpsovkvnl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuxming.cn/Article/details/gtczcwgmdv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnxiangtu.top/Article/details/gtnqhoifyn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gttjrjzvkv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dashuyun.cn/Article/details/gtgbwhluth.html

[N10] 链表节点定义
来源：http://dali.xuanzx.com/Article/details/gtltbluxmh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.vqdsnc.cn/Article/details/gtdqzzszhi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hfpthk.cn/Article/details/gtpvtrnain.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cdnleiting.top/Article/details/gtvwguswxd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yongpay.top/Article/details/gtwqralggv.html

Java: class Node { int v; Node next; }
来源：http://dali.yj202588.top/Article/details/gtctmdfewq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shuidangran.top/Article/details/gtmtrrvlth.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daria6918.cn/Article/details/gtwnflucoa.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinqigfzy.top/Article/details/gtomhiffir.html

[N11] 二叉树中序遍历
来源：http://dali.xylfe.cn/Article/details/gtncsakmcv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigfzy.top/Article/details/gthpbffmvc.html

PHP:  // 手写递归函数
来源：http://dali.gogol.net.cn/Article/details/gtotuavbjm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gtmkhusvok.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangshuangyany.cn/Article/details/gtikvwvosp.html

Java: // 手写递归
来源：http://dali.fzhhl.top/Article/details/gtiumehkjy.html

Go:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gtmabrhrvy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhiwuduotai.top/Article/details/gtwjjnixzu.html

C#:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gtohovzemw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.redwolf501.top/Article/details/gttjmmgdsl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jianghu66.top/Article/details/gtgkmeqynz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxuanxn.top/Article/details/gtpavldbkx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gtcsxkixrn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgoawczui.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gtiirgteyv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pycfn.com/Article/details/gtrowwfswz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gtqqkssejs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.smart0.xyz/Article/details/gtpoywrqrn.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtswmcfdxm.html

O. 并发与异步
来源：http://dali.feifeiyinyue.top/Article/details/gtrkvczgbv.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtqadpzbmg.html

[O01] 启动一个线程
来源：http://dali.meibo888.top/Article/details/gtiwfxkyxg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jianghu66.top/Article/details/gthsdtkdfa.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaovmvlew.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.aizwys.cn/Article/details/gthdzokbfr.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gtinwzrcia.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258888.top/Article/details/gtpvvgqljm.html

Go:   go f()
来源：http://dali.cashguo.top/Article/details/gtqhjatcoh.html

Ruby: Thread.new { f }
来源：http://dali.chenzaomai.com/Article/details/gtjfqukvrj.html

C#:   Task.Run(() => F());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwbuevgr.html

[O02] 使用线程池
来源：http://dali.sysykeji.top/Article/details/gthrcilbdf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtczrkekjm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yonumen.top/Article/details/gtzpthjqij.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbbuufzk.html

TS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gtlleiewtq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.bjfxy.top/Article/details/gtokeasydw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daxiang520.top/Article/details/gtvtbhqsak.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yvedp.cn/Article/details/gtufuhmiyu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jiagoushi.top/Article/details/gtcjomowcn.html

[O03] 加锁保护共享数据
来源：http://dali.birdmap.top/Article/details/gtsemaxzsl.html

Py:   with lock: shared += 1
来源：http://dali.tian-w.cn/Article/details/gtiedihfza.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cdnleiting.top/Article/details/gtmxokihnp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhoulong.xyz/Article/details/gtcgmshxdf.html

TS:   // 同 JS
来源：http://dali.iojbl.cn/Article/details/gttcpqxpzv.html

Java: synchronized (this) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gtmrgepfxg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.aizwys.cn/Article/details/gticxbsijg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenlongwang.top/Article/details/gtdvmkuqjr.html

C#:   lock (gate) { shared++; }
来源：http://dali.ehwqpu.com/Article/details/gtbufezufi.html

[O04] 定义异步函数并等待
来源：http://dali.cucudq.cn/Article/details/gtyhtvzvgr.html

Py:   async def f():⏎    await g()
来源：http://dali.sxryk.cn/Article/details/gtuaiwfnzb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangshuangyany.cn/Article/details/gtiuasqgyi.html

JS:   async function f() { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gtgafqbgro.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmqydmmh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sxryk.cn/Article/details/gtiucgpvnx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tian-w.cn/Article/details/gtqxfunffg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.haohaochexian.top/Article/details/gtqakfqayq.html

C#:   async Task F() { await G(); }
来源：http://dali.xziqi.cn/Article/details/gtddghepmv.html

[O05] 并发执行并等待全部完成
来源：http://dali.hfpthk.cn/Article/details/gtoklwsnvq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daria6918.cn/Article/details/gtfmsibyvc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fengsongda.top/Article/details/gtlytwngnk.html

JS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gtxlixkdnz.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtdbszverv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xziqi.cn/Article/details/gtjqxrtqvf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhongyouzk.top/Article/details/gtukbndwio.html

Ruby: threads.map(&:join)
来源：http://dali.yueranfly.top/Article/details/gtksfmouao.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jlsjyb.cn/Article/details/gtiltlbmdj.html

[O06] 使用进程池
来源：http://dali.ppjwa.cn/Article/details/gtrrmvhkpk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cucudq.cn/Article/details/gtzxcqkkhe.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nanxuanxn.top/Article/details/gtchdpfrjk.html

JS:   // child_process / cluster 模块
来源：http://dali.yj20258.top/Article/details/gtecpudpmj.html

TS:   // child_process / cluster 模块
来源：http://dali.cdnleiting.top/Article/details/gtyvglivml.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sweek.top/Article/details/gtxrihtdyl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ybcxt.top/Article/details/gtbinrmzyk.html

Ruby: // fork 块
来源：http://dali.jinqigufen.top/Article/details/gtvohyxsvm.html

C#:   Parallel.For
来源：http://dali.xuetiantiany.cn/Article/details/gtucdjosun.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtauflazqp.html

P. 常用工具函数
来源：http://dali.wangshuangyany.cn/Article/details/gtapaurqci.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtctkfwvbx.html

[P01] 生成 UUID
来源：http://dali.yuanzhike.top/Article/details/gteuqlzgsj.html

Py:   str(uuid.uuid4())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidyoarpn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xziqi.cn/Article/details/gtxgmrxawr.html

JS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtjtzetarz.html

TS:   crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gtcchikvvf.html

Java: UUID.randomUUID().toString()
来源：http://dali.guannengcc.top/Article/details/gttwtaahea.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gtsiikrhtg.html

Ruby: SecureRandom.uuid
来源：http://dali.chenzaomai.com/Article/details/gttfashrfw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.havefunace.top/Article/details/gtebjxpkxj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.snrcjt.cn/Article/details/gtckdpuitd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cqqwz.cn/Article/details/gtvybeguxz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgpylczu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tian-w.cn/Article/details/gtngrmggxu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shuidangran.top/Article/details/gtrpnkaiyn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtiyjxlefd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hnxiangtu.top/Article/details/gtddykbbzs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ppjwa.cn/Article/details/gtmedsmbgo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hammf.cn/Article/details/gtkovlltcl.html

[P03] 生成短随机字符串
来源：http://dali.aizwys.cn/Article/details/gtapfmkqsh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nwbrower.top/Article/details/gtbbuvuywe.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnqzz.top/Article/details/gtatprbgjk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gtqmhofmsk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gtwuvgjmkt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sysykeji.top/Article/details/gtnrfqsbzb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nwbrower.top/Article/details/gtoyonwkiu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnqzz.top/Article/details/gtfjkneofk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jiagoushi.top/Article/details/gtalaihqiz.html

[P04] 求长度
来源：http://dali.hongshengwenyu.top/Article/details/gtrllyijad.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tanke756.top/Article/details/gtqmjnpwyf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtfuudmmjm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gtychlrjln.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yongpay.top/Article/details/gtqfnwobuo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258888.top/Article/details/gttqyobvuv.html

Go:   len(arr);  len(m)
来源：http://dali.xuanzx.com/Article/details/gtclprefit.html

Ruby: x.length;  x.size
来源：http://dali.birdmap.top/Article/details/gtlfbttzth.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gtnllyveal.html

[P05] 判断两个对象内容是否相等
来源：http://dali.c1oappe.top/Article/details/gtjuksewlg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigufen.top/Article/details/gtdexxoyod.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ybcxt.top/Article/details/gtlvhosysd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fengsongda.top/Article/details/gtvdzwsdhq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yueranfly.top/Article/details/gtuuirkene.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nanxuanxn.top/Article/details/gtnbzwevto.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sxryk.cn/Article/details/gtsfchdqap.html

Ruby: a == b
来源：http://dali.nanxuanxn.top/Article/details/gtrmkvowbz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daria6918.cn/Article/details/gtdqlnwemi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jlsjyb.cn/Article/details/gtvwgqyctf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yangfankeji.com/Article/details/gtmssnmgpu.html

PHP:  if (empty($x)) {}
来源：http://dali.jlsjyb.cn/Article/details/gtaiubtsom.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dianchejie.cn/Article/details/gtwpfywliq.html

TS:   if (x == null) {}
来源：http://dali.jiagoushi.top/Article/details/gtlobccmir.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nanxinkj.top/Article/details/gtopcojujg.html

Go:   if x == nil {}
来源：http://dali.daxiang520.top/Article/details/gtqpbfyemy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tanke756.top/Article/details/gtkrmrbztw.html

C#:   if (x is null) {}
来源：http://dali.redwolf501.top/Article/details/gtsqkezudy.html

[P07] 防抖与节流
来源：http://dali.pycfn.com/Article/details/gtheuozbyk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aibaodan.cn/Article/details/gtbhrtnwmz.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gttgyfxykl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gtwwqecwzm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gtbwlklhbq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zdqjudy.top/Article/details/gtykotispl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tanke756.top/Article/details/gtmpraqqjl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jiagoushi.top/Article/details/gtprxedrhe.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.9152youxi.cn/Article/details/gtbccpyfll.html

[P08] 处理浮点精度问题
来源：http://dali.yangfankeji.com/Article/details/gtpvhbgrcc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jqgfzy.top/Article/details/gtscspgxpq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhoulong.xyz/Article/details/gtppvflnrn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.quarkkingdee.top/Article/details/gtdaaliaxi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yj202588.top/Article/details/gtueozyivv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.birdmap.top/Article/details/gtchoffhen.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yangfankeji.com/Article/details/gtxgwkbcqw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.guannengcc.top/Article/details/gthzycmfyq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sweek.top/Article/details/gthgwmqpbe.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtbfzeufje.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhixingplan.top/Article/details/gtdrgydeab.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gttsejulla.html

[Q01] 创建表
来源：http://dali.shangyingyoupin.top/Article/details/gtpiefevoo.html

CREATE TABLE users (
来源：http://dali.c1oappe.top/Article/details/gtsfvgjthf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gtmayjttwl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jlsjyb.cn/Article/details/gtyntcsiso.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cdnleiting.top/Article/details/gttezgzpvx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.fzhhl.top/Article/details/gthyhbdqaz.html

);
来源：http://dali.wangdashe.top/Article/details/gtbrlsvdie.html

[Q02] 创建带外键的表
来源：http://dali.snrcjt.cn/Article/details/gtiohgwdvv.html

CREATE TABLE orders (
来源：http://dali.hnqzz.top/Article/details/gtimylmfii.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gtfhxasnlr.html

user_id INT NOT NULL,
来源：http://dali.haohaochexian.top/Article/details/gtoianxneb.html

amount DECIMAL(10, 2),
来源：http://dali.yueranfly.top/Article/details/gtvdveohoo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj20258888.top/Article/details/gttlbobbec.html

);
来源：http://dali.yuxming.cn/Article/details/gtpskercns.html

[Q03] 增加列
来源：http://dali.hysaishi.cn/Article/details/gtqdkbnwuz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yanxiufei.cn/Article/details/gtqbigimkn.html

[Q04] 修改列类型
来源：http://dali.quarkkingdee.top/Article/details/gtnwivqcps.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pycfn.com/Article/details/gtzwlvmjzm.html

[Q05] 重命名列
来源：http://dali.hysaishi.cn/Article/details/gtxzngtzrg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.mhx1999.top/Article/details/gtyzaisukj.html

[Q06] 删除列
来源：http://dali.redwolf501.top/Article/details/gtrnodmrmm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hfpthk.cn/Article/details/gtvmazxknz.html

[Q07] 删除表
来源：http://dali.xylfe.cn/Article/details/gtyqwxqdhc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinqigufen.top/Article/details/gtevxnghcg.html

[Q08] 创建普通索引
来源：http://dali.jiagoushi.top/Article/details/gtuqeflyyd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sxryk.cn/Article/details/gtezowjboi.html

[Q09] 创建唯一索引
来源：http://dali.zdqjudy.top/Article/details/gtdspaqcfa.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gtpdlekdyl.html

[Q10] 插入单行
来源：http://dali.birdmap.top/Article/details/gttdfyjmrc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tanke756.top/Article/details/gtpbortwpn.html

[Q11] 一次插入多行
来源：http://dali.jyoumei.cn/Article/details/gtxqhixvst.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tianlin.xyz/Article/details/gtatoklqcm.html

[Q12] 插入后取自增 ID
来源：http://dali.dianchejie.cn/Article/details/gtzdkslaod.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gtbgybgcie.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nwbrower.top/Article/details/gtldcpjyxq.html

[Q13] 忽略重复插入
来源：http://dali.gotoacloud.top/Article/details/gtrtwyyjow.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xziqi.cn/Article/details/gtordnzftw.html

[Q14] 存在则更新（upsert）
来源：http://dali.shzxlz.cn/Article/details/gttrvsrcwu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.svipenyu.cn/Article/details/gtcgnidvys.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjamgbdt.html

[Q15] 查询全部
来源：http://dali.ivvv.top/Article/details/gtbhqyuznx.html

SELECT * FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtusyxfksk.html

[Q16] 查询指定列
来源：http://dali.dianchejie.cn/Article/details/gtnvffykdp.html

SELECT id, name FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtpswhgigo.html

[Q17] 条件查询
来源：http://dali.jianghu66.top/Article/details/gtovrtpkyr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenzaomai.com/Article/details/gtfzestxjj.html

[Q18] 模糊匹配
来源：http://dali.chenlongwang.top/Article/details/gtqvuhmcpq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.aibaodan.cn/Article/details/gtebzdqbar.html

[Q19] 范围查询
来源：http://dali.sysykeji.top/Article/details/gttcccdqsp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhiwuduotai.top/Article/details/gtdrwxpwdo.html

[Q20] IN 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtllejnifm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yongpay.top/Article/details/gtsvobmqkb.html

[Q21] 空值判断
来源：http://dali.kuanghao11.cn/Article/details/gtlldusnoh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yongpay.top/Article/details/gtaguvwogr.html

[Q22] 排序
来源：http://dali.yangfankeji.com/Article/details/gtseszsncq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xziqi.cn/Article/details/gtqvrozzin.html

[Q23] 分页
来源：http://dali.shzxlz.cn/Article/details/gtzoaqewqi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yvedp.cn/Article/details/gtfaeaxdql.html

[Q24] 去重
来源：http://dali.kuanghao11.cn/Article/details/gtasfjmxlv.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtsiifaqrp.html

[Q25] 只取前 N 条
来源：http://dali.jinqigufen.top/Article/details/gtzxaetmwz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cqqwz.cn/Article/details/gtcxgpipbe.html

[Q26] 计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfuddwsbm.html

SELECT COUNT(*) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtifrjsdwy.html

[Q27] 条件计数
来源：http://dali.gaohongyu789.top/Article/details/gtdghxqmom.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmqvwbvw.html

[Q28] 求和与平均
来源：http://dali.gotoacloud.top/Article/details/gtjlpqvcwf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cheryme.top/Article/details/gtdqxltpdk.html

[Q29] 最大最小值
来源：http://dali.xylfe.cn/Article/details/gtufisqnfo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoabjouon.html

[Q30] 分组统计
来源：http://dali.hfpthk.cn/Article/details/gtpwqlpino.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtxueuqone.html

[Q31] 分组后过滤
来源：http://dali.zycfv.cn/Article/details/gtdhchbhpe.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.mhx1999.top/Article/details/gtxhigktzp.html

[Q32] 分组拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgoqodsja.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gtkmnihxkt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.fzhhl.top/Article/details/gtmnstsexu.html

[Q33] 多列分组
来源：http://dali.pengpengdd.cyou/Article/details/gttcxfzpcs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.c1oappe.top/Article/details/gttkgadixi.html

[Q34] 每组取第一条
来源：http://dali.yvedp.cn/Article/details/gtrxeidxgb.html

SELECT * FROM (
来源：http://dali.guannengcc.top/Article/details/gtechmaxjj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pycfn.com/Article/details/gtzmeykdxu.html

) t WHERE rn = 1;
来源：http://dali.aibaodan.cn/Article/details/gtiyyclwok.html

[Q35] 内连接
来源：http://dali.shangyingyoupin.top/Article/details/gtkzvpjlis.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gtnozxrjpt.html

[Q36] 左连接
来源：http://dali.mhx1999.top/Article/details/gtgxklxtdi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jyoumei.cn/Article/details/gtprbnjsui.html

[Q37] 右连接
来源：http://dali.nanxuanxn.top/Article/details/gttnpocsmv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hammf.cn/Article/details/gtpnqmrqwg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hysaishi.cn/Article/details/gtgmpqnewk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinqigufen.top/Article/details/gtdnkoomeq.html

[Q39] 自连接（查上下级）
来源：http://dali.jqgfzy.top/Article/details/gthqqzsvll.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ybcxt.top/Article/details/gtkvgmrdvc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yangfankeji.com/Article/details/gtyrvkndhj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj202588.top/Article/details/gtxybnnzod.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xziqi.cn/Article/details/gtvbhemohk.html

[Q41] 多表连接
来源：http://dali.kuanghao11.cn/Article/details/gtmarxldgu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sweek.top/Article/details/gtgveavwzj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tanke756.top/Article/details/gtruhmpbwc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinqigfzy.top/Article/details/gtpvplihhj.html

[Q42] 连接条件附加过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtpcrnzntk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yongpay.top/Article/details/gtvvpvndhh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.birdmap.top/Article/details/gtixrooszn.html

[Q43] 标量子查询
来源：http://dali.daria6918.cn/Article/details/gtkzxxeayd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgufenzy.top/Article/details/gtmnagtssl.html

[Q44] IN 子查询
来源：http://dali.hfpthk.cn/Article/details/gtdpqupkci.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.havefunace.top/Article/details/gtdayzazac.html

[Q45] EXISTS 判断存在
来源：http://dali.nwbrower.top/Article/details/gtwcsqsljs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hammf.cn/Article/details/gtywnyijpg.html


<!-- 参考信息 -->