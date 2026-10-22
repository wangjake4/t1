代发 wailian999

Ruby: exit 1
来源：http://dali.cdnleiting.top/Article/details/gtcqfunvyz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hammf.cn/Article/details/gtytlitbuu.html

[M06] 向标准错误输出
来源：http://dali.dashuyun.cn/Article/details/gtremowxai.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fzhhl.top/Article/details/gtsjccblku.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gotoacloud.top/Article/details/gtabbipgha.html

JS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxqgtvwm.html

TS:   console.error("err")
来源：http://dali.nwbrower.top/Article/details/gtvmmefpxj.html

Java: System.err.println("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpisxchro.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhongyouzk.top/Article/details/gtmmmqmjxb.html

Ruby: warn "err"
来源：http://dali.havefunace.top/Article/details/gtvqvazeay.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shzxlz.cn/Article/details/gtvfehvndp.html

[M07] 判断是否为主入口
来源：http://dali.jinqigufen.top/Article/details/gtvdihjfpy.html

Py:   if __name__ == "__main__":
来源：http://dali.guowangkeji.top/Article/details/gtebreqlxl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtdagafbda.html

JS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gtsiehqhmx.html

TS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gtrmbeeity.html

Java: public static void main(String[] args)
来源：http://dali.wangdashe.top/Article/details/gtiwkgiogp.html

Go:   func main()
来源：http://dali.nwbrower.top/Article/details/gtbazlmsfj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangdashe.top/Article/details/gtxfnzhenf.html

C#:   static void Main(string[] args)
来源：http://dali.chenlongwang.top/Article/details/gtjujnydbt.html

[M08] 获取系统与运行时信息
来源：http://dali.ivvv.top/Article/details/gtiwxdvgva.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gotoacloud.top/Article/details/gtxonzjtim.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.bjfxy.top/Article/details/gtnjuujxfj.html

JS:   process.platform;  process.version
来源：http://dali.yj202588.top/Article/details/gtsyvexkhp.html

TS:   process.platform;  process.version
来源：http://dali.zhixingplan.top/Article/details/gtdqjummbz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hfpthk.cn/Article/details/gtsjvlxgbw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yueranfly.top/Article/details/gtjhxkyjic.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.redwolf501.top/Article/details/gthepwvuio.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hongshengwenyu.top/Article/details/gtxlmyixeu.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtiudqfxlc.html

N. 数据结构与算法
来源：http://dali.cdnleiting.top/Article/details/gtkcryxphi.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtematxsfh.html

[N01] 二分查找（有序数组）
来源：http://dali.9152youxi.cn/Article/details/gttbwsawif.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtvhohaoxi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sysykeji.top/Article/details/gtwszcemyy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtlasxdwmw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gtomgkwuur.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtclfvdats.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtuuhyvyry.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxinkj.top/Article/details/gtzltdckyw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtwknvtekn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.havefunace.top/Article/details/gtdlejfpnt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtjpzassjb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.snrcjt.cn/Article/details/gtkzqcheed.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gtqgdifdcr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtpiqfbsaw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigufen.top/Article/details/gtqfmmcedu.html

Go:   slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gthgjcpdyu.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gtnuqmtvow.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlroekjv.html

[N03] 快速排序（分治示例）
来源：http://dali.gaohongyu789.top/Article/details/gtohtszcrp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj202588.top/Article/details/gtqqdfbntv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jlsjyb.cn/Article/details/gtyddntnti.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zdqjudy.top/Article/details/gtbazlkklp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobpwmfpt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxinkj.top/Article/details/gtohzesjqn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sufxvd.cn/Article/details/gthvawfuew.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.316326.xyz/Article/details/gtypmllgtn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shangyingyoupin.top/Article/details/gtfqmzgjuk.html

[N04] 斐波那契数列
来源：http://dali.guannengcc.top/Article/details/gtwlkgxeuu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gtufgcwlha.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.pengpengdd.cyou/Article/details/gtefyltnje.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gtoljlzybe.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gtiegemqpx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gtlgeqhwcl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xinyue.icu/Article/details/gtnrlijhgn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gtefovyyjd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtrczljqyx.html

[N05] 最大公约数
来源：http://dali.cashguo.top/Article/details/gtdiudzmrv.html

Py:   math.gcd(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtdwoaxtds.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fengsongda.top/Article/details/gtzmustefx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gtiqrjacsy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmnvvqvi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.kuanghao11.cn/Article/details/gtcdggaeqc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhiwuduotai.top/Article/details/gtyfhcepmw.html

Ruby: a.gcd(b)
来源：http://dali.c1oappe.top/Article/details/gtxdocqlzo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cqqwz.cn/Article/details/gtrfcijobf.html

[N06] 判断回文字符串
来源：http://dali.fzhhl.top/Article/details/gthfhgmbmf.html

Py:   s == s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gtzvdbxhyk.html

PHP:  $s === strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gtbfdmsnhh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtgvearnuy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtjvjttwwj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.dianchejie.cn/Article/details/gthhrofqgg.html

Go:   // 双指针从两端比较
来源：http://dali.kuanghao11.cn/Article/details/gtirjsmwmy.html

Ruby: s == s.reverse
来源：http://dali.gzhubu.top/Article/details/gtipsjhgst.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gtapeaqehg.html

[N07] 两数之和（返回下标）
来源：http://dali.xziqi.cn/Article/details/gtzpamhkck.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yangfankeji.com/Article/details/gtslnwambw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.c1oappe.top/Article/details/gtujdpcqzu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cheryme.top/Article/details/gtqaurvdiv.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenjidiqi.icu/Article/details/gtxqpztfoa.html

Java: // 手写 HashMap
来源：http://dali.yuanzhike.top/Article/details/gtotzjcunx.html

Go:   // 手写 map[int]int
来源：http://dali.shzxlz.cn/Article/details/gtpwwugvos.html

Ruby: // 手写 Hash
来源：http://dali.c1oappe.top/Article/details/gtrsafulou.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnqzz.top/Article/details/gtaerusmpt.html

[N08] 生成全排列
来源：http://dali.gaohongyu789.top/Article/details/gtovkpehnw.html

Py:   itertools.permutations(arr)
来源：http://dali.guowangkeji.top/Article/details/gtyqanxzqr.html

PHP:  // 手写递归交换
来源：http://dali.ydzc1.top/Article/details/gtexzwaujx.html

JS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gttxrlizeo.html

TS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtfqjnjjhe.html

Java: // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpybwazo.html

Go:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gthhaatkuq.html

Ruby: arr.permutation.to_a
来源：http://dali.cucudq.cn/Article/details/gteyrmtonv.html

C#:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtailrwykd.html

[N09] 栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gtbuhqsbmc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ybcxt.top/Article/details/gtxzcauxwg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhuqpabf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gtamhdtdlz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sufxvd.cn/Article/details/gtjlomosod.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.haohaochexian.top/Article/details/gtevylalwg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhongyouzk.top/Article/details/gtlfydcmfr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gtwcnddrzf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gtilajvgnt.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gtxomfagkq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.redwolf501.top/Article/details/gtemwtinng.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhiwuduotai.top/Article/details/gtphqlwjzj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhoulong.xyz/Article/details/gttvwkdipx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.svipenyu.cn/Article/details/gtiqmgkjdq.html

Java: class Node { int v; Node next; }
来源：http://dali.hnxiangtu.top/Article/details/gthnrmokkl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.birdmap.top/Article/details/gtxvpiuxsq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sysykeji.top/Article/details/gtqlyojwki.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yonumen.top/Article/details/gtdqdxolaf.html

[N11] 二叉树中序遍历
来源：http://dali.guowangkeji.top/Article/details/gtndfwzwws.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cheryme.top/Article/details/gtgefdqvys.html

PHP:  // 手写递归函数
来源：http://dali.zycfv.cn/Article/details/gtqnreojsn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pengpengdd.cyou/Article/details/gtrwfvjdrz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.vqdsnc.cn/Article/details/gtzwprkqyx.html

Java: // 手写递归
来源：http://dali.yvedp.cn/Article/details/gthjhvbdhe.html

Go:   // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gtbnxjogfm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fzhhl.top/Article/details/gtslubhjxz.html

C#:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gthcjrdwlo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tian-w.cn/Article/details/gtsuhvwvkx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.iojbl.cn/Article/details/gtmowdynpd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.iojbl.cn/Article/details/gtvdridfzw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hywenlv.cn/Article/details/gtndzocrhe.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gtbuirfrcn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gtecxmzopm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yonumen.top/Article/details/gtgyhimcvd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hysaishi.cn/Article/details/gtmtlqlkht.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gtzxihcpkp.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtgwcyayuu.html

O. 并发与异步
来源：http://dali.ivvv.top/Article/details/gtbaheheuy.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gttffagsqy.html

[O01] 启动一个线程
来源：http://dali.yuxming.cn/Article/details/gtbmqsevjv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ybcxt.top/Article/details/gtmehcnfic.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhengqikj.top/Article/details/gttcxtfcna.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenzaomai.com/Article/details/gtrhmzpamq.html

TS:   // 同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsfkofhp.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlyynnigb.html

Go:   go f()
来源：http://dali.hongshengwenyu.top/Article/details/gtnfuwlahs.html

Ruby: Thread.new { f }
来源：http://dali.jinqigufen.top/Article/details/gtumlpndhy.html

C#:   Task.Run(() => F());
来源：http://dali.andypj.xyz/Article/details/gtwdjtzgny.html

[O02] 使用线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbllnjazc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aizwys.cn/Article/details/gtnafinqxx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sysykeji.top/Article/details/gtzzjgiwik.html

JS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gtrwrkvyol.html

TS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gtkigbuhze.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhengqikj.top/Article/details/gtxmejukdf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinqigufen.top/Article/details/gteplglidj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.dashuyun.cn/Article/details/gtjvkcnbfr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zdqjudy.top/Article/details/gtyeniemyw.html

[O03] 加锁保护共享数据
来源：http://dali.xuetiantiany.cn/Article/details/gtnifpfncc.html

Py:   with lock: shared += 1
来源：http://dali.chenjidiqi.icu/Article/details/gtfvdrhdum.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xuanzx.com/Article/details/gtvzdghlpj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ydzc1.top/Article/details/gtprqovdkm.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gtdjftsjbi.html

Java: synchronized (this) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gtecdkpyke.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gogol.net.cn/Article/details/gtfygxnvnw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jlsjyb.cn/Article/details/gtkjdexlzf.html

C#:   lock (gate) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gtlmlfykzh.html

[O04] 定义异步函数并等待
来源：http://dali.dianchejie.cn/Article/details/gtluwnncyj.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxuanxn.top/Article/details/gtbohgzcks.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrjsqvmaa.html

JS:   async function f() { await g(); }
来源：http://dali.fzhhl.top/Article/details/gtlgisebjs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.316326.xyz/Article/details/gtbfnnjpxm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hnxiangtu.top/Article/details/gtuxhnarwd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hongshengwenyu.top/Article/details/gtoxujoird.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ivvv.top/Article/details/gtqbejfnax.html

C#:   async Task F() { await G(); }
来源：http://dali.feifeiyinyue.top/Article/details/gttvzyphyb.html

[O05] 并发执行并等待全部完成
来源：http://dali.gotoacloud.top/Article/details/gtnwmwocea.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sysykeji.top/Article/details/gtioorwbir.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.mhx1999.top/Article/details/gtvaolxjsx.html

JS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gtbdezfzhs.html

TS:   await Promise.all(tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmwasbpt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cucudq.cn/Article/details/gtpbmqviov.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yongpay.top/Article/details/gttcjasoyy.html

Ruby: threads.map(&:join)
来源：http://dali.zycfv.cn/Article/details/gtfvouahrk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.316326.xyz/Article/details/gtocdraihp.html

[O06] 使用进程池
来源：http://dali.9152youxi.cn/Article/details/gtwhpbzdtw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenjidiqi.icu/Article/details/gtuobpaymc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj20258.top/Article/details/gtjxadjncq.html

JS:   // child_process / cluster 模块
来源：http://dali.tanke756.top/Article/details/gthcjepkqr.html

TS:   // child_process / cluster 模块
来源：http://dali.meibo888.top/Article/details/gtlqitcyel.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yueranfly.top/Article/details/gtgodcdsbk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shangyingyoupin.top/Article/details/gtaupvhxhh.html

Ruby: // fork 块
来源：http://dali.0kj1m.cn/Article/details/gtjuatnjrc.html

C#:   Parallel.For
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfdtzvzk.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gttryumpzs.html

P. 常用工具函数
来源：http://dali.zdqjudy.top/Article/details/gtyiotznrk.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtkbuzhtmk.html

[P01] 生成 UUID
来源：http://dali.cashguo.top/Article/details/gtxucvhoin.html

Py:   str(uuid.uuid4())
来源：http://dali.cashguo.top/Article/details/gtrepjlros.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigfzy.top/Article/details/gtmykytbml.html

JS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gtrdyasykv.html

TS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gtoprftkby.html

Java: UUID.randomUUID().toString()
来源：http://dali.andypj.xyz/Article/details/gtxktmooax.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yueranfly.top/Article/details/gtxjwjllvp.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgufenzy.top/Article/details/gtgbgxtzre.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yuxming.cn/Article/details/gtjysqpvqq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jlsjyb.cn/Article/details/gtptxqfiqm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shuidangran.top/Article/details/gtwbdpzzey.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xylfe.cn/Article/details/gtdyiorwhd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sxryk.cn/Article/details/gtnrcydglr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tian-w.cn/Article/details/gtgpegdeyp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gtyyygdwnp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hnxiangtu.top/Article/details/gthlvktdsj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tanke756.top/Article/details/gtegjclkej.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aizwys.cn/Article/details/gtwmtbuwrt.html

[P03] 生成短随机字符串
来源：http://dali.gaohongyu789.top/Article/details/gtoqvugink.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guowangkeji.top/Article/details/gtkychrilm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwroxspbd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yvedp.cn/Article/details/gtxsyogwkt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sufxvd.cn/Article/details/gtzzkepfgj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guannengcc.top/Article/details/gtihqjmbcj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.9152youxi.cn/Article/details/gtcmgzifum.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.guannengcc.top/Article/details/gtguscrulw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fengsongda.top/Article/details/gtbgrctiob.html

[P04] 求长度
来源：http://dali.hnxiangtu.top/Article/details/gtyjlhnnwj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xuetiantiany.cn/Article/details/gtfrljgubl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtieioxjmu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gtuvspulyg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sufxvd.cn/Article/details/gtupqdyafu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ivvv.top/Article/details/gtulvkfcjy.html

Go:   len(arr);  len(m)
来源：http://dali.svipenyu.cn/Article/details/gtvxkocxnv.html

Ruby: x.length;  x.size
来源：http://dali.xuetiantiany.cn/Article/details/gtpsgxbksl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.haohaochexian.top/Article/details/gtjgovotbn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yongpay.top/Article/details/gtuztfhuhn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xylfe.cn/Article/details/gtljmlueqd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sufxvd.cn/Article/details/gtxaeokpgz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daria6918.cn/Article/details/gtbghmyqua.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258888.top/Article/details/gtvkijzaml.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gogol.net.cn/Article/details/gtpsiodvco.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ehwqpu.com/Article/details/gthgwbeevk.html

Ruby: a == b
来源：http://dali.ydzc1.top/Article/details/gtgwblqzoc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.andypj.xyz/Article/details/gtiiyfbrbo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ydzc1.top/Article/details/gtjqsxcgcw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jqgfzy.top/Article/details/gtkynyuwfk.html

PHP:  if (empty($x)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtiopxmdcu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cucudq.cn/Article/details/gtpzlvgknn.html

TS:   if (x == null) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtezlvklct.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yonumen.top/Article/details/gtttfjgqnh.html

Go:   if x == nil {}
来源：http://dali.jiagoushi.top/Article/details/gtbxuwsizm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.bjfxy.top/Article/details/gthhdqqnwq.html

C#:   if (x is null) {}
来源：http://dali.xziqi.cn/Article/details/gtwaxthexh.html

[P07] 防抖与节流
来源：http://dali.jinqigufen.top/Article/details/gtbyspdtjd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gtiuiovppq.html

PHP:  // 手写时间戳比较
来源：http://dali.hywenlv.cn/Article/details/gtxfmqgmjb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gtbtxgpxhz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gtcuzbnjxy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aizwys.cn/Article/details/gtdxeabjyg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shangyingyoupin.top/Article/details/gtkeimpsdi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dianchejie.cn/Article/details/gtrqdqrqrm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.kuanghao11.cn/Article/details/gtgzyrnnoa.html

[P08] 处理浮点精度问题
来源：http://dali.zhixingplan.top/Article/details/gtugpzjjen.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yonumen.top/Article/details/gtgaelyxvd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.aizwys.cn/Article/details/gtpaammqct.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.bjfxy.top/Article/details/gtynbzghis.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdwkjuuu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.haohaochexian.top/Article/details/gtylrbjdtp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnqzz.top/Article/details/gtgvqfarti.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.quarkkingdee.top/Article/details/gtyykxzkzb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.smart0.xyz/Article/details/gtuasukoii.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtyzlxyabi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.wangdashe.top/Article/details/gtrduhsqni.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtdcnsomvi.html

[Q01] 创建表
来源：http://dali.yj20258.top/Article/details/gtfczbemyv.html

CREATE TABLE users (
来源：http://dali.chenzaomai.com/Article/details/gtohodsseu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigfzy.top/Article/details/gtnajwdhge.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shuidangran.top/Article/details/gtwnmxfbps.html

email VARCHAR(100) UNIQUE,
来源：http://dali.guannengcc.top/Article/details/gtzrxserib.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhengqikj.top/Article/details/gtgrcemvhr.html

);
来源：http://dali.feifeiyinyue.top/Article/details/gtnqopipxd.html

[Q02] 创建带外键的表
来源：http://dali.jlsjyb.cn/Article/details/gtalldcbaa.html

CREATE TABLE orders (
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuuamwzbl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuanzhike.top/Article/details/gtptexzijj.html

user_id INT NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gtvxmbjtze.html

amount DECIMAL(10, 2),
来源：http://dali.cashguo.top/Article/details/gtdzgfiqyb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gthcuahfgt.html

);
来源：http://dali.ppjwa.cn/Article/details/gtqwiopdjq.html

[Q03] 增加列
来源：http://dali.redwolf501.top/Article/details/gtofjdlxjl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenzaomai.com/Article/details/gttbmhhgsh.html

[Q04] 修改列类型
来源：http://dali.ehwqpu.com/Article/details/gtdxdziehd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jiagoushi.top/Article/details/gtopqfrrpd.html

[Q05] 重命名列
来源：http://dali.zhongyouzk.top/Article/details/gtpoyfnapk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigfzy.top/Article/details/gtfgkoibqu.html

[Q06] 删除列
来源：http://dali.meibo888.top/Article/details/gtncpspwyk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdsrmjeef.html

[Q07] 删除表
来源：http://dali.zycfv.cn/Article/details/gtsgpxyvys.html

DROP TABLE IF EXISTS orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtisexcxur.html

[Q08] 创建普通索引
来源：http://dali.yuxming.cn/Article/details/gtdndkiyit.html


<!-- 参考信息 -->