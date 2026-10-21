代发 wailian999

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sxryk.cn/Article/details/gthfmfkvcy.html

JS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gtqoueplra.html

TS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gtewbtetfx.html

Java: System.err.println("err")
来源：http://dali.birdmap.top/Article/details/gtxnuuxbcl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.0kj1m.cn/Article/details/gtltrycxls.html

Ruby: warn "err"
来源：http://dali.xuanzx.com/Article/details/gtqehyzblj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cdnleiting.top/Article/details/gthocfieea.html

[M07] 判断是否为主入口
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxjnqgkz.html

Py:   if __name__ == "__main__":
来源：http://dali.ivvv.top/Article/details/gtvvgojgin.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.9152youxi.cn/Article/details/gtkzkofdaj.html

JS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gthhmqwjbf.html

TS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gtsxvuctpn.html

Java: public static void main(String[] args)
来源：http://dali.jinqigufen.top/Article/details/gtutgonbnc.html

Go:   func main()
来源：http://dali.sysykeji.top/Article/details/gtlndoskvj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yongpay.top/Article/details/gtfytmyivb.html

C#:   static void Main(string[] args)
来源：http://dali.zhoulong.xyz/Article/details/gtflirfuck.html

[M08] 获取系统与运行时信息
来源：http://dali.0kj1m.cn/Article/details/gteflfefzi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.kuanghao11.cn/Article/details/gtxqwmqmzp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvinmaqk.html

JS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gtnbpqbpct.html

TS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gtaenybsjq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.haohaochexian.top/Article/details/gtgkbeajhx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenzaomai.com/Article/details/gtzjhrbiun.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cdnleiting.top/Article/details/gtnliednao.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dianchejie.cn/Article/details/gthjvtdvgo.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbficbmq.html

N. 数据结构与算法
来源：http://dali.jyoumei.cn/Article/details/gtfqtziptg.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtctljzyva.html

[N01] 二分查找（有序数组）
来源：http://dali.birdmap.top/Article/details/gtbnasauil.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtlagjpvai.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtugqsxeyu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gthpwpmkug.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gtkwkkegfc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtqycdefwy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtfdvepvqa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jqgfzy.top/Article/details/gtrukbjxgo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtidwtjbrd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhoulong.xyz/Article/details/gtipzgyaxo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gtgsnraecu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aizwys.cn/Article/details/gtyqorcsar.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gtrsbztigl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyytwkjyv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gtovwwmewq.html

Go:   slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gtchkvbwid.html

Ruby: arr.sort
来源：http://dali.havefunace.top/Article/details/gtmtbhfosy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuetiantiany.cn/Article/details/gtkkxyhdxa.html

[N03] 快速排序（分治示例）
来源：http://dali.cqqwz.cn/Article/details/gtricuqgvb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gthurrsfzb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xziqi.cn/Article/details/gtcuzdwckr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gtqhngqmrq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gtkwwqikre.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxuanxn.top/Article/details/gthxldppfr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinghuilouyu.cn/Article/details/gteuagrsgc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jqgufenzy.top/Article/details/gtasyqfafo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yongpay.top/Article/details/gtbpbnliyi.html

[N04] 斐波那契数列
来源：http://dali.shuidangran.top/Article/details/gtlvlkarxd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.316326.xyz/Article/details/gtfrhcejsp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.andypj.xyz/Article/details/gtxyavifcj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtnmkjfhor.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gttcueyngz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gtbjchnnrp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gotoacloud.top/Article/details/gteiwzswdt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hywenlv.cn/Article/details/gtjcqcwrrn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtzbcctnnx.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gtrmyprxax.html

Py:   math.gcd(a, b)
来源：http://dali.dianchejie.cn/Article/details/gtboxpthyl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtzlxhwgnv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gtyntopbfr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fzhhl.top/Article/details/gtbiwznlri.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthfmfgtqb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hfpthk.cn/Article/details/gtphwkgdeg.html

Ruby: a.gcd(b)
来源：http://dali.daxiang520.top/Article/details/gtdnskgwth.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenjidiqi.icu/Article/details/gtwgmzhlks.html

[N06] 判断回文字符串
来源：http://dali.mhx1999.top/Article/details/gtijyiaupf.html

Py:   s == s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gtoaikhgkf.html

PHP:  $s === strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gtfjhbotpw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtbvvlofdl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtocfhrazf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yanxiufei.cn/Article/details/gtnccvbrki.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gtixmtjlrd.html

Ruby: s == s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtkzgxqyvo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gthvwsojvf.html

[N07] 两数之和（返回下标）
来源：http://dali.shzxlz.cn/Article/details/gtdbfblipe.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nwbrower.top/Article/details/gtimmzplul.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yonumen.top/Article/details/gtdvrnmpry.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cqqwz.cn/Article/details/gtbjsaiekt.html

TS:   // 手写 Map<string, number>
来源：http://dali.jqgfzy.top/Article/details/gtgudwxulz.html

Java: // 手写 HashMap
来源：http://dali.shuidangran.top/Article/details/gttmwwsqnr.html

Go:   // 手写 map[int]int
来源：http://dali.smart0.xyz/Article/details/gtovgpyecf.html

Ruby: // 手写 Hash
来源：http://dali.yangfankeji.com/Article/details/gtztrdcxjf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.c1oappe.top/Article/details/gtmxlrbyzs.html

[N08] 生成全排列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmdkjhmp.html

Py:   itertools.permutations(arr)
来源：http://dali.redwolf501.top/Article/details/gthtvjsutr.html

PHP:  // 手写递归交换
来源：http://dali.shangyingyoupin.top/Article/details/gtuonxyorg.html

JS:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtfhnfouyz.html

TS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtuhrsvhts.html

Java: // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtoufsquec.html

Go:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtxobxgnxc.html

Ruby: arr.permutation.to_a
来源：http://dali.gaohongyu789.top/Article/details/gtshsbacjj.html

C#:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtwxoyjfbe.html

[N09] 栈与队列
来源：http://dali.tianlin.xyz/Article/details/gtezneoady.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtcoxqqmhw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuanzx.com/Article/details/gtmovkcozj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gtpkdgcoqw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.birdmap.top/Article/details/gtndevedbx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gtbuklwjvs.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnqzz.top/Article/details/gthraelvgd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gtzolseknc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.birdmap.top/Article/details/gtwuzkimrw.html

[N10] 链表节点定义
来源：http://dali.tian-w.cn/Article/details/gtgaogwzbg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sxryk.cn/Article/details/gtaugnzilu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dianchejie.cn/Article/details/gtgyhhrdyt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xuetiantiany.cn/Article/details/gtohphdxgo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cashguo.top/Article/details/gttpauwhbi.html

Java: class Node { int v; Node next; }
来源：http://dali.zycfv.cn/Article/details/gtdyazwamy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj202588.top/Article/details/gthgiyqcsy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pycfn.com/Article/details/gtimlihllx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.smart0.xyz/Article/details/gtgmzyupgd.html

[N11] 二叉树中序遍历
来源：http://dali.yonumen.top/Article/details/gtnkxhnimp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhengqikj.top/Article/details/gtvkebpbhp.html

PHP:  // 手写递归函数
来源：http://dali.gaohongyu789.top/Article/details/gtvwlfkcvd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gtpumrjemz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gtebgcqvlj.html

Java: // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gteegwurut.html

Go:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gtukillfar.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.kuanghao11.cn/Article/details/gtythrpbjs.html

C#:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtvxxzrxhc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gotoacloud.top/Article/details/gtuwlxfpco.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sxryk.cn/Article/details/gtcsibosxz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gzhubu.top/Article/details/gtvutzrlan.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gtnwgvrnfb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hfpthk.cn/Article/details/gtejpxzzqr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gtmkuvnpgv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sufxvd.cn/Article/details/gtdcjjsgjy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.vqdsnc.cn/Article/details/gttbodytww.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.316326.xyz/Article/details/gtotdryegi.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtcngikpse.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvjvfnmv.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtkwrfyirg.html

[O01] 启动一个线程
来源：http://dali.chenzaomai.com/Article/details/gtawmrvsya.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.9152youxi.cn/Article/details/gtepcfouko.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgdxkccf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jianghu66.top/Article/details/gtmitofnyt.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gthaojvkry.html

Java: new Thread(() -> f()).start()
来源：http://dali.dashuyun.cn/Article/details/gtrqpbejem.html

Go:   go f()
来源：http://dali.hfpthk.cn/Article/details/gtongyojwk.html

Ruby: Thread.new { f }
来源：http://dali.zhixingplan.top/Article/details/gteopnsviu.html

C#:   Task.Run(() => F());
来源：http://dali.tanke756.top/Article/details/gtqprtmsho.html

[O02] 使用线程池
来源：http://dali.yongpay.top/Article/details/gtqbkkzcjv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tianlin.xyz/Article/details/gtczckubuy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jiagoushi.top/Article/details/gtwadubpvj.html

JS:   // worker_threads 线程池
来源：http://dali.snrcjt.cn/Article/details/gtewikehdl.html

TS:   // worker_threads 线程池
来源：http://dali.kuanghao11.cn/Article/details/gtvpixzrvc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zycfv.cn/Article/details/gtxdzhtzyy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhaomingkeji.xyz/Article/details/gttylpvalo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgfzy.top/Article/details/gtadbqikry.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yvedp.cn/Article/details/gtyhiebysq.html

[O03] 加锁保护共享数据
来源：http://dali.quarkkingdee.top/Article/details/gtyrfcpfea.html

Py:   with lock: shared += 1
来源：http://dali.daria6918.cn/Article/details/gtcjoiffou.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ybcxt.top/Article/details/gtncdmxrvy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yvedp.cn/Article/details/gtxoffzixu.html

TS:   // 同 JS
来源：http://dali.yangfankeji.com/Article/details/gtcoauraoz.html

Java: synchronized (this) { shared++; }
来源：http://dali.cheryme.top/Article/details/gtmosyrjrh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwcqwrlp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hammf.cn/Article/details/gtjkgluggr.html

C#:   lock (gate) { shared++; }
来源：http://dali.mhx1999.top/Article/details/gtvkiusyfz.html

[O04] 定义异步函数并等待
来源：http://dali.chenlongwang.top/Article/details/gtsxmzdlaq.html

Py:   async def f():⏎    await g()
来源：http://dali.bjfxy.top/Article/details/gtgisyaikj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangshuangyany.cn/Article/details/gtwqcgiwnl.html

JS:   async function f() { await g(); }
来源：http://dali.birdmap.top/Article/details/gtqtwyizgi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yonumen.top/Article/details/gtoymdbqfs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dashuyun.cn/Article/details/gtrprsqjzj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.wangdashe.top/Article/details/gtpufgfaei.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sysykeji.top/Article/details/gtjzkxligz.html

C#:   async Task F() { await G(); }
来源：http://dali.ppjwa.cn/Article/details/gtqffnehpi.html

[O05] 并发执行并等待全部完成
来源：http://dali.ivvv.top/Article/details/gtzmwlvrtf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.birdmap.top/Article/details/gtgjqkoqdd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cdnleiting.top/Article/details/gtflpvmulw.html

JS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gtqwcpcrea.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258.top/Article/details/gtmxlxhjba.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pengpengdd.cyou/Article/details/gtxiwoxbin.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuezqdvyi.html

Ruby: threads.map(&:join)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpkkmlbg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jiagoushi.top/Article/details/gtpmmgjlqz.html

[O06] 使用进程池
来源：http://dali.xuanzx.com/Article/details/gtebewvjco.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xuetiantiany.cn/Article/details/gtecnygyah.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenlongwang.top/Article/details/gtnlkyyukd.html

JS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gtxnfxlytb.html

TS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gttgvbwevk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.andypj.xyz/Article/details/gthqkfzwdh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinqigfzy.top/Article/details/gtunctndiz.html

Ruby: // fork 块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktylowlx.html

C#:   Parallel.For
来源：http://dali.pengpengdd.cyou/Article/details/gtxesjmmhk.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtvxcjntam.html

P. 常用工具函数
来源：http://dali.sweek.top/Article/details/gtsroberzc.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtxyxycpkw.html

[P01] 生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gtbtvhfmjj.html

Py:   str(uuid.uuid4())
来源：http://dali.chenjidiqi.icu/Article/details/gtnafexxtv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.0kj1m.cn/Article/details/gtflinvisx.html

JS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtauaeuxdj.html

TS:   crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkcxwcdv.html

Java: UUID.randomUUID().toString()
来源：http://dali.zdqjudy.top/Article/details/gtnbsoppjh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgufenzy.top/Article/details/gtggtkqmgm.html

Ruby: SecureRandom.uuid
来源：http://dali.jianghu66.top/Article/details/gtwwexiwmf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.316326.xyz/Article/details/gtoqdojbts.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hammf.cn/Article/details/gtgrzmlywj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.snrcjt.cn/Article/details/gtvtfpqbcy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ybcxt.top/Article/details/gtcvdbnfuw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtgberlmga.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yangfankeji.com/Article/details/gtkmmpgyym.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtabodzopb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.andypj.xyz/Article/details/gtvellucig.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hywenlv.cn/Article/details/gtdodnhetw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuxming.cn/Article/details/gtwjxrujhh.html

[P03] 生成短随机字符串
来源：http://dali.kuanghao11.cn/Article/details/gtdbdpzntf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.daria6918.cn/Article/details/gtuxkimptu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sxryk.cn/Article/details/gtsrixlnkq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigufen.top/Article/details/gtlopxpnsm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtbrogjkpw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cucudq.cn/Article/details/gturovfsgv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenzaomai.com/Article/details/gtddmrnyzh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nwbrower.top/Article/details/gtzkgyrhsq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.iojbl.cn/Article/details/gtzmgtytal.html

[P04] 求长度
来源：http://dali.jlsjyb.cn/Article/details/gtysrtrdym.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dianchejie.cn/Article/details/gtpygrsohy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzweiqyzb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zycfv.cn/Article/details/gtgwiviack.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gtdkezvpnc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shuidangran.top/Article/details/gtdmjvwzcj.html

Go:   len(arr);  len(m)
来源：http://dali.chenlongwang.top/Article/details/gtnopgpbvo.html

Ruby: x.length;  x.size
来源：http://dali.zhixingplan.top/Article/details/gtumhybmzv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtxreforze.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ybcxt.top/Article/details/gtffldykyg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.haohaochexian.top/Article/details/gtirxqavsi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jianghu66.top/Article/details/gthadydnai.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jlsjyb.cn/Article/details/gtyiazmney.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gaohongyu789.top/Article/details/gteonuzrlj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.daria6918.cn/Article/details/gtxnqnbcld.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtmawxcptt.html

Ruby: a == b
来源：http://dali.hongshengwenyu.top/Article/details/gtcimjhqxa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.aibaodan.cn/Article/details/gtzuhwapna.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnqzz.top/Article/details/gtddqifgtp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gaohongyu789.top/Article/details/gtszaumeuo.html

PHP:  if (empty($x)) {}
来源：http://dali.daria6918.cn/Article/details/gtrbelqtyw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.snrcjt.cn/Article/details/gtdnwaibxa.html

TS:   if (x == null) {}
来源：http://dali.dianchejie.cn/Article/details/gthhwvikly.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gtehcbxksj.html

Go:   if x == nil {}
来源：http://dali.zdqjudy.top/Article/details/gtrkvvqovp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gogol.net.cn/Article/details/gtauhfmdcu.html

C#:   if (x is null) {}
来源：http://dali.yj20258888.top/Article/details/gttebpuerp.html

[P07] 防抖与节流
来源：http://dali.tian-w.cn/Article/details/gtgscwxrex.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hfpthk.cn/Article/details/gtkbqzrehi.html

PHP:  // 手写时间戳比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxopovjcr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gtdqctoiio.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xinyue.icu/Article/details/gtavsdrnbt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhengqikj.top/Article/details/gtlbgzoxqi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zycfv.cn/Article/details/gtzuucqamn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrywjcfbu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jlsjyb.cn/Article/details/gtrclblzws.html

[P08] 处理浮点精度问题
来源：http://dali.andypj.xyz/Article/details/gtndpdhnfq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.meibo888.top/Article/details/gtzmavzyqf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yongpay.top/Article/details/gtmivgnrlp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtziflwlsv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.redwolf501.top/Article/details/gthlisrcin.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ybcxt.top/Article/details/gtxcinhpte.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.bjfxy.top/Article/details/gthlwlfokf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.aibaodan.cn/Article/details/gtrfcxtbtf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgfzy.top/Article/details/gtrisqmabr.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtybfdvshc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuanzhike.top/Article/details/gtiqvqlhqn.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtgnhfydcq.html

[Q01] 创建表
来源：http://dali.guowangkeji.top/Article/details/gtjbvlgttc.html

CREATE TABLE users (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvymjpjae.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jlsjyb.cn/Article/details/gtynbtqjgl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.pengpengdd.cyou/Article/details/gtizmfwyae.html

email VARCHAR(100) UNIQUE,
来源：http://dali.guannengcc.top/Article/details/gtxiedurua.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.iojbl.cn/Article/details/gtsqptwzrh.html

);
来源：http://dali.zhongyouzk.top/Article/details/gtyhehjdsb.html

[Q02] 创建带外键的表
来源：http://dali.pycfn.com/Article/details/gtppwhxvgp.html

CREATE TABLE orders (
来源：http://dali.fengsongda.top/Article/details/gtrzortueq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gtmeynlrsk.html

user_id INT NOT NULL,
来源：http://dali.birdmap.top/Article/details/gtzzwrflch.html

amount DECIMAL(10, 2),
来源：http://dali.hywenlv.cn/Article/details/gtywzmhzsz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zdqjudy.top/Article/details/gtqlbjepbo.html

);
来源：http://dali.yj20258888.top/Article/details/gtlznremmf.html

[Q03] 增加列
来源：http://dali.snrcjt.cn/Article/details/gtkixwcycn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.0kj1m.cn/Article/details/gtuxhjrfie.html

[Q04] 修改列类型
来源：http://dali.mhx1999.top/Article/details/gttsxzromc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigfzy.top/Article/details/gtitmfmtjp.html

[Q05] 重命名列
来源：http://dali.zhoulong.xyz/Article/details/gtwvsaufff.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daxiang520.top/Article/details/gtaoxrjzxc.html

[Q06] 删除列
来源：http://dali.shanyushiyangtech.top/Article/details/gtsocqctvu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcpfntny.html

[Q07] 删除表
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkdvlfcm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ydzc1.top/Article/details/gtiwnxyisu.html

[Q08] 创建普通索引
来源：http://dali.chenjidiqi.icu/Article/details/gtkvtvfbzx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gtkmtexybr.html

[Q09] 创建唯一索引
来源：http://dali.birdmap.top/Article/details/gtrdxprbow.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gtakgtlodm.html

[Q10] 插入单行
来源：http://dali.jyoumei.cn/Article/details/gtqdwtmexo.html


<!-- 参考信息 -->