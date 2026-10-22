代发 wailian999

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtpnrftkce.html

[M01] 读取命令行参数
来源：http://dali.daria6918.cn/Article/details/gttpvmimpa.html

Py:   sys.argv[1:]
来源：http://dali.aizwys.cn/Article/details/gttgdivklb.html

PHP:  $argv;  $argc;
来源：http://dali.svipenyu.cn/Article/details/gtnwzyywbt.html

JS:   process.argv.slice(2)
来源：http://dali.shzxlz.cn/Article/details/gtgultnrjt.html

TS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gtvstiwafd.html

Java: args 数组（main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtnftapxei.html

Go:   os.Args[1:]
来源：http://dali.cheryme.top/Article/details/gthucxrman.html

Ruby: ARGV
来源：http://dali.zycfv.cn/Article/details/gtgvnozcde.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gtfhyfzjkx.html

[M02] 读取环境变量
来源：http://dali.wangdashe.top/Article/details/gthqbudhih.html

Py:   os.environ.get("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtyduhsavt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gthvoldfvn.html

JS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gtfwncfvne.html

TS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gtndvgqszu.html

Java: System.getenv("HOME")
来源：http://dali.zycfv.cn/Article/details/gtsaiwtwkq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtvowlgujn.html

Ruby: ENV["HOME"]
来源：http://dali.nanxuanxn.top/Article/details/gtugpdwkmq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtkvjzniem.html

[M03] 执行外部命令
来源：http://dali.yj20258.top/Article/details/gtjqytaoyc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxqmzbal.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.9152youxi.cn/Article/details/gtaprdwmqq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gtclafgcex.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gtossblufu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.birdmap.top/Article/details/gtndnxfxzw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ybcxt.top/Article/details/gtgkvfigni.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xinyue.icu/Article/details/gtvbghuigd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sweek.top/Article/details/gtxxnfuqax.html

[M04] 获取当前工作目录
来源：http://dali.yj20258888.top/Article/details/gtkmboiyiv.html

Py:   os.getcwd()
来源：http://dali.0kj1m.cn/Article/details/gtnjhkmvjk.html

PHP:  getcwd();
来源：http://dali.daxiang520.top/Article/details/gtgacrurzl.html

JS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gtifaqqnok.html

TS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnatkmuxv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpepjxmil.html

Go:   os.Getwd()
来源：http://dali.ybcxt.top/Article/details/gttqtjlmwx.html

Ruby: Dir.pwd
来源：http://dali.gogol.net.cn/Article/details/gtuuddznol.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gtkkgmpmnz.html

[M05] 设置退出码
来源：http://dali.jqgufenzy.top/Article/details/gtkekszroo.html

Py:   sys.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtpdiejflm.html

PHP:  exit(1);
来源：http://dali.nanxuanxn.top/Article/details/gtobiulyts.html

JS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gttbgvveaf.html

TS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gteqgxmzat.html

Java: System.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnmgcojz.html

Go:   os.Exit(1)
来源：http://dali.cashguo.top/Article/details/gtkpmgsgld.html

Ruby: exit 1
来源：http://dali.nwbrower.top/Article/details/gtsehfogzi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenlongwang.top/Article/details/gtxtmaqwer.html

[M06] 向标准错误输出
来源：http://dali.smart0.xyz/Article/details/gtouovzutl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xinyue.icu/Article/details/gtmxjqbnge.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxuanxn.top/Article/details/gtcsiivrks.html

JS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtiswoyvmg.html

TS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gtetifruir.html

Java: System.err.println("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtnffbfgbt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yvedp.cn/Article/details/gtewniylyi.html

Ruby: warn "err"
来源：http://dali.shuidangran.top/Article/details/gtzvlybthb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gaohongyu789.top/Article/details/gtnxagdofa.html

[M07] 判断是否为主入口
来源：http://dali.jinqigufen.top/Article/details/gttshgmilu.html

Py:   if __name__ == "__main__":
来源：http://dali.birdmap.top/Article/details/gtmfawyoqv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenjidiqi.icu/Article/details/gthnfawlwd.html

JS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gtdaidpnor.html

TS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gtutsjvyqk.html

Java: public static void main(String[] args)
来源：http://dali.jinqigfzy.top/Article/details/gtuajqvfmm.html

Go:   func main()
来源：http://dali.wangdashe.top/Article/details/gtcdehufck.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj202588.top/Article/details/gtruqapvuz.html

C#:   static void Main(string[] args)
来源：http://dali.yj202588.top/Article/details/gtvcpajyug.html

[M08] 获取系统与运行时信息
来源：http://dali.sufxvd.cn/Article/details/gtixhnnqlz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenzaomai.com/Article/details/gtvhnllzdw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gotoacloud.top/Article/details/gtnwlyrkxq.html

JS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gtksbgoilf.html

TS:   process.platform;  process.version
来源：http://dali.yvedp.cn/Article/details/gtxisyenyc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gtmjpcjyin.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnxiangtu.top/Article/details/gtbljnpldj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hongshengwenyu.top/Article/details/gtghygnbfc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenzaomai.com/Article/details/gtyonuherw.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtuckiyvef.html

N. 数据结构与算法
来源：http://dali.c1oappe.top/Article/details/gtjtnzrwnm.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtloircgvp.html

[N01] 二分查找（有序数组）
来源：http://dali.vqdsnc.cn/Article/details/gtfejzyzyg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtqvogavts.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jiagoushi.top/Article/details/gtcqkdsfrv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcefbfxbd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gtphanpurx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtcrpduvcl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkelegbb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.pengpengdd.cyou/Article/details/gtsylkpdbi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtldzvdrzh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnqzz.top/Article/details/gtjcjivplv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tianlin.xyz/Article/details/gtujoucfja.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ivvv.top/Article/details/gtytpgnzuw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gtqavxwkub.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfvwcxuu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tianlin.xyz/Article/details/gtxexskbzs.html

Go:   slices.Sort(arr)
来源：http://dali.snrcjt.cn/Article/details/gtzxmvdhel.html

Ruby: arr.sort
来源：http://dali.dianchejie.cn/Article/details/gtfhgvtnni.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.0kj1m.cn/Article/details/gthimifcfd.html

[N03] 快速排序（分治示例）
来源：http://dali.vqdsnc.cn/Article/details/gtkwdwddoi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yueranfly.top/Article/details/gtexfwozpr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbffbnjux.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gtzsnrzacb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gteresblso.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhixingplan.top/Article/details/gtrzwvfcvl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fzhhl.top/Article/details/gttechqguq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cashguo.top/Article/details/gtpgvdfoma.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shzxlz.cn/Article/details/gtjjwekwte.html

[N04] 斐波那契数列
来源：http://dali.birdmap.top/Article/details/gtxwmnadpk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gtgsgmfjks.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gtmigpzrty.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gtogxfyffp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gtdrgvveyo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gtnksyndtp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ivvv.top/Article/details/gtbohfxqin.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gtrsrcmwsr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtgdwwvjud.html

[N05] 最大公约数
来源：http://dali.shangyingyoupin.top/Article/details/gtoemnsbfq.html

Py:   math.gcd(a, b)
来源：http://dali.bjfxy.top/Article/details/gtythdufly.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.0kj1m.cn/Article/details/gtorbmwmcq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gtkzzpxctb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gtvzlelbog.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yangfankeji.com/Article/details/gtgmwzagym.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yanxiufei.cn/Article/details/gttbqybbcn.html

Ruby: a.gcd(b)
来源：http://dali.9152youxi.cn/Article/details/gttykbeeou.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yueranfly.top/Article/details/gtnshchdxq.html

[N06] 判断回文字符串
来源：http://dali.wangdashe.top/Article/details/gtefzativi.html

Py:   s == s[::-1]
来源：http://dali.andypj.xyz/Article/details/gtejrzhjer.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gtvdervkno.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtuinyqvfn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtghfvyjqy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gotoacloud.top/Article/details/gtvhxlepab.html

Go:   // 双指针从两端比较
来源：http://dali.zhixingplan.top/Article/details/gtxwjmcorw.html

Ruby: s == s.reverse
来源：http://dali.smart0.xyz/Article/details/gticrgsqmc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gtcpufiijx.html

[N07] 两数之和（返回下标）
来源：http://dali.9152youxi.cn/Article/details/gtcdfmijbw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shangyingyoupin.top/Article/details/gtemyzicts.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.316326.xyz/Article/details/gtwcmeuxdt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhoulong.xyz/Article/details/gtnidfpaoq.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenzaomai.com/Article/details/gttuazyyhb.html

Java: // 手写 HashMap
来源：http://dali.xylfe.cn/Article/details/gttgmycpys.html

Go:   // 手写 map[int]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gteyjktzbo.html

Ruby: // 手写 Hash
来源：http://dali.hfpthk.cn/Article/details/gtwcximkxw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhongyouzk.top/Article/details/gtwrsxgpwl.html

[N08] 生成全排列
来源：http://dali.wangshuangyany.cn/Article/details/gtoclhoxyl.html

Py:   itertools.permutations(arr)
来源：http://dali.fzhhl.top/Article/details/gtkelvptdf.html

PHP:  // 手写递归交换
来源：http://dali.jianghu66.top/Article/details/gttnqkernx.html

JS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtduftsaqc.html

TS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtnwssgyhw.html

Java: // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtzqpdswrp.html

Go:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfwujoye.html

Ruby: arr.permutation.to_a
来源：http://dali.aizwys.cn/Article/details/gtocatiosb.html

C#:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtbvrzzkdv.html

[N09] 栈与队列
来源：http://dali.tanke756.top/Article/details/gtgscaijko.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtatijfqiw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tian-w.cn/Article/details/gthusjozqh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtondkqnsp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuanzx.com/Article/details/gtmxgdccsq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tian-w.cn/Article/details/gtpviaiygo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.vqdsnc.cn/Article/details/gtiikmejvi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtjjmldnfq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hfpthk.cn/Article/details/gtymoqqrcv.html

[N10] 链表节点定义
来源：http://dali.xinyue.icu/Article/details/gtmkmibxfp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jyoumei.cn/Article/details/gtsayfymoa.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhiwuduotai.top/Article/details/gthajbjono.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daria6918.cn/Article/details/gtahgltiuf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cqqwz.cn/Article/details/gtljyokqxo.html

Java: class Node { int v; Node next; }
来源：http://dali.nanxuanxn.top/Article/details/gtwafzxrhq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.iojbl.cn/Article/details/gtinwoosjg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.9152youxi.cn/Article/details/gtzckjxvdd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ydzc1.top/Article/details/gtwchnlygo.html

[N11] 二叉树中序遍历
来源：http://dali.cheryme.top/Article/details/gtkahaxgvc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cdnleiting.top/Article/details/gtfkbxhphj.html

PHP:  // 手写递归函数
来源：http://dali.xinyue.icu/Article/details/gtrmubjedv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xylfe.cn/Article/details/gtyqfdnbsi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangshuangyany.cn/Article/details/gtkjoqdvpc.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gtjbzvijtk.html

Go:   // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gtfltriatj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sxryk.cn/Article/details/gtfykgtwpy.html

C#:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtsspqgrpk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sysykeji.top/Article/details/gtpkcemnwc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jiagoushi.top/Article/details/gtpwoempla.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigufen.top/Article/details/gtsyfoeiiq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gtotmwuvht.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gtifalbxht.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gtzqlyaifj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gtuaefotyg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sxryk.cn/Article/details/gtgfkxocza.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gtupbxvshf.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtcunxxnsg.html

O. 并发与异步
来源：http://dali.birdmap.top/Article/details/gttfyyvlsf.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtxzscxzag.html

[O01] 启动一个线程
来源：http://dali.yj20258.top/Article/details/gtbfdbdicd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aizwys.cn/Article/details/gtrmdysria.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.havefunace.top/Article/details/gttmruawik.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gzhubu.top/Article/details/gtyiokdelz.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gteffyjopb.html

Java: new Thread(() -> f()).start()
来源：http://dali.ivvv.top/Article/details/gthcisgfbc.html

Go:   go f()
来源：http://dali.cashguo.top/Article/details/gtprgkzbdb.html

Ruby: Thread.new { f }
来源：http://dali.jinqigufen.top/Article/details/gtebocmcdn.html

C#:   Task.Run(() => F());
来源：http://dali.jlsjyb.cn/Article/details/gtnxmtbrwa.html

[O02] 使用线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtksnasqvb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhgevpjh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.kuanghao11.cn/Article/details/gtddtbfecd.html

JS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gtbqbuices.html

TS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gtvhjywanl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cucudq.cn/Article/details/gtgyhqmjhh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.andypj.xyz/Article/details/gtcydqkhmo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hywenlv.cn/Article/details/gtfbjqvptr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenjidiqi.icu/Article/details/gtikibodia.html

[O03] 加锁保护共享数据
来源：http://dali.hfpthk.cn/Article/details/gturgkmqun.html

Py:   with lock: shared += 1
来源：http://dali.jianghu66.top/Article/details/gtdnvhmbbq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cdnleiting.top/Article/details/gtcnuywppx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.bjfxy.top/Article/details/gtqtfrapij.html

TS:   // 同 JS
来源：http://dali.aibaodan.cn/Article/details/gtcrtkygyt.html

Java: synchronized (this) { shared++; }
来源：http://dali.ehwqpu.com/Article/details/gtylogcsgv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.haohaochexian.top/Article/details/gtioilwrsz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jyoumei.cn/Article/details/gtecdcmwwj.html

C#:   lock (gate) { shared++; }
来源：http://dali.ehwqpu.com/Article/details/gtnslnzuib.html

[O04] 定义异步函数并等待
来源：http://dali.fengsongda.top/Article/details/gtoiwbiasu.html

Py:   async def f():⏎    await g()
来源：http://dali.xinyue.icu/Article/details/gtfhbexufb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shuidangran.top/Article/details/gtyhjtwfis.html

JS:   async function f() { await g(); }
来源：http://dali.yongpay.top/Article/details/gtekdiomzx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gzhubu.top/Article/details/gtazhzcllc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhongyouzk.top/Article/details/gteuzlcoix.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuanzhike.top/Article/details/gtywlortyr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenzaomai.com/Article/details/gtxsbmdhhm.html

C#:   async Task F() { await G(); }
来源：http://dali.dianchejie.cn/Article/details/gtybbjiitu.html

[O05] 并发执行并等待全部完成
来源：http://dali.xinyue.icu/Article/details/gtdmmdquqt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jyoumei.cn/Article/details/gtdcdkqcak.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.smart0.xyz/Article/details/gtobigiume.html

JS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gtpurcacgh.html

TS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gtbypkbiyg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigufen.top/Article/details/gtztfojoai.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gotoacloud.top/Article/details/gtcoyjshdo.html

Ruby: threads.map(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtlopsfagl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tian-w.cn/Article/details/gtsgpbdwkx.html

[O06] 使用进程池
来源：http://dali.nanxuanxn.top/Article/details/gtxfvajplt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhoulong.xyz/Article/details/gtldrsgwwf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gotoacloud.top/Article/details/gtnqgdakpx.html

JS:   // child_process / cluster 模块
来源：http://dali.guowangkeji.top/Article/details/gtefjgohuh.html

TS:   // child_process / cluster 模块
来源：http://dali.cdnleiting.top/Article/details/gtgdockqtp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinqigfzy.top/Article/details/gtdozvhvkw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yanxiufei.cn/Article/details/gtosagxvrx.html

Ruby: // fork 块
来源：http://dali.jianghu66.top/Article/details/gtvacnncfu.html

C#:   Parallel.For
来源：http://dali.jlsjyb.cn/Article/details/gtxwjlripz.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtqpqqraev.html

P. 常用工具函数
来源：http://dali.hnxiangtu.top/Article/details/gtqedtvqfs.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtjdmdlazu.html

[P01] 生成 UUID
来源：http://dali.yanxiufei.cn/Article/details/gtvynwommh.html

Py:   str(uuid.uuid4())
来源：http://dali.andypj.xyz/Article/details/gtvwtldpmc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gtubbbflyj.html

JS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gtzlxadmab.html

TS:   crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gtmejrbkvd.html

Java: UUID.randomUUID().toString()
来源：http://dali.pycfn.com/Article/details/gtshdtrvhx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dashuyun.cn/Article/details/gtkupcwudm.html

Ruby: SecureRandom.uuid
来源：http://dali.gzhubu.top/Article/details/gtdxaakdnd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuetiantiany.cn/Article/details/gtglcunelw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hongshengwenyu.top/Article/details/gtrstfhumx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gotoacloud.top/Article/details/gtcwipoube.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xziqi.cn/Article/details/gtdflnprqd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.quarkkingdee.top/Article/details/gtpbdvmsub.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cheryme.top/Article/details/gtouylornx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sysykeji.top/Article/details/gtqfmzaamc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sxryk.cn/Article/details/gtqyqcvwrd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ehwqpu.com/Article/details/gtuykqgazw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhongyouzk.top/Article/details/gtzojkwoqc.html

[P03] 生成短随机字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtbqcrkljm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.316326.xyz/Article/details/gtcxzmqvvd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzngqlvh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gtybojqtti.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gtfczklymg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dashuyun.cn/Article/details/gtjnnhosqq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.fzhhl.top/Article/details/gthdgpbadx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhiwuduotai.top/Article/details/gtjqoktdck.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigfzy.top/Article/details/gtwtcavppm.html

[P04] 求长度
来源：http://dali.yj20258888.top/Article/details/gtrjdwznzz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj202588.top/Article/details/gtkxgxgknz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gtkipiyxrd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gtlzogdnhk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xziqi.cn/Article/details/gtpuncbmhi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhengqikj.top/Article/details/gtsslidekl.html

Go:   len(arr);  len(m)
来源：http://dali.dianchejie.cn/Article/details/gtrbkauxin.html

Ruby: x.length;  x.size
来源：http://dali.hongshengwenyu.top/Article/details/gtswwptcgy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.0kj1m.cn/Article/details/gtchvriwcc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhengqikj.top/Article/details/gtxjqqwefq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cucudq.cn/Article/details/gtrjimtvjz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswijsnzb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.meibo888.top/Article/details/gtizbovzzz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.andypj.xyz/Article/details/gtoffgrhyg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgufenzy.top/Article/details/gtguzffsba.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gotoacloud.top/Article/details/gterorjnri.html

Ruby: a == b
来源：http://dali.hongshengwenyu.top/Article/details/gtchrsebyw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.quarkkingdee.top/Article/details/gtuornljfb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cheryme.top/Article/details/gtzbnkzlis.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yanxiufei.cn/Article/details/gtjxmltacv.html

PHP:  if (empty($x)) {}
来源：http://dali.sysykeji.top/Article/details/gtqdttzqzl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.c1oappe.top/Article/details/gtwzvuevzj.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthsxmdpmr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gtkzqfrxop.html

Go:   if x == nil {}
来源：http://dali.mhx1999.top/Article/details/gtpzuunzvj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuanzhike.top/Article/details/gttuarfjlp.html

C#:   if (x is null) {}
来源：http://dali.yonumen.top/Article/details/gtzwhovnof.html

[P07] 防抖与节流
来源：http://dali.c1oappe.top/Article/details/gtksjmfwdl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sufxvd.cn/Article/details/gtkrkphzqb.html


<!-- 参考信息 -->