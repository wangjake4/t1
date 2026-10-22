代发 wailian999

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cheryme.top/Article/details/gtjumdwsyt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hysaishi.cn/Article/details/gthopkirpq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinghuilouyu.cn/Article/details/gtajsscemh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfcxbzkk.html

[M04] 获取当前工作目录
来源：http://dali.cqqwz.cn/Article/details/gthffpsghv.html

Py:   os.getcwd()
来源：http://dali.birdmap.top/Article/details/gtumroujzc.html

PHP:  getcwd();
来源：http://dali.yonumen.top/Article/details/gtggjcombe.html

JS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gthlfsuvpa.html

TS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gttwatemii.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.fzhhl.top/Article/details/gtthjbsqkk.html

Go:   os.Getwd()
来源：http://dali.yanxiufei.cn/Article/details/gtkilojcbl.html

Ruby: Dir.pwd
来源：http://dali.guowangkeji.top/Article/details/gtmvfeslqo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gzhubu.top/Article/details/gtsnmjtwou.html

[M05] 设置退出码
来源：http://dali.zhengqikj.top/Article/details/gtlashxhdq.html

Py:   sys.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gttnljrqem.html

PHP:  exit(1);
来源：http://dali.jianghu66.top/Article/details/gtgpnwnhws.html

JS:   process.exit(1)
来源：http://dali.316326.xyz/Article/details/gtnjvfhxzj.html

TS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtmvjlscte.html

Java: System.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtkdrkazvq.html

Go:   os.Exit(1)
来源：http://dali.andypj.xyz/Article/details/gtyunxwehr.html

Ruby: exit 1
来源：http://dali.xziqi.cn/Article/details/gtunwgcvwk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cdnleiting.top/Article/details/gtpzkpauzd.html

[M06] 向标准错误输出
来源：http://dali.ydzc1.top/Article/details/gtuljncaad.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gthtocelyt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jiagoushi.top/Article/details/gtwdflldwa.html

JS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubhdaqfd.html

TS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gtakvlgklf.html

Java: System.err.println("err")
来源：http://dali.mhx1999.top/Article/details/gtbldagtec.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gtrwloorjl.html

Ruby: warn "err"
来源：http://dali.yj20258888.top/Article/details/gtocmljigj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hammf.cn/Article/details/gtnxvfpawz.html

[M07] 判断是否为主入口
来源：http://dali.yj20258888.top/Article/details/gtmlouilzk.html

Py:   if __name__ == "__main__":
来源：http://dali.dashuyun.cn/Article/details/gtbhofwsuw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhixingplan.top/Article/details/gtptradign.html

JS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gtdorcbwns.html

TS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gtnylootjx.html

Java: public static void main(String[] args)
来源：http://dali.shzxlz.cn/Article/details/gtrmrwnjwd.html

Go:   func main()
来源：http://dali.feifeiyinyue.top/Article/details/gtixslwxrr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuanzx.com/Article/details/gtwzzwntgq.html

C#:   static void Main(string[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gtqzhmkcih.html

[M08] 获取系统与运行时信息
来源：http://dali.yj20258888.top/Article/details/gtxwvslfqi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.birdmap.top/Article/details/gtahrlscfi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.mhx1999.top/Article/details/gtwvdstfca.html

JS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gtftvahcka.html

TS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gtpgcljqog.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hysaishi.cn/Article/details/gthqjmfqew.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xylfe.cn/Article/details/gtfmhgkriq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zdqjudy.top/Article/details/gtpneypkzp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shangyingyoupin.top/Article/details/gtrsjfhmtx.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtosuxfggq.html

N. 数据结构与算法
来源：http://dali.0kj1m.cn/Article/details/gtebijujen.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtwiokugrp.html

[N01] 二分查找（有序数组）
来源：http://dali.sxryk.cn/Article/details/gttvyzlbbn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtwzezkbuw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtjypsokxe.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gthxvlofer.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gtangsexst.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cheryme.top/Article/details/gtkivqsvsw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtikzyoubk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnumkbtv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gttgfqhmae.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.fengsongda.top/Article/details/gtzqormpxx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gtlgfuiwuh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hysaishi.cn/Article/details/gtaghkktqu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtcziyqncs.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gtetjxglli.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shzxlz.cn/Article/details/gtjsjivjiw.html

Go:   slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gtekyliabo.html

Ruby: arr.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjngftnt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinqigfzy.top/Article/details/gthipleyjp.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxinkj.top/Article/details/gtmusnnznl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sxryk.cn/Article/details/gtmzwqcccu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.birdmap.top/Article/details/gtpnxqaena.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gtzpuiliqt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgikbupxw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hammf.cn/Article/details/gtxaetxkww.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangshuangyany.cn/Article/details/gtstgwxtxi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tian-w.cn/Article/details/gtsjgpqlmk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hnxiangtu.top/Article/details/gtwrepmytw.html

[N04] 斐波那契数列
来源：http://dali.wangshuangyany.cn/Article/details/gtbivstvsq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhdwbmde.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj202588.top/Article/details/gtgjddwgsm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgmtgtnm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtxydrowyx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gtduixfouo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sysykeji.top/Article/details/gtvmakpqss.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gtkxoaaopf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclyjqlde.html

[N05] 最大公约数
来源：http://dali.hongshengwenyu.top/Article/details/gttcgbwnou.html

Py:   math.gcd(a, b)
来源：http://dali.meibo888.top/Article/details/gttjyduzbp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tian-w.cn/Article/details/gtxtbmvqnb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gtrjuytdor.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gtnxwfnpei.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258.top/Article/details/gtemyhjqab.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ehwqpu.com/Article/details/gtbdvdotrt.html

Ruby: a.gcd(b)
来源：http://dali.gotoacloud.top/Article/details/gtminzmsvh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.haohaochexian.top/Article/details/gtmdgncizt.html

[N06] 判断回文字符串
来源：http://dali.nwbrower.top/Article/details/gtwbbbqwaq.html

Py:   s == s[::-1]
来源：http://dali.guannengcc.top/Article/details/gthrczrcce.html

PHP:  $s === strrev($s);
来源：http://dali.c1oappe.top/Article/details/gthbwvrcbq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtuohzbkre.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gtzoahogix.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbitaklx.html

Go:   // 双指针从两端比较
来源：http://dali.bjfxy.top/Article/details/gthjavicwx.html

Ruby: s == s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtfyhgwulv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gteulqwqlk.html

[N07] 两数之和（返回下标）
来源：http://dali.gogol.net.cn/Article/details/gtcbmnyzfl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangshuangyany.cn/Article/details/gtoaiuggat.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jlsjyb.cn/Article/details/gtnzrvlqdn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhengqikj.top/Article/details/gtpcglyxiy.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj202588.top/Article/details/gtupposjay.html

Java: // 手写 HashMap
来源：http://dali.jinghuilouyu.cn/Article/details/gtledcmfvf.html

Go:   // 手写 map[int]int
来源：http://dali.xylfe.cn/Article/details/gtbsscdnyw.html

Ruby: // 手写 Hash
来源：http://dali.yj20258.top/Article/details/gtsmlmkbgd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.iojbl.cn/Article/details/gtbltaiuhr.html

[N08] 生成全排列
来源：http://dali.yonumen.top/Article/details/gtaayiazjt.html

Py:   itertools.permutations(arr)
来源：http://dali.sufxvd.cn/Article/details/gtdjijnpfe.html

PHP:  // 手写递归交换
来源：http://dali.ppjwa.cn/Article/details/gtowialnqz.html

JS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtpjrbzfkj.html

TS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtfgrfwisr.html

Java: // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtvmcwvqac.html

Go:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtgokokptv.html

Ruby: arr.permutation.to_a
来源：http://dali.hnqzz.top/Article/details/gtaevbtagg.html

C#:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtqwvzfgoc.html

[N09] 栈与队列
来源：http://dali.ivvv.top/Article/details/gtjyxlobck.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guowangkeji.top/Article/details/gthsncwsub.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtodninhhh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gtlpxialmf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xziqi.cn/Article/details/gtfuudxnhy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guannengcc.top/Article/details/gtcdfdseez.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yvedp.cn/Article/details/gtjkhxavts.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gtmpjxmayv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj202588.top/Article/details/gtiaiblqxl.html

[N10] 链表节点定义
来源：http://dali.cashguo.top/Article/details/gtifwcapsi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuetiantiany.cn/Article/details/gtnyayovys.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jianghu66.top/Article/details/gtdflxwsrt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.meibo888.top/Article/details/gtqbrtaygh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xylfe.cn/Article/details/gtvehfhhhc.html

Java: class Node { int v; Node next; }
来源：http://dali.pycfn.com/Article/details/gtgikysqex.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shuidangran.top/Article/details/gtdmvozrgg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenjidiqi.icu/Article/details/gtakooayfl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinqigfzy.top/Article/details/gtzoorthzz.html

[N11] 二叉树中序遍历
来源：http://dali.hywenlv.cn/Article/details/gtyuzssvmr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hammf.cn/Article/details/gtuombcxsk.html

PHP:  // 手写递归函数
来源：http://dali.svipenyu.cn/Article/details/gtqytsrjob.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gtpqbptxpz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gtebbdtcac.html

Java: // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtmtuxzjww.html

Go:   // 手写递归
来源：http://dali.sweek.top/Article/details/gtzwkwhrta.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sysykeji.top/Article/details/gtbpgesypa.html

C#:   // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gtwjsemyyr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sxryk.cn/Article/details/gtnckibshh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtentwbwbe.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gaohongyu789.top/Article/details/gtkctansji.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhiwuduotai.top/Article/details/gtfncfyrnq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gtjccmjepf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnppddbd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tanke756.top/Article/details/gtvwruksop.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gtpwxepjep.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gtomfisliy.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtinawdlhl.html

O. 并发与异步
来源：http://dali.yj20258888.top/Article/details/gtrkziqszf.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtgxsorizz.html

[O01] 启动一个线程
来源：http://dali.cheryme.top/Article/details/gttdenducn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sweek.top/Article/details/gtfqxssknw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jianghu66.top/Article/details/gtattjpqii.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.fzhhl.top/Article/details/gtbqdpnjgy.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtuycdywfd.html

Java: new Thread(() -> f()).start()
来源：http://dali.xuetiantiany.cn/Article/details/gtqckbjpoy.html

Go:   go f()
来源：http://dali.hongshengwenyu.top/Article/details/gtywqmetmv.html

Ruby: Thread.new { f }
来源：http://dali.yangfankeji.com/Article/details/gtzzwrriyt.html

C#:   Task.Run(() => F());
来源：http://dali.jiagoushi.top/Article/details/gtbahztuss.html

[O02] 使用线程池
来源：http://dali.jqgfzy.top/Article/details/gtyoyamrnx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.haohaochexian.top/Article/details/gtriwvdeon.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dashuyun.cn/Article/details/gtxuannzff.html

JS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gtxqtfngxs.html

TS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gtymtedrdw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gtxmumhuts.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258.top/Article/details/gtrwfzrvhr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fzhhl.top/Article/details/gtdugfjqru.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xuanzx.com/Article/details/gtwwlqmgpy.html

[O03] 加锁保护共享数据
来源：http://dali.jiagoushi.top/Article/details/gtllgjhjyp.html

Py:   with lock: shared += 1
来源：http://dali.ppjwa.cn/Article/details/gtznfvrpmf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangdashe.top/Article/details/gtvyphfloz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.birdmap.top/Article/details/gtekglbmxe.html

TS:   // 同 JS
来源：http://dali.sysykeji.top/Article/details/gtcxvubrhq.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gteykydohe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sweek.top/Article/details/gtpohjmjbs.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.havefunace.top/Article/details/gtgvmevdwt.html

C#:   lock (gate) { shared++; }
来源：http://dali.ivvv.top/Article/details/gtpfozzmkf.html

[O04] 定义异步函数并等待
来源：http://dali.sysykeji.top/Article/details/gtvzwuuhcl.html

Py:   async def f():⏎    await g()
来源：http://dali.zhongyouzk.top/Article/details/gtsbmdldpe.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.bjfxy.top/Article/details/gtpcczures.html

JS:   async function f() { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrtvmerp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ydzc1.top/Article/details/gtpbyripid.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.aizwys.cn/Article/details/gtdqodihik.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenlongwang.top/Article/details/gtvpufjlvg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenjidiqi.icu/Article/details/gtjrezfyif.html

C#:   async Task F() { await G(); }
来源：http://dali.ppjwa.cn/Article/details/gtgsnqjoqu.html

[O05] 并发执行并等待全部完成
来源：http://dali.cqqwz.cn/Article/details/gtcfmmgplu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yueranfly.top/Article/details/gtexzvmnll.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zycfv.cn/Article/details/gtyqiyxprk.html

JS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gtqxvkpqhs.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gtryinphll.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.c1oappe.top/Article/details/gtdslplibh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pycfn.com/Article/details/gtrnimkmgt.html

Ruby: threads.map(&:join)
来源：http://dali.316326.xyz/Article/details/gthwaglbcq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.316326.xyz/Article/details/gttcroqmyi.html

[O06] 使用进程池
来源：http://dali.shzxlz.cn/Article/details/gtlxyxmuix.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fengsongda.top/Article/details/gtobkqvbwm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daxiang520.top/Article/details/gtzxpsfrvp.html

JS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gtcbfsqmip.html

TS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gttmscdfdq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.andypj.xyz/Article/details/gtfvabojvh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gtmwlvvxwp.html

Ruby: // fork 块
来源：http://dali.sxryk.cn/Article/details/gteucdtame.html

C#:   Parallel.For
来源：http://dali.xuanzx.com/Article/details/gtqqwfsvwc.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtkkaimcrb.html

P. 常用工具函数
来源：http://dali.yonumen.top/Article/details/gtcnwowain.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtiedwoast.html

[P01] 生成 UUID
来源：http://dali.smart0.xyz/Article/details/gtzuvagwze.html

Py:   str(uuid.uuid4())
来源：http://dali.xinyue.icu/Article/details/gtymxayslb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jianghu66.top/Article/details/gtezktpace.html

JS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gtqjjvhrru.html

TS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gtevwsiama.html

Java: UUID.randomUUID().toString()
来源：http://dali.ydzc1.top/Article/details/gthyhzafbo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cashguo.top/Article/details/gtfezfpgwj.html

Ruby: SecureRandom.uuid
来源：http://dali.hywenlv.cn/Article/details/gtqrqpurii.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sysykeji.top/Article/details/gtvmhbtwqk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.c1oappe.top/Article/details/gtqqkbaggc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.dashuyun.cn/Article/details/gthqiqrcnm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gaohongyu789.top/Article/details/gtzbnzgkde.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gtdmndiylm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhoulong.xyz/Article/details/gtmtdkndbt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pycfn.com/Article/details/gteiaegzws.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hysaishi.cn/Article/details/gtsozjlgtf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhoulong.xyz/Article/details/gtaorxbmha.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.c1oappe.top/Article/details/gttadcbonb.html

[P03] 生成短随机字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtiyropuep.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hnqzz.top/Article/details/gtkyrymutu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.fengsongda.top/Article/details/gteygjdrpk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gtwsgwacyj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hysaishi.cn/Article/details/gtbrhdckxi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ydzc1.top/Article/details/gtqarhgsam.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.9152youxi.cn/Article/details/gtugtjacev.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xylfe.cn/Article/details/gtdqaxtemf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yanxiufei.cn/Article/details/gtadzplxpw.html

[P04] 求长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdggyyhky.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cashguo.top/Article/details/gtxwosrwdx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtmbufhfkj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gtsgbuodzk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jiagoushi.top/Article/details/gtjdjvsgsb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtkoxgkkke.html

Go:   len(arr);  len(m)
来源：http://dali.hnqzz.top/Article/details/gtbnqqtxak.html

Ruby: x.length;  x.size
来源：http://dali.pengpengdd.cyou/Article/details/gtjwozfawq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gtujpijtjq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yonumen.top/Article/details/gtarriegub.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jianghu66.top/Article/details/gtkebardll.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zycfv.cn/Article/details/gtdmcncwxl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fzhhl.top/Article/details/gtevfdmsvq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tianlin.xyz/Article/details/gtecrqctdt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258888.top/Article/details/gtdupxeath.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.daxiang520.top/Article/details/gtrzdbqotg.html

Ruby: a == b
来源：http://dali.jianghu66.top/Article/details/gtxlymnmkf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yanxiufei.cn/Article/details/gtmnkwtaoo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj202588.top/Article/details/gtuuwnvtct.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hammf.cn/Article/details/gtnnuwlhya.html

PHP:  if (empty($x)) {}
来源：http://dali.9152youxi.cn/Article/details/gtxpskclsk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yonumen.top/Article/details/gtwyuzcmzg.html

TS:   if (x == null) {}
来源：http://dali.cashguo.top/Article/details/gtdapagqfc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqwobzfb.html

Go:   if x == nil {}
来源：http://dali.jqgfzy.top/Article/details/gtgwfwalad.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dashuyun.cn/Article/details/gtwtuqomwd.html

C#:   if (x is null) {}
来源：http://dali.jinqigfzy.top/Article/details/gtlozjnrgp.html

[P07] 防抖与节流
来源：http://dali.yueranfly.top/Article/details/gttceofnsh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhixingplan.top/Article/details/gtxfqbciyj.html

PHP:  // 手写时间戳比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtptswwb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtoyzbcngn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gtjhtkpxhx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.kuanghao11.cn/Article/details/gtwnwywbzh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cqqwz.cn/Article/details/gtnoexvusq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenzaomai.com/Article/details/gtqwutuoxi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqmisjoy.html

[P08] 处理浮点精度问题
来源：http://dali.zdqjudy.top/Article/details/gtxoopssmd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhoulong.xyz/Article/details/gtripyheuw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cheryme.top/Article/details/gtsexainfk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nanxuanxn.top/Article/details/gtstnugwao.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zdqjudy.top/Article/details/gtntglhgfx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhixingplan.top/Article/details/gtuzpzzzgc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xuetiantiany.cn/Article/details/gtyxpftvfk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.svipenyu.cn/Article/details/gtnjgqudgf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxinkj.top/Article/details/gtxkgovzcw.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtwukcrpke.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yonumen.top/Article/details/gtikajbctz.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtiwyjbhwj.html

[Q01] 创建表
来源：http://dali.chenzaomai.com/Article/details/gtaomsrffr.html

CREATE TABLE users (
来源：http://dali.jinghuilouyu.cn/Article/details/gtqkwntaco.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gtgmemmvjo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sysykeji.top/Article/details/gtnmkftyiu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zycfv.cn/Article/details/gtqjfqyrrv.html


<!-- 参考信息 -->