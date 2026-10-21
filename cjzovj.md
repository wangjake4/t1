代发 wailian999

TS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gtdmmzdqxz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ybcxt.top/Article/details/gtoibworfs.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gtbhsqgqna.html

Ruby: Dir.pwd
来源：http://dali.smart0.xyz/Article/details/gtporfctkf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorenpmjw.html

[M05] 设置退出码
来源：http://dali.yvedp.cn/Article/details/gtagtwxtxc.html

Py:   sys.exit(1)
来源：http://dali.havefunace.top/Article/details/gtuwszabeb.html

PHP:  exit(1);
来源：http://dali.haohaochexian.top/Article/details/gtloxhuksu.html

JS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gtmfovvhgb.html

TS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtbzecnrnx.html

Java: System.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtibkwnpoj.html

Go:   os.Exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtjugvarwn.html

Ruby: exit 1
来源：http://dali.shzxlz.cn/Article/details/gtdccyckrx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hywenlv.cn/Article/details/gtguqeabbr.html

[M06] 向标准错误输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpiilkax.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dashuyun.cn/Article/details/gtzfclqhgz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.316326.xyz/Article/details/gtmjsxvbtr.html

JS:   console.error("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtyfkjucli.html

TS:   console.error("err")
来源：http://dali.jlsjyb.cn/Article/details/gtgfipfjpr.html

Java: System.err.println("err")
来源：http://dali.birdmap.top/Article/details/gtyvxtufdv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cheryme.top/Article/details/gtnjssxgrf.html

Ruby: warn "err"
来源：http://dali.316326.xyz/Article/details/gteubplbxq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.birdmap.top/Article/details/gtcohrcjyo.html

[M07] 判断是否为主入口
来源：http://dali.redwolf501.top/Article/details/gtuctffzah.html

Py:   if __name__ == "__main__":
来源：http://dali.jiagoushi.top/Article/details/gtissuzmbr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxinkj.top/Article/details/gtxdcpbakp.html

JS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gtteydefjd.html

TS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtcanxbxmr.html

Java: public static void main(String[] args)
来源：http://dali.aizwys.cn/Article/details/gtlijurhgv.html

Go:   func main()
来源：http://dali.sxryk.cn/Article/details/gtwdulnziv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.9152youxi.cn/Article/details/gtbkizhtbf.html

C#:   static void Main(string[] args)
来源：http://dali.pycfn.com/Article/details/gtnnwjzpeb.html

[M08] 获取系统与运行时信息
来源：http://dali.xziqi.cn/Article/details/gtgtuppstg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.kuanghao11.cn/Article/details/gtsupupgwk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fzhhl.top/Article/details/gtjnkqlfps.html

JS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gtdtxxxpsl.html

TS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gtfakvuhol.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhixingplan.top/Article/details/gtseuxhxjf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jianghu66.top/Article/details/gtehrjvfku.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cdnleiting.top/Article/details/gtpekxkdro.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.c1oappe.top/Article/details/gtjpygvcyp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtgvwokvbs.html

N. 数据结构与算法
来源：http://dali.smart0.xyz/Article/details/gtdtkxebcq.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtvyrltfff.html

[N01] 二分查找（有序数组）
来源：http://dali.andypj.xyz/Article/details/gtrzptheew.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtslfrdujf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.iojbl.cn/Article/details/gtriejqlwv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tanke756.top/Article/details/gtlelhrnjv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtimzhagxu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtafucqdaz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtznjnbafh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenlongwang.top/Article/details/gtitesrdyc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtvheiellf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aibaodan.cn/Article/details/gtntxlkeqx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgufenzy.top/Article/details/gtysjbjevv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngiddaur.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtlkckdysw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gtqrekrjsw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nwbrower.top/Article/details/gtqtuopjpx.html

Go:   slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gtxwdmcksy.html

Ruby: arr.sort
来源：http://dali.jyoumei.cn/Article/details/gtzfgmhgzh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.snrcjt.cn/Article/details/gtqnitdjbk.html

[N03] 快速排序（分治示例）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlndwwrio.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenlongwang.top/Article/details/gtytteblgm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinqigufen.top/Article/details/gtajcuaear.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gtppcbrssv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gtyysgtfyn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuanzx.com/Article/details/gtbindhfdv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shzxlz.cn/Article/details/gtppcjccyi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ivvv.top/Article/details/gtagpvhyjt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.kuanghao11.cn/Article/details/gtebtqhsjw.html

[N04] 斐波那契数列
来源：http://dali.cashguo.top/Article/details/gtrgjggmnc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gtbmlethsh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fzhhl.top/Article/details/gtgshsvghv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtgwjqpaig.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtgvwqgkkb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gtvozuysxm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuxming.cn/Article/details/gtvzqzcnxd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gtzvaguzpm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtrzvvbgyk.html

[N05] 最大公约数
来源：http://dali.cqqwz.cn/Article/details/gtnycbntwe.html

Py:   math.gcd(a, b)
来源：http://dali.sysykeji.top/Article/details/gtnsyzjfqv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgufenzy.top/Article/details/gtfjxqagls.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gtypqjlcul.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzuoifpsz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.bjfxy.top/Article/details/gtxipdnhkq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yonumen.top/Article/details/gtvubbtiet.html

Ruby: a.gcd(b)
来源：http://dali.yj20258888.top/Article/details/gtkxprdtgh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.havefunace.top/Article/details/gtnfuiunoa.html

[N06] 判断回文字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtxgukzmco.html

Py:   s == s[::-1]
来源：http://dali.yuxming.cn/Article/details/gtajkjgkth.html

PHP:  $s === strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gtqpffsdlo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtglbdmsdb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtjijswaft.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnxiangtu.top/Article/details/gtyombyept.html

Go:   // 双指针从两端比较
来源：http://dali.andypj.xyz/Article/details/gtssechaqw.html

Ruby: s == s.reverse
来源：http://dali.cheryme.top/Article/details/gtppbwbico.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yonumen.top/Article/details/gtiaxnapxq.html

[N07] 两数之和（返回下标）
来源：http://dali.bjfxy.top/Article/details/gtwtknyxwz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tianlin.xyz/Article/details/gtmdvgcvma.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gogol.net.cn/Article/details/gtuaatnvwu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xylfe.cn/Article/details/gtjyhfouqe.html

TS:   // 手写 Map<string, number>
来源：http://dali.yanxiufei.cn/Article/details/gtjdkiwegw.html

Java: // 手写 HashMap
来源：http://dali.cdnleiting.top/Article/details/gtqslqfkru.html

Go:   // 手写 map[int]int
来源：http://dali.hnqzz.top/Article/details/gtnvfgjdhg.html

Ruby: // 手写 Hash
来源：http://dali.hongshengwenyu.top/Article/details/gtyunbyyaw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcklcxzj.html

[N08] 生成全排列
来源：http://dali.tanke756.top/Article/details/gtcqknjasr.html

Py:   itertools.permutations(arr)
来源：http://dali.bjfxy.top/Article/details/gtttxruhml.html

PHP:  // 手写递归交换
来源：http://dali.yongpay.top/Article/details/gtfireijuh.html

JS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtquudgamx.html

TS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtfmvetaof.html

Java: // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefsgoxoa.html

Go:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gthyyyrhxy.html

Ruby: arr.permutation.to_a
来源：http://dali.hywenlv.cn/Article/details/gtnvdufrca.html

C#:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtsxcxxsso.html

[N09] 栈与队列
来源：http://dali.jiagoushi.top/Article/details/gtdgwtpspx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daria6918.cn/Article/details/gtzlmrgbqa.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gtynnqhsrc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtnemwtply.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gogol.net.cn/Article/details/gtndolkdpz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuanzhike.top/Article/details/gtxvulnvyz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenlongwang.top/Article/details/gtqqhbhamu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gtmplhtyya.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dianchejie.cn/Article/details/gtmbdpptwy.html

[N10] 链表节点定义
来源：http://dali.cheryme.top/Article/details/gtmgynjiar.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ehwqpu.com/Article/details/gtlpkfcnod.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxuanxn.top/Article/details/gtofszagtv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daxiang520.top/Article/details/gtfpmgewka.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhiwuduotai.top/Article/details/gtiahfsvoz.html

Java: class Node { int v; Node next; }
来源：http://dali.yvedp.cn/Article/details/gtpnpxltgr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ehwqpu.com/Article/details/gtouzitqgw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258.top/Article/details/gtkdqnhuxp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sysykeji.top/Article/details/gtorhfxllv.html

[N11] 二叉树中序遍历
来源：http://dali.xuanzx.com/Article/details/gtszrtzbvb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nwbrower.top/Article/details/gtqyxjgfhe.html

PHP:  // 手写递归函数
来源：http://dali.zdqjudy.top/Article/details/gthflqyuiq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cashguo.top/Article/details/gtuovlznyg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gtkqkmzosd.html

Java: // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gtwlcxadyz.html

Go:   // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gtvcwygsox.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ybcxt.top/Article/details/gtdouuhmet.html

C#:   // 手写递归
来源：http://dali.sysykeji.top/Article/details/gtndfptqun.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.dashuyun.cn/Article/details/gteqcjnurb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj20258.top/Article/details/gtpgolcjcd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yonumen.top/Article/details/gtyykrqrkg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yueranfly.top/Article/details/gtgotiwogj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gttiqzfldk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.redwolf501.top/Article/details/gtsltcvqwc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yuxming.cn/Article/details/gtuvqpdijn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenzaomai.com/Article/details/gtctwgkszt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258.top/Article/details/gtictwpyna.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtoljwvu.html

O. 并发与异步
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznhyqzow.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtzuauvihx.html

[O01] 启动一个线程
来源：http://dali.yj20258888.top/Article/details/gteaczchrb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ybcxt.top/Article/details/gtmtjemeak.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sysykeji.top/Article/details/gttxptkade.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigfzy.top/Article/details/gtijtqqptt.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gtddtbdqty.html

Java: new Thread(() -> f()).start()
来源：http://dali.birdmap.top/Article/details/gtswzlwpau.html

Go:   go f()
来源：http://dali.cucudq.cn/Article/details/gtyizibgta.html

Ruby: Thread.new { f }
来源：http://dali.hysaishi.cn/Article/details/gtluangwsy.html

C#:   Task.Run(() => F());
来源：http://dali.guowangkeji.top/Article/details/gtxnddoasc.html

[O02] 使用线程池
来源：http://dali.vqdsnc.cn/Article/details/gtkipbyopx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jianghu66.top/Article/details/gtlsjrkdjb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigfzy.top/Article/details/gtgtfwmtfz.html

JS:   // worker_threads 线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzlzekzl.html

TS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtvmkaqvmr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hywenlv.cn/Article/details/gtecdhkwbx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aizwys.cn/Article/details/gtgfvqcqgn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.feifeiyinyue.top/Article/details/gthkenszob.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zycfv.cn/Article/details/gtanhilzyg.html

[O03] 加锁保护共享数据
来源：http://dali.wangdashe.top/Article/details/gttxxfqszn.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhsmwlbr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.havefunace.top/Article/details/gtyhmjdpmx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.aibaodan.cn/Article/details/gtudwoxvbu.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gtytrekfeo.html

Java: synchronized (this) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gtzqbukdqf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xinyue.icu/Article/details/gtzjatuice.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yvedp.cn/Article/details/gtetscjsio.html

C#:   lock (gate) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtoghpmuqa.html

[O04] 定义异步函数并等待
来源：http://dali.yj202588.top/Article/details/gtomzqufbx.html

Py:   async def f():⏎    await g()
来源：http://dali.bjfxy.top/Article/details/gtsokkbmpz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.snrcjt.cn/Article/details/gtpwofsdtt.html

JS:   async function f() { await g(); }
来源：http://dali.hammf.cn/Article/details/gthaqtbtsg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gtpgqnwrpp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xinyue.icu/Article/details/gtztvhlvat.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhiwuduotai.top/Article/details/gthbdiyeil.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guannengcc.top/Article/details/gtnyntrmxz.html

C#:   async Task F() { await G(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdiqggmxw.html

[O05] 并发执行并等待全部完成
来源：http://dali.ivvv.top/Article/details/gtvqndqloz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shzxlz.cn/Article/details/gtsnbnzyjf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yvedp.cn/Article/details/gtwvbxopuu.html

JS:   await Promise.all(tasks)
来源：http://dali.jiagoushi.top/Article/details/gtmimtlcwy.html

TS:   await Promise.all(tasks)
来源：http://dali.yueranfly.top/Article/details/gtvfgsayei.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.fengsongda.top/Article/details/gtgdgmjjiz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xinyue.icu/Article/details/gttljtqxjz.html

Ruby: threads.map(&:join)
来源：http://dali.9152youxi.cn/Article/details/gtrhumwdop.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenzaomai.com/Article/details/gtdjxhapct.html

[O06] 使用进程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqlyhxfk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ybcxt.top/Article/details/gtbhbpcqkt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gogol.net.cn/Article/details/gtoxgqfjuh.html

JS:   // child_process / cluster 模块
来源：http://dali.guowangkeji.top/Article/details/gtqaauolvq.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gtgplkjkrl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fengsongda.top/Article/details/gtkwlluogh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpiviirz.html

Ruby: // fork 块
来源：http://dali.iojbl.cn/Article/details/gtookyvhfk.html

C#:   Parallel.For
来源：http://dali.9152youxi.cn/Article/details/gtecpltidl.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtligooerj.html

P. 常用工具函数
来源：http://dali.guannengcc.top/Article/details/gtbcahvdqf.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtbvkrzbnw.html

[P01] 生成 UUID
来源：http://dali.kuanghao11.cn/Article/details/gtjdgkxsgn.html

Py:   str(uuid.uuid4())
来源：http://dali.fzhhl.top/Article/details/gtmalqrjac.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.kuanghao11.cn/Article/details/gtjsfvlmve.html

JS:   crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gtgwmaasnx.html

TS:   crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gtueiavwsd.html

Java: UUID.randomUUID().toString()
来源：http://dali.c1oappe.top/Article/details/gtkshiwdbb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.pycfn.com/Article/details/gtbybmwxln.html

Ruby: SecureRandom.uuid
来源：http://dali.ybcxt.top/Article/details/gtzbxuopea.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.daxiang520.top/Article/details/gtffnebpkf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xuanzx.com/Article/details/gtgdplpzln.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.havefunace.top/Article/details/gtbmjijuvh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shuidangran.top/Article/details/gtqdjlqjua.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.9152youxi.cn/Article/details/gtuhnjzqxa.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuanzx.com/Article/details/gtwxywvfwr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yongpay.top/Article/details/gtjnwqrxgh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtacoiisuh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gtwzjeiixv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenzaomai.com/Article/details/gtbhlhphoe.html

[P03] 生成短随机字符串
来源：http://dali.yvedp.cn/Article/details/gtlniqniqu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pycfn.com/Article/details/gtbmmlibgo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sufxvd.cn/Article/details/gtmjkremxg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yueranfly.top/Article/details/gtxibsdnva.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.c1oappe.top/Article/details/gtqvufdcqt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigufen.top/Article/details/gtodgfalmj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sweek.top/Article/details/gtbifgpuyb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcpaufiom.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ppjwa.cn/Article/details/gtzkkbztvt.html

[P04] 求长度
来源：http://dali.hammf.cn/Article/details/gtcjwcxndn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinqigfzy.top/Article/details/gttmzmgawm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtzogflbcy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gtjysbnrwp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gtphqsadjv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hywenlv.cn/Article/details/gtsgiifsoo.html

Go:   len(arr);  len(m)
来源：http://dali.hysaishi.cn/Article/details/gtupwnhmtc.html

Ruby: x.length;  x.size
来源：http://dali.yuxming.cn/Article/details/gtyekdbule.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gotoacloud.top/Article/details/gtwlftqoci.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zycfv.cn/Article/details/gtwxbvunzn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigufen.top/Article/details/gtadidmbhs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.meibo888.top/Article/details/gtsmqdamfj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daxiang520.top/Article/details/gtwnxchskp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258.top/Article/details/gtbpwkncsc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgufenzy.top/Article/details/gtbxjpxcdz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yvedp.cn/Article/details/gtsrmixbsd.html

Ruby: a == b
来源：http://dali.xuanzx.com/Article/details/gtwqmmbnpa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yonumen.top/Article/details/gtkqnvfhho.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gteyrygtzv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sufxvd.cn/Article/details/gtsxqwbggt.html

PHP:  if (empty($x)) {}
来源：http://dali.yangfankeji.com/Article/details/gtrwakdwil.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.feifeiyinyue.top/Article/details/gtzqapnqol.html

TS:   if (x == null) {}
来源：http://dali.meibo888.top/Article/details/gtlqeibtcy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gtbilrnqeg.html

Go:   if x == nil {}
来源：http://dali.hnxiangtu.top/Article/details/gtnaufxjum.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.iojbl.cn/Article/details/gtbrdcxgai.html

C#:   if (x is null) {}
来源：http://dali.hfpthk.cn/Article/details/gtbbvibdxi.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gttvzectmu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sxryk.cn/Article/details/gtcbawpmvw.html

PHP:  // 手写时间戳比较
来源：http://dali.zhiwuduotai.top/Article/details/gttuhrhzvj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtllkjnfuz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gtzyqorama.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cashguo.top/Article/details/gtjxogsldx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenjidiqi.icu/Article/details/gteyukxxsb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tian-w.cn/Article/details/gtkuvwqoom.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.guannengcc.top/Article/details/gtgndwtvqh.html

[P08] 处理浮点精度问题
来源：http://dali.jianghu66.top/Article/details/gtiljxpgbw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.mhx1999.top/Article/details/gtknxrktqn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtlxpokhns.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cqqwz.cn/Article/details/gtlkstonxr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shzxlz.cn/Article/details/gtotzyylmo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gotoacloud.top/Article/details/gtosornpxc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinghuilouyu.cn/Article/details/gtycnbdghg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.iojbl.cn/Article/details/gtpnlpnudj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dianchejie.cn/Article/details/gttgigffhc.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtvvirtzzc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yvedp.cn/Article/details/gtajnmmxyq.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhhhwuyi.html

[Q01] 创建表
来源：http://dali.dianchejie.cn/Article/details/gtschafgcg.html

CREATE TABLE users (
来源：http://dali.wangdashe.top/Article/details/gtpdmavejs.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gtnwokzgdl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gtnqjepfku.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hfpthk.cn/Article/details/gtrhznjgbl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhoulong.xyz/Article/details/gtksheifcf.html

);
来源：http://dali.yuanzhike.top/Article/details/gtqkemovhx.html

[Q02] 创建带外键的表
来源：http://dali.yanxiufei.cn/Article/details/gtstnpbxpc.html

CREATE TABLE orders (
来源：http://dali.pengpengdd.cyou/Article/details/gtouahfuqw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jianghu66.top/Article/details/gtzbibujuf.html

user_id INT NOT NULL,
来源：http://dali.snrcjt.cn/Article/details/gtnwbpjbqb.html

amount DECIMAL(10, 2),
来源：http://dali.feifeiyinyue.top/Article/details/gtbgidjxya.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuetiantiany.cn/Article/details/gtpjowoilp.html


<!-- 参考信息 -->