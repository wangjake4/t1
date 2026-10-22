代发 wailian999

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hvclfvrk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jianghu66.top/Article/details/gt2jgkgrmyh.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2alfllgdn.html

M. 命令行 / 进程 / 环境
来源：http://dali.gaohongyu789.top/Article/details/gt2tgfsbhgx.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2rmcoawof.html

[M01] 读取命令行参数
来源：http://dali.yueranfly.top/Article/details/gt2keniaxpo.html

Py:   sys.argv[1:]
来源：http://dali.redwolf501.top/Article/details/gt2pbdgprll.html

PHP:  $argv;  $argc;
来源：http://dali.sxryk.cn/Article/details/gt2vuxyvxub.html

JS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gt2gdgroatb.html

TS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gt2gzmscmvj.html

Java: args 数组（main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gt2alzupxwh.html

Go:   os.Args[1:]
来源：http://dali.sweek.top/Article/details/gt2ttwohjfb.html

Ruby: ARGV
来源：http://dali.wangshuangyany.cn/Article/details/gt2ttdvgvht.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gt2zhrvukjk.html

[M02] 读取环境变量
来源：http://dali.yangfankeji.com/Article/details/gt2doqlpvxs.html

Py:   os.environ.get("HOME")
来源：http://dali.nwbrower.top/Article/details/gt2evgwedef.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gt2bcznjtlw.html

JS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gt2vewzvcxk.html

TS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gt2kvozntom.html

Java: System.getenv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gt2eletpcli.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gt2jilixnki.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2owlpjmlt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gpssfoyu.html

[M03] 执行外部命令
来源：http://dali.sufxvd.cn/Article/details/gt2buktbdtz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.vqdsnc.cn/Article/details/gt2pywwkcsi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.smart0.xyz/Article/details/gt2bsobgern.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gt2tdpajsqi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gt2oyynmoue.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wbxzkjeo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.mhx1999.top/Article/details/gt2kdofytku.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.9152youxi.cn/Article/details/gt2lbyfppmr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ivvv.top/Article/details/gt2vqlmbhou.html

[M04] 获取当前工作目录
来源：http://dali.sufxvd.cn/Article/details/gt2pjbkfuhu.html

Py:   os.getcwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bljkinfl.html

PHP:  getcwd();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dowrcpqx.html

JS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gt2ukovhiau.html

TS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gt2olisygke.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.c1oappe.top/Article/details/gt2hxewlgov.html

Go:   os.Getwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uidjklyi.html

Ruby: Dir.pwd
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2txuvseeu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gaohongyu789.top/Article/details/gt2obfnwvuf.html

[M05] 设置退出码
来源：http://dali.cucudq.cn/Article/details/gt2sdzbqdci.html

Py:   sys.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2vvxjazjm.html

PHP:  exit(1);
来源：http://dali.yonumen.top/Article/details/gt2qtufmwnd.html

JS:   process.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gt2byribydv.html

TS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gt2xjixfjcr.html

Java: System.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2ktnxgbdb.html

Go:   os.Exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2uzufepfj.html

Ruby: exit 1
来源：http://dali.xinyue.icu/Article/details/gt2njjgmigr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigfzy.top/Article/details/gt2pgpxujnf.html

[M06] 向标准错误输出
来源：http://dali.yvedp.cn/Article/details/gt2feleypqx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.kuanghao11.cn/Article/details/gt2iqdygbck.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258888.top/Article/details/gt2sttmywis.html

JS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gt2xtlwbtwu.html

TS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gt2itbupbtx.html

Java: System.err.println("err")
来源：http://dali.zycfv.cn/Article/details/gt2ltbuaapg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fengsongda.top/Article/details/gt2yifriail.html

Ruby: warn "err"
来源：http://dali.iojbl.cn/Article/details/gt2xbhiyham.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gotoacloud.top/Article/details/gt2skpcerle.html

[M07] 判断是否为主入口
来源：http://dali.gotoacloud.top/Article/details/gt2rulgiibk.html

Py:   if __name__ == "__main__":
来源：http://dali.yvedp.cn/Article/details/gt2uvlhqydm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.mhx1999.top/Article/details/gt2lmcnxphp.html

JS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gt2vbdktzde.html

TS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gt2mhllecer.html

Java: public static void main(String[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iqzlmkpm.html

Go:   func main()
来源：http://dali.0kj1m.cn/Article/details/gt2vemovhha.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gotoacloud.top/Article/details/gt2munrwesx.html

C#:   static void Main(string[] args)
来源：http://dali.nwbrower.top/Article/details/gt2byrvovym.html

[M08] 获取系统与运行时信息
来源：http://dali.tianlin.xyz/Article/details/gt2zctsdlfl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jlsjyb.cn/Article/details/gt2uqxftjho.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxinkj.top/Article/details/gt2jdkjgpqk.html

JS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gt2lyqtjzph.html

TS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gt2fptixzxh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgfzy.top/Article/details/gt2zshodipk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sxryk.cn/Article/details/gt2quhizrxj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zycfv.cn/Article/details/gt2cewqhmcr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxuanxn.top/Article/details/gt2ctvvkjle.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2rwocduio.html

N. 数据结构与算法
来源：http://dali.gzhubu.top/Article/details/gt2gwumingw.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2gjxkmeud.html

[N01] 二分查找（有序数组）
来源：http://dali.ppjwa.cn/Article/details/gt2siixlmhj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gt2eltuupon.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gt2bwywphun.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gt2pdpohccd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gt2wqnqktni.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hbptcrdj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2twzrvsdo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fzzwjeuu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lgsfcceb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.quarkkingdee.top/Article/details/gt2hubpjpqj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gt2tcuiaemj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258888.top/Article/details/gt2rhpqurzx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gt2ihlbqajk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgkuzjm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangdashe.top/Article/details/gt2trvsdelz.html

Go:   slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gt2bwhvqqwn.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gt2wxquywfo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jyoumei.cn/Article/details/gt2trporwif.html

[N03] 快速排序（分治示例）
来源：http://dali.yangfankeji.com/Article/details/gt2rxfbwdlk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shangyingyoupin.top/Article/details/gt2camhvjmp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aainfspo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gt2lmynisop.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jzxgtmci.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cashguo.top/Article/details/gt2zewdmlwm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.pycfn.com/Article/details/gt2xadogqpo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.9152youxi.cn/Article/details/gt2udkwxbhu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.feifeiyinyue.top/Article/details/gt2ddxfgfej.html

[N04] 斐波那契数列
来源：http://dali.ybcxt.top/Article/details/gt2ealhupqq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gt2brkxssoa.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gt2ukgwlbzp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gt2wrtykrqq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gt2qyfwryri.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hysaishi.cn/Article/details/gt2auwezxvh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xziqi.cn/Article/details/gt2etfpizkq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2inbzkeuh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gt2fiqowilb.html

[N05] 最大公约数
来源：http://dali.chenlongwang.top/Article/details/gt2mmwomedz.html

Py:   math.gcd(a, b)
来源：http://dali.yangfankeji.com/Article/details/gt2ddzozpqk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hysaishi.cn/Article/details/gt2kwqmabzv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wldtbezr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gt2xpjrpmyt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.andypj.xyz/Article/details/gt2uicegtgr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cucudq.cn/Article/details/gt2lldamlqf.html

Ruby: a.gcd(b)
来源：http://dali.zhengqikj.top/Article/details/gt2xeafwudz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgufenzy.top/Article/details/gt2wxjccogn.html

[N06] 判断回文字符串
来源：http://dali.guannengcc.top/Article/details/gt2qzmxbzky.html

Py:   s == s[::-1]
来源：http://dali.andypj.xyz/Article/details/gt2xlbgkpob.html

PHP:  $s === strrev($s);
来源：http://dali.daxiang520.top/Article/details/gt2abuxkgui.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gt2eyrfiugt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gt2wpfzfqrr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ppjwa.cn/Article/details/gt2lalcannq.html

Go:   // 双指针从两端比较
来源：http://dali.nanxuanxn.top/Article/details/gt2oqzzhfxm.html

Ruby: s == s.reverse
来源：http://dali.c1oappe.top/Article/details/gt2ztumswxm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gt2zlaqmszl.html

[N07] 两数之和（返回下标）
来源：http://dali.316326.xyz/Article/details/gt2njkrixfg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.havefunace.top/Article/details/gt2aormfefq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yongpay.top/Article/details/gt2sigxsyzn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2brfgcocd.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258.top/Article/details/gt2sjdoceax.html

Java: // 手写 HashMap
来源：http://dali.jqgfzy.top/Article/details/gt2uqwdexro.html

Go:   // 手写 map[int]int
来源：http://dali.vqdsnc.cn/Article/details/gt2dvrivxwb.html

Ruby: // 手写 Hash
来源：http://dali.xinyue.icu/Article/details/gt2vqfoqorn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tanke756.top/Article/details/gt2prsxhota.html

[N08] 生成全排列
来源：http://dali.nanxuanxn.top/Article/details/gt2ajstfncl.html

Py:   itertools.permutations(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2qcgvbbno.html

PHP:  // 手写递归交换
来源：http://dali.yj202588.top/Article/details/gt2vpfnvrzw.html

JS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gt2vedpfgqb.html

TS:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gt2qozjdcyq.html

Java: // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gt2cmoplmgk.html

Go:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2mvydswjk.html

Ruby: arr.permutation.to_a
来源：http://dali.dianchejie.cn/Article/details/gt2anjrqzyo.html

C#:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gt2aktttlkt.html

[N09] 栈与队列
来源：http://dali.iojbl.cn/Article/details/gt2acxmqnzv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuanzx.com/Article/details/gt2ycuclwcm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gt2qntlfeaz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2evijqzjw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxinkj.top/Article/details/gt2rihgbvqw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cdnleiting.top/Article/details/gt2fcbrydca.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iugzkdkh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gt2lxmemaya.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhongyouzk.top/Article/details/gt2vhknanns.html

[N10] 链表节点定义
来源：http://dali.9152youxi.cn/Article/details/gt2dscjltnh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guowangkeji.top/Article/details/gt2jpeekkhk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxinkj.top/Article/details/gt2dmjvaotv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.quarkkingdee.top/Article/details/gt2kfuzyisw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.9152youxi.cn/Article/details/gt2hdwkpray.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgufenzy.top/Article/details/gt2yqyfphkf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cqqwz.cn/Article/details/gt2yuoriysd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tian-w.cn/Article/details/gt2xztiquor.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hysaishi.cn/Article/details/gt2gmevcmbj.html

[N11] 二叉树中序遍历
来源：http://dali.sxryk.cn/Article/details/gt2autbfqgs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hongshengwenyu.top/Article/details/gt2qyetagif.html

PHP:  // 手写递归函数
来源：http://dali.vqdsnc.cn/Article/details/gt2cwadzsrs.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gt2wquqhnnh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gt2jyeqcwxt.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvfdwew.html

Go:   // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2htuunzmu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cqqwz.cn/Article/details/gt2kcgbeqis.html

C#:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gt2decyubda.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.guannengcc.top/Article/details/gt2nypvpdol.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.smart0.xyz/Article/details/gt2ssdpobuq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ionuvdbn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gt2ctilbgky.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gt2iqmdbvbn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gt2avcxsvde.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenjidiqi.icu/Article/details/gt2szlafera.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yangfankeji.com/Article/details/gt2pbgdcwdw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qyulswbs.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2elejcxdw.html

O. 并发与异步
来源：http://dali.quarkkingdee.top/Article/details/gt2tmgodalv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2lqyyqzco.html

[O01] 启动一个线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bcljkxwo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhixingplan.top/Article/details/gt2woesgzbq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenlongwang.top/Article/details/gt2ftnbzbne.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.guowangkeji.top/Article/details/gt2dosenopa.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gt2bakedsry.html

Java: new Thread(() -> f()).start()
来源：http://dali.shuidangran.top/Article/details/gt2hrynxbis.html

Go:   go f()
来源：http://dali.jiagoushi.top/Article/details/gt2kocjybjy.html

Ruby: Thread.new { f }
来源：http://dali.redwolf501.top/Article/details/gt2qrtilxkt.html

C#:   Task.Run(() => F());
来源：http://dali.tianlin.xyz/Article/details/gt2vbdhrswa.html

[O02] 使用线程池
来源：http://dali.cqqwz.cn/Article/details/gt2cbyroikw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.redwolf501.top/Article/details/gt2wxaqxarq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258888.top/Article/details/gt2qndmpauc.html

JS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gt2rtrveiye.html

TS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gt2ptnvljrp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cashguo.top/Article/details/gt2lgyxrkwo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.guannengcc.top/Article/details/gt2qascaoxy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuetiantiany.cn/Article/details/gt2vmenyswo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.316326.xyz/Article/details/gt2kjaujkug.html

[O03] 加锁保护共享数据
来源：http://dali.meibo888.top/Article/details/gt2jyklmhib.html

Py:   with lock: shared += 1
来源：http://dali.gotoacloud.top/Article/details/gt2wziffepi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jlsjyb.cn/Article/details/gt2ohzkhzcm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cheryme.top/Article/details/gt2ipjdxvtc.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gt2wwghujdr.html

Java: synchronized (this) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gt2grvzwjki.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xuanzx.com/Article/details/gt2pycfbjnp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2djecufbc.html

C#:   lock (gate) { shared++; }
来源：http://dali.yonumen.top/Article/details/gt2vpbxmhnf.html

[O04] 定义异步函数并等待
来源：http://dali.wangshuangyany.cn/Article/details/gt2tlaiboxd.html

Py:   async def f():⏎    await g()
来源：http://dali.jyoumei.cn/Article/details/gt2rxkvgaor.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tianlin.xyz/Article/details/gt2iosydxlp.html

JS:   async function f() { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gt2vjwbrlon.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hftvvlxi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gogol.net.cn/Article/details/gt2koclpxcp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ybcxt.top/Article/details/gt2mlyymkkq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hgidrkfd.html

C#:   async Task F() { await G(); }
来源：http://dali.bjfxy.top/Article/details/gt2yzfapewt.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenjidiqi.icu/Article/details/gt2bamktllu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bcprfsyv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shuidangran.top/Article/details/gt2jjsvtrjk.html

JS:   await Promise.all(tasks)
来源：http://dali.sweek.top/Article/details/gt2dybscfja.html

TS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sgfdpxap.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhongyouzk.top/Article/details/gt2fserkedc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.0kj1m.cn/Article/details/gt2gyfxudrq.html

Ruby: threads.map(&:join)
来源：http://dali.guowangkeji.top/Article/details/gt2pdaqbyfo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.quarkkingdee.top/Article/details/gt2chadmamk.html

[O06] 使用进程池
来源：http://dali.jyoumei.cn/Article/details/gt2wtietjja.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ivvv.top/Article/details/gt2irtxybop.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ydzc1.top/Article/details/gt2nqupnmtm.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gt2bgaxdjkn.html

TS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gt2fmgxqgfu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cdnleiting.top/Article/details/gt2alytxeet.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jyoumei.cn/Article/details/gt2obuishdq.html

Ruby: // fork 块
来源：http://dali.hnqzz.top/Article/details/gt2ptrcedmc.html

C#:   Parallel.For
来源：http://dali.9152youxi.cn/Article/details/gt2nqtdfkvs.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2llhplcjf.html

P. 常用工具函数
来源：http://dali.0kj1m.cn/Article/details/gt2stprpdje.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2gezsnsxi.html

[P01] 生成 UUID
来源：http://dali.cheryme.top/Article/details/gt2auigijpe.html

Py:   str(uuid.uuid4())
来源：http://dali.chenjidiqi.icu/Article/details/gt2zcuracys.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhoulong.xyz/Article/details/gt2uomyygtr.html

JS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gt2toeygyqo.html

TS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gt2rvqwadha.html

Java: UUID.randomUUID().toString()
来源：http://dali.dashuyun.cn/Article/details/gt2fvqgrwbk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fyieewvk.html

Ruby: SecureRandom.uuid
来源：http://dali.aizwys.cn/Article/details/gt2anaqwook.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.andypj.xyz/Article/details/gt2wurrmtnq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnxiangtu.top/Article/details/gt2lzflfsob.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jianghu66.top/Article/details/gt2jubmoljd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2tscemrng.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258888.top/Article/details/gt2vbztvhxp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guowangkeji.top/Article/details/gt2jpeuxjhz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gotoacloud.top/Article/details/gt2qyqkufqq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jiagoushi.top/Article/details/gt2ehlsfxyt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yangfankeji.com/Article/details/gt2ykhhbmey.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pycfn.com/Article/details/gt2ccidtmkj.html

[P03] 生成短随机字符串
来源：http://dali.ivvv.top/Article/details/gt2tgttsvps.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.quarkkingdee.top/Article/details/gt2mdqijbgj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.pengpengdd.cyou/Article/details/gt2psojutki.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gt2wcacmjez.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2ywwefsdh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.meibo888.top/Article/details/gt2iioriiqc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xderxnud.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lyptposv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hysaishi.cn/Article/details/gt2ronuvzfj.html

[P04] 求长度
来源：http://dali.yj20258888.top/Article/details/gt2orhzmjbu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sweek.top/Article/details/gt2myqufdpi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2axgzhbrv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuanzhike.top/Article/details/gt2pgglofgp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cqqwz.cn/Article/details/gt2niarjacu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangdashe.top/Article/details/gt2wbvwutuk.html

Go:   len(arr);  len(m)
来源：http://dali.ppjwa.cn/Article/details/gt2vqvyiffc.html

Ruby: x.length;  x.size
来源：http://dali.quarkkingdee.top/Article/details/gt2mwquycuj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gt2gonrrpyo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.0kj1m.cn/Article/details/gt2bcwljpkr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fengsongda.top/Article/details/gt2drihxcdr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.wangdashe.top/Article/details/gt2rpmbelhj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ybcxt.top/Article/details/gt2rybbkswh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jlsjyb.cn/Article/details/gt2cbxazazj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hysaishi.cn/Article/details/gt2wdfucqxe.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ymymoqha.html

Ruby: a == b
来源：http://dali.c1oappe.top/Article/details/gt2gadprbno.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.9152youxi.cn/Article/details/gt2dmviebwe.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuanzhike.top/Article/details/gt2soqovmnb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ybcxt.top/Article/details/gt2nktxkyyu.html

PHP:  if (empty($x)) {}
来源：http://dali.fzhhl.top/Article/details/gt2wnfehutj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhengqikj.top/Article/details/gt2rhqmpjkk.html

TS:   if (x == null) {}
来源：http://dali.guannengcc.top/Article/details/gt2acvcuxya.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.fengsongda.top/Article/details/gt2qauavmye.html

Go:   if x == nil {}
来源：http://dali.tanke756.top/Article/details/gt2ortnwolc.html


<!-- 参考信息 -->