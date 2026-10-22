代发 wailian999

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2meevelfl.html

[M01] 读取命令行参数
来源：http://dali.aibaodan.cn/Article/details/gt2gkdagnzd.html

Py:   sys.argv[1:]
来源：http://dali.vqdsnc.cn/Article/details/gt2qmrasmhr.html

PHP:  $argv;  $argc;
来源：http://dali.pengpengdd.cyou/Article/details/gt2nakewqkx.html

JS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gt2ygtokxvk.html

TS:   process.argv.slice(2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zqonvmav.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gt2akbxvwbb.html

Go:   os.Args[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cviccfju.html

Ruby: ARGV
来源：http://dali.tianlin.xyz/Article/details/gt2zqdldlbh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hfpthk.cn/Article/details/gt2sjwijoay.html

[M02] 读取环境变量
来源：http://dali.sweek.top/Article/details/gt2dpvmhgya.html

Py:   os.environ.get("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gt2apclpixi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jzajcesi.html

JS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gt2divyilrv.html

TS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gt2zfqtecls.html

Java: System.getenv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gt2fouplodi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yonumen.top/Article/details/gt2piqtzwax.html

Ruby: ENV["HOME"]
来源：http://dali.zhixingplan.top/Article/details/gt2pifwrdst.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2mfgvjtae.html

[M03] 执行外部命令
来源：http://dali.yangfankeji.com/Article/details/gt2wfyrtyri.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ybcxt.top/Article/details/gt2cglzircd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.316326.xyz/Article/details/gt2tidsikri.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gt2vspiozui.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gt2qphcfmhn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigufen.top/Article/details/gt2fluqlute.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fengsongda.top/Article/details/gt2atgahbib.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sweek.top/Article/details/gt2ijgywbge.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jlsjyb.cn/Article/details/gt2viytxjpv.html

[M04] 获取当前工作目录
来源：http://dali.guannengcc.top/Article/details/gt2fnmymrtf.html

Py:   os.getcwd()
来源：http://dali.yonumen.top/Article/details/gt2ikrkgete.html

PHP:  getcwd();
来源：http://dali.sxryk.cn/Article/details/gt2aybnpbjz.html

JS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gt2wzjpqaab.html

TS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2qnhbybaw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cdnleiting.top/Article/details/gt2wdwccxrt.html

Go:   os.Getwd()
来源：http://dali.havefunace.top/Article/details/gt2twymgqgf.html

Ruby: Dir.pwd
来源：http://dali.tanke756.top/Article/details/gt2ekmemegt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yongpay.top/Article/details/gt2amxyhjhy.html

[M05] 设置退出码
来源：http://dali.guannengcc.top/Article/details/gt2lhanrefu.html

Py:   sys.exit(1)
来源：http://dali.xylfe.cn/Article/details/gt2nsptyols.html

PHP:  exit(1);
来源：http://dali.jyoumei.cn/Article/details/gt2rgeajfqh.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2axarmlzg.html

TS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2swfzufat.html

Java: System.exit(1)
来源：http://dali.iojbl.cn/Article/details/gt2aagfldxk.html

Go:   os.Exit(1)
来源：http://dali.bjfxy.top/Article/details/gt2tosrocqu.html

Ruby: exit 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ldxnksfb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gogol.net.cn/Article/details/gt2xqbibeeo.html

[M06] 向标准错误输出
来源：http://dali.ivvv.top/Article/details/gt2ifkwtjcw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.0kj1m.cn/Article/details/gt2kfcmqjar.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.kuanghao11.cn/Article/details/gt2rjkxinco.html

JS:   console.error("err")
来源：http://dali.nanxinkj.top/Article/details/gt2wdjtmfcz.html

TS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gt2ogfvfoxn.html

Java: System.err.println("err")
来源：http://dali.fengsongda.top/Article/details/gt2igvrgltj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2osgipvik.html

Ruby: warn "err"
来源：http://dali.zhixingplan.top/Article/details/gt2priancqv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.9152youxi.cn/Article/details/gt2koflxdxw.html

[M07] 判断是否为主入口
来源：http://dali.aibaodan.cn/Article/details/gt2trpjrijn.html

Py:   if __name__ == "__main__":
来源：http://dali.chenlongwang.top/Article/details/gt2cuohcsmx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pengpengdd.cyou/Article/details/gt2cjfhwzki.html

JS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gt2xxlewlmh.html

TS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gt2hcgwnzzm.html

Java: public static void main(String[] args)
来源：http://dali.zycfv.cn/Article/details/gt2jjdpyazw.html

Go:   func main()
来源：http://dali.yueranfly.top/Article/details/gt2wudzbxvw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.kuanghao11.cn/Article/details/gt2nauxkdtn.html

C#:   static void Main(string[] args)
来源：http://dali.smart0.xyz/Article/details/gt2pqycghrs.html

[M08] 获取系统与运行时信息
来源：http://dali.gzhubu.top/Article/details/gt2uistexce.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangshuangyany.cn/Article/details/gt2busadcfr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ivvv.top/Article/details/gt2aewoxbmh.html

JS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gt2wbaivbph.html

TS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gt2zljvgomn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zycfv.cn/Article/details/gt2osrtceeo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj202588.top/Article/details/gt2vcrzrklu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gt2auaspmhe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yanxiufei.cn/Article/details/gt2qokdfsuo.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2vkdcfcuq.html

N. 数据结构与算法
来源：http://dali.hongshengwenyu.top/Article/details/gt2ypwbfygr.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2ilnwpvce.html

[N01] 二分查找（有序数组）
来源：http://dali.dashuyun.cn/Article/details/gt2wjfifkdv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gt2wpdgqvsn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gt2kzduhkjh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gt2picyljmr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gt2opyebypk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2blsjkjgw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2vbhqrzbd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.havefunace.top/Article/details/gt2zygdgbhp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gt2wohbdbnm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.snrcjt.cn/Article/details/gt2dbjkxmib.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gt2cwnrfrws.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxuanxn.top/Article/details/gt2paoguxgw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gt2tobjsrsx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gt2ckoeqynf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuanzx.com/Article/details/gt2hurioikk.html

Go:   slices.Sort(arr)
来源：http://dali.yongpay.top/Article/details/gt2nxbnycbg.html

Ruby: arr.sort
来源：http://dali.xinyue.icu/Article/details/gt2biileljy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2axejtghc.html

[N03] 快速排序（分治示例）
来源：http://dali.ivvv.top/Article/details/gt2nnskrkxg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wufiaccl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.guannengcc.top/Article/details/gt2qrgprhgk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gt2zubxhwze.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.smart0.xyz/Article/details/gt2dzeroopw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangshuangyany.cn/Article/details/gt2btwhrfbt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.vqdsnc.cn/Article/details/gt2lsngbgby.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nanxuanxn.top/Article/details/gt2naeswsbr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigfzy.top/Article/details/gt2nzohzabd.html

[N04] 斐波那契数列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jlzfvndp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gt2obsdmtpm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gt2olijsrss.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gt2ovpdysxv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gt2vzplxhta.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gt2pewxcewb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.andypj.xyz/Article/details/gt2zjqdtenh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gt2ievegdaw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gt2ijgjtssb.html

[N05] 最大公约数
来源：http://dali.yj202588.top/Article/details/gt2vvabsadl.html

Py:   math.gcd(a, b)
来源：http://dali.aizwys.cn/Article/details/gt2lijmovpq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.iojbl.cn/Article/details/gt2xhmsjgif.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gt2aabqubsy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2skdjrvko.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhiwuduotai.top/Article/details/gt2wxvooois.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.smart0.xyz/Article/details/gt2wxwxhtfj.html

Ruby: a.gcd(b)
来源：http://dali.ivvv.top/Article/details/gt2mclngono.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daria6918.cn/Article/details/gt2wrzscyde.html

[N06] 判断回文字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2gpwdwxoh.html

Py:   s == s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gt2yyasqacw.html

PHP:  $s === strrev($s);
来源：http://dali.yvedp.cn/Article/details/gt2lgzhcmgy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ajuisrnm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gt2zphujnrp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gaohongyu789.top/Article/details/gt2yquodrka.html

Go:   // 双指针从两端比较
来源：http://dali.chenlongwang.top/Article/details/gt2jxnqsboe.html

Ruby: s == s.reverse
来源：http://dali.guowangkeji.top/Article/details/gt2prrjclac.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gt2jymlrbkp.html

[N07] 两数之和（返回下标）
来源：http://dali.ppjwa.cn/Article/details/gt2bokfpvma.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhongyouzk.top/Article/details/gt2igifeesz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cucudq.cn/Article/details/gt2ceaejmcv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wufnwbny.html

TS:   // 手写 Map<string, number>
来源：http://dali.sufxvd.cn/Article/details/gt2qzseocpf.html

Java: // 手写 HashMap
来源：http://dali.chenlongwang.top/Article/details/gt2irbllkeo.html

Go:   // 手写 map[int]int
来源：http://dali.meibo888.top/Article/details/gt2lxigsxdu.html

Ruby: // 手写 Hash
来源：http://dali.hammf.cn/Article/details/gt2yndahwza.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ihiylqgp.html

[N08] 生成全排列
来源：http://dali.chenlongwang.top/Article/details/gt2tztypumf.html

Py:   itertools.permutations(arr)
来源：http://dali.pycfn.com/Article/details/gt2laxwgyaf.html

PHP:  // 手写递归交换
来源：http://dali.yangfankeji.com/Article/details/gt2zzhtataz.html

JS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gt2kkzxotba.html

TS:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gt2zgkixvcq.html

Java: // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gt2aolejieq.html

Go:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2dmnwmwlx.html

Ruby: arr.permutation.to_a
来源：http://dali.cqqwz.cn/Article/details/gt2krpcqlvc.html

C#:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gt2opbplmrx.html

[N09] 栈与队列
来源：http://dali.yj20258.top/Article/details/gt2rzufqxdy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.birdmap.top/Article/details/gt2woiqlmcz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sxryk.cn/Article/details/gt2menpswbl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2itqyaynz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xylfe.cn/Article/details/gt2hheikzyu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.9152youxi.cn/Article/details/gt2tvudkoxw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sufxvd.cn/Article/details/gt2yjwdedqv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmkgwfc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.bjfxy.top/Article/details/gt2hsmvewra.html

[N10] 链表节点定义
来源：http://dali.xziqi.cn/Article/details/gt2pyxqhpah.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuanzx.com/Article/details/gt2soudfmsz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.0kj1m.cn/Article/details/gt2ekcrryqd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hfpthk.cn/Article/details/gt2mbmeaopk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tian-w.cn/Article/details/gt2jcieoswe.html

Java: class Node { int v; Node next; }
来源：http://dali.gogol.net.cn/Article/details/gt2gqtoeitp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xziqi.cn/Article/details/gt2mnlqpemk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnxiangtu.top/Article/details/gt2clycxzvv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tianlin.xyz/Article/details/gt2asuayxvj.html

[N11] 二叉树中序遍历
来源：http://dali.hysaishi.cn/Article/details/gt2xdjibdoa.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sysykeji.top/Article/details/gt2gwrlnpfo.html

PHP:  // 手写递归函数
来源：http://dali.svipenyu.cn/Article/details/gt2moucqzjc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hfsuhqvb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gt2bxjedwnr.html

Java: // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gt2fgtzwyin.html

Go:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gt2zkgdkipg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hongshengwenyu.top/Article/details/gt2ffjwseqs.html

C#:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gt2zvzpjrip.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cqqwz.cn/Article/details/gt2ugtosual.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.mhx1999.top/Article/details/gt2pyxyzejw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.bjfxy.top/Article/details/gt2ytntynah.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhengqikj.top/Article/details/gt2okpbzzqm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gt2gulcijbf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gt2cfjdlwgx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hysaishi.cn/Article/details/gt2cqslwjeu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenzaomai.com/Article/details/gt2eqjcmkrl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gt2gadspxmo.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2qbmtrodv.html

O. 并发与异步
来源：http://dali.gaohongyu789.top/Article/details/gt2fzvpnrgf.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2zqretfbo.html

[O01] 启动一个线程
来源：http://dali.cdnleiting.top/Article/details/gt2urzigpsx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuanzhike.top/Article/details/gt2xipzivpz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jianghu66.top/Article/details/gt2mnfswvjs.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hywenlv.cn/Article/details/gt2ygxbwmyh.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gt2osxclhoo.html

Java: new Thread(() -> f()).start()
来源：http://dali.smart0.xyz/Article/details/gt2axcredso.html

Go:   go f()
来源：http://dali.sufxvd.cn/Article/details/gt2uwgypgms.html

Ruby: Thread.new { f }
来源：http://dali.0kj1m.cn/Article/details/gt2qnviukkg.html

C#:   Task.Run(() => F());
来源：http://dali.0kj1m.cn/Article/details/gt2krcfolts.html

[O02] 使用线程池
来源：http://dali.zhoulong.xyz/Article/details/gt2fkgqeeit.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hammf.cn/Article/details/gt2wawsjqtr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.birdmap.top/Article/details/gt2rbqqryhg.html

JS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gt2qhgrfcpl.html

TS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gt2cifwvqrg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.snrcjt.cn/Article/details/gt2vutvfvea.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gaohongyu789.top/Article/details/gt2fuqjcbqf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhixingplan.top/Article/details/gt2qrvhuesd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.aizwys.cn/Article/details/gt2ndaaxxni.html

[O03] 加锁保护共享数据
来源：http://dali.haohaochexian.top/Article/details/gt2hboncagd.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vuttiwtq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eworvlnd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fuqgrfrl.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gt2irhypsmt.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgufenzy.top/Article/details/gt2otqfnnfs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.meibo888.top/Article/details/gt2iuobzmle.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cdnleiting.top/Article/details/gt2cmbzmhxb.html

C#:   lock (gate) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gt2aziubxda.html

[O04] 定义异步函数并等待
来源：http://dali.jlsjyb.cn/Article/details/gt2yvcgmmjf.html

Py:   async def f():⏎    await g()
来源：http://dali.guannengcc.top/Article/details/gt2lbdisuks.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.iojbl.cn/Article/details/gt2chjpmnva.html

JS:   async function f() { await g(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2kuvccvek.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sweek.top/Article/details/gt2lvvjnmzo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ppjwa.cn/Article/details/gt2ygzzdezr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ykifalau.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhiwuduotai.top/Article/details/gt2svuwafsx.html

C#:   async Task F() { await G(); }
来源：http://dali.dianchejie.cn/Article/details/gt2nkdymjfo.html

[O05] 并发执行并等待全部完成
来源：http://dali.redwolf501.top/Article/details/gt2dinuvvqa.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xylfe.cn/Article/details/gt2uxcvvdvs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenjidiqi.icu/Article/details/gt2sactrqab.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigfzy.top/Article/details/gt2vmyvmezy.html

TS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gt2cccfvshi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ybcxt.top/Article/details/gt2jietflii.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj20258.top/Article/details/gt2dwkxmioy.html

Ruby: threads.map(&:join)
来源：http://dali.dashuyun.cn/Article/details/gt2dixlbffr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuanzx.com/Article/details/gt2qgssnwsh.html

[O06] 使用进程池
来源：http://dali.zhiwuduotai.top/Article/details/gt2siyluioj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cqqwz.cn/Article/details/gt2oeelebwi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tianlin.xyz/Article/details/gt2gkrargez.html

JS:   // child_process / cluster 模块
来源：http://dali.guowangkeji.top/Article/details/gt2qkoutnmz.html

TS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gt2hwhoyxfz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258888.top/Article/details/gt2evyaklre.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gogol.net.cn/Article/details/gt2ihemftha.html

Ruby: // fork 块
来源：http://dali.shzxlz.cn/Article/details/gt2yygbotvh.html

C#:   Parallel.For
来源：http://dali.tian-w.cn/Article/details/gt2rpjyxori.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2fxkbqyou.html

P. 常用工具函数
来源：http://dali.yanxiufei.cn/Article/details/gt2apjkwemo.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2ypmhwxxb.html

[P01] 生成 UUID
来源：http://dali.zhoulong.xyz/Article/details/gt2ijdivdwl.html

Py:   str(uuid.uuid4())
来源：http://dali.zhengqikj.top/Article/details/gt2qnbwxwpi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zycfv.cn/Article/details/gt2obxvuvdd.html

JS:   crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gt2qmmnruhz.html

TS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gt2kdquzyaw.html

Java: UUID.randomUUID().toString()
来源：http://dali.fengsongda.top/Article/details/gt2udpokznn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shzxlz.cn/Article/details/gt2kclymhnd.html

Ruby: SecureRandom.uuid
来源：http://dali.yueranfly.top/Article/details/gt2flnsntoq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xziqi.cn/Article/details/gt2gxxwdsxp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cqqwz.cn/Article/details/gt2gxxkziun.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.dianchejie.cn/Article/details/gt2lfqhgjzj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.andypj.xyz/Article/details/gt2aansbobl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.smart0.xyz/Article/details/gt2tneiztrc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangdashe.top/Article/details/gt2eggyzhcm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sufxvd.cn/Article/details/gt2wetvdkyp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gzhubu.top/Article/details/gt2orzmsmsa.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2adtbufau.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.vqdsnc.cn/Article/details/gt2plmgdyls.html

[P03] 生成短随机字符串
来源：http://dali.yj20258888.top/Article/details/gt2bpwudcnv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2edqdbbjk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.snrcjt.cn/Article/details/gt2xqwxkagx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gt2dqxadutc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gt2qbwzwvnu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigufen.top/Article/details/gt2fjtiikhm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.316326.xyz/Article/details/gt2xvuhcnmu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.smart0.xyz/Article/details/gt2fgtfkmxt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xuetiantiany.cn/Article/details/gt2immzhbny.html

[P04] 求长度
来源：http://dali.cashguo.top/Article/details/gt2oahldpxv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cheryme.top/Article/details/gt2fsmrbjlo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gt2jchfsnim.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258.top/Article/details/gt2vsoukhxc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qwrkvmja.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xylfe.cn/Article/details/gt2ghxrnfee.html

Go:   len(arr);  len(m)
来源：http://dali.jyoumei.cn/Article/details/gt2cnzuwtzo.html

Ruby: x.length;  x.size
来源：http://dali.dashuyun.cn/Article/details/gt2dyxpszds.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gt2dryzjodx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daxiang520.top/Article/details/gt2rotpzyut.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rabfdqtt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xuetiantiany.cn/Article/details/gt2dzpofamr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigufen.top/Article/details/gt2vzlcvpms.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fengsongda.top/Article/details/gt2gctrpftf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gzhubu.top/Article/details/gt2uirfarnh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhengqikj.top/Article/details/gt2whxizxwl.html

Ruby: a == b
来源：http://dali.pycfn.com/Article/details/gt2rdwvkeyq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenlongwang.top/Article/details/gt2uhshpvct.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hammf.cn/Article/details/gt2ozkrjuyo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinqigufen.top/Article/details/gt2acdtgzyk.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2dyfnqowe.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gogol.net.cn/Article/details/gt2ztbgyxsb.html

TS:   if (x == null) {}
来源：http://dali.sweek.top/Article/details/gt2htvkskse.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zufzhqbx.html

Go:   if x == nil {}
来源：http://dali.cheryme.top/Article/details/gt2bixrsmgw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hnxiangtu.top/Article/details/gt2rxtoiqck.html

C#:   if (x is null) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2pywsaabr.html

[P07] 防抖与节流
来源：http://dali.tanke756.top/Article/details/gt2kuygoebl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aizwys.cn/Article/details/gt2nngkrfyg.html


<!-- 参考信息 -->