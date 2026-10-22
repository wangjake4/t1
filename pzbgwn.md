代发 wailian999

TS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gtwxyavxcp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hywenlv.cn/Article/details/gtyxnjscfg.html

Go:   os.Getwd()
来源：http://dali.svipenyu.cn/Article/details/gtxgfewkoa.html

Ruby: Dir.pwd
来源：http://dali.ybcxt.top/Article/details/gtvhwofnio.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.andypj.xyz/Article/details/gtmsnumzgc.html

[M05] 设置退出码
来源：http://dali.fengsongda.top/Article/details/gtujqcenzo.html

Py:   sys.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gttbvdfdtl.html

PHP:  exit(1);
来源：http://dali.sweek.top/Article/details/gtteqvjjpq.html

JS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtkpjfagzg.html

TS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtmfbuyoep.html

Java: System.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtbgeizjoq.html

Go:   os.Exit(1)
来源：http://dali.sweek.top/Article/details/gttaqfxxyb.html

Ruby: exit 1
来源：http://dali.snrcjt.cn/Article/details/gtqqyelvjf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tanke756.top/Article/details/gthokkljjk.html

[M06] 向标准错误输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibaptxjr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenjidiqi.icu/Article/details/gtartslpog.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.iojbl.cn/Article/details/gtrwmjpnlm.html

JS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gtokiisgck.html

TS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwybwxab.html

Java: System.err.println("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtwyrjevfr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.birdmap.top/Article/details/gtxtuazspu.html

Ruby: warn "err"
来源：http://dali.yongpay.top/Article/details/gthxstijix.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxinkj.top/Article/details/gthbuygycf.html

[M07] 判断是否为主入口
来源：http://dali.cheryme.top/Article/details/gtgatpinqz.html

Py:   if __name__ == "__main__":
来源：http://dali.vqdsnc.cn/Article/details/gtuwzeqron.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuxming.cn/Article/details/gtzmlwdvur.html

JS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gtlogfmzlw.html

TS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gtnobuklli.html

Java: public static void main(String[] args)
来源：http://dali.jinqigufen.top/Article/details/gtgjlmsftt.html

Go:   func main()
来源：http://dali.chenjidiqi.icu/Article/details/gtwgqtzezd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgufenzy.top/Article/details/gtvdzjzqyl.html

C#:   static void Main(string[] args)
来源：http://dali.xuanzx.com/Article/details/gtmbyohqdv.html

[M08] 获取系统与运行时信息
来源：http://dali.ivvv.top/Article/details/gtkblfxhew.html

Py:   platform.system();  platform.python_version()
来源：http://dali.iojbl.cn/Article/details/gtzpxkiemb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cdnleiting.top/Article/details/gtfujtahtt.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gtkjnkzwtb.html

TS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gtmwflpmzh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yvedp.cn/Article/details/gtjzhrkjlk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtingkixoq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.snrcjt.cn/Article/details/gtlyjfkwmr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hongshengwenyu.top/Article/details/gtocwqcwgn.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gttilxubup.html

N. 数据结构与算法
来源：http://dali.cdnleiting.top/Article/details/gtwohnqhpu.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtcwgoilgp.html

[N01] 二分查找（有序数组）
来源：http://dali.hammf.cn/Article/details/gthgpcplyy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlkehfulq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ivvv.top/Article/details/gtjdcztvcw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gtsvkslbox.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gthxkomosb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtaqmfykbv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtgohywkho.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.pycfn.com/Article/details/gtxihkknxe.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtligpbfyx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dianchejie.cn/Article/details/gtpsczoyta.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hywenlv.cn/Article/details/gtkyyznpxw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtfbvzdwda.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gtciebbtff.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtzuuetbaw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shuidangran.top/Article/details/gtgxhallar.html

Go:   slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gtfvwztmni.html

Ruby: arr.sort
来源：http://dali.chenzaomai.com/Article/details/gtvvufpbae.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gzhubu.top/Article/details/gtqsdxhqbq.html

[N03] 快速排序（分治示例）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnehfcjdb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbotamta.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ydzc1.top/Article/details/gttvdcenaw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gtilyicbpv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gtzwounxpy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtoshiebzt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.feifeiyinyue.top/Article/details/gtamdcdlvt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ydzc1.top/Article/details/gthzdmviwt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhongyouzk.top/Article/details/gtwilgkhvf.html

[N04] 斐波那契数列
来源：http://dali.gaohongyu789.top/Article/details/gtqmnepmur.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gtrtgbcbrk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gtpjfdxekg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgdgoscr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxjpardw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gtqwyokixx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinqigfzy.top/Article/details/gtohjexmxe.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gtfirqrpqk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gtldannmgj.html

[N05] 最大公约数
来源：http://dali.bjfxy.top/Article/details/gtobmmbfea.html

Py:   math.gcd(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gthnnpksii.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yanxiufei.cn/Article/details/gtezgaaksi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gtijscbydi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gtppnbgrke.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yanxiufei.cn/Article/details/gtbsqjovga.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jiagoushi.top/Article/details/gtszektytt.html

Ruby: a.gcd(b)
来源：http://dali.sysykeji.top/Article/details/gtcoeknvvo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gtthiuprkv.html

[N06] 判断回文字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdtwlkyl.html

Py:   s == s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzsuuxlrn.html

PHP:  $s === strrev($s);
来源：http://dali.tanke756.top/Article/details/gtirpflslv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtceknnbuz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbsmwypgc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.snrcjt.cn/Article/details/gtjlhjorpv.html

Go:   // 双指针从两端比较
来源：http://dali.zhiwuduotai.top/Article/details/gtknrzezzq.html

Ruby: s == s.reverse
来源：http://dali.hysaishi.cn/Article/details/gtwfoenxya.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gtgqykjyff.html

[N07] 两数之和（返回下标）
来源：http://dali.dashuyun.cn/Article/details/gtlpckbtjv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gaohongyu789.top/Article/details/gtupoikfhl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.haohaochexian.top/Article/details/gtmfhtqnsk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ybcxt.top/Article/details/gtkvbnhqvb.html

TS:   // 手写 Map<string, number>
来源：http://dali.daria6918.cn/Article/details/gtkbzllzub.html

Java: // 手写 HashMap
来源：http://dali.bjfxy.top/Article/details/gtnqlspicv.html

Go:   // 手写 map[int]int
来源：http://dali.nwbrower.top/Article/details/gtpufbaznt.html

Ruby: // 手写 Hash
来源：http://dali.zdqjudy.top/Article/details/gtyxcjghfv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuanzx.com/Article/details/gtteaspajs.html

[N08] 生成全排列
来源：http://dali.yj202588.top/Article/details/gtcdbwwexx.html

Py:   itertools.permutations(arr)
来源：http://dali.tanke756.top/Article/details/gtjtjdpnpw.html

PHP:  // 手写递归交换
来源：http://dali.yj202588.top/Article/details/gtsowipctl.html

JS:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtkunvnofc.html

TS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtbpdaupko.html

Java: // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtpoosmykz.html

Go:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtkkxoggvn.html

Ruby: arr.permutation.to_a
来源：http://dali.sxryk.cn/Article/details/gtnlmvckwp.html

C#:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtxgrdttzv.html

[N09] 栈与队列
来源：http://dali.sysykeji.top/Article/details/gtvtwdxebb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvqzwmlu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtuxsmzosl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gtcsthbsda.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasmydfsr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hysaishi.cn/Article/details/gtzwcjplio.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhixingplan.top/Article/details/gtmzltaskk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gtohbqknvb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.andypj.xyz/Article/details/gtxtayzrjz.html

[N10] 链表节点定义
来源：http://dali.tanke756.top/Article/details/gtbaswomyj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jlsjyb.cn/Article/details/gtkyjuwygt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxuanxn.top/Article/details/gtizzvahyn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.smart0.xyz/Article/details/gttkbomzzi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.svipenyu.cn/Article/details/gtvtdrvbpi.html

Java: class Node { int v; Node next; }
来源：http://dali.ybcxt.top/Article/details/gtpdcfobvs.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xylfe.cn/Article/details/gtyszllmli.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sxryk.cn/Article/details/gtuwoyegko.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.mhx1999.top/Article/details/gtqdseolzl.html

[N11] 二叉树中序遍历
来源：http://dali.hfpthk.cn/Article/details/gtgxzzaypo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhoulong.xyz/Article/details/gttksixdrm.html

PHP:  // 手写递归函数
来源：http://dali.yuanzhike.top/Article/details/gtqsztbvth.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shuidangran.top/Article/details/gtotsoggtn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xziqi.cn/Article/details/gtiuqhlrkn.html

Java: // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtdmimqlyb.html

Go:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gttcfxuifa.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nwbrower.top/Article/details/gtaekzkcfg.html

C#:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gtksmliwxk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gttslndwcg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fzhhl.top/Article/details/gtacpdsgnz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hongshengwenyu.top/Article/details/gtdppjyejm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gthvzoajnj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gaohongyu789.top/Article/details/gtorsbtexg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gtktsmpdlw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.andypj.xyz/Article/details/gtmdjmqjbk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.0kj1m.cn/Article/details/gtwdnvdgal.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gtddbnykbm.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdrvtgfq.html

O. 并发与异步
来源：http://dali.cashguo.top/Article/details/gtgspbfijo.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtsbvijbyx.html

[O01] 启动一个线程
来源：http://dali.fengsongda.top/Article/details/gtmuayhctb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sxryk.cn/Article/details/gtdwpnkfzs.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sufxvd.cn/Article/details/gthovkmgga.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangshuangyany.cn/Article/details/gtlaronvhx.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gthewwzqco.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuxming.cn/Article/details/gtfhbcxbzk.html

Go:   go f()
来源：http://dali.gaohongyu789.top/Article/details/gthjbkbywq.html

Ruby: Thread.new { f }
来源：http://dali.cheryme.top/Article/details/gtcuvivqkq.html

C#:   Task.Run(() => F());
来源：http://dali.redwolf501.top/Article/details/gtfsxpnibd.html

[O02] 使用线程池
来源：http://dali.yonumen.top/Article/details/gtddnswhlj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhiwuduotai.top/Article/details/gtomnihyrg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shangyingyoupin.top/Article/details/gtogvoxbqy.html

JS:   // worker_threads 线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlulmpszj.html

TS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gttemjicdt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sweek.top/Article/details/gtrmkepemj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xuanzx.com/Article/details/gtovnvggzl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shzxlz.cn/Article/details/gtmmlicngl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yueranfly.top/Article/details/gtdiwodtrw.html

[O03] 加锁保护共享数据
来源：http://dali.hammf.cn/Article/details/gtcvbgnfsx.html

Py:   with lock: shared += 1
来源：http://dali.daria6918.cn/Article/details/gtcguppjas.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzudleybg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shangyingyoupin.top/Article/details/gtngmgpadq.html

TS:   // 同 JS
来源：http://dali.ivvv.top/Article/details/gtxacdatuv.html

Java: synchronized (this) { shared++; }
来源：http://dali.dashuyun.cn/Article/details/gtykblfjqn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cucudq.cn/Article/details/gteslenrac.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guowangkeji.top/Article/details/gtioocpyio.html

C#:   lock (gate) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gtyatjydfi.html

[O04] 定义异步函数并等待
来源：http://dali.hnxiangtu.top/Article/details/gtvrscnrzx.html

Py:   async def f():⏎    await g()
来源：http://dali.guowangkeji.top/Article/details/gturqelntk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yanxiufei.cn/Article/details/gtbebsenfc.html

JS:   async function f() { await g(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrgnxlnr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.wangshuangyany.cn/Article/details/gttgkdodfi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigufen.top/Article/details/gtgcmalfli.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.pengpengdd.cyou/Article/details/gtaxzoktgi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yueranfly.top/Article/details/gttnxbdjwf.html

C#:   async Task F() { await G(); }
来源：http://dali.guowangkeji.top/Article/details/gtxsilciwj.html

[O05] 并发执行并等待全部完成
来源：http://dali.fengsongda.top/Article/details/gtvzosallg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhengqikj.top/Article/details/gtpaunkbiz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenzaomai.com/Article/details/gtksriigwb.html

JS:   await Promise.all(tasks)
来源：http://dali.redwolf501.top/Article/details/gtvazlxfbe.html

TS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtayszzqol.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhixingplan.top/Article/details/gtjmujptww.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.0kj1m.cn/Article/details/gtgjwlbijw.html

Ruby: threads.map(&:join)
来源：http://dali.xziqi.cn/Article/details/gtrfceedtp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yangfankeji.com/Article/details/gtbqqqpqyo.html

[O06] 使用进程池
来源：http://dali.zycfv.cn/Article/details/gtpxdswmtb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yueranfly.top/Article/details/gttalvpxmq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shangyingyoupin.top/Article/details/gteiqishep.html

JS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gtriweueit.html

TS:   // child_process / cluster 模块
来源：http://dali.guannengcc.top/Article/details/gtqnmspwkg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ehwqpu.com/Article/details/gtjynfyqwl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shzxlz.cn/Article/details/gtjbswzgdo.html

Ruby: // fork 块
来源：http://dali.sysykeji.top/Article/details/gtlipfapjh.html

C#:   Parallel.For
来源：http://dali.zhixingplan.top/Article/details/gtkvcvwxrg.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtbtfyefhx.html

P. 常用工具函数
来源：http://dali.haohaochexian.top/Article/details/gtzromledw.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtwiaglhhl.html

[P01] 生成 UUID
来源：http://dali.daria6918.cn/Article/details/gtgjjysotm.html

Py:   str(uuid.uuid4())
来源：http://dali.hongshengwenyu.top/Article/details/gtmuwbadzh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.kuanghao11.cn/Article/details/gtmaajovln.html

JS:   crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gthzzhnptt.html

TS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gtqslgrzjg.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gttonefutc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sxryk.cn/Article/details/gttkwzxxck.html

Ruby: SecureRandom.uuid
来源：http://dali.aibaodan.cn/Article/details/gtmoklmcti.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yueranfly.top/Article/details/gtzlxvwfkq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cucudq.cn/Article/details/gtdarmcwgo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigufen.top/Article/details/gtezizwkst.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxzkfjad.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shuidangran.top/Article/details/gtpzsgdwrw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.pengpengdd.cyou/Article/details/gtkoxeqjrp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ppjwa.cn/Article/details/gtmpxgsyjy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwynbypzr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtjvigxgfn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnxiangtu.top/Article/details/gtivtacfji.html

[P03] 生成短随机字符串
来源：http://dali.xylfe.cn/Article/details/gtadjglxir.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.havefunace.top/Article/details/gtauinkkgn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hysaishi.cn/Article/details/gtclgtyeek.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yvedp.cn/Article/details/gtrzxvkfwh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tianlin.xyz/Article/details/gtaqujxovf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnxiangtu.top/Article/details/gtdyfdpzbd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhoulong.xyz/Article/details/gtzlgnpfrp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.meibo888.top/Article/details/gtydegefvt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.dashuyun.cn/Article/details/gtmggywevf.html

[P04] 求长度
来源：http://dali.hnqzz.top/Article/details/gtabondjvc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.andypj.xyz/Article/details/gtypvyyukq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtqvdhjztm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pengpengdd.cyou/Article/details/gtoxwgydeu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuanzhike.top/Article/details/gtytvxbauh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ydzc1.top/Article/details/gtnhhpsncd.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gtfukrmkmp.html

Ruby: x.length;  x.size
来源：http://dali.svipenyu.cn/Article/details/gtcqeqrpft.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoesslpzy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gogol.net.cn/Article/details/gtwppfdneo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.aibaodan.cn/Article/details/gtegebnlba.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daria6918.cn/Article/details/gtkhczqgyt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuanzhike.top/Article/details/gtticbsjws.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hammf.cn/Article/details/gtaosetwbj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhixingplan.top/Article/details/gtmsdhetbe.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nwbrower.top/Article/details/gttuaonscz.html

Ruby: a == b
来源：http://dali.cashguo.top/Article/details/gtwnmilfkb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.0kj1m.cn/Article/details/gtabujmdpu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.kuanghao11.cn/Article/details/gttlsvccko.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.wangshuangyany.cn/Article/details/gtflvgcvkw.html

PHP:  if (empty($x)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkiyboozg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.316326.xyz/Article/details/gtpsfeznwi.html

TS:   if (x == null) {}
来源：http://dali.smart0.xyz/Article/details/gtxinlwajf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gtevnaehxx.html

Go:   if x == nil {}
来源：http://dali.jiagoushi.top/Article/details/gtaindrnfj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cashguo.top/Article/details/gtvvgbgrou.html

C#:   if (x is null) {}
来源：http://dali.yj202588.top/Article/details/gtsmdfdoto.html

[P07] 防抖与节流
来源：http://dali.guannengcc.top/Article/details/gtvqsovqzi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yongpay.top/Article/details/gtxaxghmkc.html

PHP:  // 手写时间戳比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebaevijp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxpcfgvs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gtycbzfggg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.guannengcc.top/Article/details/gtjvgrouvb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.wangshuangyany.cn/Article/details/gtbbnradhc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxinkj.top/Article/details/gtnvfmbgwi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ppjwa.cn/Article/details/gtaggmhegd.html

[P08] 处理浮点精度问题
来源：http://dali.jyoumei.cn/Article/details/gtdkphxuet.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.daxiang520.top/Article/details/gtjuxkodvk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xinyue.icu/Article/details/gtrpviyciq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenzaomai.com/Article/details/gtlsknmlzm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.vqdsnc.cn/Article/details/gtxplgeone.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigfzy.top/Article/details/gthqaugvgy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xylfe.cn/Article/details/gtcacflunq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cqqwz.cn/Article/details/gtrnpphlar.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yueranfly.top/Article/details/gtwnbnbwxl.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtvgnemgae.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xylfe.cn/Article/details/gtyrptdavq.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtdwjkpqhx.html

[Q01] 创建表
来源：http://dali.316326.xyz/Article/details/gtwywhketm.html

CREATE TABLE users (
来源：http://dali.mhx1999.top/Article/details/gtldpvosbx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xylfe.cn/Article/details/gtdbpvhfvq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258888.top/Article/details/gtximtksol.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yonumen.top/Article/details/gtcfzishmb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xylfe.cn/Article/details/gtychhqsud.html

);
来源：http://dali.gzhubu.top/Article/details/gtldgfhyov.html

[Q02] 创建带外键的表
来源：http://dali.fzhhl.top/Article/details/gtsiwlfyvv.html

CREATE TABLE orders (
来源：http://dali.daxiang520.top/Article/details/gtaeilrqtq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqihiztno.html

user_id INT NOT NULL,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanolugws.html

amount DECIMAL(10, 2),
来源：http://dali.yj20258.top/Article/details/gtcnymuciw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.0kj1m.cn/Article/details/gtofyuedxd.html


<!-- 参考信息 -->