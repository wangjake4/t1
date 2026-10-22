代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtcniwygfv.html

[M01] 读取命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtosumrikl.html

Py:   sys.argv[1:]
来源：http://dali.hnqzz.top/Article/details/gtibbirhbv.html

PHP:  $argv;  $argc;
来源：http://dali.fzhhl.top/Article/details/gtvhubgnre.html

JS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gtnnosftua.html

TS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gthgduakbd.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gtiauybhpy.html

Go:   os.Args[1:]
来源：http://dali.hammf.cn/Article/details/gtlhqqhmfj.html

Ruby: ARGV
来源：http://dali.zhengqikj.top/Article/details/gtohjxrkuz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gtqpkphtvc.html

[M02] 读取环境变量
来源：http://dali.gotoacloud.top/Article/details/gtbnsamimh.html

Py:   os.environ.get("HOME")
来源：http://dali.pycfn.com/Article/details/gtxnoygweu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gtzatcelrk.html

JS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gtyxxdffow.html

TS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gtquqbvvwa.html

Java: System.getenv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtvdeobdsq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtieimvkij.html

Ruby: ENV["HOME"]
来源：http://dali.tianlin.xyz/Article/details/gtsmesaitq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jyoumei.cn/Article/details/gthfdintvs.html

[M03] 执行外部命令
来源：http://dali.shuidangran.top/Article/details/gtsosxmtep.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnxiangtu.top/Article/details/gtxsrjbhaz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.iojbl.cn/Article/details/gteqwncwby.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gtjrkcizcn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtqxzlirfw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cdnleiting.top/Article/details/gtxhkjgbiv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgufenzy.top/Article/details/gtlanoikvt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258888.top/Article/details/gtfvshcaba.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj202588.top/Article/details/gtcazfyoex.html

[M04] 获取当前工作目录
来源：http://dali.vqdsnc.cn/Article/details/gtqsuwmftw.html

Py:   os.getcwd()
来源：http://dali.aizwys.cn/Article/details/gtojlmtokm.html

PHP:  getcwd();
来源：http://dali.cqqwz.cn/Article/details/gtzmmwciyd.html

JS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gtzxnxchud.html

TS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gtwutftvwa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcvukdym.html

Go:   os.Getwd()
来源：http://dali.sufxvd.cn/Article/details/gtynozlfco.html

Ruby: Dir.pwd
来源：http://dali.jinqigfzy.top/Article/details/gtsykfkuvs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tanke756.top/Article/details/gtdggerqdt.html

[M05] 设置退出码
来源：http://dali.kuanghao11.cn/Article/details/gtbqmyypdx.html

Py:   sys.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtvkcugckk.html

PHP:  exit(1);
来源：http://dali.xuetiantiany.cn/Article/details/gtmowtigzu.html

JS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gtuiriajsn.html

TS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtbnlspuzl.html

Java: System.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtundvbtuo.html

Go:   os.Exit(1)
来源：http://dali.redwolf501.top/Article/details/gthbmkblfr.html

Ruby: exit 1
来源：http://dali.guannengcc.top/Article/details/gtccfmoxfu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tanke756.top/Article/details/gtyeoimmcm.html

[M06] 向标准错误输出
来源：http://dali.zhongyouzk.top/Article/details/gtpqygjfjq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gtmgkafvot.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fengsongda.top/Article/details/gtgklctbyg.html

JS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gtbbbzxomt.html

TS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gtefmedojt.html

Java: System.err.println("err")
来源：http://dali.haohaochexian.top/Article/details/gtkoftrcbt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnqzz.top/Article/details/gtfwuofyqd.html

Ruby: warn "err"
来源：http://dali.shanyushiyangkeji.top/Article/details/gteagvwhwc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenzaomai.com/Article/details/gtnpnzbgbs.html

[M07] 判断是否为主入口
来源：http://dali.xziqi.cn/Article/details/gtmdgalgzo.html

Py:   if __name__ == "__main__":
来源：http://dali.tian-w.cn/Article/details/gtkcqvjbcz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigufen.top/Article/details/gtcqfjojfi.html

JS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gtvxnpnruu.html

TS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gtfakghauo.html

Java: public static void main(String[] args)
来源：http://dali.xylfe.cn/Article/details/gtulrhnqwm.html

Go:   func main()
来源：http://dali.smart0.xyz/Article/details/gtyggrvcvy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.birdmap.top/Article/details/gtpodinkus.html

C#:   static void Main(string[] args)
来源：http://dali.tian-w.cn/Article/details/gtdjzrtgos.html

[M08] 获取系统与运行时信息
来源：http://dali.xinyue.icu/Article/details/gtuextxqec.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pengpengdd.cyou/Article/details/gtyvkayyng.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daria6918.cn/Article/details/gthldjdozb.html

JS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gtjfbnggjy.html

TS:   process.platform;  process.version
来源：http://dali.haohaochexian.top/Article/details/gtdlcxtajn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jianghu66.top/Article/details/gtokwxqugh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shuidangran.top/Article/details/gtxrqsgstg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cucudq.cn/Article/details/gtdbyrmczo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xziqi.cn/Article/details/gtekpyvwnv.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtkyohcics.html

N. 数据结构与算法
来源：http://dali.316326.xyz/Article/details/gtxfbvukch.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtkybaglak.html

[N01] 二分查找（有序数组）
来源：http://dali.0kj1m.cn/Article/details/gtfydygnum.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtyztxojlp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.birdmap.top/Article/details/gtxyqmkfnr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gtzqldgntn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gtcrpglwnn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtproittnu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtjuddjsfl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj202588.top/Article/details/gtefuqacxg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.meibo888.top/Article/details/gtbpedzvpk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jiagoushi.top/Article/details/gtxsfbqyun.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gtuvkxzbqs.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zycfv.cn/Article/details/gtmzocgthr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnhimpwk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gtqvsfhzaa.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hongshengwenyu.top/Article/details/gtezmmryqh.html

Go:   slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gtmegvswzu.html

Ruby: arr.sort
来源：http://dali.hfpthk.cn/Article/details/gtkjzuedxn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.mhx1999.top/Article/details/gtfpafjtfo.html

[N03] 快速排序（分治示例）
来源：http://dali.zycfv.cn/Article/details/gtdsuytvfc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aibaodan.cn/Article/details/gtrgeokmzu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.9152youxi.cn/Article/details/gtxptqndqx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gtzfvmchvu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gtkhtizfcf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.quarkkingdee.top/Article/details/gtsgwuvbjh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hywenlv.cn/Article/details/gtgbkwoifi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.feifeiyinyue.top/Article/details/gtpxukgiys.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daxiang520.top/Article/details/gtfhfxfhdp.html

[N04] 斐波那契数列
来源：http://dali.ivvv.top/Article/details/gttmgkwgmg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gtkpskpdko.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gtkjnybidh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gtynoazpet.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gtzidfnyda.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ivvv.top/Article/details/gtxshpgzct.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmsbnrjst.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gtiwdiufoy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gtwxfoioid.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gtllzwgcjy.html

Py:   math.gcd(a, b)
来源：http://dali.daria6918.cn/Article/details/gtmxlwuiml.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtptrrbdds.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gtxuyftaqz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtisgkssmp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.redwolf501.top/Article/details/gtpytyntmm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.smart0.xyz/Article/details/gtvvragkiv.html

Ruby: a.gcd(b)
来源：http://dali.0kj1m.cn/Article/details/gtlljrfacs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.feifeiyinyue.top/Article/details/gtzjgqltkw.html

[N06] 判断回文字符串
来源：http://dali.gzhubu.top/Article/details/gthhxryeul.html

Py:   s == s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gtdvwidfjm.html

PHP:  $s === strrev($s);
来源：http://dali.tanke756.top/Article/details/gtarolhcno.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtsiuraerc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtehsnuhsk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.feifeiyinyue.top/Article/details/gtkoyoiidp.html

Go:   // 双指针从两端比较
来源：http://dali.yvedp.cn/Article/details/gtwgecifhj.html

Ruby: s == s.reverse
来源：http://dali.quarkkingdee.top/Article/details/gthkilpolb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yueranfly.top/Article/details/gtiftlqhgo.html

[N07] 两数之和（返回下标）
来源：http://dali.zycfv.cn/Article/details/gtqmnxogta.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guowangkeji.top/Article/details/gtcmukedjf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhiwuduotai.top/Article/details/gtvfciyufj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jianghu66.top/Article/details/gtifjvpmiv.html

TS:   // 手写 Map<string, number>
来源：http://dali.jlsjyb.cn/Article/details/gtihlqwglq.html

Java: // 手写 HashMap
来源：http://dali.xuetiantiany.cn/Article/details/gtgnsgxgft.html

Go:   // 手写 map[int]int
来源：http://dali.yj202588.top/Article/details/gthnzttxth.html

Ruby: // 手写 Hash
来源：http://dali.shangyingyoupin.top/Article/details/gtnmpjoacn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hongshengwenyu.top/Article/details/gtnrrwviox.html

[N08] 生成全排列
来源：http://dali.shzxlz.cn/Article/details/gtqhanghal.html

Py:   itertools.permutations(arr)
来源：http://dali.pycfn.com/Article/details/gtbaguueba.html

PHP:  // 手写递归交换
来源：http://dali.hysaishi.cn/Article/details/gtsownsjgl.html

JS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtmfsgroxw.html

TS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtadwijeuw.html

Java: // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndeenzif.html

Go:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtjoodeixc.html

Ruby: arr.permutation.to_a
来源：http://dali.kuanghao11.cn/Article/details/gtmtccrvgi.html

C#:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtiqmgkbip.html

[N09] 栈与队列
来源：http://dali.daria6918.cn/Article/details/gttpdjuclx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtygwfhzjn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hammf.cn/Article/details/gtxihfbdfe.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gtbxtizeqr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cdnleiting.top/Article/details/gtjgynlizb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gtjaztyemp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkcbclkc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtefvsoylc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdwnvpbi.html

[N10] 链表节点定义
来源：http://dali.aibaodan.cn/Article/details/gtnfuvljww.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigufen.top/Article/details/gteeaigptc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgufenzy.top/Article/details/gtbeytfwhr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yonumen.top/Article/details/gtknrvgcpo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yvedp.cn/Article/details/gtlqvwtgji.html

Java: class Node { int v; Node next; }
来源：http://dali.jlsjyb.cn/Article/details/gtnwoymikb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jlsjyb.cn/Article/details/gtaepqwsjc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xuetiantiany.cn/Article/details/gtygnjeoxw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnqzz.top/Article/details/gtihumyeig.html

[N11] 二叉树中序遍历
来源：http://dali.chenlongwang.top/Article/details/gtvcoqqazf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhongyouzk.top/Article/details/gtqfojljfy.html

PHP:  // 手写递归函数
来源：http://dali.ivvv.top/Article/details/gtfetmhbwy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gtleknnpmf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuanzx.com/Article/details/gtszajviez.html

Java: // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtygrsaocc.html

Go:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtuefxmafw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.9152youxi.cn/Article/details/gtrkjwjqxx.html

C#:   // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gtktmiudcj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sufxvd.cn/Article/details/gthmcubldj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shangyingyoupin.top/Article/details/gtymfydauz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cashguo.top/Article/details/gtouipvsav.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gtrwbctxuk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gticqcjcez.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gtijtlztkj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigufen.top/Article/details/gtzipssjkp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtmpceeelb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ydzc1.top/Article/details/gtpyfxoura.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtzpnqupxt.html

O. 并发与异步
来源：http://dali.nwbrower.top/Article/details/gtnbaahqdr.html

================================================================================
来源：http://dali.sweek.top/Article/details/gttfhjwodm.html

[O01] 启动一个线程
来源：http://dali.zhongyouzk.top/Article/details/gtuvcttdiy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.haohaochexian.top/Article/details/gtovxsrdbb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yangfankeji.com/Article/details/gtbulabiuc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.kuanghao11.cn/Article/details/gtkerinack.html

TS:   // 同 JS
来源：http://dali.ppjwa.cn/Article/details/gtpeoksmcw.html

Java: new Thread(() -> f()).start()
来源：http://dali.andypj.xyz/Article/details/gtrtvrewmm.html

Go:   go f()
来源：http://dali.xuetiantiany.cn/Article/details/gtybnrkeyx.html

Ruby: Thread.new { f }
来源：http://dali.birdmap.top/Article/details/gtjbsfqvam.html

C#:   Task.Run(() => F());
来源：http://dali.mhx1999.top/Article/details/gtijjauvou.html

[O02] 使用线程池
来源：http://dali.aibaodan.cn/Article/details/gtbjejzylk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.c1oappe.top/Article/details/gtjltbivmm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.bjfxy.top/Article/details/gtmetgtwqj.html

JS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gtapfqtsvt.html

TS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gtynmpjgev.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhongyouzk.top/Article/details/gtouwmhbgh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.smart0.xyz/Article/details/gtjjuomaky.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenjidiqi.icu/Article/details/gtvljtzaud.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgfzy.top/Article/details/gtbhzqwgip.html

[O03] 加锁保护共享数据
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmwkqrbr.html

Py:   with lock: shared += 1
来源：http://dali.pengpengdd.cyou/Article/details/gtdtefykzb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.vqdsnc.cn/Article/details/gtaekoqpii.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pengpengdd.cyou/Article/details/gtdwthisvp.html

TS:   // 同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdrfbpda.html

Java: synchronized (this) { shared++; }
来源：http://dali.dashuyun.cn/Article/details/gtvenfkmph.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.guannengcc.top/Article/details/gtcocjbkzc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ydzc1.top/Article/details/gtqyrobyaf.html

C#:   lock (gate) { shared++; }
来源：http://dali.hammf.cn/Article/details/gtyfvfracc.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigufen.top/Article/details/gtkbsectxa.html

Py:   async def f():⏎    await g()
来源：http://dali.zycfv.cn/Article/details/gtxmmqnljx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.iojbl.cn/Article/details/gtteigsepe.html

JS:   async function f() { await g(); }
来源：http://dali.quarkkingdee.top/Article/details/gtjsqhbvnj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj202588.top/Article/details/gtahtqhkqf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yanxiufei.cn/Article/details/gtlxvqdllw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dashuyun.cn/Article/details/gtshnrjcaq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.c1oappe.top/Article/details/gtwvvwgnhl.html

C#:   async Task F() { await G(); }
来源：http://dali.hywenlv.cn/Article/details/gtwylvlsyb.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgfzy.top/Article/details/gtulnsrljj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gtypooicpa.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yongpay.top/Article/details/gtugzquenn.html

JS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gtlhxcjmmp.html

TS:   await Promise.all(tasks)
来源：http://dali.yvedp.cn/Article/details/gtmunpfcwx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ybcxt.top/Article/details/gttqritujp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dianchejie.cn/Article/details/gtpamnskvg.html

Ruby: threads.map(&:join)
来源：http://dali.ehwqpu.com/Article/details/gtrgidkuxa.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuetiantiany.cn/Article/details/gtzfyjykbp.html

[O06] 使用进程池
来源：http://dali.jianghu66.top/Article/details/gtivyaoish.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hnxiangtu.top/Article/details/gtyontyrxe.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tian-w.cn/Article/details/gtsgfaazhz.html

JS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gtejtyncrd.html

TS:   // child_process / cluster 模块
来源：http://dali.redwolf501.top/Article/details/gthxtmqxqw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.guowangkeji.top/Article/details/gtoqawroaf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.daria6918.cn/Article/details/gtcmuhojbu.html

Ruby: // fork 块
来源：http://dali.guowangkeji.top/Article/details/gtmbrjngea.html

C#:   Parallel.For
来源：http://dali.haohaochexian.top/Article/details/gtekrnrfpr.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtsyepurji.html

P. 常用工具函数
来源：http://dali.0kj1m.cn/Article/details/gtnsptweap.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtnynesxnt.html

[P01] 生成 UUID
来源：http://dali.cheryme.top/Article/details/gtjamknhrk.html

Py:   str(uuid.uuid4())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyogverdg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangdashe.top/Article/details/gtediswgpz.html

JS:   crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gtwiubfkoo.html

TS:   crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gtjxjzteba.html

Java: UUID.randomUUID().toString()
来源：http://dali.dianchejie.cn/Article/details/gtnirpgrhm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ppjwa.cn/Article/details/gtyusyyeez.html

Ruby: SecureRandom.uuid
来源：http://dali.ydzc1.top/Article/details/gtgvaavtdz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hongshengwenyu.top/Article/details/gtjzwwmbsh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sweek.top/Article/details/gtjdflhszk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xinyue.icu/Article/details/gtxwqqhpke.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnqzz.top/Article/details/gtpsihsqxa.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.9152youxi.cn/Article/details/gtonylwgyt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.smart0.xyz/Article/details/gtsvypeqxq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zdqjudy.top/Article/details/gtdddosolv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgfzy.top/Article/details/gtflveorcb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.daxiang520.top/Article/details/gtmptvingt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuanzx.com/Article/details/gtpbkajudj.html

[P03] 生成短随机字符串
来源：http://dali.zycfv.cn/Article/details/gtujeamxso.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.quarkkingdee.top/Article/details/gtysocwfrq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yanxiufei.cn/Article/details/gtuicyefaw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gtwdgxplzy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtcbiviurx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gaohongyu789.top/Article/details/gtznmiwwyr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ivvv.top/Article/details/gtugaixzbk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugekjmay.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xuanzx.com/Article/details/gtclmwhkld.html

[P04] 求长度
来源：http://dali.316326.xyz/Article/details/gtqvidxmgr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cheryme.top/Article/details/gtvslsbhqt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtsgieyomb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hongshengwenyu.top/Article/details/gtqhvzhriy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gtcawuwoqj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yangfankeji.com/Article/details/gtiaodcglx.html

Go:   len(arr);  len(m)
来源：http://dali.mhx1999.top/Article/details/gtbekfgour.html

Ruby: x.length;  x.size
来源：http://dali.wangshuangyany.cn/Article/details/gtzzpkmxrv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcyrrbccw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhengqikj.top/Article/details/gtnjtptmsp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenjidiqi.icu/Article/details/gtddfdxzkn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.havefunace.top/Article/details/gtxvcasctj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tanke756.top/Article/details/gttoyglufz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtriocvkaf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.birdmap.top/Article/details/gtdqduqrry.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ybcxt.top/Article/details/gtzykpuutr.html

Ruby: a == b
来源：http://dali.xylfe.cn/Article/details/gtstuqyprf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xziqi.cn/Article/details/gtdkcchrhv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxjnzuoh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jianghu66.top/Article/details/gtoefpofax.html

PHP:  if (empty($x)) {}
来源：http://dali.pycfn.com/Article/details/gtckvorfhv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ppjwa.cn/Article/details/gtxhhwhqav.html

TS:   if (x == null) {}
来源：http://dali.hfpthk.cn/Article/details/gtjfperbrb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslhrktom.html

Go:   if x == nil {}
来源：http://dali.fengsongda.top/Article/details/gtxjiakgrj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xuetiantiany.cn/Article/details/gtalepfsxa.html

C#:   if (x is null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimaevdhn.html

[P07] 防抖与节流
来源：http://dali.sxryk.cn/Article/details/gtmndcqhzk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jlsjyb.cn/Article/details/gtyblottal.html


<!-- 参考信息 -->