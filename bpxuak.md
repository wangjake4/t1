代发 wailian999

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yongpay.top/Article/details/gtmxjfqjki.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xinyue.icu/Article/details/gtvfbdjjfv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtmqovlqmk.html

M. 命令行 / 进程 / 环境
来源：http://dali.guannengcc.top/Article/details/gtyecwfner.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtkpfyzgrj.html

[M01] 读取命令行参数
来源：http://dali.aizwys.cn/Article/details/gtudjfojup.html

Py:   sys.argv[1:]
来源：http://dali.dianchejie.cn/Article/details/gtudtqquma.html

PHP:  $argv;  $argc;
来源：http://dali.ybcxt.top/Article/details/gtuaryzdde.html

JS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtnhknjzxj.html

TS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodpwgajy.html

Java: args 数组（main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gtvycuqbiv.html

Go:   os.Args[1:]
来源：http://dali.jqgfzy.top/Article/details/gtdeniiltb.html

Ruby: ARGV
来源：http://dali.shangyingyoupin.top/Article/details/gtpchxtswc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gttdwbkrac.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gteskpordu.html

Py:   os.environ.get("HOME")
来源：http://dali.aizwys.cn/Article/details/gtebhetsgg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gtuqplebri.html

JS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gtqtajsnnu.html

TS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gtlgqjnkbn.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtuhgwrmra.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtrzegwmmm.html

Ruby: ENV["HOME"]
来源：http://dali.shangyingyoupin.top/Article/details/gtfjkyyzpl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangdashe.top/Article/details/gtdtdsuast.html

[M03] 执行外部命令
来源：http://dali.cashguo.top/Article/details/gtiqlbceih.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxuanxn.top/Article/details/gtbawvwglh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuetiantiany.cn/Article/details/gtqamooist.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpyfyappp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gtoaipkekq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.iojbl.cn/Article/details/gtobyoaagq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixirtqrj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sysykeji.top/Article/details/gtbenwzncw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tianlin.xyz/Article/details/gttmaggnkw.html

[M04] 获取当前工作目录
来源：http://dali.cqqwz.cn/Article/details/gtrdplyrlb.html

Py:   os.getcwd()
来源：http://dali.ppjwa.cn/Article/details/gtcgxhsadg.html

PHP:  getcwd();
来源：http://dali.9152youxi.cn/Article/details/gtvwvgiqox.html

JS:   process.cwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtevkkornz.html

TS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gtkdweczxv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cheryme.top/Article/details/gtazpglgbt.html

Go:   os.Getwd()
来源：http://dali.yj202588.top/Article/details/gtldtyqrqr.html

Ruby: Dir.pwd
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmbqstpo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cucudq.cn/Article/details/gtmlzayyij.html

[M05] 设置退出码
来源：http://dali.jinqigfzy.top/Article/details/gtzxwygfhl.html

Py:   sys.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtzyadnhgd.html

PHP:  exit(1);
来源：http://dali.zycfv.cn/Article/details/gtoirfebgk.html

JS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gthrbzyake.html

TS:   process.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtygrfwake.html

Java: System.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtodsxjmvx.html

Go:   os.Exit(1)
来源：http://dali.xylfe.cn/Article/details/gtjhwicdql.html

Ruby: exit 1
来源：http://dali.yuxming.cn/Article/details/gttrcifdri.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.wangshuangyany.cn/Article/details/gttbhtjrjz.html

[M06] 向标准错误输出
来源：http://dali.yonumen.top/Article/details/gtofwfcyjw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daxiang520.top/Article/details/gteiikqpgv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zycfv.cn/Article/details/gtzmmvlwzo.html

JS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gtcvehdrtj.html

TS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gtxfdfhenf.html

Java: System.err.println("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnvlvdow.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shuidangran.top/Article/details/gtqgfudtqm.html

Ruby: warn "err"
来源：http://dali.shuidangran.top/Article/details/gtidgooeii.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenzaomai.com/Article/details/gtdvedmieo.html

[M07] 判断是否为主入口
来源：http://dali.jyoumei.cn/Article/details/gtehbnclex.html

Py:   if __name__ == "__main__":
来源：http://dali.mhx1999.top/Article/details/gtvbdjwhsa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxinkj.top/Article/details/gtmepguzgc.html

JS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gtibcpxrlr.html

TS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gtoviwtfjr.html

Java: public static void main(String[] args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjjagsbt.html

Go:   func main()
来源：http://dali.zhongyouzk.top/Article/details/gtopegqmnn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.0kj1m.cn/Article/details/gtswydnssv.html

C#:   static void Main(string[] args)
来源：http://dali.jqgufenzy.top/Article/details/gtttcmrrbm.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gtighuypnc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.c1oappe.top/Article/details/gtgkasgsmf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sysykeji.top/Article/details/gtfqxrebzh.html

JS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gtoysjagbb.html

TS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gtjrnixdgh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigfzy.top/Article/details/gtpaukccrf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cucudq.cn/Article/details/gtwywykpzd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xziqi.cn/Article/details/gtseddrixa.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfbelupl.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtkgpumxrr.html

N. 数据结构与算法
来源：http://dali.havefunace.top/Article/details/gthjowbvtx.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtjgeqyhis.html

[N01] 二分查找（有序数组）
来源：http://dali.andypj.xyz/Article/details/gtliyqivdk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gthzwiojyf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yueranfly.top/Article/details/gtgoygcbtd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gtsoeytduz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtslbsgbvs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sxryk.cn/Article/details/gthkhxnttb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtqoitsdab.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258.top/Article/details/gtrpxttfln.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtaojcvwym.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gogol.net.cn/Article/details/gtkmbwptmf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yueranfly.top/Article/details/gtvpwkwclo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.smart0.xyz/Article/details/gtdrpihwdp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtjufekxbu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gtktsgiphm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gogol.net.cn/Article/details/gtidiwabjz.html

Go:   slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gtlgkcvuvf.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gtcgchqcgp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ivvv.top/Article/details/gtfykjgruu.html

[N03] 快速排序（分治示例）
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkspmcyb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daxiang520.top/Article/details/gtepwgmehg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sysykeji.top/Article/details/gtusharaub.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gteuvvvgel.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gtkfeavyeh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jiagoushi.top/Article/details/gtatwlyaqi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.pycfn.com/Article/details/gtfctpywyr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xziqi.cn/Article/details/gtampfevwl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hfpthk.cn/Article/details/gtwifzvsds.html

[N04] 斐波那契数列
来源：http://dali.zhoulong.xyz/Article/details/gtxphpgoha.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gtonwkarel.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiglzixvd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtajuptxcd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtofrkkdrd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gtzjcyyzgo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yonumen.top/Article/details/gtcedpzlcn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gtxsnlyblr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtqkcmtrbj.html

[N05] 最大公约数
来源：http://dali.c1oappe.top/Article/details/gthqmublup.html

Py:   math.gcd(a, b)
来源：http://dali.cashguo.top/Article/details/gtqujttuvl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.wangdashe.top/Article/details/gtokitdeov.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gtbwdahnyt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gtbydkfuze.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sufxvd.cn/Article/details/gtqqazxcyf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xinyue.icu/Article/details/gtiptaecfz.html

Ruby: a.gcd(b)
来源：http://dali.ybcxt.top/Article/details/gtciwqmexe.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dianchejie.cn/Article/details/gtjqyxaktg.html

[N06] 判断回文字符串
来源：http://dali.hywenlv.cn/Article/details/gtiasmhxkl.html

Py:   s == s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gtorrbondm.html

PHP:  $s === strrev($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtofcfzoba.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtedqxsxxh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtdhsansnj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnqzz.top/Article/details/gtgjgxrxkw.html

Go:   // 双指针从两端比较
来源：http://dali.zhengqikj.top/Article/details/gtxzqabrum.html

Ruby: s == s.reverse
来源：http://dali.gogol.net.cn/Article/details/gtspiumwrv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gtlkxqqgig.html

[N07] 两数之和（返回下标）
来源：http://dali.hywenlv.cn/Article/details/gtsytpbxch.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258.top/Article/details/gtssaljpqy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.vqdsnc.cn/Article/details/gtvcqohjze.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangshuangyany.cn/Article/details/gtotphtabw.html

TS:   // 手写 Map<string, number>
来源：http://dali.c1oappe.top/Article/details/gtutnocftc.html

Java: // 手写 HashMap
来源：http://dali.aibaodan.cn/Article/details/gttvmjkxiu.html

Go:   // 手写 map[int]int
来源：http://dali.meibo888.top/Article/details/gtpltcpcrt.html

Ruby: // 手写 Hash
来源：http://dali.nanxuanxn.top/Article/details/gtemjlruve.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yuxming.cn/Article/details/gtpkyktnfg.html

[N08] 生成全排列
来源：http://dali.jiagoushi.top/Article/details/gtbutgddgu.html

Py:   itertools.permutations(arr)
来源：http://dali.iojbl.cn/Article/details/gtrxtmeycu.html

PHP:  // 手写递归交换
来源：http://dali.tanke756.top/Article/details/gtlsbqsxve.html

JS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtdeieajoi.html

TS:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtjegmaasd.html

Java: // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgsxinmca.html

Go:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtcpbgapom.html

Ruby: arr.permutation.to_a
来源：http://dali.pengpengdd.cyou/Article/details/gtgqbfjhpf.html

C#:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtcgzhcata.html

[N09] 栈与队列
来源：http://dali.tianlin.xyz/Article/details/gtuqoepasw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnvzfbmk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gtjioxolhm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtwxvigqqu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jyoumei.cn/Article/details/gtfsboegaz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenzaomai.com/Article/details/gtzeuzqsej.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yuanzhike.top/Article/details/gtjntnqrrf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzwgfqmk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zdqjudy.top/Article/details/gtocauspvu.html

[N10] 链表节点定义
来源：http://dali.yangfankeji.com/Article/details/gtwurmsraw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.haohaochexian.top/Article/details/gtimrbtblv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xuetiantiany.cn/Article/details/gtmgrnqgqn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuaysquqm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sufxvd.cn/Article/details/gtixcwzhrx.html

Java: class Node { int v; Node next; }
来源：http://dali.hammf.cn/Article/details/gtjlzgaata.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tianlin.xyz/Article/details/gtctouxmzf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sufxvd.cn/Article/details/gtyrjfifxo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpxpzjpdc.html

[N11] 二叉树中序遍历
来源：http://dali.nanxuanxn.top/Article/details/gtwyjlhdcc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aizwys.cn/Article/details/gtecrnjfnu.html

PHP:  // 手写递归函数
来源：http://dali.gaohongyu789.top/Article/details/gtpauqpopj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gtjgdzxars.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gtbadxezmp.html

Java: // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gtlrfwdbla.html

Go:   // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtrguzxjfe.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgscimtdh.html

C#:   // 手写递归
来源：http://dali.redwolf501.top/Article/details/gtlpudghbu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hysaishi.cn/Article/details/gtkdoyazxe.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cucudq.cn/Article/details/gtubrckrcf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sufxvd.cn/Article/details/gtsrqhlzuh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gtygsluylv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjktuqwf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gtlnswwqyp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zdqjudy.top/Article/details/gthmcftyiq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.svipenyu.cn/Article/details/gtwlicmlwi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gtrhmsikla.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtrrizmcap.html

O. 并发与异步
来源：http://dali.ydzc1.top/Article/details/gtopieolhs.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtklnghprm.html

[O01] 启动一个线程
来源：http://dali.aizwys.cn/Article/details/gtpcrakgur.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sxryk.cn/Article/details/gtrduogwuv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.haohaochexian.top/Article/details/gtblfkataf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhoulong.xyz/Article/details/gtlpwhrecx.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gtqyqwjerv.html

Java: new Thread(() -> f()).start()
来源：http://dali.ivvv.top/Article/details/gtfszwilko.html

Go:   go f()
来源：http://dali.jqgfzy.top/Article/details/gtssjbvdys.html

Ruby: Thread.new { f }
来源：http://dali.zycfv.cn/Article/details/gtqwdarudm.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigfzy.top/Article/details/gtxieeoyoy.html

[O02] 使用线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gttimhfcof.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xuanzx.com/Article/details/gtbeoqkgfs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.quarkkingdee.top/Article/details/gtmejcidpk.html

JS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gteugoumgr.html

TS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gtcggvmivg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cashguo.top/Article/details/gtxzfhobsw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cdnleiting.top/Article/details/gtgjaeozkx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nanxinkj.top/Article/details/gthokvruzf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.c1oappe.top/Article/details/gtgfkafred.html

[O03] 加锁保护共享数据
来源：http://dali.yj20258888.top/Article/details/gtabmqulez.html

Py:   with lock: shared += 1
来源：http://dali.gaohongyu789.top/Article/details/gtevkojhgr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aizwys.cn/Article/details/gtligyjkow.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yueranfly.top/Article/details/gtmcqhjhnz.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gtpfveirjz.html

Java: synchronized (this) { shared++; }
来源：http://dali.dashuyun.cn/Article/details/gtlmzsmarz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hongshengwenyu.top/Article/details/gtjoqsmiph.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gtnfjuhpxt.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttnmhqnnt.html

[O04] 定义异步函数并等待
来源：http://dali.316326.xyz/Article/details/gtjrqrqojj.html

Py:   async def f():⏎    await g()
来源：http://dali.quarkkingdee.top/Article/details/gtiopgeoqh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj202588.top/Article/details/gtpklvbndw.html

JS:   async function f() { await g(); }
来源：http://dali.nanxuanxn.top/Article/details/gthulmhpev.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.meibo888.top/Article/details/gtfxhhilsy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.316326.xyz/Article/details/gtgobvexjx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.vqdsnc.cn/Article/details/gtcsffjigg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pengpengdd.cyou/Article/details/gtoihzaysx.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigfzy.top/Article/details/gthstrsckj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gtoyzkzuvl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.vqdsnc.cn/Article/details/gtlyiyatub.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenjidiqi.icu/Article/details/gtgjhviseg.html

JS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gtccgyvmvl.html

TS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gtnaowynul.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.c1oappe.top/Article/details/gtgwbjfcsa.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yuxming.cn/Article/details/gtgfkuenwf.html

Ruby: threads.map(&:join)
来源：http://dali.andypj.xyz/Article/details/gtnvftilnw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hysaishi.cn/Article/details/gtpgqinteo.html

[O06] 使用进程池
来源：http://dali.hywenlv.cn/Article/details/gtcmofqnjb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.snrcjt.cn/Article/details/gtvansgfmo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtakyeapmc.html

JS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gtihkdcihi.html

TS:   // child_process / cluster 模块
来源：http://dali.smart0.xyz/Article/details/gtndfgmwhv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sxryk.cn/Article/details/gtqpiqhzfs.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxinkj.top/Article/details/gtrfxuevvu.html

Ruby: // fork 块
来源：http://dali.zhixingplan.top/Article/details/gtpdqortqf.html

C#:   Parallel.For
来源：http://dali.nanxinkj.top/Article/details/gthsplbaxl.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtnafgctmi.html

P. 常用工具函数
来源：http://dali.ehwqpu.com/Article/details/gtkrgkssrw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtvggfswrk.html

[P01] 生成 UUID
来源：http://dali.yuxming.cn/Article/details/gtfkuanvmv.html

Py:   str(uuid.uuid4())
来源：http://dali.sysykeji.top/Article/details/gtgdwydmxb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gtpyqjfegv.html

JS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gtrnaeukcx.html

TS:   crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gtvqdgshpe.html

Java: UUID.randomUUID().toString()
来源：http://dali.hywenlv.cn/Article/details/gtongusbwu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sufxvd.cn/Article/details/gtjjurqriz.html

Ruby: SecureRandom.uuid
来源：http://dali.ydzc1.top/Article/details/gtyauczcxm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xinyue.icu/Article/details/gtpcusgptw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xuetiantiany.cn/Article/details/gtzlstqqhb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hfpthk.cn/Article/details/gtudvmqhzi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gzhubu.top/Article/details/gtwtiekxsj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.meibo888.top/Article/details/gtvuyetfmc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnqzz.top/Article/details/gtbapigwrk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guannengcc.top/Article/details/gtvrfngctg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aibaodan.cn/Article/details/gtdhmpbkif.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jyoumei.cn/Article/details/gtipkbvpxs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hywenlv.cn/Article/details/gtekmqtzxe.html

[P03] 生成短随机字符串
来源：http://dali.ydzc1.top/Article/details/gtkesitnus.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.feifeiyinyue.top/Article/details/gtyoqtdxhc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.fengsongda.top/Article/details/gtxqnukqjc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtsmbgkhxu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtktmdtewp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daria6918.cn/Article/details/gtjuudbeqa.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aibaodan.cn/Article/details/gtpquvwfst.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhixingplan.top/Article/details/gtbflujfxj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hysaishi.cn/Article/details/gtoybdbskp.html

[P04] 求长度
来源：http://dali.yueranfly.top/Article/details/gtrmlvywvs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cdnleiting.top/Article/details/gtiuidenkq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvogcnhj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtmfciapaq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zycfv.cn/Article/details/gtuhsizlsq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xylfe.cn/Article/details/gtruwfiqaq.html

Go:   len(arr);  len(m)
来源：http://dali.daria6918.cn/Article/details/gtwadsffhd.html

Ruby: x.length;  x.size
来源：http://dali.hnxiangtu.top/Article/details/gtmznoeiwj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gtpruzqubg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.andypj.xyz/Article/details/gtxgbwnwkv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jiagoushi.top/Article/details/gtqascjiff.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.vqdsnc.cn/Article/details/gttqigzvfs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xuetiantiany.cn/Article/details/gtsjhoyeke.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daria6918.cn/Article/details/gtvzptwbph.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ybcxt.top/Article/details/gteozqpcjs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tian-w.cn/Article/details/gtigyphmbo.html

Ruby: a == b
来源：http://dali.jiagoushi.top/Article/details/gtpjetobyt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuxming.cn/Article/details/gtmeszxpbb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hammf.cn/Article/details/gtfrrxcyfm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pengpengdd.cyou/Article/details/gtvyzhtakf.html

PHP:  if (empty($x)) {}
来源：http://dali.yongpay.top/Article/details/gtmqbbifqh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yueranfly.top/Article/details/gtqhisfvrk.html

TS:   if (x == null) {}
来源：http://dali.yuxming.cn/Article/details/gtrxgixkky.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gtswddwjzk.html

Go:   if x == nil {}
来源：http://dali.9152youxi.cn/Article/details/gtauzdlshj.html


<!-- 参考信息 -->