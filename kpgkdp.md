代发 wailian999

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdmvvwhx.html

[M01] 读取命令行参数
来源：http://dali.xziqi.cn/Article/details/gtjmfmzyuf.html

Py:   sys.argv[1:]
来源：http://dali.cheryme.top/Article/details/gtioxypyqz.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gtbphhnmbg.html

JS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gtdmpenduy.html

TS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtoreetxnv.html

Java: args 数组（main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtfjfhjddp.html

Go:   os.Args[1:]
来源：http://dali.gotoacloud.top/Article/details/gtcpdpefmb.html

Ruby: ARGV
来源：http://dali.ydzc1.top/Article/details/gtpgrucaao.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gtgbyqvsod.html

[M02] 读取环境变量
来源：http://dali.mhx1999.top/Article/details/gtnmyabwdh.html

Py:   os.environ.get("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtxaohvtqk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pycfn.com/Article/details/gtilbsrlic.html

JS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gtiqqpeaki.html

TS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gtvcugrhsm.html

Java: System.getenv("HOME")
来源：http://dali.tanke756.top/Article/details/gtywgrbmfd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cucudq.cn/Article/details/gtfhoykfqz.html

Ruby: ENV["HOME"]
来源：http://dali.quarkkingdee.top/Article/details/gtrvvmizdu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ppjwa.cn/Article/details/gttagbgqhl.html

[M03] 执行外部命令
来源：http://dali.fzhhl.top/Article/details/gtgcrlimgj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ppjwa.cn/Article/details/gtpvnnjurv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yueranfly.top/Article/details/gtvkduhsfp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtobngapwk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gtqwsqqoxs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yongpay.top/Article/details/gtljavitak.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sweek.top/Article/details/gtillxnujk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hywenlv.cn/Article/details/gtagagugfh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxinkj.top/Article/details/gtycfypqye.html

[M04] 获取当前工作目录
来源：http://dali.gaohongyu789.top/Article/details/gtegaannuf.html

Py:   os.getcwd()
来源：http://dali.daria6918.cn/Article/details/gtocwmtffa.html

PHP:  getcwd();
来源：http://dali.xylfe.cn/Article/details/gtwfffmlpu.html

JS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gtxkqbkdtx.html

TS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gtgjljrmbr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shzxlz.cn/Article/details/gtdzhtyrce.html

Go:   os.Getwd()
来源：http://dali.ybcxt.top/Article/details/gtacpsrukt.html

Ruby: Dir.pwd
来源：http://dali.tian-w.cn/Article/details/gtrdsmbyzi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sysykeji.top/Article/details/gtvrzxrrdw.html

[M05] 设置退出码
来源：http://dali.gogol.net.cn/Article/details/gtkoxadoas.html

Py:   sys.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtvygdvrcq.html

PHP:  exit(1);
来源：http://dali.haohaochexian.top/Article/details/gtuuywocji.html

JS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtkvogmreo.html

TS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtppafrgti.html

Java: System.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtnxfikfmq.html

Go:   os.Exit(1)
来源：http://dali.sweek.top/Article/details/gtumdxmiqe.html

Ruby: exit 1
来源：http://dali.havefunace.top/Article/details/gtnnetziwb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gotoacloud.top/Article/details/gtmpvpirof.html

[M06] 向标准错误输出
来源：http://dali.smart0.xyz/Article/details/gtmzzbvjoe.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gtomjxcysb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhongyouzk.top/Article/details/gtowdxowxe.html

JS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gtgmmkhpet.html

TS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gtdlcfzvoo.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gtbytdzjbe.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhengqikj.top/Article/details/gtxfznzktj.html

Ruby: warn "err"
来源：http://dali.snrcjt.cn/Article/details/gtsberkgka.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhixingplan.top/Article/details/gtwmsqdnoq.html

[M07] 判断是否为主入口
来源：http://dali.haohaochexian.top/Article/details/gtacozluva.html

Py:   if __name__ == "__main__":
来源：http://dali.fzhhl.top/Article/details/gtpiadfyjh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.c1oappe.top/Article/details/gtmydtyhux.html

JS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gtfacrgmmv.html

TS:   require.main === module
来源：http://dali.sweek.top/Article/details/gtmavczfej.html

Java: public static void main(String[] args)
来源：http://dali.cucudq.cn/Article/details/gtpncwpasw.html

Go:   func main()
来源：http://dali.svipenyu.cn/Article/details/gtkgwerqrt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cdnleiting.top/Article/details/gtxrasnrsu.html

C#:   static void Main(string[] args)
来源：http://dali.jqgufenzy.top/Article/details/gtvcmenbzy.html

[M08] 获取系统与运行时信息
来源：http://dali.iojbl.cn/Article/details/gttvkxxymq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fzhhl.top/Article/details/gtrejazuqh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.meibo888.top/Article/details/gtrsttpsdv.html

JS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gtkjyqstes.html

TS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gtczuqyffa.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xylfe.cn/Article/details/gtljqnexfc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.smart0.xyz/Article/details/gthowiccjq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sufxvd.cn/Article/details/gtarlrwgpj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.smart0.xyz/Article/details/gtggwugqyj.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtpdsfwtxd.html

N. 数据结构与算法
来源：http://dali.chenjidiqi.icu/Article/details/gtnewcldsa.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtnrsltiaa.html

[N01] 二分查找（有序数组）
来源：http://dali.jianghu66.top/Article/details/gtbljwbanz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtwhzllsyl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj202588.top/Article/details/gtshcebjdz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gtazeqvhcr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gtlvebness.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtccjluejl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtpcqvynoj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.havefunace.top/Article/details/gtglgqtdrf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtybitxahk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258.top/Article/details/gtyabcmrna.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.9152youxi.cn/Article/details/gtsoxxywkt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nwbrower.top/Article/details/gtgtvlssov.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gtdfbbbluf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gtpjnqbimu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigufen.top/Article/details/gtogaipkht.html

Go:   slices.Sort(arr)
来源：http://dali.ppjwa.cn/Article/details/gtxdvsvmqp.html

Ruby: arr.sort
来源：http://dali.xuanzx.com/Article/details/gtjfqxuank.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxuanxn.top/Article/details/gtxcorjzdz.html

[N03] 快速排序（分治示例）
来源：http://dali.hammf.cn/Article/details/gtduexmyfz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.mhx1999.top/Article/details/gtmvomuhzr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258.top/Article/details/gtwgthksim.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.quarkkingdee.top/Article/details/gtwbhylodu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gtjgbqfodk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yonumen.top/Article/details/gtawmghslj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fzhhl.top/Article/details/gtolkxbgtl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guannengcc.top/Article/details/gtbpwelqqs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenjidiqi.icu/Article/details/gtfpocawdz.html

[N04] 斐波那契数列
来源：http://dali.0kj1m.cn/Article/details/gtcywhcueu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gogol.net.cn/Article/details/gtwlorwcdh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fzhhl.top/Article/details/gtfeskgluj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtukutwgla.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtcnchwyxw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.birdmap.top/Article/details/gtyqbkxsxv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pycfn.com/Article/details/gtryfflhbp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gtrdvnojwt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtqtdjztks.html

[N05] 最大公约数
来源：http://dali.guannengcc.top/Article/details/gtyawhqwta.html

Py:   math.gcd(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtzkeuczpy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yonumen.top/Article/details/gtzxhbdsvc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gtdxuxfksl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gtjrsfchnw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.redwolf501.top/Article/details/gtmmmvzofa.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuanzx.com/Article/details/gtqkqcebtc.html

Ruby: a.gcd(b)
来源：http://dali.ehwqpu.com/Article/details/gtxbcfqgpw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ehwqpu.com/Article/details/gturdaerim.html

[N06] 判断回文字符串
来源：http://dali.ehwqpu.com/Article/details/gtwmvifott.html

Py:   s == s[::-1]
来源：http://dali.xziqi.cn/Article/details/gtxipazkzj.html

PHP:  $s === strrev($s);
来源：http://dali.sysykeji.top/Article/details/gtxewmqvoy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtchqocimp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gttduenork.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shzxlz.cn/Article/details/gthuanuqgw.html

Go:   // 双指针从两端比较
来源：http://dali.hongshengwenyu.top/Article/details/gttzrvzfdl.html

Ruby: s == s.reverse
来源：http://dali.xziqi.cn/Article/details/gtamkzxwgc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gtzkiisywl.html

[N07] 两数之和（返回下标）
来源：http://dali.hongshengwenyu.top/Article/details/gthidwlajm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.iojbl.cn/Article/details/gtsbyulshu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zdqjudy.top/Article/details/gtsndwtpmi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigufen.top/Article/details/gtywfsxhex.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj202588.top/Article/details/gtshwthrsz.html

Java: // 手写 HashMap
来源：http://dali.zhiwuduotai.top/Article/details/gtnbqvcffu.html

Go:   // 手写 map[int]int
来源：http://dali.andypj.xyz/Article/details/gtvjfjzlkk.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoipovosn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jianghu66.top/Article/details/gtoxxhbfgq.html

[N08] 生成全排列
来源：http://dali.chenlongwang.top/Article/details/gtplfyokcp.html

Py:   itertools.permutations(arr)
来源：http://dali.snrcjt.cn/Article/details/gtvexcolwg.html

PHP:  // 手写递归交换
来源：http://dali.yuxming.cn/Article/details/gtdlheehga.html

JS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gthxqujsnd.html

TS:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtrkufihob.html

Java: // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtrqndjokq.html

Go:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtueblvmvu.html

Ruby: arr.permutation.to_a
来源：http://dali.quarkkingdee.top/Article/details/gtteuauxtj.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtubzjyxwf.html

[N09] 栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gtcateyhch.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tian-w.cn/Article/details/gtdgwtbrxj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gtlwdwqjay.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtpngakuwa.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cqqwz.cn/Article/details/gtrssxwdzr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hysaishi.cn/Article/details/gtmnnnyihh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhspnrfx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtskweelhv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.birdmap.top/Article/details/gtkgdzohed.html

[N10] 链表节点定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnhqpzun.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zycfv.cn/Article/details/gtzlkpatvi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuxming.cn/Article/details/gttzdiyeus.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtjgmwguiz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jyoumei.cn/Article/details/gtjqssvoeq.html

Java: class Node { int v; Node next; }
来源：http://dali.xuetiantiany.cn/Article/details/gtyuvdpahb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenlongwang.top/Article/details/gtcousleqd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hongshengwenyu.top/Article/details/gtzcxrmlbe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuanzhike.top/Article/details/gtckgdiart.html

[N11] 二叉树中序遍历
来源：http://dali.jyoumei.cn/Article/details/gtrypzuvdc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqdhxkgq.html

PHP:  // 手写递归函数
来源：http://dali.yongpay.top/Article/details/gtquxcpwqm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxuanxn.top/Article/details/gtxmecipug.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gtqqdvwmua.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gtkcianjzz.html

Go:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtltdgghtb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cashguo.top/Article/details/gtcvdivdkf.html

C#:   // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gtyjmqgyes.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvsrsycn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.316326.xyz/Article/details/gtanwsngmw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.vqdsnc.cn/Article/details/gtafdyjcol.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.9152youxi.cn/Article/details/gtesxasryc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gtugqexbao.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gtdohdknpy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yonumen.top/Article/details/gtdzwggzro.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuanzhike.top/Article/details/gtoddvnzrr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigufen.top/Article/details/gtawmeeaxq.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtmlgfwjfx.html

O. 并发与异步
来源：http://dali.kuanghao11.cn/Article/details/gtsextyvcz.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtngomkfyp.html

[O01] 启动一个线程
来源：http://dali.zycfv.cn/Article/details/gtulhubavv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pycfn.com/Article/details/gtxfymxygz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tianlin.xyz/Article/details/gtieklddvv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenjidiqi.icu/Article/details/gtpwaallza.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gtgvybaits.html

Java: new Thread(() -> f()).start()
来源：http://dali.haohaochexian.top/Article/details/gtbnqkzbty.html

Go:   go f()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmivqvowh.html

Ruby: Thread.new { f }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrsdntzs.html

C#:   Task.Run(() => F());
来源：http://dali.chenlongwang.top/Article/details/gtlpvjxnxq.html

[O02] 使用线程池
来源：http://dali.xylfe.cn/Article/details/gtflsdejqk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shuidangran.top/Article/details/gtpywippgs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.svipenyu.cn/Article/details/gtpmzxbvre.html

JS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gttxbpqdqe.html

TS:   // worker_threads 线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtvvyhwmne.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.smart0.xyz/Article/details/gtxdcerray.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangshuangyany.cn/Article/details/gtmpiagczb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gotoacloud.top/Article/details/gtusewkpyk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yueranfly.top/Article/details/gtqoypsfxy.html

[O03] 加锁保护共享数据
来源：http://dali.wangshuangyany.cn/Article/details/gtqwmissyu.html

Py:   with lock: shared += 1
来源：http://dali.yvedp.cn/Article/details/gtysrnkibk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pycfn.com/Article/details/gteqegwgwt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gotoacloud.top/Article/details/gttiyaxetz.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gtuukhrnry.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhengqikj.top/Article/details/gtmlldbrbl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cashguo.top/Article/details/gtvqzsgynu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xinyue.icu/Article/details/gtpusrylnx.html

C#:   lock (gate) { shared++; }
来源：http://dali.bjfxy.top/Article/details/gthrexbmdq.html

[O04] 定义异步函数并等待
来源：http://dali.0kj1m.cn/Article/details/gtuwdaebty.html

Py:   async def f():⏎    await g()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkgdunky.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xziqi.cn/Article/details/gtjddxyfes.html

JS:   async function f() { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gtndquklxy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gtrumqppor.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.smart0.xyz/Article/details/gtdxnjuibg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvepvuvd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.kuanghao11.cn/Article/details/gtjqhqgirh.html

C#:   async Task F() { await G(); }
来源：http://dali.haohaochexian.top/Article/details/gtonhxjrae.html

[O05] 并发执行并等待全部完成
来源：http://dali.yongpay.top/Article/details/gtmcixuyyj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtllshspbo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhiwuduotai.top/Article/details/gtagbsfdgi.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gtivcxnlog.html

TS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gtaeuoefjh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cucudq.cn/Article/details/gtdzpvsceg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hywenlv.cn/Article/details/gtjtswlycn.html

Ruby: threads.map(&:join)
来源：http://dali.jqgfzy.top/Article/details/gtrzccgdza.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gotoacloud.top/Article/details/gtoexyxkec.html

[O06] 使用进程池
来源：http://dali.yvedp.cn/Article/details/gtpiqwhoza.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.aibaodan.cn/Article/details/gtnrnaaoql.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj20258888.top/Article/details/gtnpprinyd.html

JS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gtfybgcogg.html

TS:   // child_process / cluster 模块
来源：http://dali.yj202588.top/Article/details/gtsnlpaipx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hysaishi.cn/Article/details/gtupzgerzu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hongshengwenyu.top/Article/details/gtbjwgauua.html

Ruby: // fork 块
来源：http://dali.0kj1m.cn/Article/details/gtaexvjgyv.html

C#:   Parallel.For
来源：http://dali.fengsongda.top/Article/details/gtfybpokip.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtvapdfwwp.html

P. 常用工具函数
来源：http://dali.gogol.net.cn/Article/details/gtdukbjmjk.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtrhrdwgut.html

[P01] 生成 UUID
来源：http://dali.pycfn.com/Article/details/gtuckkehxn.html

Py:   str(uuid.uuid4())
来源：http://dali.jyoumei.cn/Article/details/gtsgllapvj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.pengpengdd.cyou/Article/details/gtdnziamzy.html

JS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gtuqeqphsf.html

TS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtvsuixdkh.html

Java: UUID.randomUUID().toString()
来源：http://dali.meibo888.top/Article/details/gtgyrbcybp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtfyaarfuv.html

Ruby: SecureRandom.uuid
来源：http://dali.birdmap.top/Article/details/gttaepefmn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tian-w.cn/Article/details/gtxhcvmfoo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuanzhike.top/Article/details/gtierkaqmc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigufen.top/Article/details/gtfkmfrvuv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcypyyfm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.quarkkingdee.top/Article/details/gtuyslewxa.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhongyouzk.top/Article/details/gtpnldnjez.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbsaksavp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhpxzkqa.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgufenzy.top/Article/details/gtocnvtndz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shangyingyoupin.top/Article/details/gtylvxjluo.html

[P03] 生成短随机字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtgoydwwgz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yvedp.cn/Article/details/gtfvilfctr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.fzhhl.top/Article/details/gtrjpusjbw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gtdgelalym.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogfazamu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.iojbl.cn/Article/details/gtigkydafw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.havefunace.top/Article/details/gtttuagium.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.mhx1999.top/Article/details/gthayemnmi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuxming.cn/Article/details/gtnfabdoqa.html

[P04] 求长度
来源：http://dali.cucudq.cn/Article/details/gtfztwfpcn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuxming.cn/Article/details/gtysuedigx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtyfazvpyc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtpdfrjwsv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gtrzmifjtz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.iojbl.cn/Article/details/gtutxymdfy.html

Go:   len(arr);  len(m)
来源：http://dali.zhengqikj.top/Article/details/gtmytkmofl.html

Ruby: x.length;  x.size
来源：http://dali.bjfxy.top/Article/details/gtsekiseqt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tianlin.xyz/Article/details/gtqswtvmnb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxinkj.top/Article/details/gtqwrvsnec.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sysykeji.top/Article/details/gtjegcceod.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yangfankeji.com/Article/details/gtyujllvkz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhongyouzk.top/Article/details/gtkdhysfaa.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhiwuduotai.top/Article/details/gthruopabz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xylfe.cn/Article/details/gtxqunxuqb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.smart0.xyz/Article/details/gtqrwuovvp.html

Ruby: a == b
来源：http://dali.yj20258888.top/Article/details/gtbpodkkrf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhoulong.xyz/Article/details/gthjswdzhh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbplbvijm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zycfv.cn/Article/details/gtmamfcwky.html

PHP:  if (empty($x)) {}
来源：http://dali.ydzc1.top/Article/details/gtzkraysos.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhongyouzk.top/Article/details/gteuoybyxf.html

TS:   if (x == null) {}
来源：http://dali.sufxvd.cn/Article/details/gtvhlltfqo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jqgufenzy.top/Article/details/gtczfllwjp.html

Go:   if x == nil {}
来源：http://dali.hysaishi.cn/Article/details/gtjswxpbrd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cdnleiting.top/Article/details/gtfmuheybc.html

C#:   if (x is null) {}
来源：http://dali.yj20258.top/Article/details/gtdxuodlum.html

[P07] 防抖与节流
来源：http://dali.vqdsnc.cn/Article/details/gtyuzpygbu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhixingplan.top/Article/details/gtjgmbnduo.html


<!-- 参考信息 -->