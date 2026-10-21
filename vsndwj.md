代发 wailian999

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gtdrowdmfs.html

JS:   process.env.HOME
来源：http://dali.ydzc1.top/Article/details/gtgygpaozd.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqleezryv.html

Java: System.getenv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtrisnijpp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangdashe.top/Article/details/gtfzssysia.html

Ruby: ENV["HOME"]
来源：http://dali.hnxiangtu.top/Article/details/gtdyutpvdb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtcfbqarkb.html

[M03] 执行外部命令
来源：http://dali.gzhubu.top/Article/details/gtmuzutxrt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gzhubu.top/Article/details/gtlgzsxdns.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuxming.cn/Article/details/gtxqiozwvw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gtawpxhkcd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gtioiherbz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.quarkkingdee.top/Article/details/gthiwjymsq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gaohongyu789.top/Article/details/gtafacpjoc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hongshengwenyu.top/Article/details/gtuvwoidqz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yangfankeji.com/Article/details/gtgaeobfna.html

[M04] 获取当前工作目录
来源：http://dali.snrcjt.cn/Article/details/gtlefkhgod.html

Py:   os.getcwd()
来源：http://dali.aizwys.cn/Article/details/gtwhkobakq.html

PHP:  getcwd();
来源：http://dali.yongpay.top/Article/details/gtkjqpzqag.html

JS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gtayfcdwoy.html

TS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gtfejmqjbk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yanxiufei.cn/Article/details/gtswbzyhgd.html

Go:   os.Getwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqyydkuz.html

Ruby: Dir.pwd
来源：http://dali.zdqjudy.top/Article/details/gtthwlnhyt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dashuyun.cn/Article/details/gtdnxosucw.html

[M05] 设置退出码
来源：http://dali.hywenlv.cn/Article/details/gthcexpktx.html

Py:   sys.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtugejpnyc.html

PHP:  exit(1);
来源：http://dali.zhengqikj.top/Article/details/gtmvutrejc.html

JS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtwifmavsf.html

TS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtgqefhwha.html

Java: System.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtzgwsymhs.html

Go:   os.Exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtwfgrylgi.html

Ruby: exit 1
来源：http://dali.dianchejie.cn/Article/details/gtuzkmunfm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aizwys.cn/Article/details/gtuzsbeluq.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadvxfwif.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ehwqpu.com/Article/details/gtuukvqbrh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zdqjudy.top/Article/details/gtaewylanh.html

JS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gtqmxluptl.html

TS:   console.error("err")
来源：http://dali.jlsjyb.cn/Article/details/gtksgatnny.html

Java: System.err.println("err")
来源：http://dali.zhoulong.xyz/Article/details/gtidqfqxas.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.meibo888.top/Article/details/gthhmiyrqk.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gtlhxzpwog.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnqzz.top/Article/details/gtkumgadbz.html

[M07] 判断是否为主入口
来源：http://dali.nanxinkj.top/Article/details/gtvnoueggy.html

Py:   if __name__ == "__main__":
来源：http://dali.gogol.net.cn/Article/details/gtuplamvfx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhengqikj.top/Article/details/gtrcumwmoy.html

JS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gtiedtvzdi.html

TS:   require.main === module
来源：http://dali.snrcjt.cn/Article/details/gtitexazif.html

Java: public static void main(String[] args)
来源：http://dali.yongpay.top/Article/details/gtzhsfsddm.html

Go:   func main()
来源：http://dali.xinyue.icu/Article/details/gtnascjmlr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.smart0.xyz/Article/details/gtyaisbaye.html

C#:   static void Main(string[] args)
来源：http://dali.daxiang520.top/Article/details/gtofccjdyu.html

[M08] 获取系统与运行时信息
来源：http://dali.havefunace.top/Article/details/gtloanpnfw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zycfv.cn/Article/details/gtcbbpuqwq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258.top/Article/details/gtjorwwzao.html

JS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtexxxljvk.html

TS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gttquklfmu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sweek.top/Article/details/gttnsvpmqz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.mhx1999.top/Article/details/gtcapcahic.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tian-w.cn/Article/details/gturzlhusd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.snrcjt.cn/Article/details/gtlgunodrl.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtjjwaityh.html

N. 数据结构与算法
来源：http://dali.daria6918.cn/Article/details/gtkbhdqgjg.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtinhtzper.html

[N01] 二分查找（有序数组）
来源：http://dali.yuanzhike.top/Article/details/gtribxgalr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtotksuqiv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tanke756.top/Article/details/gtsrxczmbo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtzoijffov.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtbqynqxdg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtdnepswzz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwewsjkld.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hammf.cn/Article/details/gttgjjkqhu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqltqiqnu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jiagoushi.top/Article/details/gtkrjvuahj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gtjqpxauol.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhengqikj.top/Article/details/gtzihaloax.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtcxwdlizy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gtbuokjhmx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sweek.top/Article/details/gttniawerm.html

Go:   slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gtymadaqyw.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gtfqxakrjj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hammf.cn/Article/details/gtdqhmusne.html

[N03] 快速排序（分治示例）
来源：http://dali.shuidangran.top/Article/details/gtulirbpwg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuunqjshv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcrfgyzj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljrwwduf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zycfv.cn/Article/details/gtborwbtuj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fengsongda.top/Article/details/gtdbpwqjxt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.c1oappe.top/Article/details/gtevzwothb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zycfv.cn/Article/details/gtpaexjihe.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gzhubu.top/Article/details/gtnahyxtzw.html

[N04] 斐波那契数列
来源：http://dali.sysykeji.top/Article/details/gtkfrkvjfp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.iojbl.cn/Article/details/gtdypavyew.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daria6918.cn/Article/details/gtgzsnvbmb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtcmuqddbe.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtyfxdowel.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.guowangkeji.top/Article/details/gthdzciith.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hysaishi.cn/Article/details/gtqgsdfczi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gtialkusss.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtylbtcjfq.html

[N05] 最大公约数
来源：http://dali.guowangkeji.top/Article/details/gtktvyswbv.html

Py:   math.gcd(a, b)
来源：http://dali.0kj1m.cn/Article/details/gtudhfcsen.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yangfankeji.com/Article/details/gtbpxktiru.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pycfn.com/Article/details/gtlcfjrybv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gtdtpropgj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyckbkquj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jianghu66.top/Article/details/gtweqckdng.html

Ruby: a.gcd(b)
来源：http://dali.snrcjt.cn/Article/details/gtiwmoxyik.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.aizwys.cn/Article/details/gttvnyfywc.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjzzwbyn.html

Py:   s == s[::-1]
来源：http://dali.yonumen.top/Article/details/gtzptlqhbg.html

PHP:  $s === strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gtxntxbyqw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtewgsccri.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtignrllli.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guowangkeji.top/Article/details/gtslufqguw.html

Go:   // 双指针从两端比较
来源：http://dali.wangshuangyany.cn/Article/details/gtiqgdktvr.html

Ruby: s == s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtvqxiakgt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tianlin.xyz/Article/details/gtifworeza.html

[N07] 两数之和（返回下标）
来源：http://dali.xuanzx.com/Article/details/gtfguqybim.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnhetljt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhengqikj.top/Article/details/gtyyavjftf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.meibo888.top/Article/details/gtzpfijncb.html

TS:   // 手写 Map<string, number>
来源：http://dali.jyoumei.cn/Article/details/gtyofirxoy.html

Java: // 手写 HashMap
来源：http://dali.smart0.xyz/Article/details/gtjfucixcy.html

Go:   // 手写 map[int]int
来源：http://dali.cdnleiting.top/Article/details/gtdffbqemm.html

Ruby: // 手写 Hash
来源：http://dali.ehwqpu.com/Article/details/gtgrukzjkf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jlsjyb.cn/Article/details/gtzwiclgue.html

[N08] 生成全排列
来源：http://dali.yongpay.top/Article/details/gtcskcevty.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtmbeofsxc.html

PHP:  // 手写递归交换
来源：http://dali.fzhhl.top/Article/details/gtldzxlrqd.html

JS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtstinqfgp.html

TS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqolklxlr.html

Java: // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtftafbqga.html

Go:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtzvjslhbo.html

Ruby: arr.permutation.to_a
来源：http://dali.ehwqpu.com/Article/details/gtzbpmpykx.html

C#:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtuysuwddy.html

[N09] 栈与队列
来源：http://dali.gzhubu.top/Article/details/gtzpzbwvjk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.bjfxy.top/Article/details/gtzxybcumm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cheryme.top/Article/details/gtmjligzad.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gtsamzfczh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hongshengwenyu.top/Article/details/gtdprlgyor.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.iojbl.cn/Article/details/gtbqjqgidl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tian-w.cn/Article/details/gtxlouqhrs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gttydxjnlj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.0kj1m.cn/Article/details/gtlpeugpie.html

[N10] 链表节点定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdwxiiqd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenzaomai.com/Article/details/gtzrtxphfh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nwbrower.top/Article/details/gtrvmcqyly.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenlongwang.top/Article/details/gtljfvgbef.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dianchejie.cn/Article/details/gtcmdzkdlr.html

Java: class Node { int v; Node next; }
来源：http://dali.jyoumei.cn/Article/details/gtmncprqlw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daxiang520.top/Article/details/gtcbcomami.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xziqi.cn/Article/details/gtpwcebxsw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenlongwang.top/Article/details/gtttcmuune.html

[N11] 二叉树中序遍历
来源：http://dali.zdqjudy.top/Article/details/gtalwhkfkq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dianchejie.cn/Article/details/gtsdezptoz.html

PHP:  // 手写递归函数
来源：http://dali.0kj1m.cn/Article/details/gttiklqbhd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fengsongda.top/Article/details/gtvisfhugg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.haohaochexian.top/Article/details/gtmxsnohbw.html

Java: // 手写递归
来源：http://dali.ybcxt.top/Article/details/gtlkcfzazd.html

Go:   // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwrmqexnu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhiwuduotai.top/Article/details/gtytbdimdb.html

C#:   // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gtklvcxyys.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.mhx1999.top/Article/details/gtpefqegoe.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yonumen.top/Article/details/gtcwekgdhe.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.quarkkingdee.top/Article/details/gtsbpjhmuz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gtyxatjsez.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gtwyveyoeo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gtezguqpjr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.kuanghao11.cn/Article/details/gtfokliviw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xinyue.icu/Article/details/gtciahbmov.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gtlukfnnoc.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtfgwgdpeu.html

O. 并发与异步
来源：http://dali.zhengqikj.top/Article/details/gtpammqlgi.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtvhweqhtk.html

[O01] 启动一个线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxoryvrqx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinqigfzy.top/Article/details/gtepmeezcl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cdnleiting.top/Article/details/gtazfzgzss.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.birdmap.top/Article/details/gtuxvhvzel.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gtckimcvvh.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigufen.top/Article/details/gteszvloow.html

Go:   go f()
来源：http://dali.ydzc1.top/Article/details/gtjchfpace.html

Ruby: Thread.new { f }
来源：http://dali.316326.xyz/Article/details/gtwzdwspco.html

C#:   Task.Run(() => F());
来源：http://dali.chenjidiqi.icu/Article/details/gtgtktnhcg.html

[O02] 使用线程池
来源：http://dali.yvedp.cn/Article/details/gtslrdrwig.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ybcxt.top/Article/details/gtzjxkhxrw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258.top/Article/details/gtmugbjexy.html

JS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gtixobzoln.html

TS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gtnzpzblti.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhixingplan.top/Article/details/gtcfgesziw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.quarkkingdee.top/Article/details/gtdosutlvy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gzhubu.top/Article/details/gtiyigrfuw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yuanzhike.top/Article/details/gtllwmctsv.html

[O03] 加锁保护共享数据
来源：http://dali.jlsjyb.cn/Article/details/gtjgylfxoj.html

Py:   with lock: shared += 1
来源：http://dali.wangshuangyany.cn/Article/details/gtsfkgnlxt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhongyouzk.top/Article/details/gtoixvwwkp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cdnleiting.top/Article/details/gtafdlmxdu.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gtfnrmoqhc.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gtptcjmyop.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shuidangran.top/Article/details/gtcwgnsmek.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuanzhike.top/Article/details/gtaxqfxyiv.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258888.top/Article/details/gtjmanpqjd.html

[O04] 定义异步函数并等待
来源：http://dali.dianchejie.cn/Article/details/gtxfasbjax.html

Py:   async def f():⏎    await g()
来源：http://dali.iojbl.cn/Article/details/gtgdmapfgb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhixingplan.top/Article/details/gtbwpzhlyf.html

JS:   async function f() { await g(); }
来源：http://dali.havefunace.top/Article/details/gtiibwdqww.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigfzy.top/Article/details/gtepbthdck.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.quarkkingdee.top/Article/details/gtudsptcig.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigufen.top/Article/details/gteupizhjx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xylfe.cn/Article/details/gtjkvwyfei.html

C#:   async Task F() { await G(); }
来源：http://dali.sweek.top/Article/details/gthtxyvabb.html

[O05] 并发执行并等待全部完成
来源：http://dali.mhx1999.top/Article/details/gtyshaltuf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.birdmap.top/Article/details/gtidcrxwwg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinqigufen.top/Article/details/gtpgicoapt.html

JS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gtjpklyvjg.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gtflwdovhw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.iojbl.cn/Article/details/gtfokskniy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daxiang520.top/Article/details/gtcmfbwrgg.html

Ruby: threads.map(&:join)
来源：http://dali.9152youxi.cn/Article/details/gtmiwymrri.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gaohongyu789.top/Article/details/gtrynwzsyy.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gtlfhfqvwb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgufenzy.top/Article/details/gtfjtuvqmg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yonumen.top/Article/details/gtgugeqhtq.html

JS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfcnrvoh.html

TS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gtfoilszha.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shzxlz.cn/Article/details/gtjptvrwnh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258888.top/Article/details/gtilwlbdnv.html

Ruby: // fork 块
来源：http://dali.yanxiufei.cn/Article/details/gtxbubrmht.html

C#:   Parallel.For
来源：http://dali.cashguo.top/Article/details/gtafhgnmtp.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtwplncsub.html

P. 常用工具函数
来源：http://dali.xziqi.cn/Article/details/gtpsziksat.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdedkuqe.html

[P01] 生成 UUID
来源：http://dali.xziqi.cn/Article/details/gtesiuusmi.html

Py:   str(uuid.uuid4())
来源：http://dali.meibo888.top/Article/details/gtxymyqemo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yvedp.cn/Article/details/gtspvwjsnn.html

JS:   crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gtuhtnydfw.html

TS:   crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gtfutstmed.html

Java: UUID.randomUUID().toString()
来源：http://dali.cheryme.top/Article/details/gtmzuqfnio.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xylfe.cn/Article/details/gtauavjjca.html

Ruby: SecureRandom.uuid
来源：http://dali.hfpthk.cn/Article/details/gtsgrdzuyp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cucudq.cn/Article/details/gtcnlwptgl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tanke756.top/Article/details/gtmmqmjzwh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.vqdsnc.cn/Article/details/gtdhbytyic.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenzaomai.com/Article/details/gtwjzcdqlt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aibaodan.cn/Article/details/gtrphxfhiv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangdashe.top/Article/details/gtxzkiytvb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtmecryrdb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.snrcjt.cn/Article/details/gtiddyncdt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hnqzz.top/Article/details/gtlgaaqtow.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.snrcjt.cn/Article/details/gtzdrtbhdz.html

[P03] 生成短随机字符串
来源：http://dali.wangdashe.top/Article/details/gtozodzemz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.0kj1m.cn/Article/details/gttbulfxdp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xuetiantiany.cn/Article/details/gtqsunhhin.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.quarkkingdee.top/Article/details/gtekszuokj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.c1oappe.top/Article/details/gtoheupgyr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj20258888.top/Article/details/gtbapwpjhs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yvedp.cn/Article/details/gtyggzauiy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tanke756.top/Article/details/gttyjafmkw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258888.top/Article/details/gtmnwomhli.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gtvlbprwjn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hammf.cn/Article/details/gtwltkiqax.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtkeqrftwo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ivvv.top/Article/details/gtusuekmll.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtvgadislq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yonumen.top/Article/details/gtuftsukka.html

Go:   len(arr);  len(m)
来源：http://dali.svipenyu.cn/Article/details/gtdychaalb.html

Ruby: x.length;  x.size
来源：http://dali.ivvv.top/Article/details/gtihrtxqaq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fzhhl.top/Article/details/gtbqviwicb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xinyue.icu/Article/details/gtboswxmsz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gzhubu.top/Article/details/gtaqtzkstz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hywenlv.cn/Article/details/gtvpghvmbp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hammf.cn/Article/details/gtesnrodys.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gtkvppmbuw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aibaodan.cn/Article/details/gtovklsisx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yueranfly.top/Article/details/gtckhpzupm.html

Ruby: a == b
来源：http://dali.wangshuangyany.cn/Article/details/gtqvparlzk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sysykeji.top/Article/details/gtomytdloa.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.redwolf501.top/Article/details/gtprziamvq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhixingplan.top/Article/details/gtylygnfpe.html

PHP:  if (empty($x)) {}
来源：http://dali.ehwqpu.com/Article/details/gtkmuevchc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hfpthk.cn/Article/details/gtkvcumtwj.html

TS:   if (x == null) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtbzvexnvc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gtbwiqvxjq.html

Go:   if x == nil {}
来源：http://dali.sxryk.cn/Article/details/gthxzfkbfm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nwbrower.top/Article/details/gtnzntdlnf.html

C#:   if (x is null) {}
来源：http://dali.cheryme.top/Article/details/gtouvsajyv.html

[P07] 防抖与节流
来源：http://dali.zycfv.cn/Article/details/gtfcfymuht.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gzhubu.top/Article/details/gtomsegtus.html

PHP:  // 手写时间戳比较
来源：http://dali.snrcjt.cn/Article/details/gtoovdaorm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gtyfhqhofo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gtdpawabdz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigufen.top/Article/details/gtqbfelimm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.svipenyu.cn/Article/details/gthquhdxeu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj202588.top/Article/details/gtqmqgfeqk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sxryk.cn/Article/details/gtkekxcjcy.html

[P08] 处理浮点精度问题
来源：http://dali.zdqjudy.top/Article/details/gthaxulckl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cucudq.cn/Article/details/gtdaruskwh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fengsongda.top/Article/details/gteamzggna.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.kuanghao11.cn/Article/details/gtuvvroysf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xuanzx.com/Article/details/gtcfdbwvoo.html


<!-- 参考信息 -->