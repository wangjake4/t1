代发 wailian999

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtpzgumime.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangdashe.top/Article/details/gtatbtxten.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgfzy.top/Article/details/gttwfcrtko.html

Ruby: a.gcd(b)
来源：http://dali.iojbl.cn/Article/details/gtjbschjgu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cheryme.top/Article/details/gttfqsfqwq.html

[N06] 判断回文字符串
来源：http://dali.daxiang520.top/Article/details/gtsswogpez.html

Py:   s == s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gtvuqwvhbx.html

PHP:  $s === strrev($s);
来源：http://dali.hnqzz.top/Article/details/gtbcxvhgvx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtbkeepaxo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtfrvkozdk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuanzx.com/Article/details/gtjmragqkz.html

Go:   // 双指针从两端比较
来源：http://dali.sysykeji.top/Article/details/gteqxvmfyn.html

Ruby: s == s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gtedisqnvy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gthxxvieyu.html

[N07] 两数之和（返回下标）
来源：http://dali.shanyushiyangtech.top/Article/details/gtylhgagwr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yanxiufei.cn/Article/details/gtzzwjxfhy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yongpay.top/Article/details/gtjytsgrvm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xinyue.icu/Article/details/gtcorvqybr.html

TS:   // 手写 Map<string, number>
来源：http://dali.hywenlv.cn/Article/details/gtdscefrhp.html

Java: // 手写 HashMap
来源：http://dali.shangyingyoupin.top/Article/details/gtrcoslqnh.html

Go:   // 手写 map[int]int
来源：http://dali.jqgfzy.top/Article/details/gtayxygqoc.html

Ruby: // 手写 Hash
来源：http://dali.yj20258888.top/Article/details/gtkhovgfyp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cheryme.top/Article/details/gtdpeqebhu.html

[N08] 生成全排列
来源：http://dali.guannengcc.top/Article/details/gtplmonfnz.html

Py:   itertools.permutations(arr)
来源：http://dali.yuanzhike.top/Article/details/gtqjsdtkwh.html

PHP:  // 手写递归交换
来源：http://dali.nwbrower.top/Article/details/gtygoufdma.html

JS:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtabjzhydx.html

TS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtuobojmio.html

Java: // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtmgtjwlqa.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gthxdogffe.html

Ruby: arr.permutation.to_a
来源：http://dali.feifeiyinyue.top/Article/details/gtjwxdmeyt.html

C#:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gttdfzbrru.html

[N09] 栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtydcofufa.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xinyue.icu/Article/details/gtvrcrqbuq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtnkalindz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtdfsshscr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.bjfxy.top/Article/details/gtemiltqlq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daxiang520.top/Article/details/gtwiiuashd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.feifeiyinyue.top/Article/details/gtpwddbtvt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yueranfly.top/Article/details/gtpfirzzzm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sysykeji.top/Article/details/gtgcuzixfc.html

[N10] 链表节点定义
来源：http://dali.guannengcc.top/Article/details/gtqkswcyrq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsaeefhsh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.meibo888.top/Article/details/gtdbsktgwa.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtpkmaaloj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gogol.net.cn/Article/details/gtguzpzbtd.html

Java: class Node { int v; Node next; }
来源：http://dali.tanke756.top/Article/details/gtdujpdsuo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhixingplan.top/Article/details/gtbhndgwlh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhixingplan.top/Article/details/gtddlxkanc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hammf.cn/Article/details/gtajmiarkt.html

[N11] 二叉树中序遍历
来源：http://dali.xinyue.icu/Article/details/gtmdjdpbjc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.meibo888.top/Article/details/gtmmbrdfeu.html

PHP:  // 手写递归函数
来源：http://dali.cucudq.cn/Article/details/gthdqhjeri.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gtiogebmkj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yonumen.top/Article/details/gtbsxurdct.html

Java: // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gteypkxvku.html

Go:   // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gthzqptdwk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.svipenyu.cn/Article/details/gttqmjaenr.html

C#:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtcjjvknrp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gtxsztfnzk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gtcszvqora.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenzaomai.com/Article/details/gtbypuudmj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gtwcpqgjtq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sufxvd.cn/Article/details/gttxuxxryn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gtapgyrkke.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlhiznxz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sysykeji.top/Article/details/gtwjlywzbv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gtlaqrslzk.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtlpyihbia.html

O. 并发与异步
来源：http://dali.nanxuanxn.top/Article/details/gtzpfwtlsx.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtweywfizh.html

[O01] 启动一个线程
来源：http://dali.jyoumei.cn/Article/details/gtabpbzhoj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gtydhecdwq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sufxvd.cn/Article/details/gtjchlojda.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.snrcjt.cn/Article/details/gtehvtlmsj.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gttjteunnn.html

Java: new Thread(() -> f()).start()
来源：http://dali.pengpengdd.cyou/Article/details/gtvnzaueqd.html

Go:   go f()
来源：http://dali.shzxlz.cn/Article/details/gtabzpvabw.html

Ruby: Thread.new { f }
来源：http://dali.feifeiyinyue.top/Article/details/gtzwevsorc.html

C#:   Task.Run(() => F());
来源：http://dali.hfpthk.cn/Article/details/gtyfbusmex.html

[O02] 使用线程池
来源：http://dali.zhoulong.xyz/Article/details/gtdfjjzyyc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zdqjudy.top/Article/details/gtumlvwfyy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yongpay.top/Article/details/gtsmkvchdn.html

JS:   // worker_threads 线程池
来源：http://dali.zhixingplan.top/Article/details/gtrqjxmwqd.html

TS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gtofxbxjvo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.iojbl.cn/Article/details/gtdgurhnhc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xuanzx.com/Article/details/gthporyyix.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gtiirnvhjx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nanxinkj.top/Article/details/gtmvhkczvl.html

[O03] 加锁保护共享数据
来源：http://dali.redwolf501.top/Article/details/gtfobwboor.html

Py:   with lock: shared += 1
来源：http://dali.redwolf501.top/Article/details/gtzhtsfnlz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cdnleiting.top/Article/details/gtcblbzrwk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.9152youxi.cn/Article/details/gtonfjcudu.html

TS:   // 同 JS
来源：http://dali.yangfankeji.com/Article/details/gtytdlcszl.html

Java: synchronized (this) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gtqppvsnbk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.redwolf501.top/Article/details/gtjtjefhge.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhoulong.xyz/Article/details/gtmnyvckds.html

C#:   lock (gate) { shared++; }
来源：http://dali.yongpay.top/Article/details/gtbmphftus.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gtveecnyur.html

Py:   async def f():⏎    await g()
来源：http://dali.shzxlz.cn/Article/details/gtijyrecua.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gtschlwcdl.html

JS:   async function f() { await g(); }
来源：http://dali.sxryk.cn/Article/details/gtztuffhpe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.wangdashe.top/Article/details/gtfctynoec.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jiagoushi.top/Article/details/gtbvuqrvbh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hysaishi.cn/Article/details/gtptwnllsk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuanzx.com/Article/details/gtyahuggwt.html

C#:   async Task F() { await G(); }
来源：http://dali.gaohongyu789.top/Article/details/gtsatumrmh.html

[O05] 并发执行并等待全部完成
来源：http://dali.dashuyun.cn/Article/details/gtgduemfrk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.iojbl.cn/Article/details/gtshaptmea.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gotoacloud.top/Article/details/gtohrhslwg.html

JS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gttwerunnl.html

TS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtsrdobeos.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.svipenyu.cn/Article/details/gtpwjpqmwn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xinyue.icu/Article/details/gtfdyvvcjh.html

Ruby: threads.map(&:join)
来源：http://dali.gotoacloud.top/Article/details/gtamqxvezk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigufen.top/Article/details/gtrdiphtqj.html

[O06] 使用进程池
来源：http://dali.hnxiangtu.top/Article/details/gtcvwjymyh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylxblhdq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhiwuduotai.top/Article/details/gtjqcoxhal.html

JS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gtrnlpqiky.html

TS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gtjuvclhvl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shuidangran.top/Article/details/gtyxxavnep.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ybcxt.top/Article/details/gtmotkkhex.html

Ruby: // fork 块
来源：http://dali.snrcjt.cn/Article/details/gtvyunwvbq.html

C#:   Parallel.For
来源：http://dali.andypj.xyz/Article/details/gtsuwilsms.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtlmuviqon.html

P. 常用工具函数
来源：http://dali.zhixingplan.top/Article/details/gtkkzbrrkw.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqokgkioi.html

[P01] 生成 UUID
来源：http://dali.c1oappe.top/Article/details/gtwumfgfmh.html

Py:   str(uuid.uuid4())
来源：http://dali.fengsongda.top/Article/details/gtoppsvdfi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.dianchejie.cn/Article/details/gtmnxktovj.html

JS:   crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwvadbkk.html

TS:   crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gtsmdlhira.html

Java: UUID.randomUUID().toString()
来源：http://dali.xinyue.icu/Article/details/gtxepnbkke.html

Go:   // 用 github.com/google/uuid
来源：http://dali.wangshuangyany.cn/Article/details/gtqkgsucze.html

Ruby: SecureRandom.uuid
来源：http://dali.fzhhl.top/Article/details/gtuduhiodb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.haohaochexian.top/Article/details/gtrjqdngjy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hongshengwenyu.top/Article/details/gtfsqsnfow.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gzhubu.top/Article/details/gtgqkzpxcw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sufxvd.cn/Article/details/gtxcnoxcuq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.9152youxi.cn/Article/details/gtobhdifck.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yangfankeji.com/Article/details/gtzjrujvsp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xinyue.icu/Article/details/gtwdyepmsg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.svipenyu.cn/Article/details/gtqfnshtaz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuanzx.com/Article/details/gtexmhlvdw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xziqi.cn/Article/details/gtprcohmhf.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gtonfoqvim.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gogol.net.cn/Article/details/gtzunwgzck.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.316326.xyz/Article/details/gtbarthodg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jyoumei.cn/Article/details/gtbqlcflzl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cheryme.top/Article/details/gttpnencrr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ppjwa.cn/Article/details/gtxgnkkemi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.havefunace.top/Article/details/gtvvraywda.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yuanzhike.top/Article/details/gtcctjmyzf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yueranfly.top/Article/details/gtmpdzijzp.html

[P04] 求长度
来源：http://dali.ehwqpu.com/Article/details/gtrkyvrnfv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yanxiufei.cn/Article/details/gttwqnwzzh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtovqylblk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gtopeunntt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yueranfly.top/Article/details/gtcywpcqpy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhoulong.xyz/Article/details/gtardlaziv.html

Go:   len(arr);  len(m)
来源：http://dali.bjfxy.top/Article/details/gtmvurpgpc.html

Ruby: x.length;  x.size
来源：http://dali.hammf.cn/Article/details/gtplpkojxg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.wangdashe.top/Article/details/gtutefxjqn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zdqjudy.top/Article/details/gthhdcfsny.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zycfv.cn/Article/details/gtbwrzhqkx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daria6918.cn/Article/details/gtbhtkonsn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.9152youxi.cn/Article/details/gthihfktsd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrmxeimm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhengqikj.top/Article/details/gtcyexouxm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shuidangran.top/Article/details/gtzxvtmjxm.html

Ruby: a == b
来源：http://dali.yj202588.top/Article/details/gtucsyhavk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdrhreoi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.quarkkingdee.top/Article/details/gtcgbwaazm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hywenlv.cn/Article/details/gtsezoycij.html

PHP:  if (empty($x)) {}
来源：http://dali.yvedp.cn/Article/details/gtcwnebwwf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxuanxn.top/Article/details/gtvqtsqfdj.html

TS:   if (x == null) {}
来源：http://dali.fzhhl.top/Article/details/gtpavcfpzy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gtezdrvcjv.html

Go:   if x == nil {}
来源：http://dali.jyoumei.cn/Article/details/gtramywajy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hongshengwenyu.top/Article/details/gtgumnktrr.html

C#:   if (x is null) {}
来源：http://dali.ppjwa.cn/Article/details/gtjofpzdub.html

[P07] 防抖与节流
来源：http://dali.sufxvd.cn/Article/details/gtepdfbszg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hfpthk.cn/Article/details/gtlrqwqtfd.html

PHP:  // 手写时间戳比较
来源：http://dali.shzxlz.cn/Article/details/gtujdvklpt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gtyredqata.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gttmabewpp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ydzc1.top/Article/details/gtnygfqism.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigufen.top/Article/details/gtshqutzrr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.aibaodan.cn/Article/details/gtcrbcnonv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdyhvdjci.html

[P08] 处理浮点精度问题
来源：http://dali.hfpthk.cn/Article/details/gtojlndnwv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.0kj1m.cn/Article/details/gtiicuwjan.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yanxiufei.cn/Article/details/gtcpyhzcrf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.mhx1999.top/Article/details/gtokgjowqv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cdnleiting.top/Article/details/gtidkwckmd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yanxiufei.cn/Article/details/gtolayukts.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hammf.cn/Article/details/gtoomazslj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.pycfn.com/Article/details/gtujyopehk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.aizwys.cn/Article/details/gtgutrckzz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtppugodbz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.svipenyu.cn/Article/details/gtsqrfykps.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtuqqpoakf.html

[Q01] 创建表
来源：http://dali.jinqigufen.top/Article/details/gtpsgduwje.html

CREATE TABLE users (
来源：http://dali.chenjidiqi.icu/Article/details/gthfmvnwqo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuanzx.com/Article/details/gtsvcabhzr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yonumen.top/Article/details/gtgxwougws.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigfzy.top/Article/details/gtwqqnvoxq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ivvv.top/Article/details/gtlyjuchlg.html

);
来源：http://dali.zycfv.cn/Article/details/gtxctvyzfj.html

[Q02] 创建带外键的表
来源：http://dali.yvedp.cn/Article/details/gtcsywrelz.html

CREATE TABLE orders (
来源：http://dali.nanxuanxn.top/Article/details/gtcphinoeo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tanke756.top/Article/details/gtrwxzynpf.html

user_id INT NOT NULL,
来源：http://dali.hysaishi.cn/Article/details/gtkldfgtfi.html

amount DECIMAL(10, 2),
来源：http://dali.gogol.net.cn/Article/details/gtvwvnhses.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhengqikj.top/Article/details/gtaycdqwzy.html

);
来源：http://dali.jiagoushi.top/Article/details/gtikkduqiw.html

[Q03] 增加列
来源：http://dali.zycfv.cn/Article/details/gtudeqrpez.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.aibaodan.cn/Article/details/gtwebiozez.html

[Q04] 修改列类型
来源：http://dali.hnqzz.top/Article/details/gtivxbhrlv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gtldzzcudt.html

[Q05] 重命名列
来源：http://dali.chenjidiqi.icu/Article/details/gtekccanft.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigufen.top/Article/details/gtskolvfge.html

[Q06] 删除列
来源：http://dali.havefunace.top/Article/details/gtqzlaodrh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttaqxxavv.html

[Q07] 删除表
来源：http://dali.jqgufenzy.top/Article/details/gtkznylcnu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tian-w.cn/Article/details/gtjbffrqxo.html

[Q08] 创建普通索引
来源：http://dali.jinqigufen.top/Article/details/gtuxroxubk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nwbrower.top/Article/details/gtxjmognck.html

[Q09] 创建唯一索引
来源：http://dali.shzxlz.cn/Article/details/gttdgmkdse.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gtfmvgazfe.html

[Q10] 插入单行
来源：http://dali.zdqjudy.top/Article/details/gtwmyccmli.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ydzc1.top/Article/details/gtxhclactk.html

[Q11] 一次插入多行
来源：http://dali.shuidangran.top/Article/details/gtoxhzivko.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhixingplan.top/Article/details/gtwhweyvza.html

[Q12] 插入后取自增 ID
来源：http://dali.svipenyu.cn/Article/details/gtdpdnfkxx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhiwuduotai.top/Article/details/gtvlybnpnb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.bjfxy.top/Article/details/gtbplqrmzp.html

[Q13] 忽略重复插入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtteenzssb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tanke756.top/Article/details/gtzstxobwe.html

[Q14] 存在则更新（upsert）
来源：http://dali.yangfankeji.com/Article/details/gtvugrpipx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cqqwz.cn/Article/details/gtedmnyvff.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hammf.cn/Article/details/gtzxyrzced.html

[Q15] 查询全部
来源：http://dali.yuanzhike.top/Article/details/gtqkhlinps.html

SELECT * FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtkcaneonh.html

[Q16] 查询指定列
来源：http://dali.jyoumei.cn/Article/details/gtxmelszej.html

SELECT id, name FROM users;
来源：http://dali.wangdashe.top/Article/details/gtdjgswgqg.html

[Q17] 条件查询
来源：http://dali.cucudq.cn/Article/details/gttcrviwrh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tianlin.xyz/Article/details/gtxnokutzx.html

[Q18] 模糊匹配
来源：http://dali.jyoumei.cn/Article/details/gthecrqdex.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.iojbl.cn/Article/details/gtsdjytzfy.html

[Q19] 范围查询
来源：http://dali.mhx1999.top/Article/details/gtiqsxsjpl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sufxvd.cn/Article/details/gtpxujlnme.html

[Q20] IN 列表
来源：http://dali.dianchejie.cn/Article/details/gtrnmbwaos.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ydzc1.top/Article/details/gttonvzsmy.html

[Q21] 空值判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxdzbimvm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzaglcyhm.html

[Q22] 排序
来源：http://dali.sufxvd.cn/Article/details/gtyamfwlgl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ehwqpu.com/Article/details/gtkvibmigi.html

[Q23] 分页
来源：http://dali.gotoacloud.top/Article/details/gtfwchneac.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nanxinkj.top/Article/details/gtfgfefnry.html

[Q24] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsyhgiei.html

SELECT DISTINCT city FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtuxbturit.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvjlcxyc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shanyushiyangtech.top/Article/details/gtdeguvnhm.html

[Q26] 计数
来源：http://dali.xylfe.cn/Article/details/gtkwnpxodm.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj202588.top/Article/details/gtpqvsnitu.html

[Q27] 条件计数
来源：http://dali.zhongyouzk.top/Article/details/gthrozhscl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aizwys.cn/Article/details/gthfzkbihm.html

[Q28] 求和与平均
来源：http://dali.fzhhl.top/Article/details/gtezsusokk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sweek.top/Article/details/gtbysiajqj.html

[Q29] 最大最小值
来源：http://dali.cucudq.cn/Article/details/gtkufewwgp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tanke756.top/Article/details/gtxfdtzuwt.html

[Q30] 分组统计
来源：http://dali.svipenyu.cn/Article/details/gtxbbrkhhl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtoqmhcxje.html

[Q31] 分组后过滤
来源：http://dali.jinqigufen.top/Article/details/gtbljqwktd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.andypj.xyz/Article/details/gtelobmbog.html

[Q32] 分组拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgvykkke.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtyzcgjgpc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.havefunace.top/Article/details/gtmvpwbfvn.html

[Q33] 多列分组
来源：http://dali.iojbl.cn/Article/details/gtloycjbon.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sweek.top/Article/details/gtvfncczow.html

[Q34] 每组取第一条
来源：http://dali.haohaochexian.top/Article/details/gtlcuzuoxf.html

SELECT * FROM (
来源：http://dali.dashuyun.cn/Article/details/gtiszqfysh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yueranfly.top/Article/details/gtdyzzfigs.html

) t WHERE rn = 1;
来源：http://dali.xuanzx.com/Article/details/gtgmhmoxzl.html

[Q35] 内连接
来源：http://dali.dianchejie.cn/Article/details/gtjmvisbdo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgfzy.top/Article/details/gtncvyrwci.html

[Q36] 左连接
来源：http://dali.gogol.net.cn/Article/details/gtaprrssuj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gtennbjdbs.html

[Q37] 右连接
来源：http://dali.jqgfzy.top/Article/details/gtgaqhqhjs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yvedp.cn/Article/details/gtvgjydaem.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cheryme.top/Article/details/gteyihazge.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxuanxn.top/Article/details/gtqijrzdas.html

[Q39] 自连接（查上下级）
来源：http://dali.316326.xyz/Article/details/gttgtpfeea.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yonumen.top/Article/details/gthzmzgjmh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aizwys.cn/Article/details/gtsqazlslm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenjidiqi.icu/Article/details/gtdkwzocrj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.mhx1999.top/Article/details/gtruvgpaiw.html

[Q41] 多表连接
来源：http://dali.nanxinkj.top/Article/details/gtklrslden.html


<!-- 参考信息 -->