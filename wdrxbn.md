代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gt2kvutpnfn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gt2ibzujcgi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ehwqpu.com/Article/details/gt2lszpeovz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenzaomai.com/Article/details/gt2ptmyxhfx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nwbrower.top/Article/details/gt2yoocqaac.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258.top/Article/details/gt2sgofavpb.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2srzyhcvk.html

M. 命令行 / 进程 / 环境
来源：http://dali.sysykeji.top/Article/details/gt2fhbqatul.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2djmbdjbk.html

[M01] 读取命令行参数
来源：http://dali.yj202588.top/Article/details/gt2ucqicgns.html

Py:   sys.argv[1:]
来源：http://dali.zhixingplan.top/Article/details/gt2bxbzpxfw.html

PHP:  $argv;  $argc;
来源：http://dali.hnxiangtu.top/Article/details/gt2qpmqyqcx.html

JS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gt2eaoxgxab.html

TS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gt2yvrlaswn.html

Java: args 数组（main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gt2vqhuinci.html

Go:   os.Args[1:]
来源：http://dali.zhixingplan.top/Article/details/gt2qglydsfh.html

Ruby: ARGV
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zmpajigj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gt2xucygqim.html

[M02] 读取环境变量
来源：http://dali.yueranfly.top/Article/details/gt2ipagsmed.html

Py:   os.environ.get("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pdrxhbtv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gt2pvraeyst.html

JS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gt2rgaduasl.html

TS:   process.env.HOME
来源：http://dali.snrcjt.cn/Article/details/gt2yvjjnfor.html

Java: System.getenv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gt2qssqzatf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yvedp.cn/Article/details/gt2spgucezc.html

Ruby: ENV["HOME"]
来源：http://dali.jlsjyb.cn/Article/details/gt2iyxswsfg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gzhubu.top/Article/details/gt2tndcjlsi.html

[M03] 执行外部命令
来源：http://dali.pengpengdd.cyou/Article/details/gt2arqiqncj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.bjfxy.top/Article/details/gt2pesytfmh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hammf.cn/Article/details/gt2ydqnhbvz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2vpgxqvli.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2byekfpaz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.svipenyu.cn/Article/details/gt2ffxjjzft.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dashuyun.cn/Article/details/gt2ryvqzike.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.smart0.xyz/Article/details/gt2drnmvlji.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgufenzy.top/Article/details/gt2lnqowdae.html

[M04] 获取当前工作目录
来源：http://dali.ppjwa.cn/Article/details/gt2oymbliez.html

Py:   os.getcwd()
来源：http://dali.zdqjudy.top/Article/details/gt2dzwvtnwu.html

PHP:  getcwd();
来源：http://dali.andypj.xyz/Article/details/gt2urztlhdc.html

JS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gt2cmbtuxoq.html

TS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gt2olbbyhnd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenjidiqi.icu/Article/details/gt2xtmhxier.html

Go:   os.Getwd()
来源：http://dali.aibaodan.cn/Article/details/gt2dxqgojbo.html

Ruby: Dir.pwd
来源：http://dali.yonumen.top/Article/details/gt2zlqyggly.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.316326.xyz/Article/details/gt2lviisbmv.html

[M05] 设置退出码
来源：http://dali.dashuyun.cn/Article/details/gt2jkquvpts.html

Py:   sys.exit(1)
来源：http://dali.yj20258.top/Article/details/gt2ekufpgis.html

PHP:  exit(1);
来源：http://dali.yongpay.top/Article/details/gt2vqncsjvv.html

JS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2tdrjcpts.html

TS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gt2ucrlgfxb.html

Java: System.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2djbduqqn.html

Go:   os.Exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2vhjczhal.html

Ruby: exit 1
来源：http://dali.zhongyouzk.top/Article/details/gt2nezzcgon.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.havefunace.top/Article/details/gt2syvtmvee.html

[M06] 向标准错误输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lagxouzn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xyhwfuys.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cqqwz.cn/Article/details/gt2ivgteypa.html

JS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gt2bdtkqwvz.html

TS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gt2wclgkufj.html

Java: System.err.println("err")
来源：http://dali.fzhhl.top/Article/details/gt2hfisqwlx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nwbrower.top/Article/details/gt2haynojbg.html

Ruby: warn "err"
来源：http://dali.meibo888.top/Article/details/gt2cqljqryw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jyoumei.cn/Article/details/gt2taauanop.html

[M07] 判断是否为主入口
来源：http://dali.gaohongyu789.top/Article/details/gt2leugsijs.html

Py:   if __name__ == "__main__":
来源：http://dali.zhixingplan.top/Article/details/gt2rwzspkfq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dashuyun.cn/Article/details/gt2tpvdefrz.html

JS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gt2myiuyqaw.html

TS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gt2uuxptqjd.html

Java: public static void main(String[] args)
来源：http://dali.bjfxy.top/Article/details/gt2nfxmkbpp.html

Go:   func main()
来源：http://dali.cucudq.cn/Article/details/gt2nhlemngx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zdqjudy.top/Article/details/gt2mklhgrul.html

C#:   static void Main(string[] args)
来源：http://dali.zhengqikj.top/Article/details/gt2chpndwfg.html

[M08] 获取系统与运行时信息
来源：http://dali.ybcxt.top/Article/details/gt2ortfhfwr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jlsjyb.cn/Article/details/gt2nnaxfeak.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.havefunace.top/Article/details/gt2rhayjvlp.html

JS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gt2aqsultpt.html

TS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gt2ickyemdd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mqxyajmt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jahhjjji.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jyoumei.cn/Article/details/gt2pcvonozh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ydzc1.top/Article/details/gt2ehhwgsfj.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2vcasozmh.html

N. 数据结构与算法
来源：http://dali.havefunace.top/Article/details/gt2tpsbbrec.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2nuhswddi.html

[N01] 二分查找（有序数组）
来源：http://dali.zhoulong.xyz/Article/details/gt2ifnqyfvg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2dtxhylzc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.c1oappe.top/Article/details/gt2qejtihre.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gt2eudyxqke.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gt2qktzfyst.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2dhsmqxxi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2basgujcd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jiagoushi.top/Article/details/gt2wkvuxfsa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2dnwwvinw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.fzhhl.top/Article/details/gt2egeeodbq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gt2feqpktad.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.meibo888.top/Article/details/gt2pgvvmioh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gt2sbuwtcwj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tfgmykww.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ixyxhtup.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gt2kttreubm.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gt2swnazjqg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2povjlwsb.html

[N03] 快速排序（分治示例）
来源：http://dali.wangshuangyany.cn/Article/details/gt2tuzyzxzf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.birdmap.top/Article/details/gt2ybmnxluf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cashguo.top/Article/details/gt2xktuuqsf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gt2qsuqjhoa.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gt2itjxrmev.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhongyouzk.top/Article/details/gt2tmccodgu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qekmqplm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.smart0.xyz/Article/details/gt2gzjwntle.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhixingplan.top/Article/details/gt2daykhpuj.html

[N04] 斐波那契数列
来源：http://dali.daria6918.cn/Article/details/gt2kmvwswoe.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.316326.xyz/Article/details/gt2hygwlops.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gt2baonqfdb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2ovpjrmdv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gt2bgtemwpf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jyoumei.cn/Article/details/gt2hnycgros.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gffbxwan.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gt2gygnxiks.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gt2izepnzpx.html

[N05] 最大公约数
来源：http://dali.jlsjyb.cn/Article/details/gt2znmjupzo.html

Py:   math.gcd(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rrfkfurw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lvslyyio.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gt2jwhvzmjb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gt2sppjkgym.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zycfv.cn/Article/details/gt2woztevzk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenlongwang.top/Article/details/gt2hnyenmuq.html

Ruby: a.gcd(b)
来源：http://dali.jianghu66.top/Article/details/gt2yenusnqq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuanzhike.top/Article/details/gt2otjmnmok.html

[N06] 判断回文字符串
来源：http://dali.xuanzx.com/Article/details/gt2fmsajgzn.html

Py:   s == s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gt2extzygdk.html

PHP:  $s === strrev($s);
来源：http://dali.shuidangran.top/Article/details/gt2emmkkjvh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gt2lzfvualt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gt2essufkqm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cdnleiting.top/Article/details/gt2nhhytgdo.html

Go:   // 双指针从两端比较
来源：http://dali.shuidangran.top/Article/details/gt2xhpmfevl.html

Ruby: s == s.reverse
来源：http://dali.sweek.top/Article/details/gt2nafnhtfk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2slrkwxaz.html

[N07] 两数之和（返回下标）
来源：http://dali.jinqigfzy.top/Article/details/gt2nooodyqi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258888.top/Article/details/gt2vnpcnifr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.redwolf501.top/Article/details/gt2wdyjjpys.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lqcdomvk.html

TS:   // 手写 Map<string, number>
来源：http://dali.ivvv.top/Article/details/gt2qskattmo.html

Java: // 手写 HashMap
来源：http://dali.chenlongwang.top/Article/details/gt2hgzzzsev.html

Go:   // 手写 map[int]int
来源：http://dali.yuxming.cn/Article/details/gt2beobkdho.html

Ruby: // 手写 Hash
来源：http://dali.sweek.top/Article/details/gt2xethfiws.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cashguo.top/Article/details/gt2jvgyikvt.html

[N08] 生成全排列
来源：http://dali.zycfv.cn/Article/details/gt2kaflubfa.html

Py:   itertools.permutations(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2fahbmgur.html

PHP:  // 手写递归交换
来源：http://dali.tanke756.top/Article/details/gt2tjrnvrjf.html

JS:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gt2gbxocxas.html

TS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2qjnsdkek.html

Java: // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gt2itgvrclp.html

Go:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2wgzlqgyr.html

Ruby: arr.permutation.to_a
来源：http://dali.quarkkingdee.top/Article/details/gt2vcitebrf.html

C#:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gt2ojtdawnn.html

[N09] 栈与队列
来源：http://dali.yj202588.top/Article/details/gt2tspmwpzv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.redwolf501.top/Article/details/gt2oexiwawg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gt2zlmdvtjv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gt2uwvnvfzz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yueranfly.top/Article/details/gt2hisfbvfg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xinyue.icu/Article/details/gt2vafcmmvz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigufen.top/Article/details/gt2oddeqmfk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gt2yataflwx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.meibo888.top/Article/details/gt2xuehoihw.html

[N10] 链表节点定义
来源：http://dali.ehwqpu.com/Article/details/gt2sfgattlr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.0kj1m.cn/Article/details/gt2uuhbtupc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yvedp.cn/Article/details/gt2rmgagnyu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.dashuyun.cn/Article/details/gt2ucjggytu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gzhubu.top/Article/details/gt2dvrvrpcz.html

Java: class Node { int v; Node next; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ohbtjmqt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tianlin.xyz/Article/details/gt2hfkzkejs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.c1oappe.top/Article/details/gt2vuozegcs.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cashguo.top/Article/details/gt2vvldzwwj.html

[N11] 二叉树中序遍历
来源：http://dali.yuxming.cn/Article/details/gt2tlknlnev.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pengpengdd.cyou/Article/details/gt2zvliupwu.html

PHP:  // 手写递归函数
来源：http://dali.yj20258888.top/Article/details/gt2fdxrfdxa.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guowangkeji.top/Article/details/gt2guemhham.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sysykeji.top/Article/details/gt2mdgqdbbs.html

Java: // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gt2zpntqrfq.html

Go:   // 手写递归
来源：http://dali.yongpay.top/Article/details/gt2nezkyxuw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangdashe.top/Article/details/gt2tnkhmmzm.html

C#:   // 手写递归
来源：http://dali.andypj.xyz/Article/details/gt2xtoghczp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vhahuqjk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aizwys.cn/Article/details/gt2znruwewu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jqgfzy.top/Article/details/gt2ylhjieuw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xyixmzor.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gt2glukbsbe.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gaohongyu789.top/Article/details/gt2porwjgyj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.wangdashe.top/Article/details/gt2ygnwiete.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xonmzgyk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gt2xtjdebis.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2cgvkiays.html

O. 并发与异步
来源：http://dali.hnxiangtu.top/Article/details/gt2yibffddn.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2guldewko.html

[O01] 启动一个线程
来源：http://dali.haohaochexian.top/Article/details/gt2dqomybll.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxinkj.top/Article/details/gt2vgqfxcwg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cdnleiting.top/Article/details/gt2uixynzel.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.vqdsnc.cn/Article/details/gt2inpkgluk.html

TS:   // 同 JS
来源：http://dali.kuanghao11.cn/Article/details/gt2vurteeko.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ncropzas.html

Go:   go f()
来源：http://dali.haohaochexian.top/Article/details/gt2outcexhb.html

Ruby: Thread.new { f }
来源：http://dali.pengpengdd.cyou/Article/details/gt2oboodsyx.html

C#:   Task.Run(() => F());
来源：http://dali.yuanzhike.top/Article/details/gt2wageulmh.html

[O02] 使用线程池
来源：http://dali.ydzc1.top/Article/details/gt2rhnwpvzp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigufen.top/Article/details/gt2xrukqzic.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigufen.top/Article/details/gt2lwsnfryo.html

JS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gt2rzyqlvbz.html

TS:   // worker_threads 线程池
来源：http://dali.cashguo.top/Article/details/gt2rcfrkiiv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258888.top/Article/details/gt2pfwfrfqu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdqelow.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.haohaochexian.top/Article/details/gt2tpsrnysk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.wangdashe.top/Article/details/gt2qqdhevcz.html

[O03] 加锁保护共享数据
来源：http://dali.aibaodan.cn/Article/details/gt2myheelsx.html

Py:   with lock: shared += 1
来源：http://dali.jyoumei.cn/Article/details/gt2tqxnseai.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cdnleiting.top/Article/details/gt2lqfhubmb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.316326.xyz/Article/details/gt2rmrkawsq.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gt2vigjqnrc.html

Java: synchronized (this) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gt2vfbmgnav.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.svipenyu.cn/Article/details/gt2fgdlkukx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.havefunace.top/Article/details/gt2xqxjoiel.html

C#:   lock (gate) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gt2xyobsddb.html

[O04] 定义异步函数并等待
来源：http://dali.gzhubu.top/Article/details/gt2sawpvmfy.html

Py:   async def f():⏎    await g()
来源：http://dali.cheryme.top/Article/details/gt2raftkasr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.fengsongda.top/Article/details/gt2soijyahp.html

JS:   async function f() { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2dazownyn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hammf.cn/Article/details/gt2enkhfsxl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.guannengcc.top/Article/details/gt2euitrcvw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ppxvksqn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ppjwa.cn/Article/details/gt2dyzrfith.html

C#:   async Task F() { await G(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vybfnets.html

[O05] 并发执行并等待全部完成
来源：http://dali.shuidangran.top/Article/details/gt2aewraxuv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangdashe.top/Article/details/gt2somacshr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yangfankeji.com/Article/details/gt2lybffbgf.html

JS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gt2zqqhorsg.html

TS:   await Promise.all(tasks)
来源：http://dali.fengsongda.top/Article/details/gt2xntghwme.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shuidangran.top/Article/details/gt2micblclw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.havefunace.top/Article/details/gt2qnesxden.html

Ruby: threads.map(&:join)
来源：http://dali.tanke756.top/Article/details/gt2xaoizvxd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zycfv.cn/Article/details/gt2gebwbizp.html

[O06] 使用进程池
来源：http://dali.yongpay.top/Article/details/gt2zqqqkxos.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sweek.top/Article/details/gt2nzulnseb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.iojbl.cn/Article/details/gt2zrchlrpw.html

JS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gt2tmhfsqsi.html

TS:   // child_process / cluster 模块
来源：http://dali.hfpthk.cn/Article/details/gt2vzyariax.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ehwqpu.com/Article/details/gt2odxoqsso.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jiagoushi.top/Article/details/gt2btoeelsg.html

Ruby: // fork 块
来源：http://dali.daria6918.cn/Article/details/gt2cepvmnop.html

C#:   Parallel.For
来源：http://dali.c1oappe.top/Article/details/gt2tqwwkxkk.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2qwqsxvyu.html

P. 常用工具函数
来源：http://dali.ppjwa.cn/Article/details/gt2bahisarv.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2xptdqvhe.html

[P01] 生成 UUID
来源：http://dali.haohaochexian.top/Article/details/gt2cxmplflt.html

Py:   str(uuid.uuid4())
来源：http://dali.ehwqpu.com/Article/details/gt2hxzrqprr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.pycfn.com/Article/details/gt2gxywiycw.html

JS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gt2fvjpcnsc.html

TS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gt2rksnudht.html

Java: UUID.randomUUID().toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2vaniwzvg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sxryk.cn/Article/details/gt2eycqxviw.html

Ruby: SecureRandom.uuid
来源：http://dali.gaohongyu789.top/Article/details/gt2xbuqxysv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ppjwa.cn/Article/details/gt2amacchko.html

[P02] MD5 / SHA256 摘要
来源：http://dali.birdmap.top/Article/details/gt2elhvwwyg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2jabhzrmq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sufxvd.cn/Article/details/gt2iujcrgsk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sweek.top/Article/details/gt2rgagaqqz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shuidangran.top/Article/details/gt2zuxzrqlt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xioqcndm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.andypj.xyz/Article/details/gt2tlyuixrs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.aizwys.cn/Article/details/gt2wsgqtmyk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pengpengdd.cyou/Article/details/gt2xdcnbssd.html

[P03] 生成短随机字符串
来源：http://dali.xziqi.cn/Article/details/gt2pbfjnqhl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangdashe.top/Article/details/gt2aqcbtjrd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shuidangran.top/Article/details/gt2vpzjfxti.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gt2efntxppy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gt2srpptzvt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zdqjudy.top/Article/details/gt2grojpinc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cqqwz.cn/Article/details/gt2lrorvsvh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yvedp.cn/Article/details/gt2lvnqmrjc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinghuilouyu.cn/Article/details/gt2erilbzdh.html

[P04] 求长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dqagkgiq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhoulong.xyz/Article/details/gt2zrqtbehs.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gt2jguzlnyp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gt2xaismupy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zdqjudy.top/Article/details/gt2zqhgddtl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oizjtfcz.html

Go:   len(arr);  len(m)
来源：http://dali.havefunace.top/Article/details/gt2fdiqrrqz.html

Ruby: x.length;  x.size
来源：http://dali.yonumen.top/Article/details/gt2oijgqpxj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cdnleiting.top/Article/details/gt2jbrubhis.html

[P05] 判断两个对象内容是否相等
来源：http://dali.pycfn.com/Article/details/gt2suxabaqr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shzxlz.cn/Article/details/gt2hfaqeujx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yuanzhike.top/Article/details/gt2acyarxuv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.kuanghao11.cn/Article/details/gt2jrhchkau.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oyiyunbx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ivvv.top/Article/details/gt2ncgrhaeh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.havefunace.top/Article/details/gt2jusznmfx.html

Ruby: a == b
来源：http://dali.fzhhl.top/Article/details/gt2migoifiv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zdqjudy.top/Article/details/gt2vrzwmvlt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.mhx1999.top/Article/details/gt2fjfvinoh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.smart0.xyz/Article/details/gt2olrnsaih.html

PHP:  if (empty($x)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2jsyfvkyt.html


<!-- 参考信息 -->