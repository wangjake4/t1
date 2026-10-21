代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gtswwcdmee.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cashguo.top/Article/details/gthkmlsaxn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jianghu66.top/Article/details/gtnagbvohk.html

JS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gtapakiytf.html

TS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gtyadbwyqd.html

Java: resp.statusCode()
来源：http://dali.jyoumei.cn/Article/details/gtiooxvggp.html

Go:   resp.StatusCode
来源：http://dali.pycfn.com/Article/details/gtoidldpas.html

Ruby: resp.code.to_i
来源：http://dali.mhx1999.top/Article/details/gtlvhucdtm.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gtizyfctyf.html

[L08] 并发请求多个地址
来源：http://dali.svipenyu.cn/Article/details/gtnyyerzss.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gtyofjbldv.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxinkj.top/Article/details/gtogqartjr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gtfkjesmjz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gtkxhlxlyr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ivvv.top/Article/details/gtiwakaere.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxinkj.top/Article/details/gtjsiiwmdr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yongpay.top/Article/details/gtkehgtnzm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbyswxmao.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtrrhqlawn.html

M. 命令行 / 进程 / 环境
来源：http://dali.smart0.xyz/Article/details/gtszcjzged.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtskvjbqnp.html

[M01] 读取命令行参数
来源：http://dali.yonumen.top/Article/details/gtuupfdpln.html

Py:   sys.argv[1:]
来源：http://dali.zhixingplan.top/Article/details/gtgvdgkvxj.html

PHP:  $argv;  $argc;
来源：http://dali.zycfv.cn/Article/details/gtsrxjvkla.html

JS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtvpcbhzlz.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gtoivwjdih.html

Java: args 数组（main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gtzopghhvt.html

Go:   os.Args[1:]
来源：http://dali.wangdashe.top/Article/details/gtfnawlzlj.html

Ruby: ARGV
来源：http://dali.birdmap.top/Article/details/gtralvifjr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gtkognaiia.html

[M02] 读取环境变量
来源：http://dali.smart0.xyz/Article/details/gttxmisplc.html

Py:   os.environ.get("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtwaofuekk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gtgmwveher.html

JS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtvgyutlhc.html

TS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gtnaoblfvg.html

Java: System.getenv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtevvbmjea.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtmbdmneju.html

Ruby: ENV["HOME"]
来源：http://dali.ehwqpu.com/Article/details/gtljobzpvf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtlvtibapp.html

[M03] 执行外部命令
来源：http://dali.yonumen.top/Article/details/gtkctkpmxv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.kuanghao11.cn/Article/details/gtxkrzghuh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzupnefy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gtjioujytg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gtffntgmxg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhongyouzk.top/Article/details/gtadtmttwp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258888.top/Article/details/gtodpjudtt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yonumen.top/Article/details/gtxpipqbki.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pengpengdd.cyou/Article/details/gtnvhkvoij.html

[M04] 获取当前工作目录
来源：http://dali.iojbl.cn/Article/details/gtoblkgkwf.html

Py:   os.getcwd()
来源：http://dali.gaohongyu789.top/Article/details/gtsslbvmpy.html

PHP:  getcwd();
来源：http://dali.havefunace.top/Article/details/gtixudxtrj.html

JS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gtmvatndzr.html

TS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gtofvawapu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenlongwang.top/Article/details/gtirnxoztd.html

Go:   os.Getwd()
来源：http://dali.nanxinkj.top/Article/details/gtojpsiupj.html

Ruby: Dir.pwd
来源：http://dali.cashguo.top/Article/details/gtcjpuargp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuanzx.com/Article/details/gtiwnxxsfr.html

[M05] 设置退出码
来源：http://dali.316326.xyz/Article/details/gtrmmegdil.html

Py:   sys.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtgtagwdug.html

PHP:  exit(1);
来源：http://dali.xuanzx.com/Article/details/gtuykowmgm.html

JS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtrqzcmueu.html

TS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtdkuprvdv.html

Java: System.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gthljhgnea.html

Go:   os.Exit(1)
来源：http://dali.shuidangran.top/Article/details/gtdsgpamzi.html

Ruby: exit 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpabgfeef.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shuidangran.top/Article/details/gtvrfijirg.html

[M06] 向标准错误输出
来源：http://dali.yueranfly.top/Article/details/gtpsunnvsd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aizwys.cn/Article/details/gtcsojysxn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.9152youxi.cn/Article/details/gteozrqldz.html

JS:   console.error("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtiwhcdxse.html

TS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjgfmrkog.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gtozfzdlyj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhiwuduotai.top/Article/details/gtowdlzkcn.html

Ruby: warn "err"
来源：http://dali.nanxuanxn.top/Article/details/gthmkcrckp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.316326.xyz/Article/details/gtyhrxmisy.html

[M07] 判断是否为主入口
来源：http://dali.ehwqpu.com/Article/details/gtogxdvoig.html

Py:   if __name__ == "__main__":
来源：http://dali.c1oappe.top/Article/details/gteimcolpl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258.top/Article/details/gtcphxsabl.html

JS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtfyioqcjy.html

TS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gtstxhkeyq.html

Java: public static void main(String[] args)
来源：http://dali.316326.xyz/Article/details/gtdcimpnwz.html

Go:   func main()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxcojjtby.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.bjfxy.top/Article/details/gtdgemdypv.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigufen.top/Article/details/gtdhtjjuze.html

[M08] 获取系统与运行时信息
来源：http://dali.cheryme.top/Article/details/gtbbjfjnlt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigufen.top/Article/details/gtbqgsdteh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.redwolf501.top/Article/details/gtulpsngdx.html

JS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gtbgztjhwu.html

TS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtxxrveccp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.kuanghao11.cn/Article/details/gthmtbhvni.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ivvv.top/Article/details/gtrcdgktvv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj202588.top/Article/details/gtowzxcshh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guowangkeji.top/Article/details/gtjtavttag.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtfazxqujm.html

N. 数据结构与算法
来源：http://dali.sxryk.cn/Article/details/gtravddlwh.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtzkgevylk.html

[N01] 二分查找（有序数组）
来源：http://dali.zhixingplan.top/Article/details/gtrabotrlx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gthugvcxvg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrhyaepd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.birdmap.top/Article/details/gtxuhmymvf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gtocpkylwl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtppqqtdxm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtvdcxwfrj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gaohongyu789.top/Article/details/gtvijstkcz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gttosmhgqe.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daria6918.cn/Article/details/gtpvszcyeo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtjvffgddu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ybcxt.top/Article/details/gtwtboupte.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtfbuuendv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gthfikbfuh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwtllstr.html

Go:   slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtcokpsnkz.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gtttyuclof.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjmgquaq.html

[N03] 快速排序（分治示例）
来源：http://dali.pengpengdd.cyou/Article/details/gtttllurdq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guannengcc.top/Article/details/gtnvkzryyh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.9152youxi.cn/Article/details/gttbwvlvzi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gtityxxgca.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumfqoprl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtyptpcwdh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.quarkkingdee.top/Article/details/gtilzuqjbi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guowangkeji.top/Article/details/gtcyalmaid.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cucudq.cn/Article/details/gtoxfyeisd.html

[N04] 斐波那契数列
来源：http://dali.pycfn.com/Article/details/gtipxwawzf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daxiang520.top/Article/details/gtuiwdipbr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yvedp.cn/Article/details/gtlafxqxtu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtorpauitp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gtmjkdaffu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gtkgfjsdap.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrxsbizl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gttdtjwzpa.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtoyxsoroj.html

[N05] 最大公约数
来源：http://dali.svipenyu.cn/Article/details/gtzagglqvb.html

Py:   math.gcd(a, b)
来源：http://dali.smart0.xyz/Article/details/gtnjlxhyng.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.snrcjt.cn/Article/details/gtydzbfceu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtkgmxhogs.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gtuijwvlwt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.bjfxy.top/Article/details/gtkguabiql.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hywenlv.cn/Article/details/gtmflgvdez.html

Ruby: a.gcd(b)
来源：http://dali.fzhhl.top/Article/details/gtssgcklvj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.wangdashe.top/Article/details/gtknncpodq.html

[N06] 判断回文字符串
来源：http://dali.sweek.top/Article/details/gtecwonuao.html

Py:   s == s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gthggctcjc.html

PHP:  $s === strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gtjxbzloyk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhgslrvi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtcsrlrlge.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guannengcc.top/Article/details/gtncntheqq.html

Go:   // 双指针从两端比较
来源：http://dali.aibaodan.cn/Article/details/gtfatvqzms.html

Ruby: s == s.reverse
来源：http://dali.jyoumei.cn/Article/details/gtxwcgjwga.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gtckvmqvza.html

[N07] 两数之和（返回下标）
来源：http://dali.sysykeji.top/Article/details/gtdwjaupaq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fzhhl.top/Article/details/gtrlxpbedk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.redwolf501.top/Article/details/gtrtgausii.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.guowangkeji.top/Article/details/gttexutfdn.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojryfimf.html

Java: // 手写 HashMap
来源：http://dali.shangyingyoupin.top/Article/details/gtgadzmtpy.html

Go:   // 手写 map[int]int
来源：http://dali.guowangkeji.top/Article/details/gtqphocggf.html

Ruby: // 手写 Hash
来源：http://dali.gogol.net.cn/Article/details/gtgvsfwfqs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nanxinkj.top/Article/details/gtwvruajzc.html

[N08] 生成全排列
来源：http://dali.jinqigufen.top/Article/details/gtvmrzrigc.html

Py:   itertools.permutations(arr)
来源：http://dali.mhx1999.top/Article/details/gtpyekhadg.html

PHP:  // 手写递归交换
来源：http://dali.guannengcc.top/Article/details/gtpxbglxfj.html

JS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtnrtccosa.html

TS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtldnxvevd.html

Java: // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtahrsuuda.html

Go:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtmghbtigb.html

Ruby: arr.permutation.to_a
来源：http://dali.ybcxt.top/Article/details/gtwpbrktmc.html

C#:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtafqzgpmj.html

[N09] 栈与队列
来源：http://dali.xziqi.cn/Article/details/gtshnfvpuo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hammf.cn/Article/details/gtjvquekzb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gtzcjylxzd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gtaxlgzapl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jianghu66.top/Article/details/gthiiayull.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuanzhike.top/Article/details/gtazzuxbpj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aibaodan.cn/Article/details/gtrjbtxbvt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gtmgrutgxs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yueranfly.top/Article/details/gttkzccbbb.html

[N10] 链表节点定义
来源：http://dali.guowangkeji.top/Article/details/gthycfdbmn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.kuanghao11.cn/Article/details/gtccewvtsi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xuetiantiany.cn/Article/details/gttyhnckna.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.haohaochexian.top/Article/details/gtnwvqsqcr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.smart0.xyz/Article/details/gtbjbtcjuo.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigufen.top/Article/details/gtfslglaxx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangshuangyany.cn/Article/details/gtlzcxfcbu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ivvv.top/Article/details/gtfqzltkge.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.havefunace.top/Article/details/gtvzezlgwf.html

[N11] 二叉树中序遍历
来源：http://dali.316326.xyz/Article/details/gtewcvtixl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ydzc1.top/Article/details/gtygdhfmro.html

PHP:  // 手写递归函数
来源：http://dali.yangfankeji.com/Article/details/gttvdcmyyq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxuanxn.top/Article/details/gtvhcdsqdg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gtqrfczqfn.html

Java: // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtmfnxrujo.html

Go:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtprvrdqac.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.c1oappe.top/Article/details/gtweywewpl.html

C#:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gtwnlyzwft.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.iojbl.cn/Article/details/gtmlgnhhqn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gaohongyu789.top/Article/details/gtvetkryja.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.wangdashe.top/Article/details/gtfpkgnhwk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.mhx1999.top/Article/details/gtbxicggrl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xziqi.cn/Article/details/gttgdqpztj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gtmtdnddcn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pycfn.com/Article/details/gttuqyidmr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.316326.xyz/Article/details/gtxgafllwe.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpuceuayf.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtsrmhodzv.html

O. 并发与异步
来源：http://dali.jinghuilouyu.cn/Article/details/gttjpxvwko.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtasaofkco.html

[O01] 启动一个线程
来源：http://dali.fengsongda.top/Article/details/gtmdpiwguk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.haohaochexian.top/Article/details/gtnkgaaewt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aibaodan.cn/Article/details/gthnjwxoew.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.feifeiyinyue.top/Article/details/gtxsnbmzve.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gthmscysgu.html

Java: new Thread(() -> f()).start()
来源：http://dali.guannengcc.top/Article/details/gtlzthnjnk.html

Go:   go f()
来源：http://dali.c1oappe.top/Article/details/gtyfwtzcbk.html

Ruby: Thread.new { f }
来源：http://dali.kuanghao11.cn/Article/details/gtpeweywzx.html

C#:   Task.Run(() => F());
来源：http://dali.sysykeji.top/Article/details/gtnsywkkxx.html

[O02] 使用线程池
来源：http://dali.hnxiangtu.top/Article/details/gtevgsdgth.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.chenjidiqi.icu/Article/details/gtarjgalcs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhoulong.xyz/Article/details/gtaubdvbrg.html

JS:   // worker_threads 线程池
来源：http://dali.yangfankeji.com/Article/details/gtvizgvqpp.html

TS:   // worker_threads 线程池
来源：http://dali.zhixingplan.top/Article/details/gtdnfnwapz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hnxiangtu.top/Article/details/gtxxrprhuh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.fengsongda.top/Article/details/gtcjlainxb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.iojbl.cn/Article/details/gtkbcljdgv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.dashuyun.cn/Article/details/gthfsnxjog.html

[O03] 加锁保护共享数据
来源：http://dali.cdnleiting.top/Article/details/gtopsxtuge.html

Py:   with lock: shared += 1
来源：http://dali.xziqi.cn/Article/details/gtxlstqiue.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.smart0.xyz/Article/details/gtspjfrisz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenlongwang.top/Article/details/gtsvlvwkdu.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gtcwpbhzvk.html

Java: synchronized (this) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gtgqxhkjde.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.svipenyu.cn/Article/details/gtxphqwnvf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuanzx.com/Article/details/gtsvwzqrql.html

C#:   lock (gate) { shared++; }
来源：http://dali.316326.xyz/Article/details/gtcmjjebun.html

[O04] 定义异步函数并等待
来源：http://dali.tian-w.cn/Article/details/gtcibhwzlq.html

Py:   async def f():⏎    await g()
来源：http://dali.haohaochexian.top/Article/details/gtlemzxkjq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jyoumei.cn/Article/details/gtgdnupzxe.html

JS:   async function f() { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgrsnxqt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gtwiatnocb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gaohongyu789.top/Article/details/gtsrkflxge.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuanzhike.top/Article/details/gtikuplntr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cdnleiting.top/Article/details/gtigpaqyyn.html

C#:   async Task F() { await G(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslaifpuc.html

[O05] 并发执行并等待全部完成
来源：http://dali.jianghu66.top/Article/details/gtdserybwq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gotoacloud.top/Article/details/gtbjgehukl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.feifeiyinyue.top/Article/details/gtwhqnnsjy.html

JS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnqtnxic.html

TS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gtsbnrshlx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guowangkeji.top/Article/details/gtuudxuwrn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yanxiufei.cn/Article/details/gtsxoytkkw.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gtyknocxdf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj20258.top/Article/details/gtjgpsxdxk.html

[O06] 使用进程池
来源：http://dali.yj20258.top/Article/details/gtkaletmir.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgufenzy.top/Article/details/gtwpwenjgh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.svipenyu.cn/Article/details/gtsgpptpwh.html

JS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gtdpvyayyn.html

TS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gtrylwlwbm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nanxinkj.top/Article/details/gtsoaviteh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xylfe.cn/Article/details/gtmaccrsow.html

Ruby: // fork 块
来源：http://dali.haohaochexian.top/Article/details/gtpshjiclc.html

C#:   Parallel.For
来源：http://dali.daxiang520.top/Article/details/gtqctzzjmk.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtaxugxobi.html

P. 常用工具函数
来源：http://dali.kuanghao11.cn/Article/details/gtdxwkqret.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtvvnanjty.html

[P01] 生成 UUID
来源：http://dali.dianchejie.cn/Article/details/gtblcqkcnh.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258.top/Article/details/gtlasycdpp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.birdmap.top/Article/details/gtvpjsrcof.html

JS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gttabctedz.html

TS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gtielmgone.html

Java: UUID.randomUUID().toString()
来源：http://dali.aibaodan.cn/Article/details/gtnznjjezv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ehwqpu.com/Article/details/gtbbcxedhm.html

Ruby: SecureRandom.uuid
来源：http://dali.birdmap.top/Article/details/gtwkldwhsg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.c1oappe.top/Article/details/gtmcwcvknq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tianlin.xyz/Article/details/gttdjvokca.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yuanzhike.top/Article/details/gtrjggttxy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hfpthk.cn/Article/details/gtegqswpva.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hnqzz.top/Article/details/gtmymwesye.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cqqwz.cn/Article/details/gtobkvngxm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuanzx.com/Article/details/gtwbczfnor.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sufxvd.cn/Article/details/gtifdvgnyu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.havefunace.top/Article/details/gtikiidotk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlfbmbzp.html

[P03] 生成短随机字符串
来源：http://dali.svipenyu.cn/Article/details/gtwrkrjxsd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gtdiufahqj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ydzc1.top/Article/details/gtntfgvmbn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jiagoushi.top/Article/details/gthhcpjiwb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsebiinfn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.smart0.xyz/Article/details/gtmupsksvk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shuidangran.top/Article/details/gtebnksbjr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxuanxn.top/Article/details/gtlbeqeheh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xinyue.icu/Article/details/gtjyvcsakq.html

[P04] 求长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmbjtkxo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258888.top/Article/details/gtgskouyhb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtlnntuilm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenzaomai.com/Article/details/gtcczmvvtm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenzaomai.com/Article/details/gtfulkedfz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gotoacloud.top/Article/details/gttixovoez.html

Go:   len(arr);  len(m)
来源：http://dali.sufxvd.cn/Article/details/gtqxjvgxup.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gtzfddjpdm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tianlin.xyz/Article/details/gtskrcxlrf.html


<!-- 参考信息 -->