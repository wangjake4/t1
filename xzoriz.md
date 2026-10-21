代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.havefunace.top/Article/details/gtpbwdrwiw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.andypj.xyz/Article/details/gthhvbsfbj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.feifeiyinyue.top/Article/details/gtonakrmip.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yvedp.cn/Article/details/gtjecypqsp.html

[L07] 处理 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gtqnuybbhr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gzhubu.top/Article/details/gtgvfbbsnq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fengsongda.top/Article/details/gtpkstfera.html

JS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gtqgmnaeau.html

TS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gtbvkcapgf.html

Java: resp.statusCode()
来源：http://dali.hnxiangtu.top/Article/details/gtfdrdpbra.html

Go:   resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gtseobbqmw.html

Ruby: resp.code.to_i
来源：http://dali.gogol.net.cn/Article/details/gtooypnuoy.html

C#:   (int)resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gtuzahwatu.html

[L08] 并发请求多个地址
来源：http://dali.jiagoushi.top/Article/details/gtwovehbfz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xziqi.cn/Article/details/gtzjnukvkj.html

PHP:  curl_multi_init() 系列
来源：http://dali.hongshengwenyu.top/Article/details/gtgpjjhhfc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwlmdmurw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtuucaycdq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.kuanghao11.cn/Article/details/gtrtofasdu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yueranfly.top/Article/details/gtybqivkln.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhixingplan.top/Article/details/gtgqiimqzj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtmgsxexzk.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahcrhrqt.html

M. 命令行 / 进程 / 环境
来源：http://dali.nwbrower.top/Article/details/gtjuydgbsn.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtixuaezjf.html

[M01] 读取命令行参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrjsqvty.html

Py:   sys.argv[1:]
来源：http://dali.yvedp.cn/Article/details/gtlgbiafxq.html

PHP:  $argv;  $argc;
来源：http://dali.zhongyouzk.top/Article/details/gtjruuwsuj.html

JS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtrifjwqnq.html

TS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtbfelqzzu.html

Java: args 数组（main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtmisllwhw.html

Go:   os.Args[1:]
来源：http://dali.xinyue.icu/Article/details/gtxukzkfji.html

Ruby: ARGV
来源：http://dali.feifeiyinyue.top/Article/details/gtiuwgtwjr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtzvyzfxqw.html

[M02] 读取环境变量
来源：http://dali.nwbrower.top/Article/details/gtgxzspmyp.html

Py:   os.environ.get("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtumgivywk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gtoyvzruqk.html

JS:   process.env.HOME
来源：http://dali.vqdsnc.cn/Article/details/gtklszetsw.html

TS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gtdgyrftli.html

Java: System.getenv("HOME")
来源：http://dali.guannengcc.top/Article/details/gtulzhmkle.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtntfnjdua.html

Ruby: ENV["HOME"]
来源：http://dali.zhongyouzk.top/Article/details/gtgpdqwogf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xziqi.cn/Article/details/gttzayivcq.html

[M03] 执行外部命令
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwlgqylo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dianchejie.cn/Article/details/gtblnkvvia.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.svipenyu.cn/Article/details/gtofyxkthv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtgwudtcbs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtujyjsqat.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.mhx1999.top/Article/details/gtakzranav.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlajolknp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnxiangtu.top/Article/details/gttsuhdxik.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenlongwang.top/Article/details/gtlvauzqiy.html

[M04] 获取当前工作目录
来源：http://dali.yj202588.top/Article/details/gtkeugdqbb.html

Py:   os.getcwd()
来源：http://dali.yj202588.top/Article/details/gtnafkwfnq.html

PHP:  getcwd();
来源：http://dali.havefunace.top/Article/details/gtmcnzzxwt.html

JS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gteelunmbh.html

TS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gtvrthbwoc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigufen.top/Article/details/gtusihcdhd.html

Go:   os.Getwd()
来源：http://dali.jqgfzy.top/Article/details/gtwalruxjr.html

Ruby: Dir.pwd
来源：http://dali.meibo888.top/Article/details/gtfcvvvulv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ybcxt.top/Article/details/gttnsgbton.html

[M05] 设置退出码
来源：http://dali.hywenlv.cn/Article/details/gtmrgplprx.html

Py:   sys.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtmwdobbnl.html

PHP:  exit(1);
来源：http://dali.meibo888.top/Article/details/gteaikiuvq.html

JS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtsxwtpfzo.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtunjvmgfk.html

Java: System.exit(1)
来源：http://dali.sxryk.cn/Article/details/gttriwkilz.html

Go:   os.Exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtssgaofdp.html

Ruby: exit 1
来源：http://dali.aizwys.cn/Article/details/gtdeogieok.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tianlin.xyz/Article/details/gtuivxktcv.html

[M06] 向标准错误输出
来源：http://dali.chenzaomai.com/Article/details/gtocyfpzox.html

Py:   print("err", file=sys.stderr)
来源：http://dali.bjfxy.top/Article/details/gtxtgfvoxl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgmpqknt.html

JS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gtuoijxuax.html

TS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gtiyzdhboj.html

Java: System.err.println("err")
来源：http://dali.aibaodan.cn/Article/details/gtmxeftiza.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sufxvd.cn/Article/details/gtanpqcudj.html

Ruby: warn "err"
来源：http://dali.birdmap.top/Article/details/gthgocokth.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xylfe.cn/Article/details/gtlrclaxyw.html

[M07] 判断是否为主入口
来源：http://dali.cheryme.top/Article/details/gtskqxvhou.html

Py:   if __name__ == "__main__":
来源：http://dali.aizwys.cn/Article/details/gtzfnmiwib.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.0kj1m.cn/Article/details/gtvwfsovnp.html

JS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gtezyqrxqw.html

TS:   require.main === module
来源：http://dali.smart0.xyz/Article/details/gtqjhxuymx.html

Java: public static void main(String[] args)
来源：http://dali.fzhhl.top/Article/details/gtqcvufarw.html

Go:   func main()
来源：http://dali.chenzaomai.com/Article/details/gtdrhdzssi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gaohongyu789.top/Article/details/gteyneaqsn.html

C#:   static void Main(string[] args)
来源：http://dali.jianghu66.top/Article/details/gtbeegkcru.html

[M08] 获取系统与运行时信息
来源：http://dali.quarkkingdee.top/Article/details/gtibvmjjyd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nwbrower.top/Article/details/gtztetbikv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigfzy.top/Article/details/gtvlawxeaz.html

JS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtfijgnxyg.html

TS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gtndijrqhc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ehwqpu.com/Article/details/gtqwzjzyuq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuxming.cn/Article/details/gttbvdfkaj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenzaomai.com/Article/details/gtdhrgidmn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenzaomai.com/Article/details/gtpdbboujg.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtgfmgxumf.html

N. 数据结构与算法
来源：http://dali.yanxiufei.cn/Article/details/gtkfoxcfpy.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtceeyuzat.html

[N01] 二分查找（有序数组）
来源：http://dali.feifeiyinyue.top/Article/details/gtrmjkqtue.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtxlilvghy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ydzc1.top/Article/details/gtlvxbltqg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtmzpcxwjc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xziqi.cn/Article/details/gtbwawnmhj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.meibo888.top/Article/details/gtaiswcuzr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtljmuiran.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shuidangran.top/Article/details/gtdcpuzczf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtinypushf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yangfankeji.com/Article/details/gtfiutcdya.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhiwuduotai.top/Article/details/gtasclpnup.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.svipenyu.cn/Article/details/gtdtclefrx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtwgzghvhk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtibpzlgyz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xziqi.cn/Article/details/gtbewwumzo.html

Go:   slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gtfxjgynvo.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gtvtauqose.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hfpthk.cn/Article/details/gtwluopuhw.html

[N03] 快速排序（分治示例）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhkiidwp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cashguo.top/Article/details/gtatmrwend.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yangfankeji.com/Article/details/gtovtjcbjj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gttaakbikd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gtsfqamsfu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.pengpengdd.cyou/Article/details/gtwfduwors.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.havefunace.top/Article/details/gtiswhcmab.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gzhubu.top/Article/details/gtqupqvlhj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tian-w.cn/Article/details/gtjyusmiwc.html

[N04] 斐波那契数列
来源：http://dali.yueranfly.top/Article/details/gtincldjbz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dianchejie.cn/Article/details/gtsdnckvls.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gtyamrlipk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtwgbqsdik.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtbkcimllk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gtnonlrxpn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dashuyun.cn/Article/details/gtqokmyepj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jiagoushi.top/Article/details/gtbrnlhofp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcahyyhle.html

[N05] 最大公约数
来源：http://dali.nwbrower.top/Article/details/gtpvcbmxpz.html

Py:   math.gcd(a, b)
来源：http://dali.shzxlz.cn/Article/details/gtdlgkktkw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shzxlz.cn/Article/details/gtzsueuapo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtrwcjkpqm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gttlykgxft.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigufen.top/Article/details/gtbvauteab.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yonumen.top/Article/details/gtgtmlyvcj.html

Ruby: a.gcd(b)
来源：http://dali.zycfv.cn/Article/details/gtkwhiutyr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jiagoushi.top/Article/details/gtcrrrwvzz.html

[N06] 判断回文字符串
来源：http://dali.c1oappe.top/Article/details/gtugajjpmp.html

Py:   s == s[::-1]
来源：http://dali.fengsongda.top/Article/details/gtlqumthvk.html

PHP:  $s === strrev($s);
来源：http://dali.ybcxt.top/Article/details/gtodzqtkfy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gtzdpbkkwl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtiubwscje.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.feifeiyinyue.top/Article/details/gtgpzvjiux.html

Go:   // 双指针从两端比较
来源：http://dali.guannengcc.top/Article/details/gtbfkhmmok.html

Ruby: s == s.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtuyrxzthe.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gtwjqfxdnt.html

[N07] 两数之和（返回下标）
来源：http://dali.fengsongda.top/Article/details/gtemixvjve.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pengpengdd.cyou/Article/details/gtfqmnbxzv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ehwqpu.com/Article/details/gteaubcgyz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pengpengdd.cyou/Article/details/gtlfxcdcdp.html

TS:   // 手写 Map<string, number>
来源：http://dali.mhx1999.top/Article/details/gtznirxact.html

Java: // 手写 HashMap
来源：http://dali.redwolf501.top/Article/details/gtizihxzjj.html

Go:   // 手写 map[int]int
来源：http://dali.birdmap.top/Article/details/gtjxlmepce.html

Ruby: // 手写 Hash
来源：http://dali.iojbl.cn/Article/details/gtslrrljll.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgfzy.top/Article/details/gtesaddmor.html

[N08] 生成全排列
来源：http://dali.hnqzz.top/Article/details/gttfqevxxo.html

Py:   itertools.permutations(arr)
来源：http://dali.shuidangran.top/Article/details/gtoljeudgb.html

PHP:  // 手写递归交换
来源：http://dali.sxryk.cn/Article/details/gtxxlyetof.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtnjncnppn.html

TS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtqchjnttk.html

Java: // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtrecohvqg.html

Go:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtsflwecvw.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gticlyxwjv.html

C#:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtdzjhndbn.html

[N09] 栈与队列
来源：http://dali.havefunace.top/Article/details/gtwhxezvig.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.mhx1999.top/Article/details/gteezfyrpm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtqhaumfwl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gtaivlhxqi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aizwys.cn/Article/details/gtrgrrvtoo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gtxkgsscdf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.havefunace.top/Article/details/gtnbsxacah.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonguvmqr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.haohaochexian.top/Article/details/gtcjveegrw.html

[N10] 链表节点定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtkspuomsb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shuidangran.top/Article/details/gtpttfzppe.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpwlefscp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zdqjudy.top/Article/details/gtnjuopody.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.haohaochexian.top/Article/details/gtxezebycm.html

Java: class Node { int v; Node next; }
来源：http://dali.daxiang520.top/Article/details/gtdluarcth.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gogol.net.cn/Article/details/gtifcwygpv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jianghu66.top/Article/details/gtkdjbcnsz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nwbrower.top/Article/details/gtaggfrlph.html

[N11] 二叉树中序遍历
来源：http://dali.jianghu66.top/Article/details/gtagjwwzwa.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nanxinkj.top/Article/details/gtdkajvmuz.html

PHP:  // 手写递归函数
来源：http://dali.aizwys.cn/Article/details/gtegbupnnk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gthojnzapj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gtlyzunqnb.html

Java: // 手写递归
来源：http://dali.tanke756.top/Article/details/gthscgfixw.html

Go:   // 手写递归
来源：http://dali.aizwys.cn/Article/details/gtkdgrcdoh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.havefunace.top/Article/details/gtjqpzjdbj.html

C#:   // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gtzzewklah.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenlongwang.top/Article/details/gthmjgqzbc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jyoumei.cn/Article/details/gteillmtxd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xuetiantiany.cn/Article/details/gtjhbdsghu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guowangkeji.top/Article/details/gtfxlmklmf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gtatyfskpj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pycfn.com/Article/details/gtxyzbznfw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aibaodan.cn/Article/details/gtowvithxv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenzaomai.com/Article/details/gthgdnnowd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gtqxwdbpla.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtclyfodjl.html

O. 并发与异步
来源：http://dali.yueranfly.top/Article/details/gtgsnhagdi.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtlcgkfjjg.html

[O01] 启动一个线程
来源：http://dali.sufxvd.cn/Article/details/gtdeuhsird.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gaohongyu789.top/Article/details/gtppqmehcy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dianchejie.cn/Article/details/gtnmplxdpg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jianghu66.top/Article/details/gtftwmobxc.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gtoxdmkyfq.html

Java: new Thread(() -> f()).start()
来源：http://dali.c1oappe.top/Article/details/gtexawakdj.html

Go:   go f()
来源：http://dali.nanxuanxn.top/Article/details/gtkjrdfzrb.html

Ruby: Thread.new { f }
来源：http://dali.yj20258888.top/Article/details/gtrngpvztd.html

C#:   Task.Run(() => F());
来源：http://dali.c1oappe.top/Article/details/gtnszqgfoo.html

[O02] 使用线程池
来源：http://dali.fzhhl.top/Article/details/gtyvazqpvf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jqgfzy.top/Article/details/gtqqcmptuh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.andypj.xyz/Article/details/gtlwxdqlcf.html

JS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gtczmhsvgw.html

TS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gtwscvkodq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangshuangyany.cn/Article/details/gtqhwyralp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ybcxt.top/Article/details/gtgrdjeotr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhixingplan.top/Article/details/gtwgrmftmt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.kuanghao11.cn/Article/details/gtbdglneby.html

[O03] 加锁保护共享数据
来源：http://dali.guowangkeji.top/Article/details/gtiwrbqirv.html

Py:   with lock: shared += 1
来源：http://dali.wangdashe.top/Article/details/gtjmgvedmx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hysaishi.cn/Article/details/gtxrqebecn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ppjwa.cn/Article/details/gtxfrconab.html

TS:   // 同 JS
来源：http://dali.iojbl.cn/Article/details/gtrnyldagu.html

Java: synchronized (this) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gtiwsvgkov.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhengqikj.top/Article/details/gtpdzegbno.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.9152youxi.cn/Article/details/gtsofyvbqh.html

C#:   lock (gate) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gttbljpfax.html

[O04] 定义异步函数并等待
来源：http://dali.cheryme.top/Article/details/gtvhjugmlf.html

Py:   async def f():⏎    await g()
来源：http://dali.guannengcc.top/Article/details/gtuiabeaad.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daxiang520.top/Article/details/gtbnimaesd.html

JS:   async function f() { await g(); }
来源：http://dali.ivvv.top/Article/details/gthagumrmj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gtflocaffm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jyoumei.cn/Article/details/gtaznxubkb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dashuyun.cn/Article/details/gtlppfepsz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shzxlz.cn/Article/details/gttsqzwdyp.html

C#:   async Task F() { await G(); }
来源：http://dali.cucudq.cn/Article/details/gtrenxnlzy.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqlglwoh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmnlasdk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fzhhl.top/Article/details/gtznjviwls.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gtswfcafyz.html

TS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gtfgxyjzsj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ydzc1.top/Article/details/gtzdrvqfdm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fengsongda.top/Article/details/gtxynevkza.html

Ruby: threads.map(&:join)
来源：http://dali.ydzc1.top/Article/details/gtfqclheuo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnxiangtu.top/Article/details/gtqmqtnlls.html

[O06] 使用进程池
来源：http://dali.jyoumei.cn/Article/details/gtuonwctaj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigufen.top/Article/details/gttxxorgko.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shzxlz.cn/Article/details/gtfbtzafdw.html

JS:   // child_process / cluster 模块
来源：http://dali.havefunace.top/Article/details/gtjjzoqtew.html

TS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gtxmeobhvj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ppjwa.cn/Article/details/gtajynfdno.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhiwuduotai.top/Article/details/gtnopityca.html

Ruby: // fork 块
来源：http://dali.hywenlv.cn/Article/details/gtkurgaflj.html

C#:   Parallel.For
来源：http://dali.jqgufenzy.top/Article/details/gtpdizqdyc.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtajesydjp.html

P. 常用工具函数
来源：http://dali.xylfe.cn/Article/details/gtutcvxrxg.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxjecvcp.html

[P01] 生成 UUID
来源：http://dali.zycfv.cn/Article/details/gtwjudfvzn.html

Py:   str(uuid.uuid4())
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsdpzykf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fzhhl.top/Article/details/gtlipvtszz.html

JS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gtkodizqhn.html

TS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gtsxpiqnde.html

Java: UUID.randomUUID().toString()
来源：http://dali.sxryk.cn/Article/details/gtwdlgmqaj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.smart0.xyz/Article/details/gtjoernjlm.html

Ruby: SecureRandom.uuid
来源：http://dali.zhongyouzk.top/Article/details/gtrdkvlery.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangdashe.top/Article/details/gtzigflrei.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shzxlz.cn/Article/details/gtbzgbilpd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yuanzhike.top/Article/details/gtdkmnjzlg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aibaodan.cn/Article/details/gtbmcirmhr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxaejvah.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jianghu66.top/Article/details/gtexnkwxfn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daria6918.cn/Article/details/gtdjkxcvpo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj202588.top/Article/details/gtadryygan.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbovkkih.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hammf.cn/Article/details/gtjfqsanwo.html

[P03] 生成短随机字符串
来源：http://dali.yueranfly.top/Article/details/gtqbsmqwew.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmapewrat.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnxiangtu.top/Article/details/gthielujcq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gtdggguahr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.0kj1m.cn/Article/details/gtsngrpeoo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ehwqpu.com/Article/details/gtvjgllstm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guannengcc.top/Article/details/gtxhhoqacl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsvnixfo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ivvv.top/Article/details/gttykzegeg.html

[P04] 求长度
来源：http://dali.xziqi.cn/Article/details/gtuaxomdrk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jyoumei.cn/Article/details/gtcgjmrsfj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtcacpcqew.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cdnleiting.top/Article/details/gtcgepsfve.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jlsjyb.cn/Article/details/gtaxorjdjm.html


<!-- 参考信息 -->