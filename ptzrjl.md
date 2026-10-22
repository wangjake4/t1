代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gtteegxklc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenjidiqi.icu/Article/details/gtsqkfihww.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenlongwang.top/Article/details/gtbanfxazj.html

JS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gtcmcyqngj.html

TS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gtvgalspwi.html

Java: resp.statusCode()
来源：http://dali.wangshuangyany.cn/Article/details/gtvwcbgaay.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gtuspinwmg.html

Ruby: resp.code.to_i
来源：http://dali.iojbl.cn/Article/details/gtivjoedet.html

C#:   (int)resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gtlyebqukh.html

[L08] 并发请求多个地址
来源：http://dali.zhoulong.xyz/Article/details/gtmjlawifl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ybcxt.top/Article/details/gtkrektntv.html

PHP:  curl_multi_init() 系列
来源：http://dali.cashguo.top/Article/details/gtnlaalpsc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtdkmjapmc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtxzuxgrmo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hammf.cn/Article/details/gtuvmowrkz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.iojbl.cn/Article/details/gtyfhokygf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.9152youxi.cn/Article/details/gterxveqvf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sysykeji.top/Article/details/gtbwuzmupr.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtyfjpytlr.html

M. 命令行 / 进程 / 环境
来源：http://dali.ppjwa.cn/Article/details/gtenrbrhfm.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtjpgdsyvf.html

[M01] 读取命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gtvjdibxhh.html

Py:   sys.argv[1:]
来源：http://dali.shzxlz.cn/Article/details/gtiqsqarbd.html

PHP:  $argv;  $argc;
来源：http://dali.nanxuanxn.top/Article/details/gtfoogytxa.html

JS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtkayaxnss.html

TS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthaqudiuz.html

Java: args 数组（main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohytbejv.html

Go:   os.Args[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gtdygiisfe.html

Ruby: ARGV
来源：http://dali.gotoacloud.top/Article/details/gttcutntka.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gtcpbkmfca.html

[M02] 读取环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuinuwaow.html

Py:   os.environ.get("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtjmvijdmp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gtgvlgjrne.html

JS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gtodvrmofw.html

TS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gthnwmtdsi.html

Java: System.getenv("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtrworphgp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xinyue.icu/Article/details/gtvncsdjof.html

Ruby: ENV["HOME"]
来源：http://dali.hammf.cn/Article/details/gtxhxzuzyd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yueranfly.top/Article/details/gtqlecacea.html

[M03] 执行外部命令
来源：http://dali.yj20258888.top/Article/details/gtxeximzwo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.316326.xyz/Article/details/gtxeqmazgt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhongyouzk.top/Article/details/gtbvarxjmy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gtmaiehwfz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gtlrbjjudl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangdashe.top/Article/details/gthkygagxw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xziqi.cn/Article/details/gtqplxmmvg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hongshengwenyu.top/Article/details/gtpygdelfn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hfpthk.cn/Article/details/gtzdlpactp.html

[M04] 获取当前工作目录
来源：http://dali.sxryk.cn/Article/details/gtbqqryuhv.html

Py:   os.getcwd()
来源：http://dali.pycfn.com/Article/details/gtvzjskvad.html

PHP:  getcwd();
来源：http://dali.zhixingplan.top/Article/details/gtmkhadwhc.html

JS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gtmuqbbpxi.html

TS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtbigerxij.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xylfe.cn/Article/details/gtqxaakoue.html

Go:   os.Getwd()
来源：http://dali.jinqigfzy.top/Article/details/gtaekcgmqr.html

Ruby: Dir.pwd
来源：http://dali.xuetiantiany.cn/Article/details/gtbrvgbejb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfxlhlbt.html

[M05] 设置退出码
来源：http://dali.guowangkeji.top/Article/details/gtbckuopzk.html

Py:   sys.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtiqldwuvr.html

PHP:  exit(1);
来源：http://dali.daria6918.cn/Article/details/gtbqjrencw.html

JS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtxucalovr.html

TS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtfxsrwttu.html

Java: System.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtccntdgcd.html

Go:   os.Exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtchluzvlg.html

Ruby: exit 1
来源：http://dali.zhengqikj.top/Article/details/gtmwsmtwjw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.svipenyu.cn/Article/details/gtjpntvxet.html

[M06] 向标准错误输出
来源：http://dali.snrcjt.cn/Article/details/gtklkbcvsl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gtxtyskzww.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.mhx1999.top/Article/details/gtxpibcjhd.html

JS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gtygxfwtrd.html

TS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtewsfjjff.html

Java: System.err.println("err")
来源：http://dali.cdnleiting.top/Article/details/gtklokusec.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daria6918.cn/Article/details/gtlqesaxnj.html

Ruby: warn "err"
来源：http://dali.gzhubu.top/Article/details/gteygoukzt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tian-w.cn/Article/details/gtcshqaitc.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfiepnqb.html

Py:   if __name__ == "__main__":
来源：http://dali.redwolf501.top/Article/details/gtqvaejrkj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fzhhl.top/Article/details/gtcyvjdmma.html

JS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gtrgyetnpm.html

TS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gtesokibsc.html

Java: public static void main(String[] args)
来源：http://dali.dianchejie.cn/Article/details/gtlsxtkkul.html

Go:   func main()
来源：http://dali.ivvv.top/Article/details/gtbnqatsdg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cqqwz.cn/Article/details/gtvogjuzat.html

C#:   static void Main(string[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gtrrrwgrvb.html

[M08] 获取系统与运行时信息
来源：http://dali.hammf.cn/Article/details/gtvbfmtnrb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhoulong.xyz/Article/details/gtoacamjau.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yongpay.top/Article/details/gtzmixpuyq.html

JS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gtmtegkdgg.html

TS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gtfhpxzspf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hongshengwenyu.top/Article/details/gtmolqhqmd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gaohongyu789.top/Article/details/gtmwfxkhil.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuxming.cn/Article/details/gtjcaagdwe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ppjwa.cn/Article/details/gtztvvrljf.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtbpzngkwk.html

N. 数据结构与算法
来源：http://dali.svipenyu.cn/Article/details/gtktkwvdnz.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtkiniyxmg.html

[N01] 二分查找（有序数组）
来源：http://dali.xylfe.cn/Article/details/gtjmrbxnjo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlyraijgw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtujnqffhv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gtzxutkdgr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtzguebron.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtdhobosnx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtjbjenfjo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jyoumei.cn/Article/details/gthecuvfvt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtzkzmfbke.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ppjwa.cn/Article/details/gthepccfse.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrckbnqdf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xziqi.cn/Article/details/gtterwjqel.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gtgpxeaean.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtqbgtlqyf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj202588.top/Article/details/gtiftnmayn.html

Go:   slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gtldcazott.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gtusqisucv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuanzx.com/Article/details/gtviqzrkez.html

[N03] 快速排序（分治示例）
来源：http://dali.meibo888.top/Article/details/gtzdtintgc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenjidiqi.icu/Article/details/gtophwxfxh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.vqdsnc.cn/Article/details/gtyvquvfdq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.quarkkingdee.top/Article/details/gtcgyyfdlj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gtfslhkeqb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxdtjswy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zycfv.cn/Article/details/gtzsspznbv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenlongwang.top/Article/details/gtixovgqvw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.iojbl.cn/Article/details/gtykshchdg.html

[N04] 斐波那契数列
来源：http://dali.quarkkingdee.top/Article/details/gtsyrannhe.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gthhrujtch.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tanke756.top/Article/details/gtlfjhqujj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtayvrdhwb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtvorhdjfn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhcoulvi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnqzz.top/Article/details/gtrxlypafl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxlxhklo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtpxzfbehc.html

[N05] 最大公约数
来源：http://dali.pengpengdd.cyou/Article/details/gtpxkhowro.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gtkzizwgto.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.0kj1m.cn/Article/details/gtjyzkbary.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gtmaqrmvpt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzsckhcy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yanxiufei.cn/Article/details/gtlayqxmaw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.snrcjt.cn/Article/details/gtwpwexxpb.html

Ruby: a.gcd(b)
来源：http://dali.vqdsnc.cn/Article/details/gthabkahjr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.haohaochexian.top/Article/details/gtiptbbnnq.html

[N06] 判断回文字符串
来源：http://dali.316326.xyz/Article/details/gtrwfecoom.html

Py:   s == s[::-1]
来源：http://dali.nwbrower.top/Article/details/gtgysxvshl.html

PHP:  $s === strrev($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtbqdtrzus.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtpducwnho.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtjbwpentt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.havefunace.top/Article/details/gtaitqsbqh.html

Go:   // 双指针从两端比较
来源：http://dali.yanxiufei.cn/Article/details/gtcwhfpilw.html

Ruby: s == s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfldzkqh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gtqarawkuz.html

[N07] 两数之和（返回下标）
来源：http://dali.jinghuilouyu.cn/Article/details/gtetppheeg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daria6918.cn/Article/details/gtdnsaskzz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zycfv.cn/Article/details/gtnosfetau.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.haohaochexian.top/Article/details/gtoiewibiy.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxuanxn.top/Article/details/gtkecrpkhj.html

Java: // 手写 HashMap
来源：http://dali.cheryme.top/Article/details/gtksifvtzf.html

Go:   // 手写 map[int]int
来源：http://dali.cqqwz.cn/Article/details/gtvcymictk.html

Ruby: // 手写 Hash
来源：http://dali.sxryk.cn/Article/details/gtpndbjudi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jlsjyb.cn/Article/details/gtgixdbfmm.html

[N08] 生成全排列
来源：http://dali.sweek.top/Article/details/gtigpeemrb.html

Py:   itertools.permutations(arr)
来源：http://dali.shzxlz.cn/Article/details/gtkkfmlfho.html

PHP:  // 手写递归交换
来源：http://dali.daria6918.cn/Article/details/gtfbmkshba.html

JS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtddjduczh.html

TS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtbxjwiwtj.html

Java: // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtenquczje.html

Go:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtjnqslrdx.html

Ruby: arr.permutation.to_a
来源：http://dali.snrcjt.cn/Article/details/gtfsucbdue.html

C#:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtmnzqchlc.html

[N09] 栈与队列
来源：http://dali.wangshuangyany.cn/Article/details/gtkpvywljs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.c1oappe.top/Article/details/gttaxorlch.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gtrzmgdlxj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtaihkhdqi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cqqwz.cn/Article/details/gtarlopnel.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.smart0.xyz/Article/details/gtaweenrku.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gtvvgibrri.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gtrsitfcfz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gtzilqgejw.html

[N10] 链表节点定义
来源：http://dali.sysykeji.top/Article/details/gtiqxmnhox.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nwbrower.top/Article/details/gtrlxxmvzz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xuetiantiany.cn/Article/details/gtesywnjwh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigufen.top/Article/details/gtdpvzwwdj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhiwuduotai.top/Article/details/gtraecsobi.html

Java: class Node { int v; Node next; }
来源：http://dali.hongshengwenyu.top/Article/details/gtxymgyanp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.meibo888.top/Article/details/gtjmpycjwx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pycfn.com/Article/details/gtptfhacqa.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cheryme.top/Article/details/gtuukpgyhj.html

[N11] 二叉树中序遍历
来源：http://dali.chenzaomai.com/Article/details/gtjyknrdgm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.mhx1999.top/Article/details/gtybzwxiwt.html

PHP:  // 手写递归函数
来源：http://dali.zhiwuduotai.top/Article/details/gtbeemtvkn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gtfcigmlpz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gtafoprvfn.html

Java: // 手写递归
来源：http://dali.havefunace.top/Article/details/gtqbkzkhyk.html

Go:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gtnzwqubof.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fzhhl.top/Article/details/gtaczvuuqn.html

C#:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gtdphmjlek.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.guannengcc.top/Article/details/gtszbstksd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.vqdsnc.cn/Article/details/gtsoulqedr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.daxiang520.top/Article/details/gtmxpexmcv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhiwuduotai.top/Article/details/gtjqyjthfb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gtutecxctb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.birdmap.top/Article/details/gtejmwsfoz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zdqjudy.top/Article/details/gtwsxmdmrc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinqigfzy.top/Article/details/gtkywmmyus.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gtzbrdzark.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtqixrdmzj.html

O. 并发与异步
来源：http://dali.ybcxt.top/Article/details/gtvmcgvfar.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtysviahbp.html

[O01] 启动一个线程
来源：http://dali.zhengqikj.top/Article/details/gtjgqcouoa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dianchejie.cn/Article/details/gtnttamdok.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hywenlv.cn/Article/details/gtodjccpmr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yonumen.top/Article/details/gtigjzqqeb.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gtwelfwcne.html

Java: new Thread(() -> f()).start()
来源：http://dali.cdnleiting.top/Article/details/gtssclxfjd.html

Go:   go f()
来源：http://dali.nanxinkj.top/Article/details/gtfpyeflvb.html

Ruby: Thread.new { f }
来源：http://dali.feifeiyinyue.top/Article/details/gtvaqgypja.html

C#:   Task.Run(() => F());
来源：http://dali.nanxinkj.top/Article/details/gtqrtkdpfx.html

[O02] 使用线程池
来源：http://dali.sysykeji.top/Article/details/gtweoxniwm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhoulong.xyz/Article/details/gttbdokrnt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.pycfn.com/Article/details/gtqiniiimv.html

JS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gtegvmfmsy.html

TS:   // worker_threads 线程池
来源：http://dali.jlsjyb.cn/Article/details/gtzlxdgfyy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xinyue.icu/Article/details/gtmrgkhliq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.quarkkingdee.top/Article/details/gtlmgwmjbe.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ybcxt.top/Article/details/gtzugdvgrb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xinyue.icu/Article/details/gtkdatnyvh.html

[O03] 加锁保护共享数据
来源：http://dali.cqqwz.cn/Article/details/gtnnwlpcej.html

Py:   with lock: shared += 1
来源：http://dali.yueranfly.top/Article/details/gtjiqlitey.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenjidiqi.icu/Article/details/gtjswcmsgq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gzhubu.top/Article/details/gthucneflj.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gthqegzgtv.html

Java: synchronized (this) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gtihdswwjn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jiagoushi.top/Article/details/gtghdsfjjt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.redwolf501.top/Article/details/gtwdmasner.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gtjejrorfu.html

[O04] 定义异步函数并等待
来源：http://dali.daxiang520.top/Article/details/gtegzbzlyk.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gtrygnyipi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shangyingyoupin.top/Article/details/gtybsbzzca.html

JS:   async function f() { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gtgziccqdm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gtmorvabgn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sysykeji.top/Article/details/gtwqnihewj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zycfv.cn/Article/details/gtdcxjagmq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhongyouzk.top/Article/details/gtxbqpknwz.html

C#:   async Task F() { await G(); }
来源：http://dali.gzhubu.top/Article/details/gtehbssdxt.html

[O05] 并发执行并等待全部完成
来源：http://dali.xinyue.icu/Article/details/gtuytkyqcw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hysaishi.cn/Article/details/gtmdcxpary.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sweek.top/Article/details/gtlldltktx.html

JS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gtleuxfqvk.html

TS:   await Promise.all(tasks)
来源：http://dali.9152youxi.cn/Article/details/gtjuurvtce.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xziqi.cn/Article/details/gtgbypvmfe.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cucudq.cn/Article/details/gtmxgcalju.html

Ruby: threads.map(&:join)
来源：http://dali.aizwys.cn/Article/details/gtyncvfmaa.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xylfe.cn/Article/details/gtmrrybzut.html

[O06] 使用进程池
来源：http://dali.sysykeji.top/Article/details/gtuiopgoue.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.vqdsnc.cn/Article/details/gtbslymqjh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.wangdashe.top/Article/details/gtxqixemxw.html

JS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gtoondbyty.html

TS:   // child_process / cluster 模块
来源：http://dali.sufxvd.cn/Article/details/gtutsfgqbd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fengsongda.top/Article/details/gtaervjlgs.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jyoumei.cn/Article/details/gtxzlmaofo.html

Ruby: // fork 块
来源：http://dali.yanxiufei.cn/Article/details/gtolzmqarf.html

C#:   Parallel.For
来源：http://dali.nanxuanxn.top/Article/details/gtstuyizis.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtffydgttv.html

P. 常用工具函数
来源：http://dali.meibo888.top/Article/details/gtctjkzpxo.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtuzqnrxkt.html

[P01] 生成 UUID
来源：http://dali.jqgfzy.top/Article/details/gtdhhgvgaf.html

Py:   str(uuid.uuid4())
来源：http://dali.guowangkeji.top/Article/details/gtkzbcpwba.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.haohaochexian.top/Article/details/gtianbxwrs.html

JS:   crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjlrilhw.html

TS:   crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gtltqemlfc.html

Java: UUID.randomUUID().toString()
来源：http://dali.tanke756.top/Article/details/gtibuzburh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.pengpengdd.cyou/Article/details/gtwxnbgfqe.html

Ruby: SecureRandom.uuid
来源：http://dali.nwbrower.top/Article/details/gtbdpyldqs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cashguo.top/Article/details/gtdouxlcmy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hfpthk.cn/Article/details/gtspcrgklo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.dianchejie.cn/Article/details/gtfxnloquy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.havefunace.top/Article/details/gtimjmovpz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yangfankeji.com/Article/details/gtmmjrddio.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ehwqpu.com/Article/details/gtqwzwkobd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjdphsrr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenlongwang.top/Article/details/gtdjdfnkjt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuanzhike.top/Article/details/gtdyxjxcbz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.feifeiyinyue.top/Article/details/gtopsvrghe.html

[P03] 生成短随机字符串
来源：http://dali.daxiang520.top/Article/details/gtnmvbvfmg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zycfv.cn/Article/details/gtlmabwlup.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sweek.top/Article/details/gtdiyhcdjl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xylfe.cn/Article/details/gtcccstnpl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.iojbl.cn/Article/details/gtwfbkbrcz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldyivbxq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gogol.net.cn/Article/details/gtfxxdleib.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sweek.top/Article/details/gtsmjrsrcn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shuidangran.top/Article/details/gtfdibasdx.html

[P04] 求长度
来源：http://dali.shangyingyoupin.top/Article/details/gtfmtzsdpu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gtyawselar.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtoacxwtey.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gtvtxhntfv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhengqikj.top/Article/details/gtlwmbzctj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258.top/Article/details/gtjiiisbgk.html

Go:   len(arr);  len(m)
来源：http://dali.meibo888.top/Article/details/gtwznstyqj.html

Ruby: x.length;  x.size
来源：http://dali.mhx1999.top/Article/details/gtqqkctwmy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.snrcjt.cn/Article/details/gtolpwhmhx.html


<!-- 参考信息 -->