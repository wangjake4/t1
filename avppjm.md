代发 wailian999

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gtstndjkid.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yueranfly.top/Article/details/gttdcqxpxr.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtacliwpni.html

M. 命令行 / 进程 / 环境
来源：http://dali.hfpthk.cn/Article/details/gtbyxgusmp.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtorfuhnwd.html

[M01] 读取命令行参数
来源：http://dali.yonumen.top/Article/details/gtlmreyiba.html

Py:   sys.argv[1:]
来源：http://dali.fengsongda.top/Article/details/gtciysagft.html

PHP:  $argv;  $argc;
来源：http://dali.bjfxy.top/Article/details/gtjojsjajt.html

JS:   process.argv.slice(2)
来源：http://dali.redwolf501.top/Article/details/gtziziawue.html

TS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gtnsdvvfwj.html

Java: args 数组（main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gtostmlfab.html

Go:   os.Args[1:]
来源：http://dali.jyoumei.cn/Article/details/gtkmgekjqi.html

Ruby: ARGV
来源：http://dali.gotoacloud.top/Article/details/gtbgjeowul.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gthrockqrf.html

[M02] 读取环境变量
来源：http://dali.gogol.net.cn/Article/details/gtubvbcwjn.html

Py:   os.environ.get("HOME")
来源：http://dali.andypj.xyz/Article/details/gtahpzfoaq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cheryme.top/Article/details/gtjbqjsxgx.html

JS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtvxudyyoa.html

TS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gtnzgyimzm.html

Java: System.getenv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtnxoobakp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtykrtyyon.html

Ruby: ENV["HOME"]
来源：http://dali.xinyue.icu/Article/details/gtnabslfvy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.mhx1999.top/Article/details/gtldfthlql.html

[M03] 执行外部命令
来源：http://dali.yj202588.top/Article/details/gtaexqvlyw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258.top/Article/details/gtvppawknn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.9152youxi.cn/Article/details/gtuyxxlatk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gtonraurfy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gtjwyujwiu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.316326.xyz/Article/details/gtajxnohsh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sysykeji.top/Article/details/gtptoddbab.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ppjwa.cn/Article/details/gtdkkwdgvp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gtgnappqsu.html

[M04] 获取当前工作目录
来源：http://dali.yuanzhike.top/Article/details/gtupejcmxv.html

Py:   os.getcwd()
来源：http://dali.havefunace.top/Article/details/gtiipkvqmd.html

PHP:  getcwd();
来源：http://dali.tian-w.cn/Article/details/gthvgrcolh.html

JS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gtvslphecz.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gthlqzfuah.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.mhx1999.top/Article/details/gtnghxxxrj.html

Go:   os.Getwd()
来源：http://dali.yuxming.cn/Article/details/gttdtuldzt.html

Ruby: Dir.pwd
来源：http://dali.bjfxy.top/Article/details/gtyqrqqmig.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dianchejie.cn/Article/details/gtkziaenpf.html

[M05] 设置退出码
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrvpujou.html

Py:   sys.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtflznimbi.html

PHP:  exit(1);
来源：http://dali.jyoumei.cn/Article/details/gtolbngcwg.html

JS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gtnsiuinod.html

TS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtzogdvdhm.html

Java: System.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtpwvqeutv.html

Go:   os.Exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtrzlnzvwq.html

Ruby: exit 1
来源：http://dali.nanxuanxn.top/Article/details/gtjceugpup.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptrarste.html

[M06] 向标准错误输出
来源：http://dali.nwbrower.top/Article/details/gtucunfmjn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gteapptoig.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.bjfxy.top/Article/details/gtjqhdnife.html

JS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gttmoxorak.html

TS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gtrkbnnxxo.html

Java: System.err.println("err")
来源：http://dali.iojbl.cn/Article/details/gttqiyqeqv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ydzc1.top/Article/details/gtdqliekwo.html

Ruby: warn "err"
来源：http://dali.gogol.net.cn/Article/details/gthaxiqjqj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.quarkkingdee.top/Article/details/gteaoiyfsd.html

[M07] 判断是否为主入口
来源：http://dali.jqgufenzy.top/Article/details/gtcubqnjdi.html

Py:   if __name__ == "__main__":
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpcowwnce.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtpivdoees.html

JS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gtsdtouftf.html

TS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtrvyfwewr.html

Java: public static void main(String[] args)
来源：http://dali.jianghu66.top/Article/details/gtnuzbcnoe.html

Go:   func main()
来源：http://dali.meibo888.top/Article/details/gtmdjtknxr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgejwiqnd.html

C#:   static void Main(string[] args)
来源：http://dali.fengsongda.top/Article/details/gtktzeynqj.html

[M08] 获取系统与运行时信息
来源：http://dali.jlsjyb.cn/Article/details/gtzsdqarvf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258888.top/Article/details/gtzoludxdm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ivvv.top/Article/details/gthogmuven.html

JS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gtifnbxjkv.html

TS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpivrbxx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhoulong.xyz/Article/details/gtvwvgvpkh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yongpay.top/Article/details/gtoajqefuv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigufen.top/Article/details/gtngedvoxs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangdashe.top/Article/details/gtcbiwfyjo.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtnffmhydd.html

N. 数据结构与算法
来源：http://dali.yueranfly.top/Article/details/gtijsgstju.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtaptcfayn.html

[N01] 二分查找（有序数组）
来源：http://dali.andypj.xyz/Article/details/gtuahukbib.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtluymvjwt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbsooqao.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gttdijqjuv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gtjbmewtlq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gthanlswzh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtgiywguiu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tianlin.xyz/Article/details/gtrsuuhwrn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtkcopuocn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ydzc1.top/Article/details/gtwmcxqqpe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gtgidbfmfx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfeohqcjo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gtsvkksgvk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gtjilwpewy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sxryk.cn/Article/details/gttcnefkru.html

Go:   slices.Sort(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtnegwaika.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gtpscqngtf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cqqwz.cn/Article/details/gtrxmoqncs.html

[N03] 快速排序（分治示例）
来源：http://dali.chenlongwang.top/Article/details/gtdnqbdyxa.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nanxinkj.top/Article/details/gtzdrajoev.html

PHP:  // 递归实现，或用 usort
来源：http://dali.feifeiyinyue.top/Article/details/gtmufexwvf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhaomingkeji.xyz/Article/details/gthcmyraxv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gtoclwftro.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkvxtngy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.c1oappe.top/Article/details/gtjxmhrwrt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.bjfxy.top/Article/details/gtbfoeufck.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yangfankeji.com/Article/details/gtqengssox.html

[N04] 斐波那契数列
来源：http://dali.nwbrower.top/Article/details/gteebswiso.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gthjkplftx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.guowangkeji.top/Article/details/gtyywhdtwa.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gtqqgsosic.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gtthbsvhmm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.havefunace.top/Article/details/gtoyzxokxx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guowangkeji.top/Article/details/gtpzyujevx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfqbjoac.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gttivpkrli.html

[N05] 最大公约数
来源：http://dali.sufxvd.cn/Article/details/gtzizkwtrs.html

Py:   math.gcd(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtvixblwhs.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.316326.xyz/Article/details/gtkcyjnpah.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtocujohir.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gtjectmfao.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.birdmap.top/Article/details/gtagcumbdz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.quarkkingdee.top/Article/details/gtzblepvyh.html

Ruby: a.gcd(b)
来源：http://dali.daria6918.cn/Article/details/gtacjtdodm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ivvv.top/Article/details/gtqpwyodjk.html

[N06] 判断回文字符串
来源：http://dali.iojbl.cn/Article/details/gtkknxetgf.html

Py:   s == s[::-1]
来源：http://dali.hammf.cn/Article/details/gtnpzeqrag.html

PHP:  $s === strrev($s);
来源：http://dali.mhx1999.top/Article/details/gtipgwegjw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtqbaoovmw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtypfnmjub.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xziqi.cn/Article/details/gtccocibna.html

Go:   // 双指针从两端比较
来源：http://dali.xuetiantiany.cn/Article/details/gtadspuizm.html

Ruby: s == s.reverse
来源：http://dali.yj202588.top/Article/details/gtolqljgnx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gtdoqtvlgr.html

[N07] 两数之和（返回下标）
来源：http://dali.dianchejie.cn/Article/details/gtaxjgovac.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hfpthk.cn/Article/details/gtsqvcebaa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fengsongda.top/Article/details/gtwbeybzdv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ehwqpu.com/Article/details/gtxrkuimqi.html

TS:   // 手写 Map<string, number>
来源：http://dali.xziqi.cn/Article/details/gtcuflyynm.html

Java: // 手写 HashMap
来源：http://dali.ppjwa.cn/Article/details/gtpqbodygw.html

Go:   // 手写 map[int]int
来源：http://dali.gotoacloud.top/Article/details/gtddqvwrcx.html

Ruby: // 手写 Hash
来源：http://dali.feifeiyinyue.top/Article/details/gtpmkrpxht.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cucudq.cn/Article/details/gtabdfexmm.html

[N08] 生成全排列
来源：http://dali.yvedp.cn/Article/details/gtslznfspp.html

Py:   itertools.permutations(arr)
来源：http://dali.cqqwz.cn/Article/details/gtwnxhbkte.html

PHP:  // 手写递归交换
来源：http://dali.yj20258888.top/Article/details/gtaahhzpdi.html

JS:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtnsdrtjny.html

TS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtaknmlitc.html

Java: // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtxmaehmjz.html

Go:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtsfeefvhn.html

Ruby: arr.permutation.to_a
来源：http://dali.xziqi.cn/Article/details/gtjqigcice.html

C#:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtwlbxovui.html

[N09] 栈与队列
来源：http://dali.jianghu66.top/Article/details/gtrckpecqj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yongpay.top/Article/details/gtqbcrqeer.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ivvv.top/Article/details/gtdjaodrpy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gtdjqqzmti.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.0kj1m.cn/Article/details/gtouhpiwfa.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ivvv.top/Article/details/gtfidfglkd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.haohaochexian.top/Article/details/gtakjawlzk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gttkceoqwp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.quarkkingdee.top/Article/details/gtmnzvdkjh.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuyybhdkg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.meibo888.top/Article/details/gtggcuiops.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gotoacloud.top/Article/details/gtpxuofkwc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.kuanghao11.cn/Article/details/gtaegneqka.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daxiang520.top/Article/details/gtrjyxbauu.html

Java: class Node { int v; Node next; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgjxklzc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.redwolf501.top/Article/details/gtlpjogovx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258888.top/Article/details/gtcxuvnlty.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gaohongyu789.top/Article/details/gtanvdozbq.html

[N11] 二叉树中序遍历
来源：http://dali.zhoulong.xyz/Article/details/gthefusfax.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shuidangran.top/Article/details/gtftxylzmr.html

PHP:  // 手写递归函数
来源：http://dali.chenjidiqi.icu/Article/details/gtxzqogxae.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gtylkiwyrg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxuanxn.top/Article/details/gtpbftbvgi.html

Java: // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtfsjogjfz.html

Go:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gtolnsdtrd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhongyouzk.top/Article/details/gtutztefxl.html

C#:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gtackhrhyf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258888.top/Article/details/gteidzmbcz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hfpthk.cn/Article/details/gtmfrililr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhiwuduotai.top/Article/details/gtfepywoig.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigfzy.top/Article/details/gtcdlhvncg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenlongwang.top/Article/details/gtuyuocrnj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gtaaqakbes.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sweek.top/Article/details/gtatdlfrhu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jyoumei.cn/Article/details/gttbtzvutj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gtrdlhfkmu.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtriqlllxe.html

O. 并发与异步
来源：http://dali.yj20258888.top/Article/details/gtgafrhdnt.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtdumcqser.html

[O01] 启动一个线程
来源：http://dali.jiagoushi.top/Article/details/gtyhvibpur.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shuidangran.top/Article/details/gtpmjwbcwn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zdqjudy.top/Article/details/gteuonguhg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.smart0.xyz/Article/details/gtcqvwdzyo.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gtqelbqkyr.html

Java: new Thread(() -> f()).start()
来源：http://dali.shzxlz.cn/Article/details/gtzvhfsgaf.html

Go:   go f()
来源：http://dali.hongshengwenyu.top/Article/details/gtvaaagzbm.html

Ruby: Thread.new { f }
来源：http://dali.vqdsnc.cn/Article/details/gthjhloimw.html

C#:   Task.Run(() => F());
来源：http://dali.hysaishi.cn/Article/details/gteyarldmn.html

[O02] 使用线程池
来源：http://dali.dianchejie.cn/Article/details/gtugbccapy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hysaishi.cn/Article/details/gtmfflzjvh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.meibo888.top/Article/details/gtlrkorfuw.html

JS:   // worker_threads 线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqdhqqvu.html

TS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gtxpikwpmu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xuanzx.com/Article/details/gtnaxziyoq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gogol.net.cn/Article/details/gtrlivcvtf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj202588.top/Article/details/gtykgvznay.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shzxlz.cn/Article/details/gtxlnjndmv.html

[O03] 加锁保护共享数据
来源：http://dali.sweek.top/Article/details/gtcqazftfm.html

Py:   with lock: shared += 1
来源：http://dali.fengsongda.top/Article/details/gtldpbuphx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuxming.cn/Article/details/gttgebkdwc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guowangkeji.top/Article/details/gtjwtbgdhe.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gtmszcfncu.html

Java: synchronized (this) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gtjwhpxpvi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tian-w.cn/Article/details/gtgcdobhxu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daria6918.cn/Article/details/gtqyyyzgeb.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtblboccaq.html

[O04] 定义异步函数并等待
来源：http://dali.bjfxy.top/Article/details/gtpxqhehwr.html

Py:   async def f():⏎    await g()
来源：http://dali.sweek.top/Article/details/gtkacyrblq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfxtjnkl.html

JS:   async function f() { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gtswhmqjcw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jiagoushi.top/Article/details/gtzxmzujnl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ivvv.top/Article/details/gtkvaeywov.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhyqwftq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hysaishi.cn/Article/details/gtnsjhbsuk.html

C#:   async Task F() { await G(); }
来源：http://dali.xylfe.cn/Article/details/gttpmzjbzs.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinghuilouyu.cn/Article/details/gtesmleoia.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhixingplan.top/Article/details/gtxsyjuhqf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shangyingyoupin.top/Article/details/gtmrhsnegp.html

JS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gtoceuscmm.html

TS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gtxyykxqir.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shangyingyoupin.top/Article/details/gtafwmwhge.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shangyingyoupin.top/Article/details/gtrcsjethi.html

Ruby: threads.map(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gtuvijnhdl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfzgnjaj.html

[O06] 使用进程池
来源：http://dali.quarkkingdee.top/Article/details/gtthrtkfqk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ybcxt.top/Article/details/gtefdfspal.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shangyingyoupin.top/Article/details/gtiromhukx.html

JS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gtjvriyevs.html

TS:   // child_process / cluster 模块
来源：http://dali.hongshengwenyu.top/Article/details/gtqllkjyhv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.iojbl.cn/Article/details/gtcenytsdq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sxryk.cn/Article/details/gtcykzjsag.html

Ruby: // fork 块
来源：http://dali.cqqwz.cn/Article/details/gtydnrtrhc.html

C#:   Parallel.For
来源：http://dali.yj202588.top/Article/details/gtwwizartf.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtnqyyramh.html

P. 常用工具函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtledtkgum.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtzeshjjnz.html

[P01] 生成 UUID
来源：http://dali.nanxuanxn.top/Article/details/gtgqphxoms.html

Py:   str(uuid.uuid4())
来源：http://dali.aizwys.cn/Article/details/gtesrhfkcn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gtsvkbxhxz.html

JS:   crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gtezvnvfnc.html

TS:   crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gtmjlkgqfj.html

Java: UUID.randomUUID().toString()
来源：http://dali.bjfxy.top/Article/details/gtgbufzjdl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuxming.cn/Article/details/gtaikajntm.html

Ruby: SecureRandom.uuid
来源：http://dali.0kj1m.cn/Article/details/gtfsizoqfy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xylfe.cn/Article/details/gtqbrrynvs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yonumen.top/Article/details/gtumxjgjtb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzydqewo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jiagoushi.top/Article/details/gtqlcranwf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtucxbxbmf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ivvv.top/Article/details/gtuttqnvzi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtfrzcgjdh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.smart0.xyz/Article/details/gtztghlwon.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dianchejie.cn/Article/details/gtzlqfqxjn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.kuanghao11.cn/Article/details/gtgxyhpehl.html

[P03] 生成短随机字符串
来源：http://dali.yonumen.top/Article/details/gtneqpmbya.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sysykeji.top/Article/details/gtwzmovrvt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenzaomai.com/Article/details/gthlgcdadm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gtuzepfknu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gtshxgdozv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cqqwz.cn/Article/details/gtljvuelde.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gogol.net.cn/Article/details/gtlwvxgmli.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.meibo888.top/Article/details/gtivqivjjq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.dashuyun.cn/Article/details/gttqvcneik.html

[P04] 求长度
来源：http://dali.yonumen.top/Article/details/gthjwkuwre.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shanyushiyangtech.top/Article/details/gtqihtanhm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtfvugnwen.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gtcgzawvrk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gttvjpbeam.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcurjkcbp.html

Go:   len(arr);  len(m)
来源：http://dali.zhengqikj.top/Article/details/gtnzmhznae.html

Ruby: x.length;  x.size
来源：http://dali.yj20258.top/Article/details/gtzlmvxbnu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.316326.xyz/Article/details/gtaclhtrbb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yueranfly.top/Article/details/gtwttcphsi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.redwolf501.top/Article/details/gtmjbkzbow.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgfzy.top/Article/details/gtehpemnkf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgufenzy.top/Article/details/gtmivrllba.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.svipenyu.cn/Article/details/gtzccdgeqq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sxryk.cn/Article/details/gtcopntuyr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cucudq.cn/Article/details/gtoxbdzxsn.html

Ruby: a == b
来源：http://dali.birdmap.top/Article/details/gtiinumloe.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258.top/Article/details/gtjndcwhqa.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.haohaochexian.top/Article/details/gtjzezepbo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zdqjudy.top/Article/details/gtlulxzenx.html

PHP:  if (empty($x)) {}
来源：http://dali.aizwys.cn/Article/details/gtwplwpkpi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.smart0.xyz/Article/details/gtqtffknek.html

TS:   if (x == null) {}
来源：http://dali.xylfe.cn/Article/details/gthrvseamd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtogfelyvy.html

Go:   if x == nil {}
来源：http://dali.pycfn.com/Article/details/gtuwexaiuu.html


<!-- 参考信息 -->