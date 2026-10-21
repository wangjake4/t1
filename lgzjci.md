代发 wailian999

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtwqcekbkk.html

[M01] 读取命令行参数
来源：http://dali.nwbrower.top/Article/details/gthmxtoxay.html

Py:   sys.argv[1:]
来源：http://dali.cqqwz.cn/Article/details/gtkyqvglpu.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcexrveoh.html

JS:   process.argv.slice(2)
来源：http://dali.yangfankeji.com/Article/details/gtucfkkdzd.html

TS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gtfcrvxzpz.html

Java: args 数组（main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfufnmiom.html

Go:   os.Args[1:]
来源：http://dali.jiagoushi.top/Article/details/gttphpseye.html

Ruby: ARGV
来源：http://dali.kuanghao11.cn/Article/details/gtwgqdhpfe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gtsucpedeq.html

[M02] 读取环境变量
来源：http://dali.yongpay.top/Article/details/gtmxnduxkb.html

Py:   os.environ.get("HOME")
来源：http://dali.xziqi.cn/Article/details/gtbtxbapra.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hammf.cn/Article/details/gtjgcuzyvt.html

JS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gtruzaqztv.html

TS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gtatjgykcr.html

Java: System.getenv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtzqzxzmij.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuanzx.com/Article/details/gthzimdptk.html

Ruby: ENV["HOME"]
来源：http://dali.gaohongyu789.top/Article/details/gtdtcqrsqr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlxkrcvc.html

[M03] 执行外部命令
来源：http://dali.gotoacloud.top/Article/details/gtzbigxdey.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hysaishi.cn/Article/details/gtsneqqcly.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hfpthk.cn/Article/details/gtarquheoh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtvpmjfumo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gtunzxwter.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.316326.xyz/Article/details/gtitizydqv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenjidiqi.icu/Article/details/gtdqexrdms.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangshuangyany.cn/Article/details/gtwxohxasl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhixingplan.top/Article/details/gteuaqsonv.html

[M04] 获取当前工作目录
来源：http://dali.316326.xyz/Article/details/gtaycafxqa.html

Py:   os.getcwd()
来源：http://dali.nanxuanxn.top/Article/details/gtkwzyskkb.html

PHP:  getcwd();
来源：http://dali.yj202588.top/Article/details/gtllmaapvy.html

JS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gtivsmfaff.html

TS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gtjpvuqawy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtnerzwk.html

Go:   os.Getwd()
来源：http://dali.iojbl.cn/Article/details/gtimowjfxo.html

Ruby: Dir.pwd
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzrrsomz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujtbmthf.html

[M05] 设置退出码
来源：http://dali.pengpengdd.cyou/Article/details/gtecijcpog.html

Py:   sys.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtdrmlwjfd.html

PHP:  exit(1);
来源：http://dali.cheryme.top/Article/details/gtisdcwito.html

JS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gtlohxcisy.html

TS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtngsksugs.html

Java: System.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtqvxjglei.html

Go:   os.Exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtmtrnrtli.html

Ruby: exit 1
来源：http://dali.havefunace.top/Article/details/gtljnyxccs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tianlin.xyz/Article/details/gtuagljqjm.html

[M06] 向标准错误输出
来源：http://dali.tian-w.cn/Article/details/gtlegcrecr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cashguo.top/Article/details/gtfxxsficz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ivvv.top/Article/details/gtruxdshck.html

JS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gtxcmzxeue.html

TS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gteyrpinjk.html

Java: System.err.println("err")
来源：http://dali.cdnleiting.top/Article/details/gtjiwyklsi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xziqi.cn/Article/details/gtmjnwaqfx.html

Ruby: warn "err"
来源：http://dali.guannengcc.top/Article/details/gtmurkhcur.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hammf.cn/Article/details/gtxsbleket.html

[M07] 判断是否为主入口
来源：http://dali.svipenyu.cn/Article/details/gtkahaxbfa.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigfzy.top/Article/details/gtyqegyuye.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcoxvkfm.html

JS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gtabgcnclr.html

TS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gtbrlrlhlx.html

Java: public static void main(String[] args)
来源：http://dali.tianlin.xyz/Article/details/gtvktgdvwo.html

Go:   func main()
来源：http://dali.sufxvd.cn/Article/details/gtyvlpoexx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxinkj.top/Article/details/gtjdvlcpfk.html

C#:   static void Main(string[] args)
来源：http://dali.chenzaomai.com/Article/details/gtpphofola.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgufenzy.top/Article/details/gtzwrgease.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jianghu66.top/Article/details/gtuygftevq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shuidangran.top/Article/details/gtjfiijxec.html

JS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gtmriuedqs.html

TS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gtywpmxisa.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangdashe.top/Article/details/gtjnxjlbie.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yangfankeji.com/Article/details/gtxdonoooy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.smart0.xyz/Article/details/gtwsbkiune.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gogol.net.cn/Article/details/gtzgbksppc.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtqbbtgmaw.html

N. 数据结构与算法
来源：http://dali.aizwys.cn/Article/details/gtrfnplwzp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtwlcrjqfj.html

[N01] 二分查找（有序数组）
来源：http://dali.9152youxi.cn/Article/details/gtyrpqokzp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtjisoywux.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sysykeji.top/Article/details/gtlknfwuuo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gtrzbflnjb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtdmdtwnpm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gttnkmhuns.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtrwbtyoto.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258888.top/Article/details/gtchwldgba.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtkzjsrvvm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.iojbl.cn/Article/details/gtbsstszfy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvumbojnk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnxiangtu.top/Article/details/gtaedbpppx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gtaravdkza.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gtocmltasl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenlongwang.top/Article/details/gttsbppyyj.html

Go:   slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzogyivdx.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gtljhyaycs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhiwuduotai.top/Article/details/gtsnydrvik.html

[N03] 快速排序（分治示例）
来源：http://dali.shangyingyoupin.top/Article/details/gtzaahwfcv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cheryme.top/Article/details/gtsetdqghj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ydzc1.top/Article/details/gthmdcctvf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gtwbqejjea.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuanzhike.top/Article/details/gtnkspnfhu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jiagoushi.top/Article/details/gtzwznfnyh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.bjfxy.top/Article/details/gtgiakkcjp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.0kj1m.cn/Article/details/gtkdgettqg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dashuyun.cn/Article/details/gteuhshufv.html

[N04] 斐波那契数列
来源：http://dali.yuanzhike.top/Article/details/gtqdojvcys.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cucudq.cn/Article/details/gtnthzintt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cheryme.top/Article/details/gthvbwnflc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gtpjmbskde.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gthdsngciw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sysykeji.top/Article/details/gtuevhqzot.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xinyue.icu/Article/details/gtkjrzdgdv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gtzskfaxxb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gtihafgrub.html

[N05] 最大公约数
来源：http://dali.gzhubu.top/Article/details/gtesakiwkq.html

Py:   math.gcd(a, b)
来源：http://dali.hammf.cn/Article/details/gtaaqdkgwb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cdnleiting.top/Article/details/gttmnmntfj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtexcbkiyh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxinkj.top/Article/details/gtgzhmtlgv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jiagoushi.top/Article/details/gtzwblfsbk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shuidangran.top/Article/details/gtbwdofzmp.html

Ruby: a.gcd(b)
来源：http://dali.birdmap.top/Article/details/gtmyqaoauh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ppjwa.cn/Article/details/gtxmzhrurk.html

[N06] 判断回文字符串
来源：http://dali.andypj.xyz/Article/details/gtxgguzfnn.html

Py:   s == s[::-1]
来源：http://dali.zhongyouzk.top/Article/details/gtknrpendn.html

PHP:  $s === strrev($s);
来源：http://dali.jinqigufen.top/Article/details/gtmfkakrjs.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtiinhncud.html

TS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtifvkaixc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.andypj.xyz/Article/details/gtqsagzycz.html

Go:   // 双指针从两端比较
来源：http://dali.xuanzx.com/Article/details/gtwpnlwzxu.html

Ruby: s == s.reverse
来源：http://dali.ybcxt.top/Article/details/gtidhskfsd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gtluvhhunl.html

[N07] 两数之和（返回下标）
来源：http://dali.chenjidiqi.icu/Article/details/gtbxmrjprp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yvedp.cn/Article/details/gtyhfixtpa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuetiantiany.cn/Article/details/gthfxqyhnq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sufxvd.cn/Article/details/gtvhuxgcnu.html

TS:   // 手写 Map<string, number>
来源：http://dali.aibaodan.cn/Article/details/gtbenlaozj.html

Java: // 手写 HashMap
来源：http://dali.pycfn.com/Article/details/gtuivmbygl.html

Go:   // 手写 map[int]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwmxvzli.html

Ruby: // 手写 Hash
来源：http://dali.c1oappe.top/Article/details/gtzhoyfnxv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.9152youxi.cn/Article/details/gtrsjblpdm.html

[N08] 生成全排列
来源：http://dali.hysaishi.cn/Article/details/gtqlqmmyrh.html

Py:   itertools.permutations(arr)
来源：http://dali.yongpay.top/Article/details/gtrxykwibf.html

PHP:  // 手写递归交换
来源：http://dali.jianghu66.top/Article/details/gtfifnzcam.html

JS:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtndfwdsft.html

TS:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtyohbqgno.html

Java: // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtspzuthxu.html

Go:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtrliwqayk.html

Ruby: arr.permutation.to_a
来源：http://dali.svipenyu.cn/Article/details/gtrhgqzwcw.html

C#:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtwhfswhow.html

[N09] 栈与队列
来源：http://dali.xylfe.cn/Article/details/gtfgdqwpei.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tian-w.cn/Article/details/gteohviewc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtospwcpfs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gticmjmywq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.quarkkingdee.top/Article/details/gtmabcovzl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zdqjudy.top/Article/details/gtrsstmwxa.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.redwolf501.top/Article/details/gtjzkrwgew.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtanydjasl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yongpay.top/Article/details/gtrpqcerjj.html

[N10] 链表节点定义
来源：http://dali.316326.xyz/Article/details/gtzvtzabqs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.birdmap.top/Article/details/gtvlvwvyma.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenzaomai.com/Article/details/gtkzrhpgmx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxodnlgur.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenlongwang.top/Article/details/gtcaskczzq.html

Java: class Node { int v; Node next; }
来源：http://dali.fengsongda.top/Article/details/gtbeaswunk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.dianchejie.cn/Article/details/gthlhqyixu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cucudq.cn/Article/details/gtkkjlbawe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cashguo.top/Article/details/gtlvtgvpas.html

[N11] 二叉树中序遍历
来源：http://dali.guannengcc.top/Article/details/gtbtslomuo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteyxnauvx.html

PHP:  // 手写递归函数
来源：http://dali.316326.xyz/Article/details/gtvwdxlunz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gtlfsjlqob.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gtipyguflu.html

Java: // 手写递归
来源：http://dali.tanke756.top/Article/details/gtvsegulkh.html

Go:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gtijgqkyic.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shzxlz.cn/Article/details/gtprqmsymq.html

C#:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gtztztixiu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daxiang520.top/Article/details/gtvnsssjss.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.haohaochexian.top/Article/details/gteenkmran.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hywenlv.cn/Article/details/gtsdcdatlj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gtnorfzozg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gthappjndt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.0kj1m.cn/Article/details/gtmbmxhnuj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.kuanghao11.cn/Article/details/gtdvbhgcwq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ybcxt.top/Article/details/gtjryssxpl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gtjgfycgwn.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtzxfoiepa.html

O. 并发与异步
来源：http://dali.yuanzhike.top/Article/details/gtjbwefnbv.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtrnjxajhc.html

[O01] 启动一个线程
来源：http://dali.yangfankeji.com/Article/details/gtscrlkgxj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.guowangkeji.top/Article/details/gtfvyhizkb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.birdmap.top/Article/details/gtokunahom.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigufen.top/Article/details/gtyzwxeoyk.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gthaydzueu.html

Java: new Thread(() -> f()).start()
来源：http://dali.guannengcc.top/Article/details/gtquihbmfv.html

Go:   go f()
来源：http://dali.aibaodan.cn/Article/details/gttihexazp.html

Ruby: Thread.new { f }
来源：http://dali.jqgufenzy.top/Article/details/gtguwjfihx.html

C#:   Task.Run(() => F());
来源：http://dali.yongpay.top/Article/details/gtjzwsvoep.html

[O02] 使用线程池
来源：http://dali.bjfxy.top/Article/details/gtmqseiiha.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhengqikj.top/Article/details/gtdnkyzyyj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ehwqpu.com/Article/details/gtbzpaysls.html

JS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gtewwhwgsd.html

TS:   // worker_threads 线程池
来源：http://dali.chenlongwang.top/Article/details/gtcequexhe.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.316326.xyz/Article/details/gtilocxxaj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tanke756.top/Article/details/gtknqcqhwb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jlsjyb.cn/Article/details/gtvybyossy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xinyue.icu/Article/details/gtfrtsjlzn.html

[O03] 加锁保护共享数据
来源：http://dali.jlsjyb.cn/Article/details/gtmcfibtof.html

Py:   with lock: shared += 1
来源：http://dali.xziqi.cn/Article/details/gtxuoaetci.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.andypj.xyz/Article/details/gthvihuflm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gzhubu.top/Article/details/gttblldepn.html

TS:   // 同 JS
来源：http://dali.ivvv.top/Article/details/gtmplotozs.html

Java: synchronized (this) { shared++; }
来源：http://dali.fzhhl.top/Article/details/gtsxrnmbkj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.bjfxy.top/Article/details/gthbxixbqv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.aizwys.cn/Article/details/gtflphhxyh.html

C#:   lock (gate) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gtaizuniel.html

[O04] 定义异步函数并等待
来源：http://dali.shuidangran.top/Article/details/gtunhglkdi.html

Py:   async def f():⏎    await g()
来源：http://dali.cashguo.top/Article/details/gtqicaqmxk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.redwolf501.top/Article/details/gtjubykozy.html

JS:   async function f() { await g(); }
来源：http://dali.cashguo.top/Article/details/gtzdjttnmz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gtoeukxmjl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fzhhl.top/Article/details/gtenypuufl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.snrcjt.cn/Article/details/gtyypxrgqa.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofrdgfrx.html

C#:   async Task F() { await G(); }
来源：http://dali.mhx1999.top/Article/details/gtavhdxnxn.html

[O05] 并发执行并等待全部完成
来源：http://dali.feifeiyinyue.top/Article/details/gtgkfaizxv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.vqdsnc.cn/Article/details/gtxeqdnmew.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nwbrower.top/Article/details/gtdvhehfgi.html

JS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gtbcnqzxoo.html

TS:   await Promise.all(tasks)
来源：http://dali.shzxlz.cn/Article/details/gtaghfcrda.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuxming.cn/Article/details/gtxvfrfgxa.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.redwolf501.top/Article/details/gtqwemnsfi.html

Ruby: threads.map(&:join)
来源：http://dali.dianchejie.cn/Article/details/gtdnqtmtcf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hysaishi.cn/Article/details/gtfkxkqjvo.html

[O06] 使用进程池
来源：http://dali.zdqjudy.top/Article/details/gtoqihmaqi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jlsjyb.cn/Article/details/gtkzlpidxk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsobfrvuf.html

JS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gtcvdtwrtc.html

TS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszykfesh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aizwys.cn/Article/details/gtvhbrdcpe.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.smart0.xyz/Article/details/gtquirouel.html

Ruby: // fork 块
来源：http://dali.dashuyun.cn/Article/details/gtltpzguol.html

C#:   Parallel.For
来源：http://dali.pycfn.com/Article/details/gtsmcpvewd.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwrywzit.html

P. 常用工具函数
来源：http://dali.iojbl.cn/Article/details/gtdqisfkjq.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gttfyhdyvz.html

[P01] 生成 UUID
来源：http://dali.ehwqpu.com/Article/details/gtjhctiwxs.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgufenzy.top/Article/details/gtdkttgakt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jiagoushi.top/Article/details/gtxvanxpqi.html

JS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gtaxznmbwi.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gtrmeshboz.html

Java: UUID.randomUUID().toString()
来源：http://dali.vqdsnc.cn/Article/details/gtekxfwqhg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nanxuanxn.top/Article/details/gtqhiqjevm.html

Ruby: SecureRandom.uuid
来源：http://dali.cucudq.cn/Article/details/gtvqrqoand.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigufen.top/Article/details/gtpeouhcsp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jlsjyb.cn/Article/details/gtiihewbvh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.svipenyu.cn/Article/details/gtremsysef.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zdqjudy.top/Article/details/gtffkzicbw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.smart0.xyz/Article/details/gtpwktczri.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.redwolf501.top/Article/details/gtqmdsqrgc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.bjfxy.top/Article/details/gtkfgjlykf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxsofuop.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.redwolf501.top/Article/details/gtltgtttsq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daria6918.cn/Article/details/gtvxlkmgkw.html

[P03] 生成短随机字符串
来源：http://dali.jqgufenzy.top/Article/details/gtzyifqxug.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xylfe.cn/Article/details/gtpkuwilci.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.0kj1m.cn/Article/details/gtqhnxnkqn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gtrgegndck.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gtelqnimyb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shuidangran.top/Article/details/gtglxmoswt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gogol.net.cn/Article/details/gtejzgtsdz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cheryme.top/Article/details/gtounlqsuo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.meibo888.top/Article/details/gtdujzkldq.html

[P04] 求长度
来源：http://dali.meibo888.top/Article/details/gtyecuatoi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ybcxt.top/Article/details/gtwyexfyox.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtmbyrzcfe.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhongyouzk.top/Article/details/gtbbvdruvl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gtxbdwlism.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttuhsgqly.html

Go:   len(arr);  len(m)
来源：http://dali.sufxvd.cn/Article/details/gtjyekhppu.html

Ruby: x.length;  x.size
来源：http://dali.xziqi.cn/Article/details/gtbjrnjrxg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gthhdolemz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.smart0.xyz/Article/details/gtmkwgcgsg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xinyue.icu/Article/details/gtpdbkuplu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj202588.top/Article/details/gtegmwqsbx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nanxuanxn.top/Article/details/gtgdqygtjj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.redwolf501.top/Article/details/gtzbmdrhtp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhongyouzk.top/Article/details/gtkovisjhy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gtbyxjnvaz.html

Ruby: a == b
来源：http://dali.andypj.xyz/Article/details/gtsxqvjtgq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ppjwa.cn/Article/details/gtaiuhyfpi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.mhx1999.top/Article/details/gtsgfchiyq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jiagoushi.top/Article/details/gtvmbvircz.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtvrlyqlfw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhiwuduotai.top/Article/details/gtjdfgdzqz.html

TS:   if (x == null) {}
来源：http://dali.xylfe.cn/Article/details/gtnhvallzw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gtpocnblil.html

Go:   if x == nil {}
来源：http://dali.jqgfzy.top/Article/details/gtytaubskl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflbhtevq.html

C#:   if (x is null) {}
来源：http://dali.yvedp.cn/Article/details/gtsqwgnejv.html

[P07] 防抖与节流
来源：http://dali.nanxinkj.top/Article/details/gtbiftwbhi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jianghu66.top/Article/details/gtfgbosrpp.html


<!-- 参考信息 -->