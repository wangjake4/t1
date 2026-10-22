代发 wailian999

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gt2rlcceqne.html

JS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gt2tgzqiuor.html

TS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gt2smnkclnc.html

Java: System.getenv("HOME")
来源：http://dali.fengsongda.top/Article/details/gt2yfqsdixb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gt2nvamvief.html

Ruby: ENV["HOME"]
来源：http://dali.zhoulong.xyz/Article/details/gt2zgtxcgeq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2hbthfthv.html

[M03] 执行外部命令
来源：http://dali.hongshengwenyu.top/Article/details/gt2urdzubcg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj202588.top/Article/details/gt2smbfzxjq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.wangshuangyany.cn/Article/details/gt2owxnzfnf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gt2vmsywzbf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gt2rnfvegvb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yangfankeji.com/Article/details/gt2ibtyskjm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuanzhike.top/Article/details/gt2jffvhugk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuanzx.com/Article/details/gt2jzvtrjcb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xziqi.cn/Article/details/gt2guzywoth.html

[M04] 获取当前工作目录
来源：http://dali.jinqigfzy.top/Article/details/gt2eauqdvwr.html

Py:   os.getcwd()
来源：http://dali.chenlongwang.top/Article/details/gt2mgsqtxnp.html

PHP:  getcwd();
来源：http://dali.gzhubu.top/Article/details/gt2sxigjtkf.html

JS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gt2mvoyqios.html

TS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mnppqbtq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuxming.cn/Article/details/gt2pyitkoqa.html

Go:   os.Getwd()
来源：http://dali.sweek.top/Article/details/gt2njsuzpde.html

Ruby: Dir.pwd
来源：http://dali.guannengcc.top/Article/details/gt2sipruhjc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhoulong.xyz/Article/details/gt2rtwyndcc.html

[M05] 设置退出码
来源：http://dali.cucudq.cn/Article/details/gt2jqxuvbqn.html

Py:   sys.exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2kdvtkblu.html

PHP:  exit(1);
来源：http://dali.guowangkeji.top/Article/details/gt2lxotjjbo.html

JS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2kveyfwws.html

TS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2jxsiwbsz.html

Java: System.exit(1)
来源：http://dali.xylfe.cn/Article/details/gt2zvfggtxy.html

Go:   os.Exit(1)
来源：http://dali.c1oappe.top/Article/details/gt2wjwqlxxy.html

Ruby: exit 1
来源：http://dali.sxryk.cn/Article/details/gt2mxkzhkij.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gt2phfwbwau.html

[M06] 向标准错误输出
来源：http://dali.snrcjt.cn/Article/details/gt2zrsiswxh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gt2lehozufe.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xinyue.icu/Article/details/gt2ehvgqjff.html

JS:   console.error("err")
来源：http://dali.jlsjyb.cn/Article/details/gt2pnlyxszc.html

TS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gt2flmffnap.html

Java: System.err.println("err")
来源：http://dali.guowangkeji.top/Article/details/gt2wdjpjjrp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258.top/Article/details/gt2yezcebpm.html

Ruby: warn "err"
来源：http://dali.hammf.cn/Article/details/gt2ijpgovuf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258888.top/Article/details/gt2sdklzzpy.html

[M07] 判断是否为主入口
来源：http://dali.ydzc1.top/Article/details/gt2zandhpyb.html

Py:   if __name__ == "__main__":
来源：http://dali.zhongyouzk.top/Article/details/gt2tqwvbnrh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhengqikj.top/Article/details/gt2zgoktyjf.html

JS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gt2xsypwywa.html

TS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gt2edufcicw.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2djgwidtj.html

Go:   func main()
来源：http://dali.fengsongda.top/Article/details/gt2sloiepxs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fzhhl.top/Article/details/gt2vzvemsbw.html

C#:   static void Main(string[] args)
来源：http://dali.yangfankeji.com/Article/details/gt2bvmntgoe.html

[M08] 获取系统与运行时信息
来源：http://dali.hfpthk.cn/Article/details/gt2cwheqelk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wbvptmrm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.smart0.xyz/Article/details/gt2fzofgbgh.html

JS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gt2jsgvogxi.html

TS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gt2sjtdlqlp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gt2syoyxkqf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lezjwuzu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ivvv.top/Article/details/gt2tfpdobos.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jianghu66.top/Article/details/gt2scbkdgdi.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2andheqad.html

N. 数据结构与算法
来源：http://dali.yj202588.top/Article/details/gt2eoataubg.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2chntwjqi.html

[N01] 二分查找（有序数组）
来源：http://dali.zhiwuduotai.top/Article/details/gt2rrrnnrmf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gt2vwclavjc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ecbmnogs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ixqlsyde.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnqzz.top/Article/details/gt2itlzzkdd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2oipatwom.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2zkjotqhy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cashguo.top/Article/details/gt2dyvjkxvn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2knlnljge.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shuidangran.top/Article/details/gt2nqpkbdqh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ppjwa.cn/Article/details/gt2qgpeseqv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tian-w.cn/Article/details/gt2erwykuef.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gt2vynfziwd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gt2jhsvsadv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dashuyun.cn/Article/details/gt2kqkkghpa.html

Go:   slices.Sort(arr)
来源：http://dali.tian-w.cn/Article/details/gt2fsqltdgk.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gt2vbafbubg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fengsongda.top/Article/details/gt2birxtjwh.html

[N03] 快速排序（分治示例）
来源：http://dali.zhongyouzk.top/Article/details/gt2yetfulcd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pycfn.com/Article/details/gt2cgowauzn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258888.top/Article/details/gt2brzoqdoi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gt2aryppvxx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gt2omklqzgw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yanxiufei.cn/Article/details/gt2femyeeim.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangshuangyany.cn/Article/details/gt2vudiatop.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wyuxkgnd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cqqwz.cn/Article/details/gt2mqpctzpa.html

[N04] 斐波那契数列
来源：http://dali.zhiwuduotai.top/Article/details/gt2bvxkawzk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daxiang520.top/Article/details/gt2uognfchf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258.top/Article/details/gt2syvulccn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gt2azkoxshv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gt2ldjzksvs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gt2akhpihcs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.snrcjt.cn/Article/details/gt2vazwmxgs.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aoxggdyt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gt2oygrmwzu.html

[N05] 最大公约数
来源：http://dali.smart0.xyz/Article/details/gt2qijdcihd.html

Py:   math.gcd(a, b)
来源：http://dali.xylfe.cn/Article/details/gt2pyfjbjjr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258888.top/Article/details/gt2laggscat.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gt2qplbvwir.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gt2avcsadms.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pengpengdd.cyou/Article/details/gt2aeenzxkl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sxryk.cn/Article/details/gt2ylsirdyl.html

Ruby: a.gcd(b)
来源：http://dali.sweek.top/Article/details/gt2mukbtpfg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shuidangran.top/Article/details/gt2pissbcob.html

[N06] 判断回文字符串
来源：http://dali.ivvv.top/Article/details/gt2grzslxjy.html

Py:   s == s[::-1]
来源：http://dali.hnqzz.top/Article/details/gt2llmwbicy.html

PHP:  $s === strrev($s);
来源：http://dali.ybcxt.top/Article/details/gt2plugonvt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gt2nuwxnmwp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2essthlmt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tanke756.top/Article/details/gt2zjahadux.html

Go:   // 双指针从两端比较
来源：http://dali.jiagoushi.top/Article/details/gt2tvqimeln.html

Ruby: s == s.reverse
来源：http://dali.ydzc1.top/Article/details/gt2hotvxsda.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gt2gtfjjkfi.html

[N07] 两数之和（返回下标）
来源：http://dali.yvedp.cn/Article/details/gt2zrzmfbmj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guowangkeji.top/Article/details/gt2pfirylok.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.birdmap.top/Article/details/gt2lbgeerzh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zdqjudy.top/Article/details/gt2uposzgbb.html

TS:   // 手写 Map<string, number>
来源：http://dali.cdnleiting.top/Article/details/gt2tvzsuhdx.html

Java: // 手写 HashMap
来源：http://dali.cqqwz.cn/Article/details/gt2loffqred.html

Go:   // 手写 map[int]int
来源：http://dali.chenlongwang.top/Article/details/gt2cpwjgxyw.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gt2xcmklfxu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gotoacloud.top/Article/details/gt2xjxtjukb.html

[N08] 生成全排列
来源：http://dali.yanxiufei.cn/Article/details/gt2kukfffzs.html

Py:   itertools.permutations(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2ilvnjvah.html

PHP:  // 手写递归交换
来源：http://dali.zhengqikj.top/Article/details/gt2zsnttufm.html

JS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2kwiryvjs.html

TS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gt2fhbfimar.html

Java: // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gt2swfhiogp.html

Go:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gt2xhxlwcrm.html

Ruby: arr.permutation.to_a
来源：http://dali.xziqi.cn/Article/details/gt2hxmamgon.html

C#:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gt2xgjhbmar.html

[N09] 栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2vvkhjtgz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yonumen.top/Article/details/gt2mrtijoqm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.c1oappe.top/Article/details/gt2zffwbfyp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gt2rrsdtrul.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fengsongda.top/Article/details/gt2rkzntgtk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258888.top/Article/details/gt2mdfrigzj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xuetiantiany.cn/Article/details/gt2atigykvw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gt2eficdedc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gt2tknpxwjw.html

[N10] 链表节点定义
来源：http://dali.wangdashe.top/Article/details/gt2pisnqsnh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ehwqpu.com/Article/details/gt2cosajutc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj20258888.top/Article/details/gt2mzqrghpo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cheryme.top/Article/details/gt2lfoskupk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zdqjudy.top/Article/details/gt2epipqyik.html

Java: class Node { int v; Node next; }
来源：http://dali.shuidangran.top/Article/details/gt2xvrsfyze.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbroeqq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.dashuyun.cn/Article/details/gt2desanhjd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.9152youxi.cn/Article/details/gt2nundlnzp.html

[N11] 二叉树中序遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2vkwexinj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xylfe.cn/Article/details/gt2eivmkfor.html

PHP:  // 手写递归函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2jdbjttgf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gt2luorpekr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gt2osangtpg.html

Java: // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gt2gewnslzd.html

Go:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gt2wolziybd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shangyingyoupin.top/Article/details/gt2xnvmhiyo.html

C#:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gt2supidezh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sweek.top/Article/details/gt2wtezbaqb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jiagoushi.top/Article/details/gt2vtivqpyl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jlsjyb.cn/Article/details/gt2tpklzcyf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.snrcjt.cn/Article/details/gt2qiohphgt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.mhx1999.top/Article/details/gt2auljecwx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gt2rqnuujmi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gogol.net.cn/Article/details/gt2jlwguxmf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hywenlv.cn/Article/details/gt2xgsxulbs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gt2xfwninwv.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kovqqcfm.html

O. 并发与异步
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tzajejtv.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2jdhizbxm.html

[O01] 启动一个线程
来源：http://dali.jiagoushi.top/Article/details/gt2dtpuzcfe.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.9152youxi.cn/Article/details/gt2nlumybnk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cqqwz.cn/Article/details/gt2sayszrxi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gotoacloud.top/Article/details/gt2nbkjphgi.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gt2qpseqeyz.html

Java: new Thread(() -> f()).start()
来源：http://dali.nanxinkj.top/Article/details/gt2sohodqdb.html

Go:   go f()
来源：http://dali.ehwqpu.com/Article/details/gt2lteuwcrp.html

Ruby: Thread.new { f }
来源：http://dali.fzhhl.top/Article/details/gt2drzxrwda.html

C#:   Task.Run(() => F());
来源：http://dali.sufxvd.cn/Article/details/gt2qgipjaxh.html

[O02] 使用线程池
来源：http://dali.cheryme.top/Article/details/gt2ebegctlp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhengqikj.top/Article/details/gt2dxaecrqa.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yueranfly.top/Article/details/gt2kjqbmpsj.html

JS:   // worker_threads 线程池
来源：http://dali.pycfn.com/Article/details/gt2snwymnpg.html

TS:   // worker_threads 线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2geelnfhv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj202588.top/Article/details/gt2zigrkjgv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.guowangkeji.top/Article/details/gt2yhcfpxap.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.9152youxi.cn/Article/details/gt2lgjyiklq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gzhubu.top/Article/details/gt2upwsocms.html

[O03] 加锁保护共享数据
来源：http://dali.xinyue.icu/Article/details/gt2mwfvudjj.html

Py:   with lock: shared += 1
来源：http://dali.vqdsnc.cn/Article/details/gt2efbwpnki.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ivvv.top/Article/details/gt2cpkbvzwe.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hywenlv.cn/Article/details/gt2lzmexpww.html

TS:   // 同 JS
来源：http://dali.dianchejie.cn/Article/details/gt2cvbsxcaq.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aphkuylg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnxiangtu.top/Article/details/gt2kgfvklzp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhoulong.xyz/Article/details/gt2nnslstzz.html

C#:   lock (gate) { shared++; }
来源：http://dali.yangfankeji.com/Article/details/gt2maznwskl.html

[O04] 定义异步函数并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tevepufc.html

Py:   async def f():⏎    await g()
来源：http://dali.yj20258888.top/Article/details/gt2uzhmtkie.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxinkj.top/Article/details/gt2nqsgzeph.html

JS:   async function f() { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gt2imevmgxl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yrslpvsj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zdqjudy.top/Article/details/gt2omkaxlyv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.svipenyu.cn/Article/details/gt2lptjhhjl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dashuyun.cn/Article/details/gt2zrftcjje.html

C#:   async Task F() { await G(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2mzjetulp.html

[O05] 并发执行并等待全部完成
来源：http://dali.nanxinkj.top/Article/details/gt2oygpeyci.html

Py:   asyncio.gather(*tasks)
来源：http://dali.iojbl.cn/Article/details/gt2enjyppen.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sgjdhgej.html

JS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gt2fvvcqgfl.html

TS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gt2nlfupepd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yanxiufei.cn/Article/details/gt2htobmixg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yvedp.cn/Article/details/gt2dzbmkjzm.html

Ruby: threads.map(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gt2plkudtzs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sweek.top/Article/details/gt2hqtnyjje.html

[O06] 使用进程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ghlbnkog.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fzhhl.top/Article/details/gt2pfghbphy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zdqjudy.top/Article/details/gt2lusbamdi.html

JS:   // child_process / cluster 模块
来源：http://dali.hongshengwenyu.top/Article/details/gt2ithcsolt.html

TS:   // child_process / cluster 模块
来源：http://dali.pengpengdd.cyou/Article/details/gt2aozavzio.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dszyyaaw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hysaishi.cn/Article/details/gt2kqchlljd.html

Ruby: // fork 块
来源：http://dali.guowangkeji.top/Article/details/gt2tfbnapka.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuziwlb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2yhuuzaor.html

P. 常用工具函数
来源：http://dali.aibaodan.cn/Article/details/gt2viurefvc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2xgtstsrb.html

[P01] 生成 UUID
来源：http://dali.zhoulong.xyz/Article/details/gt2kzdgkbzv.html

Py:   str(uuid.uuid4())
来源：http://dali.sufxvd.cn/Article/details/gt2hgpopgkk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tian-w.cn/Article/details/gt2ekyozzdg.html

JS:   crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gt2xllsttno.html

TS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gt2doylltvl.html

Java: UUID.randomUUID().toString()
来源：http://dali.xziqi.cn/Article/details/gt2rhafqcvb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zvbgtwzz.html

Ruby: SecureRandom.uuid
来源：http://dali.tianlin.xyz/Article/details/gt2iqnxpcmq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zdqjudy.top/Article/details/gt2dkrfpmsm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gotoacloud.top/Article/details/gt2heksqgnd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hfpthk.cn/Article/details/gt2stejvzhg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2cfabrnkf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xuanzx.com/Article/details/gt2vhurgkzy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj202588.top/Article/details/gt2lurqrdyt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qvllbfgb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ivvv.top/Article/details/gt2vyffrlit.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.316326.xyz/Article/details/gt2pyyoqazq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yongpay.top/Article/details/gt2flyinkmi.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xerpdkhr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xziqi.cn/Article/details/gt2oabeodct.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sweek.top/Article/details/gt2iuasxahp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gt2bhfvjzsy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gt2flmqvplu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uggnszlt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinqigufen.top/Article/details/gt2oxtkkwvz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cucudq.cn/Article/details/gt2ljnqbzqg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fzhhl.top/Article/details/gt2tdfkaxjd.html

[P04] 求长度
来源：http://dali.snrcjt.cn/Article/details/gt2lzppsqwt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fyeswcdq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gt2cqnbmvfg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nwbrower.top/Article/details/gt2yfmledbv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gt2vqrewwzd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258888.top/Article/details/gt2ugydnokp.html

Go:   len(arr);  len(m)
来源：http://dali.vqdsnc.cn/Article/details/gt2quyxozoe.html

Ruby: x.length;  x.size
来源：http://dali.yanxiufei.cn/Article/details/gt2hfkdpygg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gt2pbzgpyqb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jyoumei.cn/Article/details/gt2yhqghxig.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.aizwys.cn/Article/details/gt2ymvkizpy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yuxming.cn/Article/details/gt2ciotmprl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guowangkeji.top/Article/details/gt2wqioxkyj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gt2doxrhpja.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guowangkeji.top/Article/details/gt2oswzcyba.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tian-w.cn/Article/details/gt2pyprtyma.html

Ruby: a == b
来源：http://dali.smart0.xyz/Article/details/gt2luabvyik.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.aibaodan.cn/Article/details/gt2porrmums.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnxiangtu.top/Article/details/gt2xmspzyiy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.svipenyu.cn/Article/details/gt2pdjjxujq.html

PHP:  if (empty($x)) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2hkxszmtx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hammf.cn/Article/details/gt2imhlvqmo.html

TS:   if (x == null) {}
来源：http://dali.aibaodan.cn/Article/details/gt2gukauvzr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2mbiygxxa.html

Go:   if x == nil {}
来源：http://dali.jqgfzy.top/Article/details/gt2derpsxns.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xylfe.cn/Article/details/gt2qfdkhppx.html

C#:   if (x is null) {}
来源：http://dali.zhixingplan.top/Article/details/gt2nigqxrbs.html

[P07] 防抖与节流
来源：http://dali.aibaodan.cn/Article/details/gt2gevpputz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xylfe.cn/Article/details/gt2imcxxkto.html

PHP:  // 手写时间戳比较
来源：http://dali.dashuyun.cn/Article/details/gt2ceynahul.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gt2vqokobyy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gt2lfyvydkf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ivbpzijj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenlongwang.top/Article/details/gt2ohcvrksi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ptqbchas.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.bjfxy.top/Article/details/gt2zzioenak.html

[P08] 处理浮点精度问题
来源：http://dali.yj20258.top/Article/details/gt2zfkipoas.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yongpay.top/Article/details/gt2suytnusf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.smart0.xyz/Article/details/gt2mscamaap.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oaikiuxg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xuanzx.com/Article/details/gt2ddoszlxa.html


<!-- 参考信息 -->