代发 wailian999

Ruby: ARGV
来源：http://dali.fengsongda.top/Article/details/gtrjgdmfsp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guowangkeji.top/Article/details/gtnzrtxgye.html

[M02] 读取环境变量
来源：http://dali.cucudq.cn/Article/details/gtmnisywsq.html

Py:   os.environ.get("HOME")
来源：http://dali.316326.xyz/Article/details/gtwkydxdlc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gtmpnhshkd.html

JS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gtnfckcnwo.html

TS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtnzuwowca.html

Java: System.getenv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtxhompdmg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sweek.top/Article/details/gtplktfshk.html

Ruby: ENV["HOME"]
来源：http://dali.hnxiangtu.top/Article/details/gthpchgler.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guannengcc.top/Article/details/gtkfgtymnl.html

[M03] 执行外部命令
来源：http://dali.dashuyun.cn/Article/details/gtuixwomac.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.9152youxi.cn/Article/details/gtppedocki.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.c1oappe.top/Article/details/gthrqhelei.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ehwqpu.com/Article/details/gtrzforplh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gtmctnftct.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fengsongda.top/Article/details/gtezsamlqy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zdqjudy.top/Article/details/gtmydletdu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zdqjudy.top/Article/details/gtbuvkombr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgfzy.top/Article/details/gtvesbbpgn.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gtdmmllzwv.html

Py:   os.getcwd()
来源：http://dali.smart0.xyz/Article/details/gtadaymond.html

PHP:  getcwd();
来源：http://dali.0kj1m.cn/Article/details/gtgbjbxopr.html

JS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gteehzvpjq.html

TS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gtojayaejk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangshuangyany.cn/Article/details/gtofhoayxn.html

Go:   os.Getwd()
来源：http://dali.xylfe.cn/Article/details/gttwpuakaa.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gtygwntmoc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgfzy.top/Article/details/gtrltyjtbc.html

[M05] 设置退出码
来源：http://dali.jianghu66.top/Article/details/gtvzouaxzg.html

Py:   sys.exit(1)
来源：http://dali.ybcxt.top/Article/details/gterljcxut.html

PHP:  exit(1);
来源：http://dali.haohaochexian.top/Article/details/gtuvrlmwhr.html

JS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtrydowfqf.html

TS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtiibkibqh.html

Java: System.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtwasoekot.html

Go:   os.Exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtqlksokco.html

Ruby: exit 1
来源：http://dali.ivvv.top/Article/details/gtnawodwld.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.iojbl.cn/Article/details/gtuwzhstwf.html

[M06] 向标准错误输出
来源：http://dali.sysykeji.top/Article/details/gtpydzntjz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tianlin.xyz/Article/details/gtpmykwqug.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.bjfxy.top/Article/details/gtraxyrfdc.html

JS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gtmpfqddha.html

TS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gtrtyxjjbd.html

Java: System.err.println("err")
来源：http://dali.andypj.xyz/Article/details/gtutcltcba.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.svipenyu.cn/Article/details/gtjkcfrvwh.html

Ruby: warn "err"
来源：http://dali.nwbrower.top/Article/details/gttunlkvuq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhixingplan.top/Article/details/gtywrlsswh.html

[M07] 判断是否为主入口
来源：http://dali.zycfv.cn/Article/details/gtgdkzjyxg.html

Py:   if __name__ == "__main__":
来源：http://dali.c1oappe.top/Article/details/gtfjeyrtbz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.c1oappe.top/Article/details/gtejjqzjru.html

JS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtxogiqkuq.html

TS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gtqewyxrgc.html

Java: public static void main(String[] args)
来源：http://dali.yj202588.top/Article/details/gtlmcpaixc.html

Go:   func main()
来源：http://dali.cdnleiting.top/Article/details/gtxjojuqxn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.mhx1999.top/Article/details/gtvzpngawi.html

C#:   static void Main(string[] args)
来源：http://dali.zhixingplan.top/Article/details/gtbhpeymrn.html

[M08] 获取系统与运行时信息
来源：http://dali.xinyue.icu/Article/details/gtsxtbinmr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangtech.top/Article/details/gtztthaxnk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shuidangran.top/Article/details/gtjwgooqqm.html

JS:   process.platform;  process.version
来源：http://dali.haohaochexian.top/Article/details/gtwrxmdswy.html

TS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtnlopuhxq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fengsongda.top/Article/details/gtkvtnhoof.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xinyue.icu/Article/details/gtchvvdbmo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yonumen.top/Article/details/gtrngvznyt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sweek.top/Article/details/gtiholjzre.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtsfxclrsb.html

N. 数据结构与算法
来源：http://dali.yonumen.top/Article/details/gtoktqujlz.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtbchitxlu.html

[N01] 二分查找（有序数组）
来源：http://dali.haohaochexian.top/Article/details/gthtfugyoj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudiusldj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cashguo.top/Article/details/gttzclcpgn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gtngjifswe.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gtgmmbljqi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtlqshthij.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtyjjufvvp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.9152youxi.cn/Article/details/gtwlgoxtws.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzqgnpzg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhixingplan.top/Article/details/gtipmhnmqk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrwwhgch.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtohyclxfg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtbbtpjhxl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gtgtbonreu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.mhx1999.top/Article/details/gttuaivppy.html

Go:   slices.Sort(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtzyqcoyzo.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gthtcumxov.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangdashe.top/Article/details/gtrjltlund.html

[N03] 快速排序（分治示例）
来源：http://dali.316326.xyz/Article/details/gtngiqjruy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sweek.top/Article/details/gtybrhzcyv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shzxlz.cn/Article/details/gtqktpjrhd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gtmosdssaf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.quarkkingdee.top/Article/details/gtymdrbbxf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nwbrower.top/Article/details/gtlfvqqzir.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuanzhike.top/Article/details/gttohngrfi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yueranfly.top/Article/details/gtdkiuznli.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sxryk.cn/Article/details/gthzwwcmdw.html

[N04] 斐波那契数列
来源：http://dali.tianlin.xyz/Article/details/gtrmujcdqv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gtzwujtrur.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gtefmsmwmw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtbhlgswda.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtflipygxx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pycfn.com/Article/details/gtmvrvufhr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj202588.top/Article/details/gtbfitlogl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cheryme.top/Article/details/gtovrtaiax.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gttnietill.html

[N05] 最大公约数
来源：http://dali.yueranfly.top/Article/details/gtahpjpnjo.html

Py:   math.gcd(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtxezykmxs.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zycfv.cn/Article/details/gtwbcqsnfr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gtlmmjmlaf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gtxszyceyr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkeejualt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yangfankeji.com/Article/details/gtyfujaxwx.html

Ruby: a.gcd(b)
来源：http://dali.cqqwz.cn/Article/details/gtphykujxq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.havefunace.top/Article/details/gtulrslvky.html

[N06] 判断回文字符串
来源：http://dali.guannengcc.top/Article/details/gtdacbodtb.html

Py:   s == s[::-1]
来源：http://dali.hnqzz.top/Article/details/gtcaxicsuz.html

PHP:  $s === strrev($s);
来源：http://dali.c1oappe.top/Article/details/gtkihdvdog.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtilkmftsg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gtbbkhjcaz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.daxiang520.top/Article/details/gtnzingehy.html

Go:   // 双指针从两端比较
来源：http://dali.yanxiufei.cn/Article/details/gtvemzrggx.html

Ruby: s == s.reverse
来源：http://dali.ppjwa.cn/Article/details/gtltixkmio.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gtigphihgx.html

[N07] 两数之和（返回下标）
来源：http://dali.yuxming.cn/Article/details/gtefahddix.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yonumen.top/Article/details/gtqrxsfcaj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xziqi.cn/Article/details/gtwjiujzlh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteyamtaxy.html

TS:   // 手写 Map<string, number>
来源：http://dali.svipenyu.cn/Article/details/gtypycosvu.html

Java: // 手写 HashMap
来源：http://dali.yuanzhike.top/Article/details/gtelzrgnie.html

Go:   // 手写 map[int]int
来源：http://dali.birdmap.top/Article/details/gtxrywmyys.html

Ruby: // 手写 Hash
来源：http://dali.zycfv.cn/Article/details/gtwbuuvshn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gzhubu.top/Article/details/gtwatmgnpf.html

[N08] 生成全排列
来源：http://dali.hammf.cn/Article/details/gtxqbdrrhw.html

Py:   itertools.permutations(arr)
来源：http://dali.xinyue.icu/Article/details/gtikuolyua.html

PHP:  // 手写递归交换
来源：http://dali.ppjwa.cn/Article/details/gthnicmbgg.html

JS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtwmutqbuw.html

TS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtbpjwnjme.html

Java: // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtafkrgqdo.html

Go:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtwzcqkqrj.html

Ruby: arr.permutation.to_a
来源：http://dali.svipenyu.cn/Article/details/gtwxghoybs.html

C#:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtjfruzlii.html

[N09] 栈与队列
来源：http://dali.jqgfzy.top/Article/details/gtunlrluoe.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.0kj1m.cn/Article/details/gthpecsttd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtbycbytni.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gttiuncjvo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yvedp.cn/Article/details/gttowqibwn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.316326.xyz/Article/details/gtijvxpyqo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhengqikj.top/Article/details/gtxgnymzxw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtpixdafuw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yueranfly.top/Article/details/gtucjaaefu.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangtech.top/Article/details/gthsyvcijj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nanxinkj.top/Article/details/gtgzodvzmq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjovqhijx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nanxuanxn.top/Article/details/gtsrkmhtui.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.smart0.xyz/Article/details/gtvmtdanos.html

Java: class Node { int v; Node next; }
来源：http://dali.yj202588.top/Article/details/gtkaxbifcc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.bjfxy.top/Article/details/gthagdlzii.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwmxkbst.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenjidiqi.icu/Article/details/gtumbbmcip.html

[N11] 二叉树中序遍历
来源：http://dali.jiagoushi.top/Article/details/gtnnoyqoqq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhengqikj.top/Article/details/gtgvvwrrho.html

PHP:  // 手写递归函数
来源：http://dali.daxiang520.top/Article/details/gthpkqukhp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.mhx1999.top/Article/details/gtunybidyl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gtzjualyvr.html

Java: // 手写递归
来源：http://dali.yongpay.top/Article/details/gterijanbc.html

Go:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gtsugikaze.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.svipenyu.cn/Article/details/gtakddvkxj.html

C#:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gteazbuuls.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.iojbl.cn/Article/details/gtkldzcpnc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtisfzlsww.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gtiprmmptc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gtxgybxlox.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gtvomljnur.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gtvymikbkd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.fengsongda.top/Article/details/gtgvrtgtev.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pycfn.com/Article/details/gtlixezplr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gtxyabqlse.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtrxqwpebq.html

O. 并发与异步
来源：http://dali.tian-w.cn/Article/details/gtgtvqdgvn.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtuuwxtatt.html

[O01] 启动一个线程
来源：http://dali.wangshuangyany.cn/Article/details/gtcxiefius.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sxryk.cn/Article/details/gtvlsloapm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aibaodan.cn/Article/details/gtrbijvyed.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.quarkkingdee.top/Article/details/gtavkaimdu.html

TS:   // 同 JS
来源：http://dali.nanxinkj.top/Article/details/gtbeklimsv.html

Java: new Thread(() -> f()).start()
来源：http://dali.zdqjudy.top/Article/details/gtslgdhgcc.html

Go:   go f()
来源：http://dali.sufxvd.cn/Article/details/gteciepzgp.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gtljiirjgn.html

C#:   Task.Run(() => F());
来源：http://dali.iojbl.cn/Article/details/gtdflogauy.html

[O02] 使用线程池
来源：http://dali.nanxuanxn.top/Article/details/gtnvwawddj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.iojbl.cn/Article/details/gtwvwigxjb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hywenlv.cn/Article/details/gtxnarxesr.html

JS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gtpmmvdbse.html

TS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gtibrmwppu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.haohaochexian.top/Article/details/gtozoenacu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shzxlz.cn/Article/details/gtrmtvqosq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.guowangkeji.top/Article/details/gtqxwzyoje.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgraficza.html

[O03] 加锁保护共享数据
来源：http://dali.wangshuangyany.cn/Article/details/gtjumkuxzz.html

Py:   with lock: shared += 1
来源：http://dali.cdnleiting.top/Article/details/gtoavfqhre.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shzxlz.cn/Article/details/gtdxcxztmb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zdqjudy.top/Article/details/gtkrpeltzz.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gtezxyjcvv.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgufenzy.top/Article/details/gtqmzybbzy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gaohongyu789.top/Article/details/gtgfixfkyf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ppjwa.cn/Article/details/gtivqwapnr.html

C#:   lock (gate) { shared++; }
来源：http://dali.havefunace.top/Article/details/gttgayiyet.html

[O04] 定义异步函数并等待
来源：http://dali.cucudq.cn/Article/details/gtvhzmcgrj.html

Py:   async def f():⏎    await g()
来源：http://dali.quarkkingdee.top/Article/details/gtrwfdteyh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenzaomai.com/Article/details/gttxiehxss.html

JS:   async function f() { await g(); }
来源：http://dali.smart0.xyz/Article/details/gtzbotyzjj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gtsboxsbrw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangdashe.top/Article/details/gtdlylsblb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gogol.net.cn/Article/details/gtgdyhximp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ivvv.top/Article/details/gtifjcujjy.html

C#:   async Task F() { await G(); }
来源：http://dali.cucudq.cn/Article/details/gtfwplanyz.html

[O05] 并发执行并等待全部完成
来源：http://dali.nanxuanxn.top/Article/details/gtetajezsj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.kuanghao11.cn/Article/details/gtncvtctln.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiotquewk.html

JS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gtzwnmxdxx.html

TS:   await Promise.all(tasks)
来源：http://dali.xinyue.icu/Article/details/gtpxabxqnp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.dianchejie.cn/Article/details/gtxmewlaji.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cheryme.top/Article/details/gtgxvaknxj.html

Ruby: threads.map(&:join)
来源：http://dali.tanke756.top/Article/details/gtwvjnbghe.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnqzz.top/Article/details/gtlfrrqzci.html

[O06] 使用进程池
来源：http://dali.ivvv.top/Article/details/gtjyibapou.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ppjwa.cn/Article/details/gtulqubjrf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnqzz.top/Article/details/gtjqdyrmyi.html

JS:   // child_process / cluster 模块
来源：http://dali.chenzaomai.com/Article/details/gtkeopfhjh.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gthtngjebe.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezqtakmj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gtatnmgqjr.html

Ruby: // fork 块
来源：http://dali.c1oappe.top/Article/details/gtukbvuhsh.html

C#:   Parallel.For
来源：http://dali.yuanzhike.top/Article/details/gtbpumzslj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtjxgnafuy.html

P. 常用工具函数
来源：http://dali.hnqzz.top/Article/details/gtuvvcfzgr.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtrgzwwzvz.html

[P01] 生成 UUID
来源：http://dali.zhengqikj.top/Article/details/gtqpybvalw.html

Py:   str(uuid.uuid4())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqucrfuji.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.mhx1999.top/Article/details/gtcrfdceey.html

JS:   crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gtyaogytnr.html

TS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gtomvdioze.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnqzz.top/Article/details/gtnsttrjgv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daxiang520.top/Article/details/gtmcoxdmvx.html

Ruby: SecureRandom.uuid
来源：http://dali.dashuyun.cn/Article/details/gtlxrxphyp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yvedp.cn/Article/details/gtkbbnxntd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinghuilouyu.cn/Article/details/gttrquodzx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.bjfxy.top/Article/details/gtrdqhhsbl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.mhx1999.top/Article/details/gtizmbjrwv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hywenlv.cn/Article/details/gtdrqryjor.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.daria6918.cn/Article/details/gtcgcgjfuw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygtmddfg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuanzhike.top/Article/details/gtcbebauzc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fzhhl.top/Article/details/gtecnykkic.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.guowangkeji.top/Article/details/gtgbujqzez.html

[P03] 生成短随机字符串
来源：http://dali.jinqigufen.top/Article/details/gtgistywqn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.9152youxi.cn/Article/details/gtpaxalgqi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuxming.cn/Article/details/gtlmwxkfjc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yongpay.top/Article/details/gtdarzwyha.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gtdibjdcss.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yueranfly.top/Article/details/gtjqxqbupt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.0kj1m.cn/Article/details/gtjnwiemkr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.aibaodan.cn/Article/details/gtfvqbkydr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfaqwaju.html

[P04] 求长度
来源：http://dali.hnxiangtu.top/Article/details/gtzbdzptrq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyechaacw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtqbbdssuk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuanzx.com/Article/details/gtwwctcfkm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gtxpfbbsaz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nwbrower.top/Article/details/gtqmzvenaz.html

Go:   len(arr);  len(m)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkkscfzq.html

Ruby: x.length;  x.size
来源：http://dali.cqqwz.cn/Article/details/gtynktqapt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhixingplan.top/Article/details/gtmzkrrdgc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.feifeiyinyue.top/Article/details/gtymyehfcq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daxiang520.top/Article/details/gttfrhyygf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj202588.top/Article/details/gtfumjfqsp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fengsongda.top/Article/details/gttmgrlxck.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxinkj.top/Article/details/gtadnqfzmz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aibaodan.cn/Article/details/gtazyyqzqw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.c1oappe.top/Article/details/gtkbzkgjmj.html

Ruby: a == b
来源：http://dali.zhongyouzk.top/Article/details/gticmbmiaw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hammf.cn/Article/details/gtwbpeiiww.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinghuilouyu.cn/Article/details/gtbupvqzfq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yuxming.cn/Article/details/gtxphwvmen.html

PHP:  if (empty($x)) {}
来源：http://dali.wangdashe.top/Article/details/gtfdqxauzq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nwbrower.top/Article/details/gtyeiuiexu.html

TS:   if (x == null) {}
来源：http://dali.nanxuanxn.top/Article/details/gtoplmkeoj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtlzcaaxcb.html

Go:   if x == nil {}
来源：http://dali.hnqzz.top/Article/details/gtdtylqxjz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwyuvkwc.html

C#:   if (x is null) {}
来源：http://dali.cucudq.cn/Article/details/gtkqgfrkta.html

[P07] 防抖与节流
来源：http://dali.hysaishi.cn/Article/details/gtnoxfngxc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gzhubu.top/Article/details/gtgrgipjbi.html

PHP:  // 手写时间戳比较
来源：http://dali.shangyingyoupin.top/Article/details/gtffzaxmbi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tianlin.xyz/Article/details/gtelomfwgx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqxnxhxd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tanke756.top/Article/details/gticjzpcui.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cashguo.top/Article/details/gtpkygbsjo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitenynpt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sxryk.cn/Article/details/gtqenttkon.html

[P08] 处理浮点精度问题
来源：http://dali.wangshuangyany.cn/Article/details/gthbrawqmf.html


<!-- 参考信息 -->