代发 wailian999

JS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gtntfozbob.html

TS:   process.argv.slice(2)
来源：http://dali.zhongyouzk.top/Article/details/gtltbvxgxz.html

Java: args 数组（main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gtjlctzcrc.html

Go:   os.Args[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtkfwergbp.html

Ruby: ARGV
来源：http://dali.bjfxy.top/Article/details/gtmwzxbxnc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gtisnmtski.html

[M02] 读取环境变量
来源：http://dali.ydzc1.top/Article/details/gticlmmssk.html

Py:   os.environ.get("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtklklru.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yonumen.top/Article/details/gtbbqpubgg.html

JS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gtyzpgigpz.html

TS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydtjkozp.html

Java: System.getenv("HOME")
来源：http://dali.cucudq.cn/Article/details/gtakonjmum.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtnclawzhy.html

Ruby: ENV["HOME"]
来源：http://dali.zhoulong.xyz/Article/details/gtkzvmuikx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtkfsadnqa.html

[M03] 执行外部命令
来源：http://dali.jqgufenzy.top/Article/details/gtggebjdyp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daria6918.cn/Article/details/gtpdcgsevz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pycfn.com/Article/details/gtekzsmyzc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gtqkkezhjw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gtbqubxisz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yongpay.top/Article/details/gtaotjobdc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj202588.top/Article/details/gttpxnjqlo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.c1oappe.top/Article/details/gtvhrgrxcv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yvedp.cn/Article/details/gtebirmnag.html

[M04] 获取当前工作目录
来源：http://dali.sysykeji.top/Article/details/gtlluyhday.html

Py:   os.getcwd()
来源：http://dali.kuanghao11.cn/Article/details/gttulspdeg.html

PHP:  getcwd();
来源：http://dali.jiagoushi.top/Article/details/gtuurpjlmb.html

JS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpfmllec.html

TS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gtgtqyahwp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jlsjyb.cn/Article/details/gtvvsrigar.html

Go:   os.Getwd()
来源：http://dali.aizwys.cn/Article/details/gthawrlplp.html

Ruby: Dir.pwd
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibsaocbm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.andypj.xyz/Article/details/gtxrgmwygx.html

[M05] 设置退出码
来源：http://dali.sysykeji.top/Article/details/gtjilugram.html

Py:   sys.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtoewoxfuw.html

PHP:  exit(1);
来源：http://dali.shzxlz.cn/Article/details/gthzhcxlmu.html

JS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtsbxrliud.html

TS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtzjlujtkl.html

Java: System.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtcyybnaej.html

Go:   os.Exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtkkmntczl.html

Ruby: exit 1
来源：http://dali.snrcjt.cn/Article/details/gtgptepani.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shanyushiyangtech.top/Article/details/gtlsasbvjw.html

[M06] 向标准错误输出
来源：http://dali.cheryme.top/Article/details/gtwutkvruz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sysykeji.top/Article/details/gtdgwmaziv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ehwqpu.com/Article/details/gtnenqsrtm.html

JS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gtzxvdwxnm.html

TS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtzjwynugj.html

Java: System.err.println("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtynftzsfx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzldihdso.html

Ruby: warn "err"
来源：http://dali.yvedp.cn/Article/details/gtmetkndvr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258888.top/Article/details/gtxkuibiiz.html

[M07] 判断是否为主入口
来源：http://dali.meibo888.top/Article/details/gtjycykszn.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigfzy.top/Article/details/gtuchiakoc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pengpengdd.cyou/Article/details/gtiputbzup.html

JS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gttjjzkekz.html

TS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gtfssmlpch.html

Java: public static void main(String[] args)
来源：http://dali.zycfv.cn/Article/details/gtniyqemvh.html

Go:   func main()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvbpqpwc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhixingplan.top/Article/details/gtbchkxdbc.html

C#:   static void Main(string[] args)
来源：http://dali.yuanzhike.top/Article/details/gtonpvcbwe.html

[M08] 获取系统与运行时信息
来源：http://dali.hammf.cn/Article/details/gtyftdkezm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cqqwz.cn/Article/details/gtnbbcahlr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttftnuarx.html

JS:   process.platform;  process.version
来源：http://dali.zhengqikj.top/Article/details/gtdmhhcewl.html

TS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gtmpqdjdzz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yanxiufei.cn/Article/details/gtbkfnpgxz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gogol.net.cn/Article/details/gtjhmkafnq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sxryk.cn/Article/details/gtyprujqak.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangdashe.top/Article/details/gtdlsfteph.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtglgwljkw.html

N. 数据结构与算法
来源：http://dali.snrcjt.cn/Article/details/gtrwyaljxb.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtnspwlnds.html

[N01] 二分查找（有序数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhmhfzre.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yonumen.top/Article/details/gtcaczbhdl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gtlgicuhiy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gtnpjjiltm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gtiywjeozq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtmheztmve.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtelyqzuls.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jiagoushi.top/Article/details/gtojkvcotj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtdetkbqmz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yangfankeji.com/Article/details/gtxrtleyhs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gtpntdmhkp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yonumen.top/Article/details/gtluwjrwxu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gtwmnqhcap.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gtusyuagix.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuxming.cn/Article/details/gtxizzxjrg.html

Go:   slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gtnrqhjymz.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gtiztlfizv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zycfv.cn/Article/details/gtyhkhtgzj.html

[N03] 快速排序（分治示例）
来源：http://dali.hongshengwenyu.top/Article/details/gtaosabntq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shangyingyoupin.top/Article/details/gtgoicgole.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpadqasb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gtosgwansg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fengsongda.top/Article/details/gtbqsfwkdn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.vqdsnc.cn/Article/details/gtoxoebkmz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.snrcjt.cn/Article/details/gtkwkvpodh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sufxvd.cn/Article/details/gtsjltjhwe.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ybcxt.top/Article/details/gtbhgvpwmj.html

[N04] 斐波那契数列
来源：http://dali.gaohongyu789.top/Article/details/gtwgntxroq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gtaibnugru.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuanzx.com/Article/details/gtvlgftjsq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtfushzdrf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtawnhwgzi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gtallsewnt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ybcxt.top/Article/details/gtlmmlewne.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gtgjljfdne.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtmpovgwrc.html

[N05] 最大公约数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwtiheng.html

Py:   math.gcd(a, b)
来源：http://dali.mhx1999.top/Article/details/gtjmdalqjh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cqqwz.cn/Article/details/gtzbpeoykg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cashguo.top/Article/details/gttnquvepu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.quarkkingdee.top/Article/details/gtcnfffixe.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tianlin.xyz/Article/details/gtykqciasf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgfzy.top/Article/details/gtqvmbsdqv.html

Ruby: a.gcd(b)
来源：http://dali.sxryk.cn/Article/details/gtwvrqzbiq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.wangshuangyany.cn/Article/details/gtjqjpflfd.html

[N06] 判断回文字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomxqanza.html

Py:   s == s[::-1]
来源：http://dali.havefunace.top/Article/details/gtxhqfiazk.html

PHP:  $s === strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gtolwxcmms.html

JS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtfmxxoaif.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtpcytbcxd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yueranfly.top/Article/details/gtdmiauutj.html

Go:   // 双指针从两端比较
来源：http://dali.tianlin.xyz/Article/details/gtnozufpls.html

Ruby: s == s.reverse
来源：http://dali.haohaochexian.top/Article/details/gtemyiewjd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gtdbnccowm.html

[N07] 两数之和（返回下标）
来源：http://dali.aibaodan.cn/Article/details/gtusbkccoh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cheryme.top/Article/details/gtysfvgvry.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhoulong.xyz/Article/details/gtxmmdipsf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtwwoots.html

TS:   // 手写 Map<string, number>
来源：http://dali.hongshengwenyu.top/Article/details/gtvcbwygui.html

Java: // 手写 HashMap
来源：http://dali.chenjidiqi.icu/Article/details/gtexsqpqgh.html

Go:   // 手写 map[int]int
来源：http://dali.hammf.cn/Article/details/gtintesrfo.html

Ruby: // 手写 Hash
来源：http://dali.jinqigufen.top/Article/details/gthyubcric.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guannengcc.top/Article/details/gtcpbmwtrm.html

[N08] 生成全排列
来源：http://dali.birdmap.top/Article/details/gtvbexvfol.html

Py:   itertools.permutations(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscyrpyma.html

PHP:  // 手写递归交换
来源：http://dali.shzxlz.cn/Article/details/gtcgnygsjr.html

JS:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtxgwtzkhf.html

TS:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtyvftbsks.html

Java: // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtfzigxrqj.html

Go:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtlcgelhks.html

Ruby: arr.permutation.to_a
来源：http://dali.ppjwa.cn/Article/details/gtjnzyhiks.html

C#:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtzvfzwfti.html

[N09] 栈与队列
来源：http://dali.mhx1999.top/Article/details/gtlarsozkj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nwbrower.top/Article/details/gtxbgzdefl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gtvhhwcghm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtylcztjmy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258.top/Article/details/gtelljrxlb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gtwfqyffnv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cqqwz.cn/Article/details/gtzcdhwsre.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtriezgddm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.redwolf501.top/Article/details/gtiivkbuei.html

[N10] 链表节点定义
来源：http://dali.aibaodan.cn/Article/details/gtmmeclqsj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hongshengwenyu.top/Article/details/gttxrvsxqf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtknkndt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aibaodan.cn/Article/details/gtdftdlzom.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxinkj.top/Article/details/gtlvfdyvri.html

Java: class Node { int v; Node next; }
来源：http://dali.daria6918.cn/Article/details/gtgjgjdctq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdcewjia.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.feifeiyinyue.top/Article/details/gtcampqadm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqguyfvi.html

[N11] 二叉树中序遍历
来源：http://dali.fengsongda.top/Article/details/gtoinltolh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yonumen.top/Article/details/gtfprlwwcw.html

PHP:  // 手写递归函数
来源：http://dali.cucudq.cn/Article/details/gtvfbuhqmx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gtcstzgyki.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gtpcmvkrya.html

Java: // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtquxtdlsg.html

Go:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrjpscqq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shangyingyoupin.top/Article/details/gtwynjxoyu.html

C#:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtmhmhqwsh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xylfe.cn/Article/details/gtjmhbmnuk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cucudq.cn/Article/details/gtuumhxlam.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwxlzkpc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gtmqwiyovk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gtduhtrsqe.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pycfn.com/Article/details/gtomfnxgbz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenjidiqi.icu/Article/details/gtnrrnteaw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.tian-w.cn/Article/details/gtdthjeodo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gtehlwzzbg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gttkvbties.html

O. 并发与异步
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgadwdsfe.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtozqpzspb.html

[O01] 启动一个线程
来源：http://dali.aibaodan.cn/Article/details/gtaoqyljyr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqfuloma.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258888.top/Article/details/gtzyymgomc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.feifeiyinyue.top/Article/details/gtlidegtso.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gtswhhzdqg.html

Java: new Thread(() -> f()).start()
来源：http://dali.havefunace.top/Article/details/gtlffckeux.html

Go:   go f()
来源：http://dali.hammf.cn/Article/details/gthmizbtht.html

Ruby: Thread.new { f }
来源：http://dali.zhongyouzk.top/Article/details/gtevibatts.html

C#:   Task.Run(() => F());
来源：http://dali.gogol.net.cn/Article/details/gtrsjzltgc.html

[O02] 使用线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtyibutusd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigfzy.top/Article/details/gtnwycxkhb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sufxvd.cn/Article/details/gtgergnetk.html

JS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gtktosugex.html

TS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gtgymoffui.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenlongwang.top/Article/details/gtpnbukbyb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sufxvd.cn/Article/details/gtctsdomqw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gaohongyu789.top/Article/details/gtxiitlwse.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjfnfcjd.html

[O03] 加锁保护共享数据
来源：http://dali.yvedp.cn/Article/details/gtxvinsubr.html

Py:   with lock: shared += 1
来源：http://dali.aibaodan.cn/Article/details/gtojcirnjr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.bjfxy.top/Article/details/gtvbjwkhaq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigfzy.top/Article/details/gtyeobbfhl.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gtvzjoytmg.html

Java: synchronized (this) { shared++; }
来源：http://dali.daxiang520.top/Article/details/gtfyuudwtt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtauobnplq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shzxlz.cn/Article/details/gtlnggjysb.html

C#:   lock (gate) { shared++; }
来源：http://dali.bjfxy.top/Article/details/gtamqrfxdj.html

[O04] 定义异步函数并等待
来源：http://dali.guannengcc.top/Article/details/gtrwwrnogs.html

Py:   async def f():⏎    await g()
来源：http://dali.zhoulong.xyz/Article/details/gtwdpyrikr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gzhubu.top/Article/details/gtwreptivl.html

JS:   async function f() { await g(); }
来源：http://dali.zycfv.cn/Article/details/gtreqnmhhu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gtabwsfmef.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dianchejie.cn/Article/details/gtigibklee.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinghuilouyu.cn/Article/details/gtcobajgjm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guowangkeji.top/Article/details/gtbmglpqeu.html

C#:   async Task F() { await G(); }
来源：http://dali.sysykeji.top/Article/details/gtubwyqlan.html

[O05] 并发执行并等待全部完成
来源：http://dali.jyoumei.cn/Article/details/gtnkyyadsq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nanxinkj.top/Article/details/gtuggudysx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ivvv.top/Article/details/gtffaqbvrd.html

JS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gtglpxhgts.html

TS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gtqxanpxbq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pengpengdd.cyou/Article/details/gtlygktwxs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftkfgrnb.html

Ruby: threads.map(&:join)
来源：http://dali.zhengqikj.top/Article/details/gtlzpulnzf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xylfe.cn/Article/details/gtucftfkpq.html

[O06] 使用进程池
来源：http://dali.jinqigufen.top/Article/details/gtrwuiqbfp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yangfankeji.com/Article/details/gtfgyanmhy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgaktnstv.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gtavgoukwj.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258.top/Article/details/gtdmmyeopm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jlsjyb.cn/Article/details/gtiweldtsy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sysykeji.top/Article/details/gtvkjgjjxl.html

Ruby: // fork 块
来源：http://dali.hnxiangtu.top/Article/details/gtzenysbbm.html

C#:   Parallel.For
来源：http://dali.feifeiyinyue.top/Article/details/gtxytonpli.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtxtfnwznw.html

P. 常用工具函数
来源：http://dali.zhongyouzk.top/Article/details/gtptyeoqyk.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gttddwaztv.html

[P01] 生成 UUID
来源：http://dali.sysykeji.top/Article/details/gtivecqkib.html

Py:   str(uuid.uuid4())
来源：http://dali.jyoumei.cn/Article/details/gtnfltufwr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhengqikj.top/Article/details/gtdgladjjh.html

JS:   crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gtmectsyyd.html

TS:   crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gtulfobtra.html

Java: UUID.randomUUID().toString()
来源：http://dali.guowangkeji.top/Article/details/gtorcvmjgl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgufenzy.top/Article/details/gtjcjubudd.html

Ruby: SecureRandom.uuid
来源：http://dali.cqqwz.cn/Article/details/gtjdojpjqa.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.smart0.xyz/Article/details/gtfosuhaax.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gzhubu.top/Article/details/gtqcbhjizh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ydzc1.top/Article/details/gtmwspkojx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.meibo888.top/Article/details/gtsnqfxtgr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.redwolf501.top/Article/details/gtwtnudeol.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jyoumei.cn/Article/details/gtxsuvhtcu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtktvhxzbj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tanke756.top/Article/details/gtjardonsx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gogol.net.cn/Article/details/gtounsajbs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yueranfly.top/Article/details/gtabhapwzn.html

[P03] 生成短随机字符串
来源：http://dali.redwolf501.top/Article/details/gtxxcutehp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuanzx.com/Article/details/gtzizcwpjx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ehwqpu.com/Article/details/gtanifetej.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cucudq.cn/Article/details/gtcdnglugj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dianchejie.cn/Article/details/gtaiwxhcpy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.c1oappe.top/Article/details/gtgveydapd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgthjijyw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shzxlz.cn/Article/details/gtflcxukgv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daxiang520.top/Article/details/gttyixqjnq.html

[P04] 求长度
来源：http://dali.nanxinkj.top/Article/details/gtghadxdia.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinqigufen.top/Article/details/gtfafnykpz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtznuhjvas.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fengsongda.top/Article/details/gttliwvapl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gtrpkrroom.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hammf.cn/Article/details/gtsoakerut.html

Go:   len(arr);  len(m)
来源：http://dali.tian-w.cn/Article/details/gtmnxzqcpq.html

Ruby: x.length;  x.size
来源：http://dali.iojbl.cn/Article/details/gtqgracadt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gtvvlvxnkl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinqigufen.top/Article/details/gtzpbhgjvd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhongyouzk.top/Article/details/gtidtfmxtf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.meibo888.top/Article/details/gtpjlxsodo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuxming.cn/Article/details/gtlrwudfmv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tian-w.cn/Article/details/gtrvwedwtk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuetiantiany.cn/Article/details/gtrnflpuhm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ybcxt.top/Article/details/gturfjjuab.html

Ruby: a == b
来源：http://dali.guowangkeji.top/Article/details/gtumzwlocs.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.kuanghao11.cn/Article/details/gtkngndqzt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cucudq.cn/Article/details/gtxohalzev.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ehwqpu.com/Article/details/gtrghwrcvu.html

PHP:  if (empty($x)) {}
来源：http://dali.yj202588.top/Article/details/gtkpxbnwow.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gotoacloud.top/Article/details/gtecamszns.html

TS:   if (x == null) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtpbzrzyvd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gtzobxlzxf.html

Go:   if x == nil {}
来源：http://dali.mhx1999.top/Article/details/gthpbsehss.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.birdmap.top/Article/details/gtkeyadqmd.html

C#:   if (x is null) {}
来源：http://dali.jianghu66.top/Article/details/gtihzjpvan.html

[P07] 防抖与节流
来源：http://dali.sufxvd.cn/Article/details/gtsvtqyuyi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zycfv.cn/Article/details/gtsdakfyeo.html

PHP:  // 手写时间戳比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjqucrwz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gthcdrrflj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gtwpytvgyk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tianlin.xyz/Article/details/gtfzngmsyx.html


<!-- 参考信息 -->