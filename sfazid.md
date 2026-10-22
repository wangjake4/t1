代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gt2hslbxdlc.html

Java: resp.statusCode()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ipdymysx.html

Go:   resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gt2ytmpkjcu.html

Ruby: resp.code.to_i
来源：http://dali.zhongyouzk.top/Article/details/gt2yegwyywq.html

C#:   (int)resp.StatusCode
来源：http://dali.sufxvd.cn/Article/details/gt2rswsnwox.html

[L08] 并发请求多个地址
来源：http://dali.dianchejie.cn/Article/details/gt2csghejsp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pyqnbpbh.html

PHP:  curl_multi_init() 系列
来源：http://dali.ybcxt.top/Article/details/gt2ymtcmsgy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gt2irmbaary.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gt2esekduun.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2movcmnma.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nwbrower.top/Article/details/gt2ograhbnb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zycfv.cn/Article/details/gt2mlzqmyet.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sweek.top/Article/details/gt2pqbhsnte.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2csewuilf.html

M. 命令行 / 进程 / 环境
来源：http://dali.hysaishi.cn/Article/details/gt2wjnruhdj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2qfkwwrnk.html

[M01] 读取命令行参数
来源：http://dali.aizwys.cn/Article/details/gt2exvlrtpv.html

Py:   sys.argv[1:]
来源：http://dali.xylfe.cn/Article/details/gt2jbrzfufs.html

PHP:  $argv;  $argc;
来源：http://dali.yj202588.top/Article/details/gt2syvwpxcp.html

JS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gt2pojvtvhz.html

TS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gt2qnprbntp.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gt2oqxyutqm.html

Go:   os.Args[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gt2gorxjire.html

Ruby: ARGV
来源：http://dali.yuxming.cn/Article/details/gt2slzqeggz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gt2camccdue.html

[M02] 读取环境变量
来源：http://dali.zhengqikj.top/Article/details/gt2polxmzaz.html

Py:   os.environ.get("HOME")
来源：http://dali.mhx1999.top/Article/details/gt2qxrydrns.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2anccydoo.html

JS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gt2cjpclmiu.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gt2dvkzfyhf.html

Java: System.getenv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gt2ofnctloq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.birdmap.top/Article/details/gt2tuztpaup.html

Ruby: ENV["HOME"]
来源：http://dali.yvedp.cn/Article/details/gt2bgdguopi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oyiykdzv.html

[M03] 执行外部命令
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2svvxuyag.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigufen.top/Article/details/gt2attuyzuq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aibaodan.cn/Article/details/gt2wmdizrrr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gt2qbshqsye.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gt2hfhhlxdk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cqqwz.cn/Article/details/gt2keigngib.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shzxlz.cn/Article/details/gt2eoenbcka.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xinyue.icu/Article/details/gt2nkpzxzjz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sxryk.cn/Article/details/gt2ekmfirvy.html

[M04] 获取当前工作目录
来源：http://dali.pengpengdd.cyou/Article/details/gt2nuutjzbi.html

Py:   os.getcwd()
来源：http://dali.cqqwz.cn/Article/details/gt2qfekzhzb.html

PHP:  getcwd();
来源：http://dali.nanxinkj.top/Article/details/gt2tgyydmag.html

JS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gt2brdzjgfi.html

TS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2fruoqfxb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuanzhike.top/Article/details/gt2wygqopps.html

Go:   os.Getwd()
来源：http://dali.smart0.xyz/Article/details/gt2zwmtbplf.html

Ruby: Dir.pwd
来源：http://dali.hywenlv.cn/Article/details/gt2kpheecfs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxinkj.top/Article/details/gt2laoygqwx.html

[M05] 设置退出码
来源：http://dali.cucudq.cn/Article/details/gt2zwzcdtuo.html

Py:   sys.exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2lcaiurhz.html

PHP:  exit(1);
来源：http://dali.fzhhl.top/Article/details/gt2stlbjscc.html

JS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gt2snefxghq.html

TS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2hbeagyaw.html

Java: System.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2znobyhlx.html

Go:   os.Exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2swzvgban.html

Ruby: exit 1
来源：http://dali.redwolf501.top/Article/details/gt2paynswai.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tian-w.cn/Article/details/gt2zgokwplb.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhvnmem.html

Py:   print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gt2dgdqpwxe.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigufen.top/Article/details/gt2gdpngmxz.html

JS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gt2qeqdotaq.html

TS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gt2jfqoejaq.html

Java: System.err.println("err")
来源：http://dali.9152youxi.cn/Article/details/gt2rhhifnun.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wjfajmpd.html

Ruby: warn "err"
来源：http://dali.yvedp.cn/Article/details/gt2haypicbt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258888.top/Article/details/gt2envtprrp.html

[M07] 判断是否为主入口
来源：http://dali.haohaochexian.top/Article/details/gt2orzmzbui.html

Py:   if __name__ == "__main__":
来源：http://dali.svipenyu.cn/Article/details/gt2yisaypkh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vukmrrnu.html

JS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gt2dmaoyoos.html

TS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gt2wvbsgylb.html

Java: public static void main(String[] args)
来源：http://dali.iojbl.cn/Article/details/gt2qkvpfuyc.html

Go:   func main()
来源：http://dali.gzhubu.top/Article/details/gt2ndwtgfxt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ppjwa.cn/Article/details/gt2fnsqbpiv.html

C#:   static void Main(string[] args)
来源：http://dali.zycfv.cn/Article/details/gt2vcfxssdj.html

[M08] 获取系统与运行时信息
来源：http://dali.fzhhl.top/Article/details/gt2znaprsyb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dashuyun.cn/Article/details/gt2irhstdcr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangshuangyany.cn/Article/details/gt2bmorzkcy.html

JS:   process.platform;  process.version
来源：http://dali.gogol.net.cn/Article/details/gt2ermddhdu.html

TS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gt2cktecvdc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.meibo888.top/Article/details/gt2craqbyde.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yonumen.top/Article/details/gt2ppnecorn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shangyingyoupin.top/Article/details/gt2nnhghdcn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yanxiufei.cn/Article/details/gt2mmoyhxcg.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2gyoaaxey.html

N. 数据结构与算法
来源：http://dali.snrcjt.cn/Article/details/gt2hptdmxzu.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2vkswbwif.html

[N01] 二分查找（有序数组）
来源：http://dali.0kj1m.cn/Article/details/gt2iwovnyxa.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2hicmpkxl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nwbrower.top/Article/details/gt2hbmgvybm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gt2jsouoznt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gt2xkwuxshe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2ekflkekz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2oucutghi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yanxiufei.cn/Article/details/gt2utgvuvnf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2czpolttb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenjidiqi.icu/Article/details/gt2sdumxbjr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gt2lgaljlpm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zycfv.cn/Article/details/gt2mhjmcatc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gt2nfejashv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gt2fcupnbzd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.meibo888.top/Article/details/gt2xbittpzs.html

Go:   slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2djjvxqie.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zvhgwvlq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhixingplan.top/Article/details/gt2acvilxed.html

[N03] 快速排序（分治示例）
来源：http://dali.yongpay.top/Article/details/gt2mepkkrbb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xziqi.cn/Article/details/gt2udmwgctx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tanke756.top/Article/details/gt2oclpnelt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2neclghca.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gt2rlrawyxn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuetiantiany.cn/Article/details/gt2ngybjsgr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuetiantiany.cn/Article/details/gt2pwqvdjqv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shzxlz.cn/Article/details/gt2atbqxvcw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tanke756.top/Article/details/gt2qrkejzfw.html

[N04] 斐波那契数列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vinrrnlf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cheryme.top/Article/details/gt2rgsupajw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.mhx1999.top/Article/details/gt2ivxguays.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gt2nawlhfdv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gt2pudbiepn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tian-w.cn/Article/details/gt2lhvdddth.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.havefunace.top/Article/details/gt2vxozyfxm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.mhx1999.top/Article/details/gt2ddpyzxjk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gt2tersmqms.html

[N05] 最大公约数
来源：http://dali.hammf.cn/Article/details/gt2dinqehkq.html

Py:   math.gcd(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sojxworb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tian-w.cn/Article/details/gt2dlpapuui.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gt2hjeixnpr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yueranfly.top/Article/details/gt2znkvefup.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guowangkeji.top/Article/details/gt2svlgwwgf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nwbrower.top/Article/details/gt2ubqicvra.html

Ruby: a.gcd(b)
来源：http://dali.ppjwa.cn/Article/details/gt2fjyxvqdz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.c1oappe.top/Article/details/gt2wwaevdmf.html

[N06] 判断回文字符串
来源：http://dali.chenzaomai.com/Article/details/gt2apbetsnr.html

Py:   s == s[::-1]
来源：http://dali.sufxvd.cn/Article/details/gt2origlurt.html

PHP:  $s === strrev($s);
来源：http://dali.cqqwz.cn/Article/details/gt2qqjziljw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2pwrtevmy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2kbfzkerc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.andypj.xyz/Article/details/gt2ljtusjrc.html

Go:   // 双指针从两端比较
来源：http://dali.ehwqpu.com/Article/details/gt2ctjgsytd.html

Ruby: s == s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eifnoceh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gt2vgthsqty.html

[N07] 两数之和（返回下标）
来源：http://dali.sweek.top/Article/details/gt2tsvhbazm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hhobbcfc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.c1oappe.top/Article/details/gt2gigpfefe.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhixingplan.top/Article/details/gt2hocjekgk.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258.top/Article/details/gt2jcdrupvg.html

Java: // 手写 HashMap
来源：http://dali.xuanzx.com/Article/details/gt2zwchdtkr.html

Go:   // 手写 map[int]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jbbpiiri.html

Ruby: // 手写 Hash
来源：http://dali.ppjwa.cn/Article/details/gt2wvrmozda.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gzhubu.top/Article/details/gt2tmgequif.html

[N08] 生成全排列
来源：http://dali.gzhubu.top/Article/details/gt2jisbotgq.html

Py:   itertools.permutations(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2fvnrxonm.html

PHP:  // 手写递归交换
来源：http://dali.0kj1m.cn/Article/details/gt2bvsvwdqq.html

JS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2alifbods.html

TS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2lenlonpc.html

Java: // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gt2rvvtvsws.html

Go:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gt2hssaolkw.html

Ruby: arr.permutation.to_a
来源：http://dali.hnqzz.top/Article/details/gt2iasbthnb.html

C#:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gt2zmwsusjz.html

[N09] 栈与队列
来源：http://dali.zycfv.cn/Article/details/gt2dcgavdab.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hysaishi.cn/Article/details/gt2dtwsfgme.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gt2mbyfxmlq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gt2ixggsarw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tianlin.xyz/Article/details/gt2ikawujoj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.iojbl.cn/Article/details/gt2codquzsl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258.top/Article/details/gt2fexpnbqk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gt2yiglywnb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sxryk.cn/Article/details/gt2xqxtikgu.html

[N10] 链表节点定义
来源：http://dali.iojbl.cn/Article/details/gt2hrtrmlkb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gaohongyu789.top/Article/details/gt2kbeieotv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnqzz.top/Article/details/gt2arlonxvr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zdqjudy.top/Article/details/gt2jppkrwcw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigfzy.top/Article/details/gt2fulbzpgk.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258888.top/Article/details/gt2gmarscgc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hongshengwenyu.top/Article/details/gt2btauvlai.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.redwolf501.top/Article/details/gt2dcgwhtot.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dashuyun.cn/Article/details/gt2qdyanfju.html

[N11] 二叉树中序遍历
来源：http://dali.hywenlv.cn/Article/details/gt2tbesoibh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhiwuduotai.top/Article/details/gt2rokyytpu.html

PHP:  // 手写递归函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2zuunhrqf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gt2hwvnmydf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gt2kaefypxm.html

Java: // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gt2umvdldsg.html

Go:   // 手写递归
来源：http://dali.smart0.xyz/Article/details/gt2mcgdfqwk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sysykeji.top/Article/details/gt2jsqkdehr.html

C#:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2fxdlitvi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nwbrower.top/Article/details/gt2zdkieflj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nwbrower.top/Article/details/gt2txprrvsl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yuanzhike.top/Article/details/gt2oppslsba.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gt2dwtaffwp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnqzz.top/Article/details/gt2lnsfbaok.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gt2ruqvjzfw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zdqjudy.top/Article/details/gt2jqrnteuo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhengqikj.top/Article/details/gt2kouhzdwr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gt2qricblsd.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2iububaxi.html

O. 并发与异步
来源：http://dali.yongpay.top/Article/details/gt2jfxpyruv.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2pwvxwsyd.html

[O01] 启动一个线程
来源：http://dali.snrcjt.cn/Article/details/gt2tjnlbwed.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gzhubu.top/Article/details/gt2rgzlntsh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jqgufenzy.top/Article/details/gt2jfdrcigv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangdashe.top/Article/details/gt2dtxcgxli.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gt2dviwrtul.html

Java: new Thread(() -> f()).start()
来源：http://dali.shuidangran.top/Article/details/gt2ncigpjup.html

Go:   go f()
来源：http://dali.cqqwz.cn/Article/details/gt2wpyhaqmi.html

Ruby: Thread.new { f }
来源：http://dali.yuanzhike.top/Article/details/gt2ppziarjs.html

C#:   Task.Run(() => F());
来源：http://dali.fzhhl.top/Article/details/gt2ihekmtaz.html

[O02] 使用线程池
来源：http://dali.guowangkeji.top/Article/details/gt2dqfjxmng.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jyoumei.cn/Article/details/gt2yqasbwlz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hywenlv.cn/Article/details/gt2olnwgqxy.html

JS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gt2gcgvhmqf.html

TS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gt2bvolnehc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nusqenss.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.mhx1999.top/Article/details/gt2oepqdvao.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.bjfxy.top/Article/details/gt2memwrxnf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.aibaodan.cn/Article/details/gt2mhxpiwbb.html

[O03] 加锁保护共享数据
来源：http://dali.ehwqpu.com/Article/details/gt2rlkcyihb.html

Py:   with lock: shared += 1
来源：http://dali.gogol.net.cn/Article/details/gt2byhdufbp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.iojbl.cn/Article/details/gt2fxiobjhl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2oiywfzyb.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2junkvjeq.html

Java: synchronized (this) { shared++; }
来源：http://dali.hammf.cn/Article/details/gt2gmdkspbv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangshuangyany.cn/Article/details/gt2iifwwcfk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhixingplan.top/Article/details/gt2pbbyofvz.html

C#:   lock (gate) { shared++; }
来源：http://dali.9152youxi.cn/Article/details/gt2ptptdkly.html

[O04] 定义异步函数并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tficwmne.html

Py:   async def f():⏎    await g()
来源：http://dali.zhongyouzk.top/Article/details/gt2yjqsqxyv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.haohaochexian.top/Article/details/gt2mzxogzzl.html

JS:   async function f() { await g(); }
来源：http://dali.sxryk.cn/Article/details/gt2ruyhasff.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gt2qcxrwhta.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sufxvd.cn/Article/details/gt2cqgkglxa.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.guannengcc.top/Article/details/gt2ylebilbt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.316326.xyz/Article/details/gt2lcwlqedz.html

C#:   async Task F() { await G(); }
来源：http://dali.gotoacloud.top/Article/details/gt2ujzugtqg.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenzaomai.com/Article/details/gt2pwmwmvbz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yongpay.top/Article/details/gt2vobgqgsk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jqgfzy.top/Article/details/gt2vpkctcwn.html

JS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gt2veayldzs.html

TS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gt2vxlkxvra.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhengqikj.top/Article/details/gt2xgcrkzuz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hfpthk.cn/Article/details/gt2iynzehaz.html

Ruby: threads.map(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pptjnxlc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vffqkytl.html

[O06] 使用进程池
来源：http://dali.andypj.xyz/Article/details/gt2ckbwcywa.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojoybfgt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yvedp.cn/Article/details/gt2zydmldhr.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxnmofn.html

TS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gt2dfyoxggf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258888.top/Article/details/gt2nrlefimx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zdqjudy.top/Article/details/gt2ktrjdijp.html

Ruby: // fork 块
来源：http://dali.dashuyun.cn/Article/details/gt2knkripfq.html

C#:   Parallel.For
来源：http://dali.chenzaomai.com/Article/details/gt2mxadwheb.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2utnzuzpe.html

P. 常用工具函数
来源：http://dali.smart0.xyz/Article/details/gt2dmzibpet.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2xlalolje.html

[P01] 生成 UUID
来源：http://dali.wangshuangyany.cn/Article/details/gt2ywokkefa.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258.top/Article/details/gt2dzuteoqd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fzhhl.top/Article/details/gt2znlsexkn.html

JS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gt2gaosoban.html

TS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gt2eyudkmzu.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhoulong.xyz/Article/details/gt2jlkxnozj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guannengcc.top/Article/details/gt2nkautkjl.html

Ruby: SecureRandom.uuid
来源：http://dali.yangfankeji.com/Article/details/gt2telszzdg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dianchejie.cn/Article/details/gt2hofccxdv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuxming.cn/Article/details/gt2eaeqiome.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gotoacloud.top/Article/details/gt2ihmxavvp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2oaasgitq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pycfn.com/Article/details/gt2hcokfzqk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vvkgmige.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxinkj.top/Article/details/gt2imawmiiq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zycfv.cn/Article/details/gt2vqiznzgx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2bzvnpaps.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnxiangtu.top/Article/details/gt2lsnrcymd.html

[P03] 生成短随机字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xmgvlphl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.316326.xyz/Article/details/gt2bzdqgxpx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuxming.cn/Article/details/gt2tbfyctud.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2masqdvih.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2rbpeyqvv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.haohaochexian.top/Article/details/gt2qcrllxrx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gogol.net.cn/Article/details/gt2tiszacpx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2oijdbirk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ybcxt.top/Article/details/gt2yzvcwqre.html

[P04] 求长度
来源：http://dali.wangdashe.top/Article/details/gt2aalvjidu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sufxvd.cn/Article/details/gt2fqnukgnr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gt2ikfrlmpy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zdqjudy.top/Article/details/gt2euapzbpp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yueranfly.top/Article/details/gt2sbtvmjda.html

Java: list.size();  map.size();  s.length()
来源：http://dali.0kj1m.cn/Article/details/gt2qbflwvvl.html

Go:   len(arr);  len(m)
来源：http://dali.xylfe.cn/Article/details/gt2zevqjpmz.html

Ruby: x.length;  x.size
来源：http://dali.yangfankeji.com/Article/details/gt2xrvwcsnx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jianghu66.top/Article/details/gt2toeftqds.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jyoumei.cn/Article/details/gt2haocgkys.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hongshengwenyu.top/Article/details/gt2bhlfzcfr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhiwuduotai.top/Article/details/gt2pgkrjyqw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.andypj.xyz/Article/details/gt2btbccuac.html


<!-- 参考信息 -->