代发 wailian999

Ruby: ARGV
来源：http://dali.fzhhl.top/Article/details/gt2cboqcqzp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gt2lakjvrrj.html

[M02] 读取环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2jajolpwb.html

Py:   os.environ.get("HOME")
来源：http://dali.cashguo.top/Article/details/gt2dkwkgxth.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhongyouzk.top/Article/details/gt2kreiejdu.html

JS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gt2cepyxgsh.html

TS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gt2sljsnpcx.html

Java: System.getenv("HOME")
来源：http://dali.wangdashe.top/Article/details/gt2quxnjuja.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gt2pzcbnhbo.html

Ruby: ENV["HOME"]
来源：http://dali.hnxiangtu.top/Article/details/gt2extnwotz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gt2nrzqltem.html

[M03] 执行外部命令
来源：http://dali.cqqwz.cn/Article/details/gt2scudavwl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hongshengwenyu.top/Article/details/gt2owzrparl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zycfv.cn/Article/details/gt2mfgzjyad.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2vlevfghf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gt2znjglvsn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hongshengwenyu.top/Article/details/gt2yftqxqkz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cucudq.cn/Article/details/gt2dlmlptxh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sufxvd.cn/Article/details/gt2ypwscrou.html

C#:   Process.Start("ls", "-l");
来源：http://dali.andypj.xyz/Article/details/gt2ggcdiatf.html

[M04] 获取当前工作目录
来源：http://dali.snrcjt.cn/Article/details/gt2fufolgku.html

Py:   os.getcwd()
来源：http://dali.cashguo.top/Article/details/gt2ltdrdskv.html

PHP:  getcwd();
来源：http://dali.quarkkingdee.top/Article/details/gt2ohdgvtqt.html

JS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gt2qstnbfon.html

TS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gt2qiuxpyum.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ifzxlplx.html

Go:   os.Getwd()
来源：http://dali.shangyingyoupin.top/Article/details/gt2afoowmgt.html

Ruby: Dir.pwd
来源：http://dali.zhengqikj.top/Article/details/gt2gegrnfkt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pengpengdd.cyou/Article/details/gt2yjwfjxvh.html

[M05] 设置退出码
来源：http://dali.cdnleiting.top/Article/details/gt2siflfonj.html

Py:   sys.exit(1)
来源：http://dali.yj20258.top/Article/details/gt2wtafmnpk.html

PHP:  exit(1);
来源：http://dali.hnxiangtu.top/Article/details/gt2syzbrgou.html

JS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2yraabvzu.html

TS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nbukbibx.html

Java: System.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2ktgecsxd.html

Go:   os.Exit(1)
来源：http://dali.ybcxt.top/Article/details/gt2ixrgzzzm.html

Ruby: exit 1
来源：http://dali.zycfv.cn/Article/details/gt2fvpkrxwy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxinkj.top/Article/details/gt2kbkpkxbt.html

[M06] 向标准错误输出
来源：http://dali.ppjwa.cn/Article/details/gt2bukcmttj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gzhubu.top/Article/details/gt2owaycvpc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gogol.net.cn/Article/details/gt2xllrlzyk.html

JS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2dziqrcex.html

TS:   console.error("err")
来源：http://dali.sxryk.cn/Article/details/gt2okuhilup.html

Java: System.err.println("err")
来源：http://dali.hysaishi.cn/Article/details/gt2nttwdsgb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xylfe.cn/Article/details/gt2lwjjqffx.html

Ruby: warn "err"
来源：http://dali.nwbrower.top/Article/details/gt2mghnwwcm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guannengcc.top/Article/details/gt2ajtyvtuf.html

[M07] 判断是否为主入口
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zuzefqws.html

Py:   if __name__ == "__main__":
来源：http://dali.birdmap.top/Article/details/gt2vcbpvpvu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ppjwa.cn/Article/details/gt2uwlfonvc.html

JS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gt2jlqojeck.html

TS:   require.main === module
来源：http://dali.yonumen.top/Article/details/gt2pfpteirn.html

Java: public static void main(String[] args)
来源：http://dali.sxryk.cn/Article/details/gt2nuuhsoxa.html

Go:   func main()
来源：http://dali.shangyingyoupin.top/Article/details/gt2zwedpdpf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sweek.top/Article/details/gt2qbqhrfvq.html

C#:   static void Main(string[] args)
来源：http://dali.jyoumei.cn/Article/details/gt2wqjyhaek.html

[M08] 获取系统与运行时信息
来源：http://dali.tianlin.xyz/Article/details/gt2sjsfktgj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgufenzy.top/Article/details/gt2muxgbplw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.smart0.xyz/Article/details/gt2drlvxesi.html

JS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gt2awusdvbz.html

TS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gt2qocztkag.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hfpthk.cn/Article/details/gt2tjidcxuk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xziqi.cn/Article/details/gt2bpzkyzfl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gt2sfqmkokn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.birdmap.top/Article/details/gt2gfalrgad.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2ppisxicy.html

N. 数据结构与算法
来源：http://dali.nanxuanxn.top/Article/details/gt2jhbtqomd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2kuvwccbt.html

[N01] 二分查找（有序数组）
来源：http://dali.sysykeji.top/Article/details/gt2ohdrvhvn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2bsepsjtf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wcemyvde.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gt2eqhqmgtx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gt2vmucqfpk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2oqnhfhza.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2rwarpuno.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cucudq.cn/Article/details/gt2tfmybgdm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2orcgshky.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigufen.top/Article/details/gt2mnqljdpe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gt2sbusbxtn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nwbrower.top/Article/details/gt2ueaatgvx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gt2uexdhavo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gt2kkiefagc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.vqdsnc.cn/Article/details/gt2adujuwnf.html

Go:   slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gt2qmzmibxl.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gt2msecaczn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fzhhl.top/Article/details/gt2btrodxoq.html

[N03] 快速排序（分治示例）
来源：http://dali.fengsongda.top/Article/details/gt2mmaemqmr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zycfv.cn/Article/details/gt2xpadfsqk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zdqjudy.top/Article/details/gt2otffltoj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gt2mdtamrcl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.0kj1m.cn/Article/details/gt2tmglhpxe.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnxiangtu.top/Article/details/gt2mqcmhrry.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.feifeiyinyue.top/Article/details/gt2pncinfzu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yuxming.cn/Article/details/gt2uonnjdga.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258.top/Article/details/gt2zidibvah.html

[N04] 斐波那契数列
来源：http://dali.hnqzz.top/Article/details/gt2qkgdspke.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2pmwtfxdm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cjkxdazb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gt2chxfsubp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gt2tiacisna.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gt2zkzfyzst.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guannengcc.top/Article/details/gt2axzknhxr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2vanirtoa.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ouykmuxt.html

[N05] 最大公约数
来源：http://dali.zhongyouzk.top/Article/details/gt2spdfxmjx.html

Py:   math.gcd(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2phmpzxia.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhengqikj.top/Article/details/gt2jhqwdsls.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gt2vwcdmjuk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gt2efkeufja.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gzhubu.top/Article/details/gt2gknrcjzl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tian-w.cn/Article/details/gt2figpxjxe.html

Ruby: a.gcd(b)
来源：http://dali.shzxlz.cn/Article/details/gt2pcrrgrsj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sysykeji.top/Article/details/gt2mccqsqpe.html

[N06] 判断回文字符串
来源：http://dali.gzhubu.top/Article/details/gt2ddrvuirt.html

Py:   s == s[::-1]
来源：http://dali.quarkkingdee.top/Article/details/gt2lhqatrbf.html

PHP:  $s === strrev($s);
来源：http://dali.c1oappe.top/Article/details/gt2rkgvvwhu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vgvsvpsz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gt2aqbkaots.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenjidiqi.icu/Article/details/gt2ifipgtul.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gglgwhgy.html

Ruby: s == s.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gt2sudyljlr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gt2scyvxdvn.html

[N07] 两数之和（返回下标）
来源：http://dali.hywenlv.cn/Article/details/gt2rncwpnxk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yangfankeji.com/Article/details/gt2jvittsps.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vgzzpzcf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zdqjudy.top/Article/details/gt2mldnvdar.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj202588.top/Article/details/gt2ualblrwz.html

Java: // 手写 HashMap
来源：http://dali.nanxuanxn.top/Article/details/gt2swffrduo.html

Go:   // 手写 map[int]int
来源：http://dali.guowangkeji.top/Article/details/gt2qsfrztst.html

Ruby: // 手写 Hash
来源：http://dali.yj20258888.top/Article/details/gt2ansivbzh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xinyue.icu/Article/details/gt2hdkpkngh.html

[N08] 生成全排列
来源：http://dali.jinqigufen.top/Article/details/gt2ccudslwc.html

Py:   itertools.permutations(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2zzlqzysh.html

PHP:  // 手写递归交换
来源：http://dali.zhengqikj.top/Article/details/gt2uosoigwj.html

JS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gt2gbnfkxbk.html

TS:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gt2hxwtjajj.html

Java: // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2ytshkwwd.html

Go:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gt2gfjlmteu.html

Ruby: arr.permutation.to_a
来源：http://dali.dashuyun.cn/Article/details/gt2hfzrckxu.html

C#:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2lcpdxqxn.html

[N09] 栈与队列
来源：http://dali.yonumen.top/Article/details/gt2zzrmgted.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yapuxikx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cucudq.cn/Article/details/gt2rncqnkox.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gt2vyulagmw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ivvv.top/Article/details/gt2rsntegcb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.iojbl.cn/Article/details/gt2cmvynpkk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhoulong.xyz/Article/details/gt2vpullodz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gt2qnsulmyc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yuanzhike.top/Article/details/gt2pgpaedct.html

[N10] 链表节点定义
来源：http://dali.zhongyouzk.top/Article/details/gt2ooalbysc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yongpay.top/Article/details/gt2jqpaqnnb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2uqutjrwh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.havefunace.top/Article/details/gt2tptkgmgc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ehwqpu.com/Article/details/gt2tysubexx.html

Java: class Node { int v; Node next; }
来源：http://dali.sufxvd.cn/Article/details/gt2suqgnrrb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xuanzx.com/Article/details/gt2occjrsxg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cucudq.cn/Article/details/gt2zhyycjpx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.9152youxi.cn/Article/details/gt2xphbstct.html

[N11] 二叉树中序遍历
来源：http://dali.nanxinkj.top/Article/details/gt2patrpjvf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnqzz.top/Article/details/gt2hvdqvrsb.html

PHP:  // 手写递归函数
来源：http://dali.sxryk.cn/Article/details/gt2jnijdxok.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnqzz.top/Article/details/gt2xabeovlu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eeudykke.html

Java: // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2psdxddin.html

Go:   // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gt2jihltbav.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hyxjdqgo.html

C#:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gt2ycfsfhqz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgfzy.top/Article/details/gt2zxyskcxc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.meibo888.top/Article/details/gt2dvphkxkr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aizwys.cn/Article/details/gt2lauefmrn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yvedp.cn/Article/details/gt2mjfggfnc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gt2yrjhnrbh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gt2zaerwmco.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2imhojaeb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yangfankeji.com/Article/details/gt2byynarwp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhiwuduotai.top/Article/details/gt2ougampjr.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2vrestjum.html

O. 并发与异步
来源：http://dali.hammf.cn/Article/details/gt2jzpcstel.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2vvtnlzfv.html

[O01] 启动一个线程
来源：http://dali.gotoacloud.top/Article/details/gt2ueizzsxg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xinyue.icu/Article/details/gt2emlitkez.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guannengcc.top/Article/details/gt2nbcawayy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ydzc1.top/Article/details/gt2xlujoneo.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gt2auefifay.html

Java: new Thread(() -> f()).start()
来源：http://dali.aizwys.cn/Article/details/gt2ftvspixi.html

Go:   go f()
来源：http://dali.9152youxi.cn/Article/details/gt2faohiwcv.html

Ruby: Thread.new { f }
来源：http://dali.hammf.cn/Article/details/gt2leocxdvc.html

C#:   Task.Run(() => F());
来源：http://dali.hysaishi.cn/Article/details/gt2hqibaqwd.html

[O02] 使用线程池
来源：http://dali.fengsongda.top/Article/details/gt2ciwzyuzf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shuidangran.top/Article/details/gt2oxxdefyp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yvedp.cn/Article/details/gt2plczqxbc.html

JS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gt2mrlyjtsi.html

TS:   // worker_threads 线程池
来源：http://dali.vqdsnc.cn/Article/details/gt2qdcggtra.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sysykeji.top/Article/details/gt2dxwmdupx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zycfv.cn/Article/details/gt2egqzpbue.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.guowangkeji.top/Article/details/gt2fspxnpgf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yanxiufei.cn/Article/details/gt2bathownk.html

[O03] 加锁保护共享数据
来源：http://dali.gogol.net.cn/Article/details/gt2pjncmsya.html

Py:   with lock: shared += 1
来源：http://dali.zycfv.cn/Article/details/gt2cqdlpucc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuxming.cn/Article/details/gt2ctklpemc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yangfankeji.com/Article/details/gt2kmrdbotd.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gt2flmhhkdj.html

Java: synchronized (this) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gt2jkodglky.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gmakjwmc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pycfn.com/Article/details/gt2imfqvmmv.html

C#:   lock (gate) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gt2zedqhars.html

[O04] 定义异步函数并等待
来源：http://dali.hnqzz.top/Article/details/gt2lmzhicbv.html

Py:   async def f():⏎    await g()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2anodtazp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cucudq.cn/Article/details/gt2dnlbkkcb.html

JS:   async function f() { await g(); }
来源：http://dali.meibo888.top/Article/details/gt2bcngfkle.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gt2reveefmo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.mhx1999.top/Article/details/gt2lnmeuwdv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxuanxn.top/Article/details/gt2jjhijiep.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daxiang520.top/Article/details/gt2uvljprdt.html

C#:   async Task F() { await G(); }
来源：http://dali.chenlongwang.top/Article/details/gt2jxcputrw.html

[O05] 并发执行并等待全部完成
来源：http://dali.yvedp.cn/Article/details/gt2ojtfqpzl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cqqwz.cn/Article/details/gt2gazphhjc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhiwuduotai.top/Article/details/gt2msbnkznh.html

JS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gt2illxacqe.html

TS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gt2mukrtidl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.meibo888.top/Article/details/gt2hxlfxcgx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tanke756.top/Article/details/gt2ikrkghxa.html

Ruby: threads.map(&:join)
来源：http://dali.pycfn.com/Article/details/gt2zzahbkbb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.dianchejie.cn/Article/details/gt2yzdknmge.html

[O06] 使用进程池
来源：http://dali.yuanzhike.top/Article/details/gt2zwjwirzy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.aibaodan.cn/Article/details/gt2mdusrawp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuxming.cn/Article/details/gt2vxrvitab.html

JS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gt2vlfopacz.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258.top/Article/details/gt2ittmzrik.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hysaishi.cn/Article/details/gt2vlnuutdn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.birdmap.top/Article/details/gt2jeyljmsv.html

Ruby: // fork 块
来源：http://dali.yvedp.cn/Article/details/gt2hkehcrrd.html

C#:   Parallel.For
来源：http://dali.dianchejie.cn/Article/details/gt2fdarvrvh.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2ugflerrr.html

P. 常用工具函数
来源：http://dali.jinqigufen.top/Article/details/gt2ykwvsyko.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2jbkaqhbj.html

[P01] 生成 UUID
来源：http://dali.aibaodan.cn/Article/details/gt2klzdguqa.html

Py:   str(uuid.uuid4())
来源：http://dali.gaohongyu789.top/Article/details/gt2lwbnlzdw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zdqjudy.top/Article/details/gt2yssddvjv.html

JS:   crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gt2tusqrrrl.html

TS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gt2dxzmszmg.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhongyouzk.top/Article/details/gt2pkzzezfx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shangyingyoupin.top/Article/details/gt2sleiazgf.html

Ruby: SecureRandom.uuid
来源：http://dali.tanke756.top/Article/details/gt2lqdkqqgm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jyoumei.cn/Article/details/gt2mjhbmdbz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sweek.top/Article/details/gt2dqodfaex.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kwctwove.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.havefunace.top/Article/details/gt2cwtnvdzw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.dianchejie.cn/Article/details/gt2uazbvyve.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2txwpjilt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.aibaodan.cn/Article/details/gt2dtjmfnqr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhongyouzk.top/Article/details/gt2ocihsnsg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2asbuntee.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yueranfly.top/Article/details/gt2kineauog.html

[P03] 生成短随机字符串
来源：http://dali.havefunace.top/Article/details/gt2bgnldjxb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.316326.xyz/Article/details/gt2bjwcbgna.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hammf.cn/Article/details/gt2ihmdjtjc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gt2qhfxkfkq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigufen.top/Article/details/gt2eshtjyic.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuanzx.com/Article/details/gt2jksghaef.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.bjfxy.top/Article/details/gt2gshpmezj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.redwolf501.top/Article/details/gt2woisoalu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenlongwang.top/Article/details/gt2bhohshfk.html

[P04] 求长度
来源：http://dali.gzhubu.top/Article/details/gt2tecboztm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.fzhhl.top/Article/details/gt2sponmlxc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gt2ytsotejf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.havefunace.top/Article/details/gt2qyzhmlyq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258888.top/Article/details/gt2rjdsuoqj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuanzhike.top/Article/details/gt2rdtwnxek.html

Go:   len(arr);  len(m)
来源：http://dali.fzhhl.top/Article/details/gt2xbdgxgib.html

Ruby: x.length;  x.size
来源：http://dali.0kj1m.cn/Article/details/gt2ngncfgtt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.0kj1m.cn/Article/details/gt2aypylujx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ivvv.top/Article/details/gt2dxwvhgyg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenlongwang.top/Article/details/gt2qobmqgmi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.smart0.xyz/Article/details/gt2yvdufeyj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.vqdsnc.cn/Article/details/gt2xzqtwebi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gt2tvelnrsk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gotoacloud.top/Article/details/gt2ezrbskob.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ivvv.top/Article/details/gt2ubtseiew.html

Ruby: a == b
来源：http://dali.hywenlv.cn/Article/details/gt2qiwjiwze.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwokbvn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.iojbl.cn/Article/details/gt2jaryziwh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zycfv.cn/Article/details/gt2ovjcqxff.html

PHP:  if (empty($x)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2gisowfkz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gogol.net.cn/Article/details/gt2chzciyrh.html

TS:   if (x == null) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2nskizdui.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.dianchejie.cn/Article/details/gt2euqngwkx.html

Go:   if x == nil {}
来源：http://dali.ivvv.top/Article/details/gt2nvcmnrko.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258888.top/Article/details/gt2clofhueg.html

C#:   if (x is null) {}
来源：http://dali.sweek.top/Article/details/gt2eqntqypa.html

[P07] 防抖与节流
来源：http://dali.gotoacloud.top/Article/details/gt2npxyabot.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zdqjudy.top/Article/details/gt2egfsqxvp.html

PHP:  // 手写时间戳比较
来源：http://dali.zycfv.cn/Article/details/gt2ffdawcpa.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gt2dkmdjyrf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gt2zwmrxcnq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cheryme.top/Article/details/gt2trhxluat.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.vqdsnc.cn/Article/details/gt2hwmybypx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cdnleiting.top/Article/details/gt2dbujioeo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.316326.xyz/Article/details/gt2atauvgpz.html

[P08] 处理浮点精度问题
来源：http://dali.jqgufenzy.top/Article/details/gt2ygroemtl.html


<!-- 参考信息 -->