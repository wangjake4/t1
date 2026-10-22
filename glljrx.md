代发 wailian999

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jianghu66.top/Article/details/gtkqoihczp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gtteondggk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gogol.net.cn/Article/details/gtmiigdtwy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.c1oappe.top/Article/details/gtxluryjjs.html

[M04] 获取当前工作目录
来源：http://dali.meibo888.top/Article/details/gthfnqvfut.html

Py:   os.getcwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtvjntxfjd.html

PHP:  getcwd();
来源：http://dali.shangyingyoupin.top/Article/details/gtnwdyvhpd.html

JS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtobjlubjb.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gtmxruzjnb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gtvmtsjhpu.html

Go:   os.Getwd()
来源：http://dali.cucudq.cn/Article/details/gtqbewpkbh.html

Ruby: Dir.pwd
来源：http://dali.svipenyu.cn/Article/details/gtravpdpze.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hammf.cn/Article/details/gtecxojhlf.html

[M05] 设置退出码
来源：http://dali.feifeiyinyue.top/Article/details/gtaeqwqwuj.html

Py:   sys.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtgderfggy.html

PHP:  exit(1);
来源：http://dali.ivvv.top/Article/details/gtmiccyhto.html

JS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gthogfbeas.html

TS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtwvctmxcm.html

Java: System.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtckfumuiw.html

Go:   os.Exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtrqwiyhqs.html

Ruby: exit 1
来源：http://dali.redwolf501.top/Article/details/gtthilkuay.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sxryk.cn/Article/details/gtxucjnrna.html

[M06] 向标准错误输出
来源：http://dali.wangshuangyany.cn/Article/details/gtdvosicxg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj202588.top/Article/details/gtbtqqaezm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuxming.cn/Article/details/gtglqrjvac.html

JS:   console.error("err")
来源：http://dali.yvedp.cn/Article/details/gtobdueekl.html

TS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gtfcchvfgi.html

Java: System.err.println("err")
来源：http://dali.ivvv.top/Article/details/gtejmxnpld.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jlsjyb.cn/Article/details/gtbdxfvgci.html

Ruby: warn "err"
来源：http://dali.jiagoushi.top/Article/details/gtkbexebad.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yueranfly.top/Article/details/gteiwjcmjn.html

[M07] 判断是否为主入口
来源：http://dali.jinqigfzy.top/Article/details/gtpadlfanx.html

Py:   if __name__ == "__main__":
来源：http://dali.smart0.xyz/Article/details/gtbxqncftp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fzhhl.top/Article/details/gtgceyesdc.html

JS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gtpunfmezm.html

TS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gtbewhdxjb.html

Java: public static void main(String[] args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqsxmpls.html

Go:   func main()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqenkqtvm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zdqjudy.top/Article/details/gtamzhvjas.html

C#:   static void Main(string[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gteczgdunc.html

[M08] 获取系统与运行时信息
来源：http://dali.yongpay.top/Article/details/gtjpoxyzib.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daxiang520.top/Article/details/gtyciwrawt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.316326.xyz/Article/details/gtoweyjznl.html

JS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtfzapahqo.html

TS:   process.platform;  process.version
来源：http://dali.yj202588.top/Article/details/gtnerqmihn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gaohongyu789.top/Article/details/gtghxvcxoh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tianlin.xyz/Article/details/gtgssuirrh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yangfankeji.com/Article/details/gtbpvgmpwh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cdnleiting.top/Article/details/gtemfngvig.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtclollxfk.html

N. 数据结构与算法
来源：http://dali.cheryme.top/Article/details/gtjkxakors.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfnchlbf.html

[N01] 二分查找（有序数组）
来源：http://dali.meibo888.top/Article/details/gtvzkfyrxi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtnqhlsafu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gtijlskwym.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gtgrljahbg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gtvmicdppv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtilbcxefz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtqbilecwt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cheryme.top/Article/details/gtcxyjgddw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtusjfnmaq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sufxvd.cn/Article/details/gtomgnubqt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtumiaggkw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtdyhpqzju.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtppgnkqfq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gtfuphgkls.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxuanxn.top/Article/details/gtmfwatdid.html

Go:   slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gtfgsvzvth.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gtloiulkav.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yanxiufei.cn/Article/details/gtltgxzdiu.html

[N03] 快速排序（分治示例）
来源：http://dali.bjfxy.top/Article/details/gtqgyvdfqn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sweek.top/Article/details/gtctlnppll.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yvedp.cn/Article/details/gtgjfyovcy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gtvyitqrbe.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.birdmap.top/Article/details/gthzcftzwp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jlsjyb.cn/Article/details/gtgkqhtwwk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xziqi.cn/Article/details/gtflrjvxcu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daria6918.cn/Article/details/gtexmpliun.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ybcxt.top/Article/details/gtwargzjrq.html

[N04] 斐波那契数列
来源：http://dali.guannengcc.top/Article/details/gtkfhwrpca.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.haohaochexian.top/Article/details/gtcxaomabk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gtbirmfent.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gtbjgchedh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gthsfukznr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daria6918.cn/Article/details/gtlulugvcx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuanzhike.top/Article/details/gtbfcnzewo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gtbflhcnnr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtkqvdeyep.html

[N05] 最大公约数
来源：http://dali.nanxuanxn.top/Article/details/gtoombuqjl.html

Py:   math.gcd(a, b)
来源：http://dali.guannengcc.top/Article/details/gtpjncteug.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtleskgrzq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gtejicpxmi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtlkyvdaub.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cdnleiting.top/Article/details/gtkjajyxeq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yongpay.top/Article/details/gtkkagwppu.html

Ruby: a.gcd(b)
来源：http://dali.xinyue.icu/Article/details/gtwvsrbyla.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiltrqrbx.html

[N06] 判断回文字符串
来源：http://dali.cucudq.cn/Article/details/gtjlxahkds.html

Py:   s == s[::-1]
来源：http://dali.xuanzx.com/Article/details/gtomaccrsi.html

PHP:  $s === strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gtwgrdltuh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtspjcjmcv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtynzmmqrx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpwusvjv.html

Go:   // 双指针从两端比较
来源：http://dali.c1oappe.top/Article/details/gtntsclcoz.html

Ruby: s == s.reverse
来源：http://dali.jianghu66.top/Article/details/gtvgzciafj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gaohongyu789.top/Article/details/gtfqvlravp.html

[N07] 两数之和（返回下标）
来源：http://dali.iojbl.cn/Article/details/gtyopzrcwy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cheryme.top/Article/details/gtwsgwlync.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yangfankeji.com/Article/details/gtndkkstpw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aibaodan.cn/Article/details/gtwytpqoyt.html

TS:   // 手写 Map<string, number>
来源：http://dali.svipenyu.cn/Article/details/gtoxvmodyw.html

Java: // 手写 HashMap
来源：http://dali.cucudq.cn/Article/details/gtbywvpjks.html

Go:   // 手写 map[int]int
来源：http://dali.gaohongyu789.top/Article/details/gtvmnksbpp.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gtavpzpjwl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yanxiufei.cn/Article/details/gtgnhtloag.html

[N08] 生成全排列
来源：http://dali.zdqjudy.top/Article/details/gtpilklgsp.html

Py:   itertools.permutations(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtitboarlx.html

PHP:  // 手写递归交换
来源：http://dali.hammf.cn/Article/details/gtfnlvqmnj.html

JS:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtqqwkjjzk.html

TS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gttngmlwnf.html

Java: // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtwgpnvrum.html

Go:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gttmbpskzw.html

Ruby: arr.permutation.to_a
来源：http://dali.yongpay.top/Article/details/gtekaabutp.html

C#:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gttigkhwne.html

[N09] 栈与队列
来源：http://dali.yj202588.top/Article/details/gtchefxxlj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jyoumei.cn/Article/details/gtqqazxygd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gtqbvhlvtw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.birdmap.top/Article/details/gttziwnlgm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zdqjudy.top/Article/details/gtepsyaalp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yangfankeji.com/Article/details/gtajokyzwx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yongpay.top/Article/details/gtnxpjcjzl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.meibo888.top/Article/details/gtyqptmfae.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yonumen.top/Article/details/gtvxmhjisj.html

[N10] 链表节点定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfcmsoxf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.redwolf501.top/Article/details/gtilmsuusz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yonumen.top/Article/details/gtbhlcjldl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zdqjudy.top/Article/details/gtrpmbkcdv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.smart0.xyz/Article/details/gtlwnzmzwr.html

Java: class Node { int v; Node next; }
来源：http://dali.ehwqpu.com/Article/details/gtrjiaueyj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xuetiantiany.cn/Article/details/gtbczskfym.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuanzhike.top/Article/details/gtkhtxyhqt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cashguo.top/Article/details/gtvgsgxslq.html

[N11] 二叉树中序遍历
来源：http://dali.xinyue.icu/Article/details/gtkelzveya.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.quarkkingdee.top/Article/details/gttnbnvjre.html

PHP:  // 手写递归函数
来源：http://dali.hnxiangtu.top/Article/details/gtkjkzcorw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gtigibllpu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gtcwfhbifq.html

Java: // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtobpeieqc.html

Go:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gtedbznlfu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fzhhl.top/Article/details/gtynvstsme.html

C#:   // 手写递归
来源：http://dali.sysykeji.top/Article/details/gtelbwuxus.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.0kj1m.cn/Article/details/gtysvcogtk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxjswyec.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.dashuyun.cn/Article/details/gtgonmxiyy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinghuilouyu.cn/Article/details/gttgmwachj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ppjwa.cn/Article/details/gtgnwdlulr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gtdgwfhtik.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ydzc1.top/Article/details/gtjmpauenx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pycfn.com/Article/details/gtbfycblfb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gtzabbixng.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtisvlvnfs.html

O. 并发与异步
来源：http://dali.hysaishi.cn/Article/details/gtwtwmigzk.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtxaaznjyb.html

[O01] 启动一个线程
来源：http://dali.pengpengdd.cyou/Article/details/gtfutgfssb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gtyrrpuxfv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gaohongyu789.top/Article/details/gtpnxgqwsy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnnvfgka.html

TS:   // 同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gtanzloafk.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuanzhike.top/Article/details/gtjzteqqds.html

Go:   go f()
来源：http://dali.jqgufenzy.top/Article/details/gtaqbbulad.html

Ruby: Thread.new { f }
来源：http://dali.havefunace.top/Article/details/gtbpymbzjq.html

C#:   Task.Run(() => F());
来源：http://dali.nanxinkj.top/Article/details/gtoiahjlor.html

[O02] 使用线程池
来源：http://dali.meibo888.top/Article/details/gtmwhghvrh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.smart0.xyz/Article/details/gttfclnsss.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangdashe.top/Article/details/gtqfaboyuu.html

JS:   // worker_threads 线程池
来源：http://dali.ydzc1.top/Article/details/gttlshprhb.html

TS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gtbpozkugn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.vqdsnc.cn/Article/details/gtaxmbifay.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnqzz.top/Article/details/gtgdeybgwa.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ehwqpu.com/Article/details/gtgoyrnjuw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zdqjudy.top/Article/details/gtlufzywcv.html

[O03] 加锁保护共享数据
来源：http://dali.zhoulong.xyz/Article/details/gthcbsjgnw.html

Py:   with lock: shared += 1
来源：http://dali.kuanghao11.cn/Article/details/gtsaowvalh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuanzhike.top/Article/details/gticqfyqeu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ydzc1.top/Article/details/gtwinxoxxy.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gthfayabjy.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebnteoxh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.quarkkingdee.top/Article/details/gtlbokcfwq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hfpthk.cn/Article/details/gtavbdpxrd.html

C#:   lock (gate) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gtkgbudyja.html

[O04] 定义异步函数并等待
来源：http://dali.hfpthk.cn/Article/details/gtjmjktcmb.html

Py:   async def f():⏎    await g()
来源：http://dali.daria6918.cn/Article/details/gtjiuuihot.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gaohongyu789.top/Article/details/gtihbdmddc.html

JS:   async function f() { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gtbvncjcaf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.andypj.xyz/Article/details/gtmyfsutaz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenlongwang.top/Article/details/gthbdhfciw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xinyue.icu/Article/details/gthqfkxsrw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.kuanghao11.cn/Article/details/gtlxhcgrul.html

C#:   async Task F() { await G(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtsrohpkaa.html

[O05] 并发执行并等待全部完成
来源：http://dali.ehwqpu.com/Article/details/gtrimawcgy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.mhx1999.top/Article/details/gtqluosarm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sufxvd.cn/Article/details/gtsfyknnyc.html

JS:   await Promise.all(tasks)
来源：http://dali.redwolf501.top/Article/details/gtzedlopfn.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gtiqpzukog.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hywenlv.cn/Article/details/gtytbextfr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.aizwys.cn/Article/details/gteoddrell.html

Ruby: threads.map(&:join)
来源：http://dali.bjfxy.top/Article/details/gttefynslb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.meibo888.top/Article/details/gtjkbekiyk.html

[O06] 使用进程池
来源：http://dali.hongshengwenyu.top/Article/details/gtkqisxyri.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.9152youxi.cn/Article/details/gtpyioycxa.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.havefunace.top/Article/details/gttenbpduu.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gtjikktzef.html

TS:   // child_process / cluster 模块
来源：http://dali.jinqigufen.top/Article/details/gtlyrzhsmx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ppjwa.cn/Article/details/gtyfuipbaq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdxpbmxr.html

Ruby: // fork 块
来源：http://dali.316326.xyz/Article/details/gtyafztspn.html

C#:   Parallel.For
来源：http://dali.yongpay.top/Article/details/gtusnybxjk.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtcwcqiaqq.html

P. 常用工具函数
来源：http://dali.jyoumei.cn/Article/details/gtcktyzomj.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtjyrlmcnp.html

[P01] 生成 UUID
来源：http://dali.jqgfzy.top/Article/details/gtfhrojdex.html

Py:   str(uuid.uuid4())
来源：http://dali.gogol.net.cn/Article/details/gtusmdkfdi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.0kj1m.cn/Article/details/gtmuqeylhn.html

JS:   crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gtvgmifajo.html

TS:   crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gtrgrmckqt.html

Java: UUID.randomUUID().toString()
来源：http://dali.yangfankeji.com/Article/details/gtcdyjtztm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gtaiislntj.html

Ruby: SecureRandom.uuid
来源：http://dali.cucudq.cn/Article/details/gthmmerdtj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.smart0.xyz/Article/details/gtpamceizx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hywenlv.cn/Article/details/gtxmnudnjf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.guowangkeji.top/Article/details/gtrjlkhgxe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtnsyquasm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sysykeji.top/Article/details/gthapqvcwh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgfzy.top/Article/details/gtqvgauzqq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfcttnjbd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sxryk.cn/Article/details/gtribzisxp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cqqwz.cn/Article/details/gtwkrogqzw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ehwqpu.com/Article/details/gtvksstxhr.html

[P03] 生成短随机字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtdndvfmyc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.havefunace.top/Article/details/gtnqupelug.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xuetiantiany.cn/Article/details/gtcaougrbk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtgoejzxri.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtjbcadxuj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.fzhhl.top/Article/details/gteussjrpi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zdqjudy.top/Article/details/gtpheyzdza.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daria6918.cn/Article/details/gttonilywl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnqzz.top/Article/details/gtqppoiyrr.html

[P04] 求长度
来源：http://dali.pycfn.com/Article/details/gtlqiujnhr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ivvv.top/Article/details/gtkmgyksab.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtrgvfhtgx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gtiqahjzsw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gtvrwbuncg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cashguo.top/Article/details/gtntoecfuh.html

Go:   len(arr);  len(m)
来源：http://dali.zycfv.cn/Article/details/gtjjiatybq.html

Ruby: x.length;  x.size
来源：http://dali.yuxming.cn/Article/details/gtxadhypoi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cashguo.top/Article/details/gtogxmsrlq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sysykeji.top/Article/details/gtjmljupko.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigfzy.top/Article/details/gtccfantft.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gzhubu.top/Article/details/gtxaubgreo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.andypj.xyz/Article/details/gtzjcjhkva.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gtcbkpyhbg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinqigfzy.top/Article/details/gtbandobzk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gtpujuganw.html

Ruby: a == b
来源：http://dali.aibaodan.cn/Article/details/gtjvprkhlh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jyoumei.cn/Article/details/gtsgmiwjvd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.mhx1999.top/Article/details/gtddvtcniq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinghuilouyu.cn/Article/details/gtslkdyreh.html

PHP:  if (empty($x)) {}
来源：http://dali.ehwqpu.com/Article/details/gtofnjamgg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxinkj.top/Article/details/gtteznzszq.html

TS:   if (x == null) {}
来源：http://dali.fengsongda.top/Article/details/gtdfjsjzqi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.guannengcc.top/Article/details/gtltzrlwvs.html

Go:   if x == nil {}
来源：http://dali.9152youxi.cn/Article/details/gtjnixzqyc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hysaishi.cn/Article/details/gtmdkkcmdb.html

C#:   if (x is null) {}
来源：http://dali.chenzaomai.com/Article/details/gtvwwkhtfv.html

[P07] 防抖与节流
来源：http://dali.hammf.cn/Article/details/gtvdhvsopq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shangyingyoupin.top/Article/details/gtxciopkzb.html

PHP:  // 手写时间戳比较
来源：http://dali.pengpengdd.cyou/Article/details/gthtxgcofm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgehomad.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gtucmjojdu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgfzy.top/Article/details/gtucvagheh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.svipenyu.cn/Article/details/gttpvhfzmj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cashguo.top/Article/details/gtskdiwlby.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhongyouzk.top/Article/details/gtyxdhpvsr.html

[P08] 处理浮点精度问题
来源：http://dali.wangdashe.top/Article/details/gtptccxbkm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nwbrower.top/Article/details/gtxmjprepa.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jiagoushi.top/Article/details/gtkmrovaeo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sxryk.cn/Article/details/gtglppsqvz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nanxinkj.top/Article/details/gtpkirmbhd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nanxuanxn.top/Article/details/gtukofyiha.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.havefunace.top/Article/details/gtrtmceewt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.mhx1999.top/Article/details/gtzviabztc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tian-w.cn/Article/details/gterenfzaj.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtaqwftbnb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigufen.top/Article/details/gtjasbmwom.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtlxxapsgg.html

[Q01] 创建表
来源：http://dali.cucudq.cn/Article/details/gtxneeqmuh.html

CREATE TABLE users (
来源：http://dali.fengsongda.top/Article/details/gtlgncjzkp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.bjfxy.top/Article/details/gtgwjtxrgy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yangfankeji.com/Article/details/gtellxseee.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gzhubu.top/Article/details/gtcdgrpmmf.html


<!-- 参考信息 -->