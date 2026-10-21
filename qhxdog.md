代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gtwwpcysua.html

[L08] 并发请求多个地址
来源：http://dali.cashguo.top/Article/details/gtaaidgbak.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.aibaodan.cn/Article/details/gtojojohll.html

PHP:  curl_multi_init() 系列
来源：http://dali.daxiang520.top/Article/details/gtcutsbiox.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gtnuogjovx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gtwhbhvrxy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tanke756.top/Article/details/gtotnqfaxw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cashguo.top/Article/details/gtowjlasuy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhixingplan.top/Article/details/gthboxvlms.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhixingplan.top/Article/details/gtcwmacihs.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtyjfrbklq.html

M. 命令行 / 进程 / 环境
来源：http://dali.xylfe.cn/Article/details/gtlsmftyug.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtjanendxk.html

[M01] 读取命令行参数
来源：http://dali.meibo888.top/Article/details/gtfmcsetcc.html

Py:   sys.argv[1:]
来源：http://dali.svipenyu.cn/Article/details/gthjoqgefc.html

PHP:  $argv;  $argc;
来源：http://dali.sufxvd.cn/Article/details/gtghihdoul.html

JS:   process.argv.slice(2)
来源：http://dali.fengsongda.top/Article/details/gtmbgblflt.html

TS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gtvwtuywdm.html

Java: args 数组（main 方法参数）
来源：http://dali.yj202588.top/Article/details/gtyhavorlg.html

Go:   os.Args[1:]
来源：http://dali.chenlongwang.top/Article/details/gtciloktuz.html

Ruby: ARGV
来源：http://dali.nwbrower.top/Article/details/gthfgznqjq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gttjsbzscf.html

[M02] 读取环境变量
来源：http://dali.nanxuanxn.top/Article/details/gtukuhxncl.html

Py:   os.environ.get("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtpskdjojc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gtrksjnzzk.html

JS:   process.env.HOME
来源：http://dali.jqgufenzy.top/Article/details/gteznjumng.html

TS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjavkegn.html

Java: System.getenv("HOME")
来源：http://dali.hammf.cn/Article/details/gtopfodnfz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtdpzbegom.html

Ruby: ENV["HOME"]
来源：http://dali.mhx1999.top/Article/details/gtgumbhwsa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtjtwjwckg.html

[M03] 执行外部命令
来源：http://dali.shangyingyoupin.top/Article/details/gtgntqpitk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tian-w.cn/Article/details/gtcwnpfdgt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuetiantiany.cn/Article/details/gtqlgocukx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gtkfjaoyaz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gtfldkalbu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuetiantiany.cn/Article/details/gtqcamxxxs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jianghu66.top/Article/details/gttfmbzagr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhixingplan.top/Article/details/gtkfzqhitj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hongshengwenyu.top/Article/details/gtfrjofufa.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtwguvwcxt.html

Py:   os.getcwd()
来源：http://dali.aibaodan.cn/Article/details/gtfpyyjykt.html

PHP:  getcwd();
来源：http://dali.jinqigufen.top/Article/details/gtzxlccmpf.html

JS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gtyobvntlh.html

TS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gtudvwbtwe.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yangfankeji.com/Article/details/gteadjsggl.html

Go:   os.Getwd()
来源：http://dali.nwbrower.top/Article/details/gtjetuzgke.html

Ruby: Dir.pwd
来源：http://dali.vqdsnc.cn/Article/details/gtvbcambwi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenlongwang.top/Article/details/gtvblzezep.html

[M05] 设置退出码
来源：http://dali.pengpengdd.cyou/Article/details/gthlvrwkss.html

Py:   sys.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtgiwwvpqx.html

PHP:  exit(1);
来源：http://dali.gotoacloud.top/Article/details/gtgsecqzqg.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtdrcloogf.html

TS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gtjvmhlebz.html

Java: System.exit(1)
来源：http://dali.hammf.cn/Article/details/gtcpxfihxv.html

Go:   os.Exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtfrovowqt.html

Ruby: exit 1
来源：http://dali.iojbl.cn/Article/details/gtpbyjdvdr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdknetxd.html

[M06] 向标准错误输出
来源：http://dali.shzxlz.cn/Article/details/gtagkjqeky.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gtfucrcwre.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwsbiuwa.html

JS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gticldjfuv.html

TS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtekzopijm.html

Java: System.err.println("err")
来源：http://dali.chenlongwang.top/Article/details/gtkunewyqj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cheryme.top/Article/details/gtjaaxdfou.html

Ruby: warn "err"
来源：http://dali.zhiwuduotai.top/Article/details/gtjzxwjkpe.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sxryk.cn/Article/details/gtmjrtbrrc.html

[M07] 判断是否为主入口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzctmrnr.html

Py:   if __name__ == "__main__":
来源：http://dali.svipenyu.cn/Article/details/gtnuukhrhq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.kuanghao11.cn/Article/details/gtdbasaayw.html

JS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtppymloio.html

TS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtteatguwg.html

Java: public static void main(String[] args)
来源：http://dali.jianghu66.top/Article/details/gtitiidfpn.html

Go:   func main()
来源：http://dali.tian-w.cn/Article/details/gtqowqfgzw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jlsjyb.cn/Article/details/gtrprhjpgl.html

C#:   static void Main(string[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttswotvpz.html

[M08] 获取系统与运行时信息
来源：http://dali.cashguo.top/Article/details/gtcwrbuacf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jiagoushi.top/Article/details/gtorygayeh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daxiang520.top/Article/details/gtccxbqdtx.html

JS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gtqmolxjqi.html

TS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gtfygfdmwj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.svipenyu.cn/Article/details/gtolhygxxh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.kuanghao11.cn/Article/details/gtstrzfmjw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jiagoushi.top/Article/details/gtbnxhlqdq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dianchejie.cn/Article/details/gtgqhqixzc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gttxfswpul.html

N. 数据结构与算法
来源：http://dali.hnqzz.top/Article/details/gteihdmmwq.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gttoysfstv.html

[N01] 二分查找（有序数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppffeqlf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtlzsirmny.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yueranfly.top/Article/details/gtcfwzipzy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtqxpeoald.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gtluxcfnwh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtlwldjkea.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtmxtxklis.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zycfv.cn/Article/details/gtwmojfazd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkxcthji.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.birdmap.top/Article/details/gtzhxalyhg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gtyyaouqgb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258888.top/Article/details/gtfhdsinoc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gthlbhkufm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gtqjyrsxcg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.0kj1m.cn/Article/details/gtkxceivtj.html

Go:   slices.Sort(arr)
来源：http://dali.nanxinkj.top/Article/details/gtuevwrvlw.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gtftnxmkgx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpasrvzcu.html

[N03] 快速排序（分治示例）
来源：http://dali.cheryme.top/Article/details/gtrgmcrlkv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtitjzmdsl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xziqi.cn/Article/details/gtkdjillvf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.0kj1m.cn/Article/details/gtksewduzg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gtbhvsfaku.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangshuangyany.cn/Article/details/gtwqhqetjr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xinyue.icu/Article/details/gtxlvfarzu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jlsjyb.cn/Article/details/gtqurcwxba.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yonumen.top/Article/details/gttmcnaxyn.html

[N04] 斐波那契数列
来源：http://dali.0kj1m.cn/Article/details/gtdxemrooo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtyypqendm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gtbnvojxgd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gttkkxbxxz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sweek.top/Article/details/gtonsiniyk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqocpuper.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuanzx.com/Article/details/gtnyjqiysd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtbqsizwpq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gtadxbglad.html

[N05] 最大公约数
来源：http://dali.yangfankeji.com/Article/details/gtwzurzvgv.html

Py:   math.gcd(a, b)
来源：http://dali.sweek.top/Article/details/gtgbagxswh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuxming.cn/Article/details/gtvuaxmdpo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gthqpxydfg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gtdycxkkrr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shzxlz.cn/Article/details/gtwxadtizo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuanzx.com/Article/details/gtxveadyco.html

Ruby: a.gcd(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtutvhjsdy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tanke756.top/Article/details/gtwowmqgko.html

[N06] 判断回文字符串
来源：http://dali.sysykeji.top/Article/details/gtrzmlhhqt.html

Py:   s == s[::-1]
来源：http://dali.ydzc1.top/Article/details/gtecdumipx.html

PHP:  $s === strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gtrcbldajj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtiihkyirk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtewhrbotk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xziqi.cn/Article/details/gtayyokubl.html

Go:   // 双指针从两端比较
来源：http://dali.tianlin.xyz/Article/details/gtxdmkohlv.html

Ruby: s == s.reverse
来源：http://dali.iojbl.cn/Article/details/gtwgimbhkh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenjidiqi.icu/Article/details/gtddgqqtgy.html

[N07] 两数之和（返回下标）
来源：http://dali.snrcjt.cn/Article/details/gtuacyzmjf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.kuanghao11.cn/Article/details/gtlradxgnw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhiwuduotai.top/Article/details/gtbrkyapbj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sweek.top/Article/details/gticokkspv.html

TS:   // 手写 Map<string, number>
来源：http://dali.iojbl.cn/Article/details/gtpchryqfa.html

Java: // 手写 HashMap
来源：http://dali.ppjwa.cn/Article/details/gtbghnxydj.html

Go:   // 手写 map[int]int
来源：http://dali.ybcxt.top/Article/details/gtodhrtjpo.html

Ruby: // 手写 Hash
来源：http://dali.yonumen.top/Article/details/gtwnsvyvcx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.birdmap.top/Article/details/gtqdmctued.html

[N08] 生成全排列
来源：http://dali.bjfxy.top/Article/details/gtqllswjkb.html

Py:   itertools.permutations(arr)
来源：http://dali.cqqwz.cn/Article/details/gtqvgglsbn.html

PHP:  // 手写递归交换
来源：http://dali.yj20258.top/Article/details/gtdeduudic.html

JS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtgcccaize.html

TS:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtklpuwlfb.html

Java: // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtxzvpwwts.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlaoaakpu.html

Ruby: arr.permutation.to_a
来源：http://dali.shzxlz.cn/Article/details/gtggdnfnjv.html

C#:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtvmfhmsro.html

[N09] 栈与队列
来源：http://dali.hammf.cn/Article/details/gtxvqjtscc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fzhhl.top/Article/details/gtedofprvp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.mhx1999.top/Article/details/gtzkmwfkmv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtqojqpqmc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxuanxn.top/Article/details/gtjfpsupfw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenzaomai.com/Article/details/gtrtgcmwhr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ydzc1.top/Article/details/gteapipzjz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtnhjuleri.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tanke756.top/Article/details/gtyqsgdvac.html

[N10] 链表节点定义
来源：http://dali.316326.xyz/Article/details/gtgwpwetlu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.redwolf501.top/Article/details/gtkdogzobv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cheryme.top/Article/details/gtjhbnoawn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtyvqqisxr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxuanxn.top/Article/details/gtywfijmwz.html

Java: class Node { int v; Node next; }
来源：http://dali.tian-w.cn/Article/details/gtwqnyffxp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenlongwang.top/Article/details/gtunsscldy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gzhubu.top/Article/details/gttarfrake.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.9152youxi.cn/Article/details/gtwllumzfr.html

[N11] 二叉树中序遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtisachnal.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.316326.xyz/Article/details/gtldchtypj.html

PHP:  // 手写递归函数
来源：http://dali.jqgufenzy.top/Article/details/gtncztbqow.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gtwgdeghph.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gtrlhpytse.html

Java: // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gtfeuydnve.html

Go:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtinszfdke.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.mhx1999.top/Article/details/gtgxqzceww.html

C#:   // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtupagezqp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aibaodan.cn/Article/details/gtwywlplgq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.9152youxi.cn/Article/details/gtenoqdkjd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sweek.top/Article/details/gtlmucydob.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.mhx1999.top/Article/details/gtcgnxsenz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gtdlyuboyi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hfpthk.cn/Article/details/gtmekzfpso.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhoulong.xyz/Article/details/gtzpbkjlrv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zdqjudy.top/Article/details/gtdxhnymjm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gtfmcryqmt.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtkplxhshp.html

O. 并发与异步
来源：http://dali.xylfe.cn/Article/details/gtyrnefzsy.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqmjwzym.html

[O01] 启动一个线程
来源：http://dali.feifeiyinyue.top/Article/details/gtealmnrun.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yongpay.top/Article/details/gtpbeogqoj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dianchejie.cn/Article/details/gtbbahedmr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tanke756.top/Article/details/gteoqzonew.html

TS:   // 同 JS
来源：http://dali.dashuyun.cn/Article/details/gtmsmhcmhv.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigufen.top/Article/details/gtukrsldmj.html

Go:   go f()
来源：http://dali.shzxlz.cn/Article/details/gtitakfnwu.html

Ruby: Thread.new { f }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuedtsbjs.html

C#:   Task.Run(() => F());
来源：http://dali.yj202588.top/Article/details/gtkbfxwngd.html

[O02] 使用线程池
来源：http://dali.dashuyun.cn/Article/details/gtrvaspihc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.dianchejie.cn/Article/details/gtcxohqgon.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrutboura.html

JS:   // worker_threads 线程池
来源：http://dali.zdqjudy.top/Article/details/gtbkpqftor.html

TS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gtrpprtugs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aizwys.cn/Article/details/gtskeqqlye.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobajeqbd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.svipenyu.cn/Article/details/gttlerdshk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.fzhhl.top/Article/details/gtwlbzqivk.html

[O03] 加锁保护共享数据
来源：http://dali.cdnleiting.top/Article/details/gtfmkiwrnj.html

Py:   with lock: shared += 1
来源：http://dali.hnxiangtu.top/Article/details/gtdlpsrsws.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.dashuyun.cn/Article/details/gtaeunggaj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.meibo888.top/Article/details/gtguxnnvyr.html

TS:   // 同 JS
来源：http://dali.pengpengdd.cyou/Article/details/gtjfeqveos.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gtcrvdptnf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shuidangran.top/Article/details/gtovzfgjyu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guowangkeji.top/Article/details/gtxzqcfixd.html

C#:   lock (gate) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gtuskvwdrg.html

[O04] 定义异步函数并等待
来源：http://dali.jianghu66.top/Article/details/gtaobadrqc.html

Py:   async def f():⏎    await g()
来源：http://dali.cqqwz.cn/Article/details/gtnjtxulkf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.c1oappe.top/Article/details/gtxwdfognm.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gtijavkiaz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.bjfxy.top/Article/details/gtdcqabogh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dashuyun.cn/Article/details/gtaqclpzje.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhixingplan.top/Article/details/gtoyzdqujf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zdqjudy.top/Article/details/gtizbdiwci.html

C#:   async Task F() { await G(); }
来源：http://dali.jianghu66.top/Article/details/gtrvjdffiw.html

[O05] 并发执行并等待全部完成
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpyllztzd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtzqkeuyrc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cucudq.cn/Article/details/gtjfzygxld.html

JS:   await Promise.all(tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gtbgvxbgso.html

TS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtommyfrzt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.feifeiyinyue.top/Article/details/gtmszuwytn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.iojbl.cn/Article/details/gtinwhrsud.html

Ruby: threads.map(&:join)
来源：http://dali.iojbl.cn/Article/details/gtwbcoxmbh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.daria6918.cn/Article/details/gtzlmrhwfg.html

[O06] 使用进程池
来源：http://dali.havefunace.top/Article/details/gtginfjcjt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hnqzz.top/Article/details/gtqkumrecq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hammf.cn/Article/details/gtaqynpdga.html

JS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gtiumsldvv.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258888.top/Article/details/gtdooqqkif.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xylfe.cn/Article/details/gtrgglpzzq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ehwqpu.com/Article/details/gtwjffeldd.html

Ruby: // fork 块
来源：http://dali.cqqwz.cn/Article/details/gtmgyjhvcj.html

C#:   Parallel.For
来源：http://dali.yonumen.top/Article/details/gtkyysliue.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtmukoapdk.html

P. 常用工具函数
来源：http://dali.fengsongda.top/Article/details/gtgxbntxqh.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtholqsflg.html

[P01] 生成 UUID
来源：http://dali.fzhhl.top/Article/details/gtodydiomj.html

Py:   str(uuid.uuid4())
来源：http://dali.feifeiyinyue.top/Article/details/gtwvhjvhfv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhoulong.xyz/Article/details/gtozvrpsan.html

JS:   crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gtbdfzhoeh.html

TS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtsxnwlydk.html

Java: UUID.randomUUID().toString()
来源：http://dali.yangfankeji.com/Article/details/gtvgsrhwbh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yonumen.top/Article/details/gtgtakmhkf.html

Ruby: SecureRandom.uuid
来源：http://dali.hammf.cn/Article/details/gtzhjaniwo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.daria6918.cn/Article/details/gtascuyody.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nanxuanxn.top/Article/details/gtubkkefif.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xylfe.cn/Article/details/gtnytvqrre.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jqgufenzy.top/Article/details/gtuopchuhc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daria6918.cn/Article/details/gtwvjmzvdp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yueranfly.top/Article/details/gtupdysbhk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258.top/Article/details/gtvbnzenme.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shuidangran.top/Article/details/gtglgtrkhj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.c1oappe.top/Article/details/gtrdbrcbvd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hongshengwenyu.top/Article/details/gtzzyrllnv.html

[P03] 生成短随机字符串
来源：http://dali.quarkkingdee.top/Article/details/gttoiqxbnt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xziqi.cn/Article/details/gtwncyboox.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nanxuanxn.top/Article/details/gtzdqavkxb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gtfqachldj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj202588.top/Article/details/gtniofuamg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtjcsrojxv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yongpay.top/Article/details/gtzooiavkp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hongshengwenyu.top/Article/details/gtkcelqlkt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnxiangtu.top/Article/details/gtvlairevb.html

[P04] 求长度
来源：http://dali.bjfxy.top/Article/details/gtqyfrzafn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.feifeiyinyue.top/Article/details/gtkrsisbqv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtatcdmqxb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aibaodan.cn/Article/details/gtdxvhpjxd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gtsgapyjbl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gaohongyu789.top/Article/details/gtlugetmjc.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gtuyagagrk.html

Ruby: x.length;  x.size
来源：http://dali.gogol.net.cn/Article/details/gtihpzbyko.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shzxlz.cn/Article/details/gtneorjazh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.snrcjt.cn/Article/details/gtydlsvfqn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yonumen.top/Article/details/gtcplehtai.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedxwkbxh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hfpthk.cn/Article/details/gtpwcribmd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zycfv.cn/Article/details/gtgxiazzbx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cheryme.top/Article/details/gtpfbvvitt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.wangdashe.top/Article/details/gtopzdodos.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gtdhwnriaw.html


<!-- 参考信息 -->