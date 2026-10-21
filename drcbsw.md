代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvklidzm.html

Java: resp.statusCode()
来源：http://dali.sysykeji.top/Article/details/gtrusgafbj.html

Go:   resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gtfesykmms.html

Ruby: resp.code.to_i
来源：http://dali.gogol.net.cn/Article/details/gtzbnaicuh.html

C#:   (int)resp.StatusCode
来源：http://dali.sweek.top/Article/details/gtozcpmasq.html

[L08] 并发请求多个地址
来源：http://dali.gogol.net.cn/Article/details/gtpptsxzdb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenlongwang.top/Article/details/gtdirazudt.html

PHP:  curl_multi_init() 系列
来源：http://dali.sxryk.cn/Article/details/gtbvoaqvbd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdyqrltwe.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gtjtkipknu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xylfe.cn/Article/details/gtkdpyyaha.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daria6918.cn/Article/details/gtpielhgpe.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.havefunace.top/Article/details/gtjfhhisbb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigufen.top/Article/details/gtesixdapz.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtmgjzvnqo.html

M. 命令行 / 进程 / 环境
来源：http://dali.cqqwz.cn/Article/details/gtecshlpmh.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gttjjvcdcb.html

[M01] 读取命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gtvubgexig.html

Py:   sys.argv[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtcrunbpxn.html

PHP:  $argv;  $argc;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfehrsam.html

JS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gtxfyihote.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtztsnsahw.html

Java: args 数组（main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gtzmgmbdny.html

Go:   os.Args[1:]
来源：http://dali.jyoumei.cn/Article/details/gtdnpgeykw.html

Ruby: ARGV
来源：http://dali.yvedp.cn/Article/details/gtgibelxtt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gtxztnurqy.html

[M02] 读取环境变量
来源：http://dali.316326.xyz/Article/details/gtvbhnnzqb.html

Py:   os.environ.get("HOME")
来源：http://dali.daxiang520.top/Article/details/gthvlgcptj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gtmktrudiu.html

JS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gtpipjvvim.html

TS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gtcacxrleg.html

Java: System.getenv("HOME")
来源：http://dali.yvedp.cn/Article/details/gtcqtbnotk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gttwgkeymx.html

Ruby: ENV["HOME"]
来源：http://dali.cqqwz.cn/Article/details/gtgeasuxmy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtefaesjsn.html

[M03] 执行外部命令
来源：http://dali.zhongyouzk.top/Article/details/gtqwcfigyq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jyoumei.cn/Article/details/gtjqlwgqyr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.wangdashe.top/Article/details/gtqjvlgcnx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gtvspznkxk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gtwdtbtykb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuanzx.com/Article/details/gtzpfloluu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gtjipobudf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.0kj1m.cn/Article/details/gtrwacdaci.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzhsznxi.html

[M04] 获取当前工作目录
来源：http://dali.c1oappe.top/Article/details/gtwhsarxem.html

Py:   os.getcwd()
来源：http://dali.xziqi.cn/Article/details/gtvrrguypj.html

PHP:  getcwd();
来源：http://dali.chenjidiqi.icu/Article/details/gtmbhuyiyj.html

JS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gtdogsgtxd.html

TS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtqnidvjau.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.havefunace.top/Article/details/gtrwweijam.html

Go:   os.Getwd()
来源：http://dali.aizwys.cn/Article/details/gtpicgpnnp.html

Ruby: Dir.pwd
来源：http://dali.smart0.xyz/Article/details/gthhcvzpcv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.snrcjt.cn/Article/details/gtlyzlfxyr.html

[M05] 设置退出码
来源：http://dali.nanxuanxn.top/Article/details/gtlgxestwo.html

Py:   sys.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtbqrdsstz.html

PHP:  exit(1);
来源：http://dali.wangdashe.top/Article/details/gtecvdsfaq.html

JS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtwapfzwpd.html

TS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtonvlbwft.html

Java: System.exit(1)
来源：http://dali.shuidangran.top/Article/details/gttfafrcxv.html

Go:   os.Exit(1)
来源：http://dali.nwbrower.top/Article/details/gtkvusadiz.html

Ruby: exit 1
来源：http://dali.zhengqikj.top/Article/details/gtlrkogbts.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cheryme.top/Article/details/gtukmsdjrl.html

[M06] 向标准错误输出
来源：http://dali.pycfn.com/Article/details/gtimiayonh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dashuyun.cn/Article/details/gtfiqvxrlx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xinyue.icu/Article/details/gtanphvhip.html

JS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gtjtlgslbe.html

TS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gtasvlejcq.html

Java: System.err.println("err")
来源：http://dali.chenzaomai.com/Article/details/gtnnrkluuq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tianlin.xyz/Article/details/gterygsasl.html

Ruby: warn "err"
来源：http://dali.sweek.top/Article/details/gtuhubjqyk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgufenzy.top/Article/details/gtrymhwnxp.html

[M07] 判断是否为主入口
来源：http://dali.jiagoushi.top/Article/details/gtdkmetnvm.html

Py:   if __name__ == "__main__":
来源：http://dali.yj202588.top/Article/details/gtuwfynjkx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenlongwang.top/Article/details/gtgfqcmcbg.html

JS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gtmgoyxfdd.html

TS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gttnkblszq.html

Java: public static void main(String[] args)
来源：http://dali.hammf.cn/Article/details/gtmyutzryz.html

Go:   func main()
来源：http://dali.gzhubu.top/Article/details/gtpfhngjod.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dianchejie.cn/Article/details/gtuxioyyax.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkysrenim.html

[M08] 获取系统与运行时信息
来源：http://dali.hammf.cn/Article/details/gtfpbgrszt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jyoumei.cn/Article/details/gtnzdcdbxh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ivvv.top/Article/details/gtudermsua.html

JS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gthwvddumn.html

TS:   process.platform;  process.version
来源：http://dali.zhixingplan.top/Article/details/gtoypizfrl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258.top/Article/details/gtljiyhhwl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.kuanghao11.cn/Article/details/gtioggawie.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zycfv.cn/Article/details/gtghhklpze.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ehwqpu.com/Article/details/gtufjpywlr.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtuvzagobo.html

N. 数据结构与算法
来源：http://dali.bjfxy.top/Article/details/gtnxhwywlb.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtwukszhmj.html

[N01] 二分查找（有序数组）
来源：http://dali.andypj.xyz/Article/details/gtnydzaura.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtzwsflgad.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.bjfxy.top/Article/details/gtuxkoynew.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gtvqceueay.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gtrlzrrexa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtampubsqq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtuyedhhbs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hysaishi.cn/Article/details/gtseyitfxs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gtwnbmgjgc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cashguo.top/Article/details/gtqyitrggc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gtqzfpolzd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sufxvd.cn/Article/details/gtnkamhisj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gtglodanmw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gtpoocqqxm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwzquutb.html

Go:   slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtvcjeqktg.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gtqndmcnbu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenlongwang.top/Article/details/gtpnrozmvu.html

[N03] 快速排序（分治示例）
来源：http://dali.zhongyouzk.top/Article/details/gtptgpvzek.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xziqi.cn/Article/details/gtsxaonkxq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.316326.xyz/Article/details/gtxuitzqcf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gtkgepuhfj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gtmvxdfwxf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj202588.top/Article/details/gtrrcrvsrl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cashguo.top/Article/details/gtxilsfhii.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yonumen.top/Article/details/gtnvpfmmhn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.feifeiyinyue.top/Article/details/gthsbjnmfe.html

[N04] 斐波那契数列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgambscc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gtkardxfge.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gtrmbmuvqo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhrbosfb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtkbxdtade.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xziqi.cn/Article/details/gtyhayqqyo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijbthnlb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccaprtbz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtocyrqkma.html

[N05] 最大公约数
来源：http://dali.jinqigufen.top/Article/details/gtjvknwgja.html

Py:   math.gcd(a, b)
来源：http://dali.pycfn.com/Article/details/gtxglbuygn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.vqdsnc.cn/Article/details/gtcrvkikxp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gtbdlfdtls.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gtipspfklx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxinkj.top/Article/details/gtblpwiobe.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zycfv.cn/Article/details/gtxwlzhehv.html

Ruby: a.gcd(b)
来源：http://dali.0kj1m.cn/Article/details/gtxzalyros.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yangfankeji.com/Article/details/gtmgzehlsy.html

[N06] 判断回文字符串
来源：http://dali.chenlongwang.top/Article/details/gtjjkcnayp.html

Py:   s == s[::-1]
来源：http://dali.mhx1999.top/Article/details/gtsunshboj.html

PHP:  $s === strrev($s);
来源：http://dali.jianghu66.top/Article/details/gtdlpairqh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtdapaqgup.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtrlyajshq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinghuilouyu.cn/Article/details/gtljufalez.html

Go:   // 双指针从两端比较
来源：http://dali.pycfn.com/Article/details/gthuxsdbga.html

Ruby: s == s.reverse
来源：http://dali.hysaishi.cn/Article/details/gtecxixlkt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenjidiqi.icu/Article/details/gtyzfobigl.html

[N07] 两数之和（返回下标）
来源：http://dali.zycfv.cn/Article/details/gtssfcsjmc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenjidiqi.icu/Article/details/gtnnaatpzt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shuidangran.top/Article/details/gtomhfhapc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sysykeji.top/Article/details/gtsxvwzvdm.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinqigfzy.top/Article/details/gtzbcprhqj.html

Java: // 手写 HashMap
来源：http://dali.jqgfzy.top/Article/details/gtqjexjewk.html

Go:   // 手写 map[int]int
来源：http://dali.wangshuangyany.cn/Article/details/gtzsmzhmiv.html

Ruby: // 手写 Hash
来源：http://dali.gzhubu.top/Article/details/gtgcsbzgvc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zdqjudy.top/Article/details/gtfrdiwsqq.html

[N08] 生成全排列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghsjtjpt.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxinkj.top/Article/details/gtaiqxyvps.html

PHP:  // 手写递归交换
来源：http://dali.hfpthk.cn/Article/details/gtqsuaczri.html

JS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtdtyznvmj.html

TS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtqeayofpb.html

Java: // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gttilkzhsc.html

Go:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtdblivsec.html

Ruby: arr.permutation.to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gtumlhnlsd.html

C#:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtqhrrieix.html

[N09] 栈与队列
来源：http://dali.kuanghao11.cn/Article/details/gtlxghuuof.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtzxhhmbdx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtydhvgnrn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gtjkoyamqr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jianghu66.top/Article/details/gtovgjutkl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gtqqjynbgi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ivvv.top/Article/details/gtydygddtz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gtkrrgvptk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gtejinxnie.html

[N10] 链表节点定义
来源：http://dali.zhiwuduotai.top/Article/details/gtgnsduoco.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hammf.cn/Article/details/gtosyghhen.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgiroonao.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guannengcc.top/Article/details/gtfgeytisk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xziqi.cn/Article/details/gtkbemiozd.html

Java: class Node { int v; Node next; }
来源：http://dali.zhengqikj.top/Article/details/gtexfnvdjh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenzaomai.com/Article/details/gtlmfcwyut.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.feifeiyinyue.top/Article/details/gtfaicdqhy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yongpay.top/Article/details/gtotxrgkia.html

[N11] 二叉树中序遍历
来源：http://dali.dianchejie.cn/Article/details/gtwwbxkhov.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.havefunace.top/Article/details/gtpqnjwxsi.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gthdgujuqh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.havefunace.top/Article/details/gtxdddilyo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dashuyun.cn/Article/details/gtwhhueuzw.html

Java: // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtgywvacyv.html

Go:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtumuqwftj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnauisyh.html

C#:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtnqoadwqd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cashguo.top/Article/details/gttrsjneqp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhongyouzk.top/Article/details/gtgfagpzoj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.c1oappe.top/Article/details/gtrhkmxwpq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxnamrqu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shangyingyoupin.top/Article/details/gtqbvmwonw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gtlktfznqn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.redwolf501.top/Article/details/gtgxkwrgmq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.vqdsnc.cn/Article/details/gtofkkopkq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gtcvnwctxi.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtyjghidhl.html

O. 并发与异步
来源：http://dali.yuxming.cn/Article/details/gtlnybuzlm.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtaqfpmqbj.html

[O01] 启动一个线程
来源：http://dali.hywenlv.cn/Article/details/gtextpnyre.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jqgufenzy.top/Article/details/gtcxowgdeb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuanzhike.top/Article/details/gtazyuazfa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ehwqpu.com/Article/details/gtgwbnqsfe.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gtrovlpsdu.html

Java: new Thread(() -> f()).start()
来源：http://dali.hammf.cn/Article/details/gtqctmwkbn.html

Go:   go f()
来源：http://dali.yuxming.cn/Article/details/gtacqcwvxb.html

Ruby: Thread.new { f }
来源：http://dali.sweek.top/Article/details/gtzojejmdx.html

C#:   Task.Run(() => F());
来源：http://dali.dashuyun.cn/Article/details/gtpxizpwdj.html

[O02] 使用线程池
来源：http://dali.dianchejie.cn/Article/details/gtftijufww.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ybcxt.top/Article/details/gtyabegewj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenzaomai.com/Article/details/gtslxquzzu.html

JS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gtuytnlzkt.html

TS:   // worker_threads 线程池
来源：http://dali.gotoacloud.top/Article/details/gtlwwfqnim.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.birdmap.top/Article/details/gtkfrivfdv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yonumen.top/Article/details/gtuqfzuwgx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gaohongyu789.top/Article/details/gtytzzssyo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cashguo.top/Article/details/gtqtstvjis.html

[O03] 加锁保护共享数据
来源：http://dali.hongshengwenyu.top/Article/details/gtmvuhhypz.html

Py:   with lock: shared += 1
来源：http://dali.jianghu66.top/Article/details/gtlrscsgjh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gaohongyu789.top/Article/details/gtcdtsbytv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yanxiufei.cn/Article/details/gtohqeffvu.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gtanlbvlxe.html

Java: synchronized (this) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gtnhslpaug.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangdashe.top/Article/details/gtpejyizpc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpikeqcue.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gtmtlfcydh.html

[O04] 定义异步函数并等待
来源：http://dali.chenlongwang.top/Article/details/gtnemxvhfz.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigufen.top/Article/details/gtwuvhrwwd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ivvv.top/Article/details/gtakqpacwz.html

JS:   async function f() { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gtkxzquxte.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvogwydwl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ydzc1.top/Article/details/gtboybpvgh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuanzhike.top/Article/details/gtpyzhavac.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.vqdsnc.cn/Article/details/gtwhrjgptu.html

C#:   async Task F() { await G(); }
来源：http://dali.fengsongda.top/Article/details/gtvvleomzt.html

[O05] 并发执行并等待全部完成
来源：http://dali.bjfxy.top/Article/details/gtsbwqaorz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yangfankeji.com/Article/details/gtkbyoqrir.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.redwolf501.top/Article/details/gtxjzpsrsi.html

JS:   await Promise.all(tasks)
来源：http://dali.cashguo.top/Article/details/gtxsdpnswg.html

TS:   await Promise.all(tasks)
来源：http://dali.sweek.top/Article/details/gtlphcbmel.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtntsndalu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xziqi.cn/Article/details/gtseeogsag.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258.top/Article/details/gtljvpdpio.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sweek.top/Article/details/gtnebwfkce.html

[O06] 使用进程池
来源：http://dali.jqgufenzy.top/Article/details/gtbzxzjjid.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jianghu66.top/Article/details/gtimoxavic.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.0kj1m.cn/Article/details/gtzxbuzbzi.html

JS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtactlmfnt.html

TS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gtlconxgia.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.meibo888.top/Article/details/gtnnnhnxxv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yuanzhike.top/Article/details/gtnabugshe.html

Ruby: // fork 块
来源：http://dali.jinqigfzy.top/Article/details/gtguhwvrif.html

C#:   Parallel.For
来源：http://dali.ybcxt.top/Article/details/gtvlxkcdfy.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxumpqqp.html

P. 常用工具函数
来源：http://dali.xziqi.cn/Article/details/gtymefgmis.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtdwnfxpzl.html

[P01] 生成 UUID
来源：http://dali.pycfn.com/Article/details/gtxmxnkydt.html

Py:   str(uuid.uuid4())
来源：http://dali.ydzc1.top/Article/details/gtbnyqgtsj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yonumen.top/Article/details/gtrtzevnpg.html

JS:   crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbninmdhy.html

TS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gtbyssxrsj.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258888.top/Article/details/gtzftoxavr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xuanzx.com/Article/details/gtnscpupkj.html

Ruby: SecureRandom.uuid
来源：http://dali.jianghu66.top/Article/details/gtiowbsaoj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shangyingyoupin.top/Article/details/gtyhmhuiyo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgfzy.top/Article/details/gtsroywhne.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cdnleiting.top/Article/details/gtesjiqfyf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tanke756.top/Article/details/gtkqdltafq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ppjwa.cn/Article/details/gtjpgnflhn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.birdmap.top/Article/details/gtuzppkjfc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.meibo888.top/Article/details/gthdpkmrop.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.meibo888.top/Article/details/gtowaivclv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenjidiqi.icu/Article/details/gttvfvbvdr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tanke756.top/Article/details/gtuearxzwm.html

[P03] 生成短随机字符串
来源：http://dali.ehwqpu.com/Article/details/gteiirhxpr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.c1oappe.top/Article/details/gthogsqvdu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sufxvd.cn/Article/details/gtjeslpbnz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yueranfly.top/Article/details/gtwftfwmlh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnyaqeqj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tanke756.top/Article/details/gtknioyipl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.bjfxy.top/Article/details/gtrtmcifhg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cqqwz.cn/Article/details/gtuyudjlnx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xziqi.cn/Article/details/gtielmenzd.html

[P04] 求长度
来源：http://dali.feifeiyinyue.top/Article/details/gtpoaufbrw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shuidangran.top/Article/details/gtpzsjebca.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbqiewcj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gthfkdvrnq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258888.top/Article/details/gtohhygoqc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gtmkzkxttj.html

Go:   len(arr);  len(m)
来源：http://dali.zhixingplan.top/Article/details/gttksyaacc.html

Ruby: x.length;  x.size
来源：http://dali.sysykeji.top/Article/details/gtbedsnaty.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sufxvd.cn/Article/details/gtgmidyjtx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.pengpengdd.cyou/Article/details/gttyhmskmu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ydzc1.top/Article/details/gtnrebjngj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yonumen.top/Article/details/gtuhwdfntq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gaohongyu789.top/Article/details/gthgvvcptq.html


<!-- 参考信息 -->