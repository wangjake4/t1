代发 wailian999

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cdnleiting.top/Article/details/gt2lgmvymcy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aizwys.cn/Article/details/gt2kknhubwn.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2cniyldfx.html

M. 命令行 / 进程 / 环境
来源：http://dali.guowangkeji.top/Article/details/gt2dnxvcxvh.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2ffgddrgv.html

[M01] 读取命令行参数
来源：http://dali.fzhhl.top/Article/details/gt2pzjsvpge.html

Py:   sys.argv[1:]
来源：http://dali.nwbrower.top/Article/details/gt2wosuldei.html

PHP:  $argv;  $argc;
来源：http://dali.c1oappe.top/Article/details/gt2whorrjki.html

JS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gt2pwbnoudm.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gt2kaeqoasp.html

Java: args 数组（main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gt2qtaumgpe.html

Go:   os.Args[1:]
来源：http://dali.zycfv.cn/Article/details/gt2oorojscj.html

Ruby: ARGV
来源：http://dali.jinqigufen.top/Article/details/gt2nhvpkvbn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gt2jvnxukdn.html

[M02] 读取环境变量
来源：http://dali.sweek.top/Article/details/gt2zthpvppm.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2jfgswbif.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gt2upykmctc.html

JS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gt2ynpmcsib.html

TS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gt2ofajuodf.html

Java: System.getenv("HOME")
来源：http://dali.xziqi.cn/Article/details/gt2dydfsjwl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2gjeqnbql.html

Ruby: ENV["HOME"]
来源：http://dali.jqgfzy.top/Article/details/gt2ogyhxacu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ovvblbrq.html

[M03] 执行外部命令
来源：http://dali.xziqi.cn/Article/details/gt2dzbojcym.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yangfankeji.com/Article/details/gt2ruwksnul.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenzaomai.com/Article/details/gt2kfessaaa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gt2bnhmbpvo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gt2pcwvfgrr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.meibo888.top/Article/details/gt2nkzdvtsv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.vqdsnc.cn/Article/details/gt2jkhvswmn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jlsjyb.cn/Article/details/gt2xdnbdoog.html

C#:   Process.Start("ls", "-l");
来源：http://dali.smart0.xyz/Article/details/gt2vtlwuxjd.html

[M04] 获取当前工作目录
来源：http://dali.dianchejie.cn/Article/details/gt2agmmdttc.html

Py:   os.getcwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2swlmjyyg.html

PHP:  getcwd();
来源：http://dali.chenlongwang.top/Article/details/gt2powrabvo.html

JS:   process.cwd()
来源：http://dali.svipenyu.cn/Article/details/gt2hpvubxle.html

TS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gt2xvicxzms.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jlsjyb.cn/Article/details/gt2hsocsrkv.html

Go:   os.Getwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2fxkmzkre.html

Ruby: Dir.pwd
来源：http://dali.xziqi.cn/Article/details/gt2jecnlbgj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sxryk.cn/Article/details/gt2ecihqoml.html

[M05] 设置退出码
来源：http://dali.cqqwz.cn/Article/details/gt2ndcppheo.html

Py:   sys.exit(1)
来源：http://dali.fzhhl.top/Article/details/gt2lzmkqmmj.html

PHP:  exit(1);
来源：http://dali.zhongyouzk.top/Article/details/gt2lvskfbtd.html

JS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gt2ukkzvzkn.html

TS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2yfzqypas.html

Java: System.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gt2hsfcchyv.html

Go:   os.Exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2gxqwkrhx.html

Ruby: exit 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2chkwjcma.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shuidangran.top/Article/details/gt2djvibyom.html

[M06] 向标准错误输出
来源：http://dali.yvedp.cn/Article/details/gt2dkpofqfj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vohuzfja.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yqlupjyc.html

JS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yfibjmxc.html

TS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gt2sbsbzsll.html

Java: System.err.println("err")
来源：http://dali.yonumen.top/Article/details/gt2okdfpkpj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tianlin.xyz/Article/details/gt2eydcwtzi.html

Ruby: warn "err"
来源：http://dali.redwolf501.top/Article/details/gt2aafoyjzt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jlsjyb.cn/Article/details/gt2hdcvqztl.html

[M07] 判断是否为主入口
来源：http://dali.nwbrower.top/Article/details/gt2fyogyffy.html

Py:   if __name__ == "__main__":
来源：http://dali.jiagoushi.top/Article/details/gt2ewmkxkra.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2vyglalba.html

JS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gt2xyphkifv.html

TS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gt2kipwslng.html

Java: public static void main(String[] args)
来源：http://dali.zycfv.cn/Article/details/gt2hxoystnq.html

Go:   func main()
来源：http://dali.quarkkingdee.top/Article/details/gt2nnlzmlzy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dianchejie.cn/Article/details/gt2bveqsflz.html

C#:   static void Main(string[] args)
来源：http://dali.svipenyu.cn/Article/details/gt2gdbnvwzr.html

[M08] 获取系统与运行时信息
来源：http://dali.ehwqpu.com/Article/details/gt2eqnnymzy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdajadyp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.kuanghao11.cn/Article/details/gt2vwvtgnqu.html

JS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gt2mkovoimd.html

TS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gt2ifsarqrk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gogol.net.cn/Article/details/gt2bbujqpcw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.meibo888.top/Article/details/gt2oxvbormp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xuanzx.com/Article/details/gt2tqiympmz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ppjwa.cn/Article/details/gt2cbotyydu.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2rhxatnfk.html

N. 数据结构与算法
来源：http://dali.andypj.xyz/Article/details/gt2kkmnujfh.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2mkvwwatj.html

[N01] 二分查找（有序数组）
来源：http://dali.jianghu66.top/Article/details/gt2ndabztzu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vveygizm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.0kj1m.cn/Article/details/gt2kifmhfar.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ncagjdxj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gt2jaaqqvbd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2xaconyry.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2xnxffsgt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2axninadr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2iciqevgo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jlsjyb.cn/Article/details/gt2zuieoxgh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuanzhike.top/Article/details/gt2vwnpqhwb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vumfuhsn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gt2oqbiiaol.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzngprgx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tian-w.cn/Article/details/gt2utrbmtoq.html

Go:   slices.Sort(arr)
来源：http://dali.wangdashe.top/Article/details/gt2hfddzfgy.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gt2pdftehbs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guowangkeji.top/Article/details/gt2addbgvej.html

[N03] 快速排序（分治示例）
来源：http://dali.316326.xyz/Article/details/gt2tveznlhm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj202588.top/Article/details/gt2oqwfoxsm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.andypj.xyz/Article/details/gt2qsmksdes.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gt2yksllleg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jyoumei.cn/Article/details/gt2uuyziekt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.pengpengdd.cyou/Article/details/gt2aihiefnl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.andypj.xyz/Article/details/gt2ungugugj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yonumen.top/Article/details/gt2wmljerzn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nwbrower.top/Article/details/gt2jfqhcvgj.html

[N04] 斐波那契数列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yqjpysij.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yueranfly.top/Article/details/gt2zkekpimu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tian-w.cn/Article/details/gt2impegult.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gt2yccycbrz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2attisulj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2fbnkdjfl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ehwqpu.com/Article/details/gt2mggzebne.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gt2srxfslxp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2pcuujbnn.html

[N05] 最大公约数
来源：http://dali.smart0.xyz/Article/details/gt2gfslpmmw.html

Py:   math.gcd(a, b)
来源：http://dali.sweek.top/Article/details/gt2fvrxegbu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guannengcc.top/Article/details/gt2unhiagjy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gt2snsyfduk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gt2ebukhzds.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnqzz.top/Article/details/gt2dxlihfqw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuetiantiany.cn/Article/details/gt2rklsbkud.html

Ruby: a.gcd(b)
来源：http://dali.gzhubu.top/Article/details/gt2esoheztg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gogol.net.cn/Article/details/gt2dyelvvbh.html

[N06] 判断回文字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2hcwkwexs.html

Py:   s == s[::-1]
来源：http://dali.xinyue.icu/Article/details/gt2exwxfmit.html

PHP:  $s === strrev($s);
来源：http://dali.sweek.top/Article/details/gt2yllhqujz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gt2mcorsoop.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hdupuqnd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jlsjyb.cn/Article/details/gt2jwmoctry.html

Go:   // 双指针从两端比较
来源：http://dali.hnxiangtu.top/Article/details/gt2jloiofyv.html

Ruby: s == s.reverse
来源：http://dali.fzhhl.top/Article/details/gt2cdtxvpxg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gt2tteehvhu.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258.top/Article/details/gt2fxgwqhta.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.vqdsnc.cn/Article/details/gt2lrurwppy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yangfankeji.com/Article/details/gt2ivhahusi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dianchejie.cn/Article/details/gt2jnzuvhhy.html

TS:   // 手写 Map<string, number>
来源：http://dali.snrcjt.cn/Article/details/gt2ydkomkfi.html

Java: // 手写 HashMap
来源：http://dali.jyoumei.cn/Article/details/gt2xacivptp.html

Go:   // 手写 map[int]int
来源：http://dali.ybcxt.top/Article/details/gt2dldyruri.html

Ruby: // 手写 Hash
来源：http://dali.ppjwa.cn/Article/details/gt2zdivrcht.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aibaodan.cn/Article/details/gt2zbunjpdl.html

[N08] 生成全排列
来源：http://dali.0kj1m.cn/Article/details/gt2cgmqfwyv.html

Py:   itertools.permutations(arr)
来源：http://dali.yongpay.top/Article/details/gt2ahulxivc.html

PHP:  // 手写递归交换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ssdotoeb.html

JS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2vaohuluw.html

TS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2tejsajey.html

Java: // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2xlxhpmik.html

Go:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2qvakdynt.html

Ruby: arr.permutation.to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gt2twtftgoo.html

C#:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2iyjupjih.html

[N09] 栈与队列
来源：http://dali.pycfn.com/Article/details/gt2ygaczwix.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gogol.net.cn/Article/details/gt2dylvimlw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gt2fvyyszti.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gt2qbcouynl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shuidangran.top/Article/details/gt2pszqkqih.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.snrcjt.cn/Article/details/gt2btavexhk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxinkj.top/Article/details/gt2nnznymqo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2muqatswa.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.fzhhl.top/Article/details/gt2eelrdjzy.html

[N10] 链表节点定义
来源：http://dali.zhengqikj.top/Article/details/gt2pvfratgj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.redwolf501.top/Article/details/gt2zrplrwes.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yongpay.top/Article/details/gt2dwvlqxgp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.redwolf501.top/Article/details/gt2fblyxatf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ybcxt.top/Article/details/gt2nltmmihy.html

Java: class Node { int v; Node next; }
来源：http://dali.shzxlz.cn/Article/details/gt2uxmqvupa.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ydzc1.top/Article/details/gt2jiqqudxy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oeertanj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pycfn.com/Article/details/gt2ajweskfq.html

[N11] 二叉树中序遍历
来源：http://dali.tian-w.cn/Article/details/gt2wkmcerhh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenzaomai.com/Article/details/gt2kmlvkdaf.html

PHP:  // 手写递归函数
来源：http://dali.xinyue.icu/Article/details/gt2qsdgsbvh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yonumen.top/Article/details/gt2lfklkipd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gt2gaezglkp.html

Java: // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gt2vemrkkev.html

Go:   // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gt2cevznnbe.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgfzy.top/Article/details/gt2erwjibql.html

C#:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gt2mxzdmvrh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.feifeiyinyue.top/Article/details/gt2mbecqmdu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xinyue.icu/Article/details/gt2kxndnyfw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hnxiangtu.top/Article/details/gt2zfwkzjjw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gt2mqaqwgnl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gt2gazjlukn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gt2iklmdmoz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dianchejie.cn/Article/details/gt2iiavnwnv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.bjfxy.top/Article/details/gt2kirvnkji.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gt2bcecocrk.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2rqijmhos.html

O. 并发与异步
来源：http://dali.sweek.top/Article/details/gt2oqkmjref.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2molzhpue.html

[O01] 启动一个线程
来源：http://dali.bjfxy.top/Article/details/gt2azuorjfw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pycfn.com/Article/details/gt2kpnpwenh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sweek.top/Article/details/gt2oajctcdv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.iojbl.cn/Article/details/gt2zlnnbrfo.html

TS:   // 同 JS
来源：http://dali.dashuyun.cn/Article/details/gt2jdigwggm.html

Java: new Thread(() -> f()).start()
来源：http://dali.gogol.net.cn/Article/details/gt2cyygrsjw.html

Go:   go f()
来源：http://dali.shuidangran.top/Article/details/gt2bprmputp.html

Ruby: Thread.new { f }
来源：http://dali.nanxuanxn.top/Article/details/gt2eabwkwnk.html

C#:   Task.Run(() => F());
来源：http://dali.sysykeji.top/Article/details/gt2omfnzlbm.html

[O02] 使用线程池
来源：http://dali.havefunace.top/Article/details/gt2ccsfxcxo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.havefunace.top/Article/details/gt2wyzxflpx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.mhx1999.top/Article/details/gt2nwvxykgv.html

JS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gt2kputmqrl.html

TS:   // worker_threads 线程池
来源：http://dali.vqdsnc.cn/Article/details/gt2ukvhobgn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xziqi.cn/Article/details/gt2lanuuywj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hammf.cn/Article/details/gt2pdikhjfg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hnxiangtu.top/Article/details/gt2qhvjntdw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.svipenyu.cn/Article/details/gt2qyhofrxh.html

[O03] 加锁保护共享数据
来源：http://dali.haohaochexian.top/Article/details/gt2qcsnolku.html

Py:   with lock: shared += 1
来源：http://dali.ivvv.top/Article/details/gt2fbjxsjuc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.316326.xyz/Article/details/gt2hiaiqdos.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.9152youxi.cn/Article/details/gt2jsytfiqs.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxajudn.html

Java: synchronized (this) { shared++; }
来源：http://dali.daxiang520.top/Article/details/gt2mjokqcfe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yvedp.cn/Article/details/gt2ilocdafl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tanke756.top/Article/details/gt2cpxigmzn.html

C#:   lock (gate) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gt2nwpabhiu.html

[O04] 定义异步函数并等待
来源：http://dali.hnxiangtu.top/Article/details/gt2rymgqcey.html

Py:   async def f():⏎    await g()
来源：http://dali.tian-w.cn/Article/details/gt2gjotseiu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2llgreixc.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258.top/Article/details/gt2uyfsirqx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2dgzolwdz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gogol.net.cn/Article/details/gt2oekmmntr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenzaomai.com/Article/details/gt2hyghlxmz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigufen.top/Article/details/gt2lwddskus.html

C#:   async Task F() { await G(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zqjwkbci.html

[O05] 并发执行并等待全部完成
来源：http://dali.hammf.cn/Article/details/gt2inylokbk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.havefunace.top/Article/details/gt2ncrwjexr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.iojbl.cn/Article/details/gt2waqaghwa.html

JS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gt2maibzceo.html

TS:   await Promise.all(tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uwpedcau.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hywenlv.cn/Article/details/gt2pduzdgtc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tanke756.top/Article/details/gt2yxacikve.html

Ruby: threads.map(&:join)
来源：http://dali.smart0.xyz/Article/details/gt2wbctedbt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yonumen.top/Article/details/gt2lmufsqhc.html

[O06] 使用进程池
来源：http://dali.gotoacloud.top/Article/details/gt2cwgzutdh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.bjfxy.top/Article/details/gt2gpyasoxi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jlsjyb.cn/Article/details/gt2kvzukczb.html

JS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gt2loataoyy.html

TS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gt2adnhmrut.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hysaishi.cn/Article/details/gt2hezxxqlo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cqqwz.cn/Article/details/gt2yznlmkiw.html

Ruby: // fork 块
来源：http://dali.gogol.net.cn/Article/details/gt2owslqhgl.html

C#:   Parallel.For
来源：http://dali.zdqjudy.top/Article/details/gt2udsvwihj.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ftmxhxkh.html

P. 常用工具函数
来源：http://dali.tanke756.top/Article/details/gt2jfkehogx.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2cevvvnnc.html

[P01] 生成 UUID
来源：http://dali.sxryk.cn/Article/details/gt2hjuwfypf.html

Py:   str(uuid.uuid4())
来源：http://dali.cucudq.cn/Article/details/gt2zwvgphaj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.pengpengdd.cyou/Article/details/gt2nkdngarz.html

JS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gt2axfyvngf.html

TS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gt2bptforic.html

Java: UUID.randomUUID().toString()
来源：http://dali.cucudq.cn/Article/details/gt2usdfctgu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhongyouzk.top/Article/details/gt2kdegbbqd.html

Ruby: SecureRandom.uuid
来源：http://dali.wangdashe.top/Article/details/gt2tfqjwvwx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jiagoushi.top/Article/details/gt2qowsvvei.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nwbrower.top/Article/details/gt2ruxjtvzu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.316326.xyz/Article/details/gt2cnopvzqs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tianlin.xyz/Article/details/gt2zrtnpadn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daria6918.cn/Article/details/gt2kksumzop.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xinyue.icu/Article/details/gt2pgqurtww.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.haohaochexian.top/Article/details/gt2gsyrlszg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhengqikj.top/Article/details/gt2kkdncgcj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.guowangkeji.top/Article/details/gt2zakkxbjc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhengqikj.top/Article/details/gt2lxsemvel.html

[P03] 生成短随机字符串
来源：http://dali.c1oappe.top/Article/details/gt2xhuzfvra.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhengqikj.top/Article/details/gt2obvvfoot.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.guannengcc.top/Article/details/gt2fkxxmlpi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xziqi.cn/Article/details/gt2qfvobvil.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gt2eugemren.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenlongwang.top/Article/details/gt2sshtiqsj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ivvv.top/Article/details/gt2yjmprsnu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sufxvd.cn/Article/details/gt2idzlertz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuxming.cn/Article/details/gt2ouwfiqtn.html

[P04] 求长度
来源：http://dali.snrcjt.cn/Article/details/gt2ukpufkgi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgufenzy.top/Article/details/gt2auvcndjw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gt2measadhc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gt2urrluqpi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangdashe.top/Article/details/gt2pkesfbet.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sufxvd.cn/Article/details/gt2jbfubyam.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258.top/Article/details/gt2hvtqvput.html

Ruby: x.length;  x.size
来源：http://dali.iojbl.cn/Article/details/gt2slpgplpe.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hammf.cn/Article/details/gt2gbzvqiez.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ydzc1.top/Article/details/gt2mkwwlbpf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fengsongda.top/Article/details/gt2rzsfhryc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aibaodan.cn/Article/details/gt2wjwtzxdf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.andypj.xyz/Article/details/gt2nkywqavh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2csfyvtgt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sweek.top/Article/details/gt2uadsdtoa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.pycfn.com/Article/details/gt2jptgitjy.html

Ruby: a == b
来源：http://dali.zhixingplan.top/Article/details/gt2waaetlyk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sweek.top/Article/details/gt2fdvuttfv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gaohongyu789.top/Article/details/gt2aofxkibo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hongshengwenyu.top/Article/details/gt2vmsrfzaq.html

PHP:  if (empty($x)) {}
来源：http://dali.sysykeji.top/Article/details/gt2yuiyeusr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258.top/Article/details/gt2mzevryvv.html

TS:   if (x == null) {}
来源：http://dali.zhengqikj.top/Article/details/gt2lrbzvgby.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hfpthk.cn/Article/details/gt2zcjfecxk.html

Go:   if x == nil {}
来源：http://dali.hfpthk.cn/Article/details/gt2qztgrbef.html


<!-- 参考信息 -->