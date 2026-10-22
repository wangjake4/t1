代发 wailian999

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2qllaxbpi.html

[M01] 读取命令行参数
来源：http://dali.nanxinkj.top/Article/details/gt2moyegtxd.html

Py:   sys.argv[1:]
来源：http://dali.sxryk.cn/Article/details/gt2qtwxysbd.html

PHP:  $argv;  $argc;
来源：http://dali.shuidangran.top/Article/details/gt2bsiidsop.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzkjzyo.html

TS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gt2hdffjozq.html

Java: args 数组（main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gt2bkqbhkyc.html

Go:   os.Args[1:]
来源：http://dali.ehwqpu.com/Article/details/gt2nqmryumb.html

Ruby: ARGV
来源：http://dali.smart0.xyz/Article/details/gt2vsrlxhej.html

C#:   args 数组（Main 方法参数）
来源：http://dali.birdmap.top/Article/details/gt2dehrwpyo.html

[M02] 读取环境变量
来源：http://dali.sxryk.cn/Article/details/gt2fbolyetd.html

Py:   os.environ.get("HOME")
来源：http://dali.yj202588.top/Article/details/gt2ghgzlpna.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gt2uhhlzbea.html

JS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gt2bnfsjnth.html

TS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gt2emoqvzrv.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2knuxonma.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gt2lhhqcxst.html

Ruby: ENV["HOME"]
来源：http://dali.yueranfly.top/Article/details/gt2hibtjnuf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuxming.cn/Article/details/gt2sowrwlvr.html

[M03] 执行外部命令
来源：http://dali.cdnleiting.top/Article/details/gt2fnkejuam.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.snrcjt.cn/Article/details/gt2yoprjolh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gogol.net.cn/Article/details/gt2jmqhlgsi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2venjinel.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gt2vtvnlmpg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuetiantiany.cn/Article/details/gt2sggbnjjy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2szvukbux.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yangfankeji.com/Article/details/gt2lgyezrbj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnqzz.top/Article/details/gt2vilcasso.html

[M04] 获取当前工作目录
来源：http://dali.gogol.net.cn/Article/details/gt2usifmeit.html

Py:   os.getcwd()
来源：http://dali.pycfn.com/Article/details/gt2ndqriner.html

PHP:  getcwd();
来源：http://dali.mhx1999.top/Article/details/gt2vtjlayym.html

JS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2zohiqpgk.html

TS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gt2dokfkopb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuanzx.com/Article/details/gt2zqzgeuig.html

Go:   os.Getwd()
来源：http://dali.xinyue.icu/Article/details/gt2xuiqnxvq.html

Ruby: Dir.pwd
来源：http://dali.gotoacloud.top/Article/details/gt2vacduxil.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.haohaochexian.top/Article/details/gt2lnjkfdqp.html

[M05] 设置退出码
来源：http://dali.sweek.top/Article/details/gt2uewfcqdn.html

Py:   sys.exit(1)
来源：http://dali.bjfxy.top/Article/details/gt2egxqrucu.html

PHP:  exit(1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ouhfxjoy.html

JS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gt2syywmvdd.html

TS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gt2quuxzgob.html

Java: System.exit(1)
来源：http://dali.bjfxy.top/Article/details/gt2ourboaer.html

Go:   os.Exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2auazuelk.html

Ruby: exit 1
来源：http://dali.guowangkeji.top/Article/details/gt2vsububtl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuanzhike.top/Article/details/gt2fvtipvdz.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iwlkinrt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ydzc1.top/Article/details/gt2qirrmzjh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ybcxt.top/Article/details/gt2ymhusixs.html

JS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gt2uxqipxmr.html

TS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gt2tmetmobr.html

Java: System.err.println("err")
来源：http://dali.sxryk.cn/Article/details/gt2wnprvjei.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cqqwz.cn/Article/details/gt2wpkbcifg.html

Ruby: warn "err"
来源：http://dali.gotoacloud.top/Article/details/gt2cknzyiyx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yangfankeji.com/Article/details/gt2moqswkge.html

[M07] 判断是否为主入口
来源：http://dali.tianlin.xyz/Article/details/gt2ksyloszu.html

Py:   if __name__ == "__main__":
来源：http://dali.fzhhl.top/Article/details/gt2uodxobbb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gogol.net.cn/Article/details/gt2mxqjfyic.html

JS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gt2bgxntriv.html

TS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gt2fxohcxus.html

Java: public static void main(String[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jslkfxtm.html

Go:   func main()
来源：http://dali.316326.xyz/Article/details/gt2cfgfemhk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xziqi.cn/Article/details/gt2axyqpjef.html

C#:   static void Main(string[] args)
来源：http://dali.yj202588.top/Article/details/gt2kzxsnfra.html

[M08] 获取系统与运行时信息
来源：http://dali.hysaishi.cn/Article/details/gt2rrxcyjwk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gzhubu.top/Article/details/gt2qishjoeu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rhcpmoqm.html

JS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gt2igvztact.html

TS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gt2mvgvlzln.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sysykeji.top/Article/details/gt2lgohdafq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yvedp.cn/Article/details/gt2fikddfgr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gt2fnbogxlc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hysaishi.cn/Article/details/gt2tmtokmmd.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2bxzqrdew.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpexmhu.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2rgfhqywn.html

[N01] 二分查找（有序数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lbuanyof.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2iwfhohbp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mzcfiojk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gt2lmpekmsd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gt2rdxhgbhg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gt2aefzqiqw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sweek.top/Article/details/gt2svmyqdoo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guannengcc.top/Article/details/gt2lkyumttj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gt2xvciajit.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgfzy.top/Article/details/gt2idttmqzc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gt2sbbncprk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gt2wdpinmlu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gt2dwdnzhlh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gt2cjpkfdev.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ybcxt.top/Article/details/gt2eubpjjef.html

Go:   slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gt2bwkferza.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gt2obhwbdoz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shuidangran.top/Article/details/gt2vprjqvcu.html

[N03] 快速排序（分治示例）
来源：http://dali.snrcjt.cn/Article/details/gt2qtqyxqqj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.svipenyu.cn/Article/details/gt2yjvjogaq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.vqdsnc.cn/Article/details/gt2vsdnjbpn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gt2ielallxc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gt2rcvaaede.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ydzc1.top/Article/details/gt2dnzvuoux.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenzaomai.com/Article/details/gt2zyjyqtqw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2iocmspwh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.316326.xyz/Article/details/gt2aoqhreey.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vfojhyoi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2fcufxotf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gt2jxjbkczc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gt2cwkyfvpm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cmylymfs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gt2oedzroxo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2alrfnipn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gt2hzrnpdml.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zcxxjzsk.html

[N05] 最大公约数
来源：http://dali.mhx1999.top/Article/details/gt2sntvbopm.html

Py:   math.gcd(a, b)
来源：http://dali.yonumen.top/Article/details/gt2jwcwapbk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shzxlz.cn/Article/details/gt2qqccnpxx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shuidangran.top/Article/details/gt2myvkpnnk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gt2udqgbwsg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.havefunace.top/Article/details/gt2preevmku.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgfzy.top/Article/details/gt2ewwpdunw.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bxjiraqs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zycfv.cn/Article/details/gt2uaifiyye.html

[N06] 判断回文字符串
来源：http://dali.cqqwz.cn/Article/details/gt2ncpzgtqz.html

Py:   s == s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gt2slkgsvaf.html

PHP:  $s === strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gt2gsihmpwn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gt2unzdjbbb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gt2bgntkxqr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vlxykfxu.html

Go:   // 双指针从两端比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uugcowlz.html

Ruby: s == s.reverse
来源：http://dali.fzhhl.top/Article/details/gt2oyaawjxj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gt2hcamorqf.html

[N07] 两数之和（返回下标）
来源：http://dali.shuidangran.top/Article/details/gt2kketgxcc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gzhubu.top/Article/details/gt2zmqiacxw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.redwolf501.top/Article/details/gt2qnoziwrx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jyoumei.cn/Article/details/gt2hxiugkkq.html

TS:   // 手写 Map<string, number>
来源：http://dali.snrcjt.cn/Article/details/gt2pzcpueie.html

Java: // 手写 HashMap
来源：http://dali.chenlongwang.top/Article/details/gt2sbokwpcl.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258.top/Article/details/gt2sngggsuh.html

Ruby: // 手写 Hash
来源：http://dali.haohaochexian.top/Article/details/gt2rhoyhzml.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qskoojdj.html

[N08] 生成全排列
来源：http://dali.hywenlv.cn/Article/details/gt2lvspycaf.html

Py:   itertools.permutations(arr)
来源：http://dali.yongpay.top/Article/details/gt2klckzfcp.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nduwgybd.html

JS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yuswowqk.html

TS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gt2yrrracak.html

Java: // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tsajgtqt.html

Go:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gt2tygmxpte.html

Ruby: arr.permutation.to_a
来源：http://dali.hnxiangtu.top/Article/details/gt2dujygugs.html

C#:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gt2wfcwcugs.html

[N09] 栈与队列
来源：http://dali.ybcxt.top/Article/details/gt2somdaaul.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gt2zzeuubfs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.mhx1999.top/Article/details/gt2oepdqysf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gt2zhhfrwyu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tianlin.xyz/Article/details/gt2damgnstk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ybcxt.top/Article/details/gt2gzcpfliq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2itdygasq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aizwys.cn/Article/details/gt2tnjbazuu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dashuyun.cn/Article/details/gt2ixtswnhq.html

[N10] 链表节点定义
来源：http://dali.guannengcc.top/Article/details/gt2zcuzcwhl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.quarkkingdee.top/Article/details/gt2zaqbkpro.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cheryme.top/Article/details/gt2lvlpmnbb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ydzc1.top/Article/details/gt2tbbbdftb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zejcvyxy.html

Java: class Node { int v; Node next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wcacntmn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sysykeji.top/Article/details/gt2rwenpalq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sweek.top/Article/details/gt2ovesnnkq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ivvv.top/Article/details/gt2ndvcnjkc.html

[N11] 二叉树中序遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2dojppglq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yuxming.cn/Article/details/gt2joxipbfe.html

PHP:  // 手写递归函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2fhxcwwfm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yueranfly.top/Article/details/gt2dyqqnbkq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gt2ojwhhijv.html

Java: // 手写递归
来源：http://dali.ivvv.top/Article/details/gt2xhhobdjd.html

Go:   // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gt2kdsmlwmd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2onctktmk.html

C#:   // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gt2huwckzoy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gogol.net.cn/Article/details/gt2rsqlypou.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2kdivkeoa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenjidiqi.icu/Article/details/gt2qfplogjc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gt2yskbyplj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gt2jutuqvad.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zdqjudy.top/Article/details/gt2teqifucb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jiagoushi.top/Article/details/gt2pxofxsfg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jyoumei.cn/Article/details/gt2dzxofjuz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.0kj1m.cn/Article/details/gt2dwhfisxb.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2nluehnxv.html

O. 并发与异步
来源：http://dali.nwbrower.top/Article/details/gt2loqtfwxi.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sxsovgvy.html

[O01] 启动一个线程
来源：http://dali.yvedp.cn/Article/details/gt2rnwadnkg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2agrlenvx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jianghu66.top/Article/details/gt2mafovuxu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangdashe.top/Article/details/gt2ljdoarmo.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gt2qkokkotx.html

Java: new Thread(() -> f()).start()
来源：http://dali.gogol.net.cn/Article/details/gt2nknraedl.html

Go:   go f()
来源：http://dali.ivvv.top/Article/details/gt2yuwwmtcu.html

Ruby: Thread.new { f }
来源：http://dali.jianghu66.top/Article/details/gt2hviumewc.html

C#:   Task.Run(() => F());
来源：http://dali.zhoulong.xyz/Article/details/gt2ogmmkqgy.html

[O02] 使用线程池
来源：http://dali.cdnleiting.top/Article/details/gt2tnzfhxoi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gaohongyu789.top/Article/details/gt2bzcassab.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hongshengwenyu.top/Article/details/gt2ugnjvftw.html

JS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gt2gmhcoyxd.html

TS:   // worker_threads 线程池
来源：http://dali.tanke756.top/Article/details/gt2qskopibr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenlongwang.top/Article/details/gt2ekjnfiqt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cdnleiting.top/Article/details/gt2sxhvlrdo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.feifeiyinyue.top/Article/details/gt2cavfsvgm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.snrcjt.cn/Article/details/gt2yjwbcohh.html

[O03] 加锁保护共享数据
来源：http://dali.wangshuangyany.cn/Article/details/gt2ccesnljo.html

Py:   with lock: shared += 1
来源：http://dali.sweek.top/Article/details/gt2kxaetlnc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.daria6918.cn/Article/details/gt2xavcrtka.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenjidiqi.icu/Article/details/gt2fmanvfdo.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gt2whsbnufp.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2swuejieu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2keqdnllu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.bjfxy.top/Article/details/gt2mabmyltb.html

C#:   lock (gate) { shared++; }
来源：http://dali.birdmap.top/Article/details/gt2ibwvivgf.html

[O04] 定义异步函数并等待
来源：http://dali.pengpengdd.cyou/Article/details/gt2pojyrblj.html

Py:   async def f():⏎    await g()
来源：http://dali.hnxiangtu.top/Article/details/gt2btmbiucf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shuidangran.top/Article/details/gt2oajpexmb.html

JS:   async function f() { await g(); }
来源：http://dali.sxryk.cn/Article/details/gt2kvvjwdjj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bmvliplp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yanxiufei.cn/Article/details/gt2pthazult.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gaohongyu789.top/Article/details/gt2fhpqmldp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj202588.top/Article/details/gt2evgxkufj.html

C#:   async Task F() { await G(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2srqjvnxz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zdqjudy.top/Article/details/gt2vqybkwwc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dashuyun.cn/Article/details/gt2dqrjioaq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hnxiangtu.top/Article/details/gt2dubcdsni.html

JS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gt2euivkkap.html

TS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gt2cmuoqaki.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hywenlv.cn/Article/details/gt2ldjfvqtf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sweek.top/Article/details/gt2aqjrmkxq.html

Ruby: threads.map(&:join)
来源：http://dali.pycfn.com/Article/details/gt2lcgicbjf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2enpxuifw.html

[O06] 使用进程池
来源：http://dali.zhixingplan.top/Article/details/gt2rndpknyb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.guannengcc.top/Article/details/gt2epklabzq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nwbrower.top/Article/details/gt2wshfpfzs.html

JS:   // child_process / cluster 模块
来源：http://dali.guannengcc.top/Article/details/gt2xxsqsfrm.html

TS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gt2rmjrjkgg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daria6918.cn/Article/details/gt2lobsooqd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.daria6918.cn/Article/details/gt2ickwgifa.html

Ruby: // fork 块
来源：http://dali.cqqwz.cn/Article/details/gt2tktoscsa.html

C#:   Parallel.For
来源：http://dali.wangdashe.top/Article/details/gt2nslraqfo.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2tfanvdqr.html

P. 常用工具函数
来源：http://dali.mhx1999.top/Article/details/gt2wxwrguob.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2vvksecol.html

[P01] 生成 UUID
来源：http://dali.ppjwa.cn/Article/details/gt2blbtwekc.html

Py:   str(uuid.uuid4())
来源：http://dali.zhiwuduotai.top/Article/details/gt2vbztqtgz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fengsongda.top/Article/details/gt2qbhqpswv.html

JS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gt2khvoxgwr.html

TS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gt2soaswivf.html

Java: UUID.randomUUID().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2lemxmjad.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nanxuanxn.top/Article/details/gt2wvktxoha.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgufenzy.top/Article/details/gt2epzfgeem.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jqgfzy.top/Article/details/gt2gygtaxia.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jiagoushi.top/Article/details/gt2zkvaujba.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigufen.top/Article/details/gt2bipliozk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fzhhl.top/Article/details/gt2llcstuwi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lnaxhmya.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ybbzwpqj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ehwqpu.com/Article/details/gt2vgboibgs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daxiang520.top/Article/details/gt2mluadepq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.daria6918.cn/Article/details/gt2tzinzvcw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xylfe.cn/Article/details/gt2tovpqhcd.html

[P03] 生成短随机字符串
来源：http://dali.9152youxi.cn/Article/details/gt2xydtnanx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yongpay.top/Article/details/gt2xmjvclkb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yazfrboe.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuanzhike.top/Article/details/gt2zvrozosp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2ehelyubw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nwbrower.top/Article/details/gt2pyamzmbj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yuxming.cn/Article/details/gt2dhbrhzna.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yoyfnbgi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhongyouzk.top/Article/details/gt2arartdyl.html

[P04] 求长度
来源：http://dali.quarkkingdee.top/Article/details/gt2wftqdvlg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shangyingyoupin.top/Article/details/gt2mozlmbwr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gt2ppsajihg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pengpengdd.cyou/Article/details/gt2dmvpospt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gt2pmcnccgj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xziqi.cn/Article/details/gt2dzilsned.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258.top/Article/details/gt2dwcqujfn.html

Ruby: x.length;  x.size
来源：http://dali.jlsjyb.cn/Article/details/gt2rnibkkya.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ydzc1.top/Article/details/gt2lpecgbrw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenjidiqi.icu/Article/details/gt2ejdsyrxz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ydzc1.top/Article/details/gt2bprgwmwo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cashguo.top/Article/details/gt2kfheqxwm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ybcxt.top/Article/details/gt2aeqydeox.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.9152youxi.cn/Article/details/gt2hsxphiad.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2lxowgmpv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aibaodan.cn/Article/details/gt2uaypkqxu.html

Ruby: a == b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zwcstvfp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhongyouzk.top/Article/details/gt2oooufnjr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.mhx1999.top/Article/details/gt2acuvcjpx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ehwqpu.com/Article/details/gt2oxzqkfwp.html

PHP:  if (empty($x)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uxfuyclb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yueranfly.top/Article/details/gt2tncvpoai.html

TS:   if (x == null) {}
来源：http://dali.xziqi.cn/Article/details/gt2qddzcdyt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cdnleiting.top/Article/details/gt2jbgxgsla.html

Go:   if x == nil {}
来源：http://dali.zhongyouzk.top/Article/details/gt2xmpyhybz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.kuanghao11.cn/Article/details/gt2nalrcofo.html

C#:   if (x is null) {}
来源：http://dali.yuanzhike.top/Article/details/gt2ropjhijn.html

[P07] 防抖与节流
来源：http://dali.smart0.xyz/Article/details/gt2vsuuyrvz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.svipenyu.cn/Article/details/gt2xzsokvkc.html


<!-- 参考信息 -->