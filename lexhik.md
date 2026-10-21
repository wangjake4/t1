代发 wailian999

================================================================================
来源：http://dali.birdmap.top/Article/details/gtbqjxyzjd.html

[M01] 读取命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gtlptsfpwp.html

Py:   sys.argv[1:]
来源：http://dali.sufxvd.cn/Article/details/gtafvbzevj.html

PHP:  $argv;  $argc;
来源：http://dali.hammf.cn/Article/details/gtdnuwgglc.html

JS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gtrfsijfhx.html

TS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gtxhbquepj.html

Java: args 数组（main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gtrkjwzeng.html

Go:   os.Args[1:]
来源：http://dali.iojbl.cn/Article/details/gtewigxvjx.html

Ruby: ARGV
来源：http://dali.snrcjt.cn/Article/details/gtkfhgyphh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gtovhienns.html

[M02] 读取环境变量
来源：http://dali.hywenlv.cn/Article/details/gtecgaygai.html

Py:   os.environ.get("HOME")
来源：http://dali.sysykeji.top/Article/details/gtykvazsrh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gtihikedpj.html

JS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gtshszrdhe.html

TS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtvxggrhew.html

Java: System.getenv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtsyyfyljv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtaqkoaaep.html

Ruby: ENV["HOME"]
来源：http://dali.yj202588.top/Article/details/gtpgzkwswt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xylfe.cn/Article/details/gtfpuezyrx.html

[M03] 执行外部命令
来源：http://dali.quarkkingdee.top/Article/details/gtsnuksldr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shuidangran.top/Article/details/gtieppzrqt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinqigufen.top/Article/details/gtzmtusdov.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gtunwscpxl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gtdzxzixba.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yueranfly.top/Article/details/gtxhbfswiw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.iojbl.cn/Article/details/gtsppsaqvo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.redwolf501.top/Article/details/gtezfrkxzu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxuanxn.top/Article/details/gtkdeigypb.html

[M04] 获取当前工作目录
来源：http://dali.cashguo.top/Article/details/gthpamtwtu.html

Py:   os.getcwd()
来源：http://dali.cashguo.top/Article/details/gtunihetzy.html

PHP:  getcwd();
来源：http://dali.ppjwa.cn/Article/details/gttuvwbqvc.html

JS:   process.cwd()
来源：http://dali.kuanghao11.cn/Article/details/gtoqudwxqp.html

TS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gtnwpuvimu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.9152youxi.cn/Article/details/gtsnfzoprd.html

Go:   os.Getwd()
来源：http://dali.dianchejie.cn/Article/details/gtpttpzntv.html

Ruby: Dir.pwd
来源：http://dali.hywenlv.cn/Article/details/gtgtmardrm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cucudq.cn/Article/details/gtgcfynezq.html

[M05] 设置退出码
来源：http://dali.yj20258.top/Article/details/gtwgdqfykb.html

Py:   sys.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtnsnkxmvx.html

PHP:  exit(1);
来源：http://dali.zycfv.cn/Article/details/gtsrgvsdvt.html

JS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtcirdstuz.html

TS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtfmnrhtco.html

Java: System.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtzclkwoad.html

Go:   os.Exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtljtvikhv.html

Ruby: exit 1
来源：http://dali.yanxiufei.cn/Article/details/gtflgsfsas.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.kuanghao11.cn/Article/details/gtulurpaxc.html

[M06] 向标准错误输出
来源：http://dali.gogol.net.cn/Article/details/gtyevnttoj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gzhubu.top/Article/details/gtznitjyde.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cashguo.top/Article/details/gtwncqsrls.html

JS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gtqzljpvin.html

TS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gtiwbqcvyo.html

Java: System.err.println("err")
来源：http://dali.aibaodan.cn/Article/details/gtypkwuutq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ehwqpu.com/Article/details/gtcaykswwd.html

Ruby: warn "err"
来源：http://dali.ivvv.top/Article/details/gtcqqpldav.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtlhzizwgd.html

[M07] 判断是否为主入口
来源：http://dali.sweek.top/Article/details/gtvwysnnpz.html

Py:   if __name__ == "__main__":
来源：http://dali.haohaochexian.top/Article/details/gtxazwvmpf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.mhx1999.top/Article/details/gttgylefaz.html

JS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gtjltlyuee.html

TS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gtknimabls.html

Java: public static void main(String[] args)
来源：http://dali.jlsjyb.cn/Article/details/gtanwvjwmd.html

Go:   func main()
来源：http://dali.zhiwuduotai.top/Article/details/gtbyptlwbv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinqigufen.top/Article/details/gtwazuzeny.html

C#:   static void Main(string[] args)
来源：http://dali.nanxinkj.top/Article/details/gtcvmvqexe.html

[M08] 获取系统与运行时信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwyfqkcs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmysbjum.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.smart0.xyz/Article/details/gtfjmercme.html

JS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gtjuoaxoyy.html

TS:   process.platform;  process.version
来源：http://dali.hongshengwenyu.top/Article/details/gtrncpgige.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gtyhkyxthq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuanzx.com/Article/details/gtfskumdxw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpdtwdeg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.iojbl.cn/Article/details/gtlrmippzd.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtttarjzoc.html

N. 数据结构与算法
来源：http://dali.nanxuanxn.top/Article/details/gtqbgfyawo.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtimlktgae.html

[N01] 二分查找（有序数组）
来源：http://dali.gzhubu.top/Article/details/gtnumobypv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtlthgebyx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cucudq.cn/Article/details/gtibbymqiw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatviqekb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gtouqelzeu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gteewbttoe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtcnvckrsi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.meibo888.top/Article/details/gteanzpqyw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gtergqnncd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.guowangkeji.top/Article/details/gtcelwkycb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtinjazaww.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtudspmbbn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gtifapyxig.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gtfddxntgv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cucudq.cn/Article/details/gtlihkxkbl.html

Go:   slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtepntpcgc.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gthiexqdyb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.andypj.xyz/Article/details/gtgvmnplsd.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbkrmadp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gtzsvqucif.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxinkj.top/Article/details/gtsxvuqfmv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.birdmap.top/Article/details/gtbnjzmeio.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gttgksdahz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sufxvd.cn/Article/details/gtxukwkdcz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gotoacloud.top/Article/details/gtlimkltcr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigufen.top/Article/details/gtzkwgqafx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.iojbl.cn/Article/details/gteblotmyd.html

[N04] 斐波那契数列
来源：http://dali.bjfxy.top/Article/details/gtguxsduux.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gtpwailpvw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gthzmvedqh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtqppondma.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtypzbmowi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuanzx.com/Article/details/gtqrxjgbph.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.andypj.xyz/Article/details/gtdewoxhvv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hnxiangtu.top/Article/details/gtrynbhyak.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gttdfabkua.html

[N05] 最大公约数
来源：http://dali.cqqwz.cn/Article/details/gtmkbjdwqk.html

Py:   math.gcd(a, b)
来源：http://dali.shuidangran.top/Article/details/gtefjsqoyu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guannengcc.top/Article/details/gthotbntxb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gogol.net.cn/Article/details/gtzndsdsua.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gtpogeoort.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cashguo.top/Article/details/gtjojrqtrm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gogol.net.cn/Article/details/gtzlwzzgzj.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gtjzyzdwjt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fzhhl.top/Article/details/gtrqdfecwp.html

[N06] 判断回文字符串
来源：http://dali.hywenlv.cn/Article/details/gtatfkhyot.html

Py:   s == s[::-1]
来源：http://dali.yvedp.cn/Article/details/gtseuorevw.html

PHP:  $s === strrev($s);
来源：http://dali.xinyue.icu/Article/details/gtzrqtestr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtqbupjrkt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtxrmhsfke.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hongshengwenyu.top/Article/details/gtfludpfvj.html

Go:   // 双指针从两端比较
来源：http://dali.cheryme.top/Article/details/gtmzeiscle.html

Ruby: s == s.reverse
来源：http://dali.haohaochexian.top/Article/details/gtfppvusqf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gtkxwpzszw.html

[N07] 两数之和（返回下标）
来源：http://dali.xinyue.icu/Article/details/gtnmktjtcb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cucudq.cn/Article/details/gtdikohrcz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.316326.xyz/Article/details/gtwenrxjyt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsxhlpwi.html

TS:   // 手写 Map<string, number>
来源：http://dali.jiagoushi.top/Article/details/gtqjbtibtb.html

Java: // 手写 HashMap
来源：http://dali.havefunace.top/Article/details/gtffwrbamu.html

Go:   // 手写 map[int]int
来源：http://dali.gogol.net.cn/Article/details/gtigyeztco.html

Ruby: // 手写 Hash
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrcshqef.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.0kj1m.cn/Article/details/gtdzauytza.html

[N08] 生成全排列
来源：http://dali.xuanzx.com/Article/details/gtyaxaivln.html

Py:   itertools.permutations(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtpclsctmi.html

PHP:  // 手写递归交换
来源：http://dali.fengsongda.top/Article/details/gtaifvtqzn.html

JS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtiqiczkel.html

TS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtdtbituxz.html

Java: // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtpherhzic.html

Go:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtxfafrgfn.html

Ruby: arr.permutation.to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezbndvyx.html

C#:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtfabszdck.html

[N09] 栈与队列
来源：http://dali.xylfe.cn/Article/details/gtoapndlzh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jiagoushi.top/Article/details/gtxnuweieh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gtalebfkis.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.c1oappe.top/Article/details/gtgggsywyg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.havefunace.top/Article/details/gtncyvmmla.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.bjfxy.top/Article/details/gtmmgxzhtc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.haohaochexian.top/Article/details/gtodvrlezo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtunfygwvu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuanzx.com/Article/details/gtvixqgeqe.html

[N10] 链表节点定义
来源：http://dali.hfpthk.cn/Article/details/gtatrjinwa.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ydzc1.top/Article/details/gtjlzahokz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvbktzmuv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daxiang520.top/Article/details/gtenxdgikn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxinkj.top/Article/details/gtnvlnmped.html

Java: class Node { int v; Node next; }
来源：http://dali.fzhhl.top/Article/details/gtpczvxzpl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258.top/Article/details/gthooagknv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.mhx1999.top/Article/details/gteegmklyb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pycfn.com/Article/details/gtyalextbp.html

[N11] 二叉树中序遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxldmzvga.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pengpengdd.cyou/Article/details/gtbvecduea.html

PHP:  // 手写递归函数
来源：http://dali.ybcxt.top/Article/details/gtqkdjrbip.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gthoyqavgb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gtdmmvfzjq.html

Java: // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhexnotf.html

Go:   // 手写递归
来源：http://dali.redwolf501.top/Article/details/gtshjqbiwz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuanzx.com/Article/details/gtouvksuyk.html

C#:   // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gtjtstzxxf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yongpay.top/Article/details/gtmsgbuxzs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenlongwang.top/Article/details/gtjxysgolt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xziqi.cn/Article/details/gtoqkifqgp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gtobnuahcb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gtdqftqfzp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gtxdpmqudt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.haohaochexian.top/Article/details/gtxyztxcaf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gtjwctaetn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuanzx.com/Article/details/gtmyxvsyre.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtmijcvrna.html

O. 并发与异步
来源：http://dali.jianghu66.top/Article/details/gtvzubktql.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqkudtmo.html

[O01] 启动一个线程
来源：http://dali.dianchejie.cn/Article/details/gtzwoshjkw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cqqwz.cn/Article/details/gtyhrexbne.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tianlin.xyz/Article/details/gtrevbiutf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hywenlv.cn/Article/details/gtfhwymasa.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gtnnhjtyjc.html

Java: new Thread(() -> f()).start()
来源：http://dali.ybcxt.top/Article/details/gtsmbdcikm.html

Go:   go f()
来源：http://dali.vqdsnc.cn/Article/details/gtvvyuztym.html

Ruby: Thread.new { f }
来源：http://dali.yonumen.top/Article/details/gtrkvordzh.html

C#:   Task.Run(() => F());
来源：http://dali.ppjwa.cn/Article/details/gtjaijvgnt.html

[O02] 使用线程池
来源：http://dali.tian-w.cn/Article/details/gtswebjdcs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.havefunace.top/Article/details/gtsypqpfml.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangdashe.top/Article/details/gtxmegoujj.html

JS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gttkyynxrt.html

TS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gtuuurkaaq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tianlin.xyz/Article/details/gtasjybldg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.meibo888.top/Article/details/gtrfwonkbm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fengsongda.top/Article/details/gtxzkkxcmn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.andypj.xyz/Article/details/gtufvpepxs.html

[O03] 加锁保护共享数据
来源：http://dali.andypj.xyz/Article/details/gtyzgojefh.html

Py:   with lock: shared += 1
来源：http://dali.cdnleiting.top/Article/details/gtxzpzrfhv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ppjwa.cn/Article/details/gtqrflrjli.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhftgjly.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocnydesc.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgufenzy.top/Article/details/gtkdvvmvrj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sweek.top/Article/details/gtpqtnhbwa.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gtgdhuydis.html

C#:   lock (gate) { shared++; }
来源：http://dali.fzhhl.top/Article/details/gtcbfcbgeg.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigufen.top/Article/details/gtkwswlklm.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gttdivxrqv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dianchejie.cn/Article/details/gtuljmwdke.html

JS:   async function f() { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gtumtawnze.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gtxknupnmw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhixingplan.top/Article/details/gttlcyeioo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xinyue.icu/Article/details/gtmvugspjr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhengqikj.top/Article/details/gtgrltzyeo.html

C#:   async Task F() { await G(); }
来源：http://dali.yj202588.top/Article/details/gthnfsfjup.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwiqbllh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtlvvkktyt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.andypj.xyz/Article/details/gtyvgelzgr.html

JS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gtrqvvrkrs.html

TS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtpwrbinkj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.aibaodan.cn/Article/details/gtakudyzth.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hfpthk.cn/Article/details/gtckbjcjtz.html

Ruby: threads.map(&:join)
来源：http://dali.yuxming.cn/Article/details/gthpwzfzde.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zdqjudy.top/Article/details/gtjvjrwhso.html

[O06] 使用进程池
来源：http://dali.svipenyu.cn/Article/details/gtqdsjjzzc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sxryk.cn/Article/details/gtnqkzrwol.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.0kj1m.cn/Article/details/gtgytlifww.html

JS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gttperrrhm.html

TS:   // child_process / cluster 模块
来源：http://dali.shzxlz.cn/Article/details/gtohfiphyy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yueranfly.top/Article/details/gtzdhtwhov.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.fzhhl.top/Article/details/gtnhssfoxg.html

Ruby: // fork 块
来源：http://dali.jinqigufen.top/Article/details/gtymngoahj.html

C#:   Parallel.For
来源：http://dali.zdqjudy.top/Article/details/gtbynywqjz.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtezmalkcj.html

P. 常用工具函数
来源：http://dali.xuanzx.com/Article/details/gtstkznsbt.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtcygezzqu.html

[P01] 生成 UUID
来源：http://dali.xziqi.cn/Article/details/gtimzipszi.html

Py:   str(uuid.uuid4())
来源：http://dali.gaohongyu789.top/Article/details/gtpnpsmojx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shzxlz.cn/Article/details/gtpjipbqus.html

JS:   crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gtxigimicw.html

TS:   crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gtxqhdypnz.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnxiangtu.top/Article/details/gtshldzrle.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgufenzy.top/Article/details/gtuuubbrov.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgfzy.top/Article/details/gthqbqchot.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.daxiang520.top/Article/details/gtbczdkipk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ybcxt.top/Article/details/gtzeegteny.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yangfankeji.com/Article/details/gtcuakfkwm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jqgfzy.top/Article/details/gtduclqffs.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gaohongyu789.top/Article/details/gtxtpoztpz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.andypj.xyz/Article/details/gtdstjtbas.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtyzhoypie.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hywenlv.cn/Article/details/gtruexbvni.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenlongwang.top/Article/details/gtefegzhao.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cqqwz.cn/Article/details/gtujcbffml.html

[P03] 生成短随机字符串
来源：http://dali.cucudq.cn/Article/details/gtbcklgrfu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxinkj.top/Article/details/gtwhhcpxkm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgfzy.top/Article/details/gtiykhfnlv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tianlin.xyz/Article/details/gtultbmees.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gtcdzadzew.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gzhubu.top/Article/details/gteoajoqcp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sufxvd.cn/Article/details/gtokszhxjo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gogol.net.cn/Article/details/gttuuczpyg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.0kj1m.cn/Article/details/gtdjsbibny.html

[P04] 求长度
来源：http://dali.havefunace.top/Article/details/gtcauukqge.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenjidiqi.icu/Article/details/gtrscwdsva.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbiimhax.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gtmgwszcxm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgufenzy.top/Article/details/gtoldefsoy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hywenlv.cn/Article/details/gtpisglddk.html

Go:   len(arr);  len(m)
来源：http://dali.xinyue.icu/Article/details/gtobadrioq.html

Ruby: x.length;  x.size
来源：http://dali.daria6918.cn/Article/details/gtignotrwu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xylfe.cn/Article/details/gtolnbedxl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jianghu66.top/Article/details/gtfcsuhqgz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhiwuduotai.top/Article/details/gtzhmctoah.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenlongwang.top/Article/details/gtdkjmbzqm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhoulong.xyz/Article/details/gtamjtdlza.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.316326.xyz/Article/details/gtqrnkkslv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.daxiang520.top/Article/details/gtueikvrhc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.fengsongda.top/Article/details/gtucxohjfb.html

Ruby: a == b
来源：http://dali.ehwqpu.com/Article/details/gtkbplryih.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.feifeiyinyue.top/Article/details/gtqithqxxj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.bjfxy.top/Article/details/gtizjcbpie.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cheryme.top/Article/details/gtnrdnfbzr.html

PHP:  if (empty($x)) {}
来源：http://dali.birdmap.top/Article/details/gtpktskcuu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhengqikj.top/Article/details/gtnkuemrci.html

TS:   if (x == null) {}
来源：http://dali.nanxinkj.top/Article/details/gtoyigovru.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gtwjeaarjq.html

Go:   if x == nil {}
来源：http://dali.meibo888.top/Article/details/gtrmegsjlj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hysaishi.cn/Article/details/gtqfoapunp.html

C#:   if (x is null) {}
来源：http://dali.guowangkeji.top/Article/details/gtvbbahcjl.html

[P07] 防抖与节流
来源：http://dali.ivvv.top/Article/details/gtzawuwdxe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.316326.xyz/Article/details/gttiuptcje.html


<!-- 参考信息 -->