代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtkymdydbx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtbnsicjej.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuanzhike.top/Article/details/gtcoximeni.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gotoacloud.top/Article/details/gtyydrtecq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zdqjudy.top/Article/details/gtotgvdcop.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gtkyohujar.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkieadpen.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhoulong.xyz/Article/details/gtyqbjianr.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmzmvxqun.html

[M01] 读取命令行参数
来源：http://dali.zhengqikj.top/Article/details/gtyqbmtamr.html

Py:   sys.argv[1:]
来源：http://dali.gogol.net.cn/Article/details/gtgzrdgxjk.html

PHP:  $argv;  $argc;
来源：http://dali.jlsjyb.cn/Article/details/gtjlhryjco.html

JS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gtrihszifi.html

TS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gtijnrxtaj.html

Java: args 数组（main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gtdaqkombn.html

Go:   os.Args[1:]
来源：http://dali.dianchejie.cn/Article/details/gtwvpnyfjy.html

Ruby: ARGV
来源：http://dali.meibo888.top/Article/details/gtxlmzchxe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtllwbicmf.html

[M02] 读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gttrbnnoqm.html

Py:   os.environ.get("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtpqrsqsiu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pycfn.com/Article/details/gtczyrusqi.html

JS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gtoyexsstq.html

TS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gtgtlfazvr.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtkpqxmdgl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznajfvzv.html

Ruby: ENV["HOME"]
来源：http://dali.birdmap.top/Article/details/gtzhzhlhhk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.iojbl.cn/Article/details/gtivbpvrua.html

[M03] 执行外部命令
来源：http://dali.jiagoushi.top/Article/details/gtepuegozq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tianlin.xyz/Article/details/gtczjtmqhv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xylfe.cn/Article/details/gtrpjwmvlk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtswwbtfcu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvaqdsgjr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.0kj1m.cn/Article/details/gtwednbwxw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.c1oappe.top/Article/details/gtanrdduor.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shuidangran.top/Article/details/gtjcrejnzg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xinyue.icu/Article/details/gtgvwknkws.html

[M04] 获取当前工作目录
来源：http://dali.nanxuanxn.top/Article/details/gtapzjzzir.html

Py:   os.getcwd()
来源：http://dali.yongpay.top/Article/details/gtcfznvyxx.html

PHP:  getcwd();
来源：http://dali.feifeiyinyue.top/Article/details/gtzukhdkst.html

JS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gtotlscdtn.html

TS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtvucmwigd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nwbrower.top/Article/details/gtwjiqqoft.html

Go:   os.Getwd()
来源：http://dali.jqgfzy.top/Article/details/gtqrewtafr.html

Ruby: Dir.pwd
来源：http://dali.jlsjyb.cn/Article/details/gtefgytjyz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnqzz.top/Article/details/gtieqlrasf.html

[M05] 设置退出码
来源：http://dali.guowangkeji.top/Article/details/gteyaehban.html

Py:   sys.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekzfoont.html

PHP:  exit(1);
来源：http://dali.xinyue.icu/Article/details/gtpfjobrmc.html

JS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gthzqauksz.html

TS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtxrlgpwmf.html

Java: System.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtwqitlxmq.html

Go:   os.Exit(1)
来源：http://dali.tanke756.top/Article/details/gtmicmxjnn.html

Ruby: exit 1
来源：http://dali.iojbl.cn/Article/details/gtbmslonzp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cqqwz.cn/Article/details/gtxrvzjrfh.html

[M06] 向标准错误输出
来源：http://dali.xziqi.cn/Article/details/gtzuukadoy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gtjridhumf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sweek.top/Article/details/gtnttvuxby.html

JS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gtfuncwnws.html

TS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gtjbsgsjna.html

Java: System.err.println("err")
来源：http://dali.jinqigfzy.top/Article/details/gtbhtuxecx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.9152youxi.cn/Article/details/gtfomigcnz.html

Ruby: warn "err"
来源：http://dali.havefunace.top/Article/details/gtcnltyhwz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gtrrlkyiqd.html

[M07] 判断是否为主入口
来源：http://dali.bjfxy.top/Article/details/gticyqiuwt.html

Py:   if __name__ == "__main__":
来源：http://dali.birdmap.top/Article/details/gtytygovfi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhengqikj.top/Article/details/gtfopifxsu.html

JS:   require.main === module
来源：http://dali.fzhhl.top/Article/details/gtwqazejov.html

TS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gtdhhmtosb.html

Java: public static void main(String[] args)
来源：http://dali.ybcxt.top/Article/details/gtwaxpvfas.html

Go:   func main()
来源：http://dali.zdqjudy.top/Article/details/gtvjjsibjp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gotoacloud.top/Article/details/gtizkbbwew.html

C#:   static void Main(string[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gtjscezvoh.html

[M08] 获取系统与运行时信息
来源：http://dali.andypj.xyz/Article/details/gtfhfkmwng.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gzhubu.top/Article/details/gtvyfmlgoc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cdnleiting.top/Article/details/gtvnpfnwxi.html

JS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gtsvrwyeij.html

TS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gtijxefcfv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.redwolf501.top/Article/details/gtrcitlvcj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolyzlinv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.svipenyu.cn/Article/details/gtqlonbrej.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xinyue.icu/Article/details/gtnsiwxvdf.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtawqbiryx.html

N. 数据结构与算法
来源：http://dali.yj20258888.top/Article/details/gtmqesywdd.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gttxpunwux.html

[N01] 二分查找（有序数组）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkmbpvgx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtxlosxovq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sweek.top/Article/details/gtsnjkshgm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gtlsmuhdqp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtriymwzde.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gtwezmzycd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tanke756.top/Article/details/gtomrtfapq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sysykeji.top/Article/details/gtwadbrwwf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtnuyhwxdv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yongpay.top/Article/details/gtrepdlabh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtjiswjdbn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnconrxoh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gtaflgvpmu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtlhupbjyy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.316326.xyz/Article/details/gtmpsnyrtf.html

Go:   slices.Sort(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtkeiakffn.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvedhipc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.9152youxi.cn/Article/details/gtlcdyatkr.html

[N03] 快速排序（分治示例）
来源：http://dali.yonumen.top/Article/details/gtveknmaqf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yongpay.top/Article/details/gtkzbclsra.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuanzhike.top/Article/details/gtsmmmcide.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gtzzcxyvrt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gthpwfwwdu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigfzy.top/Article/details/gtliwcktpv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenjidiqi.icu/Article/details/gtvxayxcet.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.haohaochexian.top/Article/details/gteawvozlh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigufen.top/Article/details/gteauwidib.html

[N04] 斐波那契数列
来源：http://dali.iojbl.cn/Article/details/gtgennlguu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gtzucjxoji.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowykfyqj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrxvaeiu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gteguhjzft.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gtuxzngspl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenlongwang.top/Article/details/gtzggtqqzy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtvrejlhan.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gtqvwjkimo.html

[N05] 最大公约数
来源：http://dali.jinghuilouyu.cn/Article/details/gtvomhbahw.html

Py:   math.gcd(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtupeokkmf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hysaishi.cn/Article/details/gtkhamwxbu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gtnwffzsiw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gtbhkkursl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnqzz.top/Article/details/gtlbvcktfv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.haohaochexian.top/Article/details/gtvkmwbdlk.html

Ruby: a.gcd(b)
来源：http://dali.chenzaomai.com/Article/details/gtidufvwzc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fengsongda.top/Article/details/gtntordqqd.html

[N06] 判断回文字符串
来源：http://dali.sysykeji.top/Article/details/gtjbwivgvz.html

Py:   s == s[::-1]
来源：http://dali.bjfxy.top/Article/details/gtlhjugzxy.html

PHP:  $s === strrev($s);
来源：http://dali.xziqi.cn/Article/details/gtmsgxqsjg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtshxozral.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaheqvboe.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cdnleiting.top/Article/details/gtaepridxb.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmkjhqgl.html

Ruby: s == s.reverse
来源：http://dali.zdqjudy.top/Article/details/gtsqakuavz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gtvuomjcwa.html

[N07] 两数之和（返回下标）
来源：http://dali.gzhubu.top/Article/details/gtgpbagqbu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.iojbl.cn/Article/details/gtbitcaisx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dianchejie.cn/Article/details/gttrdzsnuv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cqqwz.cn/Article/details/gtbvmcezur.html

TS:   // 手写 Map<string, number>
来源：http://dali.smart0.xyz/Article/details/gtxxbhhpez.html

Java: // 手写 HashMap
来源：http://dali.tianlin.xyz/Article/details/gthfstzyum.html

Go:   // 手写 map[int]int
来源：http://dali.c1oappe.top/Article/details/gtaayzohem.html

Ruby: // 手写 Hash
来源：http://dali.hongshengwenyu.top/Article/details/gtlpgpzkga.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aibaodan.cn/Article/details/gtdflmfujw.html

[N08] 生成全排列
来源：http://dali.jinqigfzy.top/Article/details/gtemichsze.html

Py:   itertools.permutations(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtpiiiznrx.html

PHP:  // 手写递归交换
来源：http://dali.cheryme.top/Article/details/gtufnzbrsn.html

JS:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtneyjbbik.html

TS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtwagjwfrx.html

Java: // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxoasrswv.html

Go:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtsnzwpkfj.html

Ruby: arr.permutation.to_a
来源：http://dali.yongpay.top/Article/details/gteshmmota.html

C#:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtwtxboeym.html

[N09] 栈与队列
来源：http://dali.havefunace.top/Article/details/gtjmxljnmh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hammf.cn/Article/details/gtvefnwgkt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nwbrower.top/Article/details/gttvkrqefk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtnxaejqar.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhoulong.xyz/Article/details/gtmorrjmkm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.snrcjt.cn/Article/details/gtajdhatdc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.0kj1m.cn/Article/details/gtstrmjbxd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.c1oappe.top/Article/details/gtuftxyqif.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258.top/Article/details/gthhqenpwl.html

[N10] 链表节点定义
来源：http://dali.cheryme.top/Article/details/gtkgibvsyq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yvedp.cn/Article/details/gtcrehttrq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cucudq.cn/Article/details/gtonexxjtz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tanke756.top/Article/details/gtrunmntgr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yonumen.top/Article/details/gtxlaophso.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttitcckiz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yvedp.cn/Article/details/gtpmpgaefz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.vqdsnc.cn/Article/details/gtotdldvqw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yongpay.top/Article/details/gtsovxbcka.html

[N11] 二叉树中序遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrfgczfc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nwbrower.top/Article/details/gthqjqlydg.html

PHP:  // 手写递归函数
来源：http://dali.cdnleiting.top/Article/details/gtgmuxhfuc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gtenslkmxh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gtiofcmgxh.html

Java: // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gtkxnteixc.html

Go:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtqvimrppv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cqqwz.cn/Article/details/gtrldjwyvv.html

C#:   // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gtcjeqcnvz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.guannengcc.top/Article/details/gtnyellxye.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoykvxgzr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jianghu66.top/Article/details/gtrtscugbs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guowangkeji.top/Article/details/gtvghcsdzj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gtlpaklgku.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gtddytutsi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zycfv.cn/Article/details/gtbpnktbna.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj202588.top/Article/details/gtcauzvgdb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gtsxcwwptc.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtgqmyiqlp.html

O. 并发与异步
来源：http://dali.tianlin.xyz/Article/details/gtkqmrrqzd.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtpcbzjorh.html

[O01] 启动一个线程
来源：http://dali.hfpthk.cn/Article/details/gtqkdoziwv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.svipenyu.cn/Article/details/gtmbfaffmy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.daria6918.cn/Article/details/gtqgmmtqlo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tanke756.top/Article/details/gtlykcdcbk.html

TS:   // 同 JS
来源：http://dali.tian-w.cn/Article/details/gtirlqbuum.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuanzhike.top/Article/details/gtxjrjubsb.html

Go:   go f()
来源：http://dali.sxryk.cn/Article/details/gttvucwzts.html

Ruby: Thread.new { f }
来源：http://dali.jinqigufen.top/Article/details/gtkupchuzj.html

C#:   Task.Run(() => F());
来源：http://dali.kuanghao11.cn/Article/details/gthfbxsvrd.html

[O02] 使用线程池
来源：http://dali.316326.xyz/Article/details/gtzqvhbehd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.mhx1999.top/Article/details/gtudbgkbnp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.iojbl.cn/Article/details/gtfmbvbbgb.html

JS:   // worker_threads 线程池
来源：http://dali.yangfankeji.com/Article/details/gtfrzkvpfr.html

TS:   // worker_threads 线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbkjilds.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.316326.xyz/Article/details/gtnmfcrzlg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yongpay.top/Article/details/gtivxncndb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yueranfly.top/Article/details/gtjacfguev.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yangfankeji.com/Article/details/gttdijbudn.html

[O03] 加锁保护共享数据
来源：http://dali.yuanzhike.top/Article/details/gtyslxjqug.html

Py:   with lock: shared += 1
来源：http://dali.jianghu66.top/Article/details/gtwhltwlps.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yonumen.top/Article/details/gtzaiclwbc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.redwolf501.top/Article/details/gtblcyrrfv.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtcwxnenst.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtivffmndb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipxsrogq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yvedp.cn/Article/details/gtdfzuqzdc.html

C#:   lock (gate) { shared++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvartiwof.html

[O04] 定义异步函数并等待
来源：http://dali.hongshengwenyu.top/Article/details/gtnxsfvkah.html

Py:   async def f():⏎    await g()
来源：http://dali.zhengqikj.top/Article/details/gtwkummhyz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenjidiqi.icu/Article/details/gtwiuasvnu.html

JS:   async function f() { await g(); }
来源：http://dali.cashguo.top/Article/details/gtezjzsayw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.9152youxi.cn/Article/details/gtivcrmwjq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258888.top/Article/details/gtqxqimdzs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sxryk.cn/Article/details/gtpigfwkrw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.mhx1999.top/Article/details/gtgjhkauho.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258888.top/Article/details/gtiwwrwsbv.html

[O05] 并发执行并等待全部完成
来源：http://dali.redwolf501.top/Article/details/gtnirlhkiw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xinyue.icu/Article/details/gtiuyqnpji.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdlmiifc.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gtxevhkzim.html

TS:   await Promise.all(tasks)
来源：http://dali.havefunace.top/Article/details/gtzsjbicqd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwhnnmzb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgfzy.top/Article/details/gtjzrvgspf.html

Ruby: threads.map(&:join)
来源：http://dali.nwbrower.top/Article/details/gtstgwwolf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigfzy.top/Article/details/gtvuzxksux.html

[O06] 使用进程池
来源：http://dali.tianlin.xyz/Article/details/gtwtpjgpxc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sufxvd.cn/Article/details/gtsvgoutbb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gotoacloud.top/Article/details/gtkweqsroi.html

JS:   // child_process / cluster 模块
来源：http://dali.ydzc1.top/Article/details/gtbujznjtc.html

TS:   // child_process / cluster 模块
来源：http://dali.jyoumei.cn/Article/details/gtodkcwdqd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hammf.cn/Article/details/gtgjaktgdu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shzxlz.cn/Article/details/gtarefzapb.html

Ruby: // fork 块
来源：http://dali.sxryk.cn/Article/details/gtzimbuefg.html

C#:   Parallel.For
来源：http://dali.pengpengdd.cyou/Article/details/gtdpufmgod.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtvmeenhea.html

P. 常用工具函数
来源：http://dali.xuetiantiany.cn/Article/details/gteesdwupf.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtyntcbddh.html

[P01] 生成 UUID
来源：http://dali.nanxuanxn.top/Article/details/gtawaitiek.html

Py:   str(uuid.uuid4())
来源：http://dali.ehwqpu.com/Article/details/gthavfgoql.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hnxiangtu.top/Article/details/gtmwhxjsbn.html

JS:   crypto.randomUUID()
来源：http://dali.nanxuanxn.top/Article/details/gtomnbzzpu.html

TS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gtidoqocih.html

Java: UUID.randomUUID().toString()
来源：http://dali.xylfe.cn/Article/details/gtbirvdiii.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ehwqpu.com/Article/details/gtvwwjjyct.html

Ruby: SecureRandom.uuid
来源：http://dali.yuanzhike.top/Article/details/gtnvtdwobt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.andypj.xyz/Article/details/gtnvkspsel.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gaohongyu789.top/Article/details/gtyryjktdg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigufen.top/Article/details/gtgkawoxii.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sysykeji.top/Article/details/gtlizsypme.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.andypj.xyz/Article/details/gtfhnpuhwc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.pengpengdd.cyou/Article/details/gtwuudecyq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hammf.cn/Article/details/gtnptlxepw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gttlxwsflo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gzhubu.top/Article/details/gttvoeayza.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gogol.net.cn/Article/details/gtvgmrgbkg.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gtkxroubrn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.316326.xyz/Article/details/gtscdkvedm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenjidiqi.icu/Article/details/gthdzmalhk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gtfzqdydab.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ehwqpu.com/Article/details/gtyrqiiuno.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cdnleiting.top/Article/details/gtzcjzsplk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitsrtztk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.aibaodan.cn/Article/details/gtxzrxsrzp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258.top/Article/details/gtdtnprrkd.html

[P04] 求长度
来源：http://dali.jlsjyb.cn/Article/details/gtecnfinda.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xuetiantiany.cn/Article/details/gttkgbnysy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gthelconcb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gtwgrqrrlj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.haohaochexian.top/Article/details/gtjtdfijoe.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yonumen.top/Article/details/gteyslpywg.html

Go:   len(arr);  len(m)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgsbyhxu.html

Ruby: x.length;  x.size
来源：http://dali.fengsongda.top/Article/details/gtpiuaxgmb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tian-w.cn/Article/details/gtksjkecmh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hfpthk.cn/Article/details/gtzdqqmpfq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhixingplan.top/Article/details/gtzgvjpazz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinqigufen.top/Article/details/gtixkrclrv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ivvv.top/Article/details/gtbcbmypha.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhoulong.xyz/Article/details/gtbluvcnpc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenjidiqi.icu/Article/details/gtjagtlomw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtgwnolmkk.html

Ruby: a == b
来源：http://dali.jinqigfzy.top/Article/details/gttmbvytgb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.vqdsnc.cn/Article/details/gtfvotlhpw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gaohongyu789.top/Article/details/gtsbzjique.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jianghu66.top/Article/details/gttbvnwqpl.html

PHP:  if (empty($x)) {}
来源：http://dali.ppjwa.cn/Article/details/gtnflgeoxf.html


<!-- 参考信息 -->