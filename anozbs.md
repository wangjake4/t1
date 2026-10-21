代发 wailian999

[M04] 获取当前工作目录
来源：http://dali.tianlin.xyz/Article/details/gtaihefoke.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gtpwcrfuyl.html

PHP:  getcwd();
来源：http://dali.yuxming.cn/Article/details/gtpakpziqu.html

JS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttftxfvdf.html

TS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gtcwzwqgzw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dashuyun.cn/Article/details/gtekthgtcc.html

Go:   os.Getwd()
来源：http://dali.dashuyun.cn/Article/details/gtlwubbnxs.html

Ruby: Dir.pwd
来源：http://dali.xylfe.cn/Article/details/gtobauhpfj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hammf.cn/Article/details/gtpsatmzlr.html

[M05] 设置退出码
来源：http://dali.redwolf501.top/Article/details/gtzaipvjwq.html

Py:   sys.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtjveuujey.html

PHP:  exit(1);
来源：http://dali.cucudq.cn/Article/details/gtfrubhwqj.html

JS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtpwonjcsy.html

TS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtenahnvgr.html

Java: System.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gttraqmjwy.html

Go:   os.Exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtjthrvgqq.html

Ruby: exit 1
来源：http://dali.pycfn.com/Article/details/gtosknhdsj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tianlin.xyz/Article/details/gtbwhavwov.html

[M06] 向标准错误输出
来源：http://dali.shzxlz.cn/Article/details/gtbwxamnyp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gtmtlejrgx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daxiang520.top/Article/details/gtrkgkszlb.html

JS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gtmzycvagb.html

TS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gtmmbsxgpp.html

Java: System.err.println("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtctlkzuot.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jianghu66.top/Article/details/gtesbgxaol.html

Ruby: warn "err"
来源：http://dali.9152youxi.cn/Article/details/gtypzdirkr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenjidiqi.icu/Article/details/gthbtudcii.html

[M07] 判断是否为主入口
来源：http://dali.ydzc1.top/Article/details/gtttnvdghu.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258888.top/Article/details/gtglrrrmje.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnlzebghn.html

JS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gtyizrkepc.html

TS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gtrmumdykc.html

Java: public static void main(String[] args)
来源：http://dali.kuanghao11.cn/Article/details/gtrtfevnyu.html

Go:   func main()
来源：http://dali.andypj.xyz/Article/details/gtfyqyhtiy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gogol.net.cn/Article/details/gtxcrbxcai.html

C#:   static void Main(string[] args)
来源：http://dali.jyoumei.cn/Article/details/gtnkvlqbst.html

[M08] 获取系统与运行时信息
来源：http://dali.dashuyun.cn/Article/details/gtmiqcrnrg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.haohaochexian.top/Article/details/gtpgilkajj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cashguo.top/Article/details/gtqendvoqh.html

JS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gtcuxqpwja.html

TS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gtjtrqqxel.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xziqi.cn/Article/details/gtmjdioaly.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.smart0.xyz/Article/details/gtmlffuern.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigufen.top/Article/details/gtaxcwpawr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cashguo.top/Article/details/gtucepkojq.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtwmkjeqhz.html

N. 数据结构与算法
来源：http://dali.jyoumei.cn/Article/details/gtmwgnqtvz.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtdoytqtax.html

[N01] 二分查找（有序数组）
来源：http://dali.daria6918.cn/Article/details/gtighnxsft.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtgbtlfjsg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtobuvctnt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtxtuitgds.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtbfdlqzmu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtnnfsmkyd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtvvmutgyy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.316326.xyz/Article/details/gtgxqqtbfk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gtqpaiciol.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dashuyun.cn/Article/details/gtipvuibge.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtnrkninjm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtlsxbietj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gtasnftddz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gtesaqepld.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cheryme.top/Article/details/gtowlanvjz.html

Go:   slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gtdjuppvfb.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gtbxnxpxsg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhoulong.xyz/Article/details/gtoblxhnkn.html

[N03] 快速排序（分治示例）
来源：http://dali.andypj.xyz/Article/details/gtvkijusnj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenlongwang.top/Article/details/gtghcgsnav.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aizwys.cn/Article/details/gthzzmotdl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gtosjlppei.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gtalfdrjjj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangdashe.top/Article/details/gtxhdghlir.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hfpthk.cn/Article/details/gtftuwuisy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ppjwa.cn/Article/details/gtvwyqsgym.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ivvv.top/Article/details/gtmlszcjai.html

[N04] 斐波那契数列
来源：http://dali.mhx1999.top/Article/details/gtgtkuunfa.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gtgdyksbct.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daxiang520.top/Article/details/gtvwbktjri.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gttlhgahhz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtnwxwcrym.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gtcbhdosbk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cdnleiting.top/Article/details/gtbbvrgvic.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtdochlrue.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtpxlvcfdq.html

[N05] 最大公约数
来源：http://dali.shangyingyoupin.top/Article/details/gtweaihzuy.html

Py:   math.gcd(a, b)
来源：http://dali.aizwys.cn/Article/details/gtbgktmbvt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zycfv.cn/Article/details/gtraufwsvc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtnldjxv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gtadmurame.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tanke756.top/Article/details/gtpgdpysll.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gotoacloud.top/Article/details/gtkkwzjoqk.html

Ruby: a.gcd(b)
来源：http://dali.zycfv.cn/Article/details/gtjtudziey.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xinyue.icu/Article/details/gtxnvljcuk.html

[N06] 判断回文字符串
来源：http://dali.pycfn.com/Article/details/gtmvxxmuuv.html

Py:   s == s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gtnibwtnew.html

PHP:  $s === strrev($s);
来源：http://dali.guannengcc.top/Article/details/gtkppxkcpx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtiurnqbrb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsjhshob.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aizwys.cn/Article/details/gtojhqjyje.html

Go:   // 双指针从两端比较
来源：http://dali.0kj1m.cn/Article/details/gtsqqlaska.html

Ruby: s == s.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtijodfjrn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gtrctfmhut.html

[N07] 两数之和（返回下标）
来源：http://dali.quarkkingdee.top/Article/details/gtenpmvhqj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jianghu66.top/Article/details/gtsagadvtm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yangfankeji.com/Article/details/gtupsqmfay.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdszkybk.html

TS:   // 手写 Map<string, number>
来源：http://dali.sweek.top/Article/details/gtdiyjnhtd.html

Java: // 手写 HashMap
来源：http://dali.ivvv.top/Article/details/gtrnqpljbq.html

Go:   // 手写 map[int]int
来源：http://dali.dashuyun.cn/Article/details/gtyfmfihtp.html

Ruby: // 手写 Hash
来源：http://dali.cheryme.top/Article/details/gtnwvlgneo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pengpengdd.cyou/Article/details/gttyztusvh.html

[N08] 生成全排列
来源：http://dali.daxiang520.top/Article/details/gtrrzkojsa.html

Py:   itertools.permutations(arr)
来源：http://dali.yonumen.top/Article/details/gtctwhetfo.html

PHP:  // 手写递归交换
来源：http://dali.aibaodan.cn/Article/details/gtiqcaftfi.html

JS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtidwpeljp.html

TS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gttdeuijlm.html

Java: // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtkhcaibdn.html

Go:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtaawqviwh.html

Ruby: arr.permutation.to_a
来源：http://dali.birdmap.top/Article/details/gtsihudbdb.html

C#:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtjiqisqsc.html

[N09] 栈与队列
来源：http://dali.pycfn.com/Article/details/gteykidtpb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxinkj.top/Article/details/gtnxadxkhy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gtvubeosuc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtsxqwydrv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cdnleiting.top/Article/details/gtofxbocdf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ehwqpu.com/Article/details/gtanyaajgw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tanke756.top/Article/details/gtatxuuyxr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtavtzvumi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.bjfxy.top/Article/details/gtqgouzsrh.html

[N10] 链表节点定义
来源：http://dali.yuxming.cn/Article/details/gtvjjafmdt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jyoumei.cn/Article/details/gtjnzpxmka.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmzpdxcg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtdzqlocvd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenjidiqi.icu/Article/details/gtwqnrppdh.html

Java: class Node { int v; Node next; }
来源：http://dali.yueranfly.top/Article/details/gtcoxbmjss.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenlongwang.top/Article/details/gtwysrzedv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aizwys.cn/Article/details/gthpvxetkr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cucudq.cn/Article/details/gtnfvcdhnq.html

[N11] 二叉树中序遍历
来源：http://dali.yueranfly.top/Article/details/gtaigswlap.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xylfe.cn/Article/details/gtgxelsjef.html

PHP:  // 手写递归函数
来源：http://dali.xinyue.icu/Article/details/gtfvmzrgih.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangshuangyany.cn/Article/details/gtwfweczlo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cheryme.top/Article/details/gthmjxznsm.html

Java: // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbrlihwr.html

Go:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gtuhpbelya.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.kuanghao11.cn/Article/details/gtoorwaihg.html

C#:   // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gtzsgxoovz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.snrcjt.cn/Article/details/gtcctriwsc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daxiang520.top/Article/details/gtiglzlxxd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jiagoushi.top/Article/details/gttuybrmma.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gzhubu.top/Article/details/gtzoolrnkr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gtdypcqdkp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gtpokaziic.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cqqwz.cn/Article/details/gtrvlnjzyy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gtpvtlcvwo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhengqikj.top/Article/details/gtmjfrnhya.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtaneauuwq.html

O. 并发与异步
来源：http://dali.quarkkingdee.top/Article/details/gtzzlreiol.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtfljhkvuo.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gtifekxhqw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.haohaochexian.top/Article/details/gtrjsszkqj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tanke756.top/Article/details/gtrpusvzoc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hongshengwenyu.top/Article/details/gtgkuzojix.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gteuluhfqo.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuxming.cn/Article/details/gthsvgxyds.html

Go:   go f()
来源：http://dali.wangdashe.top/Article/details/gtgkmgqlfo.html

Ruby: Thread.new { f }
来源：http://dali.yanxiufei.cn/Article/details/gtxkyibkoc.html

C#:   Task.Run(() => F());
来源：http://dali.ehwqpu.com/Article/details/gtdvjqjyju.html

[O02] 使用线程池
来源：http://dali.hnxiangtu.top/Article/details/gteypfilvc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gtbjnztoxv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258.top/Article/details/gtvgkwuvrs.html

JS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gtknqtlfpl.html

TS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gtefvxvegg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hammf.cn/Article/details/gtwpudfwsh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.pengpengdd.cyou/Article/details/gttbwwtrmo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ppjwa.cn/Article/details/gtshunfdjk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopmcfadx.html

[O03] 加锁保护共享数据
来源：http://dali.ydzc1.top/Article/details/gtlppgotrz.html

Py:   with lock: shared += 1
来源：http://dali.havefunace.top/Article/details/gtuliduqpl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.dianchejie.cn/Article/details/gtbtfpofyq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cdnleiting.top/Article/details/gtpzqortgt.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gtbzpudjmo.html

Java: synchronized (this) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gtkrarurwo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cqqwz.cn/Article/details/gtbyyompfi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tanke756.top/Article/details/gtqzrjctxc.html

C#:   lock (gate) { shared++; }
来源：http://dali.mhx1999.top/Article/details/gtdlewjomw.html

[O04] 定义异步函数并等待
来源：http://dali.kuanghao11.cn/Article/details/gtvzflaqdb.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigfzy.top/Article/details/gtkrwogepd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxinkj.top/Article/details/gtkeoahxzu.html

JS:   async function f() { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gtdflybofi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gtyiabinpq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cashguo.top/Article/details/gtpzczrlcm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.iojbl.cn/Article/details/gttldogupl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guannengcc.top/Article/details/gtjydwegvr.html

C#:   async Task F() { await G(); }
来源：http://dali.gotoacloud.top/Article/details/gtbqgmfpko.html

[O05] 并发执行并等待全部完成
来源：http://dali.jlsjyb.cn/Article/details/gtnxccxair.html

Py:   asyncio.gather(*tasks)
来源：http://dali.andypj.xyz/Article/details/gtwozuibve.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dashuyun.cn/Article/details/gtnlzcyjbq.html

JS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gtsscsqmhe.html

TS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gtbtugqvwo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hysaishi.cn/Article/details/gtkqfgtgaw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xziqi.cn/Article/details/gttklcqxkj.html

Ruby: threads.map(&:join)
来源：http://dali.guowangkeji.top/Article/details/gtkmexkhth.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgfzy.top/Article/details/gtpabumwbg.html

[O06] 使用进程池
来源：http://dali.quarkkingdee.top/Article/details/gtecmqcrmc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.9152youxi.cn/Article/details/gtvkfrgmvi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtbichuvlv.html

JS:   // child_process / cluster 模块
来源：http://dali.redwolf501.top/Article/details/gtncudoxlz.html

TS:   // child_process / cluster 模块
来源：http://dali.hnqzz.top/Article/details/gtkbydhxst.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jqgfzy.top/Article/details/gtcwfcbwnh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.smart0.xyz/Article/details/gttxruuchr.html

Ruby: // fork 块
来源：http://dali.daxiang520.top/Article/details/gtdplkjmst.html

C#:   Parallel.For
来源：http://dali.ydzc1.top/Article/details/gtjvbkqdui.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtpzqjrano.html

P. 常用工具函数
来源：http://dali.iojbl.cn/Article/details/gtpqnkcnkc.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtqtjaozrm.html

[P01] 生成 UUID
来源：http://dali.nanxuanxn.top/Article/details/gtdemgcvef.html

Py:   str(uuid.uuid4())
来源：http://dali.cdnleiting.top/Article/details/gtazzaufid.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hysaishi.cn/Article/details/gteileoxws.html

JS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gtvcqalbtg.html

TS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gtjhayvpeg.html

Java: UUID.randomUUID().toString()
来源：http://dali.gaohongyu789.top/Article/details/gtxdpsllyj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinqigufen.top/Article/details/gtcbmyphgz.html

Ruby: SecureRandom.uuid
来源：http://dali.quarkkingdee.top/Article/details/gtleaspmlr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigfzy.top/Article/details/gtsxeenttn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ivvv.top/Article/details/gtsxfrtoxe.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhongyouzk.top/Article/details/gthdflmyda.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258888.top/Article/details/gtkmibkufk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gteiyaugvm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guannengcc.top/Article/details/gtuuowtxkq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.snrcjt.cn/Article/details/gtphoispyh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shuidangran.top/Article/details/gtubifrwmx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ybcxt.top/Article/details/gtrgjkxpdl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxuanxn.top/Article/details/gtinnzrjvx.html

[P03] 生成短随机字符串
来源：http://dali.gotoacloud.top/Article/details/gtlrnnuswq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.kuanghao11.cn/Article/details/gttuptutdh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dianchejie.cn/Article/details/gtctgakqou.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dianchejie.cn/Article/details/gtmyqxvtoe.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gtffazgpya.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigfzy.top/Article/details/gtgjqwoxwb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinqigfzy.top/Article/details/gtcurqisbw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gogol.net.cn/Article/details/gtlvkehytp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jianghu66.top/Article/details/gtwlnpvhap.html

[P04] 求长度
来源：http://dali.ybcxt.top/Article/details/gtrxzlrohk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hywenlv.cn/Article/details/gtwytmxisr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtoeekykjf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gtfusonnug.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tian-w.cn/Article/details/gtalaakczq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gtrojtwhbn.html

Go:   len(arr);  len(m)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskekmjyf.html

Ruby: x.length;  x.size
来源：http://dali.cashguo.top/Article/details/gtecrqkdpo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuanzhike.top/Article/details/gtdvvybuna.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ydzc1.top/Article/details/gtyrpvznyn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenlongwang.top/Article/details/gtlkhtnuaf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zdqjudy.top/Article/details/gtbpmdtvkl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.aizwys.cn/Article/details/gtywbcjqhg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ivvv.top/Article/details/gtyhjqzxev.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hysaishi.cn/Article/details/gtsxjgwhny.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtrqiylets.html

Ruby: a == b
来源：http://dali.dianchejie.cn/Article/details/gtkhcfuphe.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jiagoushi.top/Article/details/gtkygjwkgq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fzhhl.top/Article/details/gtkatanrcf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pengpengdd.cyou/Article/details/gtxusmzgwu.html

PHP:  if (empty($x)) {}
来源：http://dali.jiagoushi.top/Article/details/gtbkexjvke.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sysykeji.top/Article/details/gtakxjswxk.html

TS:   if (x == null) {}
来源：http://dali.gotoacloud.top/Article/details/gtkbcoeweq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gtexezqquo.html

Go:   if x == nil {}
来源：http://dali.chenzaomai.com/Article/details/gtomseljim.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.svipenyu.cn/Article/details/gtvvomkxtf.html

C#:   if (x is null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxatjmlm.html

[P07] 防抖与节流
来源：http://dali.nwbrower.top/Article/details/gtxwczrvto.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xuanzx.com/Article/details/gtdrertloj.html

PHP:  // 手写时间戳比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejqqpebu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gtgyvrbqot.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtukuohrpm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hywenlv.cn/Article/details/gtgbvjlgkc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jyoumei.cn/Article/details/gtoqckdsyh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sxryk.cn/Article/details/gtpofjwybo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhiwuduotai.top/Article/details/gtzvsjkuwe.html

[P08] 处理浮点精度问题
来源：http://dali.yuxming.cn/Article/details/gtbxduoltt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ppjwa.cn/Article/details/gtbfifroan.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tanke756.top/Article/details/gtfeatkuot.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.redwolf501.top/Article/details/gtsgbsvvcz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznhejmsq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.quarkkingdee.top/Article/details/gtfpizowwg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemstcgin.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yuanzhike.top/Article/details/gtbejjsnbr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jianghu66.top/Article/details/gtnypjiqwo.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtcwyckaal.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hnxiangtu.top/Article/details/gtmiqvvcxg.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtjzxxckgt.html

[Q01] 创建表
来源：http://dali.kuanghao11.cn/Article/details/gtzaagrkyc.html

CREATE TABLE users (
来源：http://dali.chenlongwang.top/Article/details/gtmkqzfray.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gtyhdcknjg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gtdpvsmwnv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nwbrower.top/Article/details/gtsknsilep.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258.top/Article/details/gtxvhghcls.html

);
来源：http://dali.yanxiufei.cn/Article/details/gtopoxibje.html

[Q02] 创建带外键的表
来源：http://dali.hywenlv.cn/Article/details/gtoyataaad.html

CREATE TABLE orders (
来源：http://dali.ivvv.top/Article/details/gtcmjhxoxh.html


<!-- 参考信息 -->