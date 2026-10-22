代发 wailian999

JS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gt2yrrxeauf.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gt2uclcwrgx.html

Java: args 数组（main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gt2pvxcxcak.html

Go:   os.Args[1:]
来源：http://dali.shzxlz.cn/Article/details/gt2ykubunfh.html

Ruby: ARGV
来源：http://dali.sufxvd.cn/Article/details/gt2kefhxloe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258.top/Article/details/gt2ypmmmapw.html

[M02] 读取环境变量
来源：http://dali.jinqigfzy.top/Article/details/gt2dmmjskyh.html

Py:   os.environ.get("HOME")
来源：http://dali.tanke756.top/Article/details/gt2ygjcnfji.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gt2ywunsiin.html

JS:   process.env.HOME
来源：http://dali.jiagoushi.top/Article/details/gt2rdrlcgrx.html

TS:   process.env.HOME
来源：http://dali.jinqigfzy.top/Article/details/gt2onjqrcaa.html

Java: System.getenv("HOME")
来源：http://dali.xylfe.cn/Article/details/gt2fklvvayg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gt2uragxmnn.html

Ruby: ENV["HOME"]
来源：http://dali.quarkkingdee.top/Article/details/gt2mbhmools.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yueranfly.top/Article/details/gt2rnecqike.html

[M03] 执行外部命令
来源：http://dali.hywenlv.cn/Article/details/gt2rzntdeqe.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2axqhwdeq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nwbrower.top/Article/details/gt2ieklfrom.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gt2ouukuhjn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gt2ohagbdqd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ybcxt.top/Article/details/gt2hkjcavst.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aizwys.cn/Article/details/gt2kvfaietx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tianlin.xyz/Article/details/gt2xyapbrio.html

C#:   Process.Start("ls", "-l");
来源：http://dali.c1oappe.top/Article/details/gt2kbyljahu.html

[M04] 获取当前工作目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wbawerme.html

Py:   os.getcwd()
来源：http://dali.jianghu66.top/Article/details/gt2pfzmpixu.html

PHP:  getcwd();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yimlgzcn.html

JS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gt2mqhjywmd.html

TS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gt2yrluywlz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jlsjyb.cn/Article/details/gt2xpydnzau.html

Go:   os.Getwd()
来源：http://dali.316326.xyz/Article/details/gt2emubhrap.html

Ruby: Dir.pwd
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hzwmfdwf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxinkj.top/Article/details/gt2zwnmbguq.html

[M05] 设置退出码
来源：http://dali.hfpthk.cn/Article/details/gt2itvkkexg.html

Py:   sys.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xrhdvjvf.html

PHP:  exit(1);
来源：http://dali.guowangkeji.top/Article/details/gt2ihnxghvf.html

JS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gt2qqdoipho.html

TS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gt2ksgojcfa.html

Java: System.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2mebfosba.html

Go:   os.Exit(1)
来源：http://dali.bjfxy.top/Article/details/gt2subhdtso.html

Ruby: exit 1
来源：http://dali.zhengqikj.top/Article/details/gt2agtkrbzz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.pycfn.com/Article/details/gt2efamvnie.html

[M06] 向标准错误输出
来源：http://dali.yuxming.cn/Article/details/gt2prasvjbs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nrbfmlri.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnqzz.top/Article/details/gt2syyaljae.html

JS:   console.error("err")
来源：http://dali.sxryk.cn/Article/details/gt2fvbmktst.html

TS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gt2jzsvcbdd.html

Java: System.err.println("err")
来源：http://dali.ybcxt.top/Article/details/gt2piqytriv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vvwmuuia.html

Ruby: warn "err"
来源：http://dali.pycfn.com/Article/details/gt2hvruhpuc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gt2yweqvbom.html

[M07] 判断是否为主入口
来源：http://dali.tanke756.top/Article/details/gt2arvffhyg.html

Py:   if __name__ == "__main__":
来源：http://dali.smart0.xyz/Article/details/gt2pmfisxrg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uyktssns.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2iiedjkyb.html

TS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gt2pxnqcyyw.html

Java: public static void main(String[] args)
来源：http://dali.shzxlz.cn/Article/details/gt2cyyvoiio.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2djheebzr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ydzc1.top/Article/details/gt2sferhuyx.html

C#:   static void Main(string[] args)
来源：http://dali.jiagoushi.top/Article/details/gt2mofakrqn.html

[M08] 获取系统与运行时信息
来源：http://dali.hywenlv.cn/Article/details/gt2yiqnojmo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhiwuduotai.top/Article/details/gt2wkhvlony.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.svipenyu.cn/Article/details/gt2cmxvhveh.html

JS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gt2tgndelqd.html

TS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gt2vjnsqafx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sufxvd.cn/Article/details/gt2ntmqchtr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenzaomai.com/Article/details/gt2lrezgwgt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daxiang520.top/Article/details/gt2kcubvnsk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daxiang520.top/Article/details/gt2gkazkohj.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2qzarlkwo.html

N. 数据结构与算法
来源：http://dali.birdmap.top/Article/details/gt2lchgwikd.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2fnrwnqjv.html

[N01] 二分查找（有序数组）
来源：http://dali.andypj.xyz/Article/details/gt2nnkbzgrr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zycfv.cn/Article/details/gt2uuphhxzf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hywenlv.cn/Article/details/gt2ubszeisi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jsxdqska.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gt2vpvsvzqj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2jizpfgkr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2aahnnaeg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.quarkkingdee.top/Article/details/gt2rqwuylya.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gt2rdrukbfb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gpyqbtio.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tanke756.top/Article/details/gt2cwfmdbmb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aibaodan.cn/Article/details/gt2fhxotdht.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gt2vtsvdlwi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gt2jftqmfsu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daria6918.cn/Article/details/gt2uzjtvwpy.html

Go:   slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2damazlgg.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gt2zlejphna.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangshuangyany.cn/Article/details/gt2sffxsvjh.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxinkj.top/Article/details/gt2rmresifn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cashguo.top/Article/details/gt2dahffqkj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.haohaochexian.top/Article/details/gt2lvlxdjyk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gt2xcwaauhd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gt2yckxmbdx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.0kj1m.cn/Article/details/gt2gqmiamye.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.feifeiyinyue.top/Article/details/gt2cnbfcaux.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shzxlz.cn/Article/details/gt2jzgcimph.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenlongwang.top/Article/details/gt2jcqowizp.html

[N04] 斐波那契数列
来源：http://dali.svipenyu.cn/Article/details/gt2brxqtknk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gt2ykzmmyzx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sweek.top/Article/details/gt2yzgczsnn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gt2bcngwoec.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2jdmokstc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ydzc1.top/Article/details/gt2pxxiblye.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nlishuks.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.316326.xyz/Article/details/gt2grqguolw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gt2plosomnj.html

[N05] 最大公约数
来源：http://dali.xylfe.cn/Article/details/gt2pvndqppe.html

Py:   math.gcd(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gt2ydnebkof.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ucvqxxcp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gt2expwjaqf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxuanxn.top/Article/details/gt2fbnsvozj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhongyouzk.top/Article/details/gt2tuluewiy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.9152youxi.cn/Article/details/gt2opximmvz.html

Ruby: a.gcd(b)
来源：http://dali.yanxiufei.cn/Article/details/gt2xijxcxhl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hfpthk.cn/Article/details/gt2tjwmgtfq.html

[N06] 判断回文字符串
来源：http://dali.yuanzhike.top/Article/details/gt2hwwdmciy.html

Py:   s == s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gt2xukadbwo.html

PHP:  $s === strrev($s);
来源：http://dali.yj20258888.top/Article/details/gt2zdwpqluw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gt2jtxxyaea.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2omgqgmyt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxuanxn.top/Article/details/gt2bvexrpug.html

Go:   // 双指针从两端比较
来源：http://dali.jyoumei.cn/Article/details/gt2udpvmfvq.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zxblttpm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2naahpbae.html

[N07] 两数之和（返回下标）
来源：http://dali.xylfe.cn/Article/details/gt2ekgtdelx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cseikkyg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhixingplan.top/Article/details/gt2grwdwerl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhoulong.xyz/Article/details/gt2batcnwzn.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenlongwang.top/Article/details/gt2bpkswifz.html

Java: // 手写 HashMap
来源：http://dali.gzhubu.top/Article/details/gt2kprubszk.html

Go:   // 手写 map[int]int
来源：http://dali.mhx1999.top/Article/details/gt2ycyusaci.html

Ruby: // 手写 Hash
来源：http://dali.quarkkingdee.top/Article/details/gt2avuulxwc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fzhhl.top/Article/details/gt2bsvrweti.html

[N08] 生成全排列
来源：http://dali.yongpay.top/Article/details/gt2uzpvlvkc.html

Py:   itertools.permutations(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mogbckfl.html

PHP:  // 手写递归交换
来源：http://dali.hysaishi.cn/Article/details/gt2zktxejhs.html

JS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gt2zfvkomiu.html

TS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gt2hqxhxvgh.html

Java: // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jphrpvjy.html

Go:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gt2tyvmotck.html

Ruby: arr.permutation.to_a
来源：http://dali.pycfn.com/Article/details/gt2jsizpmpj.html

C#:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2lzvdcplb.html

[N09] 栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2sqkzvryh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.havefunace.top/Article/details/gt2finwqcdr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.smart0.xyz/Article/details/gt2ehdettor.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2gyfrlwjo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dianchejie.cn/Article/details/gt2hsqbjgzo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2nxajgoap.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxuanxn.top/Article/details/gt2zugvhbyk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gt2kfpcozte.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ttwllsxc.html

[N10] 链表节点定义
来源：http://dali.yj20258888.top/Article/details/gt2dbrflbwr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.vqdsnc.cn/Article/details/gt2chxdswfk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hammf.cn/Article/details/gt2qopneika.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.havefunace.top/Article/details/gt2lqjfgxkk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.havefunace.top/Article/details/gt2auscvgqf.html

Java: class Node { int v; Node next; }
来源：http://dali.sufxvd.cn/Article/details/gt2bwxuftoi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258.top/Article/details/gt2zgfmqnyi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yonumen.top/Article/details/gt2eoietauk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinqigfzy.top/Article/details/gt2iasoreya.html

[N11] 二叉树中序遍历
来源：http://dali.jyoumei.cn/Article/details/gt2yszdrhsl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daria6918.cn/Article/details/gt2zaybjxan.html

PHP:  // 手写递归函数
来源：http://dali.zhoulong.xyz/Article/details/gt2zsxfmvpx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.vqdsnc.cn/Article/details/gt2arlwargl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yvedp.cn/Article/details/gt2ozkucwyo.html

Java: // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2awhybrnm.html

Go:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gt2nxpocyjj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cashguo.top/Article/details/gt2nhefxadf.html

C#:   // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gt2pglwwirp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.guowangkeji.top/Article/details/gt2ddonewux.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jndngxrn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fengsongda.top/Article/details/gt2twjgtlgi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhengqikj.top/Article/details/gt2ojxdvhyf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gywuckwv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lfpppjsf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shuidangran.top/Article/details/gt2cwswkryy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cdnleiting.top/Article/details/gt2wmisxtll.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gt2vqnzztbv.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2prwlafki.html

O. 并发与异步
来源：http://dali.cucudq.cn/Article/details/gt2ybihrfuu.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mhasbogw.html

[O01] 启动一个线程
来源：http://dali.hywenlv.cn/Article/details/gt2lklpifzc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2emztugud.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shzxlz.cn/Article/details/gt2yqxammen.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sweysfiv.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gt2kwjiljwf.html

Java: new Thread(() -> f()).start()
来源：http://dali.yvedp.cn/Article/details/gt2llmofrph.html

Go:   go f()
来源：http://dali.meibo888.top/Article/details/gt2sesrxggw.html

Ruby: Thread.new { f }
来源：http://dali.pycfn.com/Article/details/gt2cvefmfbx.html

C#:   Task.Run(() => F());
来源：http://dali.feifeiyinyue.top/Article/details/gt2wtezmvip.html

[O02] 使用线程池
来源：http://dali.yj20258888.top/Article/details/gt2wdkubkoi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tdkchqbh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yuanzhike.top/Article/details/gt2hjadvvcc.html

JS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gt2midxxams.html

TS:   // worker_threads 线程池
来源：http://dali.ehwqpu.com/Article/details/gt2wudxfapi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhixingplan.top/Article/details/gt2lvvmlkhj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ojbrdzox.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.birdmap.top/Article/details/gt2yscvclds.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenlongwang.top/Article/details/gt2wvrahzem.html

[O03] 加锁保护共享数据
来源：http://dali.birdmap.top/Article/details/gt2viafgkma.html

Py:   with lock: shared += 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2crglwkku.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hongshengwenyu.top/Article/details/gt2wdpkdglz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.feifeiyinyue.top/Article/details/gt2jspmepbx.html

TS:   // 同 JS
来源：http://dali.ehwqpu.com/Article/details/gt2jcluwfte.html

Java: synchronized (this) { shared++; }
来源：http://dali.yonumen.top/Article/details/gt2tavwpkta.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2guhmspnp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xziqi.cn/Article/details/gt2xemdmdtb.html

C#:   lock (gate) { shared++; }
来源：http://dali.cashguo.top/Article/details/gt2abjhtwhs.html

[O04] 定义异步函数并等待
来源：http://dali.nwbrower.top/Article/details/gt2tmavzluv.html

Py:   async def f():⏎    await g()
来源：http://dali.xuetiantiany.cn/Article/details/gt2wzpmsget.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jianghu66.top/Article/details/gt2fpkavbdt.html

JS:   async function f() { await g(); }
来源：http://dali.birdmap.top/Article/details/gt2ssnzvvdf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.wangdashe.top/Article/details/gt2cyzilvrl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xziqi.cn/Article/details/gt2cdjaulib.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.havefunace.top/Article/details/gt2wbkyyaaz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xinyue.icu/Article/details/gt2mdaoujkm.html

C#:   async Task F() { await G(); }
来源：http://dali.cucudq.cn/Article/details/gt2zqyownud.html

[O05] 并发执行并等待全部完成
来源：http://dali.hysaishi.cn/Article/details/gt2axhdryxv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhixingplan.top/Article/details/gt2rzfujcqv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.0kj1m.cn/Article/details/gt2rswdafoi.html

JS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gt2alpsgwab.html

TS:   await Promise.all(tasks)
来源：http://dali.jyoumei.cn/Article/details/gt2smiozjfe.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.wangdashe.top/Article/details/gt2bgbybzwv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ybcxt.top/Article/details/gt2ntabhjvg.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258888.top/Article/details/gt2daqefxls.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.bjfxy.top/Article/details/gt2frwlgrtl.html

[O06] 使用进程池
来源：http://dali.xziqi.cn/Article/details/gt2doifvtbg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangdashe.top/Article/details/gt2ackpsmcv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jqgufenzy.top/Article/details/gt2yppopbth.html

JS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gt2nzwylsft.html

TS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qwgihlva.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fzhhl.top/Article/details/gt2fgdlajfv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cqqwz.cn/Article/details/gt2nnavfatk.html

Ruby: // fork 块
来源：http://dali.guowangkeji.top/Article/details/gt2ujnpwbjx.html

C#:   Parallel.For
来源：http://dali.shzxlz.cn/Article/details/gt2bypkggsx.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2fnayojeb.html

P. 常用工具函数
来源：http://dali.quarkkingdee.top/Article/details/gt2aismvrrf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2pdthftnd.html

[P01] 生成 UUID
来源：http://dali.jqgufenzy.top/Article/details/gt2rxckslzy.html

Py:   str(uuid.uuid4())
来源：http://dali.mhx1999.top/Article/details/gt2ouoqsxlc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tian-w.cn/Article/details/gt2ncmxussw.html

JS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gt2umsqfjdj.html

TS:   crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gt2dzwzxudd.html

Java: UUID.randomUUID().toString()
来源：http://dali.redwolf501.top/Article/details/gt2smvbnkhc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.bjfxy.top/Article/details/gt2umuqqoqc.html

Ruby: SecureRandom.uuid
来源：http://dali.ivvv.top/Article/details/gt2dziphrfl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ybcxt.top/Article/details/gt2uzqjbzhq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhengqikj.top/Article/details/gt2jcdtooxz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gogol.net.cn/Article/details/gt2fyongglg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.meibo888.top/Article/details/gt2beaqlzrx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.fzhhl.top/Article/details/gt2kqocuihh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ayvukhnc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sxryk.cn/Article/details/gt2fegbqmes.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.quarkkingdee.top/Article/details/gt2wpbwyvnu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2tswzqkeu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jianghu66.top/Article/details/gt2cipvzzza.html

[P03] 生成短随机字符串
来源：http://dali.sweek.top/Article/details/gt2bmdlpoew.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yueranfly.top/Article/details/gt2zwluyobd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj20258888.top/Article/details/gt2hffulrqu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wmypqqba.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.0kj1m.cn/Article/details/gt2qlgwgqcq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.c1oappe.top/Article/details/gt2mtgtutxf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yuanzhike.top/Article/details/gt2rxqenlgt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jlsjyb.cn/Article/details/gt2ourigizb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenzaomai.com/Article/details/gt2cbmsoqhj.html

[P04] 求长度
来源：http://dali.shuidangran.top/Article/details/gt2dzmltktz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qjbwlktu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gt2fnuyljur.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.andypj.xyz/Article/details/gt2qkmkaalx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuhhoki.html

Java: list.size();  map.size();  s.length()
来源：http://dali.andypj.xyz/Article/details/gt2thwduhbh.html

Go:   len(arr);  len(m)
来源：http://dali.yuxming.cn/Article/details/gt2yarnflyk.html

Ruby: x.length;  x.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wqutfqbj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xuanzx.com/Article/details/gt2iwkrowty.html

[P05] 判断两个对象内容是否相等
来源：http://dali.aibaodan.cn/Article/details/gt2cwgqnukt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pvheqhzn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shuidangran.top/Article/details/gt2hzqhhglq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shuidangran.top/Article/details/gt2wqbrlbix.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dpmtpqxd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ivvv.top/Article/details/gt2kmnrcgai.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nwbrower.top/Article/details/gt2uwgddszf.html

Ruby: a == b
来源：http://dali.yangfankeji.com/Article/details/gt2zxulensl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shuidangran.top/Article/details/gt2yowkmhlq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jianghu66.top/Article/details/gt2jmfybfva.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kxirovhp.html

PHP:  if (empty($x)) {}
来源：http://dali.jyoumei.cn/Article/details/gt2vkfrlgkx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.snrcjt.cn/Article/details/gt2bitgnwqz.html

TS:   if (x == null) {}
来源：http://dali.yj20258888.top/Article/details/gt2lbhjpbbp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gt2nwzkbpff.html

Go:   if x == nil {}
来源：http://dali.gaohongyu789.top/Article/details/gt2smodgcbh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jiagoushi.top/Article/details/gt2mxsrmcwf.html

C#:   if (x is null) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yayatpno.html

[P07] 防抖与节流
来源：http://dali.quarkkingdee.top/Article/details/gt2sbmqqvef.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mxxhgiwx.html

PHP:  // 手写时间戳比较
来源：http://dali.aibaodan.cn/Article/details/gt2icpwusnw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gt2ktdupyuz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gt2stxohxit.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qwjwmqil.html


<!-- 参考信息 -->