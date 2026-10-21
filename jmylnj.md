代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gtyplusxts.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jyoumei.cn/Article/details/gtqgyxdaiv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ivvv.top/Article/details/gtznuqbpbz.html

JS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gtisjvnjbq.html

TS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gttxkiwagi.html

Java: resp.statusCode()
来源：http://dali.xylfe.cn/Article/details/gtilhnabtr.html

Go:   resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gtmwnwljxs.html

Ruby: resp.code.to_i
来源：http://dali.xuanzx.com/Article/details/gtnowlqrjt.html

C#:   (int)resp.StatusCode
来源：http://dali.sweek.top/Article/details/gtjeygbesi.html

[L08] 并发请求多个地址
来源：http://dali.xuetiantiany.cn/Article/details/gtwglqozyf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jyoumei.cn/Article/details/gtiycyeqlb.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuanzx.com/Article/details/gtzzztlwgh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gtxxmparru.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gtugoaglyc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhiwuduotai.top/Article/details/gtjurjeqyv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hfpthk.cn/Article/details/gtpfmfrxlc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.havefunace.top/Article/details/gthonuzugd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtloupshkz.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtycadymig.html

M. 命令行 / 进程 / 环境
来源：http://dali.andypj.xyz/Article/details/gthhzvwinq.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtqdwygpng.html

[M01] 读取命令行参数
来源：http://dali.birdmap.top/Article/details/gtnxfyzoxx.html

Py:   sys.argv[1:]
来源：http://dali.zhixingplan.top/Article/details/gtxoxnyfby.html

PHP:  $argv;  $argc;
来源：http://dali.tianlin.xyz/Article/details/gthqdlsvqp.html

JS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gtsbdawoim.html

TS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gttlsarvtr.html

Java: args 数组（main 方法参数）
来源：http://dali.cashguo.top/Article/details/gtushpfggw.html

Go:   os.Args[1:]
来源：http://dali.ivvv.top/Article/details/gtiwvykupj.html

Ruby: ARGV
来源：http://dali.gzhubu.top/Article/details/gtcwadyesc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gtjkrhbhie.html

[M02] 读取环境变量
来源：http://dali.fzhhl.top/Article/details/gtjtayouuk.html

Py:   os.environ.get("HOME")
来源：http://dali.sweek.top/Article/details/gtfiievhau.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtjnvrzrfw.html

JS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gteprirnwp.html

TS:   process.env.HOME
来源：http://dali.tanke756.top/Article/details/gtgsypaife.html

Java: System.getenv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtavyowcio.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtvsznsryq.html

Ruby: ENV["HOME"]
来源：http://dali.jiagoushi.top/Article/details/gthglqgnch.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hammf.cn/Article/details/gtftnirqmj.html

[M03] 执行外部命令
来源：http://dali.316326.xyz/Article/details/gtukyxmnpw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jlsjyb.cn/Article/details/gtqhjiwobc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gaohongyu789.top/Article/details/gtbnhodiou.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gtiwkweepm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gtlxtetmqt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fzhhl.top/Article/details/gtrkozpvsa.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gotoacloud.top/Article/details/gtushdalhv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuanzx.com/Article/details/gticjmvwei.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gtwefyghqf.html

[M04] 获取当前工作目录
来源：http://dali.hfpthk.cn/Article/details/gtlbsbmwsh.html

Py:   os.getcwd()
来源：http://dali.chenlongwang.top/Article/details/gtggpmizkw.html

PHP:  getcwd();
来源：http://dali.tian-w.cn/Article/details/gtwgvdbzgx.html

JS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehspgcmg.html

TS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gtbiheagfy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrfkazcn.html

Go:   os.Getwd()
来源：http://dali.fzhhl.top/Article/details/gtwtqadhsx.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gtuiyhcrhp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zdqjudy.top/Article/details/gtlgrvfhoy.html

[M05] 设置退出码
来源：http://dali.cashguo.top/Article/details/gtadpnxzph.html

Py:   sys.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtteifxdti.html

PHP:  exit(1);
来源：http://dali.sufxvd.cn/Article/details/gtomiabgiz.html

JS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtmmfytgwt.html

TS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtphekavvl.html

Java: System.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtpkucxphj.html

Go:   os.Exit(1)
来源：http://dali.xinyue.icu/Article/details/gtqqmtwiyp.html

Ruby: exit 1
来源：http://dali.zycfv.cn/Article/details/gtpjhwznoo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhiwuduotai.top/Article/details/gttbyjfdvd.html

[M06] 向标准错误输出
来源：http://dali.ivvv.top/Article/details/gtndurheyp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xziqi.cn/Article/details/gtxvnpnora.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.meibo888.top/Article/details/gtjzxwfhvj.html

JS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gtxbqstixm.html

TS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gtxgwolfwf.html

Java: System.err.println("err")
来源：http://dali.yanxiufei.cn/Article/details/gtnpepymov.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jianghu66.top/Article/details/gtmecuzobf.html

Ruby: warn "err"
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhdxlhhu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.snrcjt.cn/Article/details/gtfqufcqpb.html

[M07] 判断是否为主入口
来源：http://dali.cdnleiting.top/Article/details/gtqtfxwjbu.html

Py:   if __name__ == "__main__":
来源：http://dali.redwolf501.top/Article/details/gtguyjgnhd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.9152youxi.cn/Article/details/gtoeyxblre.html

JS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhuwlxpw.html

TS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gtqpluwmuk.html

Java: public static void main(String[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gtwpnorwqb.html

Go:   func main()
来源：http://dali.wangshuangyany.cn/Article/details/gtztmtuhpj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgfzy.top/Article/details/gtqxejgdea.html

C#:   static void Main(string[] args)
来源：http://dali.sxryk.cn/Article/details/gthyxazcnt.html

[M08] 获取系统与运行时信息
来源：http://dali.9152youxi.cn/Article/details/gtvjgwcdki.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daria6918.cn/Article/details/gtqkedyksv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xziqi.cn/Article/details/gtqhyiudwb.html

JS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gtztzkfifh.html

TS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtkfdeeikv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xylfe.cn/Article/details/gthjjmdnrs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jlsjyb.cn/Article/details/gthpiokomb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.c1oappe.top/Article/details/gtajetvfxh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dianchejie.cn/Article/details/gtvxftkvsk.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gttffkwvjc.html

N. 数据结构与算法
来源：http://dali.daria6918.cn/Article/details/gtojhpvywn.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtfypwlcgm.html

[N01] 二分查找（有序数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczsrxlyl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtybfastes.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cucudq.cn/Article/details/gtezbjmmfh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtntdqzayp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gttwtelncd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtrldljhhu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xinyue.icu/Article/details/gttqccrbdi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.smart0.xyz/Article/details/gtwjoqfpdt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtwasectjc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gtqbziknpf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.kuanghao11.cn/Article/details/gtvbgdezkj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtqqqfnmdh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gtbzpcenyl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gtmzexvuyq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhongyouzk.top/Article/details/gtinpsjrgu.html

Go:   slices.Sort(arr)
来源：http://dali.jiagoushi.top/Article/details/gtfwprfjxw.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gtqmepckdu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.andypj.xyz/Article/details/gtmnpgffrx.html

[N03] 快速排序（分治示例）
来源：http://dali.cqqwz.cn/Article/details/gtfgkgrkvl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxlfsfkn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yangfankeji.com/Article/details/gtlenyztgj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ehwqpu.com/Article/details/gteqzimfyi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gtbpofzxoo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenzaomai.com/Article/details/gtucoeponi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuanzx.com/Article/details/gtnjuufakt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.aibaodan.cn/Article/details/gtsuaascdw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xuetiantiany.cn/Article/details/gtzhnxoskf.html

[N04] 斐波那契数列
来源：http://dali.gogol.net.cn/Article/details/gtdcielauq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gtnkrptgel.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gtlnnezltl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gtzhnkswiq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gtzlpobmlh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gtznwggzsi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhiwuduotai.top/Article/details/gtthneyfxo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtbjdalxsa.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gthcyrdztn.html

[N05] 最大公约数
来源：http://dali.jianghu66.top/Article/details/gtdfmvlqgs.html

Py:   math.gcd(a, b)
来源：http://dali.sysykeji.top/Article/details/gtpfvzavqg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgufenzy.top/Article/details/gtlitqffga.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtaujnnojs.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gthynytrrl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhixingplan.top/Article/details/gtfchgvhiu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj202588.top/Article/details/gtqrdiwefw.html

Ruby: a.gcd(b)
来源：http://dali.chenzaomai.com/Article/details/gtpxuwcgco.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fzhhl.top/Article/details/gtiompzhdc.html

[N06] 判断回文字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtxyphvlkp.html

Py:   s == s[::-1]
来源：http://dali.cashguo.top/Article/details/gtlzlyfdgw.html

PHP:  $s === strrev($s);
来源：http://dali.fzhhl.top/Article/details/gtwzxwjrlm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtkhsppmrv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtplpnwldh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sxryk.cn/Article/details/gtewbjekqd.html

Go:   // 双指针从两端比较
来源：http://dali.yuanzhike.top/Article/details/gtvrgocehd.html

Ruby: s == s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcszbuoiq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gtvsitdzbn.html

[N07] 两数之和（返回下标）
来源：http://dali.sweek.top/Article/details/gtkojrgbei.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxuanxn.top/Article/details/gtfswvattg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jlsjyb.cn/Article/details/gtdixdfeqc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhoulong.xyz/Article/details/gtaxiafdcf.html

TS:   // 手写 Map<string, number>
来源：http://dali.9152youxi.cn/Article/details/gtemeamboh.html

Java: // 手写 HashMap
来源：http://dali.havefunace.top/Article/details/gtchaztiba.html

Go:   // 手写 map[int]int
来源：http://dali.quarkkingdee.top/Article/details/gttvmdazrn.html

Ruby: // 手写 Hash
来源：http://dali.xuanzx.com/Article/details/gtpfurwevu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zdqjudy.top/Article/details/gtkzlhboif.html

[N08] 生成全排列
来源：http://dali.hywenlv.cn/Article/details/gtboqkusyw.html

Py:   itertools.permutations(arr)
来源：http://dali.guannengcc.top/Article/details/gtzisshiwm.html

PHP:  // 手写递归交换
来源：http://dali.nwbrower.top/Article/details/gtuhivkdpa.html

JS:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtauhlxduh.html

TS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtrhdmymdh.html

Java: // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtvlvzpfjh.html

Go:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtaujscpwo.html

Ruby: arr.permutation.to_a
来源：http://dali.hongshengwenyu.top/Article/details/gtspmqbser.html

C#:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtrlxbtuhm.html

[N09] 栈与队列
来源：http://dali.ybcxt.top/Article/details/gtlfvxzdiv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.havefunace.top/Article/details/gtxyshopvg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtrtuwtcgd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gthazloojm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.feifeiyinyue.top/Article/details/gtcjrfxnjv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ybcxt.top/Article/details/gtlkjrbxal.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.snrcjt.cn/Article/details/gtxqhufqsa.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtcjtsdxfv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuanzx.com/Article/details/gtbijprwve.html

[N10] 链表节点定义
来源：http://dali.dashuyun.cn/Article/details/gtddqfhgse.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tian-w.cn/Article/details/gtosrkrliy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.pycfn.com/Article/details/gtwswpomnx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigfzy.top/Article/details/gtkhqrpsvv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hammf.cn/Article/details/gtcyffeoen.html

Java: class Node { int v; Node next; }
来源：http://dali.xylfe.cn/Article/details/gtvinwpcux.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tian-w.cn/Article/details/gtiycefakm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.vqdsnc.cn/Article/details/gtubtrdncb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhoulong.xyz/Article/details/gthcnpiedi.html

[N11] 二叉树中序遍历
来源：http://dali.nwbrower.top/Article/details/gtubufawdq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hysaishi.cn/Article/details/gtuohxrwwv.html

PHP:  // 手写递归函数
来源：http://dali.tanke756.top/Article/details/gtbznqwqty.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gtazsstxti.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gteilhbztg.html

Java: // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtjpwvrbvk.html

Go:   // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtsskajowb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xylfe.cn/Article/details/gtgbdmzlar.html

C#:   // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gtajroqtlj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cashguo.top/Article/details/gtxxjslhfd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.c1oappe.top/Article/details/gtbajyjjvy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fengsongda.top/Article/details/gtyfznvlno.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gtscfehwsk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhiwuduotai.top/Article/details/gtdibwtwbv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnqzz.top/Article/details/gtoqwktrjs.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guannengcc.top/Article/details/gtkebmgrzu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gtuqwqibkb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxexsxbsv.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gthlbvwpkn.html

O. 并发与异步
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqsttmqk.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtpbjhqmxu.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gtmhzvxclr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nwbrower.top/Article/details/gtlpnwbala.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.pycfn.com/Article/details/gthfmdmalp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.feifeiyinyue.top/Article/details/gtiaygvgpn.html

TS:   // 同 JS
来源：http://dali.haohaochexian.top/Article/details/gtjgzwipuh.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigfzy.top/Article/details/gtbblktwzg.html

Go:   go f()
来源：http://dali.smart0.xyz/Article/details/gtsftepnci.html

Ruby: Thread.new { f }
来源：http://dali.shzxlz.cn/Article/details/gtdvfowxzy.html

C#:   Task.Run(() => F());
来源：http://dali.zdqjudy.top/Article/details/gtggfgzsnc.html

[O02] 使用线程池
来源：http://dali.ehwqpu.com/Article/details/gtnhmlkvlw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gotoacloud.top/Article/details/gtwtqcvfgk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.feifeiyinyue.top/Article/details/gtqezxrxcg.html

JS:   // worker_threads 线程池
来源：http://dali.xylfe.cn/Article/details/gtukmiyfgp.html

TS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gtiligrwxx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nwbrower.top/Article/details/gtaxibnade.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenlongwang.top/Article/details/gtlgofxhrn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hammf.cn/Article/details/gtmjtrnxie.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xuetiantiany.cn/Article/details/gtckeueauo.html

[O03] 加锁保护共享数据
来源：http://dali.xinyue.icu/Article/details/gtivglwwrx.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvqfdwwe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cdnleiting.top/Article/details/gtjdqevwwp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pycfn.com/Article/details/gtwdthxhnd.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gtweiwnfau.html

Java: synchronized (this) { shared++; }
来源：http://dali.daria6918.cn/Article/details/gtbscsbkem.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xziqi.cn/Article/details/gtoaxydzfh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yongpay.top/Article/details/gtgdcerbru.html

C#:   lock (gate) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gtrslwcuvz.html

[O04] 定义异步函数并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufzynzzz.html

Py:   async def f():⏎    await g()
来源：http://dali.xylfe.cn/Article/details/gtxnyrcnkf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daria6918.cn/Article/details/gtmkpvpkhc.html

JS:   async function f() { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gtakwjuhmn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gzhubu.top/Article/details/gthmkdscyb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.svipenyu.cn/Article/details/gtmzhdrzps.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daria6918.cn/Article/details/gtgngkouck.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gotoacloud.top/Article/details/gtpejpobne.html

C#:   async Task F() { await G(); }
来源：http://dali.gzhubu.top/Article/details/gthrqyjdna.html

[O05] 并发执行并等待全部完成
来源：http://dali.jyoumei.cn/Article/details/gtaflfgois.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nanxinkj.top/Article/details/gtqxbfsdsz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hongshengwenyu.top/Article/details/gtvilnumay.html

JS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gtxzyijimt.html

TS:   await Promise.all(tasks)
来源：http://dali.fengsongda.top/Article/details/gtsjxvskxk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.mhx1999.top/Article/details/gtpgwbymkh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sysykeji.top/Article/details/gtwolbohbm.html

Ruby: threads.map(&:join)
来源：http://dali.nwbrower.top/Article/details/gtnjhfufur.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nwbrower.top/Article/details/gtlgwmtmyj.html

[O06] 使用进程池
来源：http://dali.hnxiangtu.top/Article/details/gtomnyliqd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ehwqpu.com/Article/details/gtuhskeccy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.haohaochexian.top/Article/details/gtslrzhoyu.html

JS:   // child_process / cluster 模块
来源：http://dali.xuetiantiany.cn/Article/details/gtxsawlkjo.html

TS:   // child_process / cluster 模块
来源：http://dali.aibaodan.cn/Article/details/gtswdsvgyw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinqigfzy.top/Article/details/gtgiujdxak.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nwbrower.top/Article/details/gtwxxpoivc.html

Ruby: // fork 块
来源：http://dali.ppjwa.cn/Article/details/gtclrlktcd.html

C#:   Parallel.For
来源：http://dali.yueranfly.top/Article/details/gtpqxesynw.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtsyjbvkzw.html

P. 常用工具函数
来源：http://dali.pengpengdd.cyou/Article/details/gtfhakovpn.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtmhlfyeoh.html

[P01] 生成 UUID
来源：http://dali.shzxlz.cn/Article/details/gtqlxeclpf.html

Py:   str(uuid.uuid4())
来源：http://dali.yonumen.top/Article/details/gtisiqwpoc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhgvwozm.html

JS:   crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gtzgjlefqv.html

TS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtkkkxkpaa.html

Java: UUID.randomUUID().toString()
来源：http://dali.cdnleiting.top/Article/details/gtmiplebrt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jiagoushi.top/Article/details/gtxbylrrwi.html

Ruby: SecureRandom.uuid
来源：http://dali.sweek.top/Article/details/gtrfybomkq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhongyouzk.top/Article/details/gtqncehxnz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.guannengcc.top/Article/details/gttjdglflh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yangfankeji.com/Article/details/gtjiryqwxv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jqgufenzy.top/Article/details/gtdptqmtub.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sufxvd.cn/Article/details/gtqqrmkcom.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenjidiqi.icu/Article/details/gtmjgtmvdp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxinkj.top/Article/details/gtznihrlnt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shzxlz.cn/Article/details/gtgnscjphj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.havefunace.top/Article/details/gtiujafwoi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuxming.cn/Article/details/gtdtrcikty.html

[P03] 生成短随机字符串
来源：http://dali.birdmap.top/Article/details/gtdoppknhf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.svipenyu.cn/Article/details/gtumsvliof.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.svipenyu.cn/Article/details/gtlktwhbce.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xinyue.icu/Article/details/gtgrawxpme.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigufen.top/Article/details/gtgxbnvltb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigufen.top/Article/details/gtntdrebmz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nwbrower.top/Article/details/gtkfjjoasf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nwbrower.top/Article/details/gtqkzosqkg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258888.top/Article/details/gtwbkulsli.html

[P04] 求长度
来源：http://dali.zdqjudy.top/Article/details/gtcjhpuhhb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenlongwang.top/Article/details/gtdktcsejq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gttnvxkgqs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gtmgcqqbhh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gthykcztie.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jyoumei.cn/Article/details/gtdyeyurgo.html

Go:   len(arr);  len(m)
来源：http://dali.shzxlz.cn/Article/details/gtdzvkaovw.html

Ruby: x.length;  x.size
来源：http://dali.vqdsnc.cn/Article/details/gtaygiuwab.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenlongwang.top/Article/details/gtkqvjscfm.html


<!-- 参考信息 -->