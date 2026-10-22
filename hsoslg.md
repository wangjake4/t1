代发 wailian999

Ruby: ARGV
来源：http://dali.sysykeji.top/Article/details/gt2bhgnnvtg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gt2xoiharyl.html

[M02] 读取环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2orgxkqst.html

Py:   os.environ.get("HOME")
来源：http://dali.hammf.cn/Article/details/gt2ljyklhis.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gt2sruahhoq.html

JS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gt2oznpxmxg.html

TS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gt2vpteigya.html

Java: System.getenv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rshvczku.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sysykeji.top/Article/details/gt2cnveqjib.html

Ruby: ENV["HOME"]
来源：http://dali.hnqzz.top/Article/details/gt2mdwbcatz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gogol.net.cn/Article/details/gt2asqohfbh.html

[M03] 执行外部命令
来源：http://dali.gaohongyu789.top/Article/details/gt2atlihpgq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yangfankeji.com/Article/details/gt2cvohkaqr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.snrcjt.cn/Article/details/gt2oiuqsrjl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hozmtbub.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gt2yslrqjrq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuetiantiany.cn/Article/details/gt2kgmsdqfj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cashguo.top/Article/details/gt2wzjxdusn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2borflmio.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sweek.top/Article/details/gt2vuymitys.html

[M04] 获取当前工作目录
来源：http://dali.sxryk.cn/Article/details/gt2mhlxjtpc.html

Py:   os.getcwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2ppzqajnv.html

PHP:  getcwd();
来源：http://dali.sxryk.cn/Article/details/gt2zruhbmph.html

JS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gt2euqsyppa.html

TS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gt2ynavwpov.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigufen.top/Article/details/gt2wypnzvhb.html

Go:   os.Getwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2pmhbyyrq.html

Ruby: Dir.pwd
来源：http://dali.chenlongwang.top/Article/details/gt2fzjqipli.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhixingplan.top/Article/details/gt2gsghrbvh.html

[M05] 设置退出码
来源：http://dali.jyoumei.cn/Article/details/gt2bchyoafm.html

Py:   sys.exit(1)
来源：http://dali.guannengcc.top/Article/details/gt2ruprripc.html

PHP:  exit(1);
来源：http://dali.yueranfly.top/Article/details/gt2aeuimrpk.html

JS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gt2xbxwpodu.html

TS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2urhjynru.html

Java: System.exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2uazkksol.html

Go:   os.Exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2lltvfszl.html

Ruby: exit 1
来源：http://dali.sufxvd.cn/Article/details/gt2qiwmlcbm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cucudq.cn/Article/details/gt2yssagomi.html

[M06] 向标准错误输出
来源：http://dali.0kj1m.cn/Article/details/gt2wcjscwha.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xinyue.icu/Article/details/gt2cbymyxjw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.vqdsnc.cn/Article/details/gt2vlwykhph.html

JS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gt2gwykwfcb.html

TS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gt2ziajrzgs.html

Java: System.err.println("err")
来源：http://dali.birdmap.top/Article/details/gt2tumsqiyf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sysykeji.top/Article/details/gt2xnqojtvn.html

Ruby: warn "err"
来源：http://dali.birdmap.top/Article/details/gt2gnuzvyhx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cqqwz.cn/Article/details/gt2fpmdyxhw.html

[M07] 判断是否为主入口
来源：http://dali.0kj1m.cn/Article/details/gt2ogmuussb.html

Py:   if __name__ == "__main__":
来源：http://dali.quarkkingdee.top/Article/details/gt2czjyxpmm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tian-w.cn/Article/details/gt2beorpzld.html

JS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gt2bllcojhv.html

TS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gt2yqyppfht.html

Java: public static void main(String[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mikzfhzh.html

Go:   func main()
来源：http://dali.guowangkeji.top/Article/details/gt2mqgwfgkh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ivvv.top/Article/details/gt2uezbazgs.html

C#:   static void Main(string[] args)
来源：http://dali.ybcxt.top/Article/details/gt2zkxbalsa.html

[M08] 获取系统与运行时信息
来源：http://dali.kuanghao11.cn/Article/details/gt2rtfwzecd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenzaomai.com/Article/details/gt2jgbprmlz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhongyouzk.top/Article/details/gt2xobhndkz.html

JS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gt2frawpmce.html

TS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gt2epdsylei.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yangfankeji.com/Article/details/gt2fcunslhi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gzhubu.top/Article/details/gt2rdeyxyvf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tian-w.cn/Article/details/gt2ndccijek.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fxsisver.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2xtaigdtq.html

N. 数据结构与算法
来源：http://dali.hnqzz.top/Article/details/gt2fwthxqym.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2sdcpfjbv.html

[N01] 二分查找（有序数组）
来源：http://dali.bjfxy.top/Article/details/gt2wlfeirut.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2tzpzrbmf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hysaishi.cn/Article/details/gt2wdylggmi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gt2tucyaqqk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xziqi.cn/Article/details/gt2kxfcrmcf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2wsycfsza.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2ryhtpzil.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cashguo.top/Article/details/gt2ocevabll.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2fpawkurt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cashguo.top/Article/details/gt2rjhucerf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gt2mkyauraa.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gzhubu.top/Article/details/gt2myduuugq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gt2svhysini.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gt2dlobwvsx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gaohongyu789.top/Article/details/gt2fjlyxlxl.html

Go:   slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gt2qbecppiv.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gt2zsilsuop.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guowangkeji.top/Article/details/gt2syfwplzx.html

[N03] 快速排序（分治示例）
来源：http://dali.dianchejie.cn/Article/details/gt2gwsesptc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenjidiqi.icu/Article/details/gt2zaucpaux.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jiagoushi.top/Article/details/gt2wjcenmgl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gt2yxzhsllw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gt2vcdglruy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jlsjyb.cn/Article/details/gt2nkabqqlm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.andypj.xyz/Article/details/gt2hlxgwcpf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guannengcc.top/Article/details/gt2ddovzoqk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ivvv.top/Article/details/gt2cpzimsto.html

[N04] 斐波那契数列
来源：http://dali.hammf.cn/Article/details/gt2ayhgzqcl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gt2azwbeodh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gt2sklfsbif.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2tzejrflo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2etkngcow.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.c1oappe.top/Article/details/gt2tfiwxbew.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cashguo.top/Article/details/gt2oervgjpp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guannengcc.top/Article/details/gt2lbliugsw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gt2gkgmacet.html

[N05] 最大公约数
来源：http://dali.zhixingplan.top/Article/details/gt2btbwerbm.html

Py:   math.gcd(a, b)
来源：http://dali.zhengqikj.top/Article/details/gt2quooquyk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.snrcjt.cn/Article/details/gt2xgwsfkid.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gt2fsqavlxu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gt2wncnpedy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.redwolf501.top/Article/details/gt2cmmrlxbj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhoulong.xyz/Article/details/gt2tlwfynqa.html

Ruby: a.gcd(b)
来源：http://dali.meibo888.top/Article/details/gt2gvtlplob.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigfzy.top/Article/details/gt2jqbyuebm.html

[N06] 判断回文字符串
来源：http://dali.andypj.xyz/Article/details/gt2jyafetwc.html

Py:   s == s[::-1]
来源：http://dali.zycfv.cn/Article/details/gt2ldrpoxqo.html

PHP:  $s === strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gt2woyzvual.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gt2akmqtbmb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gt2klcdkdcq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cqqwz.cn/Article/details/gt2xweotkap.html

Go:   // 双指针从两端比较
来源：http://dali.sysykeji.top/Article/details/gt2wtbhlpne.html

Ruby: s == s.reverse
来源：http://dali.tian-w.cn/Article/details/gt2zalloyir.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gt2pouvwqtk.html

[N07] 两数之和（返回下标）
来源：http://dali.jlsjyb.cn/Article/details/gt2atdqvtsl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.mhx1999.top/Article/details/gt2hgldktiv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gogol.net.cn/Article/details/gt2zqrxxhzo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuanzhike.top/Article/details/gt2edtyohir.html

TS:   // 手写 Map<string, number>
来源：http://dali.sxryk.cn/Article/details/gt2gvarkvxc.html

Java: // 手写 HashMap
来源：http://dali.dashuyun.cn/Article/details/gt2ddarqhln.html

Go:   // 手写 map[int]int
来源：http://dali.guowangkeji.top/Article/details/gt2qkeufwrp.html

Ruby: // 手写 Hash
来源：http://dali.ppjwa.cn/Article/details/gt2mvtlkqky.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yuanzhike.top/Article/details/gt2tgcoqfwp.html

[N08] 生成全排列
来源：http://dali.jqgfzy.top/Article/details/gt2xliqmkhi.html

Py:   itertools.permutations(arr)
来源：http://dali.yj20258.top/Article/details/gt2sqbwhfmf.html

PHP:  // 手写递归交换
来源：http://dali.yuxming.cn/Article/details/gt2plcxsxrs.html

JS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2odxqfnnc.html

TS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2njpgzsmi.html

Java: // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2earcodwj.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qhacalvh.html

Ruby: arr.permutation.to_a
来源：http://dali.hfpthk.cn/Article/details/gt2ubwtfbhh.html

C#:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gt2wgreskhk.html

[N09] 栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gt2srhmtbzq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.vqdsnc.cn/Article/details/gt2ifepegdx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daria6918.cn/Article/details/gt2oobpxkkk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gt2czltlynb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangdashe.top/Article/details/gt2atanxgpe.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tunkcduw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.svipenyu.cn/Article/details/gt2vqkpkdgq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gt2ipcmaund.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xylfe.cn/Article/details/gt2wbukgism.html

[N10] 链表节点定义
来源：http://dali.yuxming.cn/Article/details/gt2duxxyeyi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.c1oappe.top/Article/details/gt2jfsjmmna.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tian-w.cn/Article/details/gt2vstcudyz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gaohongyu789.top/Article/details/gt2grnbqvuw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cfjxfuas.html

Java: class Node { int v; Node next; }
来源：http://dali.smart0.xyz/Article/details/gt2lmoqgjar.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xinyue.icu/Article/details/gt2tktzgpnh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.fengsongda.top/Article/details/gt2zkmdjinc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgfzy.top/Article/details/gt2jlgxgqzq.html

[N11] 二叉树中序遍历
来源：http://dali.0kj1m.cn/Article/details/gt2bunbwdxv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.iojbl.cn/Article/details/gt2iqkirsar.html

PHP:  // 手写递归函数
来源：http://dali.ydzc1.top/Article/details/gt2lpzqmpve.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gt2sywlscmf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxuanxn.top/Article/details/gt2lhhfrsla.html

Java: // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gt2hearcdqj.html

Go:   // 手写递归
来源：http://dali.xylfe.cn/Article/details/gt2kvymfkog.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.snrcjt.cn/Article/details/gt2mnhbuvsr.html

C#:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gt2uavdmpya.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ppjwa.cn/Article/details/gt2rxgfbedx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yvedp.cn/Article/details/gt2kgvipvvh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.svipenyu.cn/Article/details/gt2inledbcv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gdgxjkmz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gt2zhmxkwts.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gt2gbqoqcqw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xylfe.cn/Article/details/gt2uizazjji.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sweek.top/Article/details/gt2guapdkko.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gt2wrasmrnt.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2dfttoqfp.html

O. 并发与异步
来源：http://dali.yangfankeji.com/Article/details/gt2noznquvz.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2walvtfny.html

[O01] 启动一个线程
来源：http://dali.pycfn.com/Article/details/gt2batkfolu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ppjwa.cn/Article/details/gt2wygrsnyw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nszabpru.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuxming.cn/Article/details/gt2anrfbaqg.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gt2aaqtmvqv.html

Java: new Thread(() -> f()).start()
来源：http://dali.zdqjudy.top/Article/details/gt2blfxbhfn.html

Go:   go f()
来源：http://dali.jqgufenzy.top/Article/details/gt2unkedaxw.html

Ruby: Thread.new { f }
来源：http://dali.aizwys.cn/Article/details/gt2vzbczbdh.html

C#:   Task.Run(() => F());
来源：http://dali.cqqwz.cn/Article/details/gt2yduzmjuh.html

[O02] 使用线程池
来源：http://dali.yuanzhike.top/Article/details/gt2dojfisoy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jlsjyb.cn/Article/details/gt2jyomslxj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangshuangyany.cn/Article/details/gt2ctabxcco.html

JS:   // worker_threads 线程池
来源：http://dali.yuxming.cn/Article/details/gt2vfvaqpxa.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gt2wxyansvc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guannengcc.top/Article/details/gt2rnfzxhzl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.iojbl.cn/Article/details/gt2ngggycze.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yuxming.cn/Article/details/gt2pdiycqle.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenjidiqi.icu/Article/details/gt2hromjoob.html

[O03] 加锁保护共享数据
来源：http://dali.yvedp.cn/Article/details/gt2rcfaofax.html

Py:   with lock: shared += 1
来源：http://dali.chenzaomai.com/Article/details/gt2npqloumk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gaohongyu789.top/Article/details/gt2bjouckfe.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.316326.xyz/Article/details/gt2vvlbkcct.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gt2vekuyxzg.html

Java: synchronized (this) { shared++; }
来源：http://dali.ppjwa.cn/Article/details/gt2mzdwjznz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.meibo888.top/Article/details/gt2lisnhljl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hammf.cn/Article/details/gt2tafggjoa.html

C#:   lock (gate) { shared++; }
来源：http://dali.smart0.xyz/Article/details/gt2onttanuq.html

[O04] 定义异步函数并等待
来源：http://dali.birdmap.top/Article/details/gt2ivggcdrc.html

Py:   async def f():⏎    await g()
来源：http://dali.xylfe.cn/Article/details/gt2qdrloskp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hysaishi.cn/Article/details/gt2wwphwfpc.html

JS:   async function f() { await g(); }
来源：http://dali.smart0.xyz/Article/details/gt2blqzuims.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dohxgilx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.316326.xyz/Article/details/gt2sepcsspc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigfzy.top/Article/details/gt2bhayiywa.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yonumen.top/Article/details/gt2lnkycszd.html

C#:   async Task F() { await G(); }
来源：http://dali.birdmap.top/Article/details/gt2xbldnzsz.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj20258.top/Article/details/gt2vyzbjwnh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sweek.top/Article/details/gt2qyflbjai.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.guowangkeji.top/Article/details/gt2zxsqzgaq.html

JS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gt2jkbpngmy.html

TS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gt2jbjpfemf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hfpthk.cn/Article/details/gt2sroahnxm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cucudq.cn/Article/details/gt2zlxxiexw.html

Ruby: threads.map(&:join)
来源：http://dali.yuanzhike.top/Article/details/gt2aukciqcz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.vqdsnc.cn/Article/details/gt2svxeultm.html

[O06] 使用进程池
来源：http://dali.ehwqpu.com/Article/details/gt2bhhmjlwp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sxryk.cn/Article/details/gt2pvyukmhr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jianghu66.top/Article/details/gt2qhagxwzq.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gt2gmfyuvcr.html

TS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gt2dedchgtf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gotoacloud.top/Article/details/gt2qdrnqqgt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhoulong.xyz/Article/details/gt2xhveeior.html

Ruby: // fork 块
来源：http://dali.c1oappe.top/Article/details/gt2rtkwhnxh.html

C#:   Parallel.For
来源：http://dali.shzxlz.cn/Article/details/gt2xwtrrdwb.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2siefufkq.html

P. 常用工具函数
来源：http://dali.pycfn.com/Article/details/gt2lfaxzkdq.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2majdymia.html

[P01] 生成 UUID
来源：http://dali.nanxuanxn.top/Article/details/gt2qfxlfsjw.html

Py:   str(uuid.uuid4())
来源：http://dali.zycfv.cn/Article/details/gt2luazuwxo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj20258888.top/Article/details/gt2jpxvbnwn.html

JS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gt2fafcoftm.html

TS:   crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gt2buvpzyfg.html

Java: UUID.randomUUID().toString()
来源：http://dali.birdmap.top/Article/details/gt2rehxivmj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sweek.top/Article/details/gt2ncdnnrhl.html

Ruby: SecureRandom.uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hjdbeuji.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ivvv.top/Article/details/gt2ucluusda.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yueranfly.top/Article/details/gt2amtojjhw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ivvv.top/Article/details/gt2hkmaognk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.c1oappe.top/Article/details/gt2hnvzvost.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shzxlz.cn/Article/details/gt2mdixemsq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vnkilcbf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cheryme.top/Article/details/gt2qgzzffbc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jyoumei.cn/Article/details/gt2hflfvusp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuxming.cn/Article/details/gt2cbwwyrlg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hfpthk.cn/Article/details/gt2qnwbnzwo.html

[P03] 生成短随机字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2rpwtpbql.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.daxiang520.top/Article/details/gt2cdnpuxsd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daria6918.cn/Article/details/gt2cqrimosm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2yjnmirjs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gt2wurdwauz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yvedp.cn/Article/details/gt2czqwzndp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenjidiqi.icu/Article/details/gt2izbbhkny.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sufxvd.cn/Article/details/gt2ngftrngs.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.wangshuangyany.cn/Article/details/gt2tupqybcj.html

[P04] 求长度
来源：http://dali.ydzc1.top/Article/details/gt2szapktoa.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sxryk.cn/Article/details/gt2ohvlvequ.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gt2hxrqzoag.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gt2nngzefmi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gt2jaydzija.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sufxvd.cn/Article/details/gt2okbbqikm.html

Go:   len(arr);  len(m)
来源：http://dali.jianghu66.top/Article/details/gt2oitxlcwr.html

Ruby: x.length;  x.size
来源：http://dali.ydzc1.top/Article/details/gt2niykumei.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.aizwys.cn/Article/details/gt2ixezfdoy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yvedp.cn/Article/details/gt2njryptxd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ppjwa.cn/Article/details/gt2xdtdgwrk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gotoacloud.top/Article/details/gt2ycdeztwo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.iojbl.cn/Article/details/gt2mpwagmll.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gt2nntwbmts.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.andypj.xyz/Article/details/gt2xountnrf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ounesbfv.html

Ruby: a == b
来源：http://dali.sxryk.cn/Article/details/gt2wqtzupnn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jianghu66.top/Article/details/gt2ormrosqd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xtcwdtpa.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ybcxt.top/Article/details/gt2xdswqxxg.html

PHP:  if (empty($x)) {}
来源：http://dali.zdqjudy.top/Article/details/gt2xkzpwkwj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yonumen.top/Article/details/gt2vxibckwr.html

TS:   if (x == null) {}
来源：http://dali.hysaishi.cn/Article/details/gt2vvegqmpt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gt2eqiaujrn.html

Go:   if x == nil {}
来源：http://dali.guannengcc.top/Article/details/gt2voblyzhw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhongyouzk.top/Article/details/gt2gpvtxqqf.html

C#:   if (x is null) {}
来源：http://dali.aibaodan.cn/Article/details/gt2xddrqswc.html

[P07] 防抖与节流
来源：http://dali.quarkkingdee.top/Article/details/gt2iuqzqlsl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenlongwang.top/Article/details/gt2kwhulcbu.html

PHP:  // 手写时间戳比较
来源：http://dali.xinyue.icu/Article/details/gt2pniqsazo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gt2kypppsse.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gt2bqgsdjyn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cdnleiting.top/Article/details/gt2ilskoxnq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daria6918.cn/Article/details/gt2ldjwqmgb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jlsjyb.cn/Article/details/gt2ywecseup.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj20258.top/Article/details/gt2gckvjhsj.html

[P08] 处理浮点精度问题
来源：http://dali.pycfn.com/Article/details/gt2cwjlbjzt.html


<!-- 参考信息 -->