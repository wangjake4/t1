代发 wailian999

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yangfankeji.com/Article/details/gt2mejnnlxy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangdashe.top/Article/details/gt2byisokvm.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2awwqzuii.html

M. 命令行 / 进程 / 环境
来源：http://dali.birdmap.top/Article/details/gt2aqrntotw.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2arpmncyi.html

[M01] 读取命令行参数
来源：http://dali.yj202588.top/Article/details/gt2udcugkto.html

Py:   sys.argv[1:]
来源：http://dali.hammf.cn/Article/details/gt2wvqbtqtl.html

PHP:  $argv;  $argc;
来源：http://dali.cdnleiting.top/Article/details/gt2ckpyjyyj.html

JS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gt2xvzyedwe.html

TS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gt2dirfjreb.html

Java: args 数组（main 方法参数）
来源：http://dali.guowangkeji.top/Article/details/gt2deetvyyq.html

Go:   os.Args[1:]
来源：http://dali.ybcxt.top/Article/details/gt2stdlhxjs.html

Ruby: ARGV
来源：http://dali.zdqjudy.top/Article/details/gt2dzistils.html

C#:   args 数组（Main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gt2tnxxefon.html

[M02] 读取环境变量
来源：http://dali.yvedp.cn/Article/details/gt2tfulabeh.html

Py:   os.environ.get("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gt2ouugiyiq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gt2uojlmdww.html

JS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gt2kzeugklj.html

TS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gt2pnuccmjq.html

Java: System.getenv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gt2wvjyiwfn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cashguo.top/Article/details/gt2abyhltoy.html

Ruby: ENV["HOME"]
来源：http://dali.yj20258888.top/Article/details/gt2egcgzojt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cashguo.top/Article/details/gt2viwukkkk.html

[M03] 执行外部命令
来源：http://dali.yj20258888.top/Article/details/gt2qtnppfmz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dashuyun.cn/Article/details/gt2zosgzfyd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.redwolf501.top/Article/details/gt2zqmxbjvl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.c1oappe.top/Article/details/gt2jxhhvpdx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gt2pkgkyise.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.kuanghao11.cn/Article/details/gt2dtoucnta.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.9152youxi.cn/Article/details/gt2tpptmbmo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258888.top/Article/details/gt2lnveenlo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hammf.cn/Article/details/gt2qclsxcom.html

[M04] 获取当前工作目录
来源：http://dali.jiagoushi.top/Article/details/gt2dgzdufcw.html

Py:   os.getcwd()
来源：http://dali.birdmap.top/Article/details/gt2vqspedxv.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqourlt.html

JS:   process.cwd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2nijsdqyn.html

TS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2qhaiauvt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ehwqpu.com/Article/details/gt2supyxmki.html

Go:   os.Getwd()
来源：http://dali.ehwqpu.com/Article/details/gt2cjfzvhbp.html

Ruby: Dir.pwd
来源：http://dali.cheryme.top/Article/details/gt2pupcjrpl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xziqi.cn/Article/details/gt2kovrggck.html

[M05] 设置退出码
来源：http://dali.zhoulong.xyz/Article/details/gt2fytdosoe.html

Py:   sys.exit(1)
来源：http://dali.guannengcc.top/Article/details/gt2ysvmaabv.html

PHP:  exit(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wetthnux.html

JS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gt2mxdmgsko.html

TS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2rsjkfvwd.html

Java: System.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2wmbeiyse.html

Go:   os.Exit(1)
来源：http://dali.tanke756.top/Article/details/gt2qktlbjvd.html

Ruby: exit 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2tkqjijqn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhiwuduotai.top/Article/details/gt2aaawiymf.html

[M06] 向标准错误输出
来源：http://dali.gogol.net.cn/Article/details/gt2tfhpiolx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.andypj.xyz/Article/details/gt2afaurpyw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.andypj.xyz/Article/details/gt2mrulfehc.html

JS:   console.error("err")
来源：http://dali.gotoacloud.top/Article/details/gt2yqivcxhd.html

TS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gt2wmdllpxa.html

Java: System.err.println("err")
来源：http://dali.ehwqpu.com/Article/details/gt2egvhzeju.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.meibo888.top/Article/details/gt2tmkzipbi.html

Ruby: warn "err"
来源：http://dali.gotoacloud.top/Article/details/gt2uhtoaztm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.havefunace.top/Article/details/gt2ojtbkfey.html

[M07] 判断是否为主入口
来源：http://dali.nwbrower.top/Article/details/gt2yosryfev.html

Py:   if __name__ == "__main__":
来源：http://dali.shangyingyoupin.top/Article/details/gt2hdksnjed.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxuanxn.top/Article/details/gt2gegzcyez.html

JS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gt2yyxsybqx.html

TS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gt2pzapuqws.html

Java: public static void main(String[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fzegbnux.html

Go:   func main()
来源：http://dali.snrcjt.cn/Article/details/gt2anjfielw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aioqewte.html

C#:   static void Main(string[] args)
来源：http://dali.tian-w.cn/Article/details/gt2kchoxpdi.html

[M08] 获取系统与运行时信息
来源：http://dali.andypj.xyz/Article/details/gt2otiqohns.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cheryme.top/Article/details/gt2kftmryhu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gotoacloud.top/Article/details/gt2efytpotp.html

JS:   process.platform;  process.version
来源：http://dali.svipenyu.cn/Article/details/gt2omngrabw.html

TS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gt2lrgafnmx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuanzhike.top/Article/details/gt2xivlbzvy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.bjfxy.top/Article/details/gt2lqnkijva.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hongshengwenyu.top/Article/details/gt2ahpxofiv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sxryk.cn/Article/details/gt2aoajgrod.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2mrwlpygt.html

N. 数据结构与算法
来源：http://dali.xylfe.cn/Article/details/gt2aexhsssi.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2huzczotv.html

[N01] 二分查找（有序数组）
来源：http://dali.nwbrower.top/Article/details/gt2bokpftsp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2zynixtsp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yueranfly.top/Article/details/gt2zepbbxoi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sxryk.cn/Article/details/gt2nkilpjyz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gt2rwpoqtwr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gt2eaqwzvgi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2ihchwden.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cdnleiting.top/Article/details/gt2gmfsnuet.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gt2isasjtbp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hfpthk.cn/Article/details/gt2nvypsnit.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gt2zefzosrz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zycfv.cn/Article/details/gt2qxzkyroh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gt2uonxzvxk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gt2anuivabd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.redwolf501.top/Article/details/gt2yvmahrnx.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2omilklik.html

Ruby: arr.sort
来源：http://dali.nanxuanxn.top/Article/details/gt2etqfzamy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xylfe.cn/Article/details/gt2xywlqnme.html

[N03] 快速排序（分治示例）
来源：http://dali.zhiwuduotai.top/Article/details/gt2lvmztksx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wfkttkho.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cheryme.top/Article/details/gt2xxthjdaz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.quarkkingdee.top/Article/details/gt2uubtfgiz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gt2lafueqtq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.redwolf501.top/Article/details/gt2dkxclkes.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.quarkkingdee.top/Article/details/gt2nvsltlzt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fzhhl.top/Article/details/gt2urjnzpog.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhoulong.xyz/Article/details/gt2wcodfpwq.html

[N04] 斐波那契数列
来源：http://dali.yanxiufei.cn/Article/details/gt2hjeyirxv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gt2ajfwjsjo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fzhhl.top/Article/details/gt2wpvwuwzu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2nbvlapxy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gt2xtuopnvu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.bjfxy.top/Article/details/gt2ybfrmpqn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zwtjvtmx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gt2opjfgjsn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2hqusilve.html

[N05] 最大公约数
来源：http://dali.ivvv.top/Article/details/gt2cxzggtyh.html

Py:   math.gcd(a, b)
来源：http://dali.wangdashe.top/Article/details/gt2zjrrjtft.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.quarkkingdee.top/Article/details/gt2zfgpctod.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gt2udneeprz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2enhkyokz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.iojbl.cn/Article/details/gt2fwmenptd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnqzz.top/Article/details/gt2tbgwmqdr.html

Ruby: a.gcd(b)
来源：http://dali.daxiang520.top/Article/details/gt2xawxpsjy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gaohongyu789.top/Article/details/gt2ynctajta.html

[N06] 判断回文字符串
来源：http://dali.xinyue.icu/Article/details/gt2kttlndsn.html

Py:   s == s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gt2lxfrvzjo.html

PHP:  $s === strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gt2hyfusfmq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gt2pbfqnxla.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gt2unbhzsgp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shangyingyoupin.top/Article/details/gt2gismiele.html

Go:   // 双指针从两端比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rauoxnxh.html

Ruby: s == s.reverse
来源：http://dali.wangdashe.top/Article/details/gt2tladygab.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gt2wibfpzio.html

[N07] 两数之和（返回下标）
来源：http://dali.aibaodan.cn/Article/details/gt2eygfwfpm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jqgufenzy.top/Article/details/gt2tbsqvzga.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ybcxt.top/Article/details/gt2rxahvrdk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hfpthk.cn/Article/details/gt2dwslbowy.html

TS:   // 手写 Map<string, number>
来源：http://dali.hammf.cn/Article/details/gt2kczolqkp.html

Java: // 手写 HashMap
来源：http://dali.yj20258888.top/Article/details/gt2zodzpnvz.html

Go:   // 手写 map[int]int
来源：http://dali.ppjwa.cn/Article/details/gt2wzbuvebh.html

Ruby: // 手写 Hash
来源：http://dali.cdnleiting.top/Article/details/gt2vkxmaccl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eptbwily.html

[N08] 生成全排列
来源：http://dali.dashuyun.cn/Article/details/gt2nsgeibpq.html

Py:   itertools.permutations(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dutyadss.html

PHP:  // 手写递归交换
来源：http://dali.tian-w.cn/Article/details/gt2qsffkfrh.html

JS:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gt2omixwswu.html

TS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2mmtrfmfz.html

Java: // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gt2zvoeinuj.html

Go:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2eqavnzdx.html

Ruby: arr.permutation.to_a
来源：http://dali.shangyingyoupin.top/Article/details/gt2mlmoofam.html

C#:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gt2pvblopdh.html

[N09] 栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gt2whktxmzw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shzxlz.cn/Article/details/gt2ayvyxoif.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gt2vyxanotf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2frbdsqjv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.pengpengdd.cyou/Article/details/gt2gyjpuzzm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuanzhike.top/Article/details/gt2juakgcra.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kuawrale.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gt2nhvhozmr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nwbrower.top/Article/details/gt2kfqnsnov.html

[N10] 链表节点定义
来源：http://dali.daria6918.cn/Article/details/gt2kxfcnldx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.iojbl.cn/Article/details/gt2bwyobvia.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.pycfn.com/Article/details/gt2zmhlavnl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.iojbl.cn/Article/details/gt2rflwqpcs.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhongyouzk.top/Article/details/gt2vlpurvox.html

Java: class Node { int v; Node next; }
来源：http://dali.nanxinkj.top/Article/details/gt2ilipbugf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yanxiufei.cn/Article/details/gt2qcpsdsrx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mduwucxo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bbcmmpit.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcoluen.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shangyingyoupin.top/Article/details/gt2jmekngks.html

PHP:  // 手写递归函数
来源：http://dali.tian-w.cn/Article/details/gt2akwoorwx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gt2kyrgiwjg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2itwynftk.html

Java: // 手写递归
来源：http://dali.smart0.xyz/Article/details/gt2vdxztkgm.html

Go:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gt2gksvzlaj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.havefunace.top/Article/details/gt2yvbddfpr.html

C#:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gt2veiujdlu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhongyouzk.top/Article/details/gt2gwmbxeik.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.vqdsnc.cn/Article/details/gt2ddmidhto.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gaohongyu789.top/Article/details/gt2loauiqxq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gt2ujlkjdxf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnxiangtu.top/Article/details/gt2atuginwl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gt2jyxyucuy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.andypj.xyz/Article/details/gt2sthefcsm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenlongwang.top/Article/details/gt2emlykcsx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sweek.top/Article/details/gt2uztmowqe.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2tjjcjdwa.html

O. 并发与异步
来源：http://dali.bjfxy.top/Article/details/gt2xsrjidgk.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2ursenmxi.html

[O01] 启动一个线程
来源：http://dali.tanke756.top/Article/details/gt2ovmmryty.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gzhubu.top/Article/details/gt2yvnnhzzd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.pycfn.com/Article/details/gt2cocodmdo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenlongwang.top/Article/details/gt2mepjomsm.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gt2srtisisk.html

Java: new Thread(() -> f()).start()
来源：http://dali.cdnleiting.top/Article/details/gt2lfrsaynq.html

Go:   go f()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ecciaeyu.html

Ruby: Thread.new { f }
来源：http://dali.sysykeji.top/Article/details/gt2caxbjfec.html

C#:   Task.Run(() => F());
来源：http://dali.gaohongyu789.top/Article/details/gt2yggmxgwa.html

[O02] 使用线程池
来源：http://dali.chenzaomai.com/Article/details/gt2anvhimca.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhoulong.xyz/Article/details/gt2ggntjpym.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shzxlz.cn/Article/details/gt2jmibzsbh.html

JS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gt2wbpgqzts.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yoejbqor.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigfzy.top/Article/details/gt2gxeuukgg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2baqwlrjw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yongpay.top/Article/details/gt2pvyetffu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhixingplan.top/Article/details/gt2xxaozdog.html

[O03] 加锁保护共享数据
来源：http://dali.jiagoushi.top/Article/details/gt2dkyhlmkg.html

Py:   with lock: shared += 1
来源：http://dali.fengsongda.top/Article/details/gt2wpmegxbe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuxming.cn/Article/details/gt2axxconek.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guannengcc.top/Article/details/gt2cfinobst.html

TS:   // 同 JS
来源：http://dali.sysykeji.top/Article/details/gt2tmfqgjtg.html

Java: synchronized (this) { shared++; }
来源：http://dali.aibaodan.cn/Article/details/gt2jmwffhwa.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ydzc1.top/Article/details/gt2fllkcmam.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.quarkkingdee.top/Article/details/gt2vhihautm.html

C#:   lock (gate) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gt2jegybiaq.html

[O04] 定义异步函数并等待
来源：http://dali.nanxinkj.top/Article/details/gt2hapmhgxd.html

Py:   async def f():⏎    await g()
来源：http://dali.xylfe.cn/Article/details/gt2ompsbskq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenjidiqi.icu/Article/details/gt2mfcnucgl.html

JS:   async function f() { await g(); }
来源：http://dali.daria6918.cn/Article/details/gt2jukaqkis.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.wangdashe.top/Article/details/gt2itizzqmr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.316326.xyz/Article/details/gt2xjhgqiem.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cheryme.top/Article/details/gt2xfhdqsjq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gaohongyu789.top/Article/details/gt2opugmdzl.html

C#:   async Task F() { await G(); }
来源：http://dali.xylfe.cn/Article/details/gt2stgnqiow.html

[O05] 并发执行并等待全部完成
来源：http://dali.svipenyu.cn/Article/details/gt2xeoddllh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinqigfzy.top/Article/details/gt2ycewjodt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.kuanghao11.cn/Article/details/gt2mjdxndkt.html

JS:   await Promise.all(tasks)
来源：http://dali.cdnleiting.top/Article/details/gt2wnpdupzs.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258.top/Article/details/gt2gtfbeeuj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.9152youxi.cn/Article/details/gt2gzmvngww.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.9152youxi.cn/Article/details/gt2esruhxhy.html

Ruby: threads.map(&:join)
来源：http://dali.c1oappe.top/Article/details/gt2njsorngo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mochrdvn.html

[O06] 使用进程池
来源：http://dali.316326.xyz/Article/details/gt2qhpubgum.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenlongwang.top/Article/details/gt2qffsoeek.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2usnmoveu.html

JS:   // child_process / cluster 模块
来源：http://dali.chenzaomai.com/Article/details/gt2xghsaxjl.html

TS:   // child_process / cluster 模块
来源：http://dali.wangdashe.top/Article/details/gt2mcuebhrt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.redwolf501.top/Article/details/gt2oxzzvixb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.feifeiyinyue.top/Article/details/gt2jwxztope.html

Ruby: // fork 块
来源：http://dali.pengpengdd.cyou/Article/details/gt2bydahrsx.html

C#:   Parallel.For
来源：http://dali.bjfxy.top/Article/details/gt2qmfeahng.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ielbaywu.html

P. 常用工具函数
来源：http://dali.sufxvd.cn/Article/details/gt2kuzjjjvw.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2hoskownt.html

[P01] 生成 UUID
来源：http://dali.daria6918.cn/Article/details/gt2dzaxwhmr.html

Py:   str(uuid.uuid4())
来源：http://dali.aizwys.cn/Article/details/gt2zcmoockd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hnqzz.top/Article/details/gt2doquperk.html

JS:   crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gt2pprubnhc.html

TS:   crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gt2oifruqrz.html

Java: UUID.randomUUID().toString()
来源：http://dali.ivvv.top/Article/details/gt2bddzefde.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yawtoceb.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigufen.top/Article/details/gt2ldbdeehx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhongyouzk.top/Article/details/gt2kjbrxrjc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pycfn.com/Article/details/gt2yrmvpaqk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jyoumei.cn/Article/details/gt2vqumjley.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sysykeji.top/Article/details/gt2yunohjxj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.svipenyu.cn/Article/details/gt2wndovlbt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.haohaochexian.top/Article/details/gt2fqssqyic.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.c1oappe.top/Article/details/gt2zbxlzkto.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ybcxt.top/Article/details/gt2bydgauvr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2pwhtmgfs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yanxiufei.cn/Article/details/gt2zksbopsc.html

[P03] 生成短随机字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lmohmocx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.smart0.xyz/Article/details/gt2wwjugnlv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gogol.net.cn/Article/details/gt2kwmweqng.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gt2htrroptm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gt2ctknqnjw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shzxlz.cn/Article/details/gt2mujmqweg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jianghu66.top/Article/details/gt2wfloiokw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cucudq.cn/Article/details/gt2kitnjebm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gzhubu.top/Article/details/gt2tlosmauk.html

[P04] 求长度
来源：http://dali.wangdashe.top/Article/details/gt2cgyvlqsi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhengqikj.top/Article/details/gt2xbwmggyo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gt2gptkbika.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gt2nrghdldd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuanzx.com/Article/details/gt2dxbhsbml.html

Java: list.size();  map.size();  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gt2gaxxlukf.html

Go:   len(arr);  len(m)
来源：http://dali.wangshuangyany.cn/Article/details/gt2askcckal.html

Ruby: x.length;  x.size
来源：http://dali.cheryme.top/Article/details/gt2oxkqrudh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.316326.xyz/Article/details/gt2dsoixrjq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.pycfn.com/Article/details/gt2rljgicji.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shangyingyoupin.top/Article/details/gt2sbflktam.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.feifeiyinyue.top/Article/details/gt2zorsxqiz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenzaomai.com/Article/details/gt2woajxjlb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tianlin.xyz/Article/details/gt2gcowpvta.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cucudq.cn/Article/details/gt2ivfoylwt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sweek.top/Article/details/gt2vbvbihll.html

Ruby: a == b
来源：http://dali.jqgufenzy.top/Article/details/gt2sduhdqqg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lukmwaay.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.guannengcc.top/Article/details/gt2iltkfxpq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxuanxn.top/Article/details/gt2fkjdsfsx.html

PHP:  if (empty($x)) {}
来源：http://dali.guowangkeji.top/Article/details/gt2vtodtnxk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnxiangtu.top/Article/details/gt2fgbvnbkt.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rkbhllpz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2cxpdjssf.html

Go:   if x == nil {}
来源：http://dali.zhengqikj.top/Article/details/gt2oihmeuqj.html


<!-- 参考信息 -->