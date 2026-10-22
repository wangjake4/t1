代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtvdikhiia.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gtgucircyd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.meibo888.top/Article/details/gtifivkpgf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yonumen.top/Article/details/gtevfzjpoq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gtkeazzpkk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtxmskwfoc.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtzsrlejct.html

M. 命令行 / 进程 / 环境
来源：http://dali.yuxming.cn/Article/details/gtbbcifmlf.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtlvmxfzbs.html

[M01] 读取命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtknmohrmw.html

Py:   sys.argv[1:]
来源：http://dali.dashuyun.cn/Article/details/gtmnnljuqc.html

PHP:  $argv;  $argc;
来源：http://dali.gzhubu.top/Article/details/gtmnciaptf.html

JS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gtjsgkmapm.html

TS:   process.argv.slice(2)
来源：http://dali.shzxlz.cn/Article/details/gtpjxopuie.html

Java: args 数组（main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gtfdnovvrl.html

Go:   os.Args[1:]
来源：http://dali.aibaodan.cn/Article/details/gtexnrtfzc.html

Ruby: ARGV
来源：http://dali.sysykeji.top/Article/details/gtetukicnp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gtgfaizdgs.html

[M02] 读取环境变量
来源：http://dali.jlsjyb.cn/Article/details/gtrmqmhufr.html

Py:   os.environ.get("HOME")
来源：http://dali.yueranfly.top/Article/details/gturanqjgi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gtjkmlbymm.html

JS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gtxwlycwxo.html

TS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gtpojexsjp.html

Java: System.getenv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtoqkpstjy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtexzgpwgf.html

Ruby: ENV["HOME"]
来源：http://dali.guannengcc.top/Article/details/gtzdkqsijk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtwtvaeuvp.html

[M03] 执行外部命令
来源：http://dali.dashuyun.cn/Article/details/gtzovdsepo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yvedp.cn/Article/details/gtcyonjehb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenlongwang.top/Article/details/gtmaaauefa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gtngnrhgww.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gteetazasb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shzxlz.cn/Article/details/gtmcfipaip.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmnxlfrb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkygryjf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hfpthk.cn/Article/details/gthmcxmwgn.html

[M04] 获取当前工作目录
来源：http://dali.shangyingyoupin.top/Article/details/gtzdpkpzpa.html

Py:   os.getcwd()
来源：http://dali.nanxinkj.top/Article/details/gtknqhrxap.html

PHP:  getcwd();
来源：http://dali.daria6918.cn/Article/details/gtzjuhuvqc.html

JS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gtevhvkfjc.html

TS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gtcqvmvocp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.fengsongda.top/Article/details/gtzfceijti.html

Go:   os.Getwd()
来源：http://dali.yj20258888.top/Article/details/gtjvaucujy.html

Ruby: Dir.pwd
来源：http://dali.daria6918.cn/Article/details/gtrowvutzp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zycfv.cn/Article/details/gtsioriemb.html

[M05] 设置退出码
来源：http://dali.bjfxy.top/Article/details/gtowzlynaz.html

Py:   sys.exit(1)
来源：http://dali.zycfv.cn/Article/details/gttsfemdec.html

PHP:  exit(1);
来源：http://dali.ydzc1.top/Article/details/gtmrcmnzxe.html

JS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtrrergnsf.html

TS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtfwnrayvj.html

Java: System.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtjowhxyzx.html

Go:   os.Exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtqiybcqdj.html

Ruby: exit 1
来源：http://dali.jqgfzy.top/Article/details/gtoimizxen.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.bjfxy.top/Article/details/gteevhcjos.html

[M06] 向标准错误输出
来源：http://dali.c1oappe.top/Article/details/gtvtcamgdb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fzhhl.top/Article/details/gtxgxxabfz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258.top/Article/details/gtxegavmto.html

JS:   console.error("err")
来源：http://dali.xylfe.cn/Article/details/gtteamvojk.html

TS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gtrkeylwdn.html

Java: System.err.println("err")
来源：http://dali.jianghu66.top/Article/details/gtfogsewgj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgfzy.top/Article/details/gtluokdxjb.html

Ruby: warn "err"
来源：http://dali.jqgfzy.top/Article/details/gtahhsdegy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqrioija.html

[M07] 判断是否为主入口
来源：http://dali.sweek.top/Article/details/gtrybudkpa.html

Py:   if __name__ == "__main__":
来源：http://dali.xylfe.cn/Article/details/gtkdmaxblf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cdnleiting.top/Article/details/gtcguckprt.html

JS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtaifdtsrr.html

TS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gtxdvokaus.html

Java: public static void main(String[] args)
来源：http://dali.hysaishi.cn/Article/details/gthgxepaoq.html

Go:   func main()
来源：http://dali.ivvv.top/Article/details/gtuxobuwtf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenjidiqi.icu/Article/details/gtwwpagpzp.html

C#:   static void Main(string[] args)
来源：http://dali.xinyue.icu/Article/details/gtkjhmelyl.html

[M08] 获取系统与运行时信息
来源：http://dali.sysykeji.top/Article/details/gtgpzvkiox.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zdqjudy.top/Article/details/gtsviolbhu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zycfv.cn/Article/details/gtqjoyquux.html

JS:   process.platform;  process.version
来源：http://dali.zhixingplan.top/Article/details/gtxtaietxl.html

TS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gtcmndxxdg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangdashe.top/Article/details/gtdiccsomd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpuaymluv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xinyue.icu/Article/details/gtbkqkcakv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.meibo888.top/Article/details/gtpkclosoq.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtskkqslpd.html

N. 数据结构与算法
来源：http://dali.zhengqikj.top/Article/details/gtauanwkzz.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtomruxthi.html

[N01] 二分查找（有序数组）
来源：http://dali.xuanzx.com/Article/details/gtxifywjfm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtelvqhqyj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tanke756.top/Article/details/gtgicwgqtx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtcmgtaiwt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtjycnyqvy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gttkztdhtx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtugccvesd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jyoumei.cn/Article/details/gtpdxgzxlq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtpeejwsbz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xziqi.cn/Article/details/gtcvixjrgy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gtmrhwhgjp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jianghu66.top/Article/details/gtyyfnpxuv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gtjwqeujjn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtpskesivo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sweek.top/Article/details/gtqsfnuafn.html

Go:   slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gtiimdvyss.html

Ruby: arr.sort
来源：http://dali.xinyue.icu/Article/details/gtzrmbvmng.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.kuanghao11.cn/Article/details/gttouthljf.html

[N03] 快速排序（分治示例）
来源：http://dali.jyoumei.cn/Article/details/gtszrhjqbe.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yvedp.cn/Article/details/gtqcgmirfl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.haohaochexian.top/Article/details/gtqvabekhy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gaohongyu789.top/Article/details/gtiybbbyer.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gtrdwugpxz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.havefunace.top/Article/details/gtkszoguat.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenzaomai.com/Article/details/gtllspnfba.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.havefunace.top/Article/details/gtwpjdablk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.meibo888.top/Article/details/gtruchkxef.html

[N04] 斐波那契数列
来源：http://dali.gotoacloud.top/Article/details/gtafglboxr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtekklmwgu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenjidiqi.icu/Article/details/gtpigqwdyj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtgepkbcqs.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gtvbrozsem.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gtaiajogvk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ehwqpu.com/Article/details/gtkfqgakiu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsktgztxq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gtjopvmzto.html

[N05] 最大公约数
来源：http://dali.aibaodan.cn/Article/details/gtfuzhdnxa.html

Py:   math.gcd(a, b)
来源：http://dali.ydzc1.top/Article/details/gtcrvqhtin.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dashuyun.cn/Article/details/gtnembmhwh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmedlfuds.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gtxozdikwx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xylfe.cn/Article/details/gtbvdwgmuo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdhjjmhl.html

Ruby: a.gcd(b)
来源：http://dali.cqqwz.cn/Article/details/gtxixgwnua.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenjidiqi.icu/Article/details/gtakqizyvy.html

[N06] 判断回文字符串
来源：http://dali.gaohongyu789.top/Article/details/gtjjuziydx.html

Py:   s == s[::-1]
来源：http://dali.zhongyouzk.top/Article/details/gtdkwdzopb.html

PHP:  $s === strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gtrrytznix.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtzldiuibs.html

TS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtcvxmylyq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hysaishi.cn/Article/details/gtxeozhtrr.html

Go:   // 双指针从两端比较
来源：http://dali.guannengcc.top/Article/details/gtraaemhkh.html

Ruby: s == s.reverse
来源：http://dali.hywenlv.cn/Article/details/gtxstabhav.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gteoheeowz.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258.top/Article/details/gtwcnwuujb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yanxiufei.cn/Article/details/gtdlgvrylm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ybcxt.top/Article/details/gtnuwrodfv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.snrcjt.cn/Article/details/gthzqyemaj.html

TS:   // 手写 Map<string, number>
来源：http://dali.cqqwz.cn/Article/details/gttpboqvwm.html

Java: // 手写 HashMap
来源：http://dali.kuanghao11.cn/Article/details/gtymkoxufl.html

Go:   // 手写 map[int]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtkkygnz.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkmfuadn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gtqzypamla.html

[N08] 生成全排列
来源：http://dali.zhoulong.xyz/Article/details/gtbiwduras.html

Py:   itertools.permutations(arr)
来源：http://dali.tian-w.cn/Article/details/gtwwzaydkj.html

PHP:  // 手写递归交换
来源：http://dali.nanxinkj.top/Article/details/gtvxtqgrjj.html

JS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gthjkuoptq.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnzfqecj.html

Java: // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtznbofbzd.html

Go:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtwpglhfih.html

Ruby: arr.permutation.to_a
来源：http://dali.yuxming.cn/Article/details/gtxnacttbz.html

C#:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtfkfarfrt.html

[N09] 栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gtkiqwlvwa.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xylfe.cn/Article/details/gtgghruchu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gthisvcteu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gtxgwpiwkw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhengqikj.top/Article/details/gtdpvjlivh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhixingplan.top/Article/details/gtidwmaqpd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shzxlz.cn/Article/details/gtqtmouine.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gtougzqqde.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jyoumei.cn/Article/details/gtobvypmqp.html

[N10] 链表节点定义
来源：http://dali.ppjwa.cn/Article/details/gtpxyvjaih.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zycfv.cn/Article/details/gtwjmdghyz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jianghu66.top/Article/details/gtmuypaaze.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhoulong.xyz/Article/details/gtwhravfpi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guannengcc.top/Article/details/gtsfojwvrx.html

Java: class Node { int v; Node next; }
来源：http://dali.dianchejie.cn/Article/details/gtdnpqiloz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhoulong.xyz/Article/details/gtwynhqena.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xuetiantiany.cn/Article/details/gtemrnkhpe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ppjwa.cn/Article/details/gtexwftryh.html

[N11] 二叉树中序遍历
来源：http://dali.ydzc1.top/Article/details/gtwhkrxvkl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hywenlv.cn/Article/details/gtehfeetlx.html

PHP:  // 手写递归函数
来源：http://dali.svipenyu.cn/Article/details/gtpgenuhlv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gtndyeojuw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gtifxyyirn.html

Java: // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtgirmqjuv.html

Go:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gtpaonxzkn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.snrcjt.cn/Article/details/gtpaqgnrtx.html

C#:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtmwmjkmnk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jiagoushi.top/Article/details/gtacyyjnon.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.bjfxy.top/Article/details/gtikajdioz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sxryk.cn/Article/details/gtzgamrqvs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cucudq.cn/Article/details/gtwgqqhwyr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgfzy.top/Article/details/gtvqvpfpps.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gtsxkrjrvk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.havefunace.top/Article/details/gtdavpziju.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xinyue.icu/Article/details/gtuzddgrrf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gtoxayclxe.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtwmhoholf.html

O. 并发与异步
来源：http://dali.shangyingyoupin.top/Article/details/gtiilcxisg.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtqinzzeqg.html

[O01] 启动一个线程
来源：http://dali.cheryme.top/Article/details/gtdbxijjrw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gogol.net.cn/Article/details/gtrbracfya.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuanzhike.top/Article/details/gttterkohy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hysaishi.cn/Article/details/gtzomlxhrd.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gtisoljusd.html

Java: new Thread(() -> f()).start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvbhfmas.html

Go:   go f()
来源：http://dali.ydzc1.top/Article/details/gtcqtzrpdu.html

Ruby: Thread.new { f }
来源：http://dali.iojbl.cn/Article/details/gtfokxkevc.html

C#:   Task.Run(() => F());
来源：http://dali.sufxvd.cn/Article/details/gtkjgjggog.html

[O02] 使用线程池
来源：http://dali.hywenlv.cn/Article/details/gtdmonkcfd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258.top/Article/details/gtvttfdonu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cqqwz.cn/Article/details/gtfhewmbwy.html

JS:   // worker_threads 线程池
来源：http://dali.kuanghao11.cn/Article/details/gtldaenppn.html

TS:   // worker_threads 线程池
来源：http://dali.chenlongwang.top/Article/details/gtvdsrpsqb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.9152youxi.cn/Article/details/gthybdkoeo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhiwuduotai.top/Article/details/gtpxlnawjf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yonumen.top/Article/details/gtpvctthmh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jianghu66.top/Article/details/gtbykhsvnt.html

[O03] 加锁保护共享数据
来源：http://dali.havefunace.top/Article/details/gthlvzhgpk.html

Py:   with lock: shared += 1
来源：http://dali.xziqi.cn/Article/details/gtswjzvlsx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgufenzy.top/Article/details/gtiwtcxaya.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhoulong.xyz/Article/details/gtftrbdcnm.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gtbosdkzak.html

Java: synchronized (this) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gtnmvnkzet.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xinyue.icu/Article/details/gtckiqywcq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shzxlz.cn/Article/details/gttddspyok.html

C#:   lock (gate) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gtajqtzdzf.html

[O04] 定义异步函数并等待
来源：http://dali.quarkkingdee.top/Article/details/gtnthkhtbo.html

Py:   async def f():⏎    await g()
来源：http://dali.daxiang520.top/Article/details/gtmyrtvhgg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gzhubu.top/Article/details/gtxqhfbbuk.html

JS:   async function f() { await g(); }
来源：http://dali.daria6918.cn/Article/details/gtwpkmaora.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gtkimvuitg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sysykeji.top/Article/details/gtzapxvffi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigfzy.top/Article/details/gtegitqion.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.havefunace.top/Article/details/gtxjxtpgwp.html

C#:   async Task F() { await G(); }
来源：http://dali.jianghu66.top/Article/details/gtnwuqctki.html

[O05] 并发执行并等待全部完成
来源：http://dali.redwolf501.top/Article/details/gtyggwcjas.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nwbrower.top/Article/details/gtbjwjrgfb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nwbrower.top/Article/details/gtaizmhurh.html

JS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gttogjpzgf.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258.top/Article/details/gtfijodbgi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.aizwys.cn/Article/details/gtpodvdfsp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yongpay.top/Article/details/gtzrowugeo.html

Ruby: threads.map(&:join)
来源：http://dali.guowangkeji.top/Article/details/gtdfkjrwkr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.aizwys.cn/Article/details/gtisczozil.html

[O06] 使用进程池
来源：http://dali.xuetiantiany.cn/Article/details/gttztvljye.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gaohongyu789.top/Article/details/gtwypusomu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sweek.top/Article/details/gtfjnqbwzm.html

JS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gtegflryna.html

TS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gtvsepvruo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hnxiangtu.top/Article/details/gtsrgkrsvf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqaiaasbz.html

Ruby: // fork 块
来源：http://dali.hywenlv.cn/Article/details/gtmbmpjytz.html

C#:   Parallel.For
来源：http://dali.daxiang520.top/Article/details/gthmrxisei.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gttxluxayu.html

P. 常用工具函数
来源：http://dali.gogol.net.cn/Article/details/gtnjikhwzw.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtjlxrhqof.html

[P01] 生成 UUID
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbhakncj.html

Py:   str(uuid.uuid4())
来源：http://dali.havefunace.top/Article/details/gtzdegtgwm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sweek.top/Article/details/gtbptfwmzp.html

JS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gtimyhfakh.html

TS:   crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gtgyfvtsuv.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbzxmzla.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xuanzx.com/Article/details/gtzbghybih.html

Ruby: SecureRandom.uuid
来源：http://dali.tianlin.xyz/Article/details/gtoszaqpsc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ppjwa.cn/Article/details/gtnzlhdloq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangshuangyany.cn/Article/details/gtitjhuvoo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hnxiangtu.top/Article/details/gtmzfjkmqr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sweek.top/Article/details/gtciefgjnj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhixingplan.top/Article/details/gtgzzltyyn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzoxfwupw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtwrnjhtgh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj202588.top/Article/details/gtpcmpctfd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ydzc1.top/Article/details/gtpgysyymr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yanxiufei.cn/Article/details/gtynrsybef.html

[P03] 生成短随机字符串
来源：http://dali.sufxvd.cn/Article/details/gtofbhsigp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.andypj.xyz/Article/details/gttyqkxryc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hysaishi.cn/Article/details/gtpvxwpamo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gtdbqiqojb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.kuanghao11.cn/Article/details/gtctixmsoq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.0kj1m.cn/Article/details/gtelaafdys.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cqqwz.cn/Article/details/gtkoboijmy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdupzsji.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhixingplan.top/Article/details/gtbmgadamn.html

[P04] 求长度
来源：http://dali.gotoacloud.top/Article/details/gtuxsdwprs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nwbrower.top/Article/details/gtugfvazen.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtncepivhk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhongyouzk.top/Article/details/gtmttrmtir.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gtxvodgrcu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigfzy.top/Article/details/gtzfymodel.html

Go:   len(arr);  len(m)
来源：http://dali.guowangkeji.top/Article/details/gtmduruyqr.html

Ruby: x.length;  x.size
来源：http://dali.bjfxy.top/Article/details/gtqqzqmsnu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gtkphwepce.html

[P05] 判断两个对象内容是否相等
来源：http://dali.pengpengdd.cyou/Article/details/gtzaokkrmd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258.top/Article/details/gtwyfwawwv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhixingplan.top/Article/details/gtkrpkjxcq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sysykeji.top/Article/details/gtixiipiwz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gtdwxheozx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nanxuanxn.top/Article/details/gtrghvfgan.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cdnleiting.top/Article/details/gtesvbysyn.html

Ruby: a == b
来源：http://dali.feifeiyinyue.top/Article/details/gtfclvzage.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenlongwang.top/Article/details/gtddhnjvlf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xziqi.cn/Article/details/gtaniqjeac.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yonumen.top/Article/details/gtmareiivx.html

PHP:  if (empty($x)) {}
来源：http://dali.haohaochexian.top/Article/details/gtoyetxxha.html


<!-- 参考信息 -->