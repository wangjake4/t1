代发 wailian999

JS:   s === [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtqnseehev.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtcisvnjqd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhkjdchp.html

Go:   // 双指针从两端比较
来源：http://dali.shangyingyoupin.top/Article/details/gtqqbplomt.html

Ruby: s == s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gtpkycwdxk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gtoluvpilv.html

[N07] 两数之和（返回下标）
来源：http://dali.jinqigufen.top/Article/details/gtzucgqvbj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.smart0.xyz/Article/details/gtvvemldib.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnxiangtu.top/Article/details/gtuctyokak.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhixingplan.top/Article/details/gtoouhonca.html

TS:   // 手写 Map<string, number>
来源：http://dali.dashuyun.cn/Article/details/gtfgoafwfb.html

Java: // 手写 HashMap
来源：http://dali.aibaodan.cn/Article/details/gtnaijpaxo.html

Go:   // 手写 map[int]int
来源：http://dali.cheryme.top/Article/details/gtlukrhjgk.html

Ruby: // 手写 Hash
来源：http://dali.nwbrower.top/Article/details/gtluzgiejp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.quarkkingdee.top/Article/details/gtvwmgbyle.html

[N08] 生成全排列
来源：http://dali.yongpay.top/Article/details/gtjbqdzxzq.html

Py:   itertools.permutations(arr)
来源：http://dali.zycfv.cn/Article/details/gtvygenhiw.html

PHP:  // 手写递归交换
来源：http://dali.ppjwa.cn/Article/details/gtsfmnosqf.html

JS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtlcabvqml.html

TS:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtdcshpuqu.html

Java: // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gttziocjrb.html

Go:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtsrocgirn.html

Ruby: arr.permutation.to_a
来源：http://dali.jlsjyb.cn/Article/details/gtukpyogxh.html

C#:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtovylehos.html

[N09] 栈与队列
来源：http://dali.mhx1999.top/Article/details/gtchvqkqcs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yangfankeji.com/Article/details/gtcrqihfpo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gtbyyntunz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gtscemyffi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xziqi.cn/Article/details/gtpwjqybxn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hysaishi.cn/Article/details/gtpmccykqr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhoulong.xyz/Article/details/gtaswdqxcg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gtyltubhve.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dianchejie.cn/Article/details/gtxmciwjbk.html

[N10] 链表节点定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmmextav.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guowangkeji.top/Article/details/gtxkmmepcj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpahzwdiv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ivvv.top/Article/details/gtplicymga.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258.top/Article/details/gtvumcunyy.html

Java: class Node { int v; Node next; }
来源：http://dali.cheryme.top/Article/details/gtpznollfz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ivvv.top/Article/details/gttmeasdih.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yvedp.cn/Article/details/gtgzlfkzbl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tian-w.cn/Article/details/gtrnohrfju.html

[N11] 二叉树中序遍历
来源：http://dali.cdnleiting.top/Article/details/gtohmopclv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.c1oappe.top/Article/details/gtpnodwkfv.html

PHP:  // 手写递归函数
来源：http://dali.gogol.net.cn/Article/details/gtphajuvue.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guowangkeji.top/Article/details/gtkglrjflq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shuidangran.top/Article/details/gtjfuypopm.html

Java: // 手写递归
来源：http://dali.tanke756.top/Article/details/gtrlyhgyiq.html

Go:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gtkrntutwh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sxryk.cn/Article/details/gtgurranys.html

C#:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gtsqbtfudg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgrbcuxk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ehwqpu.com/Article/details/gteumexqpt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.svipenyu.cn/Article/details/gtmrmuinzj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hysaishi.cn/Article/details/gtputeptlr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sufxvd.cn/Article/details/gtwpifilcf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenzaomai.com/Article/details/gtrqxgmgez.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hywenlv.cn/Article/details/gtvmjxgeoj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhengqikj.top/Article/details/gtqemgokmn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gtnkcxqrui.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtbfghrnhn.html

O. 并发与异步
来源：http://dali.ybcxt.top/Article/details/gtlkevllcb.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtbtjhtfag.html

[O01] 启动一个线程
来源：http://dali.chenjidiqi.icu/Article/details/gtjirmedtj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.guowangkeji.top/Article/details/gtprkfcppt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ehwqpu.com/Article/details/gtfcnsxdio.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xuetiantiany.cn/Article/details/gtpkcjrswz.html

TS:   // 同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtysaymprk.html

Java: new Thread(() -> f()).start()
来源：http://dali.dashuyun.cn/Article/details/gtqeiydipr.html

Go:   go f()
来源：http://dali.redwolf501.top/Article/details/gtqldvdcbl.html

Ruby: Thread.new { f }
来源：http://dali.mhx1999.top/Article/details/gtfomxkjfz.html

C#:   Task.Run(() => F());
来源：http://dali.aibaodan.cn/Article/details/gtyrgitlba.html

[O02] 使用线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtxbstwugd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ppjwa.cn/Article/details/gtqmlipzhd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gaohongyu789.top/Article/details/gtsqbqmerw.html

JS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gtltdejsce.html

TS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gtldexhhdz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.svipenyu.cn/Article/details/gtzejlyrup.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.iojbl.cn/Article/details/gtftzyknht.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tian-w.cn/Article/details/gtcougxoiu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cqqwz.cn/Article/details/gtyuqzqflu.html

[O03] 加锁保护共享数据
来源：http://dali.yongpay.top/Article/details/gteznwjztm.html

Py:   with lock: shared += 1
来源：http://dali.nanxuanxn.top/Article/details/gthnzixghq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.feifeiyinyue.top/Article/details/gtgmhlrdio.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fzhhl.top/Article/details/gtefdxwyej.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gtpfzsfbmn.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gthnbhhdln.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkupwqnc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinqigufen.top/Article/details/gtbxfrbmbe.html

C#:   lock (gate) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvlaardro.html

[O04] 定义异步函数并等待
来源：http://dali.yuxming.cn/Article/details/gtlsjiszuu.html

Py:   async def f():⏎    await g()
来源：http://dali.yuxming.cn/Article/details/gtjtzejwqp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinghuilouyu.cn/Article/details/gttmiezfqg.html

JS:   async function f() { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gtuadttomn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gtlekhwsew.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.birdmap.top/Article/details/gtgamvmaut.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.guannengcc.top/Article/details/gtlvnvhrrh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.quarkkingdee.top/Article/details/gtamppitje.html

C#:   async Task F() { await G(); }
来源：http://dali.0kj1m.cn/Article/details/gtmraezaku.html

[O05] 并发执行并等待全部完成
来源：http://dali.tanke756.top/Article/details/gtkkdfmidc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hywenlv.cn/Article/details/gtwetyevvt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zycfv.cn/Article/details/gtmaxldkxc.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gtzkdjmekc.html

TS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtyxjqueyy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tanke756.top/Article/details/gttstinyvu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hongshengwenyu.top/Article/details/gtauoisqxq.html

Ruby: threads.map(&:join)
来源：http://dali.birdmap.top/Article/details/gtbnccfcxb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gzhubu.top/Article/details/gtpaokykxj.html

[O06] 使用进程池
来源：http://dali.meibo888.top/Article/details/gteqmtcmvq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ehwqpu.com/Article/details/gtqexeqkkv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdsvowgm.html

JS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdijyfgm.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsmymsyn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258.top/Article/details/gtnzvzdvsn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.fengsongda.top/Article/details/gtpgozdrto.html

Ruby: // fork 块
来源：http://dali.yuxming.cn/Article/details/gtjcejhtvp.html

C#:   Parallel.For
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgnemavo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gthcwcdvxt.html

P. 常用工具函数
来源：http://dali.cucudq.cn/Article/details/gtwepminjw.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gttqxhfecr.html

[P01] 生成 UUID
来源：http://dali.cashguo.top/Article/details/gtarewyzxr.html

Py:   str(uuid.uuid4())
来源：http://dali.hfpthk.cn/Article/details/gtkbtfctio.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cheryme.top/Article/details/gtizrapjcm.html

JS:   crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gtndecohac.html

TS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gtdcdeeipf.html

Java: UUID.randomUUID().toString()
来源：http://dali.sufxvd.cn/Article/details/gtmuyslvwf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sufxvd.cn/Article/details/gtjylipoua.html

Ruby: SecureRandom.uuid
来源：http://dali.bjfxy.top/Article/details/gtrqmzmjdp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.fzhhl.top/Article/details/gthdbjzxyd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yonumen.top/Article/details/gthakgdkdx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangshuangyany.cn/Article/details/gtaiqdlgko.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cucudq.cn/Article/details/gtfcuzarzx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.quarkkingdee.top/Article/details/gtbmuofjgs.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hfpthk.cn/Article/details/gtjifdulih.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtxwgnabfy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cashguo.top/Article/details/gtaunbnkgq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shuidangran.top/Article/details/gtjbnxbson.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yanxiufei.cn/Article/details/gtkalaqgje.html

[P03] 生成短随机字符串
来源：http://dali.dashuyun.cn/Article/details/gtdyhdkupz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ybcxt.top/Article/details/gtlloldyzz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.haohaochexian.top/Article/details/gtgcnyvpns.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gtyokffczr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yongpay.top/Article/details/gtnrcnowpw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.fzhhl.top/Article/details/gtxvjazpvl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghkbunaq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ppjwa.cn/Article/details/gtykdpofkb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnxiangtu.top/Article/details/gtgazhcdur.html

[P04] 求长度
来源：http://dali.gaohongyu789.top/Article/details/gtcliiibbf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.bjfxy.top/Article/details/gtfaqvuocc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gttjnnxjry.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cashguo.top/Article/details/gtyfqkiijr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gtjvkpipkg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.fzhhl.top/Article/details/gtdlspngvl.html

Go:   len(arr);  len(m)
来源：http://dali.gotoacloud.top/Article/details/gtaluvibbz.html

Ruby: x.length;  x.size
来源：http://dali.jqgfzy.top/Article/details/gtlfhztukk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xylfe.cn/Article/details/gtmatvifad.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dianchejie.cn/Article/details/gtbdgjtiom.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sysykeji.top/Article/details/gtzkyohqwt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.smart0.xyz/Article/details/gtwsmkffdi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hywenlv.cn/Article/details/gtgtoqpnwh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhoulong.xyz/Article/details/gtcfziogff.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yangfankeji.com/Article/details/gtdctofwno.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtixqwyfhg.html

Ruby: a == b
来源：http://dali.guowangkeji.top/Article/details/gtjmhyfquw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cqqwz.cn/Article/details/gtenwdqape.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinqigufen.top/Article/details/gtuvwvmqsc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nwbrower.top/Article/details/gtexgrrjjl.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigfzy.top/Article/details/gtgcksjqnf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nwbrower.top/Article/details/gtphgjeesx.html

TS:   if (x == null) {}
来源：http://dali.chenlongwang.top/Article/details/gtwmyzkrvo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gtkovwzdvw.html

Go:   if x == nil {}
来源：http://dali.gotoacloud.top/Article/details/gtuqljwmrf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sxryk.cn/Article/details/gtirrgzneb.html

C#:   if (x is null) {}
来源：http://dali.guowangkeji.top/Article/details/gtilaiqfjp.html

[P07] 防抖与节流
来源：http://dali.wangshuangyany.cn/Article/details/gtopsuhjhd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmbhjgei.html

PHP:  // 手写时间戳比较
来源：http://dali.ehwqpu.com/Article/details/gtnwhaowkv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtaxhkntcz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gtkwwtdfng.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtfweyumok.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yuxming.cn/Article/details/gtpsygrcxv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ydzc1.top/Article/details/gtolqhisgb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jyoumei.cn/Article/details/gtqdkpseau.html

[P08] 处理浮点精度问题
来源：http://dali.wangshuangyany.cn/Article/details/gtakluwzoz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.dashuyun.cn/Article/details/gtcjvbtosf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hnqzz.top/Article/details/gtevtuoedk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shangyingyoupin.top/Article/details/gtkcbmihxm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yj202588.top/Article/details/gthqwwykwi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gzhubu.top/Article/details/gtgbdzrdlw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zycfv.cn/Article/details/gtjszbijfn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.nwbrower.top/Article/details/gtyztltnnv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xylfe.cn/Article/details/gtzkhpeejp.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtmmfdyrle.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258888.top/Article/details/gtousebrtk.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtogxtbtcf.html

[Q01] 创建表
来源：http://dali.jinghuilouyu.cn/Article/details/gttvfglsrl.html

CREATE TABLE users (
来源：http://dali.hysaishi.cn/Article/details/gtbcwsjego.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gtagrlasnn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shzxlz.cn/Article/details/gtzhwpzyew.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xuanzx.com/Article/details/gtvkxicsiw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jqgfzy.top/Article/details/gtcmjubsyh.html

);
来源：http://dali.cheryme.top/Article/details/gtanxuhwnf.html

[Q02] 创建带外键的表
来源：http://dali.yongpay.top/Article/details/gtfvuujust.html

CREATE TABLE orders (
来源：http://dali.gzhubu.top/Article/details/gtptmrikhe.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gtfcacdhdm.html

user_id INT NOT NULL,
来源：http://dali.cashguo.top/Article/details/gtahzgvfwb.html

amount DECIMAL(10, 2),
来源：http://dali.ehwqpu.com/Article/details/gtaojxuwxd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.vqdsnc.cn/Article/details/gtlfkzpvym.html

);
来源：http://dali.yongpay.top/Article/details/gtdlljxrjv.html

[Q03] 增加列
来源：http://dali.haohaochexian.top/Article/details/gtowyphxqr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cashguo.top/Article/details/gtalgmeykb.html

[Q04] 修改列类型
来源：http://dali.xziqi.cn/Article/details/gtvgxboxbh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xziqi.cn/Article/details/gtcdjjqkce.html

[Q05] 重命名列
来源：http://dali.daxiang520.top/Article/details/gtgejlggqa.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yangfankeji.com/Article/details/gtfrplxdnr.html

[Q06] 删除列
来源：http://dali.daxiang520.top/Article/details/gtnaqydpjz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cdnleiting.top/Article/details/gtzwhvshjg.html

[Q07] 删除表
来源：http://dali.tian-w.cn/Article/details/gtasyhoklv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xziqi.cn/Article/details/gtybfaopzj.html

[Q08] 创建普通索引
来源：http://dali.sxryk.cn/Article/details/gtpqvyteml.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinqigfzy.top/Article/details/gtccdhqpvz.html

[Q09] 创建唯一索引
来源：http://dali.zhoulong.xyz/Article/details/gtgwmlhviv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gtrxghsxim.html

[Q10] 插入单行
来源：http://dali.jyoumei.cn/Article/details/gtbngryomd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guowangkeji.top/Article/details/gtphnrhcek.html

[Q11] 一次插入多行
来源：http://dali.shuidangran.top/Article/details/gtfbxrteqb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ydzc1.top/Article/details/gtxxfcyczj.html

[Q12] 插入后取自增 ID
来源：http://dali.shangyingyoupin.top/Article/details/gthuywmggo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ppjwa.cn/Article/details/gtjslilish.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.andypj.xyz/Article/details/gtjmbrmaro.html

[Q13] 忽略重复插入
来源：http://dali.jlsjyb.cn/Article/details/gtmsddbhxw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmytlppsg.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnxiangtu.top/Article/details/gtsbronnhp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yueranfly.top/Article/details/gtrkmcccyd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xziqi.cn/Article/details/gtulnhyzqq.html

[Q15] 查询全部
来源：http://dali.hfpthk.cn/Article/details/gtfejvtjqt.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gttxbfnvdb.html

[Q16] 查询指定列
来源：http://dali.guannengcc.top/Article/details/gtipsqewax.html

SELECT id, name FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgmysqnp.html

[Q17] 条件查询
来源：http://dali.cashguo.top/Article/details/gttyrpgzld.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtjnsaovsd.html

[Q18] 模糊匹配
来源：http://dali.dianchejie.cn/Article/details/gtboxnyrmd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ydzc1.top/Article/details/gtghhzbfew.html

[Q19] 范围查询
来源：http://dali.iojbl.cn/Article/details/gtgbcqyrwj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shangyingyoupin.top/Article/details/gthpiktkqa.html

[Q20] IN 列表
来源：http://dali.meibo888.top/Article/details/gtupvnoxev.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xinyue.icu/Article/details/gttoeslauz.html

[Q21] 空值判断
来源：http://dali.zhixingplan.top/Article/details/gtvuujnvmm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnqzz.top/Article/details/gtpiscivna.html

[Q22] 排序
来源：http://dali.feifeiyinyue.top/Article/details/gtivpxzjym.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinghuilouyu.cn/Article/details/gtekbxtitm.html

[Q23] 分页
来源：http://dali.hywenlv.cn/Article/details/gtcvhzkggt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhixingplan.top/Article/details/gtwimegapf.html

[Q24] 去重
来源：http://dali.shzxlz.cn/Article/details/gttkzahanq.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtuzyckrvs.html

[Q25] 只取前 N 条
来源：http://dali.gzhubu.top/Article/details/gtoosrmiso.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fengsongda.top/Article/details/gtosbaodiw.html

[Q26] 计数
来源：http://dali.wangshuangyany.cn/Article/details/gtgabjbgtn.html

SELECT COUNT(*) FROM users;
来源：http://dali.sweek.top/Article/details/gtfgqviddz.html

[Q27] 条件计数
来源：http://dali.svipenyu.cn/Article/details/gtgezpygue.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xuanzx.com/Article/details/gtftoozsuk.html

[Q28] 求和与平均
来源：http://dali.feifeiyinyue.top/Article/details/gtcrspzmkh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtkzrcnkns.html

[Q29] 最大最小值
来源：http://dali.tian-w.cn/Article/details/gtkerpkmdp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtvgkhpasg.html

[Q30] 分组统计
来源：http://dali.aibaodan.cn/Article/details/gtkfdrcpuq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtfsullcbh.html

[Q31] 分组后过滤
来源：http://dali.dashuyun.cn/Article/details/gtszntvjfl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtlemwvpkl.html

[Q32] 分组拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtwwazstru.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gtucmpkqnp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xylfe.cn/Article/details/gtbsnpmlmj.html

[Q33] 多列分组
来源：http://dali.zdqjudy.top/Article/details/gtddfvajda.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.vqdsnc.cn/Article/details/gtmkjqfjqk.html

[Q34] 每组取第一条
来源：http://dali.daxiang520.top/Article/details/gtbvqazhic.html

SELECT * FROM (
来源：http://dali.mhx1999.top/Article/details/gtliblreeg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.birdmap.top/Article/details/gtmfbljwzy.html

) t WHERE rn = 1;
来源：http://dali.hfpthk.cn/Article/details/gtmtvoaewt.html

[Q35] 内连接
来源：http://dali.bjfxy.top/Article/details/gtgtgczczu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdhddbhl.html

[Q36] 左连接
来源：http://dali.yuxming.cn/Article/details/gtrtxyaoav.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbclaizx.html

[Q37] 右连接
来源：http://dali.ehwqpu.com/Article/details/gtozcflskd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cucudq.cn/Article/details/gtdbjgnyau.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkkiqzdv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenzaomai.com/Article/details/gtvfvklvmp.html

[Q39] 自连接（查上下级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnxlwafd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dashuyun.cn/Article/details/gtzntsoder.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hammf.cn/Article/details/gtusfzbprg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.feifeiyinyue.top/Article/details/gtztaggbtq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvefooeb.html

[Q41] 多表连接
来源：http://dali.zhoulong.xyz/Article/details/gtoyviwjei.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ehwqpu.com/Article/details/gtepqjjktt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jianghu66.top/Article/details/gtxtgzwhuq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sufxvd.cn/Article/details/gtpeokvhmg.html

[Q42] 连接条件附加过滤
来源：http://dali.c1oappe.top/Article/details/gtwztqtjcy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.smart0.xyz/Article/details/gtjjnrbibg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnzvkqpq.html

[Q43] 标量子查询
来源：http://dali.tanke756.top/Article/details/gtfvpbpcev.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.daxiang520.top/Article/details/gttxgwldzk.html


<!-- 参考信息 -->