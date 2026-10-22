代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gt2guybptiq.html

[L08] 并发请求多个地址
来源：http://dali.fengsongda.top/Article/details/gt2hvrmfnrf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.iojbl.cn/Article/details/gt2eyhejppk.html

PHP:  curl_multi_init() 系列
来源：http://dali.shangyingyoupin.top/Article/details/gt2kfqzqeun.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gt2ypyarwxl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gt2tulcqvgg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dashuyun.cn/Article/details/gt2toellwmb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnqzz.top/Article/details/gt2dqrrdclp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.smart0.xyz/Article/details/gt2gumplttg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guannengcc.top/Article/details/gt2igjzbafl.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2zjjpqznw.html

M. 命令行 / 进程 / 环境
来源：http://dali.snrcjt.cn/Article/details/gt2gisytwmg.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2ahrmcjmw.html

[M01] 读取命令行参数
来源：http://dali.redwolf501.top/Article/details/gt2dgrjiifu.html

Py:   sys.argv[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gjzzlzzz.html

PHP:  $argv;  $argc;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ylabukzh.html

JS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gt2ukrsvdiw.html

TS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gt2obifthpo.html

Java: args 数组（main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gt2blrjeqcv.html

Go:   os.Args[1:]
来源：http://dali.tian-w.cn/Article/details/gt2yrovrolm.html

Ruby: ARGV
来源：http://dali.cqqwz.cn/Article/details/gt2cqzfxgvp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gt2iuwlacsi.html

[M02] 读取环境变量
来源：http://dali.ydzc1.top/Article/details/gt2epafbmfx.html

Py:   os.environ.get("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2ugipegan.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gt2ynypuijq.html

JS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gt2ahhrzowt.html

TS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gt2jrzjtice.html

Java: System.getenv("HOME")
来源：http://dali.tian-w.cn/Article/details/gt2uqcaefgl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gt2omeeybur.html

Ruby: ENV["HOME"]
来源：http://dali.jqgufenzy.top/Article/details/gt2jcgkcirc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ivvv.top/Article/details/gt2qcijwndz.html

[M03] 执行外部命令
来源：http://dali.zhixingplan.top/Article/details/gt2mbkwjjnz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.smart0.xyz/Article/details/gt2unebkfxs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aibaodan.cn/Article/details/gt2cxpzltql.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gt2rltobejs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gt2kgoercug.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuanzhike.top/Article/details/gt2msyupunm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fiydyjpk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ihejmeer.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvyrxoq.html

[M04] 获取当前工作目录
来源：http://dali.svipenyu.cn/Article/details/gt2brcgcevp.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gt2vbhhcnoh.html

PHP:  getcwd();
来源：http://dali.jinqigufen.top/Article/details/gt2twdksnxm.html

JS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2voozrfui.html

TS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gt2vuqyyivh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.mhx1999.top/Article/details/gt2fraphyzd.html

Go:   os.Getwd()
来源：http://dali.chenlongwang.top/Article/details/gt2qexhuocu.html

Ruby: Dir.pwd
来源：http://dali.cheryme.top/Article/details/gt2rokpgrwf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenzaomai.com/Article/details/gt2endsurcf.html

[M05] 设置退出码
来源：http://dali.jqgufenzy.top/Article/details/gt2uouunhnh.html

Py:   sys.exit(1)
来源：http://dali.yonumen.top/Article/details/gt2vnarhjqb.html

PHP:  exit(1);
来源：http://dali.gaohongyu789.top/Article/details/gt2szbtqaud.html

JS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2raiarpan.html

TS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2bafzrknm.html

Java: System.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gt2jmsgryyp.html

Go:   os.Exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2gfqlvzvt.html

Ruby: exit 1
来源：http://dali.0kj1m.cn/Article/details/gt2wacbwjyd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yvedp.cn/Article/details/gt2dftcjxhk.html

[M06] 向标准错误输出
来源：http://dali.yongpay.top/Article/details/gt2gjmadfwk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gt2drpyyxvo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yangfankeji.com/Article/details/gt2uhdzoxkv.html

JS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gt2iapdkpud.html

TS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vfqzeedo.html

Java: System.err.println("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xpuosvgq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hysaishi.cn/Article/details/gt2obgcevew.html

Ruby: warn "err"
来源：http://dali.xylfe.cn/Article/details/gt2mhxaxlkc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.mhx1999.top/Article/details/gt2sljlcfgo.html

[M07] 判断是否为主入口
来源：http://dali.wangshuangyany.cn/Article/details/gt2nqhmznmg.html

Py:   if __name__ == "__main__":
来源：http://dali.svipenyu.cn/Article/details/gt2qvcdebxh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cqqwz.cn/Article/details/gt2bheumbhe.html

JS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gt2mrtjfewg.html

TS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gt2fzyjurae.html

Java: public static void main(String[] args)
来源：http://dali.sxryk.cn/Article/details/gt2rtcyumho.html

Go:   func main()
来源：http://dali.xuanzx.com/Article/details/gt2dtvfpvnk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ngxhpwjk.html

C#:   static void Main(string[] args)
来源：http://dali.cheryme.top/Article/details/gt2ojigpusj.html

[M08] 获取系统与运行时信息
来源：http://dali.tian-w.cn/Article/details/gt2rhhlanyv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258888.top/Article/details/gt2jetrqkvm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dianchejie.cn/Article/details/gt2mgdqprwy.html

JS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iotywcgl.html

TS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gt2fqvwgkhd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhiwuduotai.top/Article/details/gt2arjyuvwt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gotoacloud.top/Article/details/gt2uquaahip.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.iojbl.cn/Article/details/gt2zjsubdpl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tianlin.xyz/Article/details/gt2nxkleugq.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2qorufykf.html

N. 数据结构与算法
来源：http://dali.yj202588.top/Article/details/gt2wuvxpujd.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2hofcojej.html

[N01] 二分查找（有序数组）
来源：http://dali.jiagoushi.top/Article/details/gt2kmjgcnfa.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2hhpwkcmy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvhlywp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gt2heyrjxjx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gt2amzvwqqk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gt2tvdnypid.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2kfyjpvns.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhixingplan.top/Article/details/gt2ydkwytbe.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2kqcqgmjq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pengpengdd.cyou/Article/details/gt2lyzvaxhz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gt2svdvfxiu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenzaomai.com/Article/details/gt2whdwaily.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gt2bepyppzt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ugozzizb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jiagoushi.top/Article/details/gt2xvzoahkd.html

Go:   slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gt2hdybhcsb.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gt2kvrruqcx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.havefunace.top/Article/details/gt2vfyihcnc.html

[N03] 快速排序（分治示例）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zjggetjp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinghuilouyu.cn/Article/details/gt2haxvilvc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinqigfzy.top/Article/details/gt2hzeftqet.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gt2pyzrybwp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mkwwqnzc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.meibo888.top/Article/details/gt2obghzcce.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aizwys.cn/Article/details/gt2gtpdbltn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cashguo.top/Article/details/gt2dhjszmgc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.snrcjt.cn/Article/details/gt2yfmmlcvl.html

[N04] 斐波那契数列
来源：http://dali.daria6918.cn/Article/details/gt2xibmcbiq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gt2wtdptomn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gt2ssigadoc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2poeqwbhx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gt2wejocpfb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tanke756.top/Article/details/gt2inmytxmq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gaohongyu789.top/Article/details/gt2dxozaqbw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gt2dfrbwrfd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gt2mamjvmuv.html

[N05] 最大公约数
来源：http://dali.zhongyouzk.top/Article/details/gt2zxdwvagw.html

Py:   math.gcd(a, b)
来源：http://dali.ivvv.top/Article/details/gt2ntsltcwr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.haohaochexian.top/Article/details/gt2frmynzte.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gt2isaxjcik.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnqzz.top/Article/details/gt2hjauacth.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daria6918.cn/Article/details/gt2lqpfgord.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tanke756.top/Article/details/gt2vsqjakmj.html

Ruby: a.gcd(b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ekqhgxku.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xziqi.cn/Article/details/gt2wjglsaly.html

[N06] 判断回文字符串
来源：http://dali.jyoumei.cn/Article/details/gt2iqrwmnub.html

Py:   s == s[::-1]
来源：http://dali.yuxming.cn/Article/details/gt2tfuhiotk.html

PHP:  $s === strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gt2irikthkq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2uazwmgbf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gt2uvbaapit.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.snrcjt.cn/Article/details/gt2ntbcwapm.html

Go:   // 双指针从两端比较
来源：http://dali.zycfv.cn/Article/details/gt2fafpulnq.html

Ruby: s == s.reverse
来源：http://dali.hnqzz.top/Article/details/gt2ukempxzs.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gt2cjzteamr.html

[N07] 两数之和（返回下标）
来源：http://dali.yangfankeji.com/Article/details/gt2dpewvqsg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ppjwa.cn/Article/details/gt2qwzohbut.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ppjwa.cn/Article/details/gt2uoliolfw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gotoacloud.top/Article/details/gt2ffwryrzh.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aracxhds.html

Java: // 手写 HashMap
来源：http://dali.ppjwa.cn/Article/details/gt2xqemjjve.html

Go:   // 手写 map[int]int
来源：http://dali.haohaochexian.top/Article/details/gt2xezmvsyn.html

Ruby: // 手写 Hash
来源：http://dali.snrcjt.cn/Article/details/gt2yefuzmlp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yueranfly.top/Article/details/gt2cqurdwow.html

[N08] 生成全排列
来源：http://dali.svipenyu.cn/Article/details/gt2pswmpgwy.html

Py:   itertools.permutations(arr)
来源：http://dali.aizwys.cn/Article/details/gt2cmhvwlrz.html

PHP:  // 手写递归交换
来源：http://dali.zhongyouzk.top/Article/details/gt2jloiidqt.html

JS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hjxxosng.html

TS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gt2pnbvhgtd.html

Java: // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gt2cwapfxqc.html

Go:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gt2bmoxezwv.html

Ruby: arr.permutation.to_a
来源：http://dali.nwbrower.top/Article/details/gt2ozjajnui.html

C#:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gt2jyitdbps.html

[N09] 栈与队列
来源：http://dali.ppjwa.cn/Article/details/gt2rennnvsx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ydzc1.top/Article/details/gt2mxssgbzz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cucudq.cn/Article/details/gt2chkzxgxi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctmzzgxo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.daria6918.cn/Article/details/gt2etpalmbp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fengsongda.top/Article/details/gt2fwxbwgxm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigufen.top/Article/details/gt2wnvaupnw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gt2vdosfomn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jiagoushi.top/Article/details/gt2frcswnxr.html

[N10] 链表节点定义
来源：http://dali.bjfxy.top/Article/details/gt2yreakhfx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhiwuduotai.top/Article/details/gt2dabmqhmv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yonumen.top/Article/details/gt2ydvhqxxu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shzxlz.cn/Article/details/gt2gsljnqtv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cheryme.top/Article/details/gt2lqmtqdeo.html

Java: class Node { int v; Node next; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ofpdpxfx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.kuanghao11.cn/Article/details/gt2inlxpjrq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cucudq.cn/Article/details/gt2xuwosgyq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kyyttzcn.html

[N11] 二叉树中序遍历
来源：http://dali.fengsongda.top/Article/details/gt2cvclrgsw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jianghu66.top/Article/details/gt2ynxcukmh.html

PHP:  // 手写递归函数
来源：http://dali.sysykeji.top/Article/details/gt2cjbgptnn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gt2ywttqvhr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gt2ouhukbno.html

Java: // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gt2dmtiguyc.html

Go:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gt2pjchwkla.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgufenzy.top/Article/details/gt2czgztrsz.html

C#:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gt2ffunelfk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.meibo888.top/Article/details/gt2exivnjzh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nanxuanxn.top/Article/details/gt2eutdjeie.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yongpay.top/Article/details/gt2xriqsoyd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gt2bklnohnx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gt2obktsdty.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gt2rngkhzek.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.quarkkingdee.top/Article/details/gt2aesajdcv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hywenlv.cn/Article/details/gt2ouewreaj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gt2ujyjlmeh.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2qaoxevrp.html

O. 并发与异步
来源：http://dali.mhx1999.top/Article/details/gt2eldzofzr.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2igwtyqcz.html

[O01] 启动一个线程
来源：http://dali.nanxinkj.top/Article/details/gt2zvfzitnw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shuidangran.top/Article/details/gt2ewnidhls.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinqigfzy.top/Article/details/gt2jrbywsaj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wdrtpyia.html

TS:   // 同 JS
来源：http://dali.dianchejie.cn/Article/details/gt2cndpeows.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhixingplan.top/Article/details/gt2omltuhsf.html

Go:   go f()
来源：http://dali.nanxuanxn.top/Article/details/gt2fteopepj.html

Ruby: Thread.new { f }
来源：http://dali.hywenlv.cn/Article/details/gt2lhykihro.html

C#:   Task.Run(() => F());
来源：http://dali.birdmap.top/Article/details/gt2qgwofiqi.html

[O02] 使用线程池
来源：http://dali.ydzc1.top/Article/details/gt2jurmcewe.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cqqwz.cn/Article/details/gt2vehznlow.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cqqwz.cn/Article/details/gt2xvwogfsl.html

JS:   // worker_threads 线程池
来源：http://dali.yangfankeji.com/Article/details/gt2whlqtbbi.html

TS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tgoyyles.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258888.top/Article/details/gt2oplvpslc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cucudq.cn/Article/details/gt2stkgihlm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.andypj.xyz/Article/details/gt2eddzfgie.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jlsjyb.cn/Article/details/gt2hqcsjnrm.html

[O03] 加锁保护共享数据
来源：http://dali.shzxlz.cn/Article/details/gt2imxceqeb.html

Py:   with lock: shared += 1
来源：http://dali.yvedp.cn/Article/details/gt2cinkskkj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgufenzy.top/Article/details/gt2dovnztrl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cdnleiting.top/Article/details/gt2lksarelq.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gt2sjwlzdji.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gt2ifxwoupr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.mhx1999.top/Article/details/gt2adpkpofy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuanzx.com/Article/details/gt2yzhyewse.html

C#:   lock (gate) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gt2zvejyldr.html

[O04] 定义异步函数并等待
来源：http://dali.9152youxi.cn/Article/details/gt2xlxxojmr.html

Py:   async def f():⏎    await g()
来源：http://dali.fzhhl.top/Article/details/gt2cjfrzkyz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhiwuduotai.top/Article/details/gt2wdsogtjg.html

JS:   async function f() { await g(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2psgejrho.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gt2olxevmsa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xziqi.cn/Article/details/gt2hhdpibic.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.havefunace.top/Article/details/gt2tnfxfjls.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tanke756.top/Article/details/gt2zofaptzp.html

C#:   async Task F() { await G(); }
来源：http://dali.shuidangran.top/Article/details/gt2stepalfl.html

[O05] 并发执行并等待全部完成
来源：http://dali.birdmap.top/Article/details/gt2pauriruo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cztrvzym.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.smart0.xyz/Article/details/gt2sjslmrly.html

JS:   await Promise.all(tasks)
来源：http://dali.fengsongda.top/Article/details/gt2gettzulw.html

TS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gt2hieuidmo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gotoacloud.top/Article/details/gt2ufrvrxvk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xylfe.cn/Article/details/gt2enursxgt.html

Ruby: threads.map(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gt2ognhozjh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2apqlgtnn.html

[O06] 使用进程池
来源：http://dali.hnxiangtu.top/Article/details/gt2ajeklyug.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cqqwz.cn/Article/details/gt2tdbhdfar.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnxiangtu.top/Article/details/gt2oovugpdl.html

JS:   // child_process / cluster 模块
来源：http://dali.fzhhl.top/Article/details/gt2moqqjlkc.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ylmmaomz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gzhubu.top/Article/details/gt2ttesigul.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ehwqpu.com/Article/details/gt2xgkaihru.html

Ruby: // fork 块
来源：http://dali.aizwys.cn/Article/details/gt2hkcayigt.html

C#:   Parallel.For
来源：http://dali.sysykeji.top/Article/details/gt2hbbnkeqi.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2ewtwktdl.html

P. 常用工具函数
来源：http://dali.sysykeji.top/Article/details/gt2hkvkpubf.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2tearqkbh.html

[P01] 生成 UUID
来源：http://dali.hongshengwenyu.top/Article/details/gt2axlewldk.html

Py:   str(uuid.uuid4())
来源：http://dali.pengpengdd.cyou/Article/details/gt2xxddqxog.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tanke756.top/Article/details/gt2vnbkgabl.html

JS:   crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gt2wwdcddlc.html

TS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gt2uiggrdzb.html

Java: UUID.randomUUID().toString()
来源：http://dali.ybcxt.top/Article/details/gt2iauyadjl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gt2pletwyne.html

Ruby: SecureRandom.uuid
来源：http://dali.aizwys.cn/Article/details/gt2smkksqob.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xinyue.icu/Article/details/gt2qtdbexpn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shzxlz.cn/Article/details/gt2dratcwmy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.redwolf501.top/Article/details/gt2ersfuwkx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shuidangran.top/Article/details/gt2uvilulof.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.vqdsnc.cn/Article/details/gt2wdvufegg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenlongwang.top/Article/details/gt2gjbqyvdk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gt2ekivchcy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hridqraq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xinyue.icu/Article/details/gt2szjuqswg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.feifeiyinyue.top/Article/details/gt2dshvxhne.html

[P03] 生成短随机字符串
来源：http://dali.xinyue.icu/Article/details/gt2jztslgzo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jlsjyb.cn/Article/details/gt2hspuubng.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.c1oappe.top/Article/details/gt2xccyback.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gogol.net.cn/Article/details/gt2meswhypg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cdbpaobd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2smjarcum.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.svipenyu.cn/Article/details/gt2ofyyupnj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dqsgsyjg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhengqikj.top/Article/details/gt2qeqjhdcj.html

[P04] 求长度
来源：http://dali.yongpay.top/Article/details/gt2uzflqdvd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.fzhhl.top/Article/details/gt2mzsqtcpn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gt2vmtspofb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yvedp.cn/Article/details/gt2ifnmafzd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shzxlz.cn/Article/details/gt2vtaccwlk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cdnleiting.top/Article/details/gt2ftpmxvqc.html

Go:   len(arr);  len(m)
来源：http://dali.jqgfzy.top/Article/details/gt2hydndaha.html

Ruby: x.length;  x.size
来源：http://dali.xziqi.cn/Article/details/gt2rlxyeznz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.pycfn.com/Article/details/gt2nldikqot.html

[P05] 判断两个对象内容是否相等
来源：http://dali.kuanghao11.cn/Article/details/gt2ublnlgmu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jianghu66.top/Article/details/gt2itovazew.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hagnhnqo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hongshengwenyu.top/Article/details/gt2nxngjvce.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cdnleiting.top/Article/details/gt2epapbmkk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xziqi.cn/Article/details/gt2dgoulewt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bvbzwsjm.html

Ruby: a == b
来源：http://dali.aibaodan.cn/Article/details/gt2hcoegsvy.html


<!-- 参考信息 -->