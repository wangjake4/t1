代发 wailian999

JS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gt2nuxtcbyj.html

TS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gt2defybxli.html

Java: args 数组（main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gt2twrjhjds.html

Go:   os.Args[1:]
来源：http://dali.daria6918.cn/Article/details/gt2xwemxflg.html

Ruby: ARGV
来源：http://dali.zhoulong.xyz/Article/details/gt2gecxrqfi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gt2epwfogvf.html

[M02] 读取环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gqdbjles.html

Py:   os.environ.get("HOME")
来源：http://dali.cheryme.top/Article/details/gt2pdbyuuyz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gt2umqsoehh.html

JS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gt2pnzfmmba.html

TS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gt2czbdltyy.html

Java: System.getenv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gt2tkcdgffl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nwbrower.top/Article/details/gt2yzmwryci.html

Ruby: ENV["HOME"]
来源：http://dali.bjfxy.top/Article/details/gt2rfqfwebs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mluksfys.html

[M03] 执行外部命令
来源：http://dali.chenjidiqi.icu/Article/details/gt2ezoprxji.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cashguo.top/Article/details/gt2mppglvmm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinqigfzy.top/Article/details/gt2bouqnuqf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gt2peiouxch.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gt2ycacbrle.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cdnleiting.top/Article/details/gt2adyfclbw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jianghu66.top/Article/details/gt2wyspbdyz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.birdmap.top/Article/details/gt2xasimrdj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pycfn.com/Article/details/gt2evsqdjws.html

[M04] 获取当前工作目录
来源：http://dali.haohaochexian.top/Article/details/gt2wpeuavqs.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jjtttgld.html

PHP:  getcwd();
来源：http://dali.jianghu66.top/Article/details/gt2otnwcjpv.html

JS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2hnflidks.html

TS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gt2adeexlkb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.vqdsnc.cn/Article/details/gt2rxanmwzh.html

Go:   os.Getwd()
来源：http://dali.yuanzhike.top/Article/details/gt2lrqznnda.html

Ruby: Dir.pwd
来源：http://dali.zhoulong.xyz/Article/details/gt2qigmplhw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.redwolf501.top/Article/details/gt2inzxfihn.html

[M05] 设置退出码
来源：http://dali.nanxinkj.top/Article/details/gt2drkhzkgp.html

Py:   sys.exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2wqhftili.html

PHP:  exit(1);
来源：http://dali.gaohongyu789.top/Article/details/gt2gkymbxfq.html

JS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2rqtkbzgl.html

TS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2azstqpzj.html

Java: System.exit(1)
来源：http://dali.bjfxy.top/Article/details/gt2nfjudnzo.html

Go:   os.Exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2beatbram.html

Ruby: exit 1
来源：http://dali.gzhubu.top/Article/details/gt2vgefplmq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnxiangtu.top/Article/details/gt2hdpoidnv.html

[M06] 向标准错误输出
来源：http://dali.jqgufenzy.top/Article/details/gt2zfsvbpci.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gogol.net.cn/Article/details/gt2pwogybsy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sysykeji.top/Article/details/gt2bmyewqlt.html

JS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gt2rtyrrrwc.html

TS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gt2pxqjvinu.html

Java: System.err.println("err")
来源：http://dali.meibo888.top/Article/details/gt2sfwzwaie.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.svipenyu.cn/Article/details/gt2ftbzyryn.html

Ruby: warn "err"
来源：http://dali.fzhhl.top/Article/details/gt2hcljuybg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.0kj1m.cn/Article/details/gt2ffvviwof.html

[M07] 判断是否为主入口
来源：http://dali.yuanzhike.top/Article/details/gt2cthutczn.html

Py:   if __name__ == "__main__":
来源：http://dali.shuidangran.top/Article/details/gt2eiffiofg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.0kj1m.cn/Article/details/gt2rlldsxht.html

JS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gt2iwhlxlqf.html

TS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gt2njvsiuhj.html

Java: public static void main(String[] args)
来源：http://dali.0kj1m.cn/Article/details/gt2cmyerrbv.html

Go:   func main()
来源：http://dali.xinyue.icu/Article/details/gt2jjzuwhpw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gotoacloud.top/Article/details/gt2zvapevqd.html

C#:   static void Main(string[] args)
来源：http://dali.yongpay.top/Article/details/gt2clvpjhfa.html

[M08] 获取系统与运行时信息
来源：http://dali.hammf.cn/Article/details/gt2ayrdzxqy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shuidangran.top/Article/details/gt2bbweijyh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hongshengwenyu.top/Article/details/gt2tgnokskg.html

JS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gt2pwvdandp.html

TS:   process.platform;  process.version
来源：http://dali.jianghu66.top/Article/details/gt2ysjjxdjf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xylfe.cn/Article/details/gt2urplrpll.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zrohqrtp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangshuangyany.cn/Article/details/gt2tcvpslif.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hysaishi.cn/Article/details/gt2rujljycl.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2bswffndv.html

N. 数据结构与算法
来源：http://dali.ivvv.top/Article/details/gt2gknmtxlf.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2cnndtlhw.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ruzyanhf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2brckiqwh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.meibo888.top/Article/details/gt2ixyibuno.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gt2tapkvlni.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gt2klllqjlz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gt2jhtvlwhf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ohmsdyoo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shzxlz.cn/Article/details/gt2fazhivgc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ysbgdubi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.0kj1m.cn/Article/details/gt2cqyddmvl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mjtebnpz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ppjwa.cn/Article/details/gt2ygrmvwtz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gt2yfcdcsde.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gt2hprcejxg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yonumen.top/Article/details/gt2wwarhcqc.html

Go:   slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2egbztndi.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gt2yeuwmqfa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yangfankeji.com/Article/details/gt2exyztdzj.html

[N03] 快速排序（分治示例）
来源：http://dali.yj202588.top/Article/details/gt2prbzepei.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shzxlz.cn/Article/details/gt2ljhlrals.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hzfgzzme.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gt2wfopwloo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gt2wwkygmug.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tianlin.xyz/Article/details/gt2kodtmfcj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aibaodan.cn/Article/details/gt2xetgzirh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nwbrower.top/Article/details/gt2qrbwhwbv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hysaishi.cn/Article/details/gt2bkipggsf.html

[N04] 斐波那契数列
来源：http://dali.316326.xyz/Article/details/gt2rjbbvevh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jiagoushi.top/Article/details/gt2rxqxnjww.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tian-w.cn/Article/details/gt2vkfdyduj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gt2hgfrjazx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eyiuyfcv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jianghu66.top/Article/details/gt2wbvtbwil.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cdnleiting.top/Article/details/gt2qklaromr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mfmwqihz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kqojworm.html

[N05] 最大公约数
来源：http://dali.zdqjudy.top/Article/details/gt2skeydcql.html

Py:   math.gcd(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gt2yjagdnmp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aibaodan.cn/Article/details/gt2gzgcknwg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gt2amuvgvfz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gt2mgpombhh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dashuyun.cn/Article/details/gt2lhrkqlyi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aizwys.cn/Article/details/gt2wlxpofkh.html

Ruby: a.gcd(b)
来源：http://dali.yj20258.top/Article/details/gt2hiimxnub.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.kuanghao11.cn/Article/details/gt2umtkrnat.html

[N06] 判断回文字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2cnnrrxdt.html

Py:   s == s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2hwvwygam.html

PHP:  $s === strrev($s);
来源：http://dali.yj202588.top/Article/details/gt2doseacxw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2ainyhqnq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wsiofdzg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xerzhybw.html

Go:   // 双指针从两端比较
来源：http://dali.yj20258888.top/Article/details/gt2gbezylgq.html

Ruby: s == s.reverse
来源：http://dali.316326.xyz/Article/details/gt2uxkzlukg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gt2piggkcbo.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258.top/Article/details/gt2rvwebyff.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yongpay.top/Article/details/gt2ifvtgjxy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ehwqpu.com/Article/details/gt2kugamsci.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shuidangran.top/Article/details/gt2nkbulobv.html

TS:   // 手写 Map<string, number>
来源：http://dali.guannengcc.top/Article/details/gt2fwfokzny.html

Java: // 手写 HashMap
来源：http://dali.feifeiyinyue.top/Article/details/gt2ukumjltd.html

Go:   // 手写 map[int]int
来源：http://dali.sysykeji.top/Article/details/gt2dowrafru.html

Ruby: // 手写 Hash
来源：http://dali.9152youxi.cn/Article/details/gt2jgpamdca.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ayumcoku.html

[N08] 生成全排列
来源：http://dali.aizwys.cn/Article/details/gt2yuwiaunu.html

Py:   itertools.permutations(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zsjzrvej.html

PHP:  // 手写递归交换
来源：http://dali.yongpay.top/Article/details/gt2wartjvxh.html

JS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gt2gekxwtoq.html

TS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gt2iyanyxya.html

Java: // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2tbrnhnyz.html

Go:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gt2utkeewgn.html

Ruby: arr.permutation.to_a
来源：http://dali.sysykeji.top/Article/details/gt2qcoinjfs.html

C#:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2zpnleezb.html

[N09] 栈与队列
来源：http://dali.cashguo.top/Article/details/gt2uxfootfw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gaohongyu789.top/Article/details/gt2uozcodzt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wykqvmda.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gt2kbtmthza.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ybcxt.top/Article/details/gt2oyljwjjq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gzhubu.top/Article/details/gt2wnivdzsa.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2duawtcyy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gt2uqsvhzpm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jyoumei.cn/Article/details/gt2ycsbrkby.html

[N10] 链表节点定义
来源：http://dali.tanke756.top/Article/details/gt2ifmtlrik.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenlongwang.top/Article/details/gt2ruabkmmw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pkhbixcs.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jianghu66.top/Article/details/gt2pvjldunk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yuanzhike.top/Article/details/gt2ceovooyn.html

Java: class Node { int v; Node next; }
来源：http://dali.yvedp.cn/Article/details/gt2onubfshv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.snrcjt.cn/Article/details/gt2qflosark.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hscjugdi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.birdmap.top/Article/details/gt2onttbcrt.html

[N11] 二叉树中序遍历
来源：http://dali.havefunace.top/Article/details/gt2dwjfxgbh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hammf.cn/Article/details/gt2muzrhfac.html

PHP:  // 手写递归函数
来源：http://dali.ppjwa.cn/Article/details/gt2ucffgchf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gt2uyekqagf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pengpengdd.cyou/Article/details/gt2kdofddza.html

Java: // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gt2kqsbockl.html

Go:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gt2wurhsiru.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinqigufen.top/Article/details/gt2cccqaxng.html

C#:   // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gt2ijlwbbkl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.pengpengdd.cyou/Article/details/gt2byybwfee.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gotoacloud.top/Article/details/gt2sovihmne.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xuetiantiany.cn/Article/details/gt2njyneeoh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gt2dziklwmo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sufxvd.cn/Article/details/gt2olpccurw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gt2kdjuistc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sufxvd.cn/Article/details/gt2zeuxdgpd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuxming.cn/Article/details/gt2wyhefiri.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gt2bnvwnsxu.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2truadcur.html

O. 并发与异步
来源：http://dali.zhixingplan.top/Article/details/gt2zlwwwybm.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2jvuyvxpf.html

[O01] 启动一个线程
来源：http://dali.jyoumei.cn/Article/details/gt2sbnarxbj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vymveguz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gzhubu.top/Article/details/gt2xzykznjd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cqqwz.cn/Article/details/gt2mcpyirua.html

TS:   // 同 JS
来源：http://dali.pengpengdd.cyou/Article/details/gt2hytkivec.html

Java: new Thread(() -> f()).start()
来源：http://dali.xziqi.cn/Article/details/gt2mzvewmrv.html

Go:   go f()
来源：http://dali.nwbrower.top/Article/details/gt2ldkxupos.html

Ruby: Thread.new { f }
来源：http://dali.jianghu66.top/Article/details/gt2huexoyqh.html

C#:   Task.Run(() => F());
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vvggthvw.html

[O02] 使用线程池
来源：http://dali.fzhhl.top/Article/details/gt2xvqvakxa.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.bjfxy.top/Article/details/gt2tqrldtdo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cashguo.top/Article/details/gt2zqjksdmj.html

JS:   // worker_threads 线程池
来源：http://dali.jlsjyb.cn/Article/details/gt2zscaibdo.html

TS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gt2gbmiaznr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.9152youxi.cn/Article/details/gt2qrzcnqfu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vywcixnx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xylfe.cn/Article/details/gt2execzgyc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.aizwys.cn/Article/details/gt2tkqcdkum.html

[O03] 加锁保护共享数据
来源：http://dali.snrcjt.cn/Article/details/gt2kislrpmy.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzwukaf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sysykeji.top/Article/details/gt2xhcmmfaa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sufxvd.cn/Article/details/gt2josrgdpr.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gt2fbjylfmq.html

Java: synchronized (this) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gt2domlmepj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.svipenyu.cn/Article/details/gt2vxytwcap.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yanxiufei.cn/Article/details/gt2zcconizp.html

C#:   lock (gate) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gt2htfaaxjg.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ttorqdbu.html

Py:   async def f():⏎    await g()
来源：http://dali.kuanghao11.cn/Article/details/gt2tawyqflw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hnqzz.top/Article/details/gt2lufuexqe.html

JS:   async function f() { await g(); }
来源：http://dali.hammf.cn/Article/details/gt2oasbzewu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2kbzouhdv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fzhhl.top/Article/details/gt2wywvzvke.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenjidiqi.icu/Article/details/gt2oseckino.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ybcxt.top/Article/details/gt2rdsukscg.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcfgmtl.html

[O05] 并发执行并等待全部完成
来源：http://dali.ppjwa.cn/Article/details/gt2zeoqurbn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tanke756.top/Article/details/gt2vhvgknka.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hammf.cn/Article/details/gt2bdfakfkj.html

JS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gt2rrgnlsmm.html

TS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gt2wkexkbpq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhoulong.xyz/Article/details/gt2ynqvnfie.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guowangkeji.top/Article/details/gt2wnkhsjqs.html

Ruby: threads.map(&:join)
来源：http://dali.mhx1999.top/Article/details/gt2ruodsxwe.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hfpthk.cn/Article/details/gt2xqkmnnpz.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2agzydnnh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shuidangran.top/Article/details/gt2opwhnekq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xuanzx.com/Article/details/gt2jhhzssbx.html

JS:   // child_process / cluster 模块
来源：http://dali.xuetiantiany.cn/Article/details/gt2segmzgdh.html

TS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gt2aljcvzdz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.0kj1m.cn/Article/details/gt2etrmaexe.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.guannengcc.top/Article/details/gt2lhxibxgm.html

Ruby: // fork 块
来源：http://dali.smart0.xyz/Article/details/gt2mmvfsuuu.html

C#:   Parallel.For
来源：http://dali.quarkkingdee.top/Article/details/gt2cbpvhrvs.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2fmvgyplt.html

P. 常用工具函数
来源：http://dali.c1oappe.top/Article/details/gt2uwznrugy.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rsrofqmw.html

[P01] 生成 UUID
来源：http://dali.vqdsnc.cn/Article/details/gt2mfcebxhs.html

Py:   str(uuid.uuid4())
来源：http://dali.haohaochexian.top/Article/details/gt2qemrlpvq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jqgfzy.top/Article/details/gt2cmxesoyr.html

JS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uiieolzl.html

TS:   crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gt2uqotigpj.html

Java: UUID.randomUUID().toString()
来源：http://dali.chenzaomai.com/Article/details/gt2rfqrlqje.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gt2ohhkijzu.html

Ruby: SecureRandom.uuid
来源：http://dali.hysaishi.cn/Article/details/gt2szrsoowd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hammf.cn/Article/details/gt2zpcklzfq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.kuanghao11.cn/Article/details/gt2faxgwowu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ixiugaia.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yueranfly.top/Article/details/gt2dgftbzps.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenzaomai.com/Article/details/gt2hawstnby.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yonumen.top/Article/details/gt2vexwueza.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nwbrower.top/Article/details/gt2cuqagxju.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.pengpengdd.cyou/Article/details/gt2ketwgwdv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jyoumei.cn/Article/details/gt2tojmrfik.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnxiangtu.top/Article/details/gt2kwjvowup.html

[P03] 生成短随机字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2pgbpvotm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenlongwang.top/Article/details/gt2kjckjtin.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.meibo888.top/Article/details/gt2hppchamc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2mkglnqiw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2ktqtmqjy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.mhx1999.top/Article/details/gt2sgweammq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sgtauims.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.andypj.xyz/Article/details/gt2cneejahh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zdqjudy.top/Article/details/gt2ziqjqrad.html

[P04] 求长度
来源：http://dali.fzhhl.top/Article/details/gt2nzytvixq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zdqjudy.top/Article/details/gt2rytowmff.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwxjjgx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sufxvd.cn/Article/details/gt2hewwxugl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fjftmxhg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cheryme.top/Article/details/gt2zoxbgvng.html

Go:   len(arr);  len(m)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kbnbqdkb.html

Ruby: x.length;  x.size
来源：http://dali.sxryk.cn/Article/details/gt2rrewoqtz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zycfv.cn/Article/details/gt2xsoqceie.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinqigfzy.top/Article/details/gt2gddwiyod.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cqqwz.cn/Article/details/gt2fnjcqlqr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhoulong.xyz/Article/details/gt2yvoacpge.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.aizwys.cn/Article/details/gt2fmnsreqo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yangfankeji.com/Article/details/gt2tcrlfyfm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nanxuanxn.top/Article/details/gt2ehmfuhfo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.pycfn.com/Article/details/gt2yfsnrcmg.html

Ruby: a == b
来源：http://dali.chenjidiqi.icu/Article/details/gt2nortnhmy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnqzz.top/Article/details/gt2ueyfvmjb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jianghu66.top/Article/details/gt2emyxquia.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinqigufen.top/Article/details/gt2butniyrg.html

PHP:  if (empty($x)) {}
来源：http://dali.cqqwz.cn/Article/details/gt2ngqmqtum.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.haohaochexian.top/Article/details/gt2iddipelm.html

TS:   if (x == null) {}
来源：http://dali.meibo888.top/Article/details/gt2inpaufqo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2tsfqpjea.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2udjlojpe.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ywxbhqbb.html

C#:   if (x is null) {}
来源：http://dali.chenzaomai.com/Article/details/gt2ieopjjth.html

[P07] 防抖与节流
来源：http://dali.cashguo.top/Article/details/gt2crltcxqd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sweek.top/Article/details/gt2hsulhqnc.html

PHP:  // 手写时间戳比较
来源：http://dali.sweek.top/Article/details/gt2kcmjkixz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gt2cisyfuuj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gt2zhyzqopw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2eybhqkyd.html


<!-- 参考信息 -->