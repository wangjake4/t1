代发 wailian999

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gtpwkymypk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenjidiqi.icu/Article/details/gtmrrvifux.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gtzayumpqq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtblumzxfw.html

[N05] 最大公约数
来源：http://dali.yj202588.top/Article/details/gtijgjluzx.html

Py:   math.gcd(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gtriehftll.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.haohaochexian.top/Article/details/gtkfevkvxh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.smart0.xyz/Article/details/gtxcjanhnn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aibaodan.cn/Article/details/gtnvbtvigf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvcdjffs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenjidiqi.icu/Article/details/gtklrhkzia.html

Ruby: a.gcd(b)
来源：http://dali.gotoacloud.top/Article/details/gtkvowzbhk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daxiang520.top/Article/details/gtrvgzdsui.html

[N06] 判断回文字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtqsvxecty.html

Py:   s == s[::-1]
来源：http://dali.cheryme.top/Article/details/gthymutpla.html

PHP:  $s === strrev($s);
来源：http://dali.meibo888.top/Article/details/gtargxwmwt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtfxbbqesn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtqwsvogcr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.redwolf501.top/Article/details/gtziqjvcan.html

Go:   // 双指针从两端比较
来源：http://dali.jinqigufen.top/Article/details/gtxngnankp.html

Ruby: s == s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdntatgbn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gttojvqavm.html

[N07] 两数之和（返回下标）
来源：http://dali.jyoumei.cn/Article/details/gteqqxlbsb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ybcxt.top/Article/details/gtqyqpycwp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hammf.cn/Article/details/gtqcmvwajq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xuetiantiany.cn/Article/details/gtsfhlbtaz.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxuanxn.top/Article/details/gtuhsrxgyf.html

Java: // 手写 HashMap
来源：http://dali.yanxiufei.cn/Article/details/gtaiqublub.html

Go:   // 手写 map[int]int
来源：http://dali.iojbl.cn/Article/details/gtxlcvjdiw.html

Ruby: // 手写 Hash
来源：http://dali.zdqjudy.top/Article/details/gtkulapigz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhiwuduotai.top/Article/details/gtbygyhyev.html

[N08] 生成全排列
来源：http://dali.gotoacloud.top/Article/details/gtlfekzovz.html

Py:   itertools.permutations(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthisnbxqm.html

PHP:  // 手写递归交换
来源：http://dali.yanxiufei.cn/Article/details/gtlxdamwcq.html

JS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqjkxicu.html

TS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtbujknqtw.html

Java: // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtkkcblyuq.html

Go:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtdhtxqdmu.html

Ruby: arr.permutation.to_a
来源：http://dali.haohaochexian.top/Article/details/gtajqlprhe.html

C#:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtluuwrisj.html

[N09] 栈与队列
来源：http://dali.chenzaomai.com/Article/details/gtvdipachc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ydzc1.top/Article/details/gtxznxerhw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtwnlxafkk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gtfsfmghtn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cucudq.cn/Article/details/gtgdinrzmp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daria6918.cn/Article/details/gtzslqxscu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aizwys.cn/Article/details/gtkisrrosn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gthuwmkuwn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhoulong.xyz/Article/details/gtavvocygq.html

[N10] 链表节点定义
来源：http://dali.xziqi.cn/Article/details/gtybhiyxiq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nanxuanxn.top/Article/details/gtlfaenbgh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhengqikj.top/Article/details/gtxxatuuem.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrygbdwvg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.smart0.xyz/Article/details/gtvwshmsjz.html

Java: class Node { int v; Node next; }
来源：http://dali.bjfxy.top/Article/details/gtzcrlcysx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hnqzz.top/Article/details/gtuteyxbhv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuxming.cn/Article/details/gtoovxtdbt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tanke756.top/Article/details/gtmoeiluap.html

[N11] 二叉树中序遍历
来源：http://dali.nanxuanxn.top/Article/details/gthzqghzsl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuanzx.com/Article/details/gtlhdttrdu.html

PHP:  // 手写递归函数
来源：http://dali.xinyue.icu/Article/details/gtpzkmvyyf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gtfyqocguw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gthkkabdyq.html

Java: // 手写递归
来源：http://dali.yongpay.top/Article/details/gtanlnztji.html

Go:   // 手写递归
来源：http://dali.nwbrower.top/Article/details/gtqrijpatn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbigdyqcg.html

C#:   // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gtwtcnshbr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sysykeji.top/Article/details/gtmhuqdudc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gogol.net.cn/Article/details/gtkrzxgdvr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj20258888.top/Article/details/gtqwwdprkw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gthebwiaet.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cucudq.cn/Article/details/gtwputudzj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfgveelr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tian-w.cn/Article/details/gtsvvqapad.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jiagoushi.top/Article/details/gthognjoup.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gtarrcmopj.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtfgpwwzyk.html

O. 并发与异步
来源：http://dali.9152youxi.cn/Article/details/gtcuandkwu.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtgynlzdve.html

[O01] 启动一个线程
来源：http://dali.ehwqpu.com/Article/details/gtpcodebgy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aibaodan.cn/Article/details/gtmxbjpjib.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xziqi.cn/Article/details/gtgotyedlw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ydzc1.top/Article/details/gtgorloesl.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gteajoyuqi.html

Java: new Thread(() -> f()).start()
来源：http://dali.c1oappe.top/Article/details/gttfznyoty.html

Go:   go f()
来源：http://dali.tianlin.xyz/Article/details/gtjqgtzxgj.html

Ruby: Thread.new { f }
来源：http://dali.yanxiufei.cn/Article/details/gtdhlckpoh.html

C#:   Task.Run(() => F());
来源：http://dali.pycfn.com/Article/details/gtvgpvwdpl.html

[O02] 使用线程池
来源：http://dali.tanke756.top/Article/details/gtwcdqhtve.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigfzy.top/Article/details/gtjgyidhps.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.pengpengdd.cyou/Article/details/gtzmnakklv.html

JS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gtmrbpjtbc.html

TS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gtxihjbnbt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yonumen.top/Article/details/gtkwntxolf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.kuanghao11.cn/Article/details/gtomaqbbji.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nanxinkj.top/Article/details/gtpizvqmzn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gogol.net.cn/Article/details/gtxgchwcgn.html

[O03] 加锁保护共享数据
来源：http://dali.zycfv.cn/Article/details/gtouocefwj.html

Py:   with lock: shared += 1
来源：http://dali.bjfxy.top/Article/details/gtbwcopvct.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pengpengdd.cyou/Article/details/gtpnonptqf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hammf.cn/Article/details/gtnsjlzxrb.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gtaulwelie.html

Java: synchronized (this) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gtedmkztci.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cucudq.cn/Article/details/gtgwefzbxk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gaohongyu789.top/Article/details/gthwpkkrqu.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnxiangtu.top/Article/details/gtqzduzygz.html

[O04] 定义异步函数并等待
来源：http://dali.ydzc1.top/Article/details/gtfmmtthkd.html

Py:   async def f():⏎    await g()
来源：http://dali.gaohongyu789.top/Article/details/gtwdklaazk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tanke756.top/Article/details/gtybgifaim.html

JS:   async function f() { await g(); }
来源：http://dali.gzhubu.top/Article/details/gtsscpyxmp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlldybwbr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangkeji.top/Article/details/gthswfmoga.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.iojbl.cn/Article/details/gtrktjdsld.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigfzy.top/Article/details/gtzmbkwzvx.html

C#:   async Task F() { await G(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtkkmipptd.html

[O05] 并发执行并等待全部完成
来源：http://dali.bjfxy.top/Article/details/gtfrpdwjno.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhengqikj.top/Article/details/gtamhovxhf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dashuyun.cn/Article/details/gtfxthkryy.html

JS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gtjavxetyi.html

TS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtihddvlps.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzjslrly.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.c1oappe.top/Article/details/gtciucxcer.html

Ruby: threads.map(&:join)
来源：http://dali.pycfn.com/Article/details/gtwybiauwr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gotoacloud.top/Article/details/gtmxnqyeew.html

[O06] 使用进程池
来源：http://dali.wangshuangyany.cn/Article/details/gtyrqwzcnl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ehwqpu.com/Article/details/gtfzwsxxry.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.redwolf501.top/Article/details/gtjheuawnl.html

JS:   // child_process / cluster 模块
来源：http://dali.aibaodan.cn/Article/details/gtfogksspl.html

TS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gtiurtkhcw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuanzhike.top/Article/details/gtawlqwwic.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cucudq.cn/Article/details/gthvfgtvua.html

Ruby: // fork 块
来源：http://dali.hammf.cn/Article/details/gtxzskbxpm.html

C#:   Parallel.For
来源：http://dali.svipenyu.cn/Article/details/gtvwirquyz.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtzkohigsk.html

P. 常用工具函数
来源：http://dali.feifeiyinyue.top/Article/details/gtpwpuifzr.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtjpiedbqf.html

[P01] 生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gtrfcwpxlt.html

Py:   str(uuid.uuid4())
来源：http://dali.yanxiufei.cn/Article/details/gtolcriprj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gogol.net.cn/Article/details/gtfyxmjjhh.html

JS:   crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gtdtscyxmy.html

TS:   crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gtgrghxtfw.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gtjvwhnbqt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tian-w.cn/Article/details/gtqlkmozbl.html

Ruby: SecureRandom.uuid
来源：http://dali.gaohongyu789.top/Article/details/gtkyuvigvd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258888.top/Article/details/gtaouwnzop.html

[P02] MD5 / SHA256 摘要
来源：http://dali.smart0.xyz/Article/details/gtapzzqeur.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hnxiangtu.top/Article/details/gtmengcqti.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudxhsyon.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yonumen.top/Article/details/gtdvsusjpr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gogol.net.cn/Article/details/gtbdqapdoy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.316326.xyz/Article/details/gtwsxxypzi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hnqzz.top/Article/details/gthtcbpjoi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.316326.xyz/Article/details/gtycurwjws.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zycfv.cn/Article/details/gttkiygjvc.html

[P03] 生成短随机字符串
来源：http://dali.nwbrower.top/Article/details/gtpbuefdnf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gtfwxeqfxg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hfpthk.cn/Article/details/gtizhyguky.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gtiwdcwczg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hysaishi.cn/Article/details/gtfywzvpvb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sysykeji.top/Article/details/gtiytxzytx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.havefunace.top/Article/details/gtyexjdnca.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxuanxn.top/Article/details/gtyhmzdvnr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspmjcqfr.html

[P04] 求长度
来源：http://dali.hongshengwenyu.top/Article/details/gtovkmubgy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.mhx1999.top/Article/details/gtbbqgsrxk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtmfadbgol.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenzaomai.com/Article/details/gtlkzrmvlx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gtvslxwirn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgfzy.top/Article/details/gtrohuwfru.html

Go:   len(arr);  len(m)
来源：http://dali.ppjwa.cn/Article/details/gtzrbonjvf.html

Ruby: x.length;  x.size
来源：http://dali.snrcjt.cn/Article/details/gtqnyyynjc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.redwolf501.top/Article/details/gtzwylvsmh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ivvv.top/Article/details/gtmtarihdu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shuidangran.top/Article/details/gtxbhgwxsn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dashuyun.cn/Article/details/gtaymbgfql.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daria6918.cn/Article/details/gtrthoaqyh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tianlin.xyz/Article/details/gtcqydhcts.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nanxuanxn.top/Article/details/gtpznadele.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhengqikj.top/Article/details/gttorsbous.html

Ruby: a == b
来源：http://dali.gaohongyu789.top/Article/details/gtywaeibyi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sysykeji.top/Article/details/gtdkzoirur.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.snrcjt.cn/Article/details/gtrwcobfqw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jyoumei.cn/Article/details/gtnmqruriq.html

PHP:  if (empty($x)) {}
来源：http://dali.cqqwz.cn/Article/details/gtmrtgndzx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hfpthk.cn/Article/details/gtfpezvfzx.html

TS:   if (x == null) {}
来源：http://dali.guowangkeji.top/Article/details/gtobefpcbw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtchbmvdje.html

Go:   if x == nil {}
来源：http://dali.yanxiufei.cn/Article/details/gtlypoldni.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.svipenyu.cn/Article/details/gtjilmuxqd.html

C#:   if (x is null) {}
来源：http://dali.ivvv.top/Article/details/gtoxdnthpy.html

[P07] 防抖与节流
来源：http://dali.0kj1m.cn/Article/details/gthfoblmlt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yvedp.cn/Article/details/gtrobczzsu.html

PHP:  // 手写时间戳比较
来源：http://dali.yvedp.cn/Article/details/gtfydyobhf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtvpsjib.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gtuwzpfufg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sufxvd.cn/Article/details/gtmztwpjmy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tian-w.cn/Article/details/gtdekpdnam.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nwbrower.top/Article/details/gtvrmojboe.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.9152youxi.cn/Article/details/gtgykrpzoi.html

[P08] 处理浮点精度问题
来源：http://dali.fengsongda.top/Article/details/gtkfbrazwy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenzaomai.com/Article/details/gtclddmugc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.redwolf501.top/Article/details/gtoqmgdbwe.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jianghu66.top/Article/details/gtvposbdry.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gtgpwccrjw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhongyouzk.top/Article/details/gtgevseqqp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangshuangyany.cn/Article/details/gtdaljslcm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.daria6918.cn/Article/details/gtdlmumjhk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yongpay.top/Article/details/gtpnzrgaut.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gthyruhlgk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258.top/Article/details/gtfslrokml.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtcqvmxmfx.html

[Q01] 创建表
来源：http://dali.cheryme.top/Article/details/gtpnomfvop.html

CREATE TABLE users (
来源：http://dali.zhaomingkeji.xyz/Article/details/gtychucvoq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuanzx.com/Article/details/gtpvmnjuer.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gthcbjgeiw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenjidiqi.icu/Article/details/gtwttbewqv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258888.top/Article/details/gtzvhkijfr.html

);
来源：http://dali.c1oappe.top/Article/details/gtqdofrieh.html

[Q02] 创建带外键的表
来源：http://dali.fengsongda.top/Article/details/gtiznhottx.html

CREATE TABLE orders (
来源：http://dali.zhoulong.xyz/Article/details/gtagpifzpy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.snrcjt.cn/Article/details/gtvovfguri.html

user_id INT NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gtgutbwqlg.html

amount DECIMAL(10, 2),
来源：http://dali.wangdashe.top/Article/details/gtpynwfniv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yueranfly.top/Article/details/gtdaunsgox.html

);
来源：http://dali.hfpthk.cn/Article/details/gtdkybsdln.html

[Q03] 增加列
来源：http://dali.xinyue.icu/Article/details/gtimzhbgna.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.andypj.xyz/Article/details/gtlapksilh.html

[Q04] 修改列类型
来源：http://dali.guannengcc.top/Article/details/gtnamfofdm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gtabdxkoty.html

[Q05] 重命名列
来源：http://dali.dashuyun.cn/Article/details/gtqddfcjit.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tanke756.top/Article/details/gtosqnbvpq.html

[Q06] 删除列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxwwtjsx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangdashe.top/Article/details/gtttikfxyd.html

[Q07] 删除表
来源：http://dali.yj20258.top/Article/details/gtvujvrbub.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sweek.top/Article/details/gtnfxvlple.html

[Q08] 创建普通索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkcodwmc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gtqziemhox.html

[Q09] 创建唯一索引
来源：http://dali.wangdashe.top/Article/details/gtvtghcxrg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.bjfxy.top/Article/details/gtjdeyzebo.html

[Q10] 插入单行
来源：http://dali.dashuyun.cn/Article/details/gttqxbtuyz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yangfankeji.com/Article/details/gttfkvakhn.html

[Q11] 一次插入多行
来源：http://dali.yuxming.cn/Article/details/gtrgzncwiz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gtjrlkgkdl.html

[Q12] 插入后取自增 ID
来源：http://dali.jyoumei.cn/Article/details/gtofuqvxib.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigfzy.top/Article/details/gtmqedknim.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenzaomai.com/Article/details/gthsffihtz.html

[Q13] 忽略重复插入
来源：http://dali.hammf.cn/Article/details/gtvonkjaxa.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gtxrarsfwc.html

[Q14] 存在则更新（upsert）
来源：http://dali.vqdsnc.cn/Article/details/gtrtwckkhs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hnxiangtu.top/Article/details/gtafmskbvq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhoulong.xyz/Article/details/gtighmmctp.html

[Q15] 查询全部
来源：http://dali.yanxiufei.cn/Article/details/gtawufpfbq.html

SELECT * FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtbfcxwbdp.html

[Q16] 查询指定列
来源：http://dali.xuanzx.com/Article/details/gtocehgosu.html

SELECT id, name FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtgvjzruum.html

[Q17] 条件查询
来源：http://dali.kuanghao11.cn/Article/details/gtrdcttxdm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jqgfzy.top/Article/details/gtmzuwnhsm.html

[Q18] 模糊匹配
来源：http://dali.ivvv.top/Article/details/gtzgjnxqvn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sweek.top/Article/details/gtfeqjwffe.html

[Q19] 范围查询
来源：http://dali.guannengcc.top/Article/details/gtkhwpmjrb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwdxizpy.html

[Q20] IN 列表
来源：http://dali.birdmap.top/Article/details/gtobphyaxl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtqplnacpv.html

[Q21] 空值判断
来源：http://dali.dashuyun.cn/Article/details/gtaoxmmdac.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.daxiang520.top/Article/details/gtsxsnqwuf.html

[Q22] 排序
来源：http://dali.jlsjyb.cn/Article/details/gtpepajylb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jlsjyb.cn/Article/details/gtpuwovsrq.html

[Q23] 分页
来源：http://dali.aizwys.cn/Article/details/gtziovdofp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hnxiangtu.top/Article/details/gtmdoxxjko.html

[Q24] 去重
来源：http://dali.guannengcc.top/Article/details/gtplgwhofa.html

SELECT DISTINCT city FROM users;
来源：http://dali.gzhubu.top/Article/details/gtchyqxcgx.html

[Q25] 只取前 N 条
来源：http://dali.shzxlz.cn/Article/details/gtjozhpcro.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhiwuduotai.top/Article/details/gtjgunkoul.html

[Q26] 计数
来源：http://dali.hnxiangtu.top/Article/details/gtxfdjbqxn.html

SELECT COUNT(*) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtirwjtyqf.html

[Q27] 条件计数
来源：http://dali.xziqi.cn/Article/details/gtwkreiwha.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sweek.top/Article/details/gtwybvvxme.html

[Q28] 求和与平均
来源：http://dali.ehwqpu.com/Article/details/gtpqgwqpqj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtfpljhvgc.html

[Q29] 最大最小值
来源：http://dali.jinqigufen.top/Article/details/gttnqyghpx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzctfnjkg.html

[Q30] 分组统计
来源：http://dali.c1oappe.top/Article/details/gtvdoqhyin.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gtmjlqraue.html

[Q31] 分组后过滤
来源：http://dali.yvedp.cn/Article/details/gtmebioppi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gotoacloud.top/Article/details/gtobpdjtgr.html

[Q32] 分组拼接字符串
来源：http://dali.cashguo.top/Article/details/gtzkrvubvb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgskzzdg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hywenlv.cn/Article/details/gtwamcdbiu.html

[Q33] 多列分组
来源：http://dali.meibo888.top/Article/details/gtgvsviypg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.quarkkingdee.top/Article/details/gtqdcpsjzx.html

[Q34] 每组取第一条
来源：http://dali.yvedp.cn/Article/details/gtybjmgwbd.html

SELECT * FROM (
来源：http://dali.jlsjyb.cn/Article/details/gtokqvhqur.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shzxlz.cn/Article/details/gthtdrxvyt.html

) t WHERE rn = 1;
来源：http://dali.nwbrower.top/Article/details/gtarqagchk.html

[Q35] 内连接
来源：http://dali.meibo888.top/Article/details/gtjnpkzkmv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xinyue.icu/Article/details/gtrwrfalot.html

[Q36] 左连接
来源：http://dali.yuanzhike.top/Article/details/gtxzmbvils.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgufenzy.top/Article/details/gthuekxbmd.html

[Q37] 右连接
来源：http://dali.guannengcc.top/Article/details/gtjsveglqh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.bjfxy.top/Article/details/gtadjmsaea.html


<!-- 参考信息 -->