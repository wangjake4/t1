代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gtnukfchtb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sufxvd.cn/Article/details/gtbyptlzwj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenjidiqi.icu/Article/details/gtwmecgnhq.html

JS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gtbhmlecyx.html

TS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gthmmplflq.html

Java: resp.statusCode()
来源：http://dali.sufxvd.cn/Article/details/gtocbqpwqk.html

Go:   resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gtpsvowrdd.html

Ruby: resp.code.to_i
来源：http://dali.feifeiyinyue.top/Article/details/gtzsfjbjkn.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gtpgmkuzhz.html

[L08] 并发请求多个地址
来源：http://dali.yj20258.top/Article/details/gtwrdluelz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuanzhike.top/Article/details/gtykxnmnad.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenlongwang.top/Article/details/gtgefgwiir.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gtgzuucbeu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gtihzvvbwo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cqqwz.cn/Article/details/gtagqyauyl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.c1oappe.top/Article/details/gthvcpfnbq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fengsongda.top/Article/details/gtjvovwjsg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtfowibdjr.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtlaypipke.html

M. 命令行 / 进程 / 环境
来源：http://dali.ehwqpu.com/Article/details/gtiywkzvzi.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtwzubtzop.html

[M01] 读取命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gtacqevxrg.html

Py:   sys.argv[1:]
来源：http://dali.ehwqpu.com/Article/details/gtxqesucql.html

PHP:  $argv;  $argc;
来源：http://dali.yongpay.top/Article/details/gtsbgjugvi.html

JS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gtkoifzoas.html

TS:   process.argv.slice(2)
来源：http://dali.redwolf501.top/Article/details/gtvgzwebjo.html

Java: args 数组（main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gttiejghtl.html

Go:   os.Args[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtgjalgqxc.html

Ruby: ARGV
来源：http://dali.jinqigufen.top/Article/details/gtgofsttfl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gthvbusuzw.html

[M02] 读取环境变量
来源：http://dali.zdqjudy.top/Article/details/gtmuntmuom.html

Py:   os.environ.get("HOME")
来源：http://dali.shuidangran.top/Article/details/gtdziubsaa.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gogol.net.cn/Article/details/gtanycadcr.html

JS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gtvrignheg.html

TS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkznwdxu.html

Java: System.getenv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtcsgmxcle.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtvsiedwln.html

Ruby: ENV["HOME"]
来源：http://dali.yangfankeji.com/Article/details/gtwcxmwwqy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtnuiclxbs.html

[M03] 执行外部命令
来源：http://dali.chenlongwang.top/Article/details/gtnlzkvhfi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daxiang520.top/Article/details/gtjqrtrwsd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gzhubu.top/Article/details/gtncfutrah.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gtophamdiz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gtikbguspb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gtfufqhoue.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tanke756.top/Article/details/gttknmjlsd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbyxzwwg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yueranfly.top/Article/details/gtmmnkimbd.html

[M04] 获取当前工作目录
来源：http://dali.yj20258.top/Article/details/gttcnsontd.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gtxixhdohn.html

PHP:  getcwd();
来源：http://dali.yj20258888.top/Article/details/gtssmjjmkx.html

JS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gtdlgedfxe.html

TS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifrykvzc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenlongwang.top/Article/details/gtkwjwgtgt.html

Go:   os.Getwd()
来源：http://dali.havefunace.top/Article/details/gthsftoekc.html

Ruby: Dir.pwd
来源：http://dali.jianghu66.top/Article/details/gtkwvsfups.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zdqjudy.top/Article/details/gtjkicwvas.html

[M05] 设置退出码
来源：http://dali.pengpengdd.cyou/Article/details/gtspsogmqf.html

Py:   sys.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtamkofdah.html

PHP:  exit(1);
来源：http://dali.daxiang520.top/Article/details/gtvdbxrgqo.html

JS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtjwipwpir.html

TS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtyjsmpgna.html

Java: System.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtlevshrbr.html

Go:   os.Exit(1)
来源：http://dali.cashguo.top/Article/details/gtrstlruuo.html

Ruby: exit 1
来源：http://dali.ivvv.top/Article/details/gtwwwyjreo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tianlin.xyz/Article/details/gtycvovgga.html

[M06] 向标准错误输出
来源：http://dali.ydzc1.top/Article/details/gtdlcjrdtb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pengpengdd.cyou/Article/details/gtowrjxoim.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixerfetk.html

JS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtunvmktmc.html

TS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gttwmsavzk.html

Java: System.err.println("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtzsinonjm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnxiangtu.top/Article/details/gtoxbhyioy.html

Ruby: warn "err"
来源：http://dali.yuxming.cn/Article/details/gtaqgookfu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xziqi.cn/Article/details/gtbmmjovrm.html

[M07] 判断是否为主入口
来源：http://dali.jlsjyb.cn/Article/details/gtvhtsxbfb.html

Py:   if __name__ == "__main__":
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlraefmw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.snrcjt.cn/Article/details/gtynuapexs.html

JS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gtdsrtfykm.html

TS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gtrejtgywh.html

Java: public static void main(String[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gtvjjefvny.html

Go:   func main()
来源：http://dali.zdqjudy.top/Article/details/gtzgfftdot.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ppjwa.cn/Article/details/gtfgeyafbc.html

C#:   static void Main(string[] args)
来源：http://dali.hnqzz.top/Article/details/gtqkwgpndg.html

[M08] 获取系统与运行时信息
来源：http://dali.yuanzhike.top/Article/details/gtfdapesve.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fzhhl.top/Article/details/gtyohzcvfq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqlsasza.html

JS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtgeaxipgi.html

TS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gtaukcoguk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hfpthk.cn/Article/details/gtggarzasa.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tanke756.top/Article/details/gtlgrdzaly.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.snrcjt.cn/Article/details/gtthzhbvyf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxuanxn.top/Article/details/gtlxedixly.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtpbqctcdt.html

N. 数据结构与算法
来源：http://dali.yonumen.top/Article/details/gtgcyajphv.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtnxfquuga.html

[N01] 二分查找（有序数组）
来源：http://dali.chenlongwang.top/Article/details/gtsjqknnlq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtrsrrkucl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtypmodaqj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtiughkhps.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gtotgzwirs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtcapnpsyz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtkkejhbsq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aibaodan.cn/Article/details/gtkjecvnnj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtdhaxfdff.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxuanxn.top/Article/details/gtszgcxrlu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yonumen.top/Article/details/gtnfcydflo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cheryme.top/Article/details/gtmlijgnmd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtimptjqev.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gtdwrpvnqi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shangyingyoupin.top/Article/details/gtcgzkjiak.html

Go:   slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gthgwzqdhw.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gtrbhgvpty.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tianlin.xyz/Article/details/gtmhspzjmy.html

[N03] 快速排序（分治示例）
来源：http://dali.zhixingplan.top/Article/details/gtkaorpdos.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhiwuduotai.top/Article/details/gturljdtfo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvjhaujh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gtbfytqhub.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gtlmuryjtv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gotoacloud.top/Article/details/gtsiznlrdx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenjidiqi.icu/Article/details/gttjegbpdb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cucudq.cn/Article/details/gtzwqtqcub.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.9152youxi.cn/Article/details/gtwgprzmoo.html

[N04] 斐波那契数列
来源：http://dali.hongshengwenyu.top/Article/details/gtfhgracii.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gtruvlyqvs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gtpiifngyr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gtnsgshzpv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtdhwoiwut.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gtweafmbkj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.0kj1m.cn/Article/details/gtwlxkhous.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jiagoushi.top/Article/details/gteqvjtfgk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtbkowwoxe.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gtgescykag.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gthkyhofem.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hywenlv.cn/Article/details/gtoelmikch.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aizwys.cn/Article/details/gtvgbqfsjr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gtumfxayvu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hfpthk.cn/Article/details/gtomxqkjrx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzlpwodqf.html

Ruby: a.gcd(b)
来源：http://dali.yj20258888.top/Article/details/gtmypyqzaz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.bjfxy.top/Article/details/gthlifjtnp.html

[N06] 判断回文字符串
来源：http://dali.zhongyouzk.top/Article/details/gtsktmacgj.html

Py:   s == s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gtthixucyn.html

PHP:  $s === strrev($s);
来源：http://dali.jinqigfzy.top/Article/details/gtonlmfjmb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtwruqskae.html

TS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtkxfxrrfm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gtbvcsulji.html

Go:   // 双指针从两端比较
来源：http://dali.smart0.xyz/Article/details/gtdzbhvcjf.html

Ruby: s == s.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtsfjfpief.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gtesuosinm.html

[N07] 两数之和（返回下标）
来源：http://dali.zhiwuduotai.top/Article/details/gtlfippoei.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhoulong.xyz/Article/details/gtrlsgpqhu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tian-w.cn/Article/details/gtsvmthzjy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gaohongyu789.top/Article/details/gtebquryni.html

TS:   // 手写 Map<string, number>
来源：http://dali.pycfn.com/Article/details/gtzfwtgjdv.html

Java: // 手写 HashMap
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohbsesio.html

Go:   // 手写 map[int]int
来源：http://dali.ybcxt.top/Article/details/gtogzopwat.html

Ruby: // 手写 Hash
来源：http://dali.zhoulong.xyz/Article/details/gtxbbsallc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yvedp.cn/Article/details/gtoueikqgq.html

[N08] 生成全排列
来源：http://dali.zhiwuduotai.top/Article/details/gtztqkjnvj.html

Py:   itertools.permutations(arr)
来源：http://dali.meibo888.top/Article/details/gtzknnpsst.html

PHP:  // 手写递归交换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjximrfnr.html

JS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtarvbwitb.html

TS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtgeuteowj.html

Java: // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtkvrymgsx.html

Go:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtkwtyizmy.html

Ruby: arr.permutation.to_a
来源：http://dali.gzhubu.top/Article/details/gtxaytxwzu.html

C#:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtexkpzfsw.html

[N09] 栈与队列
来源：http://dali.sufxvd.cn/Article/details/gttbrcaaoj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yongpay.top/Article/details/gtbksmwtaa.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtcskyrgcs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtgovfeukf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.feifeiyinyue.top/Article/details/gtrgbditgj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.smart0.xyz/Article/details/gtmdjfbgpd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yangfankeji.com/Article/details/gtqyygzksv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtrooguzyp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yanxiufei.cn/Article/details/gtoufzxpjt.html

[N10] 链表节点定义
来源：http://dali.ehwqpu.com/Article/details/gtaidygbib.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yangfankeji.com/Article/details/gtmqusjkof.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdetstvnj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hysaishi.cn/Article/details/gtjenbutlw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cheryme.top/Article/details/gtnfzmrtkd.html

Java: class Node { int v; Node next; }
来源：http://dali.zhongyouzk.top/Article/details/gtccviplsk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.dashuyun.cn/Article/details/gtcgxtzhgx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gzhubu.top/Article/details/gtrdsrlowz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxjcbfhd.html

[N11] 二叉树中序遍历
来源：http://dali.chenlongwang.top/Article/details/gtpscipmim.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhbngczq.html

PHP:  // 手写递归函数
来源：http://dali.zdqjudy.top/Article/details/gtxqlvnswy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gtddnbrwdt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtomcqmivk.html

Java: // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtkdytmdsp.html

Go:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtsyoaxfyg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sxryk.cn/Article/details/gtpuevdiym.html

C#:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtejrzzjug.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258888.top/Article/details/gtbjfnlzvx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gotoacloud.top/Article/details/gtyurrkjng.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.havefunace.top/Article/details/gtyrwuudwb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gtldmdfgwm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gtcjmskzqb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gtphgmuela.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tanke756.top/Article/details/gtpjxuqhiq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cashguo.top/Article/details/gtjvrrtppi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gtxndnkgam.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtjaoagmaa.html

O. 并发与异步
来源：http://dali.chenzaomai.com/Article/details/gtfzhptnxp.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtopclkjem.html

[O01] 启动一个线程
来源：http://dali.jinqigfzy.top/Article/details/gtncucrwqr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhoulong.xyz/Article/details/gtegwarulb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbcxjjbe.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.vqdsnc.cn/Article/details/gtmlsetukw.html

TS:   // 同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gtjmjvgimr.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangshuangyany.cn/Article/details/gtvprbczax.html

Go:   go f()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqtksdyda.html

Ruby: Thread.new { f }
来源：http://dali.gogol.net.cn/Article/details/gtaemhejff.html

C#:   Task.Run(() => F());
来源：http://dali.hongshengwenyu.top/Article/details/gtrubtcnrw.html

[O02] 使用线程池
来源：http://dali.nanxuanxn.top/Article/details/gttmiyanfs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ehwqpu.com/Article/details/gtrmsqsxji.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.havefunace.top/Article/details/gtmxaefhlq.html

JS:   // worker_threads 线程池
来源：http://dali.guowangkeji.top/Article/details/gtdbbufqiy.html

TS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gtlkotpbgq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj202588.top/Article/details/gtvealzfjb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgufenzy.top/Article/details/gtfstyvneg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.wangshuangyany.cn/Article/details/gtavdszqgf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cqqwz.cn/Article/details/gtiwgygnrp.html

[O03] 加锁保护共享数据
来源：http://dali.yangfankeji.com/Article/details/gtralepzsm.html

Py:   with lock: shared += 1
来源：http://dali.svipenyu.cn/Article/details/gtabwiafft.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gotoacloud.top/Article/details/gtsbyfufca.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ivvv.top/Article/details/gthpuogrgl.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gtdaqipgcb.html

Java: synchronized (this) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gtylbrxfaw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenjidiqi.icu/Article/details/gtvmcziayb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yvedp.cn/Article/details/gtmkbczvti.html

C#:   lock (gate) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteuevoaty.html

[O04] 定义异步函数并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsqocxgb.html

Py:   async def f():⏎    await g()
来源：http://dali.xuetiantiany.cn/Article/details/gtcaohuwmb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.c1oappe.top/Article/details/gtrfeikulo.html

JS:   async function f() { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvsuokif.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ivvv.top/Article/details/gtfhmiztaf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gzhubu.top/Article/details/gtibhjndsz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sufxvd.cn/Article/details/gtloqehehm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shanyushiyangtech.top/Article/details/gtokixckqf.html

C#:   async Task F() { await G(); }
来源：http://dali.xuanzx.com/Article/details/gtkepebkqq.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangshuangyany.cn/Article/details/gtfsqyklqt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cheryme.top/Article/details/gtmmyuzhmv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gotoacloud.top/Article/details/gtmwogxnta.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gtqnhsjtvu.html

TS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gthhmbxund.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xinyue.icu/Article/details/gtttmvihbx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jyoumei.cn/Article/details/gtayllypdt.html

Ruby: threads.map(&:join)
来源：http://dali.wangshuangyany.cn/Article/details/gtwgpntzzj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.mhx1999.top/Article/details/gtimofepri.html

[O06] 使用进程池
来源：http://dali.hnxiangtu.top/Article/details/gttbpybhcg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daria6918.cn/Article/details/gtjkkorlsk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gotoacloud.top/Article/details/gtzzoymcgz.html

JS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gtgkgvaueg.html

TS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gtknpmxlel.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daxiang520.top/Article/details/gtvakowsav.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.vqdsnc.cn/Article/details/gtptywlazq.html

Ruby: // fork 块
来源：http://dali.havefunace.top/Article/details/gtxlosvkvi.html

C#:   Parallel.For
来源：http://dali.pengpengdd.cyou/Article/details/gtwpsypmka.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtyigbvlna.html

P. 常用工具函数
来源：http://dali.shzxlz.cn/Article/details/gtlderqcdz.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtdcdfdttq.html

[P01] 生成 UUID
来源：http://dali.xuetiantiany.cn/Article/details/gtbiogazac.html

Py:   str(uuid.uuid4())
来源：http://dali.fengsongda.top/Article/details/gtynzookto.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.andypj.xyz/Article/details/gtwdfmkmil.html

JS:   crypto.randomUUID()
来源：http://dali.nanxuanxn.top/Article/details/gtifnkwziv.html

TS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtolezlijj.html

Java: UUID.randomUUID().toString()
来源：http://dali.kuanghao11.cn/Article/details/gtqkasfwig.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sufxvd.cn/Article/details/gtrfukagfp.html

Ruby: SecureRandom.uuid
来源：http://dali.c1oappe.top/Article/details/gtdfuddupw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtovxhbeqr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinghuilouyu.cn/Article/details/gtffjetusq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvryxizxc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfzpouvr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.316326.xyz/Article/details/gtphsskimq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shzxlz.cn/Article/details/gtcandztnm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.bjfxy.top/Article/details/gtgdjtksgb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ybcxt.top/Article/details/gtersbbocu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.andypj.xyz/Article/details/gtnwintuxr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xziqi.cn/Article/details/gtcvesddyq.html

[P03] 生成短随机字符串
来源：http://dali.jiagoushi.top/Article/details/gtoytqeifk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhoulong.xyz/Article/details/gthwyexyzs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gaohongyu789.top/Article/details/gtsmoogocl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gtlkghgvvi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gtzikudmao.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guowangkeji.top/Article/details/gtpaoyacfk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sxryk.cn/Article/details/gtsrjzsjju.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.bjfxy.top/Article/details/gtihfiwkfl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ybcxt.top/Article/details/gttxyhbtib.html

[P04] 求长度
来源：http://dali.shzxlz.cn/Article/details/gtyrkqckhf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjngmrus.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gttsfcknel.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gtzdjoqwec.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zycfv.cn/Article/details/gtirukmvrv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.0kj1m.cn/Article/details/gtwhcbpurp.html

Go:   len(arr);  len(m)
来源：http://dali.quarkkingdee.top/Article/details/gtmugypnzq.html

Ruby: x.length;  x.size
来源：http://dali.nanxuanxn.top/Article/details/gthnchtbjq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hywenlv.cn/Article/details/gttpqufkmw.html


<!-- 参考信息 -->