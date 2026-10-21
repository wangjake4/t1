代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gtbcrknluj.html

Java: resp.statusCode()
来源：http://dali.dashuyun.cn/Article/details/gtovsgxdlg.html

Go:   resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gtszmdwttj.html

Ruby: resp.code.to_i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwiariqzy.html

C#:   (int)resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gtrpcngkny.html

[L08] 并发请求多个地址
来源：http://dali.aibaodan.cn/Article/details/gtjqnjpten.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.birdmap.top/Article/details/gtnteltmff.html

PHP:  curl_multi_init() 系列
来源：http://dali.daxiang520.top/Article/details/gtzydvhlfj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtrkosnwcr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtpsukotii.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shuidangran.top/Article/details/gtwtjqorrx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.meibo888.top/Article/details/gtjgzacmpi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigufen.top/Article/details/gtcwtkgpod.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ydzc1.top/Article/details/gtlqpyhagy.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtylqrbryq.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangdashe.top/Article/details/gtphdxdnsq.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtmqrvvkcw.html

[M01] 读取命令行参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiywfrlsi.html

Py:   sys.argv[1:]
来源：http://dali.sufxvd.cn/Article/details/gtjbgmnckq.html

PHP:  $argv;  $argc;
来源：http://dali.tianlin.xyz/Article/details/gtzgdjwzkm.html

JS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gtxyazpckz.html

TS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gtoxwdvrhj.html

Java: args 数组（main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gtxxydaelq.html

Go:   os.Args[1:]
来源：http://dali.zdqjudy.top/Article/details/gtmigivlsm.html

Ruby: ARGV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppoflbvv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtlgxlykxy.html

[M02] 读取环境变量
来源：http://dali.quarkkingdee.top/Article/details/gtnmoawrze.html

Py:   os.environ.get("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtpmkcjtwm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gteihaosxw.html

JS:   process.env.HOME
来源：http://dali.ydzc1.top/Article/details/gtramfuuio.html

TS:   process.env.HOME
来源：http://dali.tian-w.cn/Article/details/gtkxuvuhxr.html

Java: System.getenv("HOME")
来源：http://dali.yueranfly.top/Article/details/gttskvcmav.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtwdlpmvsq.html

Ruby: ENV["HOME"]
来源：http://dali.pengpengdd.cyou/Article/details/gtgpftrais.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpwxfkly.html

[M03] 执行外部命令
来源：http://dali.sufxvd.cn/Article/details/gtgclykodg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtbgvwzjsm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tanke756.top/Article/details/gttcwijmfx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gtnqlfzmvu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtqtbcqogm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258888.top/Article/details/gtejkqooqh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.smart0.xyz/Article/details/gtxodmakwo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gogol.net.cn/Article/details/gtvnbsovsd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xuanzx.com/Article/details/gtyovruzkc.html

[M04] 获取当前工作目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgfqfgmz.html

Py:   os.getcwd()
来源：http://dali.nanxinkj.top/Article/details/gtbhepykub.html

PHP:  getcwd();
来源：http://dali.gotoacloud.top/Article/details/gtflahybdt.html

JS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gtnpjiqtyb.html

TS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckpwodnp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sufxvd.cn/Article/details/gtqsxnuezq.html

Go:   os.Getwd()
来源：http://dali.hammf.cn/Article/details/gtbqsmtnam.html

Ruby: Dir.pwd
来源：http://dali.nwbrower.top/Article/details/gtqbynntee.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cheryme.top/Article/details/gtmltmzlbp.html

[M05] 设置退出码
来源：http://dali.yuxming.cn/Article/details/gtxsxzjgbj.html

Py:   sys.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevmwwmbc.html

PHP:  exit(1);
来源：http://dali.xinyue.icu/Article/details/gtflltisen.html

JS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtfjxluhes.html

TS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtfgggtvhf.html

Java: System.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtwgujzeng.html

Go:   os.Exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtzmfvlvgv.html

Ruby: exit 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtenncdsql.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.smart0.xyz/Article/details/gtefifrqgy.html

[M06] 向标准错误输出
来源：http://dali.jiagoushi.top/Article/details/gtkzqldboo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hysaishi.cn/Article/details/gtstecekjq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nwbrower.top/Article/details/gtwjlqfvhe.html

JS:   console.error("err")
来源：http://dali.nanxinkj.top/Article/details/gtqnpcdmbv.html

TS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gtszftzkmo.html

Java: System.err.println("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtjgojurlg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yvedp.cn/Article/details/gtofzkypob.html

Ruby: warn "err"
来源：http://dali.fengsongda.top/Article/details/gtgzfgclvs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.birdmap.top/Article/details/gtptkcoxtw.html

[M07] 判断是否为主入口
来源：http://dali.chenlongwang.top/Article/details/gtadnoyccr.html

Py:   if __name__ == "__main__":
来源：http://dali.yueranfly.top/Article/details/gtqqdrmqjw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjexoeqal.html

JS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcyaumwsl.html

TS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gtuhfoablr.html

Java: public static void main(String[] args)
来源：http://dali.xuanzx.com/Article/details/gthcvifdvf.html

Go:   func main()
来源：http://dali.zhengqikj.top/Article/details/gttikwzwsg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuanzhike.top/Article/details/gtucdhlemt.html

C#:   static void Main(string[] args)
来源：http://dali.nwbrower.top/Article/details/gtdutotidj.html

[M08] 获取系统与运行时信息
来源：http://dali.jinqigufen.top/Article/details/gtrmysgjjw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuanzhike.top/Article/details/gtvldavazk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgufenzy.top/Article/details/gtwqullplc.html

JS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gtfrobqjyv.html

TS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gtnfrzkhkt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jyoumei.cn/Article/details/gteewtgidc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shuidangran.top/Article/details/gtdimqjqgr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nwbrower.top/Article/details/gtuvetwjiq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fzhhl.top/Article/details/gtaaqrvarl.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtnkiumird.html

N. 数据结构与算法
来源：http://dali.zhengqikj.top/Article/details/gtphwstygf.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtpohndxic.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gtusucdxtz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtmmobjoya.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.meibo888.top/Article/details/gtpdfxvfne.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtulbprvru.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gtwzyenhvk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtppxdosgn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtvbctsukv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.c1oappe.top/Article/details/gtvhoomnow.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbuvryuih.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gotoacloud.top/Article/details/gtjnqhylxt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxiqcnzta.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.mhx1999.top/Article/details/gtvvvnqdfn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gthojwwiau.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gtjnmlpeyx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yueranfly.top/Article/details/gtxfxkinzj.html

Go:   slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gtfqcbtufs.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtbsbyrmgi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daxiang520.top/Article/details/gtfyftomtn.html

[N03] 快速排序（分治示例）
来源：http://dali.c1oappe.top/Article/details/gtjxmvnidg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shuidangran.top/Article/details/gtqncpovlu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tianlin.xyz/Article/details/gthqsupdhf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gtclgvexwy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnqzz.top/Article/details/gttldpnoox.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.svipenyu.cn/Article/details/gtjekppzvw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cashguo.top/Article/details/gtpafinupv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zycfv.cn/Article/details/gtiyqxpfut.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tanke756.top/Article/details/gtqyeuidyk.html

[N04] 斐波那契数列
来源：http://dali.snrcjt.cn/Article/details/gttxatqboc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gtpvgebkiv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gtkbafjhgm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtrnziochp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gtlzupmvnt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdeqgdumi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jlsjyb.cn/Article/details/gtbpklbtdb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gtnesbuycv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtrawzymse.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gtgvykexwn.html

Py:   math.gcd(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gtvhylukgd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yueranfly.top/Article/details/gtwrjhnudb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gtmndzhosj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gttotnudho.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yongpay.top/Article/details/gtjvxwhjwz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guannengcc.top/Article/details/gtchbrbupq.html

Ruby: a.gcd(b)
来源：http://dali.daria6918.cn/Article/details/gtvqaqehyp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdpknbgtj.html

[N06] 判断回文字符串
来源：http://dali.zhongyouzk.top/Article/details/gtnuhsujye.html

Py:   s == s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gtlxgwfevh.html

PHP:  $s === strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gtalsaxagk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtqayurxdv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtuotclwgr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.bjfxy.top/Article/details/gtacfdarsu.html

Go:   // 双指针从两端比较
来源：http://dali.ybcxt.top/Article/details/gtoylmthlx.html

Ruby: s == s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtzbpzrgva.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shzxlz.cn/Article/details/gtqnkmziac.html

[N07] 两数之和（返回下标）
来源：http://dali.yongpay.top/Article/details/gtlrlpkzjc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj202588.top/Article/details/gtctayadjt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guannengcc.top/Article/details/gtmhhhljxs.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.snrcjt.cn/Article/details/gtfwltxnoj.html

TS:   // 手写 Map<string, number>
来源：http://dali.xziqi.cn/Article/details/gtcopyitwg.html

Java: // 手写 HashMap
来源：http://dali.cashguo.top/Article/details/gtcrbzokmf.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvblvsaou.html

Ruby: // 手写 Hash
来源：http://dali.zhongyouzk.top/Article/details/gtikgsfdyf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.316326.xyz/Article/details/gtpufspkpj.html

[N08] 生成全排列
来源：http://dali.guowangkeji.top/Article/details/gtkghctnyc.html

Py:   itertools.permutations(arr)
来源：http://dali.hnqzz.top/Article/details/gtijncnivy.html

PHP:  // 手写递归交换
来源：http://dali.c1oappe.top/Article/details/gtziwvribl.html

JS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtohgxdehi.html

TS:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtoonftwbm.html

Java: // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtqhwiqwcu.html

Go:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtdwnispre.html

Ruby: arr.permutation.to_a
来源：http://dali.dianchejie.cn/Article/details/gtdonkthhi.html

C#:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtjhjwvsxl.html

[N09] 栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gttrpuwmba.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtbopmsvxd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gtgkaepbbv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gtcrwpjpgb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxinkj.top/Article/details/gtucghfium.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tianlin.xyz/Article/details/gtntebgclq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cashguo.top/Article/details/gtugtiuvtj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtexdsosna.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.wangdashe.top/Article/details/gtphlnmhit.html

[N10] 链表节点定义
来源：http://dali.havefunace.top/Article/details/gtlnkyoevk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xziqi.cn/Article/details/gtfqhqdyfl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ydzc1.top/Article/details/gtglbzszwu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.9152youxi.cn/Article/details/gtwijiozpu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ehwqpu.com/Article/details/gtsjttlqyc.html

Java: class Node { int v; Node next; }
来源：http://dali.yvedp.cn/Article/details/gtwbuhjuwz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj202588.top/Article/details/gthiklykof.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gogol.net.cn/Article/details/gtroimeork.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cdnleiting.top/Article/details/gtlduhoxom.html

[N11] 二叉树中序遍历
来源：http://dali.dianchejie.cn/Article/details/gteguamqjj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xinyue.icu/Article/details/gtawziqdxu.html

PHP:  // 手写递归函数
来源：http://dali.aizwys.cn/Article/details/gtchlzglsh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gtikkcxfsr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gtzmrxekqq.html

Java: // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gtoyeyiamr.html

Go:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gtgzsgwlai.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.svipenyu.cn/Article/details/gtpdildpfw.html

C#:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gthrqttuly.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sufxvd.cn/Article/details/gtywstoozo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenjidiqi.icu/Article/details/gtlpdvhjzv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yonumen.top/Article/details/gtqaylvtgf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtnnjdcwqb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gttfbfoazk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangdashe.top/Article/details/gtjhlendpb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pycfn.com/Article/details/gtwnoadqnx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.havefunace.top/Article/details/gtktlfkkmq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gtehmdqhlm.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtghcwgqif.html

O. 并发与异步
来源：http://dali.zycfv.cn/Article/details/gtovlhlujq.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtrmgcrbbk.html

[O01] 启动一个线程
来源：http://dali.wangdashe.top/Article/details/gtbgvpnaez.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hfpthk.cn/Article/details/gtmjxpsfmw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nwbrower.top/Article/details/gtqbzxiwrl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangdashe.top/Article/details/gtmfmxpypj.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gtgctzjphj.html

Java: new Thread(() -> f()).start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnigvqopq.html

Go:   go f()
来源：http://dali.haohaochexian.top/Article/details/gtytdllnwp.html

Ruby: Thread.new { f }
来源：http://dali.cucudq.cn/Article/details/gtkyiiaqbp.html

C#:   Task.Run(() => F());
来源：http://dali.tian-w.cn/Article/details/gtktcxsvfs.html

[O02] 使用线程池
来源：http://dali.jqgfzy.top/Article/details/gtlbbuvrau.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvwpdaaz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.redwolf501.top/Article/details/gttwtkpryu.html

JS:   // worker_threads 线程池
来源：http://dali.tanke756.top/Article/details/gttearabzw.html

TS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gtelnsozws.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yuanzhike.top/Article/details/gtnlmxnrwi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.iojbl.cn/Article/details/gtmuoalysu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tian-w.cn/Article/details/gtymowarej.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.birdmap.top/Article/details/gtegbxvtqs.html

[O03] 加锁保护共享数据
来源：http://dali.yueranfly.top/Article/details/gtwmmdqfbl.html

Py:   with lock: shared += 1
来源：http://dali.iojbl.cn/Article/details/gthiftnlkh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sweek.top/Article/details/gtosraxqdi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxuanxn.top/Article/details/gtojpgwibo.html

TS:   // 同 JS
来源：http://dali.tian-w.cn/Article/details/gtjammlmmu.html

Java: synchronized (this) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlvwzxjjl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dashuyun.cn/Article/details/gtkfsipnjx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenlongwang.top/Article/details/gtrbuhbqbg.html

C#:   lock (gate) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gtaxdcragp.html

[O04] 定义异步函数并等待
来源：http://dali.cdnleiting.top/Article/details/gtbxlaaqsf.html

Py:   async def f():⏎    await g()
来源：http://dali.aizwys.cn/Article/details/gtkpcvjlxz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gtcxfomeos.html

JS:   async function f() { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gtorpvhxzy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.guannengcc.top/Article/details/gtrqwadtux.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.havefunace.top/Article/details/gtfcirgstu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shzxlz.cn/Article/details/gtfpgbcppi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guannengcc.top/Article/details/gtztyxiulq.html

C#:   async Task F() { await G(); }
来源：http://dali.0kj1m.cn/Article/details/gtvuycfawn.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhengqikj.top/Article/details/gtealtobiu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jlsjyb.cn/Article/details/gtrhbwpacj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yueranfly.top/Article/details/gtrguwmkoz.html

JS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gtskbekfuk.html

TS:   await Promise.all(tasks)
来源：http://dali.sweek.top/Article/details/gtqqqbufmt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigufen.top/Article/details/gtasllainq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj20258888.top/Article/details/gtjtxqyrpt.html

Ruby: threads.map(&:join)
来源：http://dali.cucudq.cn/Article/details/gtsunpppib.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jiagoushi.top/Article/details/gtxnpouhxj.html

[O06] 使用进程池
来源：http://dali.gotoacloud.top/Article/details/gthzdjfkhl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.316326.xyz/Article/details/gtswhsajuk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.havefunace.top/Article/details/gtnyffnmvk.html

JS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gtbamcogna.html

TS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gtutcxrfkk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jqgufenzy.top/Article/details/gtvvwgoudt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gtohuhxbiu.html

Ruby: // fork 块
来源：http://dali.yanxiufei.cn/Article/details/gtgcskxbve.html

C#:   Parallel.For
来源：http://dali.zhixingplan.top/Article/details/gtrqvuxurq.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtwplgcwfo.html

P. 常用工具函数
来源：http://dali.hnqzz.top/Article/details/gthaoagabh.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtzbvkchda.html

[P01] 生成 UUID
来源：http://dali.yonumen.top/Article/details/gtiwhsmzdo.html

Py:   str(uuid.uuid4())
来源：http://dali.sufxvd.cn/Article/details/gtpiawxxzp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jlsjyb.cn/Article/details/gtzspmdbrv.html

JS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gteeyswmfm.html

TS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gtgdyxsete.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigufen.top/Article/details/gtrmwmfmne.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgfzy.top/Article/details/gtyxfuygkc.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258888.top/Article/details/gtyucanvkf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tianlin.xyz/Article/details/gtkjqnhnfd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jyoumei.cn/Article/details/gtaiortdss.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhixingplan.top/Article/details/gtxihgaheq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhongyouzk.top/Article/details/gtlxmsjute.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.9152youxi.cn/Article/details/gthwfbzxtq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cheryme.top/Article/details/gtfczrftdm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.birdmap.top/Article/details/gtpfguqxcf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangdashe.top/Article/details/gtbinjrkby.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtyoczfw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sweek.top/Article/details/gtoyumcdkn.html

[P03] 生成短随机字符串
来源：http://dali.gotoacloud.top/Article/details/gtjweohamn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangdashe.top/Article/details/gtjefqauou.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yueranfly.top/Article/details/gtefbfdarn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gttdojccsh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xylfe.cn/Article/details/gtnyusdarm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gtvdqtrdlw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yueranfly.top/Article/details/gtsmkmzhwv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.quarkkingdee.top/Article/details/gtnpurgekb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gtbktndfli.html

[P04] 求长度
来源：http://dali.nanxuanxn.top/Article/details/gtlbgsskhi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zdqjudy.top/Article/details/gtysasiaph.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtvlctnbdu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggazfaga.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjlyszis.html

Java: list.size();  map.size();  s.length()
来源：http://dali.fzhhl.top/Article/details/gtjjkcjrci.html

Go:   len(arr);  len(m)
来源：http://dali.guannengcc.top/Article/details/gtprwxjrgk.html

Ruby: x.length;  x.size
来源：http://dali.guannengcc.top/Article/details/gtsvmfkxpy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xinyue.icu/Article/details/gtpcmvfmrb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenzaomai.com/Article/details/gtfjymuiwg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ppjwa.cn/Article/details/gtjoogkbqo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gzhubu.top/Article/details/gtzvtgljog.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258888.top/Article/details/gtujwykxyd.html


<!-- 参考信息 -->