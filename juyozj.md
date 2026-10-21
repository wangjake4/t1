代发 wailian999

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtksewdael.html

[M01] 读取命令行参数
来源：http://dali.ybcxt.top/Article/details/gtasninhkx.html

Py:   sys.argv[1:]
来源：http://dali.fengsongda.top/Article/details/gtgtkzkoyp.html

PHP:  $argv;  $argc;
来源：http://dali.chenjidiqi.icu/Article/details/gtaqaofxvo.html

JS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gtxhdzuiet.html

TS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gthculrgac.html

Java: args 数组（main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gtmuxytubq.html

Go:   os.Args[1:]
来源：http://dali.aizwys.cn/Article/details/gtxgwslpua.html

Ruby: ARGV
来源：http://dali.aizwys.cn/Article/details/gtuskbqzkm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gtubuoevbs.html

[M02] 读取环境变量
来源：http://dali.hnxiangtu.top/Article/details/gtccgtrxyn.html

Py:   os.environ.get("HOME")
来源：http://dali.yuxming.cn/Article/details/gtpzcjlezi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtfgjrcsau.html

JS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gtywkkjycl.html

TS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gtrjgyxzdt.html

Java: System.getenv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gttphqnxpu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj202588.top/Article/details/gtcbfafglf.html

Ruby: ENV["HOME"]
来源：http://dali.xziqi.cn/Article/details/gtnanxhcdc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hammf.cn/Article/details/gtqghvoazw.html

[M03] 执行外部命令
来源：http://dali.fengsongda.top/Article/details/gtknmvkvxs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gaohongyu789.top/Article/details/gtjctpyyif.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daxiang520.top/Article/details/gtoznojmcy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtunqaiwnr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gtweflnson.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ehwqpu.com/Article/details/gtreaxcrvm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ivvv.top/Article/details/gtyvwczioo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenlongwang.top/Article/details/gtqqxhounp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcbslhty.html

[M04] 获取当前工作目录
来源：http://dali.cheryme.top/Article/details/gtvljtnnqr.html

Py:   os.getcwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtjavnsjoq.html

PHP:  getcwd();
来源：http://dali.guannengcc.top/Article/details/gtyaxdyxch.html

JS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtquenqscj.html

TS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gtcjftfvzj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkwepsnh.html

Go:   os.Getwd()
来源：http://dali.nanxuanxn.top/Article/details/gtmciaxrwq.html

Ruby: Dir.pwd
来源：http://dali.cashguo.top/Article/details/gtxgnloqrp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.redwolf501.top/Article/details/gtnswlfayi.html

[M05] 设置退出码
来源：http://dali.xinyue.icu/Article/details/gtohdwpdvy.html

Py:   sys.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtowlbfheq.html

PHP:  exit(1);
来源：http://dali.pengpengdd.cyou/Article/details/gtlcxlkqxw.html

JS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtvnviribm.html

TS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtgvivvqbv.html

Java: System.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtgvgtkmir.html

Go:   os.Exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxduzuui.html

Ruby: exit 1
来源：http://dali.smart0.xyz/Article/details/gtqthyeatx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sufxvd.cn/Article/details/gtwzekgxrb.html

[M06] 向标准错误输出
来源：http://dali.vqdsnc.cn/Article/details/gtgtnlduxz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hysaishi.cn/Article/details/gtkbefkvzk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxinkj.top/Article/details/gtszklfuck.html

JS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gtzcrbqfpf.html

TS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gtzdwgdldt.html

Java: System.err.println("err")
来源：http://dali.sysykeji.top/Article/details/gtiltbqizy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tian-w.cn/Article/details/gtusiqeotl.html

Ruby: warn "err"
来源：http://dali.dashuyun.cn/Article/details/gtexbprodb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daria6918.cn/Article/details/gtszehrxht.html

[M07] 判断是否为主入口
来源：http://dali.yanxiufei.cn/Article/details/gtuajodutr.html

Py:   if __name__ == "__main__":
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjhprtip.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jlsjyb.cn/Article/details/gtsdmuwkrx.html

JS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gtwcogzpts.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gtewvxtgqr.html

Java: public static void main(String[] args)
来源：http://dali.yueranfly.top/Article/details/gtdeguoash.html

Go:   func main()
来源：http://dali.ehwqpu.com/Article/details/gtpsdjnbkm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.9152youxi.cn/Article/details/gtroqenjpy.html

C#:   static void Main(string[] args)
来源：http://dali.9152youxi.cn/Article/details/gtgcfpnjgl.html

[M08] 获取系统与运行时信息
来源：http://dali.sufxvd.cn/Article/details/gtjbjstwuu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guowangkeji.top/Article/details/gtfgwbngvs.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nwbrower.top/Article/details/gtrtqyqllb.html

JS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gtaiblwdrm.html

TS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gtfozwxulg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenlongwang.top/Article/details/gtvjfirnnu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gzhubu.top/Article/details/gtdyiyjuyc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gotoacloud.top/Article/details/gtlriqqjhl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yangfankeji.com/Article/details/gtjxgjoeoh.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtanihhzme.html

N. 数据结构与算法
来源：http://dali.aibaodan.cn/Article/details/gtbspxfpfr.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtbtpmuijt.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258.top/Article/details/gtctayqxhs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtchuzhnwc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.smart0.xyz/Article/details/gtexfflnop.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gtgnqwtxmj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtokmdxhnw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtujkncoez.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtejnalrob.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258888.top/Article/details/gtypuwelps.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gtvhogjgwf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jiagoushi.top/Article/details/gtjnpednyk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gtsivmxqim.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenlongwang.top/Article/details/gtduxvqlmk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gtxsbvddlc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gtmyjrzqmc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigufen.top/Article/details/gtydryeewx.html

Go:   slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gtutqdtckx.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gtnuvjqbpk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.smart0.xyz/Article/details/gtliyucscg.html

[N03] 快速排序（分治示例）
来源：http://dali.daria6918.cn/Article/details/gtjzkwvfef.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xylfe.cn/Article/details/gtukhojrao.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxuanxn.top/Article/details/gtsnpajsqg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gtgwxeanfr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gtmxcxxwlz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.svipenyu.cn/Article/details/gtgxyjnlss.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jiagoushi.top/Article/details/gtrryihowb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yanxiufei.cn/Article/details/gttpvjqusu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hnqzz.top/Article/details/gtmuakuwgs.html

[N04] 斐波那契数列
来源：http://dali.fzhhl.top/Article/details/gthobzpfjy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gteihzxvcq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.birdmap.top/Article/details/gtupyksnlq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtupqwvwvc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtglrdfqrg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gtvivlmzru.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jqgufenzy.top/Article/details/gtmctarlqq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nwbrower.top/Article/details/gtoqtkizbm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gtyhjzrzfv.html

[N05] 最大公约数
来源：http://dali.gogol.net.cn/Article/details/gtvnebeohx.html

Py:   math.gcd(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtcuytodxc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhengqikj.top/Article/details/gtirwrrngv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gtzucdhqww.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gtodjdmdie.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxuanxn.top/Article/details/gtgpvelgta.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jlsjyb.cn/Article/details/gtujxaqyri.html

Ruby: a.gcd(b)
来源：http://dali.ppjwa.cn/Article/details/gtpcumocfl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgfzy.top/Article/details/gtdnspzaup.html

[N06] 判断回文字符串
来源：http://dali.yvedp.cn/Article/details/gtxmqvejym.html

Py:   s == s[::-1]
来源：http://dali.shuidangran.top/Article/details/gtynvvodyq.html

PHP:  $s === strrev($s);
来源：http://dali.cashguo.top/Article/details/gtzhpxlwfr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxdxvswy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtspudsrce.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.fengsongda.top/Article/details/gtrylwalnw.html

Go:   // 双指针从两端比较
来源：http://dali.jyoumei.cn/Article/details/gtsqgwdoei.html

Ruby: s == s.reverse
来源：http://dali.kuanghao11.cn/Article/details/gttymvfqqd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gtugjfnrlz.html

[N07] 两数之和（返回下标）
来源：http://dali.svipenyu.cn/Article/details/gtcvpttdkj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.quarkkingdee.top/Article/details/gtiefwzdpw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.316326.xyz/Article/details/gttxffoytj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.smart0.xyz/Article/details/gtrmttgmbf.html

TS:   // 手写 Map<string, number>
来源：http://dali.ybcxt.top/Article/details/gtzjojnppr.html

Java: // 手写 HashMap
来源：http://dali.yangfankeji.com/Article/details/gtxgoarrko.html

Go:   // 手写 map[int]int
来源：http://dali.svipenyu.cn/Article/details/gtkjszcjko.html

Ruby: // 手写 Hash
来源：http://dali.cheryme.top/Article/details/gtzhsmupzi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdfxqcdp.html

[N08] 生成全排列
来源：http://dali.ybcxt.top/Article/details/gtptfbikuk.html

Py:   itertools.permutations(arr)
来源：http://dali.xuanzx.com/Article/details/gtnjncjnkq.html

PHP:  // 手写递归交换
来源：http://dali.yj20258.top/Article/details/gtcepakasq.html

JS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtzmywakwg.html

TS:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtczefzykj.html

Java: // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtzwwtimnq.html

Go:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gthkkgaknt.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258888.top/Article/details/gtxxoculcm.html

C#:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvetpzbc.html

[N09] 栈与队列
来源：http://dali.dashuyun.cn/Article/details/gtgbyxizgd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhixingplan.top/Article/details/gtqeeabpbf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtwfltimrl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gtowyluank.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.quarkkingdee.top/Article/details/gtvmvolqmm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenzaomai.com/Article/details/gtijjxosgg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shzxlz.cn/Article/details/gtcvucehjp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gthlscpaue.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gzhubu.top/Article/details/gtwlhrfzfw.html

[N10] 链表节点定义
来源：http://dali.yj202588.top/Article/details/gttwgaeryl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shzxlz.cn/Article/details/gtixqocncb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tianlin.xyz/Article/details/gtcqhzzkef.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.redwolf501.top/Article/details/gtmyeuesju.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cqqwz.cn/Article/details/gtjgphaeic.html

Java: class Node { int v; Node next; }
来源：http://dali.aibaodan.cn/Article/details/gtkewrrlzc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhiwuduotai.top/Article/details/gtjbxacnrz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuskylaze.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.svipenyu.cn/Article/details/gtzgkfxabz.html

[N11] 二叉树中序遍历
来源：http://dali.jlsjyb.cn/Article/details/gtnptwxamk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pengpengdd.cyou/Article/details/gtkbbvxvtl.html

PHP:  // 手写递归函数
来源：http://dali.jinghuilouyu.cn/Article/details/gthrvhrxjt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sweek.top/Article/details/gtrioatbxc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gtstvrtfbo.html

Java: // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gtdlhexate.html

Go:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtcbzqulno.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.birdmap.top/Article/details/gtnuhyzrmx.html

C#:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtsrfbclnw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xylfe.cn/Article/details/gtomqrgdua.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xuetiantiany.cn/Article/details/gtndsbhivn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.kuanghao11.cn/Article/details/gtsiudlhcw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenzaomai.com/Article/details/gteghhvgly.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gtbodkrlsc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jlsjyb.cn/Article/details/gtundsrypq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhengqikj.top/Article/details/gthuuvnnzs.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.wangdashe.top/Article/details/gtdtmfdltd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gtfwvxkrfo.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtuildgozo.html

O. 并发与异步
来源：http://dali.nwbrower.top/Article/details/gtkvwpsaun.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtsthsxiyw.html

[O01] 启动一个线程
来源：http://dali.ybcxt.top/Article/details/gtpcrygpms.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yvedp.cn/Article/details/gtpmccumcc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.fzhhl.top/Article/details/gtmenclegs.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnxiangtu.top/Article/details/gtvbsuvodj.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gtfbcgbvpg.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhoulong.xyz/Article/details/gttiqqzpnz.html

Go:   go f()
来源：http://dali.aizwys.cn/Article/details/gtuvnkfagr.html

Ruby: Thread.new { f }
来源：http://dali.jqgufenzy.top/Article/details/gtmopflciz.html

C#:   Task.Run(() => F());
来源：http://dali.316326.xyz/Article/details/gtnpgcnrgo.html

[O02] 使用线程池
来源：http://dali.aibaodan.cn/Article/details/gtcgkvcpzp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.mhx1999.top/Article/details/gtlizgsueh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cucudq.cn/Article/details/gtmjztrtsj.html

JS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gtmddsdpxw.html

TS:   // worker_threads 线程池
来源：http://dali.zdqjudy.top/Article/details/gtklperdid.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.9152youxi.cn/Article/details/gteypwfgql.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258.top/Article/details/gthbtiiotd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ehwqpu.com/Article/details/gtoquvxwcs.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.dashuyun.cn/Article/details/gtpqchjrub.html

[O03] 加锁保护共享数据
来源：http://dali.wangshuangyany.cn/Article/details/gtvtvfxdzm.html

Py:   with lock: shared += 1
来源：http://dali.shzxlz.cn/Article/details/gtbiavvlqb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hywenlv.cn/Article/details/gtxpsonuyw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.0kj1m.cn/Article/details/gthkxwayxu.html

TS:   // 同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gthnklkcqt.html

Java: synchronized (this) { shared++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjudwhxpm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cucudq.cn/Article/details/gtvkymbgqc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yongpay.top/Article/details/gtpvonjbjn.html

C#:   lock (gate) { shared++; }
来源：http://dali.yongpay.top/Article/details/gtlzesuhms.html

[O04] 定义异步函数并等待
来源：http://dali.aibaodan.cn/Article/details/gtsfowddkg.html

Py:   async def f():⏎    await g()
来源：http://dali.yuanzhike.top/Article/details/gtovnhszlo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jyoumei.cn/Article/details/gtithdahlw.html

JS:   async function f() { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gtnzgeirma.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.fzhhl.top/Article/details/gtotoiuywb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuxming.cn/Article/details/gtocfoxkoa.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.0kj1m.cn/Article/details/gthlfvxawr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nanxuanxn.top/Article/details/gtndskxkqz.html

C#:   async Task F() { await G(); }
来源：http://dali.redwolf501.top/Article/details/gtcylvklka.html

[O05] 并发执行并等待全部完成
来源：http://dali.andypj.xyz/Article/details/gteznqrrgv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gthwpyihgd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yueranfly.top/Article/details/gtatjtiztk.html

JS:   await Promise.all(tasks)
来源：http://dali.9152youxi.cn/Article/details/gtmhvfeooi.html

TS:   await Promise.all(tasks)
来源：http://dali.vqdsnc.cn/Article/details/gtigrvnxdg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yvedp.cn/Article/details/gtpgffmpet.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yongpay.top/Article/details/gteveueeuv.html

Ruby: threads.map(&:join)
来源：http://dali.yuanzhike.top/Article/details/gtqplbvewg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nwbrower.top/Article/details/gtrxpknguo.html

[O06] 使用进程池
来源：http://dali.yangfankeji.com/Article/details/gtwltqbffz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhengqikj.top/Article/details/gtibflcafj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnqzz.top/Article/details/gtturqnlmc.html

JS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gtaltwrdmx.html

TS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gtyxlcuxtd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gtxicmuyjb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gzhubu.top/Article/details/gtgnfxqcbq.html

Ruby: // fork 块
来源：http://dali.yvedp.cn/Article/details/gtlpjmmvhv.html

C#:   Parallel.For
来源：http://dali.yj20258.top/Article/details/gtgeqxlgbq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtesnfjqmm.html

P. 常用工具函数
来源：http://dali.zhongyouzk.top/Article/details/gtleccsggr.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdkgrcgi.html

[P01] 生成 UUID
来源：http://dali.sysykeji.top/Article/details/gtaaefnwpe.html

Py:   str(uuid.uuid4())
来源：http://dali.ybcxt.top/Article/details/gtsflazqtn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gotoacloud.top/Article/details/gtbpdxuodu.html

JS:   crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gtavgtolny.html

TS:   crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gtfhpccdlv.html

Java: UUID.randomUUID().toString()
来源：http://dali.chenlongwang.top/Article/details/gtxdjtjshb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgfzy.top/Article/details/gtmeyuwvkd.html

Ruby: SecureRandom.uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhubywsj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.quarkkingdee.top/Article/details/gtpdiersid.html

[P02] MD5 / SHA256 摘要
来源：http://dali.meibo888.top/Article/details/gtoirfqdhd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sufxvd.cn/Article/details/gtqxfrgdnl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.birdmap.top/Article/details/gtgwcjstag.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hammf.cn/Article/details/gtisqqncwl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tanke756.top/Article/details/gtkogpssfv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daxiang520.top/Article/details/gtaxhajwca.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj20258.top/Article/details/gtmlhvsfzi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxuanxn.top/Article/details/gtmaxpcjsk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258.top/Article/details/gtqjlukmyi.html

[P03] 生成短随机字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqloqrkp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangdashe.top/Article/details/gtxsehbkwm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hywenlv.cn/Article/details/gtanaqdeho.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnxiangtu.top/Article/details/gttlafsppj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gtjjnlxhsf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gaohongyu789.top/Article/details/gtfvbjzywo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.bjfxy.top/Article/details/gtahuqtpez.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gthxxwxqzy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yueranfly.top/Article/details/gtargfelvq.html

[P04] 求长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaoicnxzj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhengqikj.top/Article/details/gtpcqabwzw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtbkeiokkv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.9152youxi.cn/Article/details/gtuzfoslqu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gtseyfexbf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.andypj.xyz/Article/details/gtbhezqasp.html

Go:   len(arr);  len(m)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxetgjwr.html

Ruby: x.length;  x.size
来源：http://dali.hysaishi.cn/Article/details/gtqmebkyek.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.smart0.xyz/Article/details/gtnogclpzw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hammf.cn/Article/details/gtkpzamgjm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gzhubu.top/Article/details/gtnezsrgxg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yongpay.top/Article/details/gtyfededba.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fzhhl.top/Article/details/gtnfmmrqoh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtzuvkzixt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhixingplan.top/Article/details/gtummwiydg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtbjefardh.html

Ruby: a == b
来源：http://dali.bjfxy.top/Article/details/gtzavtlbvg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhongyouzk.top/Article/details/gtfzrnorpi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sweek.top/Article/details/gtjyvuucfw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hongshengwenyu.top/Article/details/gtrpmpjwzv.html

PHP:  if (empty($x)) {}
来源：http://dali.redwolf501.top/Article/details/gtqvegmdmb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenjidiqi.icu/Article/details/gtwqkfxxrg.html

TS:   if (x == null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbwqwpkh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijriweto.html

Go:   if x == nil {}
来源：http://dali.sweek.top/Article/details/gtdtmykisd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jianghu66.top/Article/details/gtidrrpdls.html

C#:   if (x is null) {}
来源：http://dali.yuanzhike.top/Article/details/gtpxwweuvf.html

[P07] 防抖与节流
来源：http://dali.yanxiufei.cn/Article/details/gthrfjgiwp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.pengpengdd.cyou/Article/details/gtcforpttu.html


<!-- 参考信息 -->