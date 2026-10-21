代发 wailian999

JS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gtwfndjgnf.html

TS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gtajaaeycc.html

Java: args 数组（main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gtukmazswz.html

Go:   os.Args[1:]
来源：http://dali.fzhhl.top/Article/details/gtriovubyc.html

Ruby: ARGV
来源：http://dali.yueranfly.top/Article/details/gtgftymfec.html

C#:   args 数组（Main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gtuhgvaaeg.html

[M02] 读取环境变量
来源：http://dali.svipenyu.cn/Article/details/gtoskfvefq.html

Py:   os.environ.get("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtsbwxysqr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gtstrchedw.html

JS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gtypebuanc.html

TS:   process.env.HOME
来源：http://dali.nwbrower.top/Article/details/gttgjlpxsc.html

Java: System.getenv("HOME")
来源：http://dali.daria6918.cn/Article/details/gtbqgymwfs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnzjutwbt.html

Ruby: ENV["HOME"]
来源：http://dali.yanxiufei.cn/Article/details/gtveiqidcm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtwimedjfh.html

[M03] 执行外部命令
来源：http://dali.gotoacloud.top/Article/details/gtgfldmapi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtjiblehzb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.c1oappe.top/Article/details/gtsclyerrh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gtszfigykq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtzuztyhmh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hywenlv.cn/Article/details/gtoqytypfg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.birdmap.top/Article/details/gtnjgctgtp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.9152youxi.cn/Article/details/gtbrqzyguz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yanxiufei.cn/Article/details/gtkzuhdasx.html

[M04] 获取当前工作目录
来源：http://dali.ehwqpu.com/Article/details/gtgipkawgm.html

Py:   os.getcwd()
来源：http://dali.chenzaomai.com/Article/details/gttgtrheif.html

PHP:  getcwd();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumbasvff.html

JS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtcbjllzei.html

TS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gtiqdaekpt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258.top/Article/details/gtvyursksr.html

Go:   os.Getwd()
来源：http://dali.gzhubu.top/Article/details/gtahjsqywb.html

Ruby: Dir.pwd
来源：http://dali.chenzaomai.com/Article/details/gtuxjbsmvd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daxiang520.top/Article/details/gtvwjzjyvd.html

[M05] 设置退出码
来源：http://dali.fengsongda.top/Article/details/gthxxcyqql.html

Py:   sys.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdgkiizt.html

PHP:  exit(1);
来源：http://dali.xuanzx.com/Article/details/gtgbnscfyf.html

JS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtdtbdbwrm.html

TS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtwuwxgzet.html

Java: System.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpzzhsuwk.html

Go:   os.Exit(1)
来源：http://dali.tanke756.top/Article/details/gtwzhtbrek.html

Ruby: exit 1
来源：http://dali.zhoulong.xyz/Article/details/gtbpuxerjv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.snrcjt.cn/Article/details/gtcuiodosu.html

[M06] 向标准错误输出
来源：http://dali.zycfv.cn/Article/details/gtqysdoeih.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj202588.top/Article/details/gticykjygf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj202588.top/Article/details/gtcllteclw.html

JS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gtaafneiab.html

TS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gtphashyvq.html

Java: System.err.println("err")
来源：http://dali.9152youxi.cn/Article/details/gthpdynefm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.haohaochexian.top/Article/details/gtbeucjqrv.html

Ruby: warn "err"
来源：http://dali.cheryme.top/Article/details/gtxdsygbdg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.316326.xyz/Article/details/gtbxpytchk.html

[M07] 判断是否为主入口
来源：http://dali.daria6918.cn/Article/details/gtrxwbmjak.html

Py:   if __name__ == "__main__":
来源：http://dali.kuanghao11.cn/Article/details/gtysvecjvp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtskdamoci.html

JS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gtlsxhaqxa.html

TS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gtvzhlhlzu.html

Java: public static void main(String[] args)
来源：http://dali.zhoulong.xyz/Article/details/gtazvtpzij.html

Go:   func main()
来源：http://dali.jqgfzy.top/Article/details/gtabylmmvw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yonumen.top/Article/details/gtpztqcokg.html

C#:   static void Main(string[] args)
来源：http://dali.sysykeji.top/Article/details/gtddkpiynb.html

[M08] 获取系统与运行时信息
来源：http://dali.redwolf501.top/Article/details/gtejvxnqwh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daxiang520.top/Article/details/gteaidyyjz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhiwuduotai.top/Article/details/gtahpnayae.html

JS:   process.platform;  process.version
来源：http://dali.yj20258.top/Article/details/gttibgpqkw.html

TS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gtpjshpxxs.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dashuyun.cn/Article/details/gtcxoovjnz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guannengcc.top/Article/details/gtbbsjoypp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gotoacloud.top/Article/details/gtoqvtutxr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnxiangtu.top/Article/details/gtjzgoiitx.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtfwhorcqn.html

N. 数据结构与算法
来源：http://dali.316326.xyz/Article/details/gtajbhponn.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtwfdckgdk.html

[N01] 二分查找（有序数组）
来源：http://dali.xinyue.icu/Article/details/gtydlxouei.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtutlzlkfj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gtzwcbkdgl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gtmbauvhxb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtizizfjrf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gtysfatork.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtloduuwmc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.mhx1999.top/Article/details/gtdouhdton.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gtlfbagorx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ehwqpu.com/Article/details/gtfmylziec.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gtqemmrccg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gtutlwbtze.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtulzgfsvt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgfzy.top/Article/details/gtrvgehdug.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zdqjudy.top/Article/details/gtmpxihpdg.html

Go:   slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gtmapvhjmz.html

Ruby: arr.sort
来源：http://dali.chenzaomai.com/Article/details/gtoioxpzao.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hammf.cn/Article/details/gtstyodeqo.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gtjnspcphm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.havefunace.top/Article/details/gtybrshido.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhixingplan.top/Article/details/gtnkulmmxo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gtnefgwprg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gtyeyerffq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtbfzbchut.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgfzy.top/Article/details/gtldpjjldm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shuidangran.top/Article/details/gtxjbwogfy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxuanxn.top/Article/details/gtfmxygwis.html

[N04] 斐波那契数列
来源：http://dali.shangyingyoupin.top/Article/details/gtvjxevkjt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gtzajfznwy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hysaishi.cn/Article/details/gtqsrvbnyx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtcgxymwqf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtwehigiru.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gtqxsacyoo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hfpthk.cn/Article/details/gtawqdyxnr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtijfpwbtn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtzwrzfqah.html

[N05] 最大公约数
来源：http://dali.kuanghao11.cn/Article/details/gtazghtqyb.html

Py:   math.gcd(a, b)
来源：http://dali.fengsongda.top/Article/details/gtrmsbeixc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenzaomai.com/Article/details/gtvckqmfvb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gthedbdldg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtlhoidqge.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhixingplan.top/Article/details/gthhtmpwut.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.mhx1999.top/Article/details/gtllmqdarb.html

Ruby: a.gcd(b)
来源：http://dali.c1oappe.top/Article/details/gtreadfnpz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yonumen.top/Article/details/gtptufgorl.html

[N06] 判断回文字符串
来源：http://dali.xylfe.cn/Article/details/gtfzcyiapy.html

Py:   s == s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gtokfcujmo.html

PHP:  $s === strrev($s);
来源：http://dali.aibaodan.cn/Article/details/gtidcmwehw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtruuoagie.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtlnajqjnr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hfpthk.cn/Article/details/gtvlbzttzh.html

Go:   // 双指针从两端比较
来源：http://dali.ehwqpu.com/Article/details/gtjybfuxve.html

Ruby: s == s.reverse
来源：http://dali.xuanzx.com/Article/details/gtqvcqsfja.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gtccfhbush.html

[N07] 两数之和（返回下标）
来源：http://dali.yangfankeji.com/Article/details/gtypylhmvd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jianghu66.top/Article/details/gtkjpxofmi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinghuilouyu.cn/Article/details/gttrruijum.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhengqikj.top/Article/details/gthxddwibz.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhengqikj.top/Article/details/gtfdilsuak.html

Java: // 手写 HashMap
来源：http://dali.jqgufenzy.top/Article/details/gtbfgtbhjb.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrllsisk.html

Ruby: // 手写 Hash
来源：http://dali.jianghu66.top/Article/details/gtdhhbyokl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj20258.top/Article/details/gtsddyozow.html

[N08] 生成全排列
来源：http://dali.gzhubu.top/Article/details/gteuhitdlo.html

Py:   itertools.permutations(arr)
来源：http://dali.c1oappe.top/Article/details/gtxcslhweq.html

PHP:  // 手写递归交换
来源：http://dali.kuanghao11.cn/Article/details/gtaoxevhew.html

JS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtsnpuxunk.html

TS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtkiwrgwrr.html

Java: // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtyroqolqy.html

Go:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtymfafgsi.html

Ruby: arr.permutation.to_a
来源：http://dali.cashguo.top/Article/details/gtregvyqub.html

C#:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtifsgsayw.html

[N09] 栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqudifxn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daxiang520.top/Article/details/gtnayfuyew.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtnibyehka.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtpygxqueh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yanxiufei.cn/Article/details/gtpzzngruj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ivvv.top/Article/details/gtdqvepbyf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.dashuyun.cn/Article/details/gtrizpkere.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.birdmap.top/Article/details/gtkrpzihnp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ppjwa.cn/Article/details/gtfwsmgyco.html

[N10] 链表节点定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtenfndgnc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zdqjudy.top/Article/details/gtjutsvtjy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.iojbl.cn/Article/details/gtojfsurnw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.andypj.xyz/Article/details/gtjorjwcur.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gaohongyu789.top/Article/details/gtgvkfuxgf.html

Java: class Node { int v; Node next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhvmevic.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jianghu66.top/Article/details/gticiqumfo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.vqdsnc.cn/Article/details/gtxsyvaslv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqmxwrfxd.html

[N11] 二叉树中序遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtusxsxybe.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhixingplan.top/Article/details/gtjpyrsrad.html

PHP:  // 手写递归函数
来源：http://dali.gzhubu.top/Article/details/gthwzyudjf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.bjfxy.top/Article/details/gtnwngszzj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gtbfrgepma.html

Java: // 手写递归
来源：http://dali.tian-w.cn/Article/details/gtdlshdcou.html

Go:   // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gtlpkjwowi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jyoumei.cn/Article/details/gtelxlcgua.html

C#:   // 手写递归
来源：http://dali.smart0.xyz/Article/details/gtsomkfjwx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jianghu66.top/Article/details/gtuukdknyt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daria6918.cn/Article/details/gtdmcedmyw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenzaomai.com/Article/details/gtabhcspkg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gtrwrgqrbt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gtsbhijlfu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gtspgrceuj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ydzc1.top/Article/details/gtixumrwqu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daxiang520.top/Article/details/gtojzupnwd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gtvjpbpxgj.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtmdshadkt.html

O. 并发与异步
来源：http://dali.cdnleiting.top/Article/details/gtzowoixxa.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtuddorutl.html

[O01] 启动一个线程
来源：http://dali.yuanzhike.top/Article/details/gtrgiuhfgj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yongpay.top/Article/details/gtvypeohrh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.quarkkingdee.top/Article/details/gtxgmhhnzv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenlongwang.top/Article/details/gtakthfexr.html

TS:   // 同 JS
来源：http://dali.chenzaomai.com/Article/details/gttylzyddo.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnqzz.top/Article/details/gtnyykbhql.html

Go:   go f()
来源：http://dali.yj202588.top/Article/details/gtykshjtnv.html

Ruby: Thread.new { f }
来源：http://dali.chenlongwang.top/Article/details/gtqceugrzr.html

C#:   Task.Run(() => F());
来源：http://dali.daxiang520.top/Article/details/gthmhkypcl.html

[O02] 使用线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxdkrlso.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.c1oappe.top/Article/details/gthewuuuvx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cqqwz.cn/Article/details/gtzoqmoiaz.html

JS:   // worker_threads 线程池
来源：http://dali.hysaishi.cn/Article/details/gttejbcbwa.html

TS:   // worker_threads 线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmodnfdd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrstuyxr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.mhx1999.top/Article/details/gtzggaxfje.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenlongwang.top/Article/details/gtclyzdxcs.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cucudq.cn/Article/details/gtggelylgn.html

[O03] 加锁保护共享数据
来源：http://dali.cqqwz.cn/Article/details/gtdvvgshqj.html

Py:   with lock: shared += 1
来源：http://dali.sxryk.cn/Article/details/gtcxmxhfeq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xylfe.cn/Article/details/gtghvwxtql.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj20258888.top/Article/details/gtvnpkiljp.html

TS:   // 同 JS
来源：http://dali.ehwqpu.com/Article/details/gtbgxloddt.html

Java: synchronized (this) { shared++; }
来源：http://dali.birdmap.top/Article/details/gtrkzjcild.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ivvv.top/Article/details/gtxeocalcm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tian-w.cn/Article/details/gtpqvtkvly.html

C#:   lock (gate) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gtkqyrfbou.html

[O04] 定义异步函数并等待
来源：http://dali.jqgufenzy.top/Article/details/gttqmtoupy.html

Py:   async def f():⏎    await g()
来源：http://dali.yj20258888.top/Article/details/gtnakkgdne.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yongpay.top/Article/details/gtpoprcqus.html

JS:   async function f() { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gtrzxdaxng.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtwqwsenjm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.0kj1m.cn/Article/details/gtgetgqelg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.mhx1999.top/Article/details/gtuhujjjyc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jiagoushi.top/Article/details/gtxhmvqjwp.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gtkltdkrvb.html

[O05] 并发执行并等待全部完成
来源：http://dali.yueranfly.top/Article/details/gtnybbvgym.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yuanzhike.top/Article/details/gtwhnfkmvg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuanzx.com/Article/details/gtzkbyrrab.html

JS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtdipnxfyw.html

TS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gttvvazdqr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.9152youxi.cn/Article/details/gtgfzlkfml.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.0kj1m.cn/Article/details/gtmnpmtbmj.html

Ruby: threads.map(&:join)
来源：http://dali.ydzc1.top/Article/details/gtyqqpbsit.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigfzy.top/Article/details/gtiowvczkx.html

[O06] 使用进程池
来源：http://dali.hysaishi.cn/Article/details/gtvsvcbfgm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.0kj1m.cn/Article/details/gtjnoieykb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtswllagfm.html

JS:   // child_process / cluster 模块
来源：http://dali.fzhhl.top/Article/details/gthxcvtvxt.html

TS:   // child_process / cluster 模块
来源：http://dali.shangyingyoupin.top/Article/details/gtumdornhj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nanxinkj.top/Article/details/gtqzmysqbb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shangyingyoupin.top/Article/details/gtquwojdnb.html

Ruby: // fork 块
来源：http://dali.yj20258888.top/Article/details/gtjffrjtog.html

C#:   Parallel.For
来源：http://dali.xuanzx.com/Article/details/gtcsiusszl.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gthouodrmg.html

P. 常用工具函数
来源：http://dali.nanxinkj.top/Article/details/gtwklevwcl.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtzghbzseu.html

[P01] 生成 UUID
来源：http://dali.aizwys.cn/Article/details/gtcmfnyldz.html

Py:   str(uuid.uuid4())
来源：http://dali.c1oappe.top/Article/details/gtxlvnmhty.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hnqzz.top/Article/details/gtqvkomxfa.html

JS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gtehkbddyc.html

TS:   crypto.randomUUID()
来源：http://dali.tanke756.top/Article/details/gtnvdhjjsk.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnxiangtu.top/Article/details/gttucixrqo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xylfe.cn/Article/details/gtaixyxszc.html

Ruby: SecureRandom.uuid
来源：http://dali.wangdashe.top/Article/details/gtwlxfndgk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfbsratl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenzaomai.com/Article/details/gtbbzsigon.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hywenlv.cn/Article/details/gtsfvijbvb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sysykeji.top/Article/details/gtfjwkusjp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258888.top/Article/details/gtapelibaa.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.0kj1m.cn/Article/details/gtvmzkpqvf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenzaomai.com/Article/details/gtbltildbv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shangyingyoupin.top/Article/details/gtiwtghppc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xylfe.cn/Article/details/gtbxarxcmd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nwbrower.top/Article/details/gtefxemobu.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gtfbzsmgav.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tianlin.xyz/Article/details/gtxjikjkel.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.kuanghao11.cn/Article/details/gtauqcqaps.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhlwfdfe.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gtschjkibd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aizwys.cn/Article/details/gtiyzgeoih.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xziqi.cn/Article/details/gtjpqbjfgj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jlsjyb.cn/Article/details/gtjgaavxyk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.9152youxi.cn/Article/details/gtpzxzwmzh.html

[P04] 求长度
来源：http://dali.iojbl.cn/Article/details/gtigyjufll.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.iojbl.cn/Article/details/gtpgxuwxrd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtyabjytai.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gotoacloud.top/Article/details/gtbvfavcly.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gthqteifci.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gzhubu.top/Article/details/gticeknlpk.html

Go:   len(arr);  len(m)
来源：http://dali.ivvv.top/Article/details/gteubhbnzx.html

Ruby: x.length;  x.size
来源：http://dali.shangyingyoupin.top/Article/details/gthbzvsngp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuxming.cn/Article/details/gtxgonvqdz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ybcxt.top/Article/details/gtbtpfadsz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhixingplan.top/Article/details/gtuovawhev.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ehwqpu.com/Article/details/gtvirpxvnm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.9152youxi.cn/Article/details/gtcgqdrglw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnqzz.top/Article/details/gtroagjigh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.9152youxi.cn/Article/details/gtlbktghaw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpytghufy.html

Ruby: a == b
来源：http://dali.havefunace.top/Article/details/gtkbijpymr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yonumen.top/Article/details/gtrpvgtpzw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.aizwys.cn/Article/details/gtcfmfjbau.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xinyue.icu/Article/details/gtsktrosas.html

PHP:  if (empty($x)) {}
来源：http://dali.cdnleiting.top/Article/details/gtbnoozqvg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.iojbl.cn/Article/details/gteejosmrh.html

TS:   if (x == null) {}
来源：http://dali.sysykeji.top/Article/details/gtwyvhxfjz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jlsjyb.cn/Article/details/gtkrwxynae.html

Go:   if x == nil {}
来源：http://dali.havefunace.top/Article/details/gtxzhtotok.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.0kj1m.cn/Article/details/gtetttckbb.html

C#:   if (x is null) {}
来源：http://dali.9152youxi.cn/Article/details/gtwcqemyct.html

[P07] 防抖与节流
来源：http://dali.gaohongyu789.top/Article/details/gtzoekuytk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zdqjudy.top/Article/details/gtxcgnsioh.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258888.top/Article/details/gtxxeyutxy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yvedp.cn/Article/details/gtqijstama.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.havefunace.top/Article/details/gtuhbagqmp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.svipenyu.cn/Article/details/gtzkagregh.html


<!-- 参考信息 -->