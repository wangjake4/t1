代发 wailian999

Ruby: ARGV
来源：http://dali.hfpthk.cn/Article/details/gtiqcpejru.html

C#:   args 数组（Main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gtawtwosfy.html

[M02] 读取环境变量
来源：http://dali.birdmap.top/Article/details/gtogwatfok.html

Py:   os.environ.get("HOME")
来源：http://dali.cashguo.top/Article/details/gtgjnoulkx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gthvyakowl.html

JS:   process.env.HOME
来源：http://dali.316326.xyz/Article/details/gtwdwgbqjq.html

TS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gtwloftifv.html

Java: System.getenv("HOME")
来源：http://dali.iojbl.cn/Article/details/gtbemqapfc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gthaepyrfr.html

Ruby: ENV["HOME"]
来源：http://dali.wangdashe.top/Article/details/gtxphpxfen.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj202588.top/Article/details/gtdtiyxhfz.html

[M03] 执行外部命令
来源：http://dali.xuanzx.com/Article/details/gtlecprrxh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cdnleiting.top/Article/details/gtsmgwjewe.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspypwuws.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gtwtzmuvky.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gtryzdymmc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aibaodan.cn/Article/details/gtrdcczkaz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gtnmepuwxc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhongyouzk.top/Article/details/gtjnlrqrje.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jlsjyb.cn/Article/details/gtrqjqqwre.html

[M04] 获取当前工作目录
来源：http://dali.hnxiangtu.top/Article/details/gtkfznsfhw.html

Py:   os.getcwd()
来源：http://dali.tianlin.xyz/Article/details/gtxeccsbpp.html

PHP:  getcwd();
来源：http://dali.kuanghao11.cn/Article/details/gtzqipfjcs.html

JS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gthicmrouo.html

TS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gtldtbgpsa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daria6918.cn/Article/details/gtakccpyux.html

Go:   os.Getwd()
来源：http://dali.meibo888.top/Article/details/gtjvirsjla.html

Ruby: Dir.pwd
来源：http://dali.andypj.xyz/Article/details/gtkiinvrpq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.c1oappe.top/Article/details/gtjrwakbab.html

[M05] 设置退出码
来源：http://dali.cheryme.top/Article/details/gtereshsoz.html

Py:   sys.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtldezlhwj.html

PHP:  exit(1);
来源：http://dali.0kj1m.cn/Article/details/gtzzasiqjc.html

JS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtlhuqafkf.html

TS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gttvssyfep.html

Java: System.exit(1)
来源：http://dali.tanke756.top/Article/details/gttkmwunqy.html

Go:   os.Exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gttwvirjrl.html

Ruby: exit 1
来源：http://dali.yuxming.cn/Article/details/gtotcujpxn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gtkrhzvzyl.html

[M06] 向标准错误输出
来源：http://dali.zhoulong.xyz/Article/details/gtqnlkhpvu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cheryme.top/Article/details/gtgtfqkpyg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.316326.xyz/Article/details/gtkpzceibn.html

JS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gtsgtesfhz.html

TS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gtxlcdxffo.html

Java: System.err.println("err")
来源：http://dali.sufxvd.cn/Article/details/gtsxjxdnhe.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnqzz.top/Article/details/gthhjmiafg.html

Ruby: warn "err"
来源：http://dali.yvedp.cn/Article/details/gtroiwofys.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gtkescayfv.html

[M07] 判断是否为主入口
来源：http://dali.jyoumei.cn/Article/details/gtszsqbcoe.html

Py:   if __name__ == "__main__":
来源：http://dali.yvedp.cn/Article/details/gtckeogqji.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dashuyun.cn/Article/details/gtumlqzwjn.html

JS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gtalyzcctb.html

TS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gtpcxvjiir.html

Java: public static void main(String[] args)
来源：http://dali.hammf.cn/Article/details/gtagnffkur.html

Go:   func main()
来源：http://dali.yanxiufei.cn/Article/details/gtukzbcxkj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tian-w.cn/Article/details/gtdmhzsejy.html

C#:   static void Main(string[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gtdcaugexx.html

[M08] 获取系统与运行时信息
来源：http://dali.sufxvd.cn/Article/details/gtdgmciwun.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gzhubu.top/Article/details/gtlqnrrrek.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuetiantiany.cn/Article/details/gtvrkfzvnv.html

JS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gthqcwtqhj.html

TS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gtemqxsblp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hfpthk.cn/Article/details/gtmdsayihy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shangyingyoupin.top/Article/details/gtkbwhzihl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhoulong.xyz/Article/details/gtfzksyahk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aibaodan.cn/Article/details/gtyauhqmar.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtdznjpywf.html

N. 数据结构与算法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbvielhx.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtybiwmwxg.html

[N01] 二分查找（有序数组）
来源：http://dali.cqqwz.cn/Article/details/gtgcvdpzoc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtpxqlxfgi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtlelztylp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtsglxyxvx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtiaijclyo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtgdawvrto.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ivvv.top/Article/details/gtpsbfgdqr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj202588.top/Article/details/gtwrljalla.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gttpzcsrgt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnxiangtu.top/Article/details/gtatkacujy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gtkccsower.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258.top/Article/details/gtdciimphp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gtwfmoujri.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gtcjaisgqq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ybcxt.top/Article/details/gtmhovqyrt.html

Go:   slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmlzyttll.html

Ruby: arr.sort
来源：http://dali.hnxiangtu.top/Article/details/gtrrvzcgnv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ydzc1.top/Article/details/gttmcylyrp.html

[N03] 快速排序（分治示例）
来源：http://dali.chenjidiqi.icu/Article/details/gtksdweyyf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gaohongyu789.top/Article/details/gthixhfude.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hongshengwenyu.top/Article/details/gtrkhduvgw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gttxszumxg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuanzhike.top/Article/details/gtuuqeeckn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dianchejie.cn/Article/details/gtyhzltsyx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuanzx.com/Article/details/gtucljrvmz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xinyue.icu/Article/details/gtghivdarr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daxiang520.top/Article/details/gtoqgkgree.html

[N04] 斐波那契数列
来源：http://dali.sxryk.cn/Article/details/gtlfldnyjo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daxiang520.top/Article/details/gtjjrrggjd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.mhx1999.top/Article/details/gtqstknrty.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtxtckjljv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gthzyzkkno.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.bjfxy.top/Article/details/gtbyyeomkn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hywenlv.cn/Article/details/gttvhkoaxs.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gtkiquljdp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gtbdnguplx.html

[N05] 最大公约数
来源：http://dali.xuetiantiany.cn/Article/details/gttdbuyrmc.html

Py:   math.gcd(a, b)
来源：http://dali.ybcxt.top/Article/details/gtwtdpgcjh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xinyue.icu/Article/details/gthmltbbjw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gtqjyyehld.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gzhubu.top/Article/details/gtrryyjzpg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.c1oappe.top/Article/details/gtpxhplgeh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.mhx1999.top/Article/details/gtmicdfhrf.html

Ruby: a.gcd(b)
来源：http://dali.hywenlv.cn/Article/details/gtffneirdv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258888.top/Article/details/gtbbxqvnrz.html

[N06] 判断回文字符串
来源：http://dali.havefunace.top/Article/details/gtddolyhaq.html

Py:   s == s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gtvzxubqhy.html

PHP:  $s === strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtqtsmiuue.html

JS:   s === [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtqrlmjrdb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtxipzatps.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zycfv.cn/Article/details/gtacshxgee.html

Go:   // 双指针从两端比较
来源：http://dali.xinyue.icu/Article/details/gthniryjhe.html

Ruby: s == s.reverse
来源：http://dali.xziqi.cn/Article/details/gtnonditxi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gtlcdjqljk.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258.top/Article/details/gtfaborspo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigfzy.top/Article/details/gtihjwvlfo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.svipenyu.cn/Article/details/gtptebcvdw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gaohongyu789.top/Article/details/gtpardrnua.html

TS:   // 手写 Map<string, number>
来源：http://dali.kuanghao11.cn/Article/details/gtgsbzujef.html

Java: // 手写 HashMap
来源：http://dali.hfpthk.cn/Article/details/gtlkhkhogq.html

Go:   // 手写 map[int]int
来源：http://dali.daria6918.cn/Article/details/gtgmazzcpb.html

Ruby: // 手写 Hash
来源：http://dali.pengpengdd.cyou/Article/details/gtzehocxcp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangtech.top/Article/details/gtarjzcnwl.html

[N08] 生成全排列
来源：http://dali.wangshuangyany.cn/Article/details/gthfgeqvns.html

Py:   itertools.permutations(arr)
来源：http://dali.yj20258.top/Article/details/gtcfyhqkzi.html

PHP:  // 手写递归交换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzryqlljj.html

JS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtimtvaoxl.html

TS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtlckoqakt.html

Java: // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gttfxxgyla.html

Go:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtctectzlc.html

Ruby: arr.permutation.to_a
来源：http://dali.cheryme.top/Article/details/gttjrnseem.html

C#:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtyyvhghmr.html

[N09] 栈与队列
来源：http://dali.zhixingplan.top/Article/details/gtwlxilhfg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.haohaochexian.top/Article/details/gtffrgkwko.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gtuxptoigq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gtscsvboww.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jlsjyb.cn/Article/details/gtqawmkkad.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gtnzocuxbw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jqgfzy.top/Article/details/gtbfhhhjqr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gtxcmqelxn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gtrsdgqhiu.html

[N10] 链表节点定义
来源：http://dali.andypj.xyz/Article/details/gtbdzkhdve.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuanzx.com/Article/details/gtyctmmidw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jyoumei.cn/Article/details/gtupepfmsh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sweek.top/Article/details/gtyidyynye.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ivvv.top/Article/details/gtnvopksjh.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtceqfnqia.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmilsxfqk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daria6918.cn/Article/details/gtpxfmjmpf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.snrcjt.cn/Article/details/gtbwvzjwwe.html

[N11] 二叉树中序遍历
来源：http://dali.yuanzhike.top/Article/details/gtkjejnbkj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yueranfly.top/Article/details/gtvwakdwru.html

PHP:  // 手写递归函数
来源：http://dali.hongshengwenyu.top/Article/details/gtzesmkzch.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtviizdgwv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gtaakbjcfw.html

Java: // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtztoulbaw.html

Go:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gtktddymrk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenjidiqi.icu/Article/details/gtkgtfjdrz.html

C#:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gtiunwsmta.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jianghu66.top/Article/details/gtwuwfgxxz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.andypj.xyz/Article/details/gtdteomofs.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.9152youxi.cn/Article/details/gtzvxxnvev.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gtdgyqbdxq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gtayvsbozx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gtogdoljso.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ppjwa.cn/Article/details/gtgnnkfvkf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.tianlin.xyz/Article/details/gtdyhezyqw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gtuliaryxa.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gthfcnkdqe.html

O. 并发与异步
来源：http://dali.meibo888.top/Article/details/gtixbqzorv.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtfytxdimd.html

[O01] 启动一个线程
来源：http://dali.chenjidiqi.icu/Article/details/gtwtvkfjgl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jqgfzy.top/Article/details/gtnwqawjxi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tian-w.cn/Article/details/gtgjfkfyif.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cqqwz.cn/Article/details/gteokzkzvu.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gtwywslvkq.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuxming.cn/Article/details/gtoxjraywz.html

Go:   go f()
来源：http://dali.yongpay.top/Article/details/gtcgurerzg.html

Ruby: Thread.new { f }
来源：http://dali.dianchejie.cn/Article/details/gtiaoyzvzj.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigfzy.top/Article/details/gtlfxclypy.html

[O02] 使用线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtsakguwcf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tianlin.xyz/Article/details/gtrbkxdkpa.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guannengcc.top/Article/details/gtplvvjzcj.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtqslnbaqu.html

TS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gtaprbvbpj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hammf.cn/Article/details/gtahgplwho.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hywenlv.cn/Article/details/gtxpgkaogf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gaohongyu789.top/Article/details/gtrmylmwws.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.redwolf501.top/Article/details/gtpoqrennz.html

[O03] 加锁保护共享数据
来源：http://dali.9152youxi.cn/Article/details/gtozwfdzmk.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtkrldab.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.feifeiyinyue.top/Article/details/gtajocjkhi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.kuanghao11.cn/Article/details/gtrzcwjxhc.html

TS:   // 同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gtwgjmljrh.html

Java: synchronized (this) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gtkldaekrj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nwbrower.top/Article/details/gtscyfctfd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.iojbl.cn/Article/details/gtxekuvrxn.html

C#:   lock (gate) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gtqsjyxrik.html

[O04] 定义异步函数并等待
来源：http://dali.xziqi.cn/Article/details/gtipsltkwo.html

Py:   async def f():⏎    await g()
来源：http://dali.zhixingplan.top/Article/details/gtwjwqbtrp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cashguo.top/Article/details/gtbrnhmawt.html

JS:   async function f() { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gtvwsnlwra.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtjhwpxcwz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpjndfyn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hysaishi.cn/Article/details/gtkitzsnwv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zycfv.cn/Article/details/gtwpufimxy.html

C#:   async Task F() { await G(); }
来源：http://dali.cucudq.cn/Article/details/gtpuxaaluu.html

[O05] 并发执行并等待全部完成
来源：http://dali.yongpay.top/Article/details/gtgmdcpfhd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dianchejie.cn/Article/details/gtbhijywnb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hysaishi.cn/Article/details/gtpcjddtgb.html

JS:   await Promise.all(tasks)
来源：http://dali.yonumen.top/Article/details/gtautjdlnl.html

TS:   await Promise.all(tasks)
来源：http://dali.yongpay.top/Article/details/gtgfwjrugv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gotoacloud.top/Article/details/gtarmcjnbx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gotoacloud.top/Article/details/gtzfxjhidk.html

Ruby: threads.map(&:join)
来源：http://dali.guowangkeji.top/Article/details/gtpjpfvfbc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fzhhl.top/Article/details/gtgaoutghi.html

[O06] 使用进程池
来源：http://dali.yuanzhike.top/Article/details/gtslcoihik.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xuanzx.com/Article/details/gtrvvqmmgx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.wangshuangyany.cn/Article/details/gtiemszmvm.html

JS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gtbyptjzhi.html

TS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gtfdtauxmd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fzhhl.top/Article/details/gtlcoqazww.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.andypj.xyz/Article/details/gtbcckuivl.html

Ruby: // fork 块
来源：http://dali.ehwqpu.com/Article/details/gtmnpiyrfg.html

C#:   Parallel.For
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcwrsfkl.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtfkyustlp.html

P. 常用工具函数
来源：http://dali.ppjwa.cn/Article/details/gtpbqxqixk.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtbteevhnq.html

[P01] 生成 UUID
来源：http://dali.chenzaomai.com/Article/details/gtwvlsoktc.html

Py:   str(uuid.uuid4())
来源：http://dali.hysaishi.cn/Article/details/gtbebbscrv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guowangkeji.top/Article/details/gtmhmccsdj.html

JS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gtgnafqfty.html

TS:   crypto.randomUUID()
来源：http://dali.nanxuanxn.top/Article/details/gtujoqywog.html

Java: UUID.randomUUID().toString()
来源：http://dali.xziqi.cn/Article/details/gtryajipuw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hywenlv.cn/Article/details/gteqyoacba.html

Ruby: SecureRandom.uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexpfaqci.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.vqdsnc.cn/Article/details/gtopvygwqy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuanzhike.top/Article/details/gttinbqhdg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.quarkkingdee.top/Article/details/gtlsgviggm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ydzc1.top/Article/details/gtqwuknhfz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrsrgxug.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgufenzy.top/Article/details/gtzixoocrz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.redwolf501.top/Article/details/gtiwxaofqu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.vqdsnc.cn/Article/details/gtwkqadiak.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.daxiang520.top/Article/details/gtuhspctbx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.meibo888.top/Article/details/gtsuisjfzh.html

[P03] 生成短随机字符串
来源：http://dali.gogol.net.cn/Article/details/gtltzplzhl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fzhhl.top/Article/details/gtfbdhgftf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.kuanghao11.cn/Article/details/gtnwvaildp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuxming.cn/Article/details/gtjbnghbdp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guannengcc.top/Article/details/gtabtjejhk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xylfe.cn/Article/details/gtibpwxhen.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xziqi.cn/Article/details/gtjegiauan.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhengqikj.top/Article/details/gtvudydaqh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnxiangtu.top/Article/details/gtqguqvqaj.html

[P04] 求长度
来源：http://dali.sysykeji.top/Article/details/gtfhlwlmbz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangdashe.top/Article/details/gtjdisdbrv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtftrnajan.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gttykdaewh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.snrcjt.cn/Article/details/gtgwnyhaci.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xziqi.cn/Article/details/gtwtlecyte.html

Go:   len(arr);  len(m)
来源：http://dali.guowangkeji.top/Article/details/gtsryxfbsl.html

Ruby: x.length;  x.size
来源：http://dali.guowangkeji.top/Article/details/gtwivnahrf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.guannengcc.top/Article/details/gtvygzgifm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenlongwang.top/Article/details/gtpshqdsvu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fengsongda.top/Article/details/gtbvgbjxdw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.fzhhl.top/Article/details/gtmcreeiqn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yangfankeji.com/Article/details/gtyctxpqop.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.316326.xyz/Article/details/gtjvtymask.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuanzx.com/Article/details/gtvfdubvau.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shzxlz.cn/Article/details/gtfhuivhav.html

Ruby: a == b
来源：http://dali.wangdashe.top/Article/details/gtzooucnlg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhongyouzk.top/Article/details/gtvwvrsxou.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.snrcjt.cn/Article/details/gtgbjwclrn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jqgufenzy.top/Article/details/gtdoezflvt.html

PHP:  if (empty($x)) {}
来源：http://dali.aizwys.cn/Article/details/gtygpmmyjf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cheryme.top/Article/details/gtdwmoxogb.html

TS:   if (x == null) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtoprgjcri.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jyoumei.cn/Article/details/gtnarxalha.html

Go:   if x == nil {}
来源：http://dali.guannengcc.top/Article/details/gtjaplrfcz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.havefunace.top/Article/details/gtneernhqu.html

C#:   if (x is null) {}
来源：http://dali.jlsjyb.cn/Article/details/gtefasxqdj.html

[P07] 防抖与节流
来源：http://dali.ppjwa.cn/Article/details/gtcngjftvs.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hfpthk.cn/Article/details/gtacuodwdn.html

PHP:  // 手写时间戳比较
来源：http://dali.ivvv.top/Article/details/gtqcihummh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gtwnwtrftt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtvuased.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtdhtrsvet.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gaohongyu789.top/Article/details/gtkgnvcsaz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sweek.top/Article/details/gtfrtfjfyk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xylfe.cn/Article/details/gtwlaqyamw.html

[P08] 处理浮点精度问题
来源：http://dali.cqqwz.cn/Article/details/gtdlsnnswy.html


<!-- 参考信息 -->