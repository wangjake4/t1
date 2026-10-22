代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gt2uzekvpad.html

Java: resp.statusCode()
来源：http://dali.havefunace.top/Article/details/gt2ofwecqmm.html

Go:   resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gt2cqtdggvf.html

Ruby: resp.code.to_i
来源：http://dali.daria6918.cn/Article/details/gt2ijendntw.html

C#:   (int)resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gt2lahmvtau.html

[L08] 并发请求多个地址
来源：http://dali.fengsongda.top/Article/details/gt2hfbwhfxn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ydzc1.top/Article/details/gt2ashorxmf.html

PHP:  curl_multi_init() 系列
来源：http://dali.pengpengdd.cyou/Article/details/gt2ihyzaajk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gt2kjelemcf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gt2jikezsyj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhengqikj.top/Article/details/gt2spsyjywf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hysaishi.cn/Article/details/gt2bikndtpz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.daria6918.cn/Article/details/gt2zlqgeyyi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenlongwang.top/Article/details/gt2pjjadwqi.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2dobrkttp.html

M. 命令行 / 进程 / 环境
来源：http://dali.pycfn.com/Article/details/gt2uyjliodq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2bfnqpowb.html

[M01] 读取命令行参数
来源：http://dali.havefunace.top/Article/details/gt2vszekgrq.html

Py:   sys.argv[1:]
来源：http://dali.tianlin.xyz/Article/details/gt2tcakombv.html

PHP:  $argv;  $argc;
来源：http://dali.svipenyu.cn/Article/details/gt2axpncnyc.html

JS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gt2gwxevztl.html

TS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gt2sgdchxns.html

Java: args 数组（main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gt2diruholr.html

Go:   os.Args[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kqqmgmdt.html

Ruby: ARGV
来源：http://dali.sxryk.cn/Article/details/gt2psoavlwp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gt2yudsnxha.html

[M02] 读取环境变量
来源：http://dali.fengsongda.top/Article/details/gt2kfrqiyjo.html

Py:   os.environ.get("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2xkggaldv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gt2smxzzshs.html

JS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gt2kdrgiahr.html

TS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gt2fmzrzxma.html

Java: System.getenv("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2ixtigkow.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ybpkxnan.html

Ruby: ENV["HOME"]
来源：http://dali.yj20258.top/Article/details/gt2ylirmizq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daxiang520.top/Article/details/gt2haggquzi.html

[M03] 执行外部命令
来源：http://dali.sysykeji.top/Article/details/gt2raamwccm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cdnleiting.top/Article/details/gt2gcvzhuwr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daria6918.cn/Article/details/gt2pmdubnni.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gt2cypjntlj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gt2excmcqxi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxuanxn.top/Article/details/gt2zffjbhum.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zdqjudy.top/Article/details/gt2xxhzbmlt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangshuangyany.cn/Article/details/gt2htxqprwq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.redwolf501.top/Article/details/gt2eluqrwcl.html

[M04] 获取当前工作目录
来源：http://dali.nanxinkj.top/Article/details/gt2rgkedfzn.html

Py:   os.getcwd()
来源：http://dali.yj202588.top/Article/details/gt2nxtxjmsx.html

PHP:  getcwd();
来源：http://dali.yuxming.cn/Article/details/gt2vhebkeix.html

JS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gt2cstwowdw.html

TS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gt2jxliiosq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gt2vaeyxdnd.html

Go:   os.Getwd()
来源：http://dali.yj20258888.top/Article/details/gt2mmnmrgow.html

Ruby: Dir.pwd
来源：http://dali.xinyue.icu/Article/details/gt2btcwhuob.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yanxiufei.cn/Article/details/gt2zrippjcw.html

[M05] 设置退出码
来源：http://dali.tanke756.top/Article/details/gt2iktqshrz.html

Py:   sys.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2iyqkgfyw.html

PHP:  exit(1);
来源：http://dali.gotoacloud.top/Article/details/gt2pxcegwra.html

JS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gt2hahptish.html

TS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gt2qknsifqm.html

Java: System.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gt2kamyppnu.html

Go:   os.Exit(1)
来源：http://dali.hammf.cn/Article/details/gt2ezrjxzaf.html

Ruby: exit 1
来源：http://dali.wangdashe.top/Article/details/gt2urnsdxbj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cqqwz.cn/Article/details/gt2kkqameli.html

[M06] 向标准错误输出
来源：http://dali.redwolf501.top/Article/details/gt2twbdsbxw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.mhx1999.top/Article/details/gt2wmiwvkkn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.birdmap.top/Article/details/gt2mmlpqamz.html

JS:   console.error("err")
来源：http://dali.chenjidiqi.icu/Article/details/gt2gcknuvjv.html

TS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gt2jjtxdzgo.html

Java: System.err.println("err")
来源：http://dali.shuidangran.top/Article/details/gt2jdoaudqx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ydzc1.top/Article/details/gt2epartsqj.html

Ruby: warn "err"
来源：http://dali.fzhhl.top/Article/details/gt2vfgcimds.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.snrcjt.cn/Article/details/gt2fswaltdb.html

[M07] 判断是否为主入口
来源：http://dali.gaohongyu789.top/Article/details/gt2drkmsynf.html

Py:   if __name__ == "__main__":
来源：http://dali.pycfn.com/Article/details/gt2dhdmdoio.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jiagoushi.top/Article/details/gt2dqeaxham.html

JS:   require.main === module
来源：http://dali.sysykeji.top/Article/details/gt2uubcfhxu.html

TS:   require.main === module
来源：http://dali.cqqwz.cn/Article/details/gt2qdscxyqn.html

Java: public static void main(String[] args)
来源：http://dali.yuxming.cn/Article/details/gt2suyxaaml.html

Go:   func main()
来源：http://dali.dianchejie.cn/Article/details/gt2nnhsnytc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xinyue.icu/Article/details/gt2lslqksvc.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yocjeqay.html

[M08] 获取系统与运行时信息
来源：http://dali.tian-w.cn/Article/details/gt2ruwbduct.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gzhubu.top/Article/details/gt2kzpgolsv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.9152youxi.cn/Article/details/gt2vldmuqou.html

JS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gt2azbxrxpu.html

TS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gt2pugmctby.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhengqikj.top/Article/details/gt2hykbiebc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhengqikj.top/Article/details/gt2anibdeee.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gt2dpjqcaqo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cheryme.top/Article/details/gt2nayhxlxs.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2xemauwpx.html

N. 数据结构与算法
来源：http://dali.havefunace.top/Article/details/gt2tvjabkrz.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2glpambhb.html

[N01] 二分查找（有序数组）
来源：http://dali.ydzc1.top/Article/details/gt2tqykbgif.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2aaujmtmn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hfpthk.cn/Article/details/gt2hmckplqd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gt2icawrqkr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gt2roddmfqs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcaiddbn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2nxcwljjl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ppjwa.cn/Article/details/gt2zrkbvwuq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.316326.xyz/Article/details/gt2qzstrrlq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ppjwa.cn/Article/details/gt2dmovdjud.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuanzhike.top/Article/details/gt2qmbbjbyv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ybcxt.top/Article/details/gt2dhxspmtj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jklvnqom.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gt2ydqabtso.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yanxiufei.cn/Article/details/gt2kcxlwmws.html

Go:   slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gt2ppivzuvu.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gt2yabwpnjl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.andypj.xyz/Article/details/gt2qsvxuspc.html

[N03] 快速排序（分治示例）
来源：http://dali.c1oappe.top/Article/details/gt2hjnqwbta.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258.top/Article/details/gt2nzwthmui.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hammf.cn/Article/details/gt2eaqtelfa.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gt2aqskcuwe.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxqyvyr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenzaomai.com/Article/details/gt2zdmhieny.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangdashe.top/Article/details/gt2rhydjiav.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cucudq.cn/Article/details/gt2ieixoapy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.quarkkingdee.top/Article/details/gt2twedixpc.html

[N04] 斐波那契数列
来源：http://dali.jyoumei.cn/Article/details/gt2hffajiib.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bzgygpca.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gt2oyrqryse.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gt2fsaqxxgb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gt2oktgreun.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tanke756.top/Article/details/gt2gvbbtcjg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guowangkeji.top/Article/details/gt2stystimk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2elgedkwc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gt2flihgpax.html

[N05] 最大公约数
来源：http://dali.yj202588.top/Article/details/gt2zrxnockj.html

Py:   math.gcd(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gt2yhuugdlm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hfpthk.cn/Article/details/gt2ajxzoqtp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gt2cttypinj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gt2yooigqid.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigufen.top/Article/details/gt2xnbdpysv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yongpay.top/Article/details/gt2clhlazad.html

Ruby: a.gcd(b)
来源：http://dali.cucudq.cn/Article/details/gt2jmirnsyu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hywenlv.cn/Article/details/gt2ndlyipgs.html

[N06] 判断回文字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2tpkdflgx.html

Py:   s == s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gt2mnexuwps.html

PHP:  $s === strrev($s);
来源：http://dali.zycfv.cn/Article/details/gt2kcawqaer.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gt2kluddxjb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gt2wkjxtmot.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gzhubu.top/Article/details/gt2gsqmkypa.html

Go:   // 双指针从两端比较
来源：http://dali.zdqjudy.top/Article/details/gt2wnejbjeg.html

Ruby: s == s.reverse
来源：http://dali.chenzaomai.com/Article/details/gt2smwpshmj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gt2lptyuulv.html

[N07] 两数之和（返回下标）
来源：http://dali.sxryk.cn/Article/details/gt2equqsvxa.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sqqbljvn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jyoumei.cn/Article/details/gt2wrdyvses.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhixingplan.top/Article/details/gt2memoezrn.html

TS:   // 手写 Map<string, number>
来源：http://dali.feifeiyinyue.top/Article/details/gt2elspvxjn.html

Java: // 手写 HashMap
来源：http://dali.jinqigfzy.top/Article/details/gt2igbivjyy.html

Go:   // 手写 map[int]int
来源：http://dali.andypj.xyz/Article/details/gt2ensbplci.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gt2cuksqmfr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.meibo888.top/Article/details/gt2pimdrhjv.html

[N08] 生成全排列
来源：http://dali.yuanzhike.top/Article/details/gt2sgwsfktt.html

Py:   itertools.permutations(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2meukzgap.html

PHP:  // 手写递归交换
来源：http://dali.jinqigufen.top/Article/details/gt2qcvdgruy.html

JS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2bxvmflqe.html

TS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2diipmeub.html

Java: // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gt2khcldyup.html

Go:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gt2jckkwmws.html

Ruby: arr.permutation.to_a
来源：http://dali.gaohongyu789.top/Article/details/gt2egxzzxnx.html

C#:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2jzyvuulo.html

[N09] 栈与队列
来源：http://dali.dashuyun.cn/Article/details/gt2mxlsvsld.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cheryme.top/Article/details/gt2uhoibuvi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.birdmap.top/Article/details/gt2tmjdauka.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gt2xnznfzfd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258888.top/Article/details/gt2zftekmfd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258888.top/Article/details/gt2zjolppsl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cheryme.top/Article/details/gt2mltrljja.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gt2gneipxqn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenzaomai.com/Article/details/gt2fhnppbcl.html

[N10] 链表节点定义
来源：http://dali.jqgfzy.top/Article/details/gt2acrpodgp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgufenzy.top/Article/details/gt2pdfemwbs.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.wangdashe.top/Article/details/gt2jpbiulkl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ghqblftu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.kuanghao11.cn/Article/details/gt2zwhpuefp.html

Java: class Node { int v; Node next; }
来源：http://dali.sweek.top/Article/details/gt2tsioccel.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ydzc1.top/Article/details/gt2aaroschp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnqzz.top/Article/details/gt2hybmwwhz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yangfankeji.com/Article/details/gt2bdtawbej.html

[N11] 二叉树中序遍历
来源：http://dali.cqqwz.cn/Article/details/gt2eehlvnre.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj202588.top/Article/details/gt2vtndybug.html

PHP:  // 手写递归函数
来源：http://dali.sweek.top/Article/details/gt2oxnxvlio.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dopzcovp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gt2qlfenfwz.html

Java: // 手写递归
来源：http://dali.yvedp.cn/Article/details/gt2viuflcdo.html

Go:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gt2bhnkmxxi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.daria6918.cn/Article/details/gt2kkmxefiv.html

C#:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gt2xcsjmwlj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pvsbmmfo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.snrcjt.cn/Article/details/gt2kqxngeej.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.dashuyun.cn/Article/details/gt2opjbqfwz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gt2iyqpimof.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.snrcjt.cn/Article/details/gt2dtwbwdap.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.smart0.xyz/Article/details/gt2bgfbzola.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uvuarssx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zycfv.cn/Article/details/gt2sxrmzljo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenzaomai.com/Article/details/gt2xadzmwae.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2zdefqwdp.html

O. 并发与异步
来源：http://dali.vqdsnc.cn/Article/details/gt2doytodsc.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2jlqsmlio.html

[O01] 启动一个线程
来源：http://dali.yuxming.cn/Article/details/gt2bshrdyds.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangdashe.top/Article/details/gt2gzhsblbs.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gzhubu.top/Article/details/gt2mjjyxowo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sysykeji.top/Article/details/gt2yvbvfieu.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gt2bphnbkyf.html

Java: new Thread(() -> f()).start()
来源：http://dali.9152youxi.cn/Article/details/gt2vzvtyvgb.html

Go:   go f()
来源：http://dali.cheryme.top/Article/details/gt2udbiduyt.html

Ruby: Thread.new { f }
来源：http://dali.fzhhl.top/Article/details/gt2birnenzp.html

C#:   Task.Run(() => F());
来源：http://dali.guowangkeji.top/Article/details/gt2pmllplne.html

[O02] 使用线程池
来源：http://dali.cashguo.top/Article/details/gt2jigaslir.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tfclbgjm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jyoumei.cn/Article/details/gt2qiplwumk.html

JS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gt2ylytrnzs.html

TS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gt2xxswxnrd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangdashe.top/Article/details/gt2yzovaljo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuxming.cn/Article/details/gt2lwvftzok.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cucudq.cn/Article/details/gt2ywspscfo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sxryk.cn/Article/details/gt2wrwllvpf.html

[O03] 加锁保护共享数据
来源：http://dali.daria6918.cn/Article/details/gt2cebwhkws.html

Py:   with lock: shared += 1
来源：http://dali.meibo888.top/Article/details/gt2dotfscia.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gaohongyu789.top/Article/details/gt2bsypkgvk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2awtbasmp.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gt2zuyvgfqq.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gt2kmpsafeb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuxming.cn/Article/details/gt2khmprihv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cqqwz.cn/Article/details/gt2hmtagnjv.html

C#:   lock (gate) { shared++; }
来源：http://dali.smart0.xyz/Article/details/gt2cnszdbha.html

[O04] 定义异步函数并等待
来源：http://dali.yangfankeji.com/Article/details/gt2aubbqtdn.html

Py:   async def f():⏎    await g()
来源：http://dali.birdmap.top/Article/details/gt2ggivnwou.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenzaomai.com/Article/details/gt2lxktsfbi.html

JS:   async function f() { await g(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2garrhkjh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gt2mcmtknmc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ysuoruye.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigfzy.top/Article/details/gt2eulxxnap.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2akimhzxo.html

C#:   async Task F() { await G(); }
来源：http://dali.havefunace.top/Article/details/gt2fkjygmtd.html

[O05] 并发执行并等待全部完成
来源：http://dali.cheryme.top/Article/details/gt2wqdbzorf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gzhubu.top/Article/details/gt2ayioxmbh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aizwys.cn/Article/details/gt2cvrlubij.html

JS:   await Promise.all(tasks)
来源：http://dali.xziqi.cn/Article/details/gt2kypqrnmn.html

TS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gt2bqikbfkv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nwbrower.top/Article/details/gt2agjpfqqq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shangyingyoupin.top/Article/details/gt2stlcqxfe.html

Ruby: threads.map(&:join)
来源：http://dali.tanke756.top/Article/details/gt2qejxyufn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.9152youxi.cn/Article/details/gt2kobjbgcj.html

[O06] 使用进程池
来源：http://dali.wangshuangyany.cn/Article/details/gt2orsfioom.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gogol.net.cn/Article/details/gt2gthuupih.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cheryme.top/Article/details/gt2bnzussgj.html

JS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gt2lfaqvkcx.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtxyxnv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gotoacloud.top/Article/details/gt2kkpeyzpw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.redwolf501.top/Article/details/gt2xxmnubkq.html

Ruby: // fork 块
来源：http://dali.pengpengdd.cyou/Article/details/gt2lohsuxiu.html

C#:   Parallel.For
来源：http://dali.ivvv.top/Article/details/gt2gcigisjz.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2lqacwiqe.html

P. 常用工具函数
来源：http://dali.chenzaomai.com/Article/details/gt2gjqafgsg.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2igfungbd.html

[P01] 生成 UUID
来源：http://dali.ybcxt.top/Article/details/gt2wcojeswt.html

Py:   str(uuid.uuid4())
来源：http://dali.zdqjudy.top/Article/details/gt2oyqstkcv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shuidangran.top/Article/details/gt2jdgnnerg.html

JS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gt2hfnwyklu.html

TS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gt2zuinqcvj.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2mrdoljhh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.bjfxy.top/Article/details/gt2aqburgfu.html

Ruby: SecureRandom.uuid
来源：http://dali.ivvv.top/Article/details/gt2xfzzbjze.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tian-w.cn/Article/details/gt2ktenpphs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.smart0.xyz/Article/details/gt2stcacyqs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shuidangran.top/Article/details/gt2lqqxvdgd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.c1oappe.top/Article/details/gt2iirptsfe.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sweek.top/Article/details/gt2pigokgdi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.9152youxi.cn/Article/details/gt2anyghivk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gt2eejfboxy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj202588.top/Article/details/gt2kabzrfcp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.aizwys.cn/Article/details/gt2ybqbxusc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yangfankeji.com/Article/details/gt2tddmyvxw.html

[P03] 生成短随机字符串
来源：http://dali.yj20258.top/Article/details/gt2agrugalt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.birdmap.top/Article/details/gt2khvptpew.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.redwolf501.top/Article/details/gt2xussdpkx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tian-w.cn/Article/details/gt2kgubfzry.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gt2jtqhfbzn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jianghu66.top/Article/details/gt2hfnnildd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.9152youxi.cn/Article/details/gt2cjpaodxo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jianghu66.top/Article/details/gt2ysprixgt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xziqi.cn/Article/details/gt2uggcthqy.html

[P04] 求长度
来源：http://dali.jianghu66.top/Article/details/gt2gyrbzlzy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.bjfxy.top/Article/details/gt2vdzajacl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gt2shmackhe.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gt2fhfqdtpq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhengqikj.top/Article/details/gt2bnslbrdo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangdashe.top/Article/details/gt2mvptrjup.html

Go:   len(arr);  len(m)
来源：http://dali.vqdsnc.cn/Article/details/gt2rsmplves.html

Ruby: x.length;  x.size
来源：http://dali.nwbrower.top/Article/details/gt2sppnumda.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.dianchejie.cn/Article/details/gt2wrpyhvjm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj202588.top/Article/details/gt2ebifozci.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yuxming.cn/Article/details/gt2vygwtmqb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhixingplan.top/Article/details/gt2yhekqjyy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cucudq.cn/Article/details/gt2sxarawvi.html


<!-- 参考信息 -->