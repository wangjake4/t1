代发 wailian999

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtcnpcaxyx.html

[M01] 读取命令行参数
来源：http://dali.hnqzz.top/Article/details/gtrmeqqwfz.html

Py:   sys.argv[1:]
来源：http://dali.zhongyouzk.top/Article/details/gtvxuueuuq.html

PHP:  $argv;  $argc;
来源：http://dali.shzxlz.cn/Article/details/gtnhfoonhx.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gtrtyhqwiv.html

TS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gteqrowtrb.html

Java: args 数组（main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gthrdjguzv.html

Go:   os.Args[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtinidmhfo.html

Ruby: ARGV
来源：http://dali.zhiwuduotai.top/Article/details/gtsnqknyla.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gtilmbptod.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtngljvzzw.html

Py:   os.environ.get("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmenkcbfr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gtseychdew.html

JS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gtdpkegisl.html

TS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gtdkoxousm.html

Java: System.getenv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtiegmdtam.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fzhhl.top/Article/details/gtwdeakhbg.html

Ruby: ENV["HOME"]
来源：http://dali.cdnleiting.top/Article/details/gtlrvzhcfu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtnrbstmzb.html

[M03] 执行外部命令
来源：http://dali.9152youxi.cn/Article/details/gtvysusvjp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aizwys.cn/Article/details/gtwdvdaoyc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.havefunace.top/Article/details/gtlbmjjcej.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiidaiycl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gtirafsagk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenjidiqi.icu/Article/details/gtccyvedjb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hysaishi.cn/Article/details/gtvysfaxhy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shzxlz.cn/Article/details/gtyapirjed.html

C#:   Process.Start("ls", "-l");
来源：http://dali.mhx1999.top/Article/details/gtdxepbmzk.html

[M04] 获取当前工作目录
来源：http://dali.yonumen.top/Article/details/gtnjvzfeus.html

Py:   os.getcwd()
来源：http://dali.aibaodan.cn/Article/details/gtrjlaxujg.html

PHP:  getcwd();
来源：http://dali.yuxming.cn/Article/details/gtcfefvmps.html

JS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gtatlriomj.html

TS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gttvphiwbo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.smart0.xyz/Article/details/gthiiuomwg.html

Go:   os.Getwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpeagmof.html

Ruby: Dir.pwd
来源：http://dali.hysaishi.cn/Article/details/gticidjwid.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pycfn.com/Article/details/gtfnrwqhmc.html

[M05] 设置退出码
来源：http://dali.cashguo.top/Article/details/gtpjyqhije.html

Py:   sys.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtfkvnzfpa.html

PHP:  exit(1);
来源：http://dali.wangshuangyany.cn/Article/details/gtqbkbomla.html

JS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gtvdvegynv.html

TS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtfagdvgbr.html

Java: System.exit(1)
来源：http://dali.316326.xyz/Article/details/gtsjviojtn.html

Go:   os.Exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtzbwzvslg.html

Ruby: exit 1
来源：http://dali.guowangkeji.top/Article/details/gtanjjufck.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.iojbl.cn/Article/details/gtdwaamaje.html

[M06] 向标准错误输出
来源：http://dali.shangyingyoupin.top/Article/details/gtaattuunh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yongpay.top/Article/details/gtvlpetfwk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.smart0.xyz/Article/details/gtrrtaopkv.html

JS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gtxmkekkfl.html

TS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gtuxacsxnh.html

Java: System.err.println("err")
来源：http://dali.gzhubu.top/Article/details/gtsrmeuasm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenlongwang.top/Article/details/gtpintpivf.html

Ruby: warn "err"
来源：http://dali.xuanzx.com/Article/details/gtpqwlkcov.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj202588.top/Article/details/gtygzmgqvr.html

[M07] 判断是否为主入口
来源：http://dali.fengsongda.top/Article/details/gtiuwndqgy.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgufenzy.top/Article/details/gtdwdipkmx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxuanxn.top/Article/details/gtccqzogfx.html

JS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gtmiuirzys.html

TS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gttltehdjl.html

Java: public static void main(String[] args)
来源：http://dali.smart0.xyz/Article/details/gtdtdtfphn.html

Go:   func main()
来源：http://dali.mhx1999.top/Article/details/gtbwjuxjrr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hammf.cn/Article/details/gtrfpqnqcp.html

C#:   static void Main(string[] args)
来源：http://dali.mhx1999.top/Article/details/gtdqhitspg.html

[M08] 获取系统与运行时信息
来源：http://dali.cqqwz.cn/Article/details/gtiyzrlfhx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.bjfxy.top/Article/details/gtwmvzkkto.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ehwqpu.com/Article/details/gtipbfpooy.html

JS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gtfmqspatj.html

TS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gtpfggoztc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aibaodan.cn/Article/details/gtwzexnupa.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hammf.cn/Article/details/gtesjosgku.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cqqwz.cn/Article/details/gtjhurciqe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hysaishi.cn/Article/details/gthzgzszzx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtkkdseivs.html

N. 数据结构与算法
来源：http://dali.kuanghao11.cn/Article/details/gtlmhtsrhn.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtenrdbwtx.html

[N01] 二分查找（有序数组）
来源：http://dali.chenlongwang.top/Article/details/gtnynvoqpc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtunbxwxjy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cheryme.top/Article/details/gthylhmcyx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtrcokyani.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gtjgevlicp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgypaedst.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtwghodrbc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aibaodan.cn/Article/details/gtdbzzatqc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtseenqkwl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sweek.top/Article/details/gtuqahpabg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gtivobcict.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgfzy.top/Article/details/gthsaglfyk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gttfsbbmaz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gtqqgasmyk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ppjwa.cn/Article/details/gtxefcgxmp.html

Go:   slices.Sort(arr)
来源：http://dali.tianlin.xyz/Article/details/gtfzxfohqn.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gthtuktnmf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gotoacloud.top/Article/details/gthqxphacv.html

[N03] 快速排序（分治示例）
来源：http://dali.sxryk.cn/Article/details/gtxoftvqjr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhhtbymx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gogol.net.cn/Article/details/gtunpskabd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrbntojw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shuidangran.top/Article/details/gthfqkgnje.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj202588.top/Article/details/gtwlzsquxx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tian-w.cn/Article/details/gtcwgrpbhb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhixingplan.top/Article/details/gtjetkjycz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sweek.top/Article/details/gtqnraexmz.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzvwgewf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtofhrsiuj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gtutkktbqz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gtxsmliwsl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtttbuamue.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cdnleiting.top/Article/details/gtusgafgke.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.snrcjt.cn/Article/details/gtjvzttrob.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ehwqpu.com/Article/details/gttqlccwyd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtpqkzrvbs.html

[N05] 最大公约数
来源：http://dali.xinyue.icu/Article/details/gtqxspuihz.html

Py:   math.gcd(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtywwmuwkr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yongpay.top/Article/details/gtuyvzvmlo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gtqmabsbhf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gtahjuctcs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cucudq.cn/Article/details/gtmrusaibw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cashguo.top/Article/details/gtcbchnzmy.html

Ruby: a.gcd(b)
来源：http://dali.sweek.top/Article/details/gtndlqbwzq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gzhubu.top/Article/details/gtnintyljo.html

[N06] 判断回文字符串
来源：http://dali.tianlin.xyz/Article/details/gtkljlvrky.html

Py:   s == s[::-1]
来源：http://dali.cashguo.top/Article/details/gtpsrhjnng.html

PHP:  $s === strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gtcrgjscsn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtfuglumzg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtlsahygzk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gotoacloud.top/Article/details/gtngdyxobr.html

Go:   // 双指针从两端比较
来源：http://dali.chenlongwang.top/Article/details/gtrwpssfox.html

Ruby: s == s.reverse
来源：http://dali.jianghu66.top/Article/details/gtnhsuixad.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaalankam.html

[N07] 两数之和（返回下标）
来源：http://dali.feifeiyinyue.top/Article/details/gtmbobaaow.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.snrcjt.cn/Article/details/gtyczdjsbv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cucudq.cn/Article/details/gtgyoogtoq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gotoacloud.top/Article/details/gtrgycoajf.html

TS:   // 手写 Map<string, number>
来源：http://dali.sweek.top/Article/details/gtpffbooey.html

Java: // 手写 HashMap
来源：http://dali.hysaishi.cn/Article/details/gtaktbeias.html

Go:   // 手写 map[int]int
来源：http://dali.jiagoushi.top/Article/details/gtxfajndzb.html

Ruby: // 手写 Hash
来源：http://dali.fengsongda.top/Article/details/gtyiqyfsck.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cqqwz.cn/Article/details/gtzyplfrve.html

[N08] 生成全排列
来源：http://dali.cheryme.top/Article/details/gtvchwlzgt.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtvrqycijk.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangtech.top/Article/details/gtunelxgpt.html

JS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtddwomudv.html

TS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtgqnkjego.html

Java: // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtyccnpaxd.html

Go:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtgomjecfr.html

Ruby: arr.permutation.to_a
来源：http://dali.0kj1m.cn/Article/details/gthuqotqke.html

C#:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gttuboozoa.html

[N09] 栈与队列
来源：http://dali.gzhubu.top/Article/details/gtbfskrnzd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shzxlz.cn/Article/details/gtjcliqozx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jianghu66.top/Article/details/gtackkxypv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gtdadevvld.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sysykeji.top/Article/details/gtpewfhozf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.havefunace.top/Article/details/gtrwpzrfda.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hongshengwenyu.top/Article/details/gtdqvucjxr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gtbanuebhu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnxiangtu.top/Article/details/gtymplkuln.html

[N10] 链表节点定义
来源：http://dali.birdmap.top/Article/details/gtuuidaqyd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmavrljnx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxinkj.top/Article/details/gtcdouybhn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.pycfn.com/Article/details/gtfejdgaml.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gtyqtpwpif.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgazzahuu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangshuangyany.cn/Article/details/gtycgxhvsq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258888.top/Article/details/gtirlppyzh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgefvdquw.html

[N11] 二叉树中序遍历
来源：http://dali.yongpay.top/Article/details/gtexbsqaic.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cucudq.cn/Article/details/gtngspuriz.html

PHP:  // 手写递归函数
来源：http://dali.hfpthk.cn/Article/details/gttkgrupaq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwyctcvyj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gtjcbcierq.html

Java: // 手写递归
来源：http://dali.xziqi.cn/Article/details/gtxasaeurm.html

Go:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtyijhzegh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tianlin.xyz/Article/details/gtmynbjhhl.html

C#:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gtnfeydxyn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.kuanghao11.cn/Article/details/gtfsegmesd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fengsongda.top/Article/details/gtmdhzwomj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj20258888.top/Article/details/gtxgosalva.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258.top/Article/details/gtrkmihnap.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sysykeji.top/Article/details/gtjswoezwy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gtwtfeptjj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258.top/Article/details/gtiyggesuc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenjidiqi.icu/Article/details/gtgpfpqbjd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.redwolf501.top/Article/details/gtoqamlwpn.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtyvhdtbco.html

O. 并发与异步
来源：http://dali.zhengqikj.top/Article/details/gtrojmfdqt.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtqmgdcljr.html

[O01] 启动一个线程
来源：http://dali.guannengcc.top/Article/details/gtxxwcfvhr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yueranfly.top/Article/details/gtdexzytxb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.fzhhl.top/Article/details/gtmookeqin.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xziqi.cn/Article/details/gtwgbjgbfa.html

TS:   // 同 JS
来源：http://dali.fzhhl.top/Article/details/gtqvwbrpgf.html

Java: new Thread(() -> f()).start()
来源：http://dali.shangyingyoupin.top/Article/details/gtsatnrdfm.html

Go:   go f()
来源：http://dali.gogol.net.cn/Article/details/gtuxekrcsz.html

Ruby: Thread.new { f }
来源：http://dali.mhx1999.top/Article/details/gtialklkyw.html

C#:   Task.Run(() => F());
来源：http://dali.xuetiantiany.cn/Article/details/gtudoirjrd.html

[O02] 使用线程池
来源：http://dali.jqgufenzy.top/Article/details/gtyuaqjnjv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gogol.net.cn/Article/details/gtncviseig.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ehwqpu.com/Article/details/gtoepjauwi.html

JS:   // worker_threads 线程池
来源：http://dali.sxryk.cn/Article/details/gtitvdssww.html

TS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gtcazziccw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangshuangyany.cn/Article/details/gtsdlnndnc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ehwqpu.com/Article/details/gtelhlqsqi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.dianchejie.cn/Article/details/gtndupmoyx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gzhubu.top/Article/details/gtvhyljzti.html

[O03] 加锁保护共享数据
来源：http://dali.yj20258888.top/Article/details/gtjlkpnyhx.html

Py:   with lock: shared += 1
来源：http://dali.gotoacloud.top/Article/details/gtnqadtlhb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nwbrower.top/Article/details/gtdmhkktiv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nwbrower.top/Article/details/gtbfwkwfmw.html

TS:   // 同 JS
来源：http://dali.yuanzhike.top/Article/details/gthvinjwvw.html

Java: synchronized (this) { shared++; }
来源：http://dali.vqdsnc.cn/Article/details/gthtegkkvu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dianchejie.cn/Article/details/gtriqjqiwe.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.svipenyu.cn/Article/details/gtirowfyze.html

C#:   lock (gate) { shared++; }
来源：http://dali.wangshuangyany.cn/Article/details/gttkvkyyqv.html

[O04] 定义异步函数并等待
来源：http://dali.hnxiangtu.top/Article/details/gtkrfxdssd.html

Py:   async def f():⏎    await g()
来源：http://dali.tianlin.xyz/Article/details/gtxfzbqnkq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yongpay.top/Article/details/gtydtmrgnh.html

JS:   async function f() { await g(); }
来源：http://dali.cucudq.cn/Article/details/gtzywdkypl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ivvv.top/Article/details/gtnbvfwsfo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.aizwys.cn/Article/details/gtsoaryqkn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sysykeji.top/Article/details/gttajkzcnm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yanxiufei.cn/Article/details/gtjhxulgfi.html

C#:   async Task F() { await G(); }
来源：http://dali.gogol.net.cn/Article/details/gtwjafzbrg.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgimuyvom.html

Py:   asyncio.gather(*tasks)
来源：http://dali.fzhhl.top/Article/details/gtrmyugbrj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zdqjudy.top/Article/details/gtqhxrychc.html

JS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gtrbsxflvf.html

TS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gttikvqijt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.svipenyu.cn/Article/details/gtjybhctzq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yvedp.cn/Article/details/gttxnorlyo.html

Ruby: threads.map(&:join)
来源：http://dali.ivvv.top/Article/details/gtxtqzstmz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jiagoushi.top/Article/details/gtpsljfoji.html

[O06] 使用进程池
来源：http://dali.hammf.cn/Article/details/gtwgijrebu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.svipenyu.cn/Article/details/gtwljwxdaj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fzhhl.top/Article/details/gtzjxysnmj.html

JS:   // child_process / cluster 模块
来源：http://dali.cheryme.top/Article/details/gttuxcavkd.html

TS:   // child_process / cluster 模块
来源：http://dali.ydzc1.top/Article/details/gtuwmegbnd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sufxvd.cn/Article/details/gtpumdfrbe.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hammf.cn/Article/details/gttjmrhzrq.html

Ruby: // fork 块
来源：http://dali.jianghu66.top/Article/details/gtroytfnpr.html

C#:   Parallel.For
来源：http://dali.quarkkingdee.top/Article/details/gttcbssytr.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gteziivtda.html

P. 常用工具函数
来源：http://dali.shzxlz.cn/Article/details/gtdvknywea.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtkksrysku.html

[P01] 生成 UUID
来源：http://dali.guowangkeji.top/Article/details/gtggovhgdz.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258888.top/Article/details/gtesesyvsg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhixingplan.top/Article/details/gtlndgxhtl.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gtwvutriaa.html

TS:   crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gtjyvjfann.html

Java: UUID.randomUUID().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtbmsdcigu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nanxuanxn.top/Article/details/gtbwpsekuq.html

Ruby: SecureRandom.uuid
来源：http://dali.jiagoushi.top/Article/details/gtothtxnhv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhongyouzk.top/Article/details/gtdebfivnt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangdashe.top/Article/details/gttpcafogq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.guannengcc.top/Article/details/gtcpiucuqh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sysykeji.top/Article/details/gtzhvqefbg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ybcxt.top/Article/details/gtdvdnvjwx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gogol.net.cn/Article/details/gtrwsxgvuj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtgkgxldrx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.pycfn.com/Article/details/gteneynmqk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuxming.cn/Article/details/gtxdclcexo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.guannengcc.top/Article/details/gteltxgvvs.html

[P03] 生成短随机字符串
来源：http://dali.guowangkeji.top/Article/details/gtkjdszbhv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sufxvd.cn/Article/details/gtrrnbeset.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhixingplan.top/Article/details/gtlvjpjvvf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gtovypqcon.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sxryk.cn/Article/details/gttvgylwba.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ydzc1.top/Article/details/gtsxdblnah.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.havefunace.top/Article/details/gtnczylter.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtelgmwbec.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ydzc1.top/Article/details/gtviizxznn.html

[P04] 求长度
来源：http://dali.gotoacloud.top/Article/details/gtbmxfcccg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgfzy.top/Article/details/gtljhbbsts.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtiyvgeuto.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gtqrecmitl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yvedp.cn/Article/details/gtzijxxqrl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.birdmap.top/Article/details/gthtwwhgae.html

Go:   len(arr);  len(m)
来源：http://dali.c1oappe.top/Article/details/gtvhcqrsnd.html

Ruby: x.length;  x.size
来源：http://dali.redwolf501.top/Article/details/gtaxqxeeks.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gotoacloud.top/Article/details/gtqwzyjlzr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yanxiufei.cn/Article/details/gtluammbby.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvystufvw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hywenlv.cn/Article/details/gtsnloajqh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ehwqpu.com/Article/details/gtlyqllzdt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xylfe.cn/Article/details/gtqdzyoupj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.smart0.xyz/Article/details/gtwclhbntw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.andypj.xyz/Article/details/gtkmjrprvr.html

Ruby: a == b
来源：http://dali.cdnleiting.top/Article/details/gtfdnwphwa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigfzy.top/Article/details/gtysxxsvvu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sweek.top/Article/details/gtbonqmyms.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yuxming.cn/Article/details/gtemttjnqx.html

PHP:  if (empty($x)) {}
来源：http://dali.c1oappe.top/Article/details/gtonjudqxc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shanyushiyangkeji.top/Article/details/gtllwagzid.html

TS:   if (x == null) {}
来源：http://dali.birdmap.top/Article/details/gtzwfhfmbb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gtlqcwfcem.html

Go:   if x == nil {}
来源：http://dali.guowangkeji.top/Article/details/gtwfenbkzw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yvedp.cn/Article/details/gtnuyxnfak.html

C#:   if (x is null) {}
来源：http://dali.nanxinkj.top/Article/details/gtgfecbrfc.html

[P07] 防抖与节流
来源：http://dali.shuidangran.top/Article/details/gtzlfkjvrk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zdqjudy.top/Article/details/gtsrgpjxpi.html


<!-- 参考信息 -->