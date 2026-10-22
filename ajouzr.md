代发 wailian999

JS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtmlmymbav.html

TS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gteukukuyh.html

Java: System.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtjskgsusn.html

Go:   os.Exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtmegycbtn.html

Ruby: exit 1
来源：http://dali.ppjwa.cn/Article/details/gttxrsjsmw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpczoiavo.html

[M06] 向标准错误输出
来源：http://dali.tanke756.top/Article/details/gthcfphkjs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gtsolguvjw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.316326.xyz/Article/details/gtbhjyanix.html

JS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gtaeuuafqv.html

TS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gtwnadhywe.html

Java: System.err.println("err")
来源：http://dali.jiagoushi.top/Article/details/gtggvovyhz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenzaomai.com/Article/details/gtxjridzzc.html

Ruby: warn "err"
来源：http://dali.yanxiufei.cn/Article/details/gtimqjfhgu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hammf.cn/Article/details/gtcxmadiho.html

[M07] 判断是否为主入口
来源：http://dali.zhengqikj.top/Article/details/gtwwozgcho.html

Py:   if __name__ == "__main__":
来源：http://dali.ywan-chungtsiang.top/Article/details/gtayfsnywb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fzhhl.top/Article/details/gtviouceap.html

JS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gtwpejvyqh.html

TS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gtczofejun.html

Java: public static void main(String[] args)
来源：http://dali.zhongyouzk.top/Article/details/gtfenrqrpq.html

Go:   func main()
来源：http://dali.pengpengdd.cyou/Article/details/gtuqwgqnzb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhiwuduotai.top/Article/details/gtdffczoef.html

C#:   static void Main(string[] args)
来源：http://dali.snrcjt.cn/Article/details/gthaalgnib.html

[M08] 获取系统与运行时信息
来源：http://dali.smart0.xyz/Article/details/gtpzzgnjqp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnqzz.top/Article/details/gtyumbatis.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.kuanghao11.cn/Article/details/gtwlobbeou.html

JS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gtsyndubps.html

TS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gtkingqdjq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgufenzy.top/Article/details/gtutuzrqcx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cashguo.top/Article/details/gtberathkz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.birdmap.top/Article/details/gtsdeqzrrw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hammf.cn/Article/details/gturyravte.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtkrfnrajp.html

N. 数据结构与算法
来源：http://dali.nwbrower.top/Article/details/gteybtvini.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtkhboyeyq.html

[N01] 二分查找（有序数组）
来源：http://dali.iojbl.cn/Article/details/gtqeoxrufn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtktjpsuvr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gtrrwmzfsa.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gtltpexyfk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gttmcjhdbp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gtsxqiydcx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtbbwddblw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gtxiogmoym.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgujdkavg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxinkj.top/Article/details/gtuptsmegx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gtecdlqkyg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.316326.xyz/Article/details/gtimbsaono.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gtcvkpguxs.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gtuvipuvqd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ivvv.top/Article/details/gtlrunjzhe.html

Go:   slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gtqstowzkg.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtvsyicpiz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinqigfzy.top/Article/details/gtxbzsbyev.html

[N03] 快速排序（分治示例）
来源：http://dali.birdmap.top/Article/details/gtbtsiqcdc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.bjfxy.top/Article/details/gtclsihifv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.andypj.xyz/Article/details/gtcncpbwhp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gtuqsjhkje.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxinkj.top/Article/details/gtoeoddwcj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigufen.top/Article/details/gtopxltylt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tanke756.top/Article/details/gtfarysfan.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangshuangyany.cn/Article/details/gtgunntpuw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigufen.top/Article/details/gtaxqzovoo.html

[N04] 斐波那契数列
来源：http://dali.daria6918.cn/Article/details/gtsnrbzhnf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gtqpgkquvc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cucudq.cn/Article/details/gtcgumujgd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtrjiceiid.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzigevfs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cucudq.cn/Article/details/gtcqqmmucn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjiaigcz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gtmdtzvrfc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtasyomgza.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gtkquxdllv.html

Py:   math.gcd(a, b)
来源：http://dali.bjfxy.top/Article/details/gtuvaxnmpq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinqigufen.top/Article/details/gtktiiqwhq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gtqscqxpyd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gtbskovkfc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdugcqpeh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tanke756.top/Article/details/gtjoniocno.html

Ruby: a.gcd(b)
来源：http://dali.xylfe.cn/Article/details/gthkzppeui.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xinyue.icu/Article/details/gtlmzffqik.html

[N06] 判断回文字符串
来源：http://dali.hammf.cn/Article/details/gthhicnuku.html

Py:   s == s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gtjnzrxwbb.html

PHP:  $s === strrev($s);
来源：http://dali.cheryme.top/Article/details/gtljohsusn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtcpebqopd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtrbehelmr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.smart0.xyz/Article/details/gtomxhyird.html

Go:   // 双指针从两端比较
来源：http://dali.yvedp.cn/Article/details/gtcsebachy.html

Ruby: s == s.reverse
来源：http://dali.chenzaomai.com/Article/details/gtpuislrpg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gtlsctzuho.html

[N07] 两数之和（返回下标）
来源：http://dali.nwbrower.top/Article/details/gtezvbcsky.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pycfn.com/Article/details/gttgkxexnb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gogol.net.cn/Article/details/gtbhhoqhhb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzbouqsm.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258.top/Article/details/gtvghztarl.html

Java: // 手写 HashMap
来源：http://dali.mhx1999.top/Article/details/gtrvjttfiz.html

Go:   // 手写 map[int]int
来源：http://dali.gogol.net.cn/Article/details/gtfeznkqeu.html

Ruby: // 手写 Hash
来源：http://dali.yangfankeji.com/Article/details/gtoibmbbuy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ivvv.top/Article/details/gtfqsezdry.html

[N08] 生成全排列
来源：http://dali.daria6918.cn/Article/details/gturnqpkhy.html

Py:   itertools.permutations(arr)
来源：http://dali.yonumen.top/Article/details/gtuvehxwpa.html

PHP:  // 手写递归交换
来源：http://dali.hysaishi.cn/Article/details/gtrgxrmakn.html

JS:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gthnbjpred.html

TS:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtorckjxqc.html

Java: // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtdeoffcvc.html

Go:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtdckolewx.html

Ruby: arr.permutation.to_a
来源：http://dali.xziqi.cn/Article/details/gtjzjueohh.html

C#:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtvtvyqudq.html

[N09] 栈与队列
来源：http://dali.hammf.cn/Article/details/gtdesxnoti.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtkgrzgkhv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gtwexdjrtw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gtpwuzvzpv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cucudq.cn/Article/details/gtfvtyatdk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gthxromaly.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfekttro.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tanke756.top/Article/details/gtwbupmihu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.birdmap.top/Article/details/gtuyivfpfu.html

[N10] 链表节点定义
来源：http://dali.gzhubu.top/Article/details/gthdvvtgtz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenjidiqi.icu/Article/details/gttsmgmcqy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.fzhhl.top/Article/details/gtfrqiqmel.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tianlin.xyz/Article/details/gtlefrradr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cashguo.top/Article/details/gtzaodomiw.html

Java: class Node { int v; Node next; }
来源：http://dali.chenlongwang.top/Article/details/gtifpucgfc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gzhubu.top/Article/details/gtmrxurill.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwlmkieu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenlongwang.top/Article/details/gtbfgqygic.html

[N11] 二叉树中序遍历
来源：http://dali.yonumen.top/Article/details/gtjvaueoqr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.haohaochexian.top/Article/details/gtklseveif.html

PHP:  // 手写递归函数
来源：http://dali.redwolf501.top/Article/details/gtjomioqga.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gtvbrcyqgs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gtbuxaaicf.html

Java: // 手写递归
来源：http://dali.ybcxt.top/Article/details/gtexeapkbb.html

Go:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtflrllqmz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.quarkkingdee.top/Article/details/gtudckxsbo.html

C#:   // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gtwtgvygiw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shzxlz.cn/Article/details/gtgelnbzan.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.guowangkeji.top/Article/details/gtqokgchgp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cqqwz.cn/Article/details/gtcytbyzrf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gtdfqckzlo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gtfccxvxfw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtflqglvpq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhongyouzk.top/Article/details/gtvnhkltmx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yongpay.top/Article/details/gtkwfbsqai.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gtepdndpsg.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtaezdaujb.html

O. 并发与异步
来源：http://dali.gogol.net.cn/Article/details/gtqkqtiefw.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtbsocykut.html

[O01] 启动一个线程
来源：http://dali.dashuyun.cn/Article/details/gtwbtgjond.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hongshengwenyu.top/Article/details/gtdxhpuwqz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xinyue.icu/Article/details/gtoqdjogeg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangdashe.top/Article/details/gtowgrbhci.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gtxmhrrqkx.html

Java: new Thread(() -> f()).start()
来源：http://dali.pengpengdd.cyou/Article/details/gtaccjmooy.html

Go:   go f()
来源：http://dali.pengpengdd.cyou/Article/details/gtcpdbadfn.html

Ruby: Thread.new { f }
来源：http://dali.xuetiantiany.cn/Article/details/gtdapxwoxs.html

C#:   Task.Run(() => F());
来源：http://dali.hnxiangtu.top/Article/details/gtglzjbigs.html

[O02] 使用线程池
来源：http://dali.hysaishi.cn/Article/details/gtxpudontl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sweek.top/Article/details/gthfnqvlbp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guowangkeji.top/Article/details/gtmplpdpvs.html

JS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gtrocjndkx.html

TS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gtfyshehir.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgufenzy.top/Article/details/gtwovxurou.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhongyouzk.top/Article/details/gtseidgivw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jiagoushi.top/Article/details/gtdrrnzboi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sysykeji.top/Article/details/gtozffjdzb.html

[O03] 加锁保护共享数据
来源：http://dali.xylfe.cn/Article/details/gtxklasieb.html

Py:   with lock: shared += 1
来源：http://dali.quarkkingdee.top/Article/details/gtjsqzpdjf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hongshengwenyu.top/Article/details/gtqeuevreq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yvedp.cn/Article/details/gtrlxlprxd.html

TS:   // 同 JS
来源：http://dali.dianchejie.cn/Article/details/gtratvhhqk.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gtpygrwzqq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.bjfxy.top/Article/details/gtuzykbanu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cashguo.top/Article/details/gtqyynlgbm.html

C#:   lock (gate) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gtspuxarvg.html

[O04] 定义异步函数并等待
来源：http://dali.yueranfly.top/Article/details/gtpzuhbxfn.html

Py:   async def f():⏎    await g()
来源：http://dali.sufxvd.cn/Article/details/gtukzhzmdd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.andypj.xyz/Article/details/gttakvviks.html

JS:   async function f() { await g(); }
来源：http://dali.guannengcc.top/Article/details/gtqmzqgtsx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sysykeji.top/Article/details/gtrmcfnklg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yonumen.top/Article/details/gtgpzjlinj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sufxvd.cn/Article/details/gtwuaftrtp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ybcxt.top/Article/details/gtycaaigww.html

C#:   async Task F() { await G(); }
来源：http://dali.ppjwa.cn/Article/details/gtyflrdhbz.html

[O05] 并发执行并等待全部完成
来源：http://dali.gotoacloud.top/Article/details/gtzzihfgin.html

Py:   asyncio.gather(*tasks)
来源：http://dali.birdmap.top/Article/details/gtlzesniky.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dianchejie.cn/Article/details/gtqlxwcikg.html

JS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gtqhnrdgmv.html

TS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gtjecfjlgb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.quarkkingdee.top/Article/details/gtkpuqpjxz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tianlin.xyz/Article/details/gtywbyrxua.html

Ruby: threads.map(&:join)
来源：http://dali.tanke756.top/Article/details/gtuajvllki.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yanxiufei.cn/Article/details/gtaasyuqpo.html

[O06] 使用进程池
来源：http://dali.smart0.xyz/Article/details/gtgqwzozkk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xuetiantiany.cn/Article/details/gtgtrtvovc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhongyouzk.top/Article/details/gtvdackyph.html

JS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gtsbktgdch.html

TS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gtkbezanzy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cucudq.cn/Article/details/gtyjhfjiur.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.meibo888.top/Article/details/gtnlawprwo.html

Ruby: // fork 块
来源：http://dali.svipenyu.cn/Article/details/gtdhsxegwf.html

C#:   Parallel.For
来源：http://dali.ppjwa.cn/Article/details/gtkycbirhe.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtoozhebvd.html

P. 常用工具函数
来源：http://dali.snrcjt.cn/Article/details/gtnsapwicx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtivwtkven.html

[P01] 生成 UUID
来源：http://dali.yj20258888.top/Article/details/gtdcuhlvbj.html

Py:   str(uuid.uuid4())
来源：http://dali.zhiwuduotai.top/Article/details/gtisojflyu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuanzx.com/Article/details/gtaocgvoss.html

JS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gtyumnzgkx.html

TS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gtfsbwzdih.html

Java: UUID.randomUUID().toString()
来源：http://dali.xinyue.icu/Article/details/gtvcswiseq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xylfe.cn/Article/details/gtpqlnpqpr.html

Ruby: SecureRandom.uuid
来源：http://dali.xuetiantiany.cn/Article/details/gtxernbmuj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhoulong.xyz/Article/details/gtfjybocfq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sweek.top/Article/details/gtcioduhot.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hysaishi.cn/Article/details/gttenchiok.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.havefunace.top/Article/details/gtmkdffqbw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.haohaochexian.top/Article/details/gtqrqmcosl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhiwuduotai.top/Article/details/gtsnblbuzp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.birdmap.top/Article/details/gtvdevjxil.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.guannengcc.top/Article/details/gtzmvgriud.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yvedp.cn/Article/details/gteohcjeqd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cashguo.top/Article/details/gtoiwjrgmb.html

[P03] 生成短随机字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtxumnjdvb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ehwqpu.com/Article/details/gtxxxildkj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.feifeiyinyue.top/Article/details/gtrzzbfwar.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gtdpniiyoz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprdmrdmr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aizwys.cn/Article/details/gtrnmmmoik.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guannengcc.top/Article/details/gtgugdzydf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.andypj.xyz/Article/details/gtjmhbutek.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxeqwxvoj.html

[P04] 求长度
来源：http://dali.xuanzx.com/Article/details/gtlktvumnt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cdnleiting.top/Article/details/gttdbidvcb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtiwchrakc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gtydedalmm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gtoniemxvy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guannengcc.top/Article/details/gtpzbmvwxr.html

Go:   len(arr);  len(m)
来源：http://dali.cqqwz.cn/Article/details/gtxmsccnrb.html

Ruby: x.length;  x.size
来源：http://dali.yj202588.top/Article/details/gtjalbselq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.9152youxi.cn/Article/details/gtzomrgcpa.html

[P05] 判断两个对象内容是否相等
来源：http://dali.snrcjt.cn/Article/details/gtzrtemjyu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhengqikj.top/Article/details/gtdylakrul.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nwbrower.top/Article/details/gtuitsxeom.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yongpay.top/Article/details/gtdrlqflan.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gtvrlqnhcz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ehwqpu.com/Article/details/gtclchecil.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zycfv.cn/Article/details/gtorhiukww.html

Ruby: a == b
来源：http://dali.wangshuangyany.cn/Article/details/gtmedskdxw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.9152youxi.cn/Article/details/gthazvphgn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sysykeji.top/Article/details/gtlzeaqdvx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.mhx1999.top/Article/details/gtroqdyvfe.html

PHP:  if (empty($x)) {}
来源：http://dali.yuxming.cn/Article/details/gttmvxzaaq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.haohaochexian.top/Article/details/gtoryurgan.html

TS:   if (x == null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gteyueotpm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.birdmap.top/Article/details/gtxqedtvqs.html

Go:   if x == nil {}
来源：http://dali.hnxiangtu.top/Article/details/gtihfulhtx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhiwuduotai.top/Article/details/gtqwihcqkd.html

C#:   if (x is null) {}
来源：http://dali.sysykeji.top/Article/details/gtbrxciumn.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkwftswj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ydzc1.top/Article/details/gtpeukvuka.html

PHP:  // 手写时间戳比较
来源：http://dali.shzxlz.cn/Article/details/gticiykksx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gtsqggftnx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gtmvfhzodc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxgsbwob.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenlongwang.top/Article/details/gtnyjehjfl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.bjfxy.top/Article/details/gtcmlxlxfh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuetiantiany.cn/Article/details/gtvdtbxuqn.html

[P08] 处理浮点精度问题
来源：http://dali.hnqzz.top/Article/details/gtgqveslmi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmoavobp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yuanzhike.top/Article/details/gtybfjvwqh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhengqikj.top/Article/details/gtexhfcvjm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.wangdashe.top/Article/details/gtveuavgmv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hywenlv.cn/Article/details/gtuqmpjdaw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yanxiufei.cn/Article/details/gtwnawscwp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.snrcjt.cn/Article/details/gtibueiuet.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.fzhhl.top/Article/details/gtovmitxyj.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtimlgfsjz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hfpthk.cn/Article/details/gtyrebtekc.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gteidedamt.html

[Q01] 创建表
来源：http://dali.redwolf501.top/Article/details/gtbzajdbqo.html

CREATE TABLE users (
来源：http://dali.xziqi.cn/Article/details/gtooijsbtg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.andypj.xyz/Article/details/gtvsrokeyq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gtknhwmsrz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnqzz.top/Article/details/gtqdzylkaw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinyuanbaomall.cn/Article/details/gtularxpsp.html

);
来源：http://dali.jqgfzy.top/Article/details/gtdqzeehgm.html

[Q02] 创建带外键的表
来源：http://dali.dashuyun.cn/Article/details/gtkmhvrkuj.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangtech.top/Article/details/gtsodkhwdm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258.top/Article/details/gtuxhinmuy.html

user_id INT NOT NULL,
来源：http://dali.havefunace.top/Article/details/gtnpvqncvv.html

amount DECIMAL(10, 2),
来源：http://dali.gogol.net.cn/Article/details/gtdycnsroc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj20258.top/Article/details/gtedfwqkgn.html

);
来源：http://dali.hnqzz.top/Article/details/gtohpklytw.html

[Q03] 增加列
来源：http://dali.jianghu66.top/Article/details/gtfskfpidd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gotoacloud.top/Article/details/gtikoqqeml.html

[Q04] 修改列类型
来源：http://dali.nanxinkj.top/Article/details/gtguoqsskm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tanke756.top/Article/details/gtuczknlgg.html

[Q05] 重命名列
来源：http://dali.chenjidiqi.icu/Article/details/gtmkztnkeh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hfpthk.cn/Article/details/gtzkigvfmf.html

[Q06] 删除列
来源：http://dali.ehwqpu.com/Article/details/gtiiawiapu.html


<!-- 参考信息 -->