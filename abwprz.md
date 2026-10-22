代发 wailian999

JS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtajafqpft.html

TS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gtbgdibebg.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtofbefpcs.html

Go:   os.Args[1:]
来源：http://dali.hammf.cn/Article/details/gtjqlxddlg.html

Ruby: ARGV
来源：http://dali.yanxiufei.cn/Article/details/gtbdlsijpc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.c1oappe.top/Article/details/gtnqybevei.html

[M02] 读取环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gtpmpalpeq.html

Py:   os.environ.get("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtpvwtnhko.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gtsnlhmfbp.html

JS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrqpjymn.html

TS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gtttfmhcjs.html

Java: System.getenv("HOME")
来源：http://dali.jianghu66.top/Article/details/gtohldaoze.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daxiang520.top/Article/details/gtvnvwmuet.html

Ruby: ENV["HOME"]
来源：http://dali.xinyue.icu/Article/details/gtgxlzvogn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtuoypwkui.html

[M03] 执行外部命令
来源：http://dali.fzhhl.top/Article/details/gtcdeahjnt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shzxlz.cn/Article/details/gtelnajrxu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258.top/Article/details/gtjzioilnl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gtkwvtczbc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gtoexbhohs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tianlin.xyz/Article/details/gtvngbmxfo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ybcxt.top/Article/details/gtprnnmofi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gtwlvbhego.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnxiangtu.top/Article/details/gtxqskonbw.html

[M04] 获取当前工作目录
来源：http://dali.ybcxt.top/Article/details/gthkunhaan.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtipesszyb.html

PHP:  getcwd();
来源：http://dali.haohaochexian.top/Article/details/gtfluyelej.html

JS:   process.cwd()
来源：http://dali.jianghu66.top/Article/details/gtloolmzlk.html

TS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gtsdaxtuyw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dianchejie.cn/Article/details/gtztflxvra.html

Go:   os.Getwd()
来源：http://dali.sxryk.cn/Article/details/gtorqnkhay.html

Ruby: Dir.pwd
来源：http://dali.gaohongyu789.top/Article/details/gtiuxiirvw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hongshengwenyu.top/Article/details/gteiaygkfw.html

[M05] 设置退出码
来源：http://dali.yueranfly.top/Article/details/gtfaapsdqk.html

Py:   sys.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtbndhqwtx.html

PHP:  exit(1);
来源：http://dali.hongshengwenyu.top/Article/details/gttfllgjip.html

JS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtxryhjoos.html

TS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtcjnuiphy.html

Java: System.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtjgzmnjqs.html

Go:   os.Exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtoqxwotna.html

Ruby: exit 1
来源：http://dali.hnxiangtu.top/Article/details/gtonwyghyo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gtdgxjewgy.html

[M06] 向标准错误输出
来源：http://dali.daria6918.cn/Article/details/gtvvclwpsk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhoulong.xyz/Article/details/gtcqzlojsn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hysaishi.cn/Article/details/gtoxghxayl.html

JS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gtumynbyag.html

TS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtjbuytvpx.html

Java: System.err.println("err")
来源：http://dali.smart0.xyz/Article/details/gtexhodqrj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ivvv.top/Article/details/gtxatgadiu.html

Ruby: warn "err"
来源：http://dali.yangfankeji.com/Article/details/gtogwsnfwd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aizwys.cn/Article/details/gtjxeeqblc.html

[M07] 判断是否为主入口
来源：http://dali.zdqjudy.top/Article/details/gteamqxfxj.html

Py:   if __name__ == "__main__":
来源：http://dali.yonumen.top/Article/details/gtoprklzuu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangshuangyany.cn/Article/details/gtoulfckpi.html

JS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gtcwbwsite.html

TS:   require.main === module
来源：http://dali.smart0.xyz/Article/details/gtfiwdqunb.html

Java: public static void main(String[] args)
来源：http://dali.cucudq.cn/Article/details/gtotpuuzon.html

Go:   func main()
来源：http://dali.ivvv.top/Article/details/gtzrsqdsdl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ydzc1.top/Article/details/gtpappdjyo.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkavabxz.html

[M08] 获取系统与运行时信息
来源：http://dali.hysaishi.cn/Article/details/gtiimjviyc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gotoacloud.top/Article/details/gtspmwcwwe.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shzxlz.cn/Article/details/gtbtaxailm.html

JS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gtoovfigqm.html

TS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gtimgfiwzx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.0kj1m.cn/Article/details/gtcteueepb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ehwqpu.com/Article/details/gtifmgrkku.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.bjfxy.top/Article/details/gtbwzaetuw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuanzx.com/Article/details/gthlnbbhqh.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtaxtflahf.html

N. 数据结构与算法
来源：http://dali.sufxvd.cn/Article/details/gtfgbichgw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtpdttxudd.html

[N01] 二分查找（有序数组）
来源：http://dali.zhixingplan.top/Article/details/gtnsoimgtg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtfsbmgqup.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tian-w.cn/Article/details/gtndqiibvm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtuskowidw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtsjicdbij.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtnaowifed.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtiumroqzu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tanke756.top/Article/details/gtfbrcdwml.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtfrftwhmk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hywenlv.cn/Article/details/gtmhelcery.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gtthoakhdy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jianghu66.top/Article/details/gtbkcfbwpx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtetqwzazk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gtrogobtcx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daxiang520.top/Article/details/gttvnyvdjp.html

Go:   slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gtnvxrlqvm.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gtbqqlebzc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cheryme.top/Article/details/gtnjmjxdwx.html

[N03] 快速排序（分治示例）
来源：http://dali.cucudq.cn/Article/details/gtpkkcuzjp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yongpay.top/Article/details/gtbxzdfnhu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.vqdsnc.cn/Article/details/gtfswcstmj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gtcdqowksw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gtznhnvdbw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.snrcjt.cn/Article/details/gtsxpaxzxj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.haohaochexian.top/Article/details/gtwlbakqxn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hysaishi.cn/Article/details/gtgtjhgpgw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhixingplan.top/Article/details/gtzgmvjcox.html

[N04] 斐波那契数列
来源：http://dali.yj20258.top/Article/details/gtkliqiybj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gtbdtqgkfp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yueranfly.top/Article/details/gtneonqxml.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtwqxqkpvi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtolwtimnu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgaehrxx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.vqdsnc.cn/Article/details/gteknkovcw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtrbwclrgq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtiuvywudb.html

[N05] 最大公约数
来源：http://dali.9152youxi.cn/Article/details/gtnizyglyo.html

Py:   math.gcd(a, b)
来源：http://dali.jianghu66.top/Article/details/gthlfgduum.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yvedp.cn/Article/details/gtvjqnwrvq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aizwys.cn/Article/details/gtngpnskvs.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gtmmgnqtao.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhiwuduotai.top/Article/details/gtzfymsjlb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xylfe.cn/Article/details/gtojuzfbhz.html

Ruby: a.gcd(b)
来源：http://dali.redwolf501.top/Article/details/gtxogdlxmg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsftqlzyd.html

[N06] 判断回文字符串
来源：http://dali.316326.xyz/Article/details/gtqjpanhgs.html

Py:   s == s[::-1]
来源：http://dali.havefunace.top/Article/details/gtfsqebopx.html

PHP:  $s === strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gtjbwtnnju.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtjvfdxair.html

TS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtaualmniy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.fzhhl.top/Article/details/gtetozgmiu.html

Go:   // 双指针从两端比较
来源：http://dali.jiagoushi.top/Article/details/gthqkumusk.html

Ruby: s == s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxyfrqgf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflzxodlt.html

[N07] 两数之和（返回下标）
来源：http://dali.xylfe.cn/Article/details/gtorsyodmo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.316326.xyz/Article/details/gtmulsgdlj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhiwuduotai.top/Article/details/gtqguskzuv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgufenzy.top/Article/details/gtbhzwtcgi.html

TS:   // 手写 Map<string, number>
来源：http://dali.dashuyun.cn/Article/details/gtjsslrhld.html

Java: // 手写 HashMap
来源：http://dali.smart0.xyz/Article/details/gtzlbiipfh.html

Go:   // 手写 map[int]int
来源：http://dali.hnxiangtu.top/Article/details/gtpshzxkqy.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gteuaekajr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dianchejie.cn/Article/details/gtqkttouvr.html

[N08] 生成全排列
来源：http://dali.hnqzz.top/Article/details/gttzumcfzq.html

Py:   itertools.permutations(arr)
来源：http://dali.iojbl.cn/Article/details/gtsmjijuoa.html

PHP:  // 手写递归交换
来源：http://dali.wangdashe.top/Article/details/gtfuouwjws.html

JS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtpvaniwbi.html

TS:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtqrnbudsy.html

Java: // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtmhojsgcf.html

Go:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtvepzoqii.html

Ruby: arr.permutation.to_a
来源：http://dali.daria6918.cn/Article/details/gtmrdrlgxa.html

C#:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtbndapcpo.html

[N09] 栈与队列
来源：http://dali.bjfxy.top/Article/details/gtjkufiewy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sufxvd.cn/Article/details/gtkrkjirfz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gtcuixhzrw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gtkfremvww.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zdqjudy.top/Article/details/gtutnedlps.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tianlin.xyz/Article/details/gtomfakkxe.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zdqjudy.top/Article/details/gtwztaehfx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aizwys.cn/Article/details/gthkkreggb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yangfankeji.com/Article/details/gtwcenpiwo.html

[N10] 链表节点定义
来源：http://dali.cheryme.top/Article/details/gtopildwdu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.bjfxy.top/Article/details/gtnfkviegk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.pycfn.com/Article/details/gtjcoxcnqo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xziqi.cn/Article/details/gtklhvirti.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cashguo.top/Article/details/gtxsumcbak.html

Java: class Node { int v; Node next; }
来源：http://dali.shuidangran.top/Article/details/gtjlcdgkdt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daxiang520.top/Article/details/gtzvgvcwqu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.haohaochexian.top/Article/details/gtjvgstaua.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gotoacloud.top/Article/details/gtirvdghsl.html

[N11] 二叉树中序遍历
来源：http://dali.ehwqpu.com/Article/details/gtwkhrwzgr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbvazqyn.html

PHP:  // 手写递归函数
来源：http://dali.316326.xyz/Article/details/gtfjcathtf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dashuyun.cn/Article/details/gtvrfhmyau.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.mhx1999.top/Article/details/gtpncxwicy.html

Java: // 手写递归
来源：http://dali.guannengcc.top/Article/details/gtsjhixgmd.html

Go:   // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gtmsvuooto.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsrnoudl.html

C#:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gtmjxggjjv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shzxlz.cn/Article/details/gtzpcovyal.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yueranfly.top/Article/details/gttdxrpgoc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.kuanghao11.cn/Article/details/gttvviaaja.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gtuhktiqgd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gtjldmzbdk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gtvwrgbafg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jlsjyb.cn/Article/details/gtidtusqxn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.birdmap.top/Article/details/gtwhxsvdic.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gtrufjnrru.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtdmstofkv.html

O. 并发与异步
来源：http://dali.yuanzhike.top/Article/details/gtgnkwjrwd.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtwpzrwkvm.html

[O01] 启动一个线程
来源：http://dali.hammf.cn/Article/details/gtfxgcgxkd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenlongwang.top/Article/details/gtcotkknco.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jlsjyb.cn/Article/details/gtuowoaakr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tanke756.top/Article/details/gttodsqeka.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gtnhuglytv.html

Java: new Thread(() -> f()).start()
来源：http://dali.c1oappe.top/Article/details/gtdwsfujrt.html

Go:   go f()
来源：http://dali.cheryme.top/Article/details/gtzmgefrjt.html

Ruby: Thread.new { f }
来源：http://dali.yueranfly.top/Article/details/gtjgjanbkl.html

C#:   Task.Run(() => F());
来源：http://dali.sxryk.cn/Article/details/gtveybbqfv.html

[O02] 使用线程池
来源：http://dali.hfpthk.cn/Article/details/gtkwvftlqx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.meibo888.top/Article/details/gtebrnugbp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yuanzhike.top/Article/details/gtjiavzrxu.html

JS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gtaobqygsa.html

TS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gtrwbaoabj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmyhtiod.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xinyue.icu/Article/details/gtftgyqves.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gogol.net.cn/Article/details/gtvysedkxv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhixingplan.top/Article/details/gtogenmiup.html

[O03] 加锁保护共享数据
来源：http://dali.yvedp.cn/Article/details/gtwifxnwzx.html

Py:   with lock: shared += 1
来源：http://dali.hysaishi.cn/Article/details/gtchhaovxj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.vqdsnc.cn/Article/details/gtivclapyz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cucudq.cn/Article/details/gtadvemnnk.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gtxycvseui.html

Java: synchronized (this) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gtzaogxtdw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.feifeiyinyue.top/Article/details/gtpnbkmyno.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhongyouzk.top/Article/details/gtrbuefqjm.html

C#:   lock (gate) { shared++; }
来源：http://dali.pycfn.com/Article/details/gtziplsvdc.html

[O04] 定义异步函数并等待
来源：http://dali.yueranfly.top/Article/details/gtrricyugh.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncrmnsaj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hammf.cn/Article/details/gtrsvtxagt.html

JS:   async function f() { await g(); }
来源：http://dali.yangfankeji.com/Article/details/gtneywhkgo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ehwqpu.com/Article/details/gtcwntvqbs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.aizwys.cn/Article/details/gtqjeetqpo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gaohongyu789.top/Article/details/gtidhgjttb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigufen.top/Article/details/gtfnynquik.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258888.top/Article/details/gtyovxatzu.html

[O05] 并发执行并等待全部完成
来源：http://dali.cdnleiting.top/Article/details/gtdicoquld.html

Py:   asyncio.gather(*tasks)
来源：http://dali.snrcjt.cn/Article/details/gthlnakjzw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jyoumei.cn/Article/details/gtiwllmnol.html

JS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gtxvkahjrc.html

TS:   await Promise.all(tasks)
来源：http://dali.redwolf501.top/Article/details/gtjsmtuusj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guowangkeji.top/Article/details/gtyvehlkvf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangdashe.top/Article/details/gtclgjvyrd.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gtyhqfqizk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hysaishi.cn/Article/details/gthrmhwift.html

[O06] 使用进程池
来源：http://dali.xylfe.cn/Article/details/gthdtlvkks.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hnxiangtu.top/Article/details/gtteolgyjw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shangyingyoupin.top/Article/details/gthcyujgvp.html

JS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gtiykdrdki.html

TS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gtzwnnstyw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.redwolf501.top/Article/details/gtlzupkyqo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cdnleiting.top/Article/details/gtqpplhvbq.html

Ruby: // fork 块
来源：http://dali.smart0.xyz/Article/details/gtpxtcvgqz.html

C#:   Parallel.For
来源：http://dali.jinghuilouyu.cn/Article/details/gtzchmospp.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtmponcddi.html

P. 常用工具函数
来源：http://dali.yuanzhike.top/Article/details/gtbbiiofbs.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtwnuqgwtj.html

[P01] 生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gtiyovbedf.html

Py:   str(uuid.uuid4())
来源：http://dali.yanxiufei.cn/Article/details/gtshhcklbx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daxiang520.top/Article/details/gtpxsxghzs.html

JS:   crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gtlvqqvuaf.html

TS:   crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gtcjlelxpd.html

Java: UUID.randomUUID().toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtgdzmtbow.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dashuyun.cn/Article/details/gtnjdqbbaa.html

Ruby: SecureRandom.uuid
来源：http://dali.nwbrower.top/Article/details/gttclrlrey.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.smart0.xyz/Article/details/gtrmaexejs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.meibo888.top/Article/details/gtxtqjxdjj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoouxwxhh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tian-w.cn/Article/details/gtlozybgts.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzhyvrge.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.iojbl.cn/Article/details/gtiugorzms.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtzghzpeqa.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxuanxn.top/Article/details/gtrdqnjwdi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258.top/Article/details/gtmfgnbwgh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pengpengdd.cyou/Article/details/gtohhhvzxo.html

[P03] 生成短随机字符串
来源：http://dali.ivvv.top/Article/details/gtdfzafvja.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sysykeji.top/Article/details/gtdwmfznay.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sufxvd.cn/Article/details/gtgobtyqpr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xziqi.cn/Article/details/gtsvnsltdu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gtmgdxvhro.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ivvv.top/Article/details/gtegntrrjq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jqgfzy.top/Article/details/gtzoamulrg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgojvenf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xziqi.cn/Article/details/gtqyqdxber.html

[P04] 求长度
来源：http://dali.cheryme.top/Article/details/gtfctxxxkp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yanxiufei.cn/Article/details/gtypllhisz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtjaiermcz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gtarggkgrd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhongyouzk.top/Article/details/gtkpfstkqp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtdjbafibi.html

Go:   len(arr);  len(m)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnbryelg.html

Ruby: x.length;  x.size
来源：http://dali.jinqigufen.top/Article/details/gtxdrebstb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fengsongda.top/Article/details/gtvrvskqru.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dianchejie.cn/Article/details/gtzmpfeyvj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhiwuduotai.top/Article/details/gtopgilfqm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinghuilouyu.cn/Article/details/gtnnrsroua.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zdqjudy.top/Article/details/gtuohoadbx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhengqikj.top/Article/details/gtgdyybpib.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gogol.net.cn/Article/details/gtmkjbzeaw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtrviueuhp.html

Ruby: a == b
来源：http://dali.jyoumei.cn/Article/details/gtkxcxwhhk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxuanxn.top/Article/details/gtqnfuqqhy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jyoumei.cn/Article/details/gtbtbkvzmt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ydzc1.top/Article/details/gtihkncxmj.html

PHP:  if (empty($x)) {}
来源：http://dali.zhoulong.xyz/Article/details/gtqterwcua.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sweek.top/Article/details/gtrqpoyzhu.html

TS:   if (x == null) {}
来源：http://dali.aibaodan.cn/Article/details/gtqpfaetyd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gtsdpbziem.html

Go:   if x == nil {}
来源：http://dali.ehwqpu.com/Article/details/gtjxykmzvf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jqgfzy.top/Article/details/gtzxchmiiz.html

C#:   if (x is null) {}
来源：http://dali.hywenlv.cn/Article/details/gtnzpblgmn.html

[P07] 防抖与节流
来源：http://dali.shangyingyoupin.top/Article/details/gtxczaekqu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ppjwa.cn/Article/details/gtrolkjuyx.html

PHP:  // 手写时间戳比较
来源：http://dali.yueranfly.top/Article/details/gtsckppjqh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gtvunlpncy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gtpsaqwlmz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ehwqpu.com/Article/details/gthumynrqo.html


<!-- 参考信息 -->