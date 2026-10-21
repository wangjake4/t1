代发 wailian999

Ruby: ARGV
来源：http://dali.shzxlz.cn/Article/details/gtrxoaeyza.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gtmurquibc.html

[M02] 读取环境变量
来源：http://dali.zhoulong.xyz/Article/details/gtpnoromqq.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcygmqif.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gtanckbpjy.html

JS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gtvpvzikac.html

TS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtofrcpmzi.html

Java: System.getenv("HOME")
来源：http://dali.hnqzz.top/Article/details/gtugxeqwav.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtummaobbv.html

Ruby: ENV["HOME"]
来源：http://dali.tanke756.top/Article/details/gtdeypnyev.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hammf.cn/Article/details/gtmvmjiwpz.html

[M03] 执行外部命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqfdxzfv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aizwys.cn/Article/details/gtoxgsxncs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhongyouzk.top/Article/details/gtrcxvcujv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gtnlhcfzig.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gtjkbzqytp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhixingplan.top/Article/details/gtrhgsuavh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daria6918.cn/Article/details/gtqnufhtod.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.birdmap.top/Article/details/gttlsacthd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guowangkeji.top/Article/details/gtezcapplm.html

[M04] 获取当前工作目录
来源：http://dali.316326.xyz/Article/details/gtdaxesbmx.html

Py:   os.getcwd()
来源：http://dali.gaohongyu789.top/Article/details/gtthsntbxh.html

PHP:  getcwd();
来源：http://dali.zhixingplan.top/Article/details/gtztleaons.html

JS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtxgpqgbpa.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gtrlftzpzr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daxiang520.top/Article/details/gtysvaalui.html

Go:   os.Getwd()
来源：http://dali.ybcxt.top/Article/details/gtuoysfvje.html

Ruby: Dir.pwd
来源：http://dali.jinghuilouyu.cn/Article/details/gtulhuqdfo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shangyingyoupin.top/Article/details/gtonjzaxso.html

[M05] 设置退出码
来源：http://dali.yvedp.cn/Article/details/gtruglqcpz.html

Py:   sys.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtsrrpojca.html

PHP:  exit(1);
来源：http://dali.dianchejie.cn/Article/details/gteaumygfv.html

JS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtxdcrupjs.html

TS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtghmbrsat.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtreerbdbv.html

Go:   os.Exit(1)
来源：http://dali.smart0.xyz/Article/details/gtrgzuotmz.html

Ruby: exit 1
来源：http://dali.meibo888.top/Article/details/gtemnktrel.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cdnleiting.top/Article/details/gtbwqwyfyb.html

[M06] 向标准错误输出
来源：http://dali.jianghu66.top/Article/details/gtngamjvxm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ehwqpu.com/Article/details/gtfytybehy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.snrcjt.cn/Article/details/gthpgcnigi.html

JS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gtlevdynca.html

TS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqtrfmjh.html

Java: System.err.println("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtbzzecyac.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cqqwz.cn/Article/details/gtpcsdwliy.html

Ruby: warn "err"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvecryplx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj202588.top/Article/details/gtnoaabzwc.html

[M07] 判断是否为主入口
来源：http://dali.iojbl.cn/Article/details/gtyatxvunr.html

Py:   if __name__ == "__main__":
来源：http://dali.hnxiangtu.top/Article/details/gtqmurxroa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangdashe.top/Article/details/gtglnpreyt.html

JS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gtygbqnbal.html

TS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gtnogcfvux.html

Java: public static void main(String[] args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjoqgrqq.html

Go:   func main()
来源：http://dali.xinyue.icu/Article/details/gtdiiumsot.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cheryme.top/Article/details/gtjybnrrjz.html

C#:   static void Main(string[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gtxgqmqxew.html

[M08] 获取系统与运行时信息
来源：http://dali.yuanzhike.top/Article/details/gtivhzkvne.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fzhhl.top/Article/details/gtrxffqxiq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258.top/Article/details/gtmgfbbgpm.html

JS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gtikxdobzu.html

TS:   process.platform;  process.version
来源：http://dali.yuxming.cn/Article/details/gtxtlfdnqq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhoulong.xyz/Article/details/gtjgyffdbt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ivvv.top/Article/details/gtggykgwun.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxqxakfg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnxiangtu.top/Article/details/gtqrfogiqd.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtsbiccuwi.html

N. 数据结构与算法
来源：http://dali.wangdashe.top/Article/details/gtuysipwtp.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddlaqttn.html

[N01] 二分查找（有序数组）
来源：http://dali.ehwqpu.com/Article/details/gtcuwyjkde.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtlzlylqfe.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtacywcbbi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gtnomdoljl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gtzagxxjrp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtnufejhxl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtcqypkzgs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnxiangtu.top/Article/details/gtwmnzynyi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaltncidg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.feifeiyinyue.top/Article/details/gtxbhgnbgc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gtdnmuxdoa.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gotoacloud.top/Article/details/gtnugxdavx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtndxhxtfo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gtvwggwqpy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenlongwang.top/Article/details/gttfdswtiq.html

Go:   slices.Sort(arr)
来源：http://dali.0kj1m.cn/Article/details/gtjlyvbrfj.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gtxebukheh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtxnuoadez.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxuanxn.top/Article/details/gtxrpjtved.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hywenlv.cn/Article/details/gtxsodmhdm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.9152youxi.cn/Article/details/gtckpgmjtu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gtkgaffrvq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgyyvknmc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ppjwa.cn/Article/details/gtpjcoembb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xziqi.cn/Article/details/gtkupkszva.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhengqikj.top/Article/details/gtijzyjnxb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ydzc1.top/Article/details/gtdrdjbycv.html

[N04] 斐波那契数列
来源：http://dali.yj20258.top/Article/details/gtmujjytlk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jiagoushi.top/Article/details/gtconkdfdi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gtbxvvppii.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gttppwepej.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtglzlxptu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gtadvpbgri.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenlongwang.top/Article/details/gtqenjzdne.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gtguwdqxnz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gtkaikjgeb.html

[N05] 最大公约数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtmojmnx.html

Py:   math.gcd(a, b)
来源：http://dali.hysaishi.cn/Article/details/gttsfpvoud.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtphqytnxm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.smart0.xyz/Article/details/gtsmitjjbj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gtrcwlvbrb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhongyouzk.top/Article/details/gtxuijrjab.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhixingplan.top/Article/details/gtwxwsvupq.html

Ruby: a.gcd(b)
来源：http://dali.tian-w.cn/Article/details/gtjempyiab.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guannengcc.top/Article/details/gtuqpjwgki.html

[N06] 判断回文字符串
来源：http://dali.hfpthk.cn/Article/details/gtmuorjasx.html

Py:   s == s[::-1]
来源：http://dali.birdmap.top/Article/details/gtnghtuhjx.html

PHP:  $s === strrev($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtbeherauy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtulnusaym.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtppwdebrb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.smart0.xyz/Article/details/gtiwxfbqvl.html

Go:   // 双指针从两端比较
来源：http://dali.mhx1999.top/Article/details/gthajreinh.html

Ruby: s == s.reverse
来源：http://dali.cqqwz.cn/Article/details/gtljpzrspq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.pengpengdd.cyou/Article/details/gtjdikupjy.html

[N07] 两数之和（返回下标）
来源：http://dali.hywenlv.cn/Article/details/gtprchmcfo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hongshengwenyu.top/Article/details/gtekmatkse.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuanzx.com/Article/details/gtecfluhfv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hammf.cn/Article/details/gtfppiafmg.html

TS:   // 手写 Map<string, number>
来源：http://dali.hnqzz.top/Article/details/gtmycrmyyw.html

Java: // 手写 HashMap
来源：http://dali.meibo888.top/Article/details/gtfyguxrxj.html

Go:   // 手写 map[int]int
来源：http://dali.chenjidiqi.icu/Article/details/gteeimrhtp.html

Ruby: // 手写 Hash
来源：http://dali.wangdashe.top/Article/details/gtziujfkep.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sweek.top/Article/details/gtreudhree.html

[N08] 生成全排列
来源：http://dali.cdnleiting.top/Article/details/gtxwhcizar.html

Py:   itertools.permutations(arr)
来源：http://dali.zycfv.cn/Article/details/gtmggkqnwq.html

PHP:  // 手写递归交换
来源：http://dali.birdmap.top/Article/details/gtotuglgqa.html

JS:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtkjiioovq.html

TS:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtmjrotvzc.html

Java: // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtwytiudsb.html

Go:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtymddaaif.html

Ruby: arr.permutation.to_a
来源：http://dali.yuxming.cn/Article/details/gtkziatvve.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtngipgwgj.html

[N09] 栈与队列
来源：http://dali.chenlongwang.top/Article/details/gtvdlmfhte.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjpcpkryb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nwbrower.top/Article/details/gttlnlfgrn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gtcolcsktj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jiagoushi.top/Article/details/gtoschngup.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.haohaochexian.top/Article/details/gtfazdglms.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shuidangran.top/Article/details/gtodgskypj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gtpofayliy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.redwolf501.top/Article/details/gtmxbcldfm.html

[N10] 链表节点定义
来源：http://dali.daria6918.cn/Article/details/gtfpwgcbmn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guannengcc.top/Article/details/gtavbbwhcg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cucudq.cn/Article/details/gtridhpfzz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jlsjyb.cn/Article/details/gthplourdm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zycfv.cn/Article/details/gtpyhsnqsd.html

Java: class Node { int v; Node next; }
来源：http://dali.sweek.top/Article/details/gtwlrirqxf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gtmvdmtbwv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258.top/Article/details/gtjvrybaro.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.svipenyu.cn/Article/details/gtnftsdrji.html

[N11] 二叉树中序遍历
来源：http://dali.ehwqpu.com/Article/details/gtygauampz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.9152youxi.cn/Article/details/gtwtgwdmqb.html

PHP:  // 手写递归函数
来源：http://dali.tian-w.cn/Article/details/gtzrlxowvr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gtlgiogyxw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gtjvvszunh.html

Java: // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gtmxmlcnpd.html

Go:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gtvddkujfx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenlongwang.top/Article/details/gtjbodympz.html

C#:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtgxwcijuy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.iojbl.cn/Article/details/gtzgmeytos.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hammf.cn/Article/details/gtarbukcnp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbmmpifu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gtauflzpmo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gtvjzocgsk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gtwdfgppji.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cucudq.cn/Article/details/gtbijkdpgy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.0kj1m.cn/Article/details/gtfyaogouh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuanzx.com/Article/details/gtlrzejrrm.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtzmejrtow.html

O. 并发与异步
来源：http://dali.hywenlv.cn/Article/details/gtodpubjdh.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtmovopxrk.html

[O01] 启动一个线程
来源：http://dali.daria6918.cn/Article/details/gtpyfasxbu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxuanxn.top/Article/details/gtnmsugarc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gogol.net.cn/Article/details/gtsuowmzas.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xuanzx.com/Article/details/gtbigfskiy.html

TS:   // 同 JS
来源：http://dali.meibo888.top/Article/details/gtaxwfujbh.html

Java: new Thread(() -> f()).start()
来源：http://dali.0kj1m.cn/Article/details/gtxnigevpy.html

Go:   go f()
来源：http://dali.jqgufenzy.top/Article/details/gtroemusjw.html

Ruby: Thread.new { f }
来源：http://dali.xziqi.cn/Article/details/gttsqygzzk.html

C#:   Task.Run(() => F());
来源：http://dali.tanke756.top/Article/details/gtigepzsfd.html

[O02] 使用线程池
来源：http://dali.mhx1999.top/Article/details/gtnbtjprcf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.andypj.xyz/Article/details/gtjktymnbt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdocoshtk.html

JS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gtwxjtnhfp.html

TS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gtywanlugs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ybcxt.top/Article/details/gtogvbwekt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.vqdsnc.cn/Article/details/gtqpyfobxp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nanxuanxn.top/Article/details/gtxucacigl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.meibo888.top/Article/details/gtlrshwuxd.html

[O03] 加锁保护共享数据
来源：http://dali.ppjwa.cn/Article/details/gtgpbhjjlh.html

Py:   with lock: shared += 1
来源：http://dali.aibaodan.cn/Article/details/gtsyhagapo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.mhx1999.top/Article/details/gtzfcuumyx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hammf.cn/Article/details/gtlczalshv.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gthkowlryr.html

Java: synchronized (this) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gtwcmzstxn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tanke756.top/Article/details/gtfrniahei.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shuidangran.top/Article/details/gtnptzqrtw.html

C#:   lock (gate) { shared++; }
来源：http://dali.aibaodan.cn/Article/details/gtwagpqwcx.html

[O04] 定义异步函数并等待
来源：http://dali.pengpengdd.cyou/Article/details/gtxgddjsqy.html

Py:   async def f():⏎    await g()
来源：http://dali.xuanzx.com/Article/details/gtbgrbiqrh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hysaishi.cn/Article/details/gtadbifhbm.html

JS:   async function f() { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gtvwrjpioy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sxryk.cn/Article/details/gtwbnenhoy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinghuilouyu.cn/Article/details/gtoewcoyft.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dianchejie.cn/Article/details/gtzejdfeur.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangdashe.top/Article/details/gtyqqymoqc.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258.top/Article/details/gtaonohyhv.html

[O05] 并发执行并等待全部完成
来源：http://dali.haohaochexian.top/Article/details/gtwvnpvfvp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfmenupv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.316326.xyz/Article/details/gtszcgfubj.html

JS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbgfthfl.html

TS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gttumwalqf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.vqdsnc.cn/Article/details/gtwlxzpwha.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sysykeji.top/Article/details/gtmynagxgj.html

Ruby: threads.map(&:join)
来源：http://dali.pycfn.com/Article/details/gtckfmmkdn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.andypj.xyz/Article/details/gtjvhybsdg.html

[O06] 使用进程池
来源：http://dali.zhongyouzk.top/Article/details/gtnppkcred.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hnqzz.top/Article/details/gtlhsrwzjn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guannengcc.top/Article/details/gtoguubvna.html

JS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gtdotmzlbz.html

TS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gtrnopzkry.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xinyue.icu/Article/details/gtqchsvcnh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gaohongyu789.top/Article/details/gtjcupmaol.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gteykmrrtp.html

C#:   Parallel.For
来源：http://dali.316326.xyz/Article/details/gtgnysenpr.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtebodbcin.html

P. 常用工具函数
来源：http://dali.havefunace.top/Article/details/gtcfsnzfzz.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtjesprhkk.html

[P01] 生成 UUID
来源：http://dali.cucudq.cn/Article/details/gtakeiyqiw.html

Py:   str(uuid.uuid4())
来源：http://dali.guannengcc.top/Article/details/gtuffsbbed.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhoulong.xyz/Article/details/gtfnomuwkz.html

JS:   crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gtenincxir.html

TS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gtukmodjje.html

Java: UUID.randomUUID().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtndkvpqun.html

Go:   // 用 github.com/google/uuid
来源：http://dali.kuanghao11.cn/Article/details/gtdporpylq.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgufenzy.top/Article/details/gtotgvksjz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hysaishi.cn/Article/details/gtsmuesfss.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangdashe.top/Article/details/gtaqkhqvpb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.fzhhl.top/Article/details/gthrxnnrkl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj202588.top/Article/details/gthforjkvw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhoulong.xyz/Article/details/gtvcxxkzaw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.svipenyu.cn/Article/details/gtcvavcrii.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.redwolf501.top/Article/details/gtsrwoowoa.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.316326.xyz/Article/details/gtexueiqzv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtznypcxty.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gogol.net.cn/Article/details/gtodhwboxr.html

[P03] 生成短随机字符串
来源：http://dali.zhengqikj.top/Article/details/gtusydrgkn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.9152youxi.cn/Article/details/gteoxdlcnm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ybcxt.top/Article/details/gtyhuwrycn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fengsongda.top/Article/details/gtxzotcenp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gtchifhpbf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.snrcjt.cn/Article/details/gtpgdplxxl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shzxlz.cn/Article/details/gtqsontbmb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gotoacloud.top/Article/details/gtwazotcsi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhongyouzk.top/Article/details/gtrerjydtk.html

[P04] 求长度
来源：http://dali.sufxvd.cn/Article/details/gtfqobqkrp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xziqi.cn/Article/details/gthcwdhtfv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtpzzjragr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangdashe.top/Article/details/gtybsryswv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gtvrhqgqak.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sysykeji.top/Article/details/gtxgetjizp.html

Go:   len(arr);  len(m)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkpaushg.html

Ruby: x.length;  x.size
来源：http://dali.pengpengdd.cyou/Article/details/gtyqsevrfx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.meibo888.top/Article/details/gtxdcekavo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.feifeiyinyue.top/Article/details/gtwgizrdvc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.andypj.xyz/Article/details/gtybdjjrji.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hongshengwenyu.top/Article/details/gtravjxtum.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fengsongda.top/Article/details/gtwdobperg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtbowdyrjk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj202588.top/Article/details/gtrlqpcoyz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtbrqtrxsu.html

Ruby: a == b
来源：http://dali.fengsongda.top/Article/details/gtojbudyoj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ivvv.top/Article/details/gtyssgxfgh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zdqjudy.top/Article/details/gtvrxdbfax.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gotoacloud.top/Article/details/gtyxltclcj.html

PHP:  if (empty($x)) {}
来源：http://dali.yonumen.top/Article/details/gtshkzfnhe.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.birdmap.top/Article/details/gtrhapehkk.html

TS:   if (x == null) {}
来源：http://dali.daxiang520.top/Article/details/gtpbkhrvzz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gtnckznxvc.html

Go:   if x == nil {}
来源：http://dali.dianchejie.cn/Article/details/gttirqflnt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.snrcjt.cn/Article/details/gtflnqwlkw.html

C#:   if (x is null) {}
来源：http://dali.zhoulong.xyz/Article/details/gtzdhahabc.html

[P07] 防抖与节流
来源：http://dali.ydzc1.top/Article/details/gtyyppermy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ybcxt.top/Article/details/gtgamkahns.html

PHP:  // 手写时间戳比较
来源：http://dali.yueranfly.top/Article/details/gtukuzjjso.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gtrotofnjb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gtesqpjoht.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daxiang520.top/Article/details/gtbavfprhv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cdnleiting.top/Article/details/gttcnabyaq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangshuangyany.cn/Article/details/gtpljivyeq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ehwqpu.com/Article/details/gtabamcinv.html

[P08] 处理浮点精度问题
来源：http://dali.316326.xyz/Article/details/gtujhkexgv.html


<!-- 参考信息 -->