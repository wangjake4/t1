代发 wailian999

JS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gt2xzohblus.html

TS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gt2hzszvisa.html

Java: args 数组（main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gt2tyvjoeyq.html

Go:   os.Args[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gt2cqdvnwks.html

Ruby: ARGV
来源：http://dali.cdnleiting.top/Article/details/gt2fvlmogjy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gt2arsnzwhd.html

[M02] 读取环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nfmwduec.html

Py:   os.environ.get("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vcmgmdwy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gt2oajexotx.html

JS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gt2dmwzuseb.html

TS:   process.env.HOME
来源：http://dali.jiagoushi.top/Article/details/gt2slagcvlt.html

Java: System.getenv("HOME")
来源：http://dali.fzhhl.top/Article/details/gt2dvlvmjcq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.c1oappe.top/Article/details/gt2qwnewlrz.html

Ruby: ENV["HOME"]
来源：http://dali.redwolf501.top/Article/details/gt2egknjqef.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2yzeocqfw.html

[M03] 执行外部命令
来源：http://dali.svipenyu.cn/Article/details/gt2etnirzqk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xziqi.cn/Article/details/gt2erenisgl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258888.top/Article/details/gt2irsfcqbf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gt2kblodprp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gt2qymfiuyh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.havefunace.top/Article/details/gt2vxmzwqvw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.svipenyu.cn/Article/details/gt2qchdpkbt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenzaomai.com/Article/details/gt2djcbremg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xylfe.cn/Article/details/gt2grdcqqhg.html

[M04] 获取当前工作目录
来源：http://dali.chenlongwang.top/Article/details/gt2ioashdmc.html

Py:   os.getcwd()
来源：http://dali.vqdsnc.cn/Article/details/gt2pcsnkyni.html

PHP:  getcwd();
来源：http://dali.jyoumei.cn/Article/details/gt2vypzftsu.html

JS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gt2aneryadf.html

TS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gt2ioretofq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ehwqpu.com/Article/details/gt2xpfucptu.html

Go:   os.Getwd()
来源：http://dali.aibaodan.cn/Article/details/gt2dgtdsmaj.html

Ruby: Dir.pwd
来源：http://dali.wangshuangyany.cn/Article/details/gt2fckabsge.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj20258888.top/Article/details/gt2eejufzjq.html

[M05] 设置退出码
来源：http://dali.yj20258.top/Article/details/gt2nviznyei.html

Py:   sys.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2wybtokbh.html

PHP:  exit(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ljubuwdc.html

JS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2zdhcirdj.html

TS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2wgiedatj.html

Java: System.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2vjnddwmi.html

Go:   os.Exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2xtdteelh.html

Ruby: exit 1
来源：http://dali.ybcxt.top/Article/details/gt2aitlbcpp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.9152youxi.cn/Article/details/gt2jwbbkvwi.html

[M06] 向标准错误输出
来源：http://dali.c1oappe.top/Article/details/gt2ahpydclw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgfzy.top/Article/details/gt2zjgbmpxt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ybcxt.top/Article/details/gt2boiyickd.html

JS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gt2avnvtsct.html

TS:   console.error("err")
来源：http://dali.hnxiangtu.top/Article/details/gt2fnixvzpd.html

Java: System.err.println("err")
来源：http://dali.yuanzhike.top/Article/details/gt2gtuseixx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yonumen.top/Article/details/gt2wcnrhddr.html

Ruby: warn "err"
来源：http://dali.smart0.xyz/Article/details/gt2ibinzqye.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.mhx1999.top/Article/details/gt2uhkpveoy.html

[M07] 判断是否为主入口
来源：http://dali.yonumen.top/Article/details/gt2gycnpjrd.html

Py:   if __name__ == "__main__":
来源：http://dali.hnxiangtu.top/Article/details/gt2qkeurzak.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuetiantiany.cn/Article/details/gt2hfefmvfh.html

JS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gt2vnbrynzl.html

TS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gt2vemmtavv.html

Java: public static void main(String[] args)
来源：http://dali.vqdsnc.cn/Article/details/gt2akurbzni.html

Go:   func main()
来源：http://dali.sweek.top/Article/details/gt2bsuibpvc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgufenzy.top/Article/details/gt2zlignedr.html

C#:   static void Main(string[] args)
来源：http://dali.cqqwz.cn/Article/details/gt2zbsxilzv.html

[M08] 获取系统与运行时信息
来源：http://dali.smart0.xyz/Article/details/gt2tvtxhzhe.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cashguo.top/Article/details/gt2aqbkuciw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.316326.xyz/Article/details/gt2hilbvxlv.html

JS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gt2djsqudru.html

TS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gt2wdlasiql.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sxryk.cn/Article/details/gt2yiukfrpm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258888.top/Article/details/gt2okkhdbrp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jyoumei.cn/Article/details/gt2vrjmivcl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yongpay.top/Article/details/gt2xcdbczmw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2urwzfihm.html

N. 数据结构与算法
来源：http://dali.guannengcc.top/Article/details/gt2zahnzoio.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2yomcyofd.html

[N01] 二分查找（有序数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2usjtdsbu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gt2glmhzqyc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.svipenyu.cn/Article/details/gt2yxiijobz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gt2jmgplsfd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gt2zhsuznqg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gt2nvogycuc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gt2ksqrtfch.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhengqikj.top/Article/details/gt2jsncrgho.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gt2ijxlevhv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dashuyun.cn/Article/details/gt2qbwjdsjl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yueranfly.top/Article/details/gt2kmuyxzen.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yvedp.cn/Article/details/gt2ccjgegnn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gt2zgowlabk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gt2pigrnhaw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shzxlz.cn/Article/details/gt2jmaxjplx.html

Go:   slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2dwviiink.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gt2ftznhfhg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.9152youxi.cn/Article/details/gt2dhzbnybm.html

[N03] 快速排序（分治示例）
来源：http://dali.shuidangran.top/Article/details/gt2qmekdjds.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.meibo888.top/Article/details/gt2rjlkgghp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ehwqpu.com/Article/details/gt2fxmyqfsl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gt2voobrrlf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gt2rykbuvfc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shangyingyoupin.top/Article/details/gt2iwmfmmjm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangshuangyany.cn/Article/details/gt2piucrcar.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hysaishi.cn/Article/details/gt2xmtckjxw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jiagoushi.top/Article/details/gt2yxcdgbrv.html

[N04] 斐波那契数列
来源：http://dali.cqqwz.cn/Article/details/gt2rofpvscu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gt2txqhiion.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yongpay.top/Article/details/gt2jsiywjct.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gt2vbbofuro.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hjyfciqm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sweek.top/Article/details/gt2sxttzbrp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sweek.top/Article/details/gt2qcztatpg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xubwxbsh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hlnpihla.html

[N05] 最大公约数
来源：http://dali.andypj.xyz/Article/details/gt2nsarvfyx.html

Py:   math.gcd(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kyuqgzdu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aizwys.cn/Article/details/gt2jxfbarvg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenzaomai.com/Article/details/gt2lrrtedxo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gt2vlzcamgm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pycfn.com/Article/details/gt2hinjsvyx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.snrcjt.cn/Article/details/gt2luguvpbs.html

Ruby: a.gcd(b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2whjhzgrp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yonumen.top/Article/details/gt2pnrptlig.html

[N06] 判断回文字符串
来源：http://dali.yueranfly.top/Article/details/gt2efwihcbf.html

Py:   s == s[::-1]
来源：http://dali.ppjwa.cn/Article/details/gt2ghmrqpwg.html

PHP:  $s === strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gt2qyusilmi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gt2hnxxrvtn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gt2bnkedikg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnxiangtu.top/Article/details/gt2ocspihcd.html

Go:   // 双指针从两端比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2noenojyt.html

Ruby: s == s.reverse
来源：http://dali.iojbl.cn/Article/details/gt2thurwabs.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gt2tfqaehgk.html

[N07] 两数之和（返回下标）
来源：http://dali.hywenlv.cn/Article/details/gt2ouwdbnkf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhiwuduotai.top/Article/details/gt2htquorvm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258.top/Article/details/gt2nlhjwjer.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xziqi.cn/Article/details/gt2culfixyr.html

TS:   // 手写 Map<string, number>
来源：http://dali.ppjwa.cn/Article/details/gt2hhmhamzr.html

Java: // 手写 HashMap
来源：http://dali.sufxvd.cn/Article/details/gt2rbnlgepl.html

Go:   // 手写 map[int]int
来源：http://dali.fzhhl.top/Article/details/gt2tkgkhlqb.html

Ruby: // 手写 Hash
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxwthfli.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yangfankeji.com/Article/details/gt2vqzgnhom.html

[N08] 生成全排列
来源：http://dali.tianlin.xyz/Article/details/gt2dustsdyc.html

Py:   itertools.permutations(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bfwgtvwn.html

PHP:  // 手写递归交换
来源：http://dali.hnqzz.top/Article/details/gt2yvoxbvyh.html

JS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gt2cfgwqoas.html

TS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2exrggtby.html

Java: // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gt2crtthggj.html

Go:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2akyhxdfo.html

Ruby: arr.permutation.to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vmmimxfj.html

C#:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2oslmbjqh.html

[N09] 栈与队列
来源：http://dali.zhixingplan.top/Article/details/gt2txzadviw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2ufauhjri.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ivvv.top/Article/details/gt2zjolunlv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gt2ygwwpntc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.feifeiyinyue.top/Article/details/gt2ftqcebmp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.havefunace.top/Article/details/gt2fgsxbnte.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangshuangyany.cn/Article/details/gt2luqpmemo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gt2jcahyjgj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.smart0.xyz/Article/details/gt2wurfhpri.html

[N10] 链表节点定义
来源：http://dali.haohaochexian.top/Article/details/gt2bmitnoxc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.9152youxi.cn/Article/details/gt2kncqznma.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yueranfly.top/Article/details/gt2vhquafdg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cucudq.cn/Article/details/gt2dcxkouas.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.meibo888.top/Article/details/gt2uwefekqy.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urkgooaz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigfzy.top/Article/details/gt2adlyvjra.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aibaodan.cn/Article/details/gt2mmgvjdms.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxuanxn.top/Article/details/gt2jivolrxo.html

[N11] 二叉树中序遍历
来源：http://dali.dianchejie.cn/Article/details/gt2ybnkppdd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhiwuduotai.top/Article/details/gt2qrhvwfep.html

PHP:  // 手写递归函数
来源：http://dali.gotoacloud.top/Article/details/gt2rafswqlb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2epbztbsv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gt2fbqlcruu.html

Java: // 手写递归
来源：http://dali.yonumen.top/Article/details/gt2vyaooegn.html

Go:   // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gt2tqlhzqnt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.quarkkingdee.top/Article/details/gt2fhxweova.html

C#:   // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gt2mqnondew.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.haohaochexian.top/Article/details/gt2uvxxejzg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.andypj.xyz/Article/details/gt2plwjnpjl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ehwqpu.com/Article/details/gt2mhyvzpwv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pycfn.com/Article/details/gt2pspfudpq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gt2llcmwkyg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gt2qsukdzrb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cucudq.cn/Article/details/gt2fudgnfou.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.9152youxi.cn/Article/details/gt2qfadmvwc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gt2gtscfqvh.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2roegppgd.html

O. 并发与异步
来源：http://dali.sxryk.cn/Article/details/gt2lnzdtgns.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2hfsyiqei.html

[O01] 启动一个线程
来源：http://dali.yanxiufei.cn/Article/details/gt2etqzxams.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yanxiufei.cn/Article/details/gt2cqdqupka.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.wangdashe.top/Article/details/gt2xsfnttaa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cqqwz.cn/Article/details/gt2yzerlhbl.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gt2kjkgdxel.html

Java: new Thread(() -> f()).start()
来源：http://dali.haohaochexian.top/Article/details/gt2igtzervs.html

Go:   go f()
来源：http://dali.zycfv.cn/Article/details/gt2ryvjghmh.html

Ruby: Thread.new { f }
来源：http://dali.yuanzhike.top/Article/details/gt2ellzaqtq.html

C#:   Task.Run(() => F());
来源：http://dali.yanxiufei.cn/Article/details/gt2vzvtvzmx.html

[O02] 使用线程池
来源：http://dali.ydzc1.top/Article/details/gt2qdjpcwgl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.dashuyun.cn/Article/details/gt2qhgwbawx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hywenlv.cn/Article/details/gt2uzbgglss.html

JS:   // worker_threads 线程池
来源：http://dali.yangfankeji.com/Article/details/gt2ttyzquzt.html

TS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gt2yfdvkpeo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.bjfxy.top/Article/details/gt2tvqidfve.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.c1oappe.top/Article/details/gt2dhgvcwcp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nanxinkj.top/Article/details/gt2uvmraunj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhoulong.xyz/Article/details/gt2fmpsnnvb.html

[O03] 加锁保护共享数据
来源：http://dali.yj202588.top/Article/details/gt2kluzojyo.html

Py:   with lock: shared += 1
来源：http://dali.zycfv.cn/Article/details/gt2aevpggyk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgfzy.top/Article/details/gt2mxqzwgrq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxukxwj.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gt2uaxtghsu.html

Java: synchronized (this) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gt2xmjcewvx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qnkggkvp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuanzhike.top/Article/details/gt2wyewylxk.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gt2ucnrrmjc.html

[O04] 定义异步函数并等待
来源：http://dali.cashguo.top/Article/details/gt2ccbnuwph.html

Py:   async def f():⏎    await g()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2duamnbsw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xinyue.icu/Article/details/gt2tazzchak.html

JS:   async function f() { await g(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vybprbji.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.fzhhl.top/Article/details/gt2xbcsdjuf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.c1oappe.top/Article/details/gt2hcarexcd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.0kj1m.cn/Article/details/gt2vkekrwxi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.svipenyu.cn/Article/details/gt2ejhjbgor.html

C#:   async Task F() { await G(); }
来源：http://dali.zhixingplan.top/Article/details/gt2ssbhzdue.html

[O05] 并发执行并等待全部完成
来源：http://dali.cdnleiting.top/Article/details/gt2maerwsmy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.mhx1999.top/Article/details/gt2vminwsgk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.wangshuangyany.cn/Article/details/gt2aydbejas.html

JS:   await Promise.all(tasks)
来源：http://dali.yanxiufei.cn/Article/details/gt2qwfzlxue.html

TS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gt2ytekoftw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sxryk.cn/Article/details/gt2nlfqwpmd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2opthjpie.html

Ruby: threads.map(&:join)
来源：http://dali.c1oappe.top/Article/details/gt2pwhgmpfh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj20258.top/Article/details/gt2hdvsjrbt.html

[O06] 使用进程池
来源：http://dali.jiagoushi.top/Article/details/gt2qmmzupfs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.aizwys.cn/Article/details/gt2vulqmuej.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tian-w.cn/Article/details/gt2fsqqyhtg.html

JS:   // child_process / cluster 模块
来源：http://dali.pengpengdd.cyou/Article/details/gt2pgqsycit.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gt2fwcwyqrl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nwbrower.top/Article/details/gt2tjmzwpyc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cheryme.top/Article/details/gt2ebydluur.html

Ruby: // fork 块
来源：http://dali.yj202588.top/Article/details/gt2zfvizbln.html

C#:   Parallel.For
来源：http://dali.xuanzx.com/Article/details/gt2vydhtgtl.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bvsriqyg.html

P. 常用工具函数
来源：http://dali.nanxuanxn.top/Article/details/gt2atfxgrip.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2golrklcx.html

[P01] 生成 UUID
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mpbkxfyu.html

Py:   str(uuid.uuid4())
来源：http://dali.jianghu66.top/Article/details/gt2tsoafdxm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daria6918.cn/Article/details/gt2getudtwa.html

JS:   crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gt2xhowbjrb.html

TS:   crypto.randomUUID()
来源：http://dali.tianlin.xyz/Article/details/gt2khmlepjy.html

Java: UUID.randomUUID().toString()
来源：http://dali.gzhubu.top/Article/details/gt2btxrddcw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xuanzx.com/Article/details/gt2unxyrfhh.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgfzy.top/Article/details/gt2bokhigws.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.daxiang520.top/Article/details/gt2wshuhmly.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ydphrpxo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangdashe.top/Article/details/gt2bbgrcdcb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2aeilhfre.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gt2smblgsrg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nanxinkj.top/Article/details/gt2vhgabxiu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gogol.net.cn/Article/details/gt2ckfxsokc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jyoumei.cn/Article/details/gt2qrncjdmb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.guowangkeji.top/Article/details/gt2phubgdyw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gdiyabxm.html

[P03] 生成短随机字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2wiovqyli.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.andypj.xyz/Article/details/gt2nlnkflku.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daria6918.cn/Article/details/gt2benhpudb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gt2xdltitmr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gt2azxochii.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhixingplan.top/Article/details/gt2qtecboyh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.c1oappe.top/Article/details/gt2dvzpxwec.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gaohongyu789.top/Article/details/gt2mhyxetsp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hongshengwenyu.top/Article/details/gt2qmyayqkp.html

[P04] 求长度
来源：http://dali.nwbrower.top/Article/details/gt2hqqqfiog.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.birdmap.top/Article/details/gt2wuzdzpza.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rlvkmvyd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gt2inczeeul.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.9152youxi.cn/Article/details/gt2cwljbstp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tanke756.top/Article/details/gt2hulswgvd.html

Go:   len(arr);  len(m)
来源：http://dali.chenzaomai.com/Article/details/gt2tgzssrti.html

Ruby: x.length;  x.size
来源：http://dali.cheryme.top/Article/details/gt2dlxrndtp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fengsongda.top/Article/details/gt2jzgqtuer.html

[P05] 判断两个对象内容是否相等
来源：http://dali.9152youxi.cn/Article/details/gt2nxiljibv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cashguo.top/Article/details/gt2slnbhdxk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nwbrower.top/Article/details/gt2chzryafb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yvedp.cn/Article/details/gt2cwzincog.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.smart0.xyz/Article/details/gt2nictksag.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xziqi.cn/Article/details/gt2ivqhrssh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tian-w.cn/Article/details/gt2qzgxiohj.html

Ruby: a == b
来源：http://dali.zhiwuduotai.top/Article/details/gt2olsflxhd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gogol.net.cn/Article/details/gt2ttkcynnm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tianlin.xyz/Article/details/gt2ktyfuhrl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.andypj.xyz/Article/details/gt2uhhsgukc.html

PHP:  if (empty($x)) {}
来源：http://dali.tian-w.cn/Article/details/gt2qjqfetqs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenzaomai.com/Article/details/gt2xoneoluu.html

TS:   if (x == null) {}
来源：http://dali.havefunace.top/Article/details/gt2ohkugcdm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ccylrbhb.html

Go:   if x == nil {}
来源：http://dali.haohaochexian.top/Article/details/gt2efkqzaoj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ydzc1.top/Article/details/gt2jmiipxjd.html

C#:   if (x is null) {}
来源：http://dali.snrcjt.cn/Article/details/gt2mnvkqvhr.html

[P07] 防抖与节流
来源：http://dali.fengsongda.top/Article/details/gt2jzadmfkt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.dianchejie.cn/Article/details/gt2qwntewfj.html

PHP:  // 手写时间戳比较
来源：http://dali.shuidangran.top/Article/details/gt2ngdphppi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gt2eorhijsc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gt2hogygkjy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yuxming.cn/Article/details/gt2ejlhgpcc.html


<!-- 参考信息 -->