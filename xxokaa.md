代发 wailian999

JS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gt2zvjrbgna.html

TS:   process.argv.slice(2)
来源：http://dali.xinyue.icu/Article/details/gt2xduzsydb.html

Java: args 数组（main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gt2rkdhqaql.html

Go:   os.Args[1:]
来源：http://dali.iojbl.cn/Article/details/gt2tofdfiop.html

Ruby: ARGV
来源：http://dali.hfpthk.cn/Article/details/gt2dxvumcfg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gt2tojxoexd.html

[M02] 读取环境变量
来源：http://dali.ybcxt.top/Article/details/gt2wwnwjqko.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigufen.top/Article/details/gt2mmnitrxl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.aibaodan.cn/Article/details/gt2vejziayc.html

JS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gt2qohetysp.html

TS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gt2nfuoblof.html

Java: System.getenv("HOME")
来源：http://dali.yj20258888.top/Article/details/gt2fwqtgxva.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gt2iqcsncex.html

Ruby: ENV["HOME"]
来源：http://dali.wangdashe.top/Article/details/gt2jceetljc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shuidangran.top/Article/details/gt2gjlrtvkj.html

[M03] 执行外部命令
来源：http://dali.sxryk.cn/Article/details/gt2kopmvkxw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xhavnoum.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tanke756.top/Article/details/gt2xpsucmio.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2zuyiwtsi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gt2yyitatsm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sweek.top/Article/details/gt2uykfcyek.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ybcxt.top/Article/details/gt2erdrzvce.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jianghu66.top/Article/details/gt2tlxanryg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.bjfxy.top/Article/details/gt2bwbpirua.html

[M04] 获取当前工作目录
来源：http://dali.yongpay.top/Article/details/gt2mzmgrhls.html

Py:   os.getcwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hymtogpf.html

PHP:  getcwd();
来源：http://dali.zhixingplan.top/Article/details/gt2biutggtw.html

JS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gt2komkmcwm.html

TS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gt2yqbsspkp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhongyouzk.top/Article/details/gt2jutbthpk.html

Go:   os.Getwd()
来源：http://dali.shuidangran.top/Article/details/gt2omslunqn.html

Ruby: Dir.pwd
来源：http://dali.hysaishi.cn/Article/details/gt2bcvsbwxt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yangfankeji.com/Article/details/gt2fygyxmey.html

[M05] 设置退出码
来源：http://dali.jlsjyb.cn/Article/details/gt2dtdvpzvu.html

Py:   sys.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2yfbmdiyw.html

PHP:  exit(1);
来源：http://dali.sweek.top/Article/details/gt2njuckvgy.html

JS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2sbsyvtwz.html

TS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2biioxsdr.html

Java: System.exit(1)
来源：http://dali.xylfe.cn/Article/details/gt2bptzbwht.html

Go:   os.Exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2brzipbfo.html

Ruby: exit 1
来源：http://dali.cdnleiting.top/Article/details/gt2ulkctgpn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tian-w.cn/Article/details/gt2mxzfqetr.html

[M06] 向标准错误输出
来源：http://dali.kuanghao11.cn/Article/details/gt2yhxkapsi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daxiang520.top/Article/details/gt2spnrmmyt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xylfe.cn/Article/details/gt2zwwvjads.html

JS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2quleugmv.html

TS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gt2kfirbhyg.html

Java: System.err.println("err")
来源：http://dali.0kj1m.cn/Article/details/gt2neiqvcjn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhongyouzk.top/Article/details/gt2zcgkpvyw.html

Ruby: warn "err"
来源：http://dali.gaohongyu789.top/Article/details/gt2zditnfwh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tianlin.xyz/Article/details/gt2jiwaovis.html

[M07] 判断是否为主入口
来源：http://dali.daxiang520.top/Article/details/gt2ifrohams.html

Py:   if __name__ == "__main__":
来源：http://dali.gotoacloud.top/Article/details/gt2ntcmnppa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hongshengwenyu.top/Article/details/gt2ojisltrc.html

JS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nfxblgpm.html

TS:   require.main === module
来源：http://dali.sweek.top/Article/details/gt2sobgiwzu.html

Java: public static void main(String[] args)
来源：http://dali.havefunace.top/Article/details/gt2gzkojzmx.html

Go:   func main()
来源：http://dali.zycfv.cn/Article/details/gt2dvckkwqr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.meibo888.top/Article/details/gt2bdepvuqc.html

C#:   static void Main(string[] args)
来源：http://dali.chenzaomai.com/Article/details/gt2ubkkiduq.html

[M08] 获取系统与运行时信息
来源：http://dali.sysykeji.top/Article/details/gt2vcrvmkho.html

Py:   platform.system();  platform.python_version()
来源：http://dali.havefunace.top/Article/details/gt2rvmpzvic.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shzxlz.cn/Article/details/gt2gmavobvs.html

JS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gt2thrwjktj.html

TS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gt2ycfxnbye.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.vqdsnc.cn/Article/details/gt2kdgfoimd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yonumen.top/Article/details/gt2qncyeaof.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.0kj1m.cn/Article/details/gt2ounenvih.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvchivp.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2pvxbjqfo.html

N. 数据结构与算法
来源：http://dali.zhixingplan.top/Article/details/gt2hcmqwszt.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2gknvrssr.html

[N01] 二分查找（有序数组）
来源：http://dali.xuanzx.com/Article/details/gt2phemdnzm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2nwhtslam.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yueranfly.top/Article/details/gt2euotyxhj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.birdmap.top/Article/details/gt2htwkjvel.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fengsongda.top/Article/details/gt2zjsvsrjz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2rdoastij.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2qhtzipyn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhixingplan.top/Article/details/gt2jrcmxvqm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2ghzasadm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aizwys.cn/Article/details/gt2geuckvwh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhiwuduotai.top/Article/details/gt2duiggzfg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aizwys.cn/Article/details/gt2vscszwfk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gt2znlwqfji.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gt2grbfxfzr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.quarkkingdee.top/Article/details/gt2yeohggos.html

Go:   slices.Sort(arr)
来源：http://dali.cucudq.cn/Article/details/gt2tgmvxsja.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gt2lblaugpf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.smart0.xyz/Article/details/gt2lbidguxe.html

[N03] 快速排序（分治示例）
来源：http://dali.snrcjt.cn/Article/details/gt2qfkqqwqb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258.top/Article/details/gt2dkxkkteb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.feifeiyinyue.top/Article/details/gt2lcaimnhi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gt2dikezyic.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gt2xpagiutk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgufenzy.top/Article/details/gt2zqhwmijl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hfpthk.cn/Article/details/gt2oqohzarw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hnxiangtu.top/Article/details/gt2jtrajnar.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yongpay.top/Article/details/gt2ojybdcpc.html

[N04] 斐波那契数列
来源：http://dali.xuetiantiany.cn/Article/details/gt2egagekxg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fucuygqp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.smart0.xyz/Article/details/gt2qrbwevox.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gt2sgclrlft.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gt2vkwezdvi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daria6918.cn/Article/details/gt2ukwegztv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuxming.cn/Article/details/gt2qslhhxmh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gt2lkwuwjqv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gt2zxwkwfcq.html

[N05] 最大公约数
来源：http://dali.aibaodan.cn/Article/details/gt2rhviwmfl.html

Py:   math.gcd(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bmcaaymf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yueranfly.top/Article/details/gt2uxvctojn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gt2mhuipziq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bzwtskab.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tanke756.top/Article/details/gt2rxdayqqi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.birdmap.top/Article/details/gt2fmyasrha.html

Ruby: a.gcd(b)
来源：http://dali.ivvv.top/Article/details/gt2uuyduwuh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258.top/Article/details/gt2hqpolhls.html

[N06] 判断回文字符串
来源：http://dali.tianlin.xyz/Article/details/gt2scunaspu.html

Py:   s == s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gt2voattlpl.html

PHP:  $s === strrev($s);
来源：http://dali.hammf.cn/Article/details/gt2udsnkmof.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2jossltzk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gt2evuwygez.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cpuntbuf.html

Go:   // 双指针从两端比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2ccakdwou.html

Ruby: s == s.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gt2ognaaopd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gt2eucvdjtb.html

[N07] 两数之和（返回下标）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2exapskly.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigufen.top/Article/details/gt2xztnglkf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dashuyun.cn/Article/details/gt2zwbbldyc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yueranfly.top/Article/details/gt2pgmrpkte.html

TS:   // 手写 Map<string, number>
来源：http://dali.haohaochexian.top/Article/details/gt2khlphpxv.html

Java: // 手写 HashMap
来源：http://dali.zycfv.cn/Article/details/gt2qjxrcxfq.html

Go:   // 手写 map[int]int
来源：http://dali.cucudq.cn/Article/details/gt2kqultcot.html

Ruby: // 手写 Hash
来源：http://dali.yj20258888.top/Article/details/gt2uzqbajja.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tanke756.top/Article/details/gt2glqrmdkm.html

[N08] 生成全排列
来源：http://dali.tanke756.top/Article/details/gt2gjjblrbt.html

Py:   itertools.permutations(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hcblhznk.html

PHP:  // 手写递归交换
来源：http://dali.ydzc1.top/Article/details/gt2lvvdpppw.html

JS:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gt2wjthrvqm.html

TS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2iniephpt.html

Java: // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gt2hfthtzeo.html

Go:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2qeyaqrir.html

Ruby: arr.permutation.to_a
来源：http://dali.tanke756.top/Article/details/gt2ngrrrumg.html

C#:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gt2dlkaaxdw.html

[N09] 栈与队列
来源：http://dali.redwolf501.top/Article/details/gt2luuntbdj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.bjfxy.top/Article/details/gt2ssskvjok.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gt2oeqisapk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2htfuxrgz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gogol.net.cn/Article/details/gt2uutchemu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.vqdsnc.cn/Article/details/gt2xceyeiwo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wbvezxdw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gt2hhkugltu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jiagoushi.top/Article/details/gt2rqyfgtxm.html

[N10] 链表节点定义
来源：http://dali.chenjidiqi.icu/Article/details/gt2fvnmnfer.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.aibaodan.cn/Article/details/gt2oofnklke.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shuidangran.top/Article/details/gt2zpapyycu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yvedp.cn/Article/details/gt2spfupyyb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2twinwwra.html

Java: class Node { int v; Node next; }
来源：http://dali.9152youxi.cn/Article/details/gt2pjhhpmro.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.mhx1999.top/Article/details/gt2eblkycjr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ydzc1.top/Article/details/gt2mzclumnf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.guowangkeji.top/Article/details/gt2duhzhqrm.html

[N11] 二叉树中序遍历
来源：http://dali.shzxlz.cn/Article/details/gt2xirnxqbz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zycfv.cn/Article/details/gt2yxcqlfoy.html

PHP:  // 手写递归函数
来源：http://dali.xziqi.cn/Article/details/gt2kxkpvhwe.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhixingplan.top/Article/details/gt2slsqasnj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gt2pzrhjrpg.html

Java: // 手写递归
来源：http://dali.hnqzz.top/Article/details/gt2fbvwqdmg.html

Go:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gt2gvsvekqj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yongpay.top/Article/details/gt2jopdrnne.html

C#:   // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gt2lorrgosy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yvedp.cn/Article/details/gt2fhfreuxg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jyoumei.cn/Article/details/gt2lbwfonow.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.birdmap.top/Article/details/gt2xdturgtb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gt2xqvmxijg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenjidiqi.icu/Article/details/gt2xpouyown.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gt2cyvvubiq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hnxiangtu.top/Article/details/gt2hizvgolt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ppjwa.cn/Article/details/gt2xwcmqsgs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhengqikj.top/Article/details/gt2eupkmjwj.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2hueeuqzd.html

O. 并发与异步
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jgmnopig.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2fsibvcgi.html

[O01] 启动一个线程
来源：http://dali.316326.xyz/Article/details/gt2xxhlzbzn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nwrmaabz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gotoacloud.top/Article/details/gt2ogvytedu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ekvihfxq.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ozknzwgn.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dtffzqhj.html

Go:   go f()
来源：http://dali.yj20258888.top/Article/details/gt2ccbpfxcx.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2radgvavl.html

C#:   Task.Run(() => F());
来源：http://dali.gogol.net.cn/Article/details/gt2lpndzpyt.html

[O02] 使用线程池
来源：http://dali.hnxiangtu.top/Article/details/gt2rvhcjbpx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258888.top/Article/details/gt2azoihaud.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nanxinkj.top/Article/details/gt2qmidzsgv.html

JS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gt2lozlyydf.html

TS:   // worker_threads 线程池
来源：http://dali.hysaishi.cn/Article/details/gt2iwxxcphw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ydzc1.top/Article/details/gt2gkzcdpqp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxinkj.top/Article/details/gt2cvrzhomn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.kuanghao11.cn/Article/details/gt2ydwhqoow.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinqigufen.top/Article/details/gt2vbafgmul.html

[O03] 加锁保护共享数据
来源：http://dali.xuetiantiany.cn/Article/details/gt2pubttrrh.html

Py:   with lock: shared += 1
来源：http://dali.daxiang520.top/Article/details/gt2sfqcpvvm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hongshengwenyu.top/Article/details/gt2nytvabdg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gzhubu.top/Article/details/gt2kipiwsvl.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gt2itnuryqm.html

Java: synchronized (this) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dpocjryl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhoulong.xyz/Article/details/gt2fkyikqvx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dzeebkjy.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ybiukufe.html

[O04] 定义异步函数并等待
来源：http://dali.jqgfzy.top/Article/details/gt2jaeqrkyu.html

Py:   async def f():⏎    await g()
来源：http://dali.andypj.xyz/Article/details/gt2ylgxxlxf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ivvv.top/Article/details/gt2jtehmwzv.html

JS:   async function f() { await g(); }
来源：http://dali.gzhubu.top/Article/details/gt2oicdssod.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2tciyrehq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.havefunace.top/Article/details/gt2fbvvvggj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hfpthk.cn/Article/details/gt2zmhfcmum.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cdnleiting.top/Article/details/gt2hiwkpcka.html

C#:   async Task F() { await G(); }
来源：http://dali.yuanzhike.top/Article/details/gt2bublgdfb.html

[O05] 并发执行并等待全部完成
来源：http://dali.ppjwa.cn/Article/details/gt2bnsqbnjy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bumgqeev.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zycfv.cn/Article/details/gt2fvoxrurl.html

JS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gt2oluresup.html

TS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gt2pcnkwwxl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tanke756.top/Article/details/gt2qxwmuegz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.kuanghao11.cn/Article/details/gt2itdhqebr.html

Ruby: threads.map(&:join)
来源：http://dali.iojbl.cn/Article/details/gt2gnusxzvg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.9152youxi.cn/Article/details/gt2alvkpnng.html

[O06] 使用进程池
来源：http://dali.zycfv.cn/Article/details/gt2lyhplwyk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.smart0.xyz/Article/details/gt2ruevqumv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenlongwang.top/Article/details/gt2jkyhtvpz.html

JS:   // child_process / cluster 模块
来源：http://dali.yonumen.top/Article/details/gt2ulfuctur.html

TS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gt2vfwxlnhs.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cashguo.top/Article/details/gt2cjakyotn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.meibo888.top/Article/details/gt2ejxavakt.html

Ruby: // fork 块
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rstjnfhv.html

C#:   Parallel.For
来源：http://dali.jqgfzy.top/Article/details/gt2pgbpshbq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2twgylewv.html

P. 常用工具函数
来源：http://dali.wangdashe.top/Article/details/gt2zzrungha.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2xcvhtxdk.html

[P01] 生成 UUID
来源：http://dali.cheryme.top/Article/details/gt2eqjjhmoa.html

Py:   str(uuid.uuid4())
来源：http://dali.jlsjyb.cn/Article/details/gt2jkypgdqx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yongpay.top/Article/details/gt2icmfmgct.html

JS:   crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gt2msczvjqt.html

TS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gt2eygmtvdn.html

Java: UUID.randomUUID().toString()
来源：http://dali.bjfxy.top/Article/details/gt2nwisjnyq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.smart0.xyz/Article/details/gt2bkvmtiyb.html

Ruby: SecureRandom.uuid
来源：http://dali.wangshuangyany.cn/Article/details/gt2fuwcoutr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dyxmgbyc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigufen.top/Article/details/gt2dfecxbng.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.0kj1m.cn/Article/details/gt2edjkyzgd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnqzz.top/Article/details/gt2utbvhvwa.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.haohaochexian.top/Article/details/gt2kynrwyhc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhiwuduotai.top/Article/details/gt2beqgpxzv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nwbrower.top/Article/details/gt2bdcqrrik.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.svipenyu.cn/Article/details/gt2bzewljod.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.9152youxi.cn/Article/details/gt2teopqyrz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuetiantiany.cn/Article/details/gt2ghpihefr.html

[P03] 生成短随机字符串
来源：http://dali.yangfankeji.com/Article/details/gt2nanqcyms.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ehwqpu.com/Article/details/gt2exceecis.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnxiangtu.top/Article/details/gt2cxvvpnmb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gt2ypeinaji.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hfpthk.cn/Article/details/gt2atfmgaqg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yueranfly.top/Article/details/gt2iqwljjmf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cucudq.cn/Article/details/gt2jmkitcud.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhongyouzk.top/Article/details/gt2ravfoezm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.havefunace.top/Article/details/gt2qghvkdon.html

[P04] 求长度
来源：http://dali.zhixingplan.top/Article/details/gt2pxlcwcbq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ydzc1.top/Article/details/gt2ikqlojqf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gt2jyznqaoc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gt2rddxqcjw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gt2sxarnrxm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ivvv.top/Article/details/gt2wjumpkat.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258888.top/Article/details/gt2znffdigh.html

Ruby: x.length;  x.size
来源：http://dali.yonumen.top/Article/details/gt2yhrkqicd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tianlin.xyz/Article/details/gt2mdfopimx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sufxvd.cn/Article/details/gt2hntvbsvj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pengpengdd.cyou/Article/details/gt2xberhgjx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gcingpbb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hysaishi.cn/Article/details/gt2ymtnufzt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shzxlz.cn/Article/details/gt2vcvcebbg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shuidangran.top/Article/details/gt2gjsilmgc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2webmbdxy.html

Ruby: a == b
来源：http://dali.snrcjt.cn/Article/details/gt2ihbayrhv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenzaomai.com/Article/details/gt2vkiomwkd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hfpthk.cn/Article/details/gt2qmpdwutg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.meibo888.top/Article/details/gt2vjbfglcz.html

PHP:  if (empty($x)) {}
来源：http://dali.yj202588.top/Article/details/gt2zrkpwboj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gotoacloud.top/Article/details/gt2zqigcqca.html

TS:   if (x == null) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ansmplef.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gt2pfxbdjxa.html

Go:   if x == nil {}
来源：http://dali.hnxiangtu.top/Article/details/gt2nisimqci.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tian-w.cn/Article/details/gt2gyxwqjic.html

C#:   if (x is null) {}
来源：http://dali.chenlongwang.top/Article/details/gt2gxljnwvf.html

[P07] 防抖与节流
来源：http://dali.9152youxi.cn/Article/details/gt2ccemakcg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daxiang520.top/Article/details/gt2eqevbfgf.html

PHP:  // 手写时间戳比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jdmaallv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gt2lbvjsijr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gt2xejgiufh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rnhenpve.html


<!-- 参考信息 -->