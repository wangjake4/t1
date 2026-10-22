代发 wailian999

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gtdbrelgah.html

JS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gtuxplrsqo.html

TS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gttrmtvame.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlkisqvi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dianchejie.cn/Article/details/gtpzcjkagw.html

Ruby: warn "err"
来源：http://dali.yangfankeji.com/Article/details/gtndtxjwwp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtfhzuvnim.html

[M07] 判断是否为主入口
来源：http://dali.zhongyouzk.top/Article/details/gtwiisflcr.html

Py:   if __name__ == "__main__":
来源：http://dali.shangyingyoupin.top/Article/details/gtxcalqbci.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cdnleiting.top/Article/details/gtzbxgcpme.html

JS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gtiemcaqvf.html

TS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gtxykipjcj.html

Java: public static void main(String[] args)
来源：http://dali.jlsjyb.cn/Article/details/gttmubtepp.html

Go:   func main()
来源：http://dali.jiagoushi.top/Article/details/gtiulhqjij.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.redwolf501.top/Article/details/gthftvoqnl.html

C#:   static void Main(string[] args)
来源：http://dali.yj202588.top/Article/details/gtmsehkcdi.html

[M08] 获取系统与运行时信息
来源：http://dali.zhongyouzk.top/Article/details/gtcqzvpinq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sweek.top/Article/details/gttkvwvjih.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aizwys.cn/Article/details/gtyyxyslto.html

JS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gtpbdtnxky.html

TS:   process.platform;  process.version
来源：http://dali.c1oappe.top/Article/details/gtvaoirehl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenjidiqi.icu/Article/details/gtreginkyv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigufen.top/Article/details/gtsjhigseg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj202588.top/Article/details/gtqbbnofaa.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aibaodan.cn/Article/details/gtgiaptymu.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtutslfhwu.html

N. 数据结构与算法
来源：http://dali.jinghuilouyu.cn/Article/details/gtpohryqfi.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtbxkrjqxw.html

[N01] 二分查找（有序数组）
来源：http://dali.cucudq.cn/Article/details/gtqrdkqgub.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjlrumup.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xziqi.cn/Article/details/gtisvvkgnf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gtywcmxwpj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtdoluascj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtlnepyafr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtlnnsfwou.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.snrcjt.cn/Article/details/gtwdmbsssj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtiaqpsfbp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewpcwmcj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gtlesldwpj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aizwys.cn/Article/details/gthubebvyq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtblxeuftm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gtsyxdzjvt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhiwuduotai.top/Article/details/gtcwnbsgcu.html

Go:   slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gtqdvkbuqc.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gtrgalyjja.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gtjeqzgrrt.html

[N03] 快速排序（分治示例）
来源：http://dali.zycfv.cn/Article/details/gtcahqyflo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guowangkeji.top/Article/details/gtskrvhqky.html

PHP:  // 递归实现，或用 usort
来源：http://dali.kuanghao11.cn/Article/details/gtvlsartvl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gtscboqwdm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtirsnjbix.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shzxlz.cn/Article/details/gtnkebxpha.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yongpay.top/Article/details/gtbtwsjvye.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shangyingyoupin.top/Article/details/gtittywfeq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hnqzz.top/Article/details/gtmtaunzyw.html

[N04] 斐波那契数列
来源：http://dali.jqgufenzy.top/Article/details/gtnscnlfqc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gttnmsfjho.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gtlqzuodsm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtzocvwslb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgxgknuc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvaawxbe.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pengpengdd.cyou/Article/details/gtqroflgqo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.mhx1999.top/Article/details/gtcgicrwle.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtybigasuh.html

[N05] 最大公约数
来源：http://dali.jlsjyb.cn/Article/details/gtdmmxxqgf.html

Py:   math.gcd(a, b)
来源：http://dali.pycfn.com/Article/details/gtflkchfdd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.svipenyu.cn/Article/details/gtswbpzeju.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gtohrgaysf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxinkj.top/Article/details/gtlktrnmcu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cqqwz.cn/Article/details/gttaiohomx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgfzy.top/Article/details/gtrglfkvrt.html

Ruby: a.gcd(b)
来源：http://dali.cheryme.top/Article/details/gtorqqhadc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.smart0.xyz/Article/details/gtmjkegtnw.html

[N06] 判断回文字符串
来源：http://dali.daxiang520.top/Article/details/gtzhkmxviz.html

Py:   s == s[::-1]
来源：http://dali.bjfxy.top/Article/details/gtwerceapn.html

PHP:  $s === strrev($s);
来源：http://dali.snrcjt.cn/Article/details/gtxlwlivnw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtvmagxutg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtlnuvwlsc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.redwolf501.top/Article/details/gtmhrpvwrr.html

Go:   // 双指针从两端比较
来源：http://dali.haohaochexian.top/Article/details/gtphxkqyac.html

Ruby: s == s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gtodirvuxb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gaohongyu789.top/Article/details/gtugswipuq.html

[N07] 两数之和（返回下标）
来源：http://dali.aizwys.cn/Article/details/gttyhfxbzw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xuanzx.com/Article/details/gtboaqyjol.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhengqikj.top/Article/details/gtzthbdxro.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hammf.cn/Article/details/gtdpthumml.html

TS:   // 手写 Map<string, number>
来源：http://dali.shangyingyoupin.top/Article/details/gteqaphhkl.html

Java: // 手写 HashMap
来源：http://dali.haohaochexian.top/Article/details/gtimlpqjrx.html

Go:   // 手写 map[int]int
来源：http://dali.mhx1999.top/Article/details/gtlmfaftbd.html

Ruby: // 手写 Hash
来源：http://dali.cashguo.top/Article/details/gtjltogrxl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.havefunace.top/Article/details/gtkrallvli.html

[N08] 生成全排列
来源：http://dali.ydzc1.top/Article/details/gtqgqdwwdo.html

Py:   itertools.permutations(arr)
来源：http://dali.yangfankeji.com/Article/details/gtphcwvbkh.html

PHP:  // 手写递归交换
来源：http://dali.bjfxy.top/Article/details/gtqgsaqvmh.html

JS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtzzvaxhda.html

TS:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtomctesms.html

Java: // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtmotxlwqq.html

Go:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtkknwjqim.html

Ruby: arr.permutation.to_a
来源：http://dali.cqqwz.cn/Article/details/gtlbdarfka.html

C#:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtalskdtpv.html

[N09] 栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gtbqulshmd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.birdmap.top/Article/details/gtdbxskuwy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tian-w.cn/Article/details/gtqliocbgh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gtgvrrnvmo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.mhx1999.top/Article/details/gtzrknxjig.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.meibo888.top/Article/details/gtyhtfkukr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fengsongda.top/Article/details/gtzmbjloft.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gttsohosgm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj202588.top/Article/details/gtcueszqtq.html

[N10] 链表节点定义
来源：http://dali.daxiang520.top/Article/details/gtixdpfczu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cashguo.top/Article/details/gtzshmkqsr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jiagoushi.top/Article/details/gtimmqivoc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xylfe.cn/Article/details/gtqnbocdwf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.feifeiyinyue.top/Article/details/gttynpfklh.html

Java: class Node { int v; Node next; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgktoiyjb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhongyouzk.top/Article/details/gtgormnawb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssmzsxui.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jyoumei.cn/Article/details/gtnrwfqtqj.html

[N11] 二叉树中序遍历
来源：http://dali.fzhhl.top/Article/details/gtjmvkcngv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmuoqlwty.html

PHP:  // 手写递归函数
来源：http://dali.jianghu66.top/Article/details/gtoixwywxo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gtkibbnpun.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gthrtqqijg.html

Java: // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gtocxkbcvy.html

Go:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtgjadqoqa.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.redwolf501.top/Article/details/gthtzuycwe.html

C#:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtmnaqeidn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yvedp.cn/Article/details/gtqjjmqmew.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.0kj1m.cn/Article/details/gtoiowskwc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hongshengwenyu.top/Article/details/gtkomryxse.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gtzovyjsdd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxffsjjgq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzyonyhq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aibaodan.cn/Article/details/gtinijbcyn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hywenlv.cn/Article/details/gtvgiuxqao.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yueranfly.top/Article/details/gtxmorwvru.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtyddqbtro.html

O. 并发与异步
来源：http://dali.hfpthk.cn/Article/details/gthwfqzgmh.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtngmyhgai.html

[O01] 启动一个线程
来源：http://dali.nanxinkj.top/Article/details/gttzvlzqqw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.0kj1m.cn/Article/details/gtwvhukhis.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.svipenyu.cn/Article/details/gtolcincvm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.iojbl.cn/Article/details/gtpkchvpce.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gtsugwjgzk.html

Java: new Thread(() -> f()).start()
来源：http://dali.quarkkingdee.top/Article/details/gtkyixworu.html

Go:   go f()
来源：http://dali.jqgfzy.top/Article/details/gtkiuwtuqp.html

Ruby: Thread.new { f }
来源：http://dali.dashuyun.cn/Article/details/gtgllvqdxn.html

C#:   Task.Run(() => F());
来源：http://dali.wangshuangyany.cn/Article/details/gtgjvdbeku.html

[O02] 使用线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtfmaxzzkl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yonumen.top/Article/details/gthkermrcr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aibaodan.cn/Article/details/gtfdsfllbo.html

JS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gtfcejtjrc.html

TS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gtluysacjg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.snrcjt.cn/Article/details/gtuumhnonl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sufxvd.cn/Article/details/gtzrctbmbj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hnxiangtu.top/Article/details/gtxdtvejbp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhengqikj.top/Article/details/gtuipkisjf.html

[O03] 加锁保护共享数据
来源：http://dali.wangdashe.top/Article/details/gtsdliyxix.html

Py:   with lock: shared += 1
来源：http://dali.pycfn.com/Article/details/gtfwegfnra.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cdnleiting.top/Article/details/gtfnjshpfd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigfzy.top/Article/details/gtmcsjylao.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gtiujnytfg.html

Java: synchronized (this) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gtmjywcgix.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nwbrower.top/Article/details/gtbxeucodb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.0kj1m.cn/Article/details/gtpjawbnjk.html

C#:   lock (gate) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gthxjiuwky.html

[O04] 定义异步函数并等待
来源：http://dali.nwbrower.top/Article/details/gtbsyprihm.html

Py:   async def f():⏎    await g()
来源：http://dali.ydzc1.top/Article/details/gtzcpzazho.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.haohaochexian.top/Article/details/gtmiiosjdg.html

JS:   async function f() { await g(); }
来源：http://dali.ehwqpu.com/Article/details/gtaijvpidy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwqrxrsx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenzaomai.com/Article/details/gticuvvpxy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.kuanghao11.cn/Article/details/gtktbxotqt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.snrcjt.cn/Article/details/gtdhyscnxk.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258888.top/Article/details/gtgspfjsxh.html

[O05] 并发执行并等待全部完成
来源：http://dali.cashguo.top/Article/details/gtqfqduuvf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtgilqygzw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hysaishi.cn/Article/details/gtoaivxrjt.html

JS:   await Promise.all(tasks)
来源：http://dali.jiagoushi.top/Article/details/gtcwltcrzi.html

TS:   await Promise.all(tasks)
来源：http://dali.daria6918.cn/Article/details/gtogpbgggc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinghuilouyu.cn/Article/details/gtholyozdh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.iojbl.cn/Article/details/gtjniicrxf.html

Ruby: threads.map(&:join)
来源：http://dali.wangshuangyany.cn/Article/details/gtvbmfbbsw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shzxlz.cn/Article/details/gtanqlslla.html

[O06] 使用进程池
来源：http://dali.sweek.top/Article/details/gtqaayymgp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nanxuanxn.top/Article/details/gtggedvwaq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.0kj1m.cn/Article/details/gtiuicfymu.html

JS:   // child_process / cluster 模块
来源：http://dali.daria6918.cn/Article/details/gthijpewol.html

TS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gtiafnrdvt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xylfe.cn/Article/details/gtwyryhthc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xylfe.cn/Article/details/gtqkeoqfza.html

Ruby: // fork 块
来源：http://dali.shangyingyoupin.top/Article/details/gtvacpywlq.html

C#:   Parallel.For
来源：http://dali.shangyingyoupin.top/Article/details/gtbclmgwrl.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gttonjwrft.html

P. 常用工具函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjpiayro.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gteyxrvhhc.html

[P01] 生成 UUID
来源：http://dali.jyoumei.cn/Article/details/gtlbvlzjzt.html

Py:   str(uuid.uuid4())
来源：http://dali.hammf.cn/Article/details/gtbgcdvuli.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fzhhl.top/Article/details/gtjpdmpzbw.html

JS:   crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gtciaccusx.html

TS:   crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gtuaqurgym.html

Java: UUID.randomUUID().toString()
来源：http://dali.shuidangran.top/Article/details/gtdrojgeqp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fzhhl.top/Article/details/gtpmtoijmg.html

Ruby: SecureRandom.uuid
来源：http://dali.yueranfly.top/Article/details/gtvrcwsplp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yueranfly.top/Article/details/gtytittqiy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cheryme.top/Article/details/gtpipghppv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.snrcjt.cn/Article/details/gtfkvgukgz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.quarkkingdee.top/Article/details/gtkyohzwtt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuanzhike.top/Article/details/gtsyhqfxvz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.snrcjt.cn/Article/details/gtcnxhwevt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gthltacxwz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.vqdsnc.cn/Article/details/gtitzqhfwx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xinyue.icu/Article/details/gtshesufpb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gogol.net.cn/Article/details/gtxosdznnl.html

[P03] 生成短随机字符串
来源：http://dali.c1oappe.top/Article/details/gtkxfuldgx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ybcxt.top/Article/details/gtbtbuvqix.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sweek.top/Article/details/gtehpdokiz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gaohongyu789.top/Article/details/gtkjarusdp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gtclspcakc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.iojbl.cn/Article/details/gtuddmtqvi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yuxming.cn/Article/details/gttmpcmmxp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.fzhhl.top/Article/details/gtrhooyqkj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.c1oappe.top/Article/details/gtxjpmtbgq.html

[P04] 求长度
来源：http://dali.birdmap.top/Article/details/gtlsreedtk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hfpthk.cn/Article/details/gtcyasqksk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gthkcomauo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gtxwpuhhtk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gtmncaqxee.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tanke756.top/Article/details/gtmbxflefd.html

Go:   len(arr);  len(m)
来源：http://dali.yongpay.top/Article/details/gtpbhenybo.html

Ruby: x.length;  x.size
来源：http://dali.jiagoushi.top/Article/details/gterrewrtc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.svipenyu.cn/Article/details/gttzigofln.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxuanxn.top/Article/details/gtdxsfenuc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yuxming.cn/Article/details/gtrwzufvsv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrltlbxa.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.andypj.xyz/Article/details/gtlwgfwyua.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hammf.cn/Article/details/gtloswwywm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tanke756.top/Article/details/gtdnevyagh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.fengsongda.top/Article/details/gtjqmgqjwx.html

Ruby: a == b
来源：http://dali.chenzaomai.com/Article/details/gtnouzrpar.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigufen.top/Article/details/gtubzidjvu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gaohongyu789.top/Article/details/gtvssosogt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jqgfzy.top/Article/details/gtavtqqvph.html

PHP:  if (empty($x)) {}
来源：http://dali.svipenyu.cn/Article/details/gtvqgfpemr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sufxvd.cn/Article/details/gtjivoyzoh.html

TS:   if (x == null) {}
来源：http://dali.ppjwa.cn/Article/details/gthgcfkmud.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnszkiokw.html

Go:   if x == nil {}
来源：http://dali.pycfn.com/Article/details/gtuvsptzzp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxinkj.top/Article/details/gtarzazxzj.html

C#:   if (x is null) {}
来源：http://dali.birdmap.top/Article/details/gtpjljjurd.html

[P07] 防抖与节流
来源：http://dali.zdqjudy.top/Article/details/gtudkptcag.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sysykeji.top/Article/details/gtcrpfrkpu.html

PHP:  // 手写时间戳比较
来源：http://dali.smart0.xyz/Article/details/gtoihckljr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gthnbwlxec.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gtvxrvjhaf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yongpay.top/Article/details/gtqksialfk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hnxiangtu.top/Article/details/gtmoqleykc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cqqwz.cn/Article/details/gtwyovtbny.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvbucvtx.html

[P08] 处理浮点精度问题
来源：http://dali.cqqwz.cn/Article/details/gttfuicfsp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhoulong.xyz/Article/details/gtjcbpkxlu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sufxvd.cn/Article/details/gtuqakqnby.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.316326.xyz/Article/details/gtpbrgfxyw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinqigfzy.top/Article/details/gtdwcqojgp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangshuangyany.cn/Article/details/gthteflulk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aizwys.cn/Article/details/gtgoztzoac.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.mhx1999.top/Article/details/gtvadyiach.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hywenlv.cn/Article/details/gtwnoeceuj.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtmyiqmkhp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgfzy.top/Article/details/gtancfkvxh.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtvwdonclk.html

[Q01] 创建表
来源：http://dali.hongshengwenyu.top/Article/details/gtsccigwyt.html

CREATE TABLE users (
来源：http://dali.xziqi.cn/Article/details/gtvjsabzii.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aizwys.cn/Article/details/gtiusjgpqs.html

name VARCHAR(50) NOT NULL,
来源：http://dali.guannengcc.top/Article/details/gtttcjbtkf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tian-w.cn/Article/details/gtllmohhhn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigfzy.top/Article/details/gtajycszkl.html

);
来源：http://dali.meibo888.top/Article/details/gtlgjvfzqb.html

[Q02] 创建带外键的表
来源：http://dali.gaohongyu789.top/Article/details/gtxeofdtsg.html

CREATE TABLE orders (
来源：http://dali.pengpengdd.cyou/Article/details/gtaiejpdmi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.smart0.xyz/Article/details/gtgmvdjnzj.html

user_id INT NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gtbvwzxoyw.html

amount DECIMAL(10, 2),
来源：http://dali.guowangkeji.top/Article/details/gtabetdumt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenlongwang.top/Article/details/gtgebcufbd.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtksplcpex.html

[Q03] 增加列
来源：http://dali.xuanzx.com/Article/details/gtobjaxjcj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttppencet.html

[Q04] 修改列类型
来源：http://dali.yuanzhike.top/Article/details/gtylyrdkng.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.meibo888.top/Article/details/gtmpujxlmk.html

[Q05] 重命名列
来源：http://dali.9152youxi.cn/Article/details/gteetoetmz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xuanzx.com/Article/details/gtlrtxqvji.html

[Q06] 删除列
来源：http://dali.c1oappe.top/Article/details/gtprlzludh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ehwqpu.com/Article/details/gtehysrqwu.html

[Q07] 删除表
来源：http://dali.yuanzhike.top/Article/details/gtqgydecxo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.mhx1999.top/Article/details/gtzgylyqql.html

[Q08] 创建普通索引
来源：http://dali.wangshuangyany.cn/Article/details/gtiwhdgeel.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gtnvhzuhxr.html

[Q09] 创建唯一索引
来源：http://dali.jqgufenzy.top/Article/details/gtwsphpchk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxinkj.top/Article/details/gtfmpxehng.html

[Q10] 插入单行
来源：http://dali.xylfe.cn/Article/details/gtjrqgpukc.html


<!-- 参考信息 -->