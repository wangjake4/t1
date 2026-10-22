代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.cdnleiting.top/Article/details/gt2yllnggrq.html

Java: resp.statusCode()
来源：http://dali.jqgufenzy.top/Article/details/gt2ceeulzgd.html

Go:   resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gt2xszlsrec.html

Ruby: resp.code.to_i
来源：http://dali.cheryme.top/Article/details/gt2gkateghb.html

C#:   (int)resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gt2fdzhgrie.html

[L08] 并发请求多个地址
来源：http://dali.xinyue.icu/Article/details/gt2noikguzi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.havefunace.top/Article/details/gt2liqmznmx.html

PHP:  curl_multi_init() 系列
来源：http://dali.andypj.xyz/Article/details/gt2qakrrpcr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gt2ivmvsiqz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gt2abtbdkih.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuetiantiany.cn/Article/details/gt2ruvnztmn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.9152youxi.cn/Article/details/gt2wbjmsppr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gt2bcewxepo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.redwolf501.top/Article/details/gt2qtfzwqjy.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2pxsjvvco.html

M. 命令行 / 进程 / 环境
来源：http://dali.yueranfly.top/Article/details/gt2fezvmnds.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2ihwrpkdv.html

[M01] 读取命令行参数
来源：http://dali.meibo888.top/Article/details/gt2awtzvyto.html

Py:   sys.argv[1:]
来源：http://dali.gotoacloud.top/Article/details/gt2xgibvntw.html

PHP:  $argv;  $argc;
来源：http://dali.tanke756.top/Article/details/gt2iwiffofh.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gt2kfkyfsou.html

TS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gt2iwytpros.html

Java: args 数组（main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gt2lzcshuiz.html

Go:   os.Args[1:]
来源：http://dali.c1oappe.top/Article/details/gt2kblaeehw.html

Ruby: ARGV
来源：http://dali.jqgufenzy.top/Article/details/gt2ecjbkphb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gt2tterqzyt.html

[M02] 读取环境变量
来源：http://dali.gaohongyu789.top/Article/details/gt2vuprwrwe.html

Py:   os.environ.get("HOME")
来源：http://dali.mhx1999.top/Article/details/gt2qglloasu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gt2mgvrvqui.html

JS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gt2auwnzoze.html

TS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gt2nobucion.html

Java: System.getenv("HOME")
来源：http://dali.ivvv.top/Article/details/gt2cnhqeshr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yonumen.top/Article/details/gt2tnnoskhd.html

Ruby: ENV["HOME"]
来源：http://dali.dashuyun.cn/Article/details/gt2zmcbdale.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2ygyasjgd.html

[M03] 执行外部命令
来源：http://dali.meibo888.top/Article/details/gt2ewadaxqo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangdashe.top/Article/details/gt2yjlaxvwg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hammf.cn/Article/details/gt2wdwamnxn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gt2ozzvqdue.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gt2twnxoedt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sweek.top/Article/details/gt2orykgatw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhengqikj.top/Article/details/gt2pxneowtw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigfzy.top/Article/details/gt2xzemizxl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.vqdsnc.cn/Article/details/gt2hysyvnty.html

[M04] 获取当前工作目录
来源：http://dali.kuanghao11.cn/Article/details/gt2rqyryfde.html

Py:   os.getcwd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2udtcrwoj.html

PHP:  getcwd();
来源：http://dali.chenjidiqi.icu/Article/details/gt2vlddsdod.html

JS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gt2mskryhkg.html

TS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2oeoemfto.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.quarkkingdee.top/Article/details/gt2uhgbgbeu.html

Go:   os.Getwd()
来源：http://dali.haohaochexian.top/Article/details/gt2qousubuh.html

Ruby: Dir.pwd
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kvwafjsq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gotoacloud.top/Article/details/gt2cfvmruda.html

[M05] 设置退出码
来源：http://dali.cdnleiting.top/Article/details/gt2yajsoccb.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgsquvg.html

PHP:  exit(1);
来源：http://dali.xuanzx.com/Article/details/gt2fysgvuxi.html

JS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2vrvovedo.html

TS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2ndtkosal.html

Java: System.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2iuyuulww.html

Go:   os.Exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2jphczkuo.html

Ruby: exit 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2htspmujb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gaohongyu789.top/Article/details/gt2owrfeuay.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gt2vbudqmcc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hysaishi.cn/Article/details/gt2aopuvgvz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhengqikj.top/Article/details/gt2plhncxab.html

JS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2anqzihqt.html

TS:   console.error("err")
来源：http://dali.jlsjyb.cn/Article/details/gt2seidusry.html

Java: System.err.println("err")
来源：http://dali.yj20258.top/Article/details/gt2ccpmdnjl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aizwys.cn/Article/details/gt2ixoqlfdf.html

Ruby: warn "err"
来源：http://dali.meibo888.top/Article/details/gt2nlrfnjkt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.havefunace.top/Article/details/gt2gupalmep.html

[M07] 判断是否为主入口
来源：http://dali.zhoulong.xyz/Article/details/gt2ofcuxuzh.html

Py:   if __name__ == "__main__":
来源：http://dali.jyoumei.cn/Article/details/gt2tzegpovx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pycfn.com/Article/details/gt2npnobciw.html

JS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gt2xygzbghu.html

TS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lpvhroom.html

Java: public static void main(String[] args)
来源：http://dali.mhx1999.top/Article/details/gt2rcchxcqo.html

Go:   func main()
来源：http://dali.havefunace.top/Article/details/gt2ispfbqtt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenjidiqi.icu/Article/details/gt2ujinemlk.html

C#:   static void Main(string[] args)
来源：http://dali.zdqjudy.top/Article/details/gt2cimoncqp.html

[M08] 获取系统与运行时信息
来源：http://dali.zhiwuduotai.top/Article/details/gt2evfmpykq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuanzhike.top/Article/details/gt2cwurpzam.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigfzy.top/Article/details/gt2hywtkuca.html

JS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gt2goiypvyn.html

TS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gt2fsuopzpa.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258.top/Article/details/gt2sxtdjkiu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenjidiqi.icu/Article/details/gt2iqptjlsj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cdnleiting.top/Article/details/gt2utcfxbql.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gotoacloud.top/Article/details/gt2dhpnydap.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2piykaiei.html

N. 数据结构与算法
来源：http://dali.hywenlv.cn/Article/details/gt2jwpxlhne.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2fgyibwwb.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigufen.top/Article/details/gt2uawylufj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gt2thmrhxhk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.aizwys.cn/Article/details/gt2vtvzghib.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gt2lbjpzuia.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gt2tooadspc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2cpgqgjar.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2nbzmdqry.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cheryme.top/Article/details/gt2emrbfqiz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2mpeckpbu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenjidiqi.icu/Article/details/gt2xwpbtbxt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gt2jstbbret.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigufen.top/Article/details/gt2mjhaxdca.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gt2prtfereh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gt2tulrahex.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ivvv.top/Article/details/gt2ozmnxrzs.html

Go:   slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2wbxeqhqc.html

Ruby: arr.sort
来源：http://dali.havefunace.top/Article/details/gt2rtsnlscs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hysaishi.cn/Article/details/gt2gnmqjvbw.html

[N03] 快速排序（分治示例）
来源：http://dali.gzhubu.top/Article/details/gt2gtksyiyp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gt2fpkxxaox.html

PHP:  // 递归实现，或用 usort
来源：http://dali.c1oappe.top/Article/details/gt2mhplzrjo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gt2urmwvvfw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ehwqpu.com/Article/details/gt2pklcfbok.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gzvghxmr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgfzy.top/Article/details/gt2hbmwcbtb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shuidangran.top/Article/details/gt2vynkmwnv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxuanxn.top/Article/details/gt2xoldvxdu.html

[N04] 斐波那契数列
来源：http://dali.ivvv.top/Article/details/gt2lryqltwl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gt2nicjddml.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.havefunace.top/Article/details/gt2quwvckni.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gt2iftqojgo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gt2ahjxdznn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gt2vmtlatvm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.redwolf501.top/Article/details/gt2ijicurta.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gt2rnbbqvkt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gt2ivvbcman.html

[N05] 最大公约数
来源：http://dali.nwbrower.top/Article/details/gt2pweezddn.html

Py:   math.gcd(a, b)
来源：http://dali.cheryme.top/Article/details/gt2irzgulyp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cheryme.top/Article/details/gt2flhepgrf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gt2ungasydr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gt2nlhyoewk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhiwuduotai.top/Article/details/gt2lsouoyav.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yvedp.cn/Article/details/gt2zguipzke.html

Ruby: a.gcd(b)
来源：http://dali.vqdsnc.cn/Article/details/gt2veqjzbrt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhongyouzk.top/Article/details/gt2faekqwgr.html

[N06] 判断回文字符串
来源：http://dali.sweek.top/Article/details/gt2ozhjvqws.html

Py:   s == s[::-1]
来源：http://dali.hnxiangtu.top/Article/details/gt2gtzsilpt.html

PHP:  $s === strrev($s);
来源：http://dali.c1oappe.top/Article/details/gt2meoilhpp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gt2zkmrrlhs.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gt2mkygtisl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.iojbl.cn/Article/details/gt2zxqsrahc.html

Go:   // 双指针从两端比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2tytysltn.html

Ruby: s == s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gt2cadwpxfa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sysykeji.top/Article/details/gt2fwzcydpv.html

[N07] 两数之和（返回下标）
来源：http://dali.zhiwuduotai.top/Article/details/gt2mqcykcbs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yanxiufei.cn/Article/details/gt2jngpuzsa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vmxuaqwr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgfzy.top/Article/details/gt2fntcbiah.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxinkj.top/Article/details/gt2irusuesu.html

Java: // 手写 HashMap
来源：http://dali.redwolf501.top/Article/details/gt2dqipgizw.html

Go:   // 手写 map[int]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lyiksxhq.html

Ruby: // 手写 Hash
来源：http://dali.kuanghao11.cn/Article/details/gt2lzhqqnxt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fengsongda.top/Article/details/gt2frvzlysh.html

[N08] 生成全排列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2veozdzin.html

Py:   itertools.permutations(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2exbbtqcz.html

PHP:  // 手写递归交换
来源：http://dali.ydzc1.top/Article/details/gt2vonftktx.html

JS:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gt2wgaftlau.html

TS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2megxqhfc.html

Java: // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gt2mwzyywyi.html

Go:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2hukhdptg.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258.top/Article/details/gt2xsxeuvdj.html

C#:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gt2tqldlixy.html

[N09] 栈与队列
来源：http://dali.daxiang520.top/Article/details/gt2vbibqrzu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yangfankeji.com/Article/details/gt2rsrblifu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gt2qlqvtgnl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gt2hddbdyig.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.andypj.xyz/Article/details/gt2cppfkloi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.havefunace.top/Article/details/gt2crkfvshw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxuanxn.top/Article/details/gt2sqqqztgl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yueranfly.top/Article/details/gt2oskvntlk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jyoumei.cn/Article/details/gt2svxvqlbs.html

[N10] 链表节点定义
来源：http://dali.guannengcc.top/Article/details/gt2wlvywpsk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tianlin.xyz/Article/details/gt2qhubxhot.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hfpthk.cn/Article/details/gt2twstdkio.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.pycfn.com/Article/details/gt2bnyphvcm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yvedp.cn/Article/details/gt2yzlwayov.html

Java: class Node { int v; Node next; }
来源：http://dali.snrcjt.cn/Article/details/gt2ypyogxbk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tian-w.cn/Article/details/gt2teoipogg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cashguo.top/Article/details/gt2ucsdguok.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sysykeji.top/Article/details/gt2yemojxgr.html

[N11] 二叉树中序遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2xtlviehf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daria6918.cn/Article/details/gt2cpvlmpoa.html

PHP:  // 手写递归函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2schdoixp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2goizrnrn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gt2dfhygkiz.html

Java: // 手写递归
来源：http://dali.yvedp.cn/Article/details/gt2zdccluoo.html

Go:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gt2gjfcegez.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.daria6918.cn/Article/details/gt2rgcrtidh.html

C#:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gt2yntcjzpn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuanzx.com/Article/details/gt2dchwaclj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigufen.top/Article/details/gt2vetgfbeq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.bjfxy.top/Article/details/gt2vrnrkmss.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gt2akfhzgll.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigufen.top/Article/details/gt2dojfxfgb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gt2emzrwjjc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guowangkeji.top/Article/details/gt2zzcjusty.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.mhx1999.top/Article/details/gt2oqvtoyxw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gt2aswrlrhq.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2cmfraqlx.html

O. 并发与异步
来源：http://dali.sufxvd.cn/Article/details/gt2unmhwmmz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2uxinqyan.html

[O01] 启动一个线程
来源：http://dali.jinqigufen.top/Article/details/gt2aoyakmfm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hongshengwenyu.top/Article/details/gt2pkmtiviw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nanxinkj.top/Article/details/gt2qoccuaor.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuanzhike.top/Article/details/gt2fuawacsz.html

TS:   // 同 JS
来源：http://dali.316326.xyz/Article/details/gt2hwqznvih.html

Java: new Thread(() -> f()).start()
来源：http://dali.kuanghao11.cn/Article/details/gt2vufjahnu.html

Go:   go f()
来源：http://dali.shangyingyoupin.top/Article/details/gt2bldzkdef.html

Ruby: Thread.new { f }
来源：http://dali.daxiang520.top/Article/details/gt2azhssegt.html

C#:   Task.Run(() => F());
来源：http://dali.chenlongwang.top/Article/details/gt2ldzdzfkq.html

[O02] 使用线程池
来源：http://dali.fengsongda.top/Article/details/gt2bzyyhjhu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guowangkeji.top/Article/details/gt2ncbbrvro.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tianlin.xyz/Article/details/gt2yiwwrjhx.html

JS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gt2hjcbkffn.html

TS:   // worker_threads 线程池
来源：http://dali.yongpay.top/Article/details/gt2gkezppwn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ybcxt.top/Article/details/gt2xzhcthzw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.feifeiyinyue.top/Article/details/gt2esfhqrnf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj202588.top/Article/details/gt2gvtygqoq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.pycfn.com/Article/details/gt2qeychrjq.html

[O03] 加锁保护共享数据
来源：http://dali.tian-w.cn/Article/details/gt2rloznune.html

Py:   with lock: shared += 1
来源：http://dali.shzxlz.cn/Article/details/gt2bjtpfiah.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aibaodan.cn/Article/details/gt2oelwevlc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hongshengwenyu.top/Article/details/gt2uzjhtiyn.html

TS:   // 同 JS
来源：http://dali.sysykeji.top/Article/details/gt2qyzkgqgu.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenlongwang.top/Article/details/gt2zarpljej.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tian-w.cn/Article/details/gt2krlqorcw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.aibaodan.cn/Article/details/gt2rschtnoy.html

C#:   lock (gate) { shared++; }
来源：http://dali.smart0.xyz/Article/details/gt2hxflwzzm.html

[O04] 定义异步函数并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ppsstmty.html

Py:   async def f():⏎    await g()
来源：http://dali.hysaishi.cn/Article/details/gt2zrhttptw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shuidangran.top/Article/details/gt2qxkfqfdq.html

JS:   async function f() { await g(); }
来源：http://dali.yangfankeji.com/Article/details/gt2iwxaywpl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zdqjudy.top/Article/details/gt2kovfppwg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.0kj1m.cn/Article/details/gt2ammajfnk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gogol.net.cn/Article/details/gt2bywvrukk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jianghu66.top/Article/details/gt2nqnucitr.html

C#:   async Task F() { await G(); }
来源：http://dali.sufxvd.cn/Article/details/gt2nsrsaozl.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtxibls.html

Py:   asyncio.gather(*tasks)
来源：http://dali.svipenyu.cn/Article/details/gt2pyooebyv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yongpay.top/Article/details/gt2hrefaoqy.html

JS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gt2babaebrm.html

TS:   await Promise.all(tasks)
来源：http://dali.meibo888.top/Article/details/gt2squlhwvy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.svipenyu.cn/Article/details/gt2omhsdtjp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinqigufen.top/Article/details/gt2amsaoeyu.html

Ruby: threads.map(&:join)
来源：http://dali.jyoumei.cn/Article/details/gt2wgheovsv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vjywaztm.html

[O06] 使用进程池
来源：http://dali.andypj.xyz/Article/details/gt2rwbajzfk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yangfankeji.com/Article/details/gt2taqhhrvw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gotoacloud.top/Article/details/gt2kvsyxwyl.html

JS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gt2yjpwfzdr.html

TS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gt2zltylbns.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.meibo888.top/Article/details/gt2ybnkwnlr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xuetiantiany.cn/Article/details/gt2pvpoqlhp.html

Ruby: // fork 块
来源：http://dali.andypj.xyz/Article/details/gt2lsinfrta.html

C#:   Parallel.For
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vnocvpys.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2embcxyle.html

P. 常用工具函数
来源：http://dali.havefunace.top/Article/details/gt2yzjnxdsn.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2jfcjcvrg.html

[P01] 生成 UUID
来源：http://dali.zdqjudy.top/Article/details/gt2kunjwxfo.html

Py:   str(uuid.uuid4())
来源：http://dali.yuanzhike.top/Article/details/gt2yolbugco.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sysykeji.top/Article/details/gt2dibkztio.html

JS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gt2mfhutquf.html

TS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gt2psxiqwnl.html

Java: UUID.randomUUID().toString()
来源：http://dali.mhx1999.top/Article/details/gt2bzpqngbh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cucudq.cn/Article/details/gt2tqkfzyde.html

Ruby: SecureRandom.uuid
来源：http://dali.hywenlv.cn/Article/details/gt2evgxympm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yanxiufei.cn/Article/details/gt2fwcssvtp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gotoacloud.top/Article/details/gt2odricnvy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.kuanghao11.cn/Article/details/gt2ilwtypxp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinqigufen.top/Article/details/gt2ozparuvb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shangyingyoupin.top/Article/details/gt2ulecowtk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangshuangyany.cn/Article/details/gt2tplymjwt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yangfankeji.com/Article/details/gt2hcmkkudx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hysaishi.cn/Article/details/gt2domwwueh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2njsmiqfj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.smart0.xyz/Article/details/gt2vfoulbvk.html

[P03] 生成短随机字符串
来源：http://dali.yj20258888.top/Article/details/gt2hvmieqxg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hemytwaq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yvedp.cn/Article/details/gt2mboxhcjn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.mhx1999.top/Article/details/gt2bztxlqdn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gt2bimynhds.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2ygaitqcp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gotoacloud.top/Article/details/gt2thptgqgb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.smart0.xyz/Article/details/gt2kmqwbukt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shuidangran.top/Article/details/gt2gtmhkrlq.html

[P04] 求长度
来源：http://dali.0kj1m.cn/Article/details/gt2pzejznfi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.andypj.xyz/Article/details/gt2jvuhypyx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gt2jbyymyry.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hfpthk.cn/Article/details/gt2bwdbcley.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fengsongda.top/Article/details/gt2ftqlbnnv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.mhx1999.top/Article/details/gt2ztcvxult.html

Go:   len(arr);  len(m)
来源：http://dali.haohaochexian.top/Article/details/gt2sgwcjraw.html

Ruby: x.length;  x.size
来源：http://dali.gotoacloud.top/Article/details/gt2culpptub.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.aibaodan.cn/Article/details/gt2biagddhl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dashuyun.cn/Article/details/gt2twsmoqpl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jlsjyb.cn/Article/details/gt2lgxxuvgm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinqigufen.top/Article/details/gt2plssxyfn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.0kj1m.cn/Article/details/gt2pzhynvqr.html


<!-- 参考信息 -->