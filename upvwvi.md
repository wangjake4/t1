代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gtpsuljkfr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtiinopbtt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258.top/Article/details/gtqykoaaam.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenzaomai.com/Article/details/gtzirviljn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guowangkeji.top/Article/details/gtflkckgyv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fzhhl.top/Article/details/gtryvfcfms.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtjkpfxlid.html

M. 命令行 / 进程 / 环境
来源：http://dali.sufxvd.cn/Article/details/gtlfakjmjo.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtjifohbrz.html

[M01] 读取命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtduqfwxet.html

Py:   sys.argv[1:]
来源：http://dali.meibo888.top/Article/details/gtqrsrzfej.html

PHP:  $argv;  $argc;
来源：http://dali.xylfe.cn/Article/details/gthkesnoqz.html

JS:   process.argv.slice(2)
来源：http://dali.guowangkeji.top/Article/details/gtjnfnjwyc.html

TS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtvegsxywl.html

Java: args 数组（main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gtrklctqfy.html

Go:   os.Args[1:]
来源：http://dali.chenlongwang.top/Article/details/gtqscctfuf.html

Ruby: ARGV
来源：http://dali.yvedp.cn/Article/details/gtpdzonnct.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gtjvdafkjk.html

[M02] 读取环境变量
来源：http://dali.haohaochexian.top/Article/details/gtrdqknkwe.html

Py:   os.environ.get("HOME")
来源：http://dali.aizwys.cn/Article/details/gtvhnikwsn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gtaaagvdvi.html

JS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gtsmibyyet.html

TS:   process.env.HOME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqcghdum.html

Java: System.getenv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gticqeneyr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtghpyccyp.html

Ruby: ENV["HOME"]
来源：http://dali.chenlongwang.top/Article/details/gtqbfoezxl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258888.top/Article/details/gtquvxyipj.html

[M03] 执行外部命令
来源：http://dali.0kj1m.cn/Article/details/gtnxyffyoa.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dianchejie.cn/Article/details/gtrkswkdbj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgfzy.top/Article/details/gtjaphqphb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gtbhffnhig.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gtnunwtjjm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cqqwz.cn/Article/details/gtjqmcagsf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shuidangran.top/Article/details/gtsfacjvnh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpyjeumr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhoulong.xyz/Article/details/gtnvcndtve.html

[M04] 获取当前工作目录
来源：http://dali.zdqjudy.top/Article/details/gtviferbvt.html

Py:   os.getcwd()
来源：http://dali.nwbrower.top/Article/details/gtpnhqgcrt.html

PHP:  getcwd();
来源：http://dali.jyoumei.cn/Article/details/gtzbqxtgms.html

JS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gtitgbznca.html

TS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gtiszqrhji.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yonumen.top/Article/details/gtgyaglest.html

Go:   os.Getwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtkyvhmhsj.html

Ruby: Dir.pwd
来源：http://dali.jianghu66.top/Article/details/gtizlivgsn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbveelxf.html

[M05] 设置退出码
来源：http://dali.jiagoushi.top/Article/details/gtawouvbqg.html

Py:   sys.exit(1)
来源：http://dali.meibo888.top/Article/details/gtwoqjhdnb.html

PHP:  exit(1);
来源：http://dali.aizwys.cn/Article/details/gtqwskzohn.html

JS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtfwacnsfb.html

TS:   process.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtocutsxvw.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gthvuhjipv.html

Go:   os.Exit(1)
来源：http://dali.fzhhl.top/Article/details/gtqiqqvwzz.html

Ruby: exit 1
来源：http://dali.andypj.xyz/Article/details/gtclwwahcq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jlsjyb.cn/Article/details/gtqbjomeqx.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gtwmzzqcsz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hfpthk.cn/Article/details/gtifvdnbqt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tanke756.top/Article/details/gtpitmjmgn.html

JS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gtsfvlwemz.html

TS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gttjjreeat.html

Java: System.err.println("err")
来源：http://dali.hnxiangtu.top/Article/details/gtagtzpepa.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycfmzgxl.html

Ruby: warn "err"
来源：http://dali.ivvv.top/Article/details/gtdtamqeqf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhoulong.xyz/Article/details/gtmyyqpfed.html

[M07] 判断是否为主入口
来源：http://dali.haohaochexian.top/Article/details/gtwxymylse.html

Py:   if __name__ == "__main__":
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqjmcuvj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ivvv.top/Article/details/gtmfdlddre.html

JS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gtgwvnxqxn.html

TS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gtjqvbtwic.html

Java: public static void main(String[] args)
来源：http://dali.cqqwz.cn/Article/details/gtazepiecg.html

Go:   func main()
来源：http://dali.yj20258.top/Article/details/gtclnlyzrh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ivvv.top/Article/details/gtpkaubwjq.html

C#:   static void Main(string[] args)
来源：http://dali.yangfankeji.com/Article/details/gtdchxlfig.html

[M08] 获取系统与运行时信息
来源：http://dali.bjfxy.top/Article/details/gtxrlpvedn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jlsjyb.cn/Article/details/gtzgsupjyw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkgdntlg.html

JS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gtrziwstmf.html

TS:   process.platform;  process.version
来源：http://dali.hongshengwenyu.top/Article/details/gthnpuebqn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aibaodan.cn/Article/details/gtlctygdap.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj202588.top/Article/details/gtirzaldoi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.snrcjt.cn/Article/details/gtkidajpes.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sxryk.cn/Article/details/gtqjgrzlie.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtrgblykvg.html

N. 数据结构与算法
来源：http://dali.dianchejie.cn/Article/details/gtuzeljjek.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtpfirqbvn.html

[N01] 二分查找（有序数组）
来源：http://dali.hongshengwenyu.top/Article/details/gtlykkdxit.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtdvhpkxwj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gtcnrsbneb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gtimenpkun.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtcsbmzxxu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtzthcywqq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtdhlcjhtg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnqzz.top/Article/details/gtvqzokoxp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtunahdeap.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.fengsongda.top/Article/details/gtsaghllww.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gtdgdiogqk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuanzhike.top/Article/details/gthrozzzwx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gtzloytlmt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtxsbnyidx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ehwqpu.com/Article/details/gtajjyowjm.html

Go:   slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtwjikwjoh.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtathtwsvy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jyoumei.cn/Article/details/gtooydcnsz.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxinkj.top/Article/details/gtiibalyre.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgfzy.top/Article/details/gtnsogsjiz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zdqjudy.top/Article/details/gthcqvslcq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gtadcuseky.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gtihltoups.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gaohongyu789.top/Article/details/gtuyqdyvuh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.havefunace.top/Article/details/gtnzskfjsm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenjidiqi.icu/Article/details/gtbmabacga.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nwbrower.top/Article/details/gtvwxonyin.html

[N04] 斐波那契数列
来源：http://dali.tian-w.cn/Article/details/gtaqzffvex.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gtwsfjidpo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fengsongda.top/Article/details/gtiskxydvt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtwbqepqhs.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gtnwppytqx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gtpsccjcoq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258888.top/Article/details/gtrmdjnuuh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtcacokpjz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gtapanmrjc.html

[N05] 最大公约数
来源：http://dali.wangshuangyany.cn/Article/details/gtefxtfblz.html

Py:   math.gcd(a, b)
来源：http://dali.hfpthk.cn/Article/details/gtobfiahjn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shzxlz.cn/Article/details/gtnfilaidn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtankriryz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gtkixlpbxo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.quarkkingdee.top/Article/details/gtpkaxjech.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxbceywy.html

Ruby: a.gcd(b)
来源：http://dali.sysykeji.top/Article/details/gtgqormmdx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigfzy.top/Article/details/gtrakesgjc.html

[N06] 判断回文字符串
来源：http://dali.shuidangran.top/Article/details/gtrceiwrlz.html

Py:   s == s[::-1]
来源：http://dali.sysykeji.top/Article/details/gtlozvbfvn.html

PHP:  $s === strrev($s);
来源：http://dali.mhx1999.top/Article/details/gtiuswaujd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtrqdvclwr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtwhdjruev.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yueranfly.top/Article/details/gtwicufqsl.html

Go:   // 双指针从两端比较
来源：http://dali.jinqigfzy.top/Article/details/gtzvhxnvak.html

Ruby: s == s.reverse
来源：http://dali.316326.xyz/Article/details/gtxrcfjwgj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aibaodan.cn/Article/details/gtvrtggekp.html

[N07] 两数之和（返回下标）
来源：http://dali.daria6918.cn/Article/details/gtwpueugkd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daxiang520.top/Article/details/gtqvgxloaj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yanxiufei.cn/Article/details/gtbzkoulwl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yvedp.cn/Article/details/gtmcxvpdzc.html

TS:   // 手写 Map<string, number>
来源：http://dali.hfpthk.cn/Article/details/gtdxehnssf.html

Java: // 手写 HashMap
来源：http://dali.jlsjyb.cn/Article/details/gtgiuyhzof.html

Go:   // 手写 map[int]int
来源：http://dali.sxryk.cn/Article/details/gtzqzgllpc.html

Ruby: // 手写 Hash
来源：http://dali.shzxlz.cn/Article/details/gtdrvikhow.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.haohaochexian.top/Article/details/gtbyjbazzn.html

[N08] 生成全排列
来源：http://dali.hongshengwenyu.top/Article/details/gtbnbnkmxp.html

Py:   itertools.permutations(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtpxecmywr.html

PHP:  // 手写递归交换
来源：http://dali.ppjwa.cn/Article/details/gtizmtshji.html

JS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gthdzkbmhl.html

TS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtpfokpjbq.html

Java: // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtpngpnsug.html

Go:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtfemlllgq.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxinkj.top/Article/details/gtvvugkugr.html

C#:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtaezphofv.html

[N09] 栈与队列
来源：http://dali.chenlongwang.top/Article/details/gtfpqgondk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yuxming.cn/Article/details/gtsffudzhc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gttdntflqx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gtzxeemlhn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetifzmkt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zycfv.cn/Article/details/gtufufdoxt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.guowangkeji.top/Article/details/gtsojhqxqy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gtrykqkdas.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gogol.net.cn/Article/details/gtsjbckknz.html

[N10] 链表节点定义
来源：http://dali.nwbrower.top/Article/details/gtrfbzmlwg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yvedp.cn/Article/details/gtoujlmbzy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxinkj.top/Article/details/gtiioxhgez.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zdqjudy.top/Article/details/gtcazclecp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jlsjyb.cn/Article/details/gtlzmyfttp.html

Java: class Node { int v; Node next; }
来源：http://dali.jlsjyb.cn/Article/details/gtaphtknfw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenjidiqi.icu/Article/details/gtyalmuley.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nanxinkj.top/Article/details/gtdihnfztn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sufxvd.cn/Article/details/gtpymjvllk.html

[N11] 二叉树中序遍历
来源：http://dali.0kj1m.cn/Article/details/gtanbsdpee.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.svipenyu.cn/Article/details/gtoguntdbx.html

PHP:  // 手写递归函数
来源：http://dali.gogol.net.cn/Article/details/gtdeppeheb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzplslure.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gtoyhqfbmf.html

Java: // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gticrhhdhr.html

Go:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gtjegyspzo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.quarkkingdee.top/Article/details/gtftzmwkmt.html

C#:   // 手写递归
来源：http://dali.aizwys.cn/Article/details/gttktlxbdx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yangfankeji.com/Article/details/gtcukmsfqh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.bjfxy.top/Article/details/gtusmtivpl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.daxiang520.top/Article/details/gtdemmzpli.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gthuasyuyo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gtjpzhlwmk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gtqulienyu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aibaodan.cn/Article/details/gtwjacfixj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtzddptpzd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gthmdstiat.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtpccyfcmk.html

O. 并发与异步
来源：http://dali.ybcxt.top/Article/details/gtjwvaevpr.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtpqtfeytr.html

[O01] 启动一个线程
来源：http://dali.mhx1999.top/Article/details/gtdsvozlcp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinqigufen.top/Article/details/gtkvjwpjfi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenjidiqi.icu/Article/details/gtrsgjgjqc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykjgdhsh.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gtcsadrjoj.html

Java: new Thread(() -> f()).start()
来源：http://dali.svipenyu.cn/Article/details/gtdbkqlypo.html

Go:   go f()
来源：http://dali.jinqigufen.top/Article/details/gtrbqqzrrz.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gtjzagihoo.html

C#:   Task.Run(() => F());
来源：http://dali.jlsjyb.cn/Article/details/gtxlcdifcp.html

[O02] 使用线程池
来源：http://dali.guannengcc.top/Article/details/gttjcijmsx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnxiangtu.top/Article/details/gtdrrsbklh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hnqzz.top/Article/details/gtkvzxwxdp.html

JS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gtjgvoajpt.html

TS:   // worker_threads 线程池
来源：http://dali.yanxiufei.cn/Article/details/gtklvdnvrm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.bjfxy.top/Article/details/gtriahobox.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zdqjudy.top/Article/details/gtwrjlppfu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jiagoushi.top/Article/details/gtjxpznxgh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jiagoushi.top/Article/details/gtjhkswwwr.html

[O03] 加锁保护共享数据
来源：http://dali.tianlin.xyz/Article/details/gtqxoknxdu.html

Py:   with lock: shared += 1
来源：http://dali.svipenyu.cn/Article/details/gtucoswwam.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ehwqpu.com/Article/details/gtbqggffji.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenjidiqi.icu/Article/details/gtlckfcuzy.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gtbbxhkhmn.html

Java: synchronized (this) { shared++; }
来源：http://dali.jiagoushi.top/Article/details/gtlgaacdgf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shuidangran.top/Article/details/gtrzkdvasj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxkewgqr.html

C#:   lock (gate) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gtujztpzkn.html

[O04] 定义异步函数并等待
来源：http://dali.vqdsnc.cn/Article/details/gtzjizgjjg.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigfzy.top/Article/details/gtzfyitszn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cashguo.top/Article/details/gtbefaqovf.html

JS:   async function f() { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gtlvyfbeog.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.aibaodan.cn/Article/details/gtpekopyyc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dianchejie.cn/Article/details/gttfuqioyn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.c1oappe.top/Article/details/gtogppjlta.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shzxlz.cn/Article/details/gtyrlqsowo.html

C#:   async Task F() { await G(); }
来源：http://dali.tian-w.cn/Article/details/gtxdpmxdkk.html

[O05] 并发执行并等待全部完成
来源：http://dali.ybcxt.top/Article/details/gtdsbraain.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yvedp.cn/Article/details/gtzezvhagz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nwbrower.top/Article/details/gtdbivyktb.html

JS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gtpztqjrcg.html

TS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gtqidavxbu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yonumen.top/Article/details/gtgqbvsbmh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dashuyun.cn/Article/details/gtrhyfsmpz.html

Ruby: threads.map(&:join)
来源：http://dali.hfpthk.cn/Article/details/gtvdeawsmd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gzhubu.top/Article/details/gtueggdhte.html

[O06] 使用进程池
来源：http://dali.hongshengwenyu.top/Article/details/gtqdtwnbhj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258888.top/Article/details/gtufcmzkbi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.wangdashe.top/Article/details/gtbfkdrxpl.html

JS:   // child_process / cluster 模块
来源：http://dali.yj202588.top/Article/details/gtwqtbnmwy.html

TS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gtvfzteljf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenlongwang.top/Article/details/gtyekcfldb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shuidangran.top/Article/details/gtmlcgbkqu.html

Ruby: // fork 块
来源：http://dali.zdqjudy.top/Article/details/gthvfrkcik.html

C#:   Parallel.For
来源：http://dali.cheryme.top/Article/details/gtxeleygul.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gthngwzlfh.html

P. 常用工具函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogteffhw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtawkbsize.html

[P01] 生成 UUID
来源：http://dali.dianchejie.cn/Article/details/gtiwszlfbz.html

Py:   str(uuid.uuid4())
来源：http://dali.xuanzx.com/Article/details/gthyikfegx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.aibaodan.cn/Article/details/gtmqeaiafx.html

JS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gtakqhvwjv.html

TS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gtiesmyrjv.html

Java: UUID.randomUUID().toString()
来源：http://dali.snrcjt.cn/Article/details/gthcrdimyd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yanxiufei.cn/Article/details/gtdhjxwqda.html

Ruby: SecureRandom.uuid
来源：http://dali.hammf.cn/Article/details/gtglnphqdt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.meibo888.top/Article/details/gtmjibrsez.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xylfe.cn/Article/details/gtyaiovuwt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tian-w.cn/Article/details/gtrvheyije.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gotoacloud.top/Article/details/gtuhpeoawz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ehwqpu.com/Article/details/gtfhumsqez.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hfpthk.cn/Article/details/gtowzaxakd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cheryme.top/Article/details/gtxzfbcziy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gtaosmnrhh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shuidangran.top/Article/details/gtludifppp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.fzhhl.top/Article/details/gtbsjndmzr.html

[P03] 生成短随机字符串
来源：http://dali.wangdashe.top/Article/details/gtlhvabnzd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangshuangyany.cn/Article/details/gtvpmswibg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.9152youxi.cn/Article/details/gttbqpzvsj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sufxvd.cn/Article/details/gtoakcliqb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtkhmgbseh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jlsjyb.cn/Article/details/gtheouzebn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklxdrmlv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dianchejie.cn/Article/details/gtldwncfmy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shzxlz.cn/Article/details/gtiilzcobh.html

[P04] 求长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtilaiqmxe.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhoulong.xyz/Article/details/gtalwatnpj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtsojswntb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gthbmepvpi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xziqi.cn/Article/details/gtkelaayhf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gtbzfajeed.html

Go:   len(arr);  len(m)
来源：http://dali.yuxming.cn/Article/details/gtkcqgbrgq.html

Ruby: x.length;  x.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfurufxfa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cucudq.cn/Article/details/gttjhbrvbx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxuanxn.top/Article/details/gtvvrjxdgl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jiagoushi.top/Article/details/gtayafwlsb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvsdxbad.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.dianchejie.cn/Article/details/gtgnkiijsh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxinkj.top/Article/details/gtkkewqacy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nwbrower.top/Article/details/gtsopxdkte.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gtagfuwpuq.html

Ruby: a == b
来源：http://dali.9152youxi.cn/Article/details/gtnsbdsnff.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.mhx1999.top/Article/details/gtueklgvfs.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sxryk.cn/Article/details/gthfjvmwsg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pengpengdd.cyou/Article/details/gtvgkovbyw.html

PHP:  if (empty($x)) {}
来源：http://dali.kuanghao11.cn/Article/details/gtcirvsyuq.html


<!-- 参考信息 -->