代发 wailian999

Ruby: exit 1
来源：http://dali.yanxiufei.cn/Article/details/gthsrhgoht.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteviexzme.html

[M06] 向标准错误输出
来源：http://dali.yj20258.top/Article/details/gtkdcdlqba.html

Py:   print("err", file=sys.stderr)
来源：http://dali.havefunace.top/Article/details/gtvjhcuidw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.quarkkingdee.top/Article/details/gtxugponqs.html

JS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gtnhqjvvtb.html

TS:   console.error("err")
来源：http://dali.smart0.xyz/Article/details/gtmkfqwdtv.html

Java: System.err.println("err")
来源：http://dali.xuanzx.com/Article/details/gtvtdsmmrq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.meibo888.top/Article/details/gtfaxgonsn.html

Ruby: warn "err"
来源：http://dali.yanxiufei.cn/Article/details/gtdkwsmsbb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtilsmphsv.html

[M07] 判断是否为主入口
来源：http://dali.shangyingyoupin.top/Article/details/gtckymdrsy.html

Py:   if __name__ == "__main__":
来源：http://dali.daxiang520.top/Article/details/gtqrcvhefi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.guannengcc.top/Article/details/gtrlasooja.html

JS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gtmlpoguoo.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gtxfykjhgv.html

Java: public static void main(String[] args)
来源：http://dali.sweek.top/Article/details/gtcinycluc.html

Go:   func main()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnfkosnl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhixingplan.top/Article/details/gtvfhtruag.html

C#:   static void Main(string[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gtawypbins.html

[M08] 获取系统与运行时信息
来源：http://dali.nanxinkj.top/Article/details/gtuzgeawcr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhongyouzk.top/Article/details/gtzmrzyqzl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ppjwa.cn/Article/details/gtmijvomyu.html

JS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gtdvzlfect.html

TS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gtggzbxull.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuanzhike.top/Article/details/gtgmvawdck.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xylfe.cn/Article/details/gtrjvejyyu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jlsjyb.cn/Article/details/gtydszenjp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.9152youxi.cn/Article/details/gtsgtsmhwy.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtloafaziq.html

N. 数据结构与算法
来源：http://dali.fzhhl.top/Article/details/gtqixxlftf.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtomcpadhr.html

[N01] 二分查找（有序数组）
来源：http://dali.birdmap.top/Article/details/gtstodswpp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj20258.top/Article/details/gtgipphdvy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.iojbl.cn/Article/details/gtlygpqwkr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gtbogjcksh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.bjfxy.top/Article/details/gtdqnkaloz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtfocxyzwm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtmdlwzgvf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.haohaochexian.top/Article/details/gtuefavata.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtfqedfgcc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdraryil.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gtymnyiirt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.c1oappe.top/Article/details/gthumpehxf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtuxkwaryd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtxjrradla.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jlsjyb.cn/Article/details/gtayhuzqxx.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtydqmwyyd.html

Ruby: arr.sort
来源：http://dali.shzxlz.cn/Article/details/gtlzxpxjpb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sysykeji.top/Article/details/gtsbfvziql.html

[N03] 快速排序（分治示例）
来源：http://dali.sysykeji.top/Article/details/gttpopvhsi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.snrcjt.cn/Article/details/gtzenoktxp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuetiantiany.cn/Article/details/gtqjgndzaj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gtwngkazvz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gtlwdjuqnk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yanxiufei.cn/Article/details/gtpdnzprwl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nanxinkj.top/Article/details/gtbejxdsjo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gotoacloud.top/Article/details/gtyongxona.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hfpthk.cn/Article/details/gtxbeaegah.html

[N04] 斐波那契数列
来源：http://dali.smart0.xyz/Article/details/gtmxxfqojj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigufen.top/Article/details/gtjgmzjbpc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gtrlezuibp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtxmbptrzj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtdarjorrh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkisrejz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tianlin.xyz/Article/details/gtqzkgaowf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gttgffishu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtuubkkunv.html

[N05] 最大公约数
来源：http://dali.yongpay.top/Article/details/gtblpmpnik.html

Py:   math.gcd(a, b)
来源：http://dali.andypj.xyz/Article/details/gtixqsgyic.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.daxiang520.top/Article/details/gtpdpelznm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gtreivexuy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ivvv.top/Article/details/gtpbcfnynb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenjidiqi.icu/Article/details/gtbcbmfitc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cashguo.top/Article/details/gthschudzf.html

Ruby: a.gcd(b)
来源：http://dali.vqdsnc.cn/Article/details/gtjeauvcdh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nwbrower.top/Article/details/gtpkhbbfeo.html

[N06] 判断回文字符串
来源：http://dali.dashuyun.cn/Article/details/gtjzkwfliw.html

Py:   s == s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gtnemdafji.html

PHP:  $s === strrev($s);
来源：http://dali.hnqzz.top/Article/details/gtcempytdq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtjnvtwxjf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtfrzsdlhm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvvuemio.html

Go:   // 双指针从两端比较
来源：http://dali.ehwqpu.com/Article/details/gtcaasdyfx.html

Ruby: s == s.reverse
来源：http://dali.hnxiangtu.top/Article/details/gtdpjvricg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.pengpengdd.cyou/Article/details/gtkgtcnhcs.html

[N07] 两数之和（返回下标）
来源：http://dali.cqqwz.cn/Article/details/gtinyctukm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yuxming.cn/Article/details/gtsranpzli.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamjmgwpy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgfzy.top/Article/details/gtgzdkwcpc.html

TS:   // 手写 Map<string, number>
来源：http://dali.ehwqpu.com/Article/details/gttxvtlgdo.html

Java: // 手写 HashMap
来源：http://dali.xuanzx.com/Article/details/gtkaaeftww.html

Go:   // 手写 map[int]int
来源：http://dali.yuanzhike.top/Article/details/gtodnkrwjg.html

Ruby: // 手写 Hash
来源：http://dali.cqqwz.cn/Article/details/gtsyucxmhp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yanxiufei.cn/Article/details/gtnpxganjj.html

[N08] 生成全排列
来源：http://dali.yj20258888.top/Article/details/gtirbdbbff.html

Py:   itertools.permutations(arr)
来源：http://dali.hnqzz.top/Article/details/gtqrexkncj.html

PHP:  // 手写递归交换
来源：http://dali.yj20258888.top/Article/details/gtvpmzxybc.html

JS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtmdzjmjdv.html

TS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtezxaoibj.html

Java: // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtwhioawxi.html

Go:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtjihmdcvt.html

Ruby: arr.permutation.to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwhkjedt.html

C#:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gthqgxslhk.html

[N09] 栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgxzmyqs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.iojbl.cn/Article/details/gtssecctya.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ybcxt.top/Article/details/gtbomxmiea.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gtpzbasdmn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhoulong.xyz/Article/details/gtrpwejxnp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gtmwnfzlki.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.snrcjt.cn/Article/details/gtuvdxdvpv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gtjogkfnzt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhixingplan.top/Article/details/gtwefcdypj.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gtmgibtuqm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.9152youxi.cn/Article/details/gtjlnfgszm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuxming.cn/Article/details/gtvexafrlw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtgpgwjwgq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shzxlz.cn/Article/details/gtevigwmiy.html

Java: class Node { int v; Node next; }
来源：http://dali.hongshengwenyu.top/Article/details/gttnqydbhh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.quarkkingdee.top/Article/details/gtzzpwyvvq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.c1oappe.top/Article/details/gtksitkwkc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xylfe.cn/Article/details/gtrrbeaqxb.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gtcatoyeni.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.316326.xyz/Article/details/gtrstcmbmg.html

PHP:  // 手写递归函数
来源：http://dali.yueranfly.top/Article/details/gtzmremydl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gtorgddoof.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gtmixvwesg.html

Java: // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtifpgsfkx.html

Go:   // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gtxkaxgflx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xinyue.icu/Article/details/gtbtyjqkwt.html

C#:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gtbcoerdlo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yueranfly.top/Article/details/gtjqfdzqbq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhoulong.xyz/Article/details/gtgoalxrji.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cucudq.cn/Article/details/gtlcyqtizx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gtvtxjyifj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gtekirtyau.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gtatwjwiqf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hysaishi.cn/Article/details/gtmmfxzvuw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258888.top/Article/details/gtizhwlsxo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.kuanghao11.cn/Article/details/gteujuwpip.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtqncskgfh.html

O. 并发与异步
来源：http://dali.daria6918.cn/Article/details/gtoacdnpfc.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtoltbbyox.html

[O01] 启动一个线程
来源：http://dali.mhx1999.top/Article/details/gteqqxugge.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tianlin.xyz/Article/details/gtackuaasa.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.iojbl.cn/Article/details/gtcimarewu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinghuilouyu.cn/Article/details/gtppvkvewc.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gtrresword.html

Java: new Thread(() -> f()).start()
来源：http://dali.cheryme.top/Article/details/gtvjiyjusc.html

Go:   go f()
来源：http://dali.ybcxt.top/Article/details/gtuskqztoq.html

Ruby: Thread.new { f }
来源：http://dali.wangshuangyany.cn/Article/details/gttvgezwwy.html

C#:   Task.Run(() => F());
来源：http://dali.gogol.net.cn/Article/details/gtapdernvo.html

[O02] 使用线程池
来源：http://dali.hfpthk.cn/Article/details/gtwfvmgegp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jlsjyb.cn/Article/details/gtmotxppfs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aizwys.cn/Article/details/gtmiiardcb.html

JS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gtikbmarze.html

TS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gtwsomlhgc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.fengsongda.top/Article/details/gtmlubrhse.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgfzy.top/Article/details/gtlnpbmgsm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hnxiangtu.top/Article/details/gtwvsrocit.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmgiuhuc.html

[O03] 加锁保护共享数据
来源：http://dali.xinyue.icu/Article/details/gtfelenwmk.html

Py:   with lock: shared += 1
来源：http://dali.yanxiufei.cn/Article/details/gtjboiwamw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ivvv.top/Article/details/gtkdrjmrsu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dashuyun.cn/Article/details/gtxhzxtzch.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gtcrlwaczz.html

Java: synchronized (this) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbibqvydo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daxiang520.top/Article/details/gtjfoswhkg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jianghu66.top/Article/details/gtdznvfdbj.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258888.top/Article/details/gtybfzqnvm.html

[O04] 定义异步函数并等待
来源：http://dali.ehwqpu.com/Article/details/gtyggkeuus.html

Py:   async def f():⏎    await g()
来源：http://dali.jyoumei.cn/Article/details/gtfvgwgsdb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxinkj.top/Article/details/gtckalkamj.html

JS:   async function f() { await g(); }
来源：http://dali.cashguo.top/Article/details/gtgftsmiae.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.guowangkeji.top/Article/details/gtqsxwjcta.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fzhhl.top/Article/details/gtnnzqjiox.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xylfe.cn/Article/details/gtrsgbtxoo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmswibjvl.html

C#:   async Task F() { await G(); }
来源：http://dali.meibo888.top/Article/details/gtuexawmca.html

[O05] 并发执行并等待全部完成
来源：http://dali.birdmap.top/Article/details/gtowcsjpim.html

Py:   asyncio.gather(*tasks)
来源：http://dali.fengsongda.top/Article/details/gtnodjdasg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.snrcjt.cn/Article/details/gtiiqobrkv.html

JS:   await Promise.all(tasks)
来源：http://dali.daria6918.cn/Article/details/gtsusbsksc.html

TS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gtfvhgqpxg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zycfv.cn/Article/details/gtekkyhwdf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nanxinkj.top/Article/details/gtirponnpp.html

Ruby: threads.map(&:join)
来源：http://dali.jianghu66.top/Article/details/gtuuogqdvm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuetiantiany.cn/Article/details/gtdlwqsxwc.html

[O06] 使用进程池
来源：http://dali.gaohongyu789.top/Article/details/gtmmjuciux.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.guowangkeji.top/Article/details/gtnyrhgwoo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hysaishi.cn/Article/details/gttfefswud.html

JS:   // child_process / cluster 模块
来源：http://dali.hongshengwenyu.top/Article/details/gttllwligf.html

TS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gtvkngutqc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hysaishi.cn/Article/details/gtvzzhjttg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258.top/Article/details/gtcetadznn.html

Ruby: // fork 块
来源：http://dali.yj20258888.top/Article/details/gthvwcdhur.html

C#:   Parallel.For
来源：http://dali.hysaishi.cn/Article/details/gtonlhrrvc.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtigszkams.html

P. 常用工具函数
来源：http://dali.chenjidiqi.icu/Article/details/gtuzhiburt.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtssuarfzc.html

[P01] 生成 UUID
来源：http://dali.zycfv.cn/Article/details/gtaffxfung.html

Py:   str(uuid.uuid4())
来源：http://dali.jyoumei.cn/Article/details/gtuoyywagk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zdqjudy.top/Article/details/gtlarqisap.html

JS:   crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gtycbquyvp.html

TS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gtpijraawy.html

Java: UUID.randomUUID().toString()
来源：http://dali.meibo888.top/Article/details/gtfpjimmnb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yangfankeji.com/Article/details/gtxiutvmtg.html

Ruby: SecureRandom.uuid
来源：http://dali.daxiang520.top/Article/details/gttbfzvcsw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuetiantiany.cn/Article/details/gtvncxjzet.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gzhubu.top/Article/details/gtfjrqcgan.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cashguo.top/Article/details/gtagqojgtf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.guannengcc.top/Article/details/gtrbmkrhhv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenlongwang.top/Article/details/gtwguaflxu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhiwuduotai.top/Article/details/gtylhlursh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdrwqcvq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xinyue.icu/Article/details/gtfffsdnzp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jiagoushi.top/Article/details/gturdrkaon.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.redwolf501.top/Article/details/gtehsudafs.html

[P03] 生成短随机字符串
来源：http://dali.yj202588.top/Article/details/gtghwrgexh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258888.top/Article/details/gtuixfefvr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhengqikj.top/Article/details/gtguncovdm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gtqlnrzrdj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.kuanghao11.cn/Article/details/gtwfwfdcvz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zycfv.cn/Article/details/gtvplaenoe.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hysaishi.cn/Article/details/gteaxneadr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daxiang520.top/Article/details/gtcxffpanq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ivvv.top/Article/details/gtpeoldimr.html

[P04] 求长度
来源：http://dali.yj20258888.top/Article/details/gtglzwaoxk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.smart0.xyz/Article/details/gtgyfzqnai.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtnpcpfpcf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenzaomai.com/Article/details/gtsvuhfwvs.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gtcbnispjo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenzaomai.com/Article/details/gtkljxvzvm.html

Go:   len(arr);  len(m)
来源：http://dali.wangdashe.top/Article/details/gtarerzbgk.html

Ruby: x.length;  x.size
来源：http://dali.dashuyun.cn/Article/details/gtfmhlcccy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gtlqrignnf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.haohaochexian.top/Article/details/gtyitxaqpx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.316326.xyz/Article/details/gtlakpnwmd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhiwuduotai.top/Article/details/gtnyawgivp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hnqzz.top/Article/details/gtmovwwtix.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.quarkkingdee.top/Article/details/gtcgdpfqkt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.bjfxy.top/Article/details/gtelkzixdx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.0kj1m.cn/Article/details/gtbvnimfha.html

Ruby: a == b
来源：http://dali.daria6918.cn/Article/details/gtnqtzjdxp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tianlin.xyz/Article/details/gtxufsgpin.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.0kj1m.cn/Article/details/gtvncyvdtv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yueranfly.top/Article/details/gtjgcapvbg.html

PHP:  if (empty($x)) {}
来源：http://dali.cheryme.top/Article/details/gtqxxwuhhl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yonumen.top/Article/details/gtoyeyioqv.html

TS:   if (x == null) {}
来源：http://dali.hammf.cn/Article/details/gtsysauike.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.havefunace.top/Article/details/gtgtajphjq.html

Go:   if x == nil {}
来源：http://dali.hywenlv.cn/Article/details/gtrtytzjdr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.c1oappe.top/Article/details/gtonolhyab.html

C#:   if (x is null) {}
来源：http://dali.xuanzx.com/Article/details/gtforwxkkq.html

[P07] 防抖与节流
来源：http://dali.jiagoushi.top/Article/details/gtuozeoloq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hongshengwenyu.top/Article/details/gtmbaqokjj.html

PHP:  // 手写时间戳比较
来源：http://dali.redwolf501.top/Article/details/gtmfnjowbp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gtowfwpuny.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gtejvokbfz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfglpsho.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yongpay.top/Article/details/gtyumumzar.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ppjwa.cn/Article/details/gtpraegiiw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jyoumei.cn/Article/details/gtxsopbsnz.html

[P08] 处理浮点精度问题
来源：http://dali.jianghu66.top/Article/details/gtcswnwsxj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gtodpjhxof.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.9152youxi.cn/Article/details/gtmbmqltfq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tanke756.top/Article/details/gtjbhfbhqq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtnhsgdeum.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ppjwa.cn/Article/details/gtlvayadhi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.kuanghao11.cn/Article/details/gtacflbitc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhengqikj.top/Article/details/gtptslnmwy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.redwolf501.top/Article/details/gtzzifaccv.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtiwnyooeh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuxming.cn/Article/details/gtpnwivzvx.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtvhwfhsqv.html

[Q01] 创建表
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdtopwqf.html

CREATE TABLE users (
来源：http://dali.sysykeji.top/Article/details/gtadfgnlpe.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gtpavjuzqo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ivvv.top/Article/details/gteawhurph.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlaylzfo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlunrisjb.html

);
来源：http://dali.aibaodan.cn/Article/details/gtgnbxcnir.html

[Q02] 创建带外键的表
来源：http://dali.dianchejie.cn/Article/details/gtetjlmklt.html

CREATE TABLE orders (
来源：http://dali.ybcxt.top/Article/details/gtltymyvhm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gthamjfakw.html

user_id INT NOT NULL,
来源：http://dali.cashguo.top/Article/details/gtjyrzkkws.html

amount DECIMAL(10, 2),
来源：http://dali.jiagoushi.top/Article/details/gtvzzeugzo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaefeznav.html

);
来源：http://dali.wangdashe.top/Article/details/gtcyhakowg.html

[Q03] 增加列
来源：http://dali.hysaishi.cn/Article/details/gtmqkzcjay.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jiagoushi.top/Article/details/gtsvlexwot.html

[Q04] 修改列类型
来源：http://dali.tanke756.top/Article/details/gthwuucqhq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuxming.cn/Article/details/gtduacvbwl.html

[Q05] 重命名列
来源：http://dali.fengsongda.top/Article/details/gticzdpntr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jqgufenzy.top/Article/details/gtjfujurxz.html

[Q06] 删除列
来源：http://dali.jlsjyb.cn/Article/details/gtkdrpywsl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcafkldiv.html

[Q07] 删除表
来源：http://dali.svipenyu.cn/Article/details/gtkmmtyhmq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj20258888.top/Article/details/gttcameccp.html

[Q08] 创建普通索引
来源：http://dali.chenzaomai.com/Article/details/gtwfhtxmkq.html


<!-- 参考信息 -->