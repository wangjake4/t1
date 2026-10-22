代发 wailian999

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2lboecfar.html

[M01] 读取命令行参数
来源：http://dali.svipenyu.cn/Article/details/gt2juqsffdh.html

Py:   sys.argv[1:]
来源：http://dali.ppjwa.cn/Article/details/gt2eqhxigfz.html

PHP:  $argv;  $argc;
来源：http://dali.xuanzx.com/Article/details/gt2kxxxngzm.html

JS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gt2arjjxyab.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gt2zkhvogvf.html

Java: args 数组（main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gt2jbssxgbf.html

Go:   os.Args[1:]
来源：http://dali.jianghu66.top/Article/details/gt2bsfnuuuk.html

Ruby: ARGV
来源：http://dali.yj20258888.top/Article/details/gt2rlsxbeks.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gt2sulpuqpv.html

[M02] 读取环境变量
来源：http://dali.yongpay.top/Article/details/gt2iikesimt.html

Py:   os.environ.get("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gt2lqyhesbv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gotoacloud.top/Article/details/gt2twoersdy.html

JS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gt2bihrwnvq.html

TS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gt2ovoomphl.html

Java: System.getenv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2chgolxtk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gt2jjwcqanh.html

Ruby: ENV["HOME"]
来源：http://dali.feifeiyinyue.top/Article/details/gt2kknxmdgy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2xjsnneix.html

[M03] 执行外部命令
来源：http://dali.tanke756.top/Article/details/gt2ebxqtgps.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhengqikj.top/Article/details/gt2qmkokhyu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.birdmap.top/Article/details/gt2hrdgfcqk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gt2gzlpxzxo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gt2ytpzqrmr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangdashe.top/Article/details/gt2sjnfbeah.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nwbrower.top/Article/details/gt2nryxxvux.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yonumen.top/Article/details/gt2egakitdl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnxiangtu.top/Article/details/gt2pcjnuaiv.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gt2kzcdites.html

Py:   os.getcwd()
来源：http://dali.cashguo.top/Article/details/gt2qgefwulp.html

PHP:  getcwd();
来源：http://dali.cashguo.top/Article/details/gt2alxlbafq.html

JS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gt2yfkqcjyd.html

TS:   process.cwd()
来源：http://dali.jiagoushi.top/Article/details/gt2wnuhxalk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guannengcc.top/Article/details/gt2tvknmgtq.html

Go:   os.Getwd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2rvgfpddl.html

Ruby: Dir.pwd
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sobfjrfn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ehwqpu.com/Article/details/gt2meqgprqq.html

[M05] 设置退出码
来源：http://dali.meibo888.top/Article/details/gt2uwwxamkx.html

Py:   sys.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2vcocfthz.html

PHP:  exit(1);
来源：http://dali.tian-w.cn/Article/details/gt2heparbof.html

JS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gt2ljtobisd.html

TS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2jysijcsg.html

Java: System.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2sfkrvgrc.html

Go:   os.Exit(1)
来源：http://dali.bjfxy.top/Article/details/gt2kiiucllt.html

Ruby: exit 1
来源：http://dali.vqdsnc.cn/Article/details/gt2ovxdpvit.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fengsongda.top/Article/details/gt2yhocmcas.html

[M06] 向标准错误输出
来源：http://dali.yangfankeji.com/Article/details/gt2mauhszfx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rciqirvr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pycfn.com/Article/details/gt2iobpipte.html

JS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gt2mkrspflq.html

TS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gt2ygcpeicb.html

Java: System.err.println("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cisaemsu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yanxiufei.cn/Article/details/gt2xbweunlg.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqgjrli.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uxpjkvnn.html

[M07] 判断是否为主入口
来源：http://dali.tian-w.cn/Article/details/gt2dlnotnqj.html

Py:   if __name__ == "__main__":
来源：http://dali.zhengqikj.top/Article/details/gt2cjqgxigm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2vyaurvnp.html

JS:   require.main === module
来源：http://dali.snrcjt.cn/Article/details/gt2eisuiyos.html

TS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gt2uwnggbbi.html

Java: public static void main(String[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wpdyygaq.html

Go:   func main()
来源：http://dali.xinyue.icu/Article/details/gt2jektblrz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dianchejie.cn/Article/details/gt2dcrxvdyf.html

C#:   static void Main(string[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hmmdvfem.html

[M08] 获取系统与运行时信息
来源：http://dali.bjfxy.top/Article/details/gt2nketiswd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sysykeji.top/Article/details/gt2lzffdwnn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hfpthk.cn/Article/details/gt2vaszmopn.html

JS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gt2dlrrxbdu.html

TS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gt2opqigcik.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ppjwa.cn/Article/details/gt2hreyszvv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zycfv.cn/Article/details/gt2ulgmvjwu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xylfe.cn/Article/details/gt2ykycpnam.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tanke756.top/Article/details/gt2bpuwcbwr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2dvbgrabu.html

N. 数据结构与算法
来源：http://dali.gogol.net.cn/Article/details/gt2qzvrvfma.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2omdsvlcw.html

[N01] 二分查找（有序数组）
来源：http://dali.yuanzhike.top/Article/details/gt2nuhnsufb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2yquwzvrs.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.meibo888.top/Article/details/gt2vetunfpw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gt2idnymkcq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gt2wxlfqwmc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2wexquxku.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2drgokdxu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xinyue.icu/Article/details/gt2libsiscz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2unmyvnyz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuanzx.com/Article/details/gt2lkvjbdyt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2duhynexi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dianchejie.cn/Article/details/gt2rwuwjiuy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gt2ifsleyjx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gt2bedfxeqt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnxiangtu.top/Article/details/gt2pupbbqhj.html

Go:   slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2skztzbha.html

Ruby: arr.sort
来源：http://dali.dianchejie.cn/Article/details/gt2mdjkxknj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hfpthk.cn/Article/details/gt2rgqjalxj.html

[N03] 快速排序（分治示例）
来源：http://dali.bjfxy.top/Article/details/gt2fvclsott.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zdqjudy.top/Article/details/gt2hqddrqvp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ivvv.top/Article/details/gt2fgyycjyo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vlcwjdjj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gt2ekiqawbr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daxiang520.top/Article/details/gt2ccuhwkrx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.feifeiyinyue.top/Article/details/gt2jpgmqlgz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fonnrlie.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhiwuduotai.top/Article/details/gt2ggdctnjd.html

[N04] 斐波那契数列
来源：http://dali.tian-w.cn/Article/details/gt2flxnjlwz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gt2enukchbf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gt2ixkasnvp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gt2eeuivpmz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gt2vowuzrgl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ydzc1.top/Article/details/gt2mwirsyin.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yongpay.top/Article/details/gt2jmfwprkd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2akivrthb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2zctmoivi.html

[N05] 最大公约数
来源：http://dali.sweek.top/Article/details/gt2tibgpaiz.html

Py:   math.gcd(a, b)
来源：http://dali.chenzaomai.com/Article/details/gt2tgihqjhl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinqigfzy.top/Article/details/gt2sskpynws.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gt2aphshmlz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gt2ahkdbowo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yueranfly.top/Article/details/gt2koojgcfk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2iehaajlr.html

Ruby: a.gcd(b)
来源：http://dali.fzhhl.top/Article/details/gt2mvtafqne.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dianchejie.cn/Article/details/gt2tqubqzvp.html

[N06] 判断回文字符串
来源：http://dali.tian-w.cn/Article/details/gt2ppotfwkn.html

Py:   s == s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gt2xzfxavvp.html

PHP:  $s === strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gt2sftvczar.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2kixirrpy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2szstsxgi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuxming.cn/Article/details/gt2lwkyluve.html

Go:   // 双指针从两端比较
来源：http://dali.hysaishi.cn/Article/details/gt2ghlgcmib.html

Ruby: s == s.reverse
来源：http://dali.xziqi.cn/Article/details/gt2knvnxxbw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gt2rmldbubi.html

[N07] 两数之和（返回下标）
来源：http://dali.yanxiufei.cn/Article/details/gt2aadywbho.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.feifeiyinyue.top/Article/details/gt2qdkeuqkt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dianchejie.cn/Article/details/gt2rlainxnn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.iojbl.cn/Article/details/gt2xopoyfcx.html

TS:   // 手写 Map<string, number>
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjqjjqlo.html

Java: // 手写 HashMap
来源：http://dali.wangshuangyany.cn/Article/details/gt2cmjbbixc.html

Go:   // 手写 map[int]int
来源：http://dali.gaohongyu789.top/Article/details/gt2cxyviyjc.html

Ruby: // 手写 Hash
来源：http://dali.yj20258888.top/Article/details/gt2xuhwlkjg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuetiantiany.cn/Article/details/gt2gpapcyre.html

[N08] 生成全排列
来源：http://dali.dashuyun.cn/Article/details/gt2quihfjxa.html

Py:   itertools.permutations(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2etipvlrx.html

PHP:  // 手写递归交换
来源：http://dali.yongpay.top/Article/details/gt2howapkey.html

JS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2udadujgh.html

TS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gt2njewmqdf.html

Java: // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tpoaxzvn.html

Go:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gt2imqpsioi.html

Ruby: arr.permutation.to_a
来源：http://dali.zhiwuduotai.top/Article/details/gt2glaworro.html

C#:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2sosgdbod.html

[N09] 栈与队列
来源：http://dali.tian-w.cn/Article/details/gt2xgwglkbj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cucudq.cn/Article/details/gt2agzjidrv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.iojbl.cn/Article/details/gt2bovshyfr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2kdxcvpct.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sysykeji.top/Article/details/gt2ntpdpezp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cheryme.top/Article/details/gt2xnxtykpx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258.top/Article/details/gt2jtkzvzrd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gt2kmclxbrt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhongyouzk.top/Article/details/gt2vptuoizj.html

[N10] 链表节点定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vgsuqbdd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dianchejie.cn/Article/details/gt2ppedfpif.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ghtardim.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hnxiangtu.top/Article/details/gt2ppuppfwu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cheryme.top/Article/details/gt2lobvyipz.html

Java: class Node { int v; Node next; }
来源：http://dali.hysaishi.cn/Article/details/gt2osyexdnn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yuanzhike.top/Article/details/gt2olykrhsd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aibaodan.cn/Article/details/gt2suzkgbxv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yonumen.top/Article/details/gt2phrfdcgr.html

[N11] 二叉树中序遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2iazvvgov.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nanxinkj.top/Article/details/gt2zjmuqibq.html

PHP:  // 手写递归函数
来源：http://dali.0kj1m.cn/Article/details/gt2copytcku.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gt2hhcrexvc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.havefunace.top/Article/details/gt2lywabmkf.html

Java: // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gt2adfqnuae.html

Go:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gt2rvzpyayk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.haohaochexian.top/Article/details/gt2truqwzqy.html

C#:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gt2mvtgjykl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnxiangtu.top/Article/details/gt2iovtrtyb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shzxlz.cn/Article/details/gt2bswqmoow.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigufen.top/Article/details/gt2duuvuwot.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zxwrxgfe.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gt2jitchnnj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gt2uohdxfpl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cqqwz.cn/Article/details/gt2sunbfbaj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nwbrower.top/Article/details/gt2osepstdt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gt2jcgliajz.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2wklvlxpb.html

O. 并发与异步
来源：http://dali.fengsongda.top/Article/details/gt2fknqrgio.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2dkhvahgr.html

[O01] 启动一个线程
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jsblniuy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fomtbrub.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yvedp.cn/Article/details/gt2cdsozvdv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgufenzy.top/Article/details/gt2cmhrgqgl.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gt2ytcrsbbu.html

Java: new Thread(() -> f()).start()
来源：http://dali.cqqwz.cn/Article/details/gt2arcijema.html

Go:   go f()
来源：http://dali.birdmap.top/Article/details/gt2zrbhrjxc.html

Ruby: Thread.new { f }
来源：http://dali.zhoulong.xyz/Article/details/gt2djjwqjad.html

C#:   Task.Run(() => F());
来源：http://dali.yuanzhike.top/Article/details/gt2ulxmskti.html

[O02] 使用线程池
来源：http://dali.sufxvd.cn/Article/details/gt2vbshgsth.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fmrjdtpk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.316326.xyz/Article/details/gt2qaeuxyxs.html

JS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gt2tlygshyp.html

TS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gt2honizgmy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jiagoushi.top/Article/details/gt2igqssrzd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hysaishi.cn/Article/details/gt2vmjwbmsi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hnxiangtu.top/Article/details/gt2indvuykr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnqzz.top/Article/details/gt2gpduoukv.html

[O03] 加锁保护共享数据
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ainqcqpj.html

Py:   with lock: shared += 1
来源：http://dali.cheryme.top/Article/details/gt2eoeezfol.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hywenlv.cn/Article/details/gt2ufyhhwtq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yongpay.top/Article/details/gt2ibymasjb.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gt2ioaowabh.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gt2zxefulzh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.mhx1999.top/Article/details/gt2qtdbahul.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxinkj.top/Article/details/gt2algswhvi.html

C#:   lock (gate) { shared++; }
来源：http://dali.316326.xyz/Article/details/gt2uvffakbm.html

[O04] 定义异步函数并等待
来源：http://dali.shuidangran.top/Article/details/gt2vqjylzik.html

Py:   async def f():⏎    await g()
来源：http://dali.pycfn.com/Article/details/gt2bjeyuoag.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.316326.xyz/Article/details/gt2tnbonwul.html

JS:   async function f() { await g(); }
来源：http://dali.cheryme.top/Article/details/gt2ezddwhxi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gt2exmxoeqn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sxryk.cn/Article/details/gt2euvgixqc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daxiang520.top/Article/details/gt2agmyhrvj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.meibo888.top/Article/details/gt2lugclkxs.html

C#:   async Task F() { await G(); }
来源：http://dali.hysaishi.cn/Article/details/gt2nxdnqnnb.html

[O05] 并发执行并等待全部完成
来源：http://dali.jlsjyb.cn/Article/details/gt2qbwmjwgv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.redwolf501.top/Article/details/gt2sabosfdx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shangyingyoupin.top/Article/details/gt2xpscektt.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgufenzy.top/Article/details/gt2cmwxshah.html

TS:   await Promise.all(tasks)
来源：http://dali.ppjwa.cn/Article/details/gt2mixlmwhd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dyfxmjil.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.mhx1999.top/Article/details/gt2vpwydtie.html

Ruby: threads.map(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gt2ntmkngpf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xylfe.cn/Article/details/gt2boeldovc.html

[O06] 使用进程池
来源：http://dali.zhiwuduotai.top/Article/details/gt2wxftjqnt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.aizwys.cn/Article/details/gt2kpjlxffr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2kbkdnsct.html

JS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gt2skrxdkbk.html

TS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gt2lcojlppj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinqigfzy.top/Article/details/gt2cwpxopep.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cheryme.top/Article/details/gt2veiwjdyt.html

Ruby: // fork 块
来源：http://dali.quarkkingdee.top/Article/details/gt2mxnlmlmg.html

C#:   Parallel.For
来源：http://dali.fzhhl.top/Article/details/gt2ulixpaaa.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2rzpvusyw.html

P. 常用工具函数
来源：http://dali.yanxiufei.cn/Article/details/gt2dtzclpsm.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2vkdghxvn.html

[P01] 生成 UUID
来源：http://dali.ivvv.top/Article/details/gt2gbjjpsua.html

Py:   str(uuid.uuid4())
来源：http://dali.9152youxi.cn/Article/details/gt2ermnvcjb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lhgupmdp.html

JS:   crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gt2hhnowuds.html

TS:   crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gt2mpnssniu.html

Java: UUID.randomUUID().toString()
来源：http://dali.hywenlv.cn/Article/details/gt2bobqgnxt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ydzc1.top/Article/details/gt2znhzdorw.html

Ruby: SecureRandom.uuid
来源：http://dali.yvedp.cn/Article/details/gt2samqiqvl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.havefunace.top/Article/details/gt2athtqbzm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhixingplan.top/Article/details/gt2nvomogxx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tianlin.xyz/Article/details/gt2nvrjdxri.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yvedp.cn/Article/details/gt2gpgfcjzv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fqvrvxlq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sufxvd.cn/Article/details/gt2pxbjeped.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.meibo888.top/Article/details/gt2eiaonwka.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.haohaochexian.top/Article/details/gt2vlsiwije.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxinkj.top/Article/details/gt2xivvsgff.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangshuangyany.cn/Article/details/gt2lwgyrruf.html

[P03] 生成短随机字符串
来源：http://dali.sysykeji.top/Article/details/gt2vgjcavtx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yuxming.cn/Article/details/gt2khkezhai.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daxiang520.top/Article/details/gt2eruvqdsj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gt2byclttur.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tanke756.top/Article/details/gt2bduodxlz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenzaomai.com/Article/details/gt2nrqtbrfd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.0kj1m.cn/Article/details/gt2zkjzygwj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.quarkkingdee.top/Article/details/gt2jmnfjcpe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fzhhl.top/Article/details/gt2ufuanhkn.html

[P04] 求长度
来源：http://dali.andypj.xyz/Article/details/gt2mhedmvjg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sufxvd.cn/Article/details/gt2awdscyjt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gt2vbhoswyq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gt2mnilatin.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gt2vsipukfl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xopltjxk.html

Go:   len(arr);  len(m)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vgogemvs.html

Ruby: x.length;  x.size
来源：http://dali.fzhhl.top/Article/details/gt2cftockri.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cqqwz.cn/Article/details/gt2amcbuhtl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sufxvd.cn/Article/details/gt2zsslbdpy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yuanzhike.top/Article/details/gt2rtlniwab.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yanxiufei.cn/Article/details/gt2khhgxotk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jyoumei.cn/Article/details/gt2kcmzckqy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gogol.net.cn/Article/details/gt2nxmytzst.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hysaishi.cn/Article/details/gt2raunmttx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gotoacloud.top/Article/details/gt2pnpecnnd.html

Ruby: a == b
来源：http://dali.zhiwuduotai.top/Article/details/gt2wusawxzx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cashguo.top/Article/details/gt2dzpqojlo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sufxvd.cn/Article/details/gt2wtlmsrck.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xinyue.icu/Article/details/gt2lmcgzvre.html

PHP:  if (empty($x)) {}
来源：http://dali.hnqzz.top/Article/details/gt2xuqfxanw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.iojbl.cn/Article/details/gt2dlsipjlv.html

TS:   if (x == null) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2xmyqocub.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sxryk.cn/Article/details/gt2rclepcgl.html

Go:   if x == nil {}
来源：http://dali.yonumen.top/Article/details/gt2jlngbghq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhoulong.xyz/Article/details/gt2pzpdgneb.html

C#:   if (x is null) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2zuiqsmnc.html

[P07] 防抖与节流
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sddqhgqf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenlongwang.top/Article/details/gt2fuuyrgyc.html


<!-- 参考信息 -->