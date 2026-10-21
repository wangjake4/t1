代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gtpaxhtbxp.html

[L08] 并发请求多个地址
来源：http://dali.svipenyu.cn/Article/details/gtfywjqdzs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sysykeji.top/Article/details/gtvabbkxmw.html

PHP:  curl_multi_init() 系列
来源：http://dali.shangyingyoupin.top/Article/details/gtomgtpkhs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtuxearxry.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gtsrkumsiu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.9152youxi.cn/Article/details/gtfepqwpuv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yvedp.cn/Article/details/gtofynihxu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gtbmjsmoxm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.meibo888.top/Article/details/gtkgvpvnxh.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtfgbjrzpb.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhoulong.xyz/Article/details/gtnnzcbmsr.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtrzpjpvjz.html

[M01] 读取命令行参数
来源：http://dali.ppjwa.cn/Article/details/gtuozsqopb.html

Py:   sys.argv[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtkdfhyqxg.html

PHP:  $argv;  $argc;
来源：http://dali.hysaishi.cn/Article/details/gtqutonnbc.html

JS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gtdhnwbwqj.html

TS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gtyvekpksh.html

Java: args 数组（main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gtpzopwlfg.html

Go:   os.Args[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtkbgidbxo.html

Ruby: ARGV
来源：http://dali.havefunace.top/Article/details/gtnjiceqfr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gtuspsmpmt.html

[M02] 读取环境变量
来源：http://dali.smart0.xyz/Article/details/gtyorknsku.html

Py:   os.environ.get("HOME")
来源：http://dali.pycfn.com/Article/details/gtqrfuvymh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtsptpiyxg.html

JS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gtaysywkyn.html

TS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gtwvcvyhiq.html

Java: System.getenv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtcssgqzdr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtbuyavjit.html

Ruby: ENV["HOME"]
来源：http://dali.pycfn.com/Article/details/gtxdttfiux.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtmptjybvc.html

[M03] 执行外部命令
来源：http://dali.chenzaomai.com/Article/details/gtdvbhvkof.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zycfv.cn/Article/details/gtohhudsog.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shzxlz.cn/Article/details/gtabfbvzqb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gtkgmcgbhm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gtxdzbthms.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guannengcc.top/Article/details/gtwuvifxgs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cashguo.top/Article/details/gtazqcgocb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.haohaochexian.top/Article/details/gtqreitjje.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenzaomai.com/Article/details/gtyyucphwz.html

[M04] 获取当前工作目录
来源：http://dali.gaohongyu789.top/Article/details/gtbnpdpmsg.html

Py:   os.getcwd()
来源：http://dali.tanke756.top/Article/details/gtomfaprlz.html

PHP:  getcwd();
来源：http://dali.zhongyouzk.top/Article/details/gtsavmxyic.html

JS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gtlsuloxdq.html

TS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gtpycxuvgf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gogol.net.cn/Article/details/gtodqijflk.html

Go:   os.Getwd()
来源：http://dali.xylfe.cn/Article/details/gtwmtpuivp.html

Ruby: Dir.pwd
来源：http://dali.hywenlv.cn/Article/details/gtsctiwckb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shangyingyoupin.top/Article/details/gtrjvgmlko.html

[M05] 设置退出码
来源：http://dali.yj20258888.top/Article/details/gtmwwshvrg.html

Py:   sys.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtrmptljct.html

PHP:  exit(1);
来源：http://dali.hysaishi.cn/Article/details/gtnenvrtky.html

JS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtvxyvfidq.html

TS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtmqumbife.html

Java: System.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtgwqiwkjy.html

Go:   os.Exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtmfusmaes.html

Ruby: exit 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhstegwu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhixingplan.top/Article/details/gtwnytyigg.html

[M06] 向标准错误输出
来源：http://dali.chenzaomai.com/Article/details/gtrprkihqp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sufxvd.cn/Article/details/gtentwuxkd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tianlin.xyz/Article/details/gtkqrhrbjs.html

JS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gtttqrfvek.html

TS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gtxrvctztx.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gtdiowqvrq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangshuangyany.cn/Article/details/gtsigtdqov.html

Ruby: warn "err"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemewgrnr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hywenlv.cn/Article/details/gtkwyutkaa.html

[M07] 判断是否为主入口
来源：http://dali.zhoulong.xyz/Article/details/gtblskdlaz.html

Py:   if __name__ == "__main__":
来源：http://dali.sxryk.cn/Article/details/gtkhoqstfe.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jlsjyb.cn/Article/details/gtcsvxpkdx.html

JS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gteejvwmmg.html

TS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gtnmgzhvkt.html

Java: public static void main(String[] args)
来源：http://dali.cdnleiting.top/Article/details/gtbrxitqvo.html

Go:   func main()
来源：http://dali.smart0.xyz/Article/details/gtcjfpfwbk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.kuanghao11.cn/Article/details/gtlmdzhcym.html

C#:   static void Main(string[] args)
来源：http://dali.zdqjudy.top/Article/details/gttzbqwftp.html

[M08] 获取系统与运行时信息
来源：http://dali.ybcxt.top/Article/details/gtgqksdxtn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.quarkkingdee.top/Article/details/gtlkybephj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aibaodan.cn/Article/details/gtilbqwgcm.html

JS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrqxemdi.html

TS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gtetvwybgm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sweek.top/Article/details/gtlbkhamlo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daxiang520.top/Article/details/gtdneztudn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xziqi.cn/Article/details/gtyyonqlrz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hfpthk.cn/Article/details/gtyyvfkvmc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtwddmgjyp.html

N. 数据结构与算法
来源：http://dali.nanxuanxn.top/Article/details/gtdmyajorg.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtpwprdfzy.html

[N01] 二分查找（有序数组）
来源：http://dali.andypj.xyz/Article/details/gtuuasbxzd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtxeuhknwq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gtewddgimn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtssylxkjo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gtfccsfpfo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtcnnelmgw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtolpsybhv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jyoumei.cn/Article/details/gtbyagvneu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtiqmtwpix.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xziqi.cn/Article/details/gtntgshhku.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqvpbrha.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtpnhqgqkt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gtjpmsggde.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gteeilxuko.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dianchejie.cn/Article/details/gtujfbnpfa.html

Go:   slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gtvrysmyod.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtiqnhboin.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvflruqtk.html

[N03] 快速排序（分治示例）
来源：http://dali.yuxming.cn/Article/details/gtgtpwtlom.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xylfe.cn/Article/details/gtxbjvriwr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cheryme.top/Article/details/gtvbclqlnu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gtmwwkhjay.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gtvbuhhiej.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cucudq.cn/Article/details/gtpomhgyke.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jlsjyb.cn/Article/details/gtkpwkfref.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yanxiufei.cn/Article/details/gtxryxvwja.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hywenlv.cn/Article/details/gtetxslvdd.html

[N04] 斐波那契数列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfafccxyv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgirspply.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzfhkzsr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gtivmmjoww.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtcgaglcnj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gtcdoqyjcm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tanke756.top/Article/details/gtackutnzn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cucudq.cn/Article/details/gtkhhpvwqv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gtsuiqiezi.html

[N05] 最大公约数
来源：http://dali.xuetiantiany.cn/Article/details/gtawddoxad.html

Py:   math.gcd(a, b)
来源：http://dali.jianghu66.top/Article/details/gtcpcznejg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258.top/Article/details/gtmmsgtgqb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigufen.top/Article/details/gtedmeemaf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.vqdsnc.cn/Article/details/gtclpvvhqi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ivvv.top/Article/details/gthjhyxinj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.smart0.xyz/Article/details/gthfligeln.html

Ruby: a.gcd(b)
来源：http://dali.hywenlv.cn/Article/details/gtdvjtlymq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jiagoushi.top/Article/details/gtkyfqlavm.html

[N06] 判断回文字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiomzedkj.html

Py:   s == s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gtabupiver.html

PHP:  $s === strrev($s);
来源：http://dali.yj202588.top/Article/details/gtoobfptki.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtruauzfdg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtpfkxlmyb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.vqdsnc.cn/Article/details/gtizixcfar.html

Go:   // 双指针从两端比较
来源：http://dali.yangfankeji.com/Article/details/gtuhvnzzgb.html

Ruby: s == s.reverse
来源：http://dali.fengsongda.top/Article/details/gteezmqnbe.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gtfmxulgjh.html

[N07] 两数之和（返回下标）
来源：http://dali.ppjwa.cn/Article/details/gtxtegtxzf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jlsjyb.cn/Article/details/gtwkkegnzn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxbdedkw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhengqikj.top/Article/details/gtrhuaqzoj.html

TS:   // 手写 Map<string, number>
来源：http://dali.ydzc1.top/Article/details/gtqqousipd.html

Java: // 手写 HashMap
来源：http://dali.hongshengwenyu.top/Article/details/gtwiwlinba.html

Go:   // 手写 map[int]int
来源：http://dali.gzhubu.top/Article/details/gtucnvzggy.html

Ruby: // 手写 Hash
来源：http://dali.xylfe.cn/Article/details/gtrtfwpzpt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj20258888.top/Article/details/gtolizghpj.html

[N08] 生成全排列
来源：http://dali.daria6918.cn/Article/details/gtycpwqzga.html

Py:   itertools.permutations(arr)
来源：http://dali.svipenyu.cn/Article/details/gtkbprvdak.html

PHP:  // 手写递归交换
来源：http://dali.jinghuilouyu.cn/Article/details/gtbcxmrriz.html

JS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtjoupxyzb.html

TS:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtfsxglwbg.html

Java: // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gttcrsajes.html

Go:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtegfscodn.html

Ruby: arr.permutation.to_a
来源：http://dali.guannengcc.top/Article/details/gtfzoskzfz.html

C#:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtwisqvcvc.html

[N09] 栈与队列
来源：http://dali.mhx1999.top/Article/details/gtvhqpahyn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daxiang520.top/Article/details/gtxalaaoqi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gteqomroza.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gtjbadjglz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.snrcjt.cn/Article/details/gtkvhayhrb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hywenlv.cn/Article/details/gtdhdsdupc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnxiangtu.top/Article/details/gtahobafqu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtklffpbes.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hysaishi.cn/Article/details/gtoffyvkwh.html

[N10] 链表节点定义
来源：http://dali.ehwqpu.com/Article/details/gtwagupyxo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.vqdsnc.cn/Article/details/gtdkeidtil.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yvedp.cn/Article/details/gtxecsnqxo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtleyasiai.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ppjwa.cn/Article/details/gteemfwsyj.html

Java: class Node { int v; Node next; }
来源：http://dali.daria6918.cn/Article/details/gtjoxzzvvl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhongyouzk.top/Article/details/gtpgaznsuw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.birdmap.top/Article/details/gtdwturwty.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.bjfxy.top/Article/details/gtwenprxyl.html

[N11] 二叉树中序遍历
来源：http://dali.havefunace.top/Article/details/gtsajjtpej.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigfzy.top/Article/details/gtstgtlbby.html

PHP:  // 手写递归函数
来源：http://dali.tian-w.cn/Article/details/gtyuvbmqar.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gthadxpvba.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gthnjinsgs.html

Java: // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixzaqhsu.html

Go:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtcqodspou.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fzhhl.top/Article/details/gtxoevtbmr.html

C#:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gtyrlmpnwp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yuxming.cn/Article/details/gtfedzfwxk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.bjfxy.top/Article/details/gtluozlpvb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.dashuyun.cn/Article/details/gtelfynyia.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gzhubu.top/Article/details/gtgjpfunmd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangshuangyany.cn/Article/details/gtqvxxgqaa.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gtnqalbujq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxuanxn.top/Article/details/gtvgjzruyd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhongyouzk.top/Article/details/gtzbfzpwpa.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yangfankeji.com/Article/details/gtkvoentdj.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtrqasdnsc.html

O. 并发与异步
来源：http://dali.mhx1999.top/Article/details/gtgnxrbjdv.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtkiejwvqv.html

[O01] 启动一个线程
来源：http://dali.fengsongda.top/Article/details/gtgcygwhgh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hywenlv.cn/Article/details/gtskvrahbu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhiwuduotai.top/Article/details/gtzdycumge.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvianqos.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gthgtwgjou.html

Java: new Thread(() -> f()).start()
来源：http://dali.hysaishi.cn/Article/details/gtptaexbjf.html

Go:   go f()
来源：http://dali.cucudq.cn/Article/details/gtrmoqvjht.html

Ruby: Thread.new { f }
来源：http://dali.yongpay.top/Article/details/gtcfbrdoko.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigufen.top/Article/details/gtfgylstvn.html

[O02] 使用线程池
来源：http://dali.aizwys.cn/Article/details/gttrdyuqre.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ehwqpu.com/Article/details/gtzzdwfzcw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hnxiangtu.top/Article/details/gtfhsnrsct.html

JS:   // worker_threads 线程池
来源：http://dali.fzhhl.top/Article/details/gtgckgkbvq.html

TS:   // worker_threads 线程池
来源：http://dali.ehwqpu.com/Article/details/gtecvnrybc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hywenlv.cn/Article/details/gttzmbriyx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aibaodan.cn/Article/details/gtviwgorre.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fzhhl.top/Article/details/gtkdqwcxsl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.bjfxy.top/Article/details/gtldqsgjhr.html

[O03] 加锁保护共享数据
来源：http://dali.iojbl.cn/Article/details/gttbkfjubb.html

Py:   with lock: shared += 1
来源：http://dali.gaohongyu789.top/Article/details/gtwfdghydi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.haohaochexian.top/Article/details/gtymbdhoyw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guowangkeji.top/Article/details/gtadfjhtrr.html

TS:   // 同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdofpsept.html

Java: synchronized (this) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gtcgfymndq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.havefunace.top/Article/details/gtpdgdotki.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jlsjyb.cn/Article/details/gtyjaysvcb.html

C#:   lock (gate) { shared++; }
来源：http://dali.mhx1999.top/Article/details/gttmjsgiuc.html

[O04] 定义异步函数并等待
来源：http://dali.yuxming.cn/Article/details/gtziivanty.html

Py:   async def f():⏎    await g()
来源：http://dali.tianlin.xyz/Article/details/gtkantvrls.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yanxiufei.cn/Article/details/gtgbbvrbyx.html

JS:   async function f() { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gtlelzshbf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.316326.xyz/Article/details/gtwaireope.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daxiang520.top/Article/details/gtbeylbpgb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sysykeji.top/Article/details/gttvoulrdf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhoulong.xyz/Article/details/gtoiyrpelq.html

C#:   async Task F() { await G(); }
来源：http://dali.zhongyouzk.top/Article/details/gtzzdzqqlc.html

[O05] 并发执行并等待全部完成
来源：http://dali.aizwys.cn/Article/details/gtnuauohqd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptfzxvyt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jiagoushi.top/Article/details/gtjrblaqsu.html

JS:   await Promise.all(tasks)
来源：http://dali.yonumen.top/Article/details/gtanyltuoh.html

TS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gtbyqlkuox.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tian-w.cn/Article/details/gtmhuhaxnf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jyoumei.cn/Article/details/gtpzbsqzuq.html

Ruby: threads.map(&:join)
来源：http://dali.cdnleiting.top/Article/details/gtndpmuekd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.316326.xyz/Article/details/gtdufsingt.html

[O06] 使用进程池
来源：http://dali.aizwys.cn/Article/details/gtfauzzqrl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgfzy.top/Article/details/gtdfsogmlq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepthfnna.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gttgyexerk.html

TS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gtimbvwpth.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nanxuanxn.top/Article/details/gthalmzxoz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.fzhhl.top/Article/details/gtikvcbesm.html

Ruby: // fork 块
来源：http://dali.pycfn.com/Article/details/gtteumcwbn.html

C#:   Parallel.For
来源：http://dali.bjfxy.top/Article/details/gtsdqqqzxz.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gteveqsnox.html

P. 常用工具函数
来源：http://dali.nanxinkj.top/Article/details/gtxuwbzbmc.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtglvnsfqb.html

[P01] 生成 UUID
来源：http://dali.zhongyouzk.top/Article/details/gttmsviomo.html

Py:   str(uuid.uuid4())
来源：http://dali.shanyushiyangtech.top/Article/details/gtnfvuubyb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gogol.net.cn/Article/details/gtowmexfbn.html

JS:   crypto.randomUUID()
来源：http://dali.yj20258888.top/Article/details/gtokkbbsft.html

TS:   crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gtorsgcbeq.html

Java: UUID.randomUUID().toString()
来源：http://dali.mhx1999.top/Article/details/gtocefzknc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gtlhlgxjuz.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigufen.top/Article/details/gtsihxzugx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shzxlz.cn/Article/details/gtqwglylsf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgufenzy.top/Article/details/gtwbudhrrp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jyoumei.cn/Article/details/gtasvovwkm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqjflcce.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtdozbmfyg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigufen.top/Article/details/gtfkhyztfd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xylfe.cn/Article/details/gtsewnfjcz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gogol.net.cn/Article/details/gtcgbjoupi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cashguo.top/Article/details/gtlohfkcjs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinyuanbaomall.cn/Article/details/gthggmlttx.html

[P03] 生成短随机字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtekdcbqah.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jianghu66.top/Article/details/gtgpvhuija.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.wangdashe.top/Article/details/gtxeovozmj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cheryme.top/Article/details/gtyfgsccro.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtekkigihb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zycfv.cn/Article/details/gtojxvbpzn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jqgfzy.top/Article/details/gtmbrmkjyo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqjcwrng.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sweek.top/Article/details/gtgruiuvjq.html

[P04] 求长度
来源：http://dali.yongpay.top/Article/details/gtxdpmnvbs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.fzhhl.top/Article/details/gtmvshdpsd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtpanqnskq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gtazbqvjju.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xinyue.icu/Article/details/gtxojrwbdh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hongshengwenyu.top/Article/details/gtbwtkpcov.html

Go:   len(arr);  len(m)
来源：http://dali.zhiwuduotai.top/Article/details/gttjpyyltc.html

Ruby: x.length;  x.size
来源：http://dali.feifeiyinyue.top/Article/details/gtoxbvmegn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fengsongda.top/Article/details/gtumiftskz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.redwolf501.top/Article/details/gtwqphdtrp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yuanzhike.top/Article/details/gtspmvwxzm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinqigufen.top/Article/details/gtetgwcyge.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomwngpuj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnxiangtu.top/Article/details/gtspvtlwnu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aibaodan.cn/Article/details/gtmuquiido.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.guowangkeji.top/Article/details/gtdqqxncaq.html

Ruby: a == b
来源：http://dali.zdqjudy.top/Article/details/gtxzgtnfwf.html


<!-- 参考信息 -->