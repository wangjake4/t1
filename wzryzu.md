代发 wailian999

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gtvoljhdol.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnqzz.top/Article/details/gtgxdlnuko.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gtakwnrenm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gtlalfutrt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gtkmaycsmq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.0kj1m.cn/Article/details/gtsksxzvme.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbplkzum.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sweek.top/Article/details/gtmcuhikfj.html

[N05] 最大公约数
来源：http://dali.chenzaomai.com/Article/details/gtdjnshqrp.html

Py:   math.gcd(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtgckjkgrl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gotoacloud.top/Article/details/gtkouvtlig.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.smart0.xyz/Article/details/gtuwpnpjgf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fzhhl.top/Article/details/gtsqzuecyp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.mhx1999.top/Article/details/gtkjjchemn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnqzz.top/Article/details/gttwnaksbs.html

Ruby: a.gcd(b)
来源：http://dali.ydzc1.top/Article/details/gtcoyoffwj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteatutsvl.html

[N06] 判断回文字符串
来源：http://dali.dianchejie.cn/Article/details/gtyemzdrcm.html

Py:   s == s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gtiyfknsci.html

PHP:  $s === strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtmlfppthi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtcwkqsqzj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtctvjpkxy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.c1oappe.top/Article/details/gtorajmmdg.html

Go:   // 双指针从两端比较
来源：http://dali.nwbrower.top/Article/details/gtyldkywzl.html

Ruby: s == s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtafrmrbzb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gtstfnalsc.html

[N07] 两数之和（返回下标）
来源：http://dali.gaohongyu789.top/Article/details/gtyhumegfx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xziqi.cn/Article/details/gtkmnfkiov.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gogol.net.cn/Article/details/gtaqktbjkx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ivvv.top/Article/details/gtzzsqzhup.html

TS:   // 手写 Map<string, number>
来源：http://dali.shuidangran.top/Article/details/gtajkmhxfe.html

Java: // 手写 HashMap
来源：http://dali.nanxuanxn.top/Article/details/gtwpwahyzl.html

Go:   // 手写 map[int]int
来源：http://dali.yuanzhike.top/Article/details/gtfphwaplz.html

Ruby: // 手写 Hash
来源：http://dali.jqgufenzy.top/Article/details/gtdbarofie.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.havefunace.top/Article/details/gtjqfaccvb.html

[N08] 生成全排列
来源：http://dali.zhongyouzk.top/Article/details/gtlcrfglvc.html

Py:   itertools.permutations(arr)
来源：http://dali.xinyue.icu/Article/details/gtvfarvnwm.html

PHP:  // 手写递归交换
来源：http://dali.jiagoushi.top/Article/details/gtsvwqopsv.html

JS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtyoauqstq.html

TS:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtbddyyegv.html

Java: // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmhaouba.html

Go:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtwowsywoa.html

Ruby: arr.permutation.to_a
来源：http://dali.xinyue.icu/Article/details/gtfbsuxeji.html

C#:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtlbnulsky.html

[N09] 栈与队列
来源：http://dali.birdmap.top/Article/details/gtspvfuyaw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cucudq.cn/Article/details/gtvihupsvm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gtwhqykkfw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwojpzaf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shzxlz.cn/Article/details/gtesylzaxu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yvedp.cn/Article/details/gtrsfyzslw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sysykeji.top/Article/details/gtdrwwpjpn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtwanrfqbx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gtjrpreypa.html

[N10] 链表节点定义
来源：http://dali.pengpengdd.cyou/Article/details/gtnykjwypc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daxiang520.top/Article/details/gtqccxwxmp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ppjwa.cn/Article/details/gtxruawgds.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cqqwz.cn/Article/details/gtjiozjirl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shuidangran.top/Article/details/gtmgggxwtb.html

Java: class Node { int v; Node next; }
来源：http://dali.ybcxt.top/Article/details/gtiaumtths.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pengpengdd.cyou/Article/details/gtywhghakl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgufenzy.top/Article/details/gtjbbgnpga.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ivvv.top/Article/details/gtkeayyyev.html

[N11] 二叉树中序遍历
来源：http://dali.ydzc1.top/Article/details/gtfczqswqk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigfzy.top/Article/details/gtjkzgowiu.html

PHP:  // 手写递归函数
来源：http://dali.yueranfly.top/Article/details/gteehcjftc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtejdwxnlg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gtbfuuabau.html

Java: // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gtdgdvltvm.html

Go:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtikzqsfde.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ehwqpu.com/Article/details/gtlsfspttk.html

C#:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gttkvxdefu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.guannengcc.top/Article/details/gtzhprjfih.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ydzc1.top/Article/details/gtrslzotvr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.birdmap.top/Article/details/gtoamsbbbp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gtlnmenbgh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gtjmggjrky.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gtdbccwvay.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dianchejie.cn/Article/details/gtumakvbdh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gtvvqcqbra.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hfpthk.cn/Article/details/gttiniwvab.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtkcrxwqyt.html

O. 并发与异步
来源：http://dali.zdqjudy.top/Article/details/gtqjoulaff.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gttuzvvwnj.html

[O01] 启动一个线程
来源：http://dali.ivvv.top/Article/details/gtuqssxdvs.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zdqjudy.top/Article/details/gtqeikafca.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cdnleiting.top/Article/details/gtsguqivvg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuxming.cn/Article/details/gtgnzbttvx.html

TS:   // 同 JS
来源：http://dali.tian-w.cn/Article/details/gtyfrderqp.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenjidiqi.icu/Article/details/gtkdglbvqt.html

Go:   go f()
来源：http://dali.nanxinkj.top/Article/details/gtsgthcwvr.html

Ruby: Thread.new { f }
来源：http://dali.yangfankeji.com/Article/details/gtwkfkoxxk.html

C#:   Task.Run(() => F());
来源：http://dali.jinghuilouyu.cn/Article/details/gtsaaxlgne.html

[O02] 使用线程池
来源：http://dali.0kj1m.cn/Article/details/gtgiprkynd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aibaodan.cn/Article/details/gtnffnqzho.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ehwqpu.com/Article/details/gteioqcnab.html

JS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gtdesdbdty.html

TS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gtafkttdvi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xinyue.icu/Article/details/gtorbwuzzu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shzxlz.cn/Article/details/gtkitomfzt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cucudq.cn/Article/details/gtbnnwcuen.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tian-w.cn/Article/details/gtgjjeyszd.html

[O03] 加锁保护共享数据
来源：http://dali.hongshengwenyu.top/Article/details/gtqmuhroml.html

Py:   with lock: shared += 1
来源：http://dali.nanxuanxn.top/Article/details/gtotuoyche.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnxiangtu.top/Article/details/gthspzread.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xziqi.cn/Article/details/gtmprfnorg.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gtfhiicmds.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenjidiqi.icu/Article/details/gteqzlavdc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnxiangtu.top/Article/details/gtvfybtsic.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.aibaodan.cn/Article/details/gtdkagikhi.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gturubajsl.html

[O04] 定义异步函数并等待
来源：http://dali.jlsjyb.cn/Article/details/gtgjvvlmhf.html

Py:   async def f():⏎    await g()
来源：http://dali.316326.xyz/Article/details/gtvlypzemc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258.top/Article/details/gtmkfexdql.html

JS:   async function f() { await g(); }
来源：http://dali.cucudq.cn/Article/details/gtbpxpysgw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gtwfiqjtjv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tian-w.cn/Article/details/gtxnrbfskl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jyoumei.cn/Article/details/gtfyjistss.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guowangkeji.top/Article/details/gtukkpjyte.html

C#:   async Task F() { await G(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtcfqwigcb.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuetiantiany.cn/Article/details/gtyywbmwhy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gttdzngjga.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sysykeji.top/Article/details/gtqmkcchmn.html

JS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gtsvpxyyuh.html

TS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gtsymrytve.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuanzx.com/Article/details/gtziqtoheu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sufxvd.cn/Article/details/gtsmtderkw.html

Ruby: threads.map(&:join)
来源：http://dali.sufxvd.cn/Article/details/gtesklafgf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.haohaochexian.top/Article/details/gtqsruiaqm.html

[O06] 使用进程池
来源：http://dali.sxryk.cn/Article/details/gtoqlesldk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.0kj1m.cn/Article/details/gtbepmwnem.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cqqwz.cn/Article/details/gtxmkjvnug.html

JS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gtcsaebxrp.html

TS:   // child_process / cluster 模块
来源：http://dali.smart0.xyz/Article/details/gtqmgaelty.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.redwolf501.top/Article/details/gtvcqttvuj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hnxiangtu.top/Article/details/gtqwnlvzqu.html

Ruby: // fork 块
来源：http://dali.jianghu66.top/Article/details/gtjukngnao.html

C#:   Parallel.For
来源：http://dali.jinghuilouyu.cn/Article/details/gttzgpjknp.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbksagyr.html

P. 常用工具函数
来源：http://dali.fengsongda.top/Article/details/gtxrbqixrz.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknbyvopc.html

[P01] 生成 UUID
来源：http://dali.tianlin.xyz/Article/details/gtytelfpdj.html

Py:   str(uuid.uuid4())
来源：http://dali.aizwys.cn/Article/details/gtlzlzhmkj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtemvrwbjx.html

JS:   crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gtnjxxzxke.html

TS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gtnnddcosp.html

Java: UUID.randomUUID().toString()
来源：http://dali.fzhhl.top/Article/details/gtxjhqxfci.html

Go:   // 用 github.com/google/uuid
来源：http://dali.iojbl.cn/Article/details/gtthdstfsb.html

Ruby: SecureRandom.uuid
来源：http://dali.cdnleiting.top/Article/details/gteqlukqrq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aizwys.cn/Article/details/gtoddkjdaf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hongshengwenyu.top/Article/details/gtoawzavfz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.fengsongda.top/Article/details/gtlvizgwaq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shuidangran.top/Article/details/gtkgtbdkmv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.dianchejie.cn/Article/details/gtzujveevo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dianchejie.cn/Article/details/gtijzjwgkn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtarhhtjvp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ydzc1.top/Article/details/gtqbbcmqjf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hammf.cn/Article/details/gtszgvoouv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yueranfly.top/Article/details/gtmaclhzzk.html

[P03] 生成短随机字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtptaijwjp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenjidiqi.icu/Article/details/gtcalbpgfv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ppjwa.cn/Article/details/gtvdejugxx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ppjwa.cn/Article/details/gtkdmpsand.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gtzafxopzu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gzhubu.top/Article/details/gthxhmmmjh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.redwolf501.top/Article/details/gtklukrgbp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangshuangyany.cn/Article/details/gteotywryu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cucudq.cn/Article/details/gtmlsoiebw.html

[P04] 求长度
来源：http://dali.zhongyouzk.top/Article/details/gtsuyhupwl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangshuangyany.cn/Article/details/gtkzsmhkar.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtdugtdnwi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sweek.top/Article/details/gtqdiveqtf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sxryk.cn/Article/details/gtbcjsdgqs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.daxiang520.top/Article/details/gtnsgwbgbn.html

Go:   len(arr);  len(m)
来源：http://dali.yvedp.cn/Article/details/gtfzuwseld.html

Ruby: x.length;  x.size
来源：http://dali.zhongyouzk.top/Article/details/gtjsycvfzh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jiagoushi.top/Article/details/gtbrtkvdgs.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yonumen.top/Article/details/gticoiqqyk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zycfv.cn/Article/details/gtalgnszfh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ivvv.top/Article/details/gtxouiwokl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yueranfly.top/Article/details/gtaxapwnnb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdkaomwi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgufenzy.top/Article/details/gtszoimthf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.fengsongda.top/Article/details/gtxixvujoq.html

Ruby: a == b
来源：http://dali.chenzaomai.com/Article/details/gtumngaljr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cucudq.cn/Article/details/gtftwinqmy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenlongwang.top/Article/details/gturwrahld.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ivvv.top/Article/details/gttimqflkw.html

PHP:  if (empty($x)) {}
来源：http://dali.chenlongwang.top/Article/details/gtsekjebyw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hywenlv.cn/Article/details/gtoucotegd.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjnxzgwn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gthzstioyx.html

Go:   if x == nil {}
来源：http://dali.havefunace.top/Article/details/gtykwijaby.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.quarkkingdee.top/Article/details/gtemtngwjh.html

C#:   if (x is null) {}
来源：http://dali.havefunace.top/Article/details/gtamuwpxua.html

[P07] 防抖与节流
来源：http://dali.birdmap.top/Article/details/gtkijgakuw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gtcjujhfau.html

PHP:  // 手写时间戳比较
来源：http://dali.sxryk.cn/Article/details/gtnfzdctyd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gtvyznnrtr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yangfankeji.com/Article/details/gtxhsvidhw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cashguo.top/Article/details/gtazsqijcc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.dashuyun.cn/Article/details/gtljmrjdkx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.redwolf501.top/Article/details/gtssrnuzsy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.kuanghao11.cn/Article/details/gtjcvaoesp.html

[P08] 处理浮点精度问题
来源：http://dali.316326.xyz/Article/details/gtkqptfsvq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtwmzsjn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dianchejie.cn/Article/details/gtekbtpoav.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ydzc1.top/Article/details/gtjcuqbics.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sufxvd.cn/Article/details/gtjpbabssc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangdashe.top/Article/details/gtbhmngukb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.redwolf501.top/Article/details/gtzummlrws.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xylfe.cn/Article/details/gtyvxlljbi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hongshengwenyu.top/Article/details/gtucodygam.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtynbodrym.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xuanzx.com/Article/details/gtrdueqaev.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtcwvlnxda.html

[Q01] 创建表
来源：http://dali.yj20258888.top/Article/details/gtmkpdyytg.html

CREATE TABLE users (
来源：http://dali.kuanghao11.cn/Article/details/gtmgdrsgpd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xinyue.icu/Article/details/gtaposdghw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gtkbdmxcvl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.dashuyun.cn/Article/details/gtlhwgfypa.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangdashe.top/Article/details/gtqlyxngck.html

);
来源：http://dali.aibaodan.cn/Article/details/gtogkjqcgb.html

[Q02] 创建带外键的表
来源：http://dali.0kj1m.cn/Article/details/gtuteedtub.html

CREATE TABLE orders (
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmiqsakpw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yongpay.top/Article/details/gtadhbztlv.html

user_id INT NOT NULL,
来源：http://dali.sxryk.cn/Article/details/gtsfnhtsai.html

amount DECIMAL(10, 2),
来源：http://dali.zycfv.cn/Article/details/gtexkefhlo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxuanxn.top/Article/details/gtlaynoaoh.html

);
来源：http://dali.haohaochexian.top/Article/details/gtmjiypsmc.html

[Q03] 增加列
来源：http://dali.nanxinkj.top/Article/details/gtfnmvtpxd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cqqwz.cn/Article/details/gtebgobana.html

[Q04] 修改列类型
来源：http://dali.hywenlv.cn/Article/details/gttdxpmevx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwhrqqgj.html

[Q05] 重命名列
来源：http://dali.cashguo.top/Article/details/gtbquxbzxn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gaohongyu789.top/Article/details/gtjfiixlkr.html

[Q06] 删除列
来源：http://dali.shuidangran.top/Article/details/gtcfbifbxl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hysaishi.cn/Article/details/gthywiytkr.html

[Q07] 删除表
来源：http://dali.ppjwa.cn/Article/details/gtlayzjuwt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtuoyyopvm.html

[Q08] 创建普通索引
来源：http://dali.meibo888.top/Article/details/gtafrotfqa.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gtocnalxau.html

[Q09] 创建唯一索引
来源：http://dali.yuxming.cn/Article/details/gtsxhzjyjl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gtgsgrfrgm.html

[Q10] 插入单行
来源：http://dali.jianghu66.top/Article/details/gthxlnnbis.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.smart0.xyz/Article/details/gtesprglsq.html

[Q11] 一次插入多行
来源：http://dali.yvedp.cn/Article/details/gtsnuazkfv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zycfv.cn/Article/details/gtaoohuntc.html

[Q12] 插入后取自增 ID
来源：http://dali.316326.xyz/Article/details/gtylxjmyzk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.9152youxi.cn/Article/details/gthxflgqqk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cqqwz.cn/Article/details/gtaxcyioul.html

[Q13] 忽略重复插入
来源：http://dali.snrcjt.cn/Article/details/gtqpzamndw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tian-w.cn/Article/details/gtkhxiasuh.html

[Q14] 存在则更新（upsert）
来源：http://dali.jianghu66.top/Article/details/gtpajvcmda.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.quarkkingdee.top/Article/details/gtytofmxjf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.kuanghao11.cn/Article/details/gtniwebeis.html

[Q15] 查询全部
来源：http://dali.jlsjyb.cn/Article/details/gtsrxkeaso.html

SELECT * FROM users;
来源：http://dali.yj20258888.top/Article/details/gtxmwnyfhx.html

[Q16] 查询指定列
来源：http://dali.nwbrower.top/Article/details/gtmaillzjs.html

SELECT id, name FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtwpnmpbix.html

[Q17] 条件查询
来源：http://dali.shzxlz.cn/Article/details/gtwnewifuw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guannengcc.top/Article/details/gtchfmlvts.html

[Q18] 模糊匹配
来源：http://dali.cashguo.top/Article/details/gtilzachdx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.vqdsnc.cn/Article/details/gtpkeqgrxg.html

[Q19] 范围查询
来源：http://dali.jinqigfzy.top/Article/details/gtljhlpits.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fzhhl.top/Article/details/gtngacbivh.html

[Q20] IN 列表
来源：http://dali.jiagoushi.top/Article/details/gtlqoebjsd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cashguo.top/Article/details/gtmcjgzwtk.html

[Q21] 空值判断
来源：http://dali.yueranfly.top/Article/details/gtytlhfciq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhongyouzk.top/Article/details/gtmqxumbbc.html

[Q22] 排序
来源：http://dali.hnxiangtu.top/Article/details/gtbouehcep.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hfpthk.cn/Article/details/gthiumxtzv.html

[Q23] 分页
来源：http://dali.andypj.xyz/Article/details/gttimzxwvo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nanxuanxn.top/Article/details/gtcsdgqecj.html

[Q24] 去重
来源：http://dali.jyoumei.cn/Article/details/gtnmcpryql.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtnusjkiej.html

[Q25] 只取前 N 条
来源：http://dali.guannengcc.top/Article/details/gtlyfqxlaw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gzhubu.top/Article/details/gtgvvhcqbo.html

[Q26] 计数
来源：http://dali.havefunace.top/Article/details/gtgsrhuoai.html

SELECT COUNT(*) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtsfozcsjo.html

[Q27] 条件计数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsborvgjh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sxryk.cn/Article/details/gtlepcvlrh.html

[Q28] 求和与平均
来源：http://dali.hfpthk.cn/Article/details/gtzozjaysq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgzcitxx.html

[Q29] 最大最小值
来源：http://dali.hongshengwenyu.top/Article/details/gtbxvwahmr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtfietvumm.html

[Q30] 分组统计
来源：http://dali.sweek.top/Article/details/gtvlrtagwh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gtlgdsxmpl.html

[Q31] 分组后过滤
来源：http://dali.yj20258.top/Article/details/gttyflffqc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhixingplan.top/Article/details/gtxzwrtxxz.html

[Q32] 分组拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtpueibvdj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcienybhb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzzexlge.html

[Q33] 多列分组
来源：http://dali.snrcjt.cn/Article/details/gterhwmvzu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.andypj.xyz/Article/details/gtdzuprucr.html

[Q34] 每组取第一条
来源：http://dali.wangdashe.top/Article/details/gtqktjevri.html

SELECT * FROM (
来源：http://dali.nwbrower.top/Article/details/gttxqqchvn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yongpay.top/Article/details/gtuntkwuqi.html

) t WHERE rn = 1;
来源：http://dali.shzxlz.cn/Article/details/gtjtmxkvil.html

[Q35] 内连接
来源：http://dali.zhixingplan.top/Article/details/gtbyseypno.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gtootweplz.html


<!-- 参考信息 -->