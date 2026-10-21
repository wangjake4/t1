代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gtyehsarhn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gtcodhyfyz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.mhx1999.top/Article/details/gtykpggfqn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daria6918.cn/Article/details/gtpgmhckmo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqsqblfl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fengsongda.top/Article/details/gtuyrrzjqu.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtfjnkbuau.html

M. 命令行 / 进程 / 环境
来源：http://dali.guowangkeji.top/Article/details/gtwywuixib.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtnpsqwtjg.html

[M01] 读取命令行参数
来源：http://dali.guannengcc.top/Article/details/gtgxzcuryr.html

Py:   sys.argv[1:]
来源：http://dali.hywenlv.cn/Article/details/gtyhfrkvlm.html

PHP:  $argv;  $argc;
来源：http://dali.xylfe.cn/Article/details/gtvjardcos.html

JS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gtvfmqrzya.html

TS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gthfeloiuz.html

Java: args 数组（main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gtbaemjjit.html

Go:   os.Args[1:]
来源：http://dali.ppjwa.cn/Article/details/gtnecnsdfu.html

Ruby: ARGV
来源：http://dali.zhoulong.xyz/Article/details/gtxxihmdjc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gtuluhtlzu.html

[M02] 读取环境变量
来源：http://dali.hammf.cn/Article/details/gttnlozqtv.html

Py:   os.environ.get("HOME")
来源：http://dali.shuidangran.top/Article/details/gtoqkppjrh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gtvoplotwu.html

JS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtjsiolpdk.html

TS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gtfjvcbyjl.html

Java: System.getenv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtqawdajwf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftdgzwic.html

Ruby: ENV["HOME"]
来源：http://dali.chenjidiqi.icu/Article/details/gthrncnlkc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ivvv.top/Article/details/gtcjwvmqvz.html

[M03] 执行外部命令
来源：http://dali.sysykeji.top/Article/details/gtggvasrpb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.316326.xyz/Article/details/gtfupnpnjy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tian-w.cn/Article/details/gtyzceljsb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gtpaakwbby.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gtcwlgwhim.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tian-w.cn/Article/details/gtgcozofus.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ivvv.top/Article/details/gttcxmqfmu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sweek.top/Article/details/gtvpazcjsa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nwbrower.top/Article/details/gteuvirvcb.html

[M04] 获取当前工作目录
来源：http://dali.ehwqpu.com/Article/details/gtcqsccxgs.html

Py:   os.getcwd()
来源：http://dali.chenlongwang.top/Article/details/gtpvgkqiwz.html

PHP:  getcwd();
来源：http://dali.daria6918.cn/Article/details/gtawqjnjoe.html

JS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gtebshefqe.html

TS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gtkgsafxkv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cucudq.cn/Article/details/gtjgywlgqj.html

Go:   os.Getwd()
来源：http://dali.aizwys.cn/Article/details/gtuiatwtca.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gttvnriasd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxuanxn.top/Article/details/gtnfwtmdxd.html

[M05] 设置退出码
来源：http://dali.yonumen.top/Article/details/gtcqjlulik.html

Py:   sys.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtklfzbwro.html

PHP:  exit(1);
来源：http://dali.fzhhl.top/Article/details/gtihmnlqpc.html

JS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtdufojyfr.html

TS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtlphkxgps.html

Java: System.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtnrakosdr.html

Go:   os.Exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtimvqvtlr.html

Ruby: exit 1
来源：http://dali.svipenyu.cn/Article/details/gtazmtaoie.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fzhhl.top/Article/details/gtpujxayxy.html

[M06] 向标准错误输出
来源：http://dali.dianchejie.cn/Article/details/gtdvhdnjyo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ivvv.top/Article/details/gtkjdjevhr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.svipenyu.cn/Article/details/gtblzqnvbu.html

JS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gtlxapebrj.html

TS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gtpaxxlqlv.html

Java: System.err.println("err")
来源：http://dali.9152youxi.cn/Article/details/gtkvyntdbs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.haohaochexian.top/Article/details/gtlivnbiig.html

Ruby: warn "err"
来源：http://dali.gaohongyu789.top/Article/details/gtcvnugskq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tian-w.cn/Article/details/gtgcbvhqlq.html

[M07] 判断是否为主入口
来源：http://dali.ivvv.top/Article/details/gtlnydnqgz.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxinkj.top/Article/details/gtcrhyhuqy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.birdmap.top/Article/details/gtjwoevnbk.html

JS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gtpovczpkx.html

TS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gtickedghp.html

Java: public static void main(String[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gtrfegtmjf.html

Go:   func main()
来源：http://dali.ehwqpu.com/Article/details/gtlutncaxv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cucudq.cn/Article/details/gtltjunndp.html

C#:   static void Main(string[] args)
来源：http://dali.jqgfzy.top/Article/details/gtmbmfztoq.html

[M08] 获取系统与运行时信息
来源：http://dali.ehwqpu.com/Article/details/gtwgtpzroa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daria6918.cn/Article/details/gtfrunvdxy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhiwuduotai.top/Article/details/gtfdedlsql.html

JS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gtzhnvupeg.html

TS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gtbrxzxobw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigufen.top/Article/details/gtuebbxpbj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxinkj.top/Article/details/gtbfbnsfgl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hfpthk.cn/Article/details/gtnfoxzack.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.birdmap.top/Article/details/gtcsrkpueu.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtaetxhbbz.html

N. 数据结构与算法
来源：http://dali.cucudq.cn/Article/details/gtqmagxttu.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gttryikdkx.html

[N01] 二分查找（有序数组）
来源：http://dali.redwolf501.top/Article/details/gtojxwjayy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.havefunace.top/Article/details/gtoawzahuk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gtupafbnkr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gtsuhcnpcx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtfsoalywn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cashguo.top/Article/details/gtaskumxvb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtndhzasxg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jyoumei.cn/Article/details/gtqbypfbzl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtyjcpyudn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenzaomai.com/Article/details/gtixjabegc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gtcbysyluv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gttszkilps.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gtalqvrbwk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gtqqmdshzc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.svipenyu.cn/Article/details/gtqqhjtalc.html

Go:   slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgruqhanr.html

Ruby: arr.sort
来源：http://dali.shzxlz.cn/Article/details/gtoayewdgm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xziqi.cn/Article/details/gtiqqgpwwr.html

[N03] 快速排序（分治示例）
来源：http://dali.tanke756.top/Article/details/gtvymitqra.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pengpengdd.cyou/Article/details/gtybuaaeuj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jqgfzy.top/Article/details/gtfhcuveef.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuetiantiany.cn/Article/details/gthhmeqech.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gtfqqtkrxm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jianghu66.top/Article/details/gtzcxvinzc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.pycfn.com/Article/details/gtzbpbdrzo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pengpengdd.cyou/Article/details/gtwvgrciqc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nwbrower.top/Article/details/gtoqfmnjmk.html

[N04] 斐波那契数列
来源：http://dali.xinyue.icu/Article/details/gtzfaixqgt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gtbbamaepj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqzqxyti.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gtjxrwoznl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtpwjqxovs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hammf.cn/Article/details/gtwtzvztua.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhengqikj.top/Article/details/gtkcsckzaz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtycboajws.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gtyovsaiyg.html

[N05] 最大公约数
来源：http://dali.jianghu66.top/Article/details/gteqefufoq.html

Py:   math.gcd(a, b)
来源：http://dali.tian-w.cn/Article/details/gtnuyvnrnf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ehwqpu.com/Article/details/gtkcsuizrr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gtjofiowir.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.meibo888.top/Article/details/gtmwaqcsnp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pengpengdd.cyou/Article/details/gtnhnmzlrj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.smart0.xyz/Article/details/gtnqyxfauw.html

Ruby: a.gcd(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtqplucthj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhoulong.xyz/Article/details/gttimxngjb.html

[N06] 判断回文字符串
来源：http://dali.aizwys.cn/Article/details/gtdorxifgy.html

Py:   s == s[::-1]
来源：http://dali.nwbrower.top/Article/details/gtlqtwteov.html

PHP:  $s === strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gtpgunilzk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtrybtdzjy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtxawrpasp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sufxvd.cn/Article/details/gtlyltblki.html

Go:   // 双指针从两端比较
来源：http://dali.cheryme.top/Article/details/gthctikgys.html

Ruby: s == s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gtmkexyagy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvupcyyf.html

[N07] 两数之和（返回下标）
来源：http://dali.zhoulong.xyz/Article/details/gtzyppkiuw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.316326.xyz/Article/details/gtrinavnmu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pengpengdd.cyou/Article/details/gtohzfgwnn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgufenzy.top/Article/details/gtlyupjfmn.html

TS:   // 手写 Map<string, number>
来源：http://dali.ehwqpu.com/Article/details/gtttcldfwt.html

Java: // 手写 HashMap
来源：http://dali.ybcxt.top/Article/details/gtjypzxrdq.html

Go:   // 手写 map[int]int
来源：http://dali.guannengcc.top/Article/details/gthnwuvpfl.html

Ruby: // 手写 Hash
来源：http://dali.aibaodan.cn/Article/details/gtsqicvvpd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xylfe.cn/Article/details/gtgydtpros.html

[N08] 生成全排列
来源：http://dali.smart0.xyz/Article/details/gtpfikwjqw.html

Py:   itertools.permutations(arr)
来源：http://dali.wangdashe.top/Article/details/gtfozhydct.html

PHP:  // 手写递归交换
来源：http://dali.zhiwuduotai.top/Article/details/gteiqqqtwb.html

JS:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtvaxzktka.html

TS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtweyrazry.html

Java: // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtdljncbfb.html

Go:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqvhtqoj.html

Ruby: arr.permutation.to_a
来源：http://dali.jianghu66.top/Article/details/gtscpzdcua.html

C#:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtseofgurv.html

[N09] 栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gtjxigtotm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtnlhlnikw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaiirebau.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtrtzrzeri.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.andypj.xyz/Article/details/gttyxwllbo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shangyingyoupin.top/Article/details/gtnsjrxojd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pengpengdd.cyou/Article/details/gtyqctmlsj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkplavye.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj202588.top/Article/details/gtxttbpmmv.html

[N10] 链表节点定义
来源：http://dali.nanxuanxn.top/Article/details/gttnarfsgl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sweek.top/Article/details/gtwzqxnnhy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sysykeji.top/Article/details/gtknrgnlzb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.9152youxi.cn/Article/details/gtgkrnlhkh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guannengcc.top/Article/details/gtvewzdfrk.html

Java: class Node { int v; Node next; }
来源：http://dali.xuetiantiany.cn/Article/details/gtmbfzzbby.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pycfn.com/Article/details/gtrbgkbzxj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.quarkkingdee.top/Article/details/gtjxrnsldf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhxllbcr.html

[N11] 二叉树中序遍历
来源：http://dali.shzxlz.cn/Article/details/gtvtpbrubc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nanxuanxn.top/Article/details/gtiutklbki.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gtfxrxgvhn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gtpnlhbidr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gtapsvlgcg.html

Java: // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtfxlmppmf.html

Go:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gtmfnbhnzs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.andypj.xyz/Article/details/gtcsscnewj.html

C#:   // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gtxbetmnab.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gaohongyu789.top/Article/details/gtjlyrmqrr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ppjwa.cn/Article/details/gtgllmwbxl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gtbigonmav.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gtaikzljhd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gtlluptexk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gtwoksbhes.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dashuyun.cn/Article/details/gtjwchoudj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuxming.cn/Article/details/gtzvfgjcia.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gtchfmpuqt.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gthaywhney.html

O. 并发与异步
来源：http://dali.jqgufenzy.top/Article/details/gttwefqrol.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtllpdhjzr.html

[O01] 启动一个线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyregnfej.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.quarkkingdee.top/Article/details/gteihiabeb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.9152youxi.cn/Article/details/gtucdieitz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.andypj.xyz/Article/details/gtcjwfrqii.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gtfjgsudad.html

Java: new Thread(() -> f()).start()
来源：http://dali.cqqwz.cn/Article/details/gtlkbzczvt.html

Go:   go f()
来源：http://dali.gzhubu.top/Article/details/gtaaglrjuy.html

Ruby: Thread.new { f }
来源：http://dali.chenzaomai.com/Article/details/gtiweszlbx.html

C#:   Task.Run(() => F());
来源：http://dali.feifeiyinyue.top/Article/details/gtjevlyqkh.html

[O02] 使用线程池
来源：http://dali.gaohongyu789.top/Article/details/gtnomituwi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.redwolf501.top/Article/details/gtgfqtjazm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.9152youxi.cn/Article/details/gtuwxpfnsi.html

JS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gtcscqtllf.html

TS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gtrcrmlaei.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daxiang520.top/Article/details/gtwttaxvvy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yanxiufei.cn/Article/details/gtewzawacj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuetiantiany.cn/Article/details/gtsmnzvlpe.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tian-w.cn/Article/details/gtmxdcewji.html

[O03] 加锁保护共享数据
来源：http://dali.daxiang520.top/Article/details/gttrrsgpqj.html

Py:   with lock: shared += 1
来源：http://dali.xziqi.cn/Article/details/gtmrhwbbor.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnxiangtu.top/Article/details/gtjosklejk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jiagoushi.top/Article/details/gtxhqvsvxv.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gtilkrfhnb.html

Java: synchronized (this) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gtditroqpa.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fengsongda.top/Article/details/gtekcjsbhd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yvedp.cn/Article/details/gtuoshpwoa.html

C#:   lock (gate) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gtjjafbcst.html

[O04] 定义异步函数并等待
来源：http://dali.nanxinkj.top/Article/details/gtaufwktqq.html

Py:   async def f():⏎    await g()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvcsopfe.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gtnamplgho.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gtiymcqskh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupiuitwy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258.top/Article/details/gteqmvcrlj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhengqikj.top/Article/details/gtszchqlis.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigufen.top/Article/details/gtydbqtvur.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigfzy.top/Article/details/gteuvhqxoe.html

[O05] 并发执行并等待全部完成
来源：http://dali.ivvv.top/Article/details/gtzbtuilip.html

Py:   asyncio.gather(*tasks)
来源：http://dali.snrcjt.cn/Article/details/gtrbtsraxu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tanke756.top/Article/details/gtmccsgvfa.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwzzzaas.html

TS:   await Promise.all(tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtikdyjndy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.svipenyu.cn/Article/details/gtmtgooexw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nwbrower.top/Article/details/gtodhkalfa.html

Ruby: threads.map(&:join)
来源：http://dali.fengsongda.top/Article/details/gthglyiiqw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigufen.top/Article/details/gtjqwtlmor.html

[O06] 使用进程池
来源：http://dali.chenjidiqi.icu/Article/details/gtencquwvz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gaohongyu789.top/Article/details/gttymkamcp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhixingplan.top/Article/details/gtdqedpolp.html

JS:   // child_process / cluster 模块
来源：http://dali.hysaishi.cn/Article/details/gtrhnbjkci.html

TS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gtgvkinkzf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zycfv.cn/Article/details/gtumbpojyb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhixingplan.top/Article/details/gtyjcoghnb.html

Ruby: // fork 块
来源：http://dali.haohaochexian.top/Article/details/gtwguljppa.html

C#:   Parallel.For
来源：http://dali.yj202588.top/Article/details/gtalnrdlea.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtksrnhaoa.html

P. 常用工具函数
来源：http://dali.hammf.cn/Article/details/gtnlpbrvaw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtckystloi.html

[P01] 生成 UUID
来源：http://dali.zhoulong.xyz/Article/details/gthhwupgtx.html

Py:   str(uuid.uuid4())
来源：http://dali.tian-w.cn/Article/details/gtgxqxczvr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nwbrower.top/Article/details/gtpqlnusss.html

JS:   crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gtseayqtlz.html

TS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtmdqjvaxz.html

Java: UUID.randomUUID().toString()
来源：http://dali.haohaochexian.top/Article/details/gttjbjqfze.html

Go:   // 用 github.com/google/uuid
来源：http://dali.pengpengdd.cyou/Article/details/gtcvzzmvsk.html

Ruby: SecureRandom.uuid
来源：http://dali.zycfv.cn/Article/details/gtbwybryau.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhwtnwee.html

[P02] MD5 / SHA256 摘要
来源：http://dali.feifeiyinyue.top/Article/details/gtidqctjxg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tian-w.cn/Article/details/gtoxgmbvjg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hywenlv.cn/Article/details/gtysxqrunm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhongyouzk.top/Article/details/gtufwobzmr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sufxvd.cn/Article/details/gtukvvgolx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gtyocdhqaj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zycfv.cn/Article/details/gtatymvyoj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.pycfn.com/Article/details/gtgeikdxqr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gogol.net.cn/Article/details/gtmljgxbwi.html

[P03] 生成短随机字符串
来源：http://dali.nwbrower.top/Article/details/gtfdnmkhlz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cqqwz.cn/Article/details/gtbriydfjr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuxming.cn/Article/details/gtekuxelsg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuanzhike.top/Article/details/gthkkcgeth.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gttvcedhhv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xylfe.cn/Article/details/gtlepkvepb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.daxiang520.top/Article/details/gtrzjfyifz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnxiangtu.top/Article/details/gtuzaopeol.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xziqi.cn/Article/details/gtvamuuntl.html

[P04] 求长度
来源：http://dali.yueranfly.top/Article/details/gtkpbvkzkk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.mhx1999.top/Article/details/gtfdvucacl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gttzsmgjbn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gtlulgbujl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ivvv.top/Article/details/gtmyultfqq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.fzhhl.top/Article/details/gtfoqazame.html

Go:   len(arr);  len(m)
来源：http://dali.guowangkeji.top/Article/details/gteraxbicy.html

Ruby: x.length;  x.size
来源：http://dali.yonumen.top/Article/details/gtncnlkfuw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtosbvweib.html

[P05] 判断两个对象内容是否相等
来源：http://dali.vqdsnc.cn/Article/details/gtycjskdzd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhryggpr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.guowangkeji.top/Article/details/gtuzjagpab.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guannengcc.top/Article/details/gtiskuuwfr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jiagoushi.top/Article/details/gtfuiowmqk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tianlin.xyz/Article/details/gtbhbbjzgf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.daria6918.cn/Article/details/gtjcrchrta.html

Ruby: a == b
来源：http://dali.pycfn.com/Article/details/gtabvayfma.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yanxiufei.cn/Article/details/gtvhknaeak.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.guowangkeji.top/Article/details/gtwlmkiwcn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nwbrower.top/Article/details/gtmkrulmjj.html

PHP:  if (empty($x)) {}
来源：http://dali.xuanzx.com/Article/details/gtyttwsisr.html


<!-- 参考信息 -->