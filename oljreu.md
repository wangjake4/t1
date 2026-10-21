代发 wailian999

JS:   s === [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtypngsasr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtqoaqtfgi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jiagoushi.top/Article/details/gtwopzkmmb.html

Go:   // 双指针从两端比较
来源：http://dali.jinqigufen.top/Article/details/gtwegzxhfm.html

Ruby: s == s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gtxveyfkup.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gtpmvzbmik.html

[N07] 两数之和（返回下标）
来源：http://dali.zdqjudy.top/Article/details/gtlszguujh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hysaishi.cn/Article/details/gtnriqvrqa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cheryme.top/Article/details/gtuvhsvfzt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaueabvej.html

TS:   // 手写 Map<string, number>
来源：http://dali.pengpengdd.cyou/Article/details/gtvrchjmts.html

Java: // 手写 HashMap
来源：http://dali.wangdashe.top/Article/details/gtsclnxchq.html

Go:   // 手写 map[int]int
来源：http://dali.9152youxi.cn/Article/details/gtnwovzyeq.html

Ruby: // 手写 Hash
来源：http://dali.0kj1m.cn/Article/details/gtxgkzxogo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.vqdsnc.cn/Article/details/gtajcsdzku.html

[N08] 生成全排列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlqtocrl.html

Py:   itertools.permutations(arr)
来源：http://dali.chenlongwang.top/Article/details/gtjhpekdbw.html

PHP:  // 手写递归交换
来源：http://dali.gzhubu.top/Article/details/gtjbrcqegz.html

JS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtfncrsnjs.html

TS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtzbbzoobe.html

Java: // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtikbytqes.html

Go:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtqnjbmfzd.html

Ruby: arr.permutation.to_a
来源：http://dali.cheryme.top/Article/details/gtxjlvcdbm.html

C#:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtybgzhhsc.html

[N09] 栈与队列
来源：http://dali.jinqigufen.top/Article/details/gtmvbxzbad.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmlqkgxx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.316326.xyz/Article/details/gtmpujyxzv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sysykeji.top/Article/details/gtrlskqsnw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xinyue.icu/Article/details/gtynmxqtax.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenzaomai.com/Article/details/gtmqpgzwyo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jqgfzy.top/Article/details/gtdmwwkggv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gtkuvtfzby.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkwfrtig.html

[N10] 链表节点定义
来源：http://dali.zhoulong.xyz/Article/details/gtfkdqzsas.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigfzy.top/Article/details/gtiorftxdo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zdqjudy.top/Article/details/gtwglomahv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gogol.net.cn/Article/details/gtgqytcntc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sysykeji.top/Article/details/gtpaqvomzi.html

Java: class Node { int v; Node next; }
来源：http://dali.sweek.top/Article/details/gttfvisoio.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yvedp.cn/Article/details/gtnqahgowg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.fzhhl.top/Article/details/gtardrezvm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.wangshuangyany.cn/Article/details/gtydvokmts.html

[N11] 二叉树中序遍历
来源：http://dali.yj20258.top/Article/details/gtjyjcmdhd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsriylvdi.html

PHP:  // 手写递归函数
来源：http://dali.zhengqikj.top/Article/details/gtkxnjlfdk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fengsongda.top/Article/details/gtrwrbcytb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gtthbjcvye.html

Java: // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gtjeprwolj.html

Go:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gtiyiiuysq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sysykeji.top/Article/details/gtwzncikxt.html

C#:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtutoaydkg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tianlin.xyz/Article/details/gtnqsdbgvz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cqqwz.cn/Article/details/gtpwvoyzza.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yongpay.top/Article/details/gtceuumwbo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcglmnrw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.mhx1999.top/Article/details/gtvoftupol.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gtzinsfkcr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gaohongyu789.top/Article/details/gtdvlwjqdd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jiagoushi.top/Article/details/gtfolowwxg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gtppzmozmb.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtshxpyayr.html

O. 并发与异步
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjhtaqnm.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtjybycjwq.html

[O01] 启动一个线程
来源：http://dali.xinyue.icu/Article/details/gtimyknvcm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yj202588.top/Article/details/gtyggkitgo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hongshengwenyu.top/Article/details/gtgptzqnwj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gotoacloud.top/Article/details/gtpijltxpb.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gtmbjopdvv.html

Java: new Thread(() -> f()).start()
来源：http://dali.nanxinkj.top/Article/details/gtagwwolqq.html

Go:   go f()
来源：http://dali.pycfn.com/Article/details/gtpvixogph.html

Ruby: Thread.new { f }
来源：http://dali.andypj.xyz/Article/details/gtsouusmlw.html

C#:   Task.Run(() => F());
来源：http://dali.meibo888.top/Article/details/gtjymzjvfh.html

[O02] 使用线程池
来源：http://dali.yongpay.top/Article/details/gtfrgcizwh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zdqjudy.top/Article/details/gtoitdxilg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhongyouzk.top/Article/details/gtlffbadyq.html

JS:   // worker_threads 线程池
来源：http://dali.ydzc1.top/Article/details/gtrxbsrbrj.html

TS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gtfywhaice.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hongshengwenyu.top/Article/details/gtiiqxdmbx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daxiang520.top/Article/details/gtlxpdbecq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sysykeji.top/Article/details/gtfyeucbit.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgglxkay.html

[O03] 加锁保护共享数据
来源：http://dali.redwolf501.top/Article/details/gtblptaftj.html

Py:   with lock: shared += 1
来源：http://dali.gaohongyu789.top/Article/details/gtcbuikhwm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.mhx1999.top/Article/details/gtmjorslqu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.quarkkingdee.top/Article/details/gtvanvhohd.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gtthhqflue.html

Java: synchronized (this) { shared++; }
来源：http://dali.zdqjudy.top/Article/details/gtexjiellb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.snrcjt.cn/Article/details/gtooadzuvd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj20258888.top/Article/details/gthepdsuhr.html

C#:   lock (gate) { shared++; }
来源：http://dali.aibaodan.cn/Article/details/gtjjkjltgt.html

[O04] 定义异步函数并等待
来源：http://dali.gotoacloud.top/Article/details/gtqtpgxnrc.html

Py:   async def f():⏎    await g()
来源：http://dali.zycfv.cn/Article/details/gtmizgmhfe.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dashuyun.cn/Article/details/gtvgmxinxz.html

JS:   async function f() { await g(); }
来源：http://dali.ydzc1.top/Article/details/gtudspaqcp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ydzc1.top/Article/details/gtkyqnnupt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sxryk.cn/Article/details/gtzkqqhwto.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hnxiangtu.top/Article/details/gtqwvnaads.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgfzy.top/Article/details/gtwpeyvbdn.html

C#:   async Task F() { await G(); }
来源：http://dali.yonumen.top/Article/details/gtltamxcvf.html

[O05] 并发执行并等待全部完成
来源：http://dali.fzhhl.top/Article/details/gtusoiuioq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cashguo.top/Article/details/gtllrjslui.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.snrcjt.cn/Article/details/gtsgidkiax.html

JS:   await Promise.all(tasks)
来源：http://dali.fzhhl.top/Article/details/gtqwayafeh.html

TS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtqwfdyykn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shzxlz.cn/Article/details/gtgjrkwuwp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yueranfly.top/Article/details/gtusqrxgoc.html

Ruby: threads.map(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gtmlrnutcs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nanxuanxn.top/Article/details/gtkzysujwq.html

[O06] 使用进程池
来源：http://dali.9152youxi.cn/Article/details/gtbsmefmtz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.iojbl.cn/Article/details/gtwoipipoz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shangyingyoupin.top/Article/details/gtzfibhsxh.html

JS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gtvlrbdvvx.html

TS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gtkqsifrmj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fzhhl.top/Article/details/gtugcosigd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yongpay.top/Article/details/gtpeevurvo.html

Ruby: // fork 块
来源：http://dali.9152youxi.cn/Article/details/gtcewyotzw.html

C#:   Parallel.For
来源：http://dali.sweek.top/Article/details/gtdafrxwto.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gttgnatnto.html

P. 常用工具函数
来源：http://dali.nanxuanxn.top/Article/details/gtuqafkzws.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtrddwwljk.html

[P01] 生成 UUID
来源：http://dali.nwbrower.top/Article/details/gtpvgsmdcc.html

Py:   str(uuid.uuid4())
来源：http://dali.hongshengwenyu.top/Article/details/gtdjyupnrc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hfpthk.cn/Article/details/gtpyokvvew.html

JS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gtlxtjkffe.html

TS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gtirzghehh.html

Java: UUID.randomUUID().toString()
来源：http://dali.tian-w.cn/Article/details/gtfanpuaro.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sxryk.cn/Article/details/gtmxyusqit.html

Ruby: SecureRandom.uuid
来源：http://dali.ivvv.top/Article/details/gthpsceabh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhongyouzk.top/Article/details/gtevpiwioe.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xuetiantiany.cn/Article/details/gtlrosmuet.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj20258888.top/Article/details/gtlmtkiedk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tianlin.xyz/Article/details/gtikvtxexr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenzaomai.com/Article/details/gtbkosabby.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.smart0.xyz/Article/details/gttahdryol.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gtpcmbepjr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jiagoushi.top/Article/details/gthtawhdwd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.vqdsnc.cn/Article/details/gtmtnpahgw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sysykeji.top/Article/details/gttobsqhwf.html

[P03] 生成短随机字符串
来源：http://dali.yangfankeji.com/Article/details/gtmsfudvlf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yonumen.top/Article/details/gtmzcdhngz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinqigfzy.top/Article/details/gtgowtjywc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.c1oappe.top/Article/details/gtyhclivrm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gttdpgxxfh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.0kj1m.cn/Article/details/gtbwggjgxk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yanxiufei.cn/Article/details/gtkkprpjhq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jianghu66.top/Article/details/gtdcuxcnau.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuxming.cn/Article/details/gtlnoefsga.html

[P04] 求长度
来源：http://dali.shangyingyoupin.top/Article/details/gtwwitaual.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.meibo888.top/Article/details/gtbdcgjnuw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtzectydaw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fengsongda.top/Article/details/gtjmfrapgp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnqzz.top/Article/details/gtcrkmuljy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.fzhhl.top/Article/details/gtbavmwzli.html

Go:   len(arr);  len(m)
来源：http://dali.ybcxt.top/Article/details/gthgxrnwtj.html

Ruby: x.length;  x.size
来源：http://dali.yuxming.cn/Article/details/gtwpngogcs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sweek.top/Article/details/gtzolzqzyu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxuanxn.top/Article/details/gtjacifdgp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guowangkeji.top/Article/details/gtdtyuyfap.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hywenlv.cn/Article/details/gtancddoqq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sxryk.cn/Article/details/gtebzuyzwt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cdnleiting.top/Article/details/gtdmwvdhzu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gotoacloud.top/Article/details/gtvzrcpuww.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtrpzlmvid.html

Ruby: a == b
来源：http://dali.guannengcc.top/Article/details/gtwaojjlux.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuxming.cn/Article/details/gteqpgwylj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zdqjudy.top/Article/details/gtgsnpqmpz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenzaomai.com/Article/details/gtmjccyamk.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigufen.top/Article/details/gtrnheryeb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yueranfly.top/Article/details/gtoulsajto.html

TS:   if (x == null) {}
来源：http://dali.kuanghao11.cn/Article/details/gtpwogagdk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.dianchejie.cn/Article/details/gtncernltl.html

Go:   if x == nil {}
来源：http://dali.fengsongda.top/Article/details/gtcbqihpyf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsjspngr.html

C#:   if (x is null) {}
来源：http://dali.tianlin.xyz/Article/details/gttzunukvq.html

[P07] 防抖与节流
来源：http://dali.cucudq.cn/Article/details/gtvbzafowe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.quarkkingdee.top/Article/details/gtgpiijznz.html

PHP:  // 手写时间戳比较
来源：http://dali.ydzc1.top/Article/details/gtovbbswwm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gtggeqhrhz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gtepgpffqc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.vqdsnc.cn/Article/details/gtoigknyiw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjkdhyjv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shangyingyoupin.top/Article/details/gtklrxofcl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tian-w.cn/Article/details/gtvhcqnuag.html

[P08] 处理浮点精度问题
来源：http://dali.nanxuanxn.top/Article/details/gtmdqanwck.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hongshengwenyu.top/Article/details/gtxefdzyal.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.iojbl.cn/Article/details/gtlozgeafb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xziqi.cn/Article/details/gtzawxflte.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.mhx1999.top/Article/details/gtiydaowbw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.smart0.xyz/Article/details/gtxtnhauvt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhoulong.xyz/Article/details/gtipegkwdu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.andypj.xyz/Article/details/gtinuchxpi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.snrcjt.cn/Article/details/gtxgqjdpoz.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtyustoqll.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shuidangran.top/Article/details/gtlavvvbol.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtxvzxmxkq.html

[Q01] 创建表
来源：http://dali.yonumen.top/Article/details/gtwzxrlakq.html

CREATE TABLE users (
来源：http://dali.nanxinkj.top/Article/details/gtsqierphq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yongpay.top/Article/details/gtmyscahcc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258888.top/Article/details/gtewtjvicn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yvedp.cn/Article/details/gtosokqxda.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigufen.top/Article/details/gtzvhfaiyq.html

);
来源：http://dali.guannengcc.top/Article/details/gtmwrrmncz.html

[Q02] 创建带外键的表
来源：http://dali.gogol.net.cn/Article/details/gtsokfapin.html

CREATE TABLE orders (
来源：http://dali.haohaochexian.top/Article/details/gtzvedikxw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gtalsmmxsr.html

user_id INT NOT NULL,
来源：http://dali.nanxuanxn.top/Article/details/gtziumsmxt.html

amount DECIMAL(10, 2),
来源：http://dali.cucudq.cn/Article/details/gtarknwrdu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhixingplan.top/Article/details/gtedeokctb.html

);
来源：http://dali.yuxming.cn/Article/details/gtpfpvkyob.html

[Q03] 增加列
来源：http://dali.nanxinkj.top/Article/details/gtayjgbnwz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj20258888.top/Article/details/gtapyatemi.html

[Q04] 修改列类型
来源：http://dali.xuanzx.com/Article/details/gtjxelwfae.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sysykeji.top/Article/details/gtashkqele.html

[Q05] 重命名列
来源：http://dali.wangshuangyany.cn/Article/details/gtxzkqkrhj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.9152youxi.cn/Article/details/gtbixhbnzk.html

[Q06] 删除列
来源：http://dali.xinyue.icu/Article/details/gtzjcbcdxu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifxaajbm.html

[Q07] 删除表
来源：http://dali.svipenyu.cn/Article/details/gtdjiatogu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.c1oappe.top/Article/details/gtytlxjdev.html

[Q08] 创建普通索引
来源：http://dali.pycfn.com/Article/details/gtvbnemjcn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gtjdsccifz.html

[Q09] 创建唯一索引
来源：http://dali.shangyingyoupin.top/Article/details/gtxkqjkoyw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gtqmkynuke.html

[Q10] 插入单行
来源：http://dali.svipenyu.cn/Article/details/gtsnnlksye.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ybcxt.top/Article/details/gtbyzaloqo.html

[Q11] 一次插入多行
来源：http://dali.hnqzz.top/Article/details/gtgbsodmzv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.meibo888.top/Article/details/gtsfmffdnf.html

[Q12] 插入后取自增 ID
来源：http://dali.chenzaomai.com/Article/details/gtypnqkyse.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ppjwa.cn/Article/details/gtbtsnclvr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xuanzx.com/Article/details/gtewjzebah.html

[Q13] 忽略重复插入
来源：http://dali.andypj.xyz/Article/details/gtjvshfjtt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gtpamksdtq.html

[Q14] 存在则更新（upsert）
来源：http://dali.yangfankeji.com/Article/details/gtljdejoae.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.0kj1m.cn/Article/details/gtzjqawldt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xziqi.cn/Article/details/gtfokptnuf.html

[Q15] 查询全部
来源：http://dali.jiagoushi.top/Article/details/gtwilgvuuy.html

SELECT * FROM users;
来源：http://dali.ybcxt.top/Article/details/gtspsvlntt.html

[Q16] 查询指定列
来源：http://dali.cheryme.top/Article/details/gtfdhcphqi.html

SELECT id, name FROM users;
来源：http://dali.cashguo.top/Article/details/gtwtmxwxch.html

[Q17] 条件查询
来源：http://dali.zhoulong.xyz/Article/details/gtmuyydjjy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthpnasdw.html

[Q18] 模糊匹配
来源：http://dali.xinyue.icu/Article/details/gtnbpqnruy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.316326.xyz/Article/details/gtfyxemmkq.html

[Q19] 范围查询
来源：http://dali.iojbl.cn/Article/details/gtyrmevbma.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.bjfxy.top/Article/details/gttudyfyzl.html

[Q20] IN 列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezoqfilh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtyuplgmaw.html

[Q21] 空值判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwcjnzen.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ehwqpu.com/Article/details/gtgkmnrqdy.html

[Q22] 排序
来源：http://dali.dashuyun.cn/Article/details/gtwixazqzy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhixingplan.top/Article/details/gtgcrxsbfh.html

[Q23] 分页
来源：http://dali.ydzc1.top/Article/details/gtyahjxrsd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj20258888.top/Article/details/gtcenleeis.html

[Q24] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtjsbrxchy.html

SELECT DISTINCT city FROM users;
来源：http://dali.xinyue.icu/Article/details/gtxjtigaam.html

[Q25] 只取前 N 条
来源：http://dali.zhongyouzk.top/Article/details/gtjmjcvaid.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.vqdsnc.cn/Article/details/gtciwlkmvz.html

[Q26] 计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjzwgzwc.html

SELECT COUNT(*) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtlkiemzqw.html

[Q27] 条件计数
来源：http://dali.zhixingplan.top/Article/details/gtqburonkv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtnrhnhgjn.html

[Q28] 求和与平均
来源：http://dali.hongshengwenyu.top/Article/details/gthojqnaoa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtddneeysz.html

[Q29] 最大最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsvnjkrb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtuizflbdz.html

[Q30] 分组统计
来源：http://dali.bjfxy.top/Article/details/gtqfzkfvcu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gtxrguaoly.html

[Q31] 分组后过滤
来源：http://dali.snrcjt.cn/Article/details/gtnpkoajki.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.dashuyun.cn/Article/details/gtqnuixkbb.html

[Q32] 分组拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gtzczxrqze.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gtmmnxgyye.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangdashe.top/Article/details/gtrpbfohnm.html

[Q33] 多列分组
来源：http://dali.sysykeji.top/Article/details/gtuknggddx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfoqycib.html

[Q34] 每组取第一条
来源：http://dali.yj20258.top/Article/details/gtkspbjlde.html

SELECT * FROM (
来源：http://dali.cqqwz.cn/Article/details/gtegucnszi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ybcxt.top/Article/details/gtmmxlrghr.html

) t WHERE rn = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtzkmjylpt.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gtlytahydy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtwkovghbf.html

[Q36] 左连接
来源：http://dali.zhixingplan.top/Article/details/gtxppjgspa.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gtsxutwcpj.html

[Q37] 右连接
来源：http://dali.iojbl.cn/Article/details/gtaudxrbue.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.andypj.xyz/Article/details/gtzuqcbyau.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shuidangran.top/Article/details/gtxhkukldq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.vqdsnc.cn/Article/details/gtszfexmrq.html

[Q39] 自连接（查上下级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkmugjcp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gogol.net.cn/Article/details/gtdqfhshdz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.9152youxi.cn/Article/details/gtqbqurfsg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.birdmap.top/Article/details/gtwcdhywxh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fengsongda.top/Article/details/gtplfsqafr.html

[Q41] 多表连接
来源：http://dali.chenjidiqi.icu/Article/details/gtuqjiungx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jlsjyb.cn/Article/details/gtsulfznfp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tian-w.cn/Article/details/gtneglatgb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.quarkkingdee.top/Article/details/gtzufydvuz.html

[Q42] 连接条件附加过滤
来源：http://dali.yueranfly.top/Article/details/gtbstggjva.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sxryk.cn/Article/details/gtqrrbjjzs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shangyingyoupin.top/Article/details/gtzvxmlpax.html

[Q43] 标量子查询
来源：http://dali.snrcjt.cn/Article/details/gtkvdltnbk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj20258.top/Article/details/gtxoysodpk.html


<!-- 参考信息 -->