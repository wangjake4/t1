代发 wailian999

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2abhjufjc.html

JS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gt2honrqzsi.html

TS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gt2lkgwrrqt.html

Java: System.getenv("HOME")
来源：http://dali.wangdashe.top/Article/details/gt2ruywkzce.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2rwuonzmw.html

Ruby: ENV["HOME"]
来源：http://dali.zycfv.cn/Article/details/gt2ukwdubgy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yueranfly.top/Article/details/gt2bljjjfgd.html

[M03] 执行外部命令
来源：http://dali.feifeiyinyue.top/Article/details/gt2cxehejqm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zycfv.cn/Article/details/gt2hhffznko.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cheryme.top/Article/details/gt2xrfgreon.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gt2vyppfagu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gt2wqqdccil.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hysaishi.cn/Article/details/gt2rbhsnpfe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aizwys.cn/Article/details/gt2wpioovyl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cqqwz.cn/Article/details/gt2gfumtfqz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xinyue.icu/Article/details/gt2lssfovxe.html

[M04] 获取当前工作目录
来源：http://dali.sweek.top/Article/details/gt2almtzadx.html

Py:   os.getcwd()
来源：http://dali.smart0.xyz/Article/details/gt2huenfmmi.html

PHP:  getcwd();
来源：http://dali.xuetiantiany.cn/Article/details/gt2rwvaiwyh.html

JS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gt2gqjqixzt.html

TS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gt2ingvjvfc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sufxvd.cn/Article/details/gt2rryoifgh.html

Go:   os.Getwd()
来源：http://dali.jyoumei.cn/Article/details/gt2osmiohhr.html

Ruby: Dir.pwd
来源：http://dali.tian-w.cn/Article/details/gt2xyntulqw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gogol.net.cn/Article/details/gt2azpxitso.html

[M05] 设置退出码
来源：http://dali.xylfe.cn/Article/details/gt2gqmyfhfd.html

Py:   sys.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2megszmfk.html

PHP:  exit(1);
来源：http://dali.guowangkeji.top/Article/details/gt2wktpyfaw.html

JS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gt2jandbiga.html

TS:   process.exit(1)
来源：http://dali.316326.xyz/Article/details/gt2ilyzyqnf.html

Java: System.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2qwaykbrc.html

Go:   os.Exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2hngurjhs.html

Ruby: exit 1
来源：http://dali.tianlin.xyz/Article/details/gt2jvqfbicj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gt2trkwyyec.html

[M06] 向标准错误输出
来源：http://dali.316326.xyz/Article/details/gt2nbqzjbrr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sweixlkl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fgsbjcma.html

JS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gt2ccycfubq.html

TS:   console.error("err")
来源：http://dali.gotoacloud.top/Article/details/gt2oshzabgm.html

Java: System.err.println("err")
来源：http://dali.xuanzx.com/Article/details/gt2ixplhtdq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wuetntig.html

Ruby: warn "err"
来源：http://dali.sxryk.cn/Article/details/gt2oxgqnvdy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fengsongda.top/Article/details/gt2lkrntxws.html

[M07] 判断是否为主入口
来源：http://dali.tian-w.cn/Article/details/gt2khrssrji.html

Py:   if __name__ == "__main__":
来源：http://dali.tianlin.xyz/Article/details/gt2kzegerqt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2vxflupxz.html

JS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gt2ohjeevni.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gt2bainnngw.html

Java: public static void main(String[] args)
来源：http://dali.9152youxi.cn/Article/details/gt2jaujoluo.html

Go:   func main()
来源：http://dali.yanxiufei.cn/Article/details/gt2nohimone.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zdqjudy.top/Article/details/gt2xzpdlrrs.html

C#:   static void Main(string[] args)
来源：http://dali.tianlin.xyz/Article/details/gt2xqriizfc.html

[M08] 获取系统与运行时信息
来源：http://dali.jinqigufen.top/Article/details/gt2hqpvycej.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnqzz.top/Article/details/gt2lafksriw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daria6918.cn/Article/details/gt2kvaubgav.html

JS:   process.platform;  process.version
来源：http://dali.yj20258.top/Article/details/gt2pmhajpze.html

TS:   process.platform;  process.version
来源：http://dali.yuxming.cn/Article/details/gt2sbosnbqs.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yangfankeji.com/Article/details/gt2aszswoxz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fzhhl.top/Article/details/gt2upskaajc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.feifeiyinyue.top/Article/details/gt2fzenyppk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxinkj.top/Article/details/gt2jzwkqcwh.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2emlshrkk.html

N. 数据结构与算法
来源：http://dali.zhiwuduotai.top/Article/details/gt2alrjjueu.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2zpmywkqk.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258.top/Article/details/gt2hhvaoerw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2jhjwjrdf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yongpay.top/Article/details/gt2imezandc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gt2bagsfvar.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gt2kmoonluw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gt2sbdgeiqj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2xwwqsuzz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cuqjdkxj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2cbetjqpd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cashguo.top/Article/details/gt2dyufuita.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gt2iszwpmic.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gt2jomdqabh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gt2xuclyfur.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gt2plxmlzef.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kfqwwjhi.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2lnryhyxz.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gt2rhtcvioz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jianghu66.top/Article/details/gt2ilnsnzvd.html

[N03] 快速排序（分治示例）
来源：http://dali.yj20258.top/Article/details/gt2alwegvdc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinqigfzy.top/Article/details/gt2ldmkqnns.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj202588.top/Article/details/gt2ioizbmwh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gt2gfzbemgq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2yeckzfek.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangshuangyany.cn/Article/details/gt2gzxaahno.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hongshengwenyu.top/Article/details/gt2stianjid.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ymmazqka.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dashuyun.cn/Article/details/gt2vqljkmne.html

[N04] 斐波那契数列
来源：http://dali.nanxinkj.top/Article/details/gt2wcvejjps.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gt2vdddmnhj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.redwolf501.top/Article/details/gt2eyworvju.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gt2rkzhdqyk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gt2ipieqqjk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jyeggcnq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.snrcjt.cn/Article/details/gt2vksrydqg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258888.top/Article/details/gt2ffkdpqya.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nlaxvasq.html

[N05] 最大公约数
来源：http://dali.fengsongda.top/Article/details/gt2skwuzzse.html

Py:   math.gcd(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pfzbolos.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cucudq.cn/Article/details/gt2uxcfdovu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cashguo.top/Article/details/gt2gzamdhlp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gt2humoanjv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenzaomai.com/Article/details/gt2kenvmwhv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhongyouzk.top/Article/details/gt2glwhgira.html

Ruby: a.gcd(b)
来源：http://dali.jiagoushi.top/Article/details/gt2gdhiejqg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigufen.top/Article/details/gt2vwdpizvm.html

[N06] 判断回文字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xalqrgee.html

Py:   s == s[::-1]
来源：http://dali.316326.xyz/Article/details/gt2sbiuonip.html

PHP:  $s === strrev($s);
来源：http://dali.yvedp.cn/Article/details/gt2hvbepthd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gt2ubrzrcfh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gt2cxdvomic.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tianlin.xyz/Article/details/gt2dabjznnj.html

Go:   // 双指针从两端比较
来源：http://dali.jlsjyb.cn/Article/details/gt2stctwggi.html

Ruby: s == s.reverse
来源：http://dali.ppjwa.cn/Article/details/gt2fgigrqgc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gt2qzsausvy.html

[N07] 两数之和（返回下标）
来源：http://dali.fengsongda.top/Article/details/gt2gcktkzod.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xziqi.cn/Article/details/gt2oqhjuank.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cashguo.top/Article/details/gt2oaiinzjz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sweek.top/Article/details/gt2qyqwugrj.html

TS:   // 手写 Map<string, number>
来源：http://dali.guowangkeji.top/Article/details/gt2jmyrweuc.html

Java: // 手写 HashMap
来源：http://dali.dashuyun.cn/Article/details/gt2utigssws.html

Go:   // 手写 map[int]int
来源：http://dali.yangfankeji.com/Article/details/gt2lehijpab.html

Ruby: // 手写 Hash
来源：http://dali.guannengcc.top/Article/details/gt2uukbzskk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhixingplan.top/Article/details/gt2bspdbosw.html

[N08] 生成全排列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2czfgssvx.html

Py:   itertools.permutations(arr)
来源：http://dali.gzhubu.top/Article/details/gt2yahdolen.html

PHP:  // 手写递归交换
来源：http://dali.zhixingplan.top/Article/details/gt2vcrsurpv.html

JS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2vfwbnxqv.html

TS:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gt2uiavqzcr.html

Java: // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2dbpdxdug.html

Go:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2jpqtwvkn.html

Ruby: arr.permutation.to_a
来源：http://dali.meibo888.top/Article/details/gt2ylrysjsn.html

C#:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gt2quihrfua.html

[N09] 栈与队列
来源：http://dali.tian-w.cn/Article/details/gt2vjpcqnqx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.meibo888.top/Article/details/gt2aymitkit.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gt2cnijwtqe.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pfxuntqj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxinkj.top/Article/details/gt2nuodryzd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dianchejie.cn/Article/details/gt2ihryktpa.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shzxlz.cn/Article/details/gt2iupskich.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gt2cmsftzeq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnxiangtu.top/Article/details/gt2sqbhgdrq.html

[N10] 链表节点定义
来源：http://dali.jinqigfzy.top/Article/details/gt2maukkkrt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gotoacloud.top/Article/details/gt2grhbzjzb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhoulong.xyz/Article/details/gt2davbxiag.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuxming.cn/Article/details/gt2qdoeowsp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.fengsongda.top/Article/details/gt2tbvzybsy.html

Java: class Node { int v; Node next; }
来源：http://dali.c1oappe.top/Article/details/gt2zirngeon.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenlongwang.top/Article/details/gt2cnnjojtx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.316326.xyz/Article/details/gt2ifbrqzoz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ehwqpu.com/Article/details/gt2okvhnaxy.html

[N11] 二叉树中序遍历
来源：http://dali.gzhubu.top/Article/details/gt2szckzrtz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.quarkkingdee.top/Article/details/gt2cqjtpotf.html

PHP:  // 手写递归函数
来源：http://dali.bjfxy.top/Article/details/gt2shpoehry.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gt2sjlkswvj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gt2jzpfqljn.html

Java: // 手写递归
来源：http://dali.c1oappe.top/Article/details/gt2sghfdtka.html

Go:   // 手写递归
来源：http://dali.andypj.xyz/Article/details/gt2jqgohufc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jnafxlgb.html

C#:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gt2mprslrnc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yonumen.top/Article/details/gt2hwpqnouv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gaohongyu789.top/Article/details/gt2avrcdokz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jlsjyb.cn/Article/details/gt2ahouwxqt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gt2tvadiqqn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gt2bvfldcxr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gt2erkiqogy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zycfv.cn/Article/details/gt2vypmvdij.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2obzbjymz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenzaomai.com/Article/details/gt2ucnpunxp.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2ajnlliuy.html

O. 并发与异步
来源：http://dali.jiagoushi.top/Article/details/gt2olqbxwdl.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2uhwxzvdh.html

[O01] 启动一个线程
来源：http://dali.c1oappe.top/Article/details/gt2zajmxbls.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yvedp.cn/Article/details/gt2mzrbmhta.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guannengcc.top/Article/details/gt2vsfgwaen.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hfpthk.cn/Article/details/gt2yhvezfcg.html

TS:   // 同 JS
来源：http://dali.sysykeji.top/Article/details/gt2plctpkgb.html

Java: new Thread(() -> f()).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zqxldadv.html

Go:   go f()
来源：http://dali.zhiwuduotai.top/Article/details/gt2bjjvtqrz.html

Ruby: Thread.new { f }
来源：http://dali.yuxming.cn/Article/details/gt2pizyvvjz.html

C#:   Task.Run(() => F());
来源：http://dali.0kj1m.cn/Article/details/gt2eqleqolm.html

[O02] 使用线程池
来源：http://dali.xuanzx.com/Article/details/gt2lxuzyseu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guowangkeji.top/Article/details/gt2tasykcwv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.mhx1999.top/Article/details/gt2iggliymg.html

JS:   // worker_threads 线程池
来源：http://dali.hysaishi.cn/Article/details/gt2rnxviwoq.html

TS:   // worker_threads 线程池
来源：http://dali.yanxiufei.cn/Article/details/gt2ouduncqv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhixingplan.top/Article/details/gt2dvvbuago.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aibaodan.cn/Article/details/gt2xnltdxol.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shuidangran.top/Article/details/gt2zqdrpgsu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2irkqkxqu.html

[O03] 加锁保护共享数据
来源：http://dali.yj202588.top/Article/details/gt2cehvlcut.html

Py:   with lock: shared += 1
来源：http://dali.daxiang520.top/Article/details/gt2iyveowug.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guannengcc.top/Article/details/gt2xaeeksbu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigufen.top/Article/details/gt2xyapjyjp.html

TS:   // 同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gt2ztugwqwt.html

Java: synchronized (this) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pncgzemn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.aibaodan.cn/Article/details/gt2tmjyxatt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yvedp.cn/Article/details/gt2zrtkmxyh.html

C#:   lock (gate) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hxiulezs.html

[O04] 定义异步函数并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qjglgwkv.html

Py:   async def f():⏎    await g()
来源：http://dali.jqgufenzy.top/Article/details/gt2egqygipc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.guannengcc.top/Article/details/gt2gufhhxla.html

JS:   async function f() { await g(); }
来源：http://dali.smart0.xyz/Article/details/gt2ixhvfnxg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.iojbl.cn/Article/details/gt2lvtgpbsm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wlbcjlki.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ivvv.top/Article/details/gt2ihvaqgbu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hongshengwenyu.top/Article/details/gt2mffiknls.html

C#:   async Task F() { await G(); }
来源：http://dali.jyoumei.cn/Article/details/gt2xlxtftpm.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigfzy.top/Article/details/gt2gpmpfemm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.mhx1999.top/Article/details/gt2ttujjrjl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenjidiqi.icu/Article/details/gt2nlaqlwem.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgfhrgu.html

TS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gt2lvodqsvs.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxinkj.top/Article/details/gt2czkvzync.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.havefunace.top/Article/details/gt2igzuoulb.html

Ruby: threads.map(&:join)
来源：http://dali.zhengqikj.top/Article/details/gt2jhzaxxxf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guowangkeji.top/Article/details/gt2vikdmtzu.html

[O06] 使用进程池
来源：http://dali.ydzc1.top/Article/details/gt2xuobiyxw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ojyrjafj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2xopcwntg.html

JS:   // child_process / cluster 模块
来源：http://dali.hfpthk.cn/Article/details/gt2vlsnsije.html

TS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gt2brjqpcpb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fengsongda.top/Article/details/gt2wohglmlc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.wangdashe.top/Article/details/gt2ktecrngy.html

Ruby: // fork 块
来源：http://dali.yangfankeji.com/Article/details/gt2amjzmqcb.html

C#:   Parallel.For
来源：http://dali.ppjwa.cn/Article/details/gt2gppdajii.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2uinsglcy.html

P. 常用工具函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2ttiqaomf.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2tjtjxnum.html

[P01] 生成 UUID
来源：http://dali.cqqwz.cn/Article/details/gt2jpvbudva.html

Py:   str(uuid.uuid4())
来源：http://dali.snrcjt.cn/Article/details/gt2tnhyosse.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gzhubu.top/Article/details/gt2cntqysmd.html

JS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gt2vggqhjmo.html

TS:   crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gt2xbekhagr.html

Java: UUID.randomUUID().toString()
来源：http://dali.gaohongyu789.top/Article/details/gt2vncupfzs.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gt2bwaquuwb.html

Ruby: SecureRandom.uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pcifcrmc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cheryme.top/Article/details/gt2snijkjya.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258888.top/Article/details/gt2bifishgk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jiagoushi.top/Article/details/gt2jalvgovu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jianghu66.top/Article/details/gt2qxtojvxi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.quarkkingdee.top/Article/details/gt2feddijku.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhoulong.xyz/Article/details/gt2lnhuawhy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cdnleiting.top/Article/details/gt2isqhqgke.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangdashe.top/Article/details/gt2xkliswoe.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.pycfn.com/Article/details/gt2wytyuxvy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258888.top/Article/details/gt2rzgqqhgl.html

[P03] 生成短随机字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2onirupjy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuanzx.com/Article/details/gt2duzyvmxp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.haohaochexian.top/Article/details/gt2iullffsd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2lhoucdfu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ejzlstii.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dianchejie.cn/Article/details/gt2rptnsnrk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gogol.net.cn/Article/details/gt2dotmvffa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.316326.xyz/Article/details/gt2naaewtco.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hywenlv.cn/Article/details/gt2lyfcjzem.html

[P04] 求长度
来源：http://dali.zhoulong.xyz/Article/details/gt2zdxcdidz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenjidiqi.icu/Article/details/gt2ddbrcrvx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gt2lnvmnjxu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gt2lfusbgfo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gt2hbvdegcc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zdqjudy.top/Article/details/gt2hdollcmi.html

Go:   len(arr);  len(m)
来源：http://dali.316326.xyz/Article/details/gt2upsooyjp.html

Ruby: x.length;  x.size
来源：http://dali.yvedp.cn/Article/details/gt2edwofmls.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhixingplan.top/Article/details/gt2bautbqtc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.kuanghao11.cn/Article/details/gt2floilydx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yongpay.top/Article/details/gt2wkutzafd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dashuyun.cn/Article/details/gt2jwuknuwk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fengsongda.top/Article/details/gt2prtmfkzb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aibaodan.cn/Article/details/gt2kmoepzok.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hywenlv.cn/Article/details/gt2efoxqqev.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vetjrqxq.html

Ruby: a == b
来源：http://dali.haohaochexian.top/Article/details/gt2meewhfaj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.svipenyu.cn/Article/details/gt2erumojtd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jiagoushi.top/Article/details/gt2bvzrhire.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yuanzhike.top/Article/details/gt2bogdasgk.html

PHP:  if (empty($x)) {}
来源：http://dali.zycfv.cn/Article/details/gt2azxzulid.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ndaiqmim.html

TS:   if (x == null) {}
来源：http://dali.zhixingplan.top/Article/details/gt2hznxovvw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gt2jzxllufr.html

Go:   if x == nil {}
来源：http://dali.yvedp.cn/Article/details/gt2vpscqjgf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2prlhukly.html

C#:   if (x is null) {}
来源：http://dali.sxryk.cn/Article/details/gt2dvceeqaj.html

[P07] 防抖与节流
来源：http://dali.cdnleiting.top/Article/details/gt2uulbcfod.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hongshengwenyu.top/Article/details/gt2qmqqftbo.html

PHP:  // 手写时间戳比较
来源：http://dali.yongpay.top/Article/details/gt2laajanni.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gt2ukbnucya.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gt2lridscxk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tianlin.xyz/Article/details/gt2xhzphhfn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.kuanghao11.cn/Article/details/gt2lgkfijcw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jiagoushi.top/Article/details/gt2eflwflex.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gaohongyu789.top/Article/details/gt2luhtfiej.html

[P08] 处理浮点精度问题
来源：http://dali.daxiang520.top/Article/details/gt2isgeqjev.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangdashe.top/Article/details/gt2idnbpijg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.andypj.xyz/Article/details/gt2gwgobqwy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hysaishi.cn/Article/details/gt2pzlyujpe.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhengqikj.top/Article/details/gt2kuxmygtd.html


<!-- 参考信息 -->