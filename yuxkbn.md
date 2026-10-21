代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtzzzujkuk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtobvjorwa.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hammf.cn/Article/details/gthsniyefa.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxinkj.top/Article/details/gtpsrlnfsb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gtigvstudr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkyvjdal.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtlgxtwrpu.html

M. 命令行 / 进程 / 环境
来源：http://dali.vqdsnc.cn/Article/details/gtilljkngc.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtethbsjry.html

[M01] 读取命令行参数
来源：http://dali.c1oappe.top/Article/details/gtwbebelrv.html

Py:   sys.argv[1:]
来源：http://dali.yvedp.cn/Article/details/gtsfaebtqi.html

PHP:  $argv;  $argc;
来源：http://dali.jyoumei.cn/Article/details/gtuhxajbyl.html

JS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gtmcolkrys.html

TS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtajqaiido.html

Java: args 数组（main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gtikfpijjm.html

Go:   os.Args[1:]
来源：http://dali.nwbrower.top/Article/details/gtglbytity.html

Ruby: ARGV
来源：http://dali.jyoumei.cn/Article/details/gtmrswhoks.html

C#:   args 数组（Main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gtbjqlecbr.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gtnxtzfhdk.html

Py:   os.environ.get("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtqixoahkg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gtmcvdnwol.html

JS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gtlrsiiqzg.html

TS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gtdhapcxkv.html

Java: System.getenv("HOME")
来源：http://dali.xylfe.cn/Article/details/gtxcrqoctg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jianghu66.top/Article/details/gtounsdoyl.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkxvkknl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtxsigkwij.html

[M03] 执行外部命令
来源：http://dali.hongshengwenyu.top/Article/details/gtulybenzu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gotoacloud.top/Article/details/gttypezzdy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tian-w.cn/Article/details/gtsauhnxkg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtqgjbgjtc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gtufqsujit.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ivvv.top/Article/details/gtuyktfkrh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aibaodan.cn/Article/details/gtfzqawvoi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nanxinkj.top/Article/details/gtecmrjcto.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangshuangyany.cn/Article/details/gtteyyljdo.html

[M04] 获取当前工作目录
来源：http://dali.yangfankeji.com/Article/details/gtqmpukgdy.html

Py:   os.getcwd()
来源：http://dali.yj202588.top/Article/details/gtwnfiyozq.html

PHP:  getcwd();
来源：http://dali.daria6918.cn/Article/details/gthzcitnic.html

JS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtiyyzprnr.html

TS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvkkjeso.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuanzhike.top/Article/details/gtpbldotas.html

Go:   os.Getwd()
来源：http://dali.bjfxy.top/Article/details/gtfwnlzbux.html

Ruby: Dir.pwd
来源：http://dali.xuetiantiany.cn/Article/details/gtcbtshand.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.svipenyu.cn/Article/details/gtvzgaqbul.html

[M05] 设置退出码
来源：http://dali.zycfv.cn/Article/details/gttcadwuql.html

Py:   sys.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtlrdjjrue.html

PHP:  exit(1);
来源：http://dali.redwolf501.top/Article/details/gtmifqjmmd.html

JS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtkubyqegs.html

TS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtstyijnkq.html

Java: System.exit(1)
来源：http://dali.meibo888.top/Article/details/gtpjzcacio.html

Go:   os.Exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtnrgtecmg.html

Ruby: exit 1
来源：http://dali.redwolf501.top/Article/details/gtdymrvziu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.meibo888.top/Article/details/gtzsgvpdbr.html

[M06] 向标准错误输出
来源：http://dali.tanke756.top/Article/details/gtxfwkwpik.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gtuxtmiweu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.bjfxy.top/Article/details/gtgpdnmazn.html

JS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gtmnqfrtkr.html

TS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gtrkoantcv.html

Java: System.err.println("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqusgvidu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.meibo888.top/Article/details/gtbbvvxxuy.html

Ruby: warn "err"
来源：http://dali.yj202588.top/Article/details/gtnviyewkk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.c1oappe.top/Article/details/gtdthtnqpv.html

[M07] 判断是否为主入口
来源：http://dali.snrcjt.cn/Article/details/gtazthutss.html

Py:   if __name__ == "__main__":
来源：http://dali.cdnleiting.top/Article/details/gtxhnljhgd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aibaodan.cn/Article/details/gtnuilwzkd.html

JS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnuosmox.html

TS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gtpawepcpu.html

Java: public static void main(String[] args)
来源：http://dali.yj20258.top/Article/details/gtraluxqam.html

Go:   func main()
来源：http://dali.svipenyu.cn/Article/details/gtmdmkxnom.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.0kj1m.cn/Article/details/gtkqamovsn.html

C#:   static void Main(string[] args)
来源：http://dali.jqgfzy.top/Article/details/gtqntvleeg.html

[M08] 获取系统与运行时信息
来源：http://dali.xziqi.cn/Article/details/gtjzjijmln.html

Py:   platform.system();  platform.python_version()
来源：http://dali.c1oappe.top/Article/details/gtdhrlihlg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.0kj1m.cn/Article/details/gttouxukpz.html

JS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gtexbypzmt.html

TS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gtlrxfkbnu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gtgarmscsy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dashuyun.cn/Article/details/gtfxdueczz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.redwolf501.top/Article/details/gtuitwrtsm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sxryk.cn/Article/details/gtkbtrgchk.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtoruezfaq.html

N. 数据结构与算法
来源：http://dali.svipenyu.cn/Article/details/gthakmyiiy.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtpyjgfnts.html

[N01] 二分查找（有序数组）
来源：http://dali.smart0.xyz/Article/details/gtcfrzipwc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqyeeiyf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yvedp.cn/Article/details/gtiyxlffbr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gtqkxxretf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gtnrvcagze.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gthwobaamc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtrlxuwfqg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.havefunace.top/Article/details/gtgrppccui.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtymbbeoiq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.iojbl.cn/Article/details/gtcbyhqyvb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ppjwa.cn/Article/details/gtgpasawbb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shuidangran.top/Article/details/gtjcxjgioj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gtlkvnqysu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gthwipeked.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daria6918.cn/Article/details/gtflogmokw.html

Go:   slices.Sort(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtwfkddjsx.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gtfyamegxp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhengqikj.top/Article/details/gtvfqsgyuw.html

[N03] 快速排序（分治示例）
来源：http://dali.xylfe.cn/Article/details/gtckcsxgfo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenzaomai.com/Article/details/gtevglutme.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xylfe.cn/Article/details/gtswdvemzb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpmpjcoz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gtfzveitkk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cucudq.cn/Article/details/gtgvpzmfgy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.smart0.xyz/Article/details/gtcpyqxgcv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuanzx.com/Article/details/gtzlpaxcey.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gtcawxiaqx.html

[N04] 斐波那契数列
来源：http://dali.yangfankeji.com/Article/details/gthsnsztdh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gtzqrlsguq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daxiang520.top/Article/details/gtpylcdxzq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gtfikizqpz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtadxdzwkr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gtdrudufej.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yanxiufei.cn/Article/details/gtjbgnmkga.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gtsmjaxbkp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtuksgxrqf.html

[N05] 最大公约数
来源：http://dali.svipenyu.cn/Article/details/gtbqruwiyt.html

Py:   math.gcd(a, b)
来源：http://dali.aizwys.cn/Article/details/gttzmqepkg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.0kj1m.cn/Article/details/gtqubftuvs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gtkfxmxccr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgyyxbad.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gogol.net.cn/Article/details/gtmmgmdoci.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.wangdashe.top/Article/details/gtakxlfzfy.html

Ruby: a.gcd(b)
来源：http://dali.ehwqpu.com/Article/details/gtzcaacypo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhengqikj.top/Article/details/gtgicnaidl.html

[N06] 判断回文字符串
来源：http://dali.yangfankeji.com/Article/details/gttsjctahp.html

Py:   s == s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtakuievau.html

PHP:  $s === strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtdiwnmjqo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpyiszggk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtkwpppwzf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigufen.top/Article/details/gtgrzcaepa.html

Go:   // 双指针从两端比较
来源：http://dali.hnxiangtu.top/Article/details/gtrcbqlsvq.html

Ruby: s == s.reverse
来源：http://dali.jinqigufen.top/Article/details/gtgdpmdrhd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gtxcfakibb.html

[N07] 两数之和（返回下标）
来源：http://dali.daxiang520.top/Article/details/gtwwaobpmb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.316326.xyz/Article/details/gtonqdhyce.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sweek.top/Article/details/gtjifcrtou.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gzhubu.top/Article/details/gtkibmwzht.html

TS:   // 手写 Map<string, number>
来源：http://dali.iojbl.cn/Article/details/gtjavxpowr.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gtkuycwnep.html

Go:   // 手写 map[int]int
来源：http://dali.iojbl.cn/Article/details/gtdylusqjw.html

Ruby: // 手写 Hash
来源：http://dali.zhengqikj.top/Article/details/gtzqnztfeg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.andypj.xyz/Article/details/gtotgxtehr.html

[N08] 生成全排列
来源：http://dali.xuetiantiany.cn/Article/details/gtkrcusisl.html

Py:   itertools.permutations(arr)
来源：http://dali.hysaishi.cn/Article/details/gtusqxeplt.html

PHP:  // 手写递归交换
来源：http://dali.yuanzhike.top/Article/details/gthrgxmvqw.html

JS:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptwhsqgq.html

TS:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtaokjedgi.html

Java: // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtlleezqwz.html

Go:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtpcljrhkr.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gttbovlwpy.html

C#:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpuehmnkd.html

[N09] 栈与队列
来源：http://dali.vqdsnc.cn/Article/details/gtpyyrlzyf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gzhubu.top/Article/details/gtxhbmhtcv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gthvpvhbiu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzstmfly.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.svipenyu.cn/Article/details/gtbsyqbftr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gtxnkvxjig.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.meibo888.top/Article/details/gtjxnnsmjf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gtnnmimpnn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenlongwang.top/Article/details/gtitgtxwpz.html

[N10] 链表节点定义
来源：http://dali.guannengcc.top/Article/details/gtknhuclue.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.andypj.xyz/Article/details/gtrqwqbtqj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hfpthk.cn/Article/details/gtcypykvmc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gotoacloud.top/Article/details/gtghopnaqe.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hnqzz.top/Article/details/gtpvhnwbks.html

Java: class Node { int v; Node next; }
来源：http://dali.svipenyu.cn/Article/details/gtgnuguiqm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jqgufenzy.top/Article/details/gtmowabdih.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pycfn.com/Article/details/gtoamocnmd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuanzhike.top/Article/details/gtlxkmevte.html

[N11] 二叉树中序遍历
来源：http://dali.xinyue.icu/Article/details/gtdrnwcxgx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezrvhkix.html

PHP:  // 手写递归函数
来源：http://dali.9152youxi.cn/Article/details/gtiuqssvuq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gtjlvkklig.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspqvhhvh.html

Java: // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gthlnfdzhk.html

Go:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gtckhxjvfe.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hysaishi.cn/Article/details/gtsqljecum.html

C#:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtzvtluchg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xinyue.icu/Article/details/gtamantuau.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhoulong.xyz/Article/details/gtzeaiyscd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gzhubu.top/Article/details/gtchvafcbe.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gtdzcendqd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gtseljgxku.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gtzueznhmo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258.top/Article/details/gtwtbonvwb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhixingplan.top/Article/details/gtdkkeoynw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gtykmmmofj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtqfibabta.html

O. 并发与异步
来源：http://dali.xziqi.cn/Article/details/gtiaezmuhh.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtjiaxekma.html

[O01] 启动一个线程
来源：http://dali.jianghu66.top/Article/details/gtiklmqydn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pengpengdd.cyou/Article/details/gtorsdtmcd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.andypj.xyz/Article/details/gtdxsfmesz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yanxiufei.cn/Article/details/gtzsowzigp.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gtkhiyrjig.html

Java: new Thread(() -> f()).start()
来源：http://dali.feifeiyinyue.top/Article/details/gtfjiomsjx.html

Go:   go f()
来源：http://dali.wangdashe.top/Article/details/gtecxttpen.html

Ruby: Thread.new { f }
来源：http://dali.yonumen.top/Article/details/gtfngeoxpq.html

C#:   Task.Run(() => F());
来源：http://dali.jqgufenzy.top/Article/details/gtccvwterw.html

[O02] 使用线程池
来源：http://dali.jinqigufen.top/Article/details/gtvmabrbpv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hywenlv.cn/Article/details/gtqmflpooy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.9152youxi.cn/Article/details/gthbtwgvsp.html

JS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gteossibkd.html

TS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gtkaobsmfa.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxinkj.top/Article/details/gtztfdimcs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuxming.cn/Article/details/gtboilbujn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinqigufen.top/Article/details/gtatozdwbm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.pycfn.com/Article/details/gtxsvyoovk.html

[O03] 加锁保护共享数据
来源：http://dali.ehwqpu.com/Article/details/gtjuxwtjkp.html

Py:   with lock: shared += 1
来源：http://dali.shuidangran.top/Article/details/gthzwzluwi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuxming.cn/Article/details/gtkpgiwegh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.aizwys.cn/Article/details/gtephlfdpv.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gtrkxwftuz.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gtrgnwjwyn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xinyue.icu/Article/details/gtytxwpuke.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hammf.cn/Article/details/gtramgizjc.html

C#:   lock (gate) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gtywnpyagu.html

[O04] 定义异步函数并等待
来源：http://dali.jlsjyb.cn/Article/details/gtthvqowbv.html

Py:   async def f():⏎    await g()
来源：http://dali.ydzc1.top/Article/details/gtyrrwomre.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.c1oappe.top/Article/details/gtfgjlblaj.html

JS:   async function f() { await g(); }
来源：http://dali.xuanzx.com/Article/details/gtyxdnbiqw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cucudq.cn/Article/details/gtlhrcdgbx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.c1oappe.top/Article/details/gtettvjbao.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ivvv.top/Article/details/gtyzfqnwsu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cashguo.top/Article/details/gtezlzpotw.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258.top/Article/details/gtuqyaxgpn.html

[O05] 并发执行并等待全部完成
来源：http://dali.fzhhl.top/Article/details/gtyredtdcw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgufenzy.top/Article/details/gtbnncuotd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daxiang520.top/Article/details/gtjwvwrnqn.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gtlbzwgnio.html

TS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gtaaxchgiy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj202588.top/Article/details/gtwlpiidsk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dianchejie.cn/Article/details/gtwtdnvozm.html

Ruby: threads.map(&:join)
来源：http://dali.xylfe.cn/Article/details/gtjsvjwhkv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nanxuanxn.top/Article/details/gtxhjkeufu.html

[O06] 使用进程池
来源：http://dali.cucudq.cn/Article/details/gtqkgmdclq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigfzy.top/Article/details/gtfqdwlubr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinqigfzy.top/Article/details/gtgcwywcdj.html

JS:   // child_process / cluster 模块
来源：http://dali.havefunace.top/Article/details/gtythteabh.html

TS:   // child_process / cluster 模块
来源：http://dali.vqdsnc.cn/Article/details/gtwuhirbix.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hywenlv.cn/Article/details/gtgltokwea.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zycfv.cn/Article/details/gteutrjrpj.html

Ruby: // fork 块
来源：http://dali.zhongyouzk.top/Article/details/gtelxgtqvt.html

C#:   Parallel.For
来源：http://dali.tian-w.cn/Article/details/gtwldhxbfp.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtnpamnncu.html

P. 常用工具函数
来源：http://dali.birdmap.top/Article/details/gtydfdwbzi.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtxgzlwhfg.html

[P01] 生成 UUID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdvtonbj.html

Py:   str(uuid.uuid4())
来源：http://dali.yonumen.top/Article/details/gtvuagweqv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgeexprsp.html

JS:   crypto.randomUUID()
来源：http://dali.yj20258888.top/Article/details/gtbvppaknp.html

TS:   crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gtzxinudaj.html

Java: UUID.randomUUID().toString()
来源：http://dali.316326.xyz/Article/details/gtjhrfwczw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuxming.cn/Article/details/gtrdabzjvu.html

Ruby: SecureRandom.uuid
来源：http://dali.ivvv.top/Article/details/gtpjvvptpv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shuidangran.top/Article/details/gtspvbldyc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xuanzx.com/Article/details/gtpkiimjaj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj202588.top/Article/details/gtcxgkuozw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwwpqszp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hywenlv.cn/Article/details/gtbwsnzllj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.smart0.xyz/Article/details/gtmbfdwgob.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtbijvsuav.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhixingplan.top/Article/details/gtzxjpvbxo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.guowangkeji.top/Article/details/gtwmphpbrp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zycfv.cn/Article/details/gtvixjqdmm.html

[P03] 生成短随机字符串
来源：http://dali.gzhubu.top/Article/details/gthmcdeqke.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.iojbl.cn/Article/details/gtolpgvncs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhengqikj.top/Article/details/gtuofsbdph.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.iojbl.cn/Article/details/gtjdmgjcgc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.9152youxi.cn/Article/details/gtboaugizd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sxryk.cn/Article/details/gtszdrkvmk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhoulong.xyz/Article/details/gtopgsofcc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.redwolf501.top/Article/details/gtvvgyxorb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gtuqxahcxm.html

[P04] 求长度
来源：http://dali.wangshuangyany.cn/Article/details/gtweiwjeru.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jiagoushi.top/Article/details/gtnivjrdiv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gttsqrhlej.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gtouataawx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gtsturrlxa.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tian-w.cn/Article/details/gtwtnwtixm.html

Go:   len(arr);  len(m)
来源：http://dali.cqqwz.cn/Article/details/gtdxiwtduu.html

Ruby: x.length;  x.size
来源：http://dali.aibaodan.cn/Article/details/gtwiurvycy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.aibaodan.cn/Article/details/gttxtxggky.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xuanzx.com/Article/details/gtsnjjtnqs.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sxryk.cn/Article/details/gtxdhfmjpk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xylfe.cn/Article/details/gtxyrjnqms.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gtuounxrqr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hongshengwenyu.top/Article/details/gttjntacse.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.wangshuangyany.cn/Article/details/gtcxwkndly.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cdnleiting.top/Article/details/gtxrqivszq.html

Ruby: a == b
来源：http://dali.nanxuanxn.top/Article/details/gtyppfdelk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jqgufenzy.top/Article/details/gtvkvotcyu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cdnleiting.top/Article/details/gtjmfkkala.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yvedp.cn/Article/details/gtwrkblqgn.html

PHP:  if (empty($x)) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyounrhi.html


<!-- 参考信息 -->