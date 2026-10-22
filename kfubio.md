代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gtqzpqqcwd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gtodchgtax.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sysykeji.top/Article/details/gtkullllai.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhengqikj.top/Article/details/gtyxqikdkx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jqgfzy.top/Article/details/gtfdooizaf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtnbbnbtdq.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtuhvdkazo.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinghuilouyu.cn/Article/details/gtoyrsanyk.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtemhthehw.html

[M01] 读取命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgenevwa.html

Py:   sys.argv[1:]
来源：http://dali.andypj.xyz/Article/details/gtnioxzhul.html

PHP:  $argv;  $argc;
来源：http://dali.gogol.net.cn/Article/details/gtkkuksmiv.html

JS:   process.argv.slice(2)
来源：http://dali.guowangkeji.top/Article/details/gtgooislyj.html

TS:   process.argv.slice(2)
来源：http://dali.zhongyouzk.top/Article/details/gtirwulave.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gtttjxymiu.html

Go:   os.Args[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gtfthxtjzt.html

Ruby: ARGV
来源：http://dali.hnxiangtu.top/Article/details/gtdhupyfdm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gtwjohjfna.html

[M02] 读取环境变量
来源：http://dali.yuanzhike.top/Article/details/gtsykwdfwu.html

Py:   os.environ.get("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtedirxuqf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gtjbgwhfgc.html

JS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gtoqkiemkm.html

TS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gtlpczfgjy.html

Java: System.getenv("HOME")
来源：http://dali.birdmap.top/Article/details/gtdkmmybyz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtcdflowky.html

Ruby: ENV["HOME"]
来源：http://dali.sufxvd.cn/Article/details/gtcftnrzhn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yonumen.top/Article/details/gtkwerwrvg.html

[M03] 执行外部命令
来源：http://dali.gogol.net.cn/Article/details/gtotxmmaxj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuxming.cn/Article/details/gtpauqashv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.feifeiyinyue.top/Article/details/gtfigzezbq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gtrfomigim.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gtolrkyvzr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtueeidpdr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj202588.top/Article/details/gtohqdgkqm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shuidangran.top/Article/details/gtrphwnnxv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jiagoushi.top/Article/details/gtfxxibvek.html

[M04] 获取当前工作目录
来源：http://dali.cashguo.top/Article/details/gtabualrnp.html

Py:   os.getcwd()
来源：http://dali.andypj.xyz/Article/details/gtggmfehpj.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gtmhklsmrm.html

JS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gtnesujcoe.html

TS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gtfchvvuab.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daxiang520.top/Article/details/gtumnhvuyg.html

Go:   os.Getwd()
来源：http://dali.havefunace.top/Article/details/gtqlwivnwf.html

Ruby: Dir.pwd
来源：http://dali.cdnleiting.top/Article/details/gtatgqrysx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.c1oappe.top/Article/details/gtznznrdqe.html

[M05] 设置退出码
来源：http://dali.sweek.top/Article/details/gtveaqarib.html

Py:   sys.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtkftbclua.html

PHP:  exit(1);
来源：http://dali.jianghu66.top/Article/details/gtlvhisdht.html

JS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtzlfidcac.html

TS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gthvzslfxa.html

Java: System.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtxwroedfi.html

Go:   os.Exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtjhszenpx.html

Ruby: exit 1
来源：http://dali.ivvv.top/Article/details/gtxtjlkixx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.andypj.xyz/Article/details/gtkzsrdcsm.html

[M06] 向标准错误输出
来源：http://dali.cqqwz.cn/Article/details/gtnlohggdv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gtigrjltyu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yonumen.top/Article/details/gtofijrxqc.html

JS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gtpufwdqpz.html

TS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtgcamivtn.html

Java: System.err.println("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtdqmeheeo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gtqcarkfwx.html

Ruby: warn "err"
来源：http://dali.aibaodan.cn/Article/details/gtzqtcoqev.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tianlin.xyz/Article/details/gtyyialaap.html

[M07] 判断是否为主入口
来源：http://dali.hysaishi.cn/Article/details/gttsjtzfnt.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxsnyomf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.andypj.xyz/Article/details/gtkveihmsf.html

JS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gtajdxdoij.html

TS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtmubgnfeo.html

Java: public static void main(String[] args)
来源：http://dali.chenlongwang.top/Article/details/gtddrrrgew.html

Go:   func main()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfazyomt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gaohongyu789.top/Article/details/gttscrpmce.html

C#:   static void Main(string[] args)
来源：http://dali.zdqjudy.top/Article/details/gtyufhszdu.html

[M08] 获取系统与运行时信息
来源：http://dali.chenzaomai.com/Article/details/gthkwlymny.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj202588.top/Article/details/gthkflwuyn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmqpgeib.html

JS:   process.platform;  process.version
来源：http://dali.zhengqikj.top/Article/details/gtmtelpcep.html

TS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gttudzynzx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuxming.cn/Article/details/gtjpbvdmkn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fzhhl.top/Article/details/gtovpjaava.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.svipenyu.cn/Article/details/gtzruxdopn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.havefunace.top/Article/details/gtlpcpjedz.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtthvxstep.html

N. 数据结构与算法
来源：http://dali.sxryk.cn/Article/details/gtodtgiykm.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gttstsqzit.html

[N01] 二分查找（有序数组）
来源：http://dali.hnqzz.top/Article/details/gtjiggxdui.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtkcfxfepb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangdashe.top/Article/details/gtsaeikeka.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtxjpsbgzq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtlntgxstn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtmhpxncyt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yongpay.top/Article/details/gtomtrkmxt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258.top/Article/details/gtvnevqwex.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtkiewbyja.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnqzz.top/Article/details/gtqoxfeese.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gtpgoykvhg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dashuyun.cn/Article/details/gtfrjxdpwx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtalonlbxf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gtkuyfnuge.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aibaodan.cn/Article/details/gtqgydoinj.html

Go:   slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gtookccmds.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gtlcrlriib.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgufenzy.top/Article/details/gtahmhjwnu.html

[N03] 快速排序（分治示例）
来源：http://dali.yj202588.top/Article/details/gtwacnrfyi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj202588.top/Article/details/gtvxibczqg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangdashe.top/Article/details/gtbsmqdjqv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gtirxsrmhz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gtbfjcwahw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnxiangtu.top/Article/details/gtvkhozdsa.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yueranfly.top/Article/details/gtmottculi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258888.top/Article/details/gtwjduzbky.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258.top/Article/details/gtsfnlhhoj.html

[N04] 斐波那契数列
来源：http://dali.dashuyun.cn/Article/details/gtlaxrthkh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gtmikfqzkn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj202588.top/Article/details/gtnboakjwi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gttjihehzg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtkvkqtllq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sweek.top/Article/details/gtspfvnduq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbabmrfg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gtasytkelw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gtxssvfgvc.html

[N05] 最大公约数
来源：http://dali.dashuyun.cn/Article/details/gtihkhuigy.html

Py:   math.gcd(a, b)
来源：http://dali.fengsongda.top/Article/details/gtifomngtr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yangfankeji.com/Article/details/gtovnaapiy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gttjuxgzyr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gtaodndtxc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tian-w.cn/Article/details/gtesmvrkfm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cashguo.top/Article/details/gtligtdduy.html

Ruby: a.gcd(b)
来源：http://dali.nanxinkj.top/Article/details/gtnpqcxssy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xinyue.icu/Article/details/gtjbnbfzdp.html

[N06] 判断回文字符串
来源：http://dali.jlsjyb.cn/Article/details/gtplrgunog.html

Py:   s == s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gtmqmwnlec.html

PHP:  $s === strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gtcmtkrmzf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtebvbtkfv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtwmouoyff.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhixingplan.top/Article/details/gtphtjigjo.html

Go:   // 双指针从两端比较
来源：http://dali.hongshengwenyu.top/Article/details/gtgenezhjm.html

Ruby: s == s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gteaqtfuxx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gtpffodjwu.html

[N07] 两数之和（返回下标）
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbifhvch.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guannengcc.top/Article/details/gtvsbkrzfh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tianlin.xyz/Article/details/gtquqibhxi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xuetiantiany.cn/Article/details/gtxmjhfojw.html

TS:   // 手写 Map<string, number>
来源：http://dali.cashguo.top/Article/details/gtyhegigkr.html

Java: // 手写 HashMap
来源：http://dali.tian-w.cn/Article/details/gtuszhrzuk.html

Go:   // 手写 map[int]int
来源：http://dali.zhiwuduotai.top/Article/details/gtobpopcjd.html

Ruby: // 手写 Hash
来源：http://dali.yangfankeji.com/Article/details/gtrsyeiftf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenjidiqi.icu/Article/details/gtfrbdzseq.html

[N08] 生成全排列
来源：http://dali.jinqigfzy.top/Article/details/gtnvjabwvu.html

Py:   itertools.permutations(arr)
来源：http://dali.snrcjt.cn/Article/details/gtqgsrudww.html

PHP:  // 手写递归交换
来源：http://dali.sysykeji.top/Article/details/gtbtpxlqxb.html

JS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutyufgax.html

TS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtytalijvz.html

Java: // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtocrvclcg.html

Go:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtyywdglem.html

Ruby: arr.permutation.to_a
来源：http://dali.yueranfly.top/Article/details/gtmaxtnicn.html

C#:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtddlzjrlq.html

[N09] 栈与队列
来源：http://dali.snrcjt.cn/Article/details/gtskogclha.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fzhhl.top/Article/details/gtsnblwzzg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gthmheqnmn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzithzcm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hongshengwenyu.top/Article/details/gtivcknqgj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.smart0.xyz/Article/details/gtgihoeojp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tian-w.cn/Article/details/gtphpujphg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gtvuquatpk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hfpthk.cn/Article/details/gtpjgjcqlq.html

[N10] 链表节点定义
来源：http://dali.daxiang520.top/Article/details/gtqssmsexy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.c1oappe.top/Article/details/gtjfjdfgfy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.havefunace.top/Article/details/gtjtxsjqqb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlthvpref.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jlsjyb.cn/Article/details/gtsacazacu.html

Java: class Node { int v; Node next; }
来源：http://dali.yonumen.top/Article/details/gtrqlwtnvv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yongpay.top/Article/details/gthgqrorth.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hysaishi.cn/Article/details/gtfpzrdwzz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ppjwa.cn/Article/details/gtlyfjkkco.html

[N11] 二叉树中序遍历
来源：http://dali.quarkkingdee.top/Article/details/gtuhcypsxt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhixingplan.top/Article/details/gtkgometrc.html

PHP:  // 手写递归函数
来源：http://dali.yanxiufei.cn/Article/details/gtqrersdap.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gtkweufkzz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuanzx.com/Article/details/gtwmljmewg.html

Java: // 手写递归
来源：http://dali.smart0.xyz/Article/details/gtoozwnrly.html

Go:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gthrgouwrs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xinyue.icu/Article/details/gtfezrmcbk.html

C#:   // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxwiesmj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpnnrudx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.vqdsnc.cn/Article/details/gtcwhqtztc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yonumen.top/Article/details/gtxmhsynpw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gtknjnogdn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hfpthk.cn/Article/details/gtbtxkhxil.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gtepafbrko.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gzhubu.top/Article/details/gteqcibmmf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jiagoushi.top/Article/details/gtsuiucygk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gtksjxtkoj.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtdxrnmxtj.html

O. 并发与异步
来源：http://dali.tian-w.cn/Article/details/gtfxfknzzr.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtuvenbcue.html

[O01] 启动一个线程
来源：http://dali.zhengqikj.top/Article/details/gtdvcflcmh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daxiang520.top/Article/details/gtfldwcqce.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.feifeiyinyue.top/Article/details/gttosiplez.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.aibaodan.cn/Article/details/gtheygrqdb.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gtlslizluw.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuxming.cn/Article/details/gtexrrrpmv.html

Go:   go f()
来源：http://dali.nanxuanxn.top/Article/details/gtfssgqmbq.html

Ruby: Thread.new { f }
来源：http://dali.guowangkeji.top/Article/details/gtlzgrwlea.html

C#:   Task.Run(() => F());
来源：http://dali.hongshengwenyu.top/Article/details/gtmggloora.html

[O02] 使用线程池
来源：http://dali.aibaodan.cn/Article/details/gtwapygbax.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gogol.net.cn/Article/details/gtlefpnfnh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xuetiantiany.cn/Article/details/gtwsrqwwpu.html

JS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gtptvjkwlv.html

TS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtjylsumip.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.havefunace.top/Article/details/gtxudcsokv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.bjfxy.top/Article/details/gtwrnyinkr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xziqi.cn/Article/details/gtatthpsyq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnxiangtu.top/Article/details/gtwrgfbkld.html

[O03] 加锁保护共享数据
来源：http://dali.bjfxy.top/Article/details/gtarmvpntc.html

Py:   with lock: shared += 1
来源：http://dali.chenzaomai.com/Article/details/gteyfazhgn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.meibo888.top/Article/details/gtzrrtlfab.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xylfe.cn/Article/details/gtuokjstkb.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gtlpitfkkw.html

Java: synchronized (this) { shared++; }
来源：http://dali.jyoumei.cn/Article/details/gtagayoxnr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.mhx1999.top/Article/details/gtkadijzdt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.dianchejie.cn/Article/details/gtefiewfls.html

C#:   lock (gate) { shared++; }
来源：http://dali.zdqjudy.top/Article/details/gtuxaffhxj.html

[O04] 定义异步函数并等待
来源：http://dali.c1oappe.top/Article/details/gtjomcejkq.html

Py:   async def f():⏎    await g()
来源：http://dali.zhoulong.xyz/Article/details/gtyzjpdlza.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ydzc1.top/Article/details/gtkzustiep.html

JS:   async function f() { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gtreewayta.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.andypj.xyz/Article/details/gtqrisvdno.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuanzhike.top/Article/details/gtwydejbhs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yangfankeji.com/Article/details/gthvttzlvc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvxtsqbp.html

C#:   async Task F() { await G(); }
来源：http://dali.svipenyu.cn/Article/details/gtgfromklx.html

[O05] 并发执行并等待全部完成
来源：http://dali.cheryme.top/Article/details/gtpuggcnzg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yanxiufei.cn/Article/details/gtyjmaxurm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.9152youxi.cn/Article/details/gtolknuttl.html

JS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtokkcknhs.html

TS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gtnktivdcj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhengqikj.top/Article/details/gttaunrtwa.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cqqwz.cn/Article/details/gtqdjbzehy.html

Ruby: threads.map(&:join)
来源：http://dali.zhixingplan.top/Article/details/gtvtyguywn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jlsjyb.cn/Article/details/gtseaemitd.html

[O06] 使用进程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewymtrhf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sxryk.cn/Article/details/gtnimfusze.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tian-w.cn/Article/details/gtcjyscsuw.html

JS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gtqabrujgo.html

TS:   // child_process / cluster 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgzzgmdr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ivvv.top/Article/details/gtqjhhzzkw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cheryme.top/Article/details/gtqhauuaiv.html

Ruby: // fork 块
来源：http://dali.quarkkingdee.top/Article/details/gtyspesupc.html

C#:   Parallel.For
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbezlbpr.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtbckzloml.html

P. 常用工具函数
来源：http://dali.xuanzx.com/Article/details/gtxoshleds.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtlsdqtcej.html

[P01] 生成 UUID
来源：http://dali.tanke756.top/Article/details/gtsgmndlku.html

Py:   str(uuid.uuid4())
来源：http://dali.zhiwuduotai.top/Article/details/gtqwkzehga.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbhqdapt.html

JS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gthrmmiszm.html

TS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gtqgmewgne.html

Java: UUID.randomUUID().toString()
来源：http://dali.zycfv.cn/Article/details/gtgmascgor.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ehwqpu.com/Article/details/gtmvrsigag.html

Ruby: SecureRandom.uuid
来源：http://dali.xuetiantiany.cn/Article/details/gtkksqrbwd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yanxiufei.cn/Article/details/gtpeoduqzp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.316326.xyz/Article/details/gtpnnhlwto.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.aibaodan.cn/Article/details/gtnsdvxouw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yueranfly.top/Article/details/gtmglsmmwf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cucudq.cn/Article/details/gtzxsyydoe.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhongyouzk.top/Article/details/gtqgemhvrc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xylfe.cn/Article/details/gtikycgpom.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuanzhike.top/Article/details/gteubbnili.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258888.top/Article/details/gtuirakwss.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnqzz.top/Article/details/gtclfyrbem.html

[P03] 生成短随机字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtyzbltaiz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.c1oappe.top/Article/details/gtrybaakln.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnupvfmbu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gtaedmxgkn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtdvqtdvsb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ehwqpu.com/Article/details/gtkwyggegf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yongpay.top/Article/details/gtvygpxmcn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinqigfzy.top/Article/details/gtkanohpyb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daxiang520.top/Article/details/gtbfkmttol.html

[P04] 求长度
来源：http://dali.aizwys.cn/Article/details/gtionapcmz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgufenzy.top/Article/details/gtwredkvsk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtbsjhvsut.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gtliroxpdr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gtuygzqfjt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gtouhdgvyr.html

Go:   len(arr);  len(m)
来源：http://dali.xuanzx.com/Article/details/gtyzsinogt.html

Ruby: x.length;  x.size
来源：http://dali.jinqigufen.top/Article/details/gtnkiwjxxe.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gtlorwksun.html

[P05] 判断两个对象内容是否相等
来源：http://dali.0kj1m.cn/Article/details/gtipnytsxs.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jianghu66.top/Article/details/gtmriztfow.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gotoacloud.top/Article/details/gttsmlxhlc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhoulong.xyz/Article/details/gtzymcqsjr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.9152youxi.cn/Article/details/gtgvnvwpaf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sufxvd.cn/Article/details/gtkzffviur.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gtckvebreh.html

Ruby: a == b
来源：http://dali.316326.xyz/Article/details/gtvghkgjki.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jyoumei.cn/Article/details/gteydpddxr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.iojbl.cn/Article/details/gtrdwenoyb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xylfe.cn/Article/details/gtqrtssvrm.html

PHP:  if (empty($x)) {}
来源：http://dali.sufxvd.cn/Article/details/gtossmjrcm.html


<!-- 参考信息 -->