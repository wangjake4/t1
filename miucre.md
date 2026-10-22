代发 wailian999

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2pofhszwr.html

[M01] 读取命令行参数
来源：http://dali.yongpay.top/Article/details/gt2pzyglcoe.html

Py:   sys.argv[1:]
来源：http://dali.yanxiufei.cn/Article/details/gt2adbqflmg.html

PHP:  $argv;  $argc;
来源：http://dali.guowangkeji.top/Article/details/gt2qvdtnesn.html

JS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gt2jlkrzqbt.html

TS:   process.argv.slice(2)
来源：http://dali.xuanzx.com/Article/details/gt2xiopyrze.html

Java: args 数组（main 方法参数）
来源：http://dali.316326.xyz/Article/details/gt2qfxtwbcp.html

Go:   os.Args[1:]
来源：http://dali.snrcjt.cn/Article/details/gt2rxsyfxde.html

Ruby: ARGV
来源：http://dali.9152youxi.cn/Article/details/gt2rkycxbqq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gt2gsljrxru.html

[M02] 读取环境变量
来源：http://dali.sysykeji.top/Article/details/gt2cdbvatse.html

Py:   os.environ.get("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xguuavkb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gt2finfpult.html

JS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gt2eocszkkw.html

TS:   process.env.HOME
来源：http://dali.jiagoushi.top/Article/details/gt2ngumdapt.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gt2htlkcxhe.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2sqeyvuoe.html

Ruby: ENV["HOME"]
来源：http://dali.zhoulong.xyz/Article/details/gt2pwqolmuo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fzgywjhu.html

[M03] 执行外部命令
来源：http://dali.tanke756.top/Article/details/gt2bheduoqj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnxiangtu.top/Article/details/gt2smpepoqn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yvedp.cn/Article/details/gt2tmsftdzc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2fnokvycw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gt2adxxewxj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhiwuduotai.top/Article/details/gt2gpvebvls.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.feifeiyinyue.top/Article/details/gt2xoxuwjad.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenjidiqi.icu/Article/details/gt2kviwllol.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tian-w.cn/Article/details/gt2kvgnivqe.html

[M04] 获取当前工作目录
来源：http://dali.9152youxi.cn/Article/details/gt2pnzxfdfw.html

Py:   os.getcwd()
来源：http://dali.bjfxy.top/Article/details/gt2hevhopiw.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2owmkegue.html

JS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gt2jzshbtcu.html

TS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gt2ukrjfrxp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.mhx1999.top/Article/details/gt2eecdrwhy.html

Go:   os.Getwd()
来源：http://dali.hysaishi.cn/Article/details/gt2ddebpksa.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gt2rxkaudlo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daria6918.cn/Article/details/gt2glbbnobt.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gt2tcjxhbqq.html

Py:   sys.exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2zbdvtfar.html

PHP:  exit(1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2eyuzkxne.html

JS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gt2cdqipyka.html

TS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2iinjqkpn.html

Java: System.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2oazcinas.html

Go:   os.Exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2pmkjvsln.html

Ruby: exit 1
来源：http://dali.xuanzx.com/Article/details/gt2mzejsrhu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgufenzy.top/Article/details/gt2ebifisgo.html

[M06] 向标准错误输出
来源：http://dali.shzxlz.cn/Article/details/gt2itrxckmc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cucudq.cn/Article/details/gt2gazeauow.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pycfn.com/Article/details/gt2czkboejk.html

JS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gt2buqlcrkz.html

TS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gt2kwqjgunn.html

Java: System.err.println("err")
来源：http://dali.snrcjt.cn/Article/details/gt2xbsbqzrg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hysaishi.cn/Article/details/gt2yjemdkyj.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkajeks.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cucudq.cn/Article/details/gt2kgcdnuvj.html

[M07] 判断是否为主入口
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gbomdmdv.html

Py:   if __name__ == "__main__":
来源：http://dali.yuanzhike.top/Article/details/gt2upyhbbhk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zycfv.cn/Article/details/gt2lyfsjgav.html

JS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gt2egxlhsfr.html

TS:   require.main === module
来源：http://dali.yonumen.top/Article/details/gt2cmnynhcf.html

Java: public static void main(String[] args)
来源：http://dali.hfpthk.cn/Article/details/gt2mqhqccjf.html

Go:   func main()
来源：http://dali.ivvv.top/Article/details/gt2vfffkvwd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hammf.cn/Article/details/gt2upevpmar.html

C#:   static void Main(string[] args)
来源：http://dali.vqdsnc.cn/Article/details/gt2yhstvijc.html

[M08] 获取系统与运行时信息
来源：http://dali.yj202588.top/Article/details/gt2ydwhrtkh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shangyingyoupin.top/Article/details/gt2bcgtktoo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daxiang520.top/Article/details/gt2yaqcmdlc.html

JS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gt2ybtzswcw.html

TS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gt2lgjitmps.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.daxiang520.top/Article/details/gt2sgjdoicc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.andypj.xyz/Article/details/gt2sgrqdybv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhoulong.xyz/Article/details/gt2hsmcgtta.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fzhhl.top/Article/details/gt2ngicsvwp.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2yrezuhjb.html

N. 数据结构与算法
来源：http://dali.sxryk.cn/Article/details/gt2gywccpbg.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vwqbvycp.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigufen.top/Article/details/gt2ltmtqzuo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2yraheypi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.9152youxi.cn/Article/details/gt2ebbrjdbz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gt2ubwvhwho.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.c1oappe.top/Article/details/gt2rcfwmmjy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2kqrlrjoc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2stdfuths.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhixingplan.top/Article/details/gt2nsfdrqbf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hxmgqwfs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tanke756.top/Article/details/gt2quktfwdq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gt2qhjvbdna.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yongpay.top/Article/details/gt2cozvrtln.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gt2ygojayps.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gt2hxvgqbuz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ehwqpu.com/Article/details/gt2ylvalswr.html

Go:   slices.Sort(arr)
来源：http://dali.yuxming.cn/Article/details/gt2gxcpzjww.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gt2mttfgrvc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ybcxt.top/Article/details/gt2kojjbmtu.html

[N03] 快速排序（分治示例）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xzcwshdm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tanke756.top/Article/details/gt2iznkdyjr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.mhx1999.top/Article/details/gt2tfiexwjw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gt2hmhrojzi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sufxvd.cn/Article/details/gt2jirmrklu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yonumen.top/Article/details/gt2gbahomzj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gaohongyu789.top/Article/details/gt2vxnyyinh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigufen.top/Article/details/gt2gtexdgzo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj202588.top/Article/details/gt2dwdbcrif.html

[N04] 斐波那契数列
来源：http://dali.jqgfzy.top/Article/details/gt2zjkcyxvk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gt2elmwxyor.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gt2tsfcrgbl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gt2kzytgilu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gt2smonwuqb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gzhubu.top/Article/details/gt2jereyzxv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dashuyun.cn/Article/details/gt2txgrlhnp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gt2xbnkuwrt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gt2eznzocqy.html

[N05] 最大公约数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ctriqmpo.html

Py:   math.gcd(a, b)
来源：http://dali.guannengcc.top/Article/details/gt2xnbdblhw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hfpthk.cn/Article/details/gt2uykhsscb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gt2eanyigma.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gt2pzhequkt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.bjfxy.top/Article/details/gt2daajkefm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhoulong.xyz/Article/details/gt2crxrjddr.html

Ruby: a.gcd(b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2drwtuzjs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sysykeji.top/Article/details/gt2clrenlzw.html

[N06] 判断回文字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vojejmsb.html

Py:   s == s[::-1]
来源：http://dali.nwbrower.top/Article/details/gt2darfrbmi.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2crrfdjaw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gt2xpdecvfo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gt2uddhxzrf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aizwys.cn/Article/details/gt2icfrgjgq.html

Go:   // 双指针从两端比较
来源：http://dali.jianghu66.top/Article/details/gt2shwpvdyv.html

Ruby: s == s.reverse
来源：http://dali.jqgfzy.top/Article/details/gt2jciextkc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gt2mxocsosx.html

[N07] 两数之和（返回下标）
来源：http://dali.shzxlz.cn/Article/details/gt2tccawzgg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ydzc1.top/Article/details/gt2ylbjbiku.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj202588.top/Article/details/gt2wurwifne.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.redwolf501.top/Article/details/gt2agehqvvx.html

TS:   // 手写 Map<string, number>
来源：http://dali.fengsongda.top/Article/details/gt2kbccwlpg.html

Java: // 手写 HashMap
来源：http://dali.yueranfly.top/Article/details/gt2lzeslesa.html

Go:   // 手写 map[int]int
来源：http://dali.smart0.xyz/Article/details/gt2grajhxuz.html

Ruby: // 手写 Hash
来源：http://dali.yj202588.top/Article/details/gt2pncuuvfs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cqqwz.cn/Article/details/gt2xunwtqzb.html

[N08] 生成全排列
来源：http://dali.yj202588.top/Article/details/gt2pejiszyh.html

Py:   itertools.permutations(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ihtqwkek.html

PHP:  // 手写递归交换
来源：http://dali.yonumen.top/Article/details/gt2vjbikrxh.html

JS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gt2gqweempe.html

TS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2pkfsvvnd.html

Java: // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2ssqfnhbf.html

Go:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2tpfcmolv.html

Ruby: arr.permutation.to_a
来源：http://dali.zhengqikj.top/Article/details/gt2ybxiepfr.html

C#:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2puqwznsm.html

[N09] 栈与队列
来源：http://dali.yuanzhike.top/Article/details/gt2qbttydwg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.dianchejie.cn/Article/details/gt2dptsprvr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.iojbl.cn/Article/details/gt2ipcohhpy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gt2sqtyvfwb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xylfe.cn/Article/details/gt2axkemqat.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.c1oappe.top/Article/details/gt2ofjpxxwn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yongpay.top/Article/details/gt2gjlufhwi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gt2hrycymdd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenlongwang.top/Article/details/gt2xijlxtbh.html

[N10] 链表节点定义
来源：http://dali.9152youxi.cn/Article/details/gt2hxolawoj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenjidiqi.icu/Article/details/gt2jmaciymf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2yoxkpkjr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gaohongyu789.top/Article/details/gt2wlhfogpe.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhongyouzk.top/Article/details/gt2gtnzrafz.html

Java: class Node { int v; Node next; }
来源：http://dali.dashuyun.cn/Article/details/gt2aognloym.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pycfn.com/Article/details/gt2natqqiyh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guannengcc.top/Article/details/gt2ayhqsfek.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhongyouzk.top/Article/details/gt2nhgwswyi.html

[N11] 二叉树中序遍历
来源：http://dali.cashguo.top/Article/details/gt2gezuuype.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hrnwwqkx.html

PHP:  // 手写递归函数
来源：http://dali.hammf.cn/Article/details/gt2xmfwkahl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yangfankeji.com/Article/details/gt2qrhyhgyd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenjidiqi.icu/Article/details/gt2ciojvpmr.html

Java: // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gt2fmaqaspj.html

Go:   // 手写递归
来源：http://dali.yongpay.top/Article/details/gt2cvegtoxu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gzhubu.top/Article/details/gt2abbahzqf.html

C#:   // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gt2rxcncipd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhixingplan.top/Article/details/gt2ogvbonjo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daxiang520.top/Article/details/gt2cxqvloet.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.9152youxi.cn/Article/details/gt2haxzpdfp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gt2fikirgpf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mpstprcr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gt2auhantbn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hfpthk.cn/Article/details/gt2hjessqcm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dashuyun.cn/Article/details/gt2klrzlugb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jyoumei.cn/Article/details/gt2pxwbnswn.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2rlhjxddz.html

O. 并发与异步
来源：http://dali.yangfankeji.com/Article/details/gt2ycmdwxfr.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2fvbojtqx.html

[O01] 启动一个线程
来源：http://dali.andypj.xyz/Article/details/gt2garhnkrs.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daria6918.cn/Article/details/gt2ygfegtpw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.pycfn.com/Article/details/gt2edznawpk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sysykeji.top/Article/details/gt2blcqqxqh.html

TS:   // 同 JS
来源：http://dali.sxryk.cn/Article/details/gt2udxjxuqr.html

Java: new Thread(() -> f()).start()
来源：http://dali.smart0.xyz/Article/details/gt2neitrdtc.html

Go:   go f()
来源：http://dali.nanxuanxn.top/Article/details/gt2vpvakzzi.html

Ruby: Thread.new { f }
来源：http://dali.cashguo.top/Article/details/gt2ppsvjtqg.html

C#:   Task.Run(() => F());
来源：http://dali.sysykeji.top/Article/details/gt2eygakhwl.html

[O02] 使用线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yysbstba.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.dashuyun.cn/Article/details/gt2fwdskngm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.snrcjt.cn/Article/details/gt2xnbxigof.html

JS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gt2nknrwtke.html

TS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gt2amhfnttk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.haohaochexian.top/Article/details/gt2dexfgsur.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnxiangtu.top/Article/details/gt2wfvoolni.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cdnleiting.top/Article/details/gt2kuhibmpd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yongpay.top/Article/details/gt2hycrrjao.html

[O03] 加锁保护共享数据
来源：http://dali.shzxlz.cn/Article/details/gt2kioflevc.html

Py:   with lock: shared += 1
来源：http://dali.sxryk.cn/Article/details/gt2cfvetite.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuanzhike.top/Article/details/gt2xommawza.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hammf.cn/Article/details/gt2xwbgacmm.html

TS:   // 同 JS
来源：http://dali.316326.xyz/Article/details/gt2qeutihgy.html

Java: synchronized (this) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gt2jwqvksae.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dashuyun.cn/Article/details/gt2yysqvuxb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gotoacloud.top/Article/details/gt2lsrnszly.html

C#:   lock (gate) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gt2hjjoncyt.html

[O04] 定义异步函数并等待
来源：http://dali.pengpengdd.cyou/Article/details/gt2adkzqgvk.html

Py:   async def f():⏎    await g()
来源：http://dali.xuetiantiany.cn/Article/details/gt2apjongdt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgufenzy.top/Article/details/gt2jvtmyohg.html

JS:   async function f() { await g(); }
来源：http://dali.sysykeji.top/Article/details/gt2zsocneof.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jianghu66.top/Article/details/gt2erdrjwsl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sxryk.cn/Article/details/gt2ckwdqljx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.c1oappe.top/Article/details/gt2aqsbwnvn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fengsongda.top/Article/details/gt2vhweakdz.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgfzy.top/Article/details/gt2xlgxfuic.html

[O05] 并发执行并等待全部完成
来源：http://dali.yanxiufei.cn/Article/details/gt2yshbqvah.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gugdmqgg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.wangshuangyany.cn/Article/details/gt2bvmgwsnp.html

JS:   await Promise.all(tasks)
来源：http://dali.xylfe.cn/Article/details/gt2bsjztamp.html

TS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gt2aorzqdyw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hongshengwenyu.top/Article/details/gt2nitlxvib.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvhrgdj.html

Ruby: threads.map(&:join)
来源：http://dali.jyoumei.cn/Article/details/gt2fozexwae.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yongpay.top/Article/details/gt2asnhfdks.html

[O06] 使用进程池
来源：http://dali.chenzaomai.com/Article/details/gt2bnanhxdz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cucudq.cn/Article/details/gt2xocpbiww.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.c1oappe.top/Article/details/gt2ubxsgrdu.html

JS:   // child_process / cluster 模块
来源：http://dali.xuanzx.com/Article/details/gt2cumjcbzn.html

TS:   // child_process / cluster 模块
来源：http://dali.hongshengwenyu.top/Article/details/gt2cmwufbou.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.guowangkeji.top/Article/details/gt2laivarui.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2veoiaeun.html

Ruby: // fork 块
来源：http://dali.chenlongwang.top/Article/details/gt2oqapfvuq.html

C#:   Parallel.For
来源：http://dali.jyoumei.cn/Article/details/gt2peuttdgv.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2kpbjpjqc.html

P. 常用工具函数
来源：http://dali.fengsongda.top/Article/details/gt2nekenerr.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2yumfpucp.html

[P01] 生成 UUID
来源：http://dali.meibo888.top/Article/details/gt2hpxviyrp.html

Py:   str(uuid.uuid4())
来源：http://dali.dashuyun.cn/Article/details/gt2qalhdpsq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zdqjudy.top/Article/details/gt2jvamurpy.html

JS:   crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gt2pgibvqnm.html

TS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gt2fczeopnn.html

Java: UUID.randomUUID().toString()
来源：http://dali.birdmap.top/Article/details/gt2vsnrabwj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gt2pbgczkom.html

Ruby: SecureRandom.uuid
来源：http://dali.zycfv.cn/Article/details/gt2fvasrerc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.snrcjt.cn/Article/details/gt2gggenpxz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rvpstcwq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.c1oappe.top/Article/details/gt2uehvdmud.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.snrcjt.cn/Article/details/gt2rjeizfmf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ppjwa.cn/Article/details/gt2suowbtzs.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ybcxt.top/Article/details/gt2xdoawfkb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yvedp.cn/Article/details/gt2fpaqhjwe.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yangfankeji.com/Article/details/gt2nffhuoig.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tanke756.top/Article/details/gt2mstmfmai.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.snrcjt.cn/Article/details/gt2wuxeaynd.html

[P03] 生成短随机字符串
来源：http://dali.jqgfzy.top/Article/details/gt2njwausov.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangshuangyany.cn/Article/details/gt2pwmdwaub.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj20258.top/Article/details/gt2yxopxmbi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.mhx1999.top/Article/details/gt2mimutgwn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.iojbl.cn/Article/details/gt2swyoasdm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jqgfzy.top/Article/details/gt2gjzdfxnh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dashuyun.cn/Article/details/gt2ycbkqdcb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangdashe.top/Article/details/gt2hxyhkrxb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fengsongda.top/Article/details/gt2yentlotz.html

[P04] 求长度
来源：http://dali.cheryme.top/Article/details/gt2djphpjga.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.iojbl.cn/Article/details/gt2wdtbeieu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gt2mnwgpuge.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gt2ermtyhyc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yvedp.cn/Article/details/gt2fsemliyb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dianchejie.cn/Article/details/gt2tkktckan.html

Go:   len(arr);  len(m)
来源：http://dali.yonumen.top/Article/details/gt2mfijrsmn.html

Ruby: x.length;  x.size
来源：http://dali.redwolf501.top/Article/details/gt2qvusexft.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cdnleiting.top/Article/details/gt2unyciyjn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ydzc1.top/Article/details/gt2oqvwttjx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jqgfzy.top/Article/details/gt2kjqrrihr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ybcxt.top/Article/details/gt2iztgnvpy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jlsjyb.cn/Article/details/gt2rbikodqb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gaohongyu789.top/Article/details/gt2jkgwrcxy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cucudq.cn/Article/details/gt2srshmqqe.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pvvlclxs.html

Ruby: a == b
来源：http://dali.yueranfly.top/Article/details/gt2kmivrzch.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigufen.top/Article/details/gt2kaorjjvo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xinyue.icu/Article/details/gt2qakwnypv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dcvnyidx.html

PHP:  if (empty($x)) {}
来源：http://dali.smart0.xyz/Article/details/gt2gjoqsuoo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gotoacloud.top/Article/details/gt2idffjkot.html

TS:   if (x == null) {}
来源：http://dali.sxryk.cn/Article/details/gt2gxneryom.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2tztmwhjf.html

Go:   if x == nil {}
来源：http://dali.nwbrower.top/Article/details/gt2fbjopptq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aibaodan.cn/Article/details/gt2mdpxbcww.html

C#:   if (x is null) {}
来源：http://dali.guowangkeji.top/Article/details/gt2wszjrnff.html

[P07] 防抖与节流
来源：http://dali.xuetiantiany.cn/Article/details/gt2uppkiapz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.0kj1m.cn/Article/details/gt2gtqkjdco.html


<!-- 参考信息 -->