代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.meibo888.top/Article/details/gttjgupljl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shangyingyoupin.top/Article/details/gttzniyaot.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtqesmvlbm.html

[L06] 解析响应为 JSON
来源：http://dali.cashguo.top/Article/details/gtakmnjpxb.html

Py:   resp.json()
来源：http://dali.aibaodan.cn/Article/details/gteitwelgz.html

PHP:  json_decode($body, true);
来源：http://dali.0kj1m.cn/Article/details/gtypyqozto.html

JS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gtfgdcqpoc.html

TS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gtanpbycdi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtqalphlam.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhbeiwhi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ybcxt.top/Article/details/gtkbznougt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.bjfxy.top/Article/details/gtcibqkkuk.html

[L07] 处理 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gtexacvfwv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yueranfly.top/Article/details/gtakawmibs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tianlin.xyz/Article/details/gtdueyynax.html

JS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gtuvowjavx.html

TS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gtaxhwtfmr.html

Java: resp.statusCode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdsztnsfe.html

Go:   resp.StatusCode
来源：http://dali.wangdashe.top/Article/details/gtthvbirhk.html

Ruby: resp.code.to_i
来源：http://dali.sufxvd.cn/Article/details/gtbcwpzflj.html

C#:   (int)resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gtjdmnupvu.html

[L08] 并发请求多个地址
来源：http://dali.hnxiangtu.top/Article/details/gtwlzmedmw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zdqjudy.top/Article/details/gtsksamoxe.html

PHP:  curl_multi_init() 系列
来源：http://dali.dianchejie.cn/Article/details/gtnmxydkfg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtptbsqlnd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gtacvfzvbk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cashguo.top/Article/details/gtjetnjqcn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.kuanghao11.cn/Article/details/gtaddqvqvh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xziqi.cn/Article/details/gtlsslpwvf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zdqjudy.top/Article/details/gtvdtdyqfb.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtzskgmeoj.html

M. 命令行 / 进程 / 环境
来源：http://dali.ivvv.top/Article/details/gtvxmmgxlp.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtjvveytfd.html

[M01] 读取命令行参数
来源：http://dali.316326.xyz/Article/details/gtpwgkdjup.html

Py:   sys.argv[1:]
来源：http://dali.tanke756.top/Article/details/gtjqjaebeo.html

PHP:  $argv;  $argc;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzuwdcox.html

JS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gtqsmfyekc.html

TS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtndiqwvhs.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gtsjvjegyr.html

Go:   os.Args[1:]
来源：http://dali.gzhubu.top/Article/details/gtakgpqxor.html

Ruby: ARGV
来源：http://dali.yj20258888.top/Article/details/gtwclopxyp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtviywfswx.html

[M02] 读取环境变量
来源：http://dali.yonumen.top/Article/details/gtcuptjmjb.html

Py:   os.environ.get("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtuiriaaoc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gtrgzzkhiq.html

JS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gteivqrihn.html

TS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gtrlnkkxyc.html

Java: System.getenv("HOME")
来源：http://dali.nwbrower.top/Article/details/gtzvfadsur.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtytuksbjy.html

Ruby: ENV["HOME"]
来源：http://dali.hongshengwenyu.top/Article/details/gtikarlesi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtvazobgnh.html

[M03] 执行外部命令
来源：http://dali.vqdsnc.cn/Article/details/gtlexbrdub.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.meibo888.top/Article/details/gtjnznjdpt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shuidangran.top/Article/details/gtspoagscc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtjlantzav.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gtjmxyaoal.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.0kj1m.cn/Article/details/gtiskrjrcq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sxryk.cn/Article/details/gtvnpxyifx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ppjwa.cn/Article/details/gtvkhahjeq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.dashuyun.cn/Article/details/gtrkqyxcyo.html

[M04] 获取当前工作目录
来源：http://dali.gogol.net.cn/Article/details/gtkjtugnfe.html

Py:   os.getcwd()
来源：http://dali.jqgfzy.top/Article/details/gtszocjhez.html

PHP:  getcwd();
来源：http://dali.feifeiyinyue.top/Article/details/gtlcfhbqth.html

JS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyykvimav.html

TS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtnybhbkrc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ydzc1.top/Article/details/gthrdvetpy.html

Go:   os.Getwd()
来源：http://dali.haohaochexian.top/Article/details/gtiqbbyvay.html

Ruby: Dir.pwd
来源：http://dali.xuanzx.com/Article/details/gtdgurpsou.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dianchejie.cn/Article/details/gtgeaqjfix.html

[M05] 设置退出码
来源：http://dali.yj202588.top/Article/details/gtaqksxegc.html

Py:   sys.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtzvvsqlnk.html

PHP:  exit(1);
来源：http://dali.cheryme.top/Article/details/gtoilatvbh.html

JS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtfppporvt.html

TS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtortmtppz.html

Java: System.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtkkrbtebw.html

Go:   os.Exit(1)
来源：http://dali.mhx1999.top/Article/details/gtipujvrez.html

Ruby: exit 1
来源：http://dali.jinqigfzy.top/Article/details/gtuyzhgbbc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yueranfly.top/Article/details/gtqkpilnbw.html

[M06] 向标准错误输出
来源：http://dali.snrcjt.cn/Article/details/gtcmbsgrhd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pycfn.com/Article/details/gtpfjwnvyo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aizwys.cn/Article/details/gthabvfsjm.html

JS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gtjhwfsgzf.html

TS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gtbhnjeeyc.html

Java: System.err.println("err")
来源：http://dali.hysaishi.cn/Article/details/gtzxvszpyb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangdashe.top/Article/details/gtqufcohgh.html

Ruby: warn "err"
来源：http://dali.xinyue.icu/Article/details/gtrvusynrh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tian-w.cn/Article/details/gtserokqpf.html

[M07] 判断是否为主入口
来源：http://dali.jyoumei.cn/Article/details/gtmpvmpxal.html

Py:   if __name__ == "__main__":
来源：http://dali.svipenyu.cn/Article/details/gthlvfbpir.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hywenlv.cn/Article/details/gtsippmopp.html

JS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gtpffehelx.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gtpwbfsrnf.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzngqqojx.html

Go:   func main()
来源：http://dali.dianchejie.cn/Article/details/gtxspyyiwh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.iojbl.cn/Article/details/gtbqrlyixs.html

C#:   static void Main(string[] args)
来源：http://dali.hnqzz.top/Article/details/gtsttdxczc.html

[M08] 获取系统与运行时信息
来源：http://dali.guannengcc.top/Article/details/gtfglcmncx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gaohongyu789.top/Article/details/gttdlxbmmu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hammf.cn/Article/details/gtbxdtmhnf.html

JS:   process.platform;  process.version
来源：http://dali.c1oappe.top/Article/details/gtgmptaynw.html

TS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gtmrrbfsdb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ppjwa.cn/Article/details/gtdvtzmlan.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ybcxt.top/Article/details/gtuysagicv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.snrcjt.cn/Article/details/gtcvuqmoub.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ydzc1.top/Article/details/gthamrhihy.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtmukxndtu.html

N. 数据结构与算法
来源：http://dali.daria6918.cn/Article/details/gtxtvvdyob.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtnnscintv.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgufenzy.top/Article/details/gtplfewmno.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cashguo.top/Article/details/gtdbilgxgv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnqzz.top/Article/details/gtruwiqidw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnqzz.top/Article/details/gtsbrryjcc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gtvyctoxvs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtzwwlllwo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtfdqteagg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenlongwang.top/Article/details/gtrseowedy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtldxsfzju.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.svipenyu.cn/Article/details/gtcflvamss.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj202588.top/Article/details/gtdsuxkbsq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtfstxomgx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtbwvnmmqz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gtvstfzztx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jqgfzy.top/Article/details/gtwczzzxcd.html

Go:   slices.Sort(arr)
来源：http://dali.wangdashe.top/Article/details/gtvlxuoktt.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gtolgbrqkz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtirmzdrwd.html

[N03] 快速排序（分治示例）
来源：http://dali.cheryme.top/Article/details/gtnvjevofq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aibaodan.cn/Article/details/gtbizmetag.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shangyingyoupin.top/Article/details/gtvwuzqlbg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gtdsgonciy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsdmupglu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhongyouzk.top/Article/details/gtkqxqunil.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hnxiangtu.top/Article/details/gttrfcxdxy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hysaishi.cn/Article/details/gtkfuelhwp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tanke756.top/Article/details/gtuskkorhu.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangtech.top/Article/details/gtajitsstx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxgrwxyf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ivvv.top/Article/details/gtpdsernty.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gtqmmuhzsf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gtxobavvjg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dashuyun.cn/Article/details/gtwkdlfuld.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnqzz.top/Article/details/gtujxxhydt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtmkksfksz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtctubrylo.html

[N05] 最大公约数
来源：http://dali.cheryme.top/Article/details/gtybwflsfa.html

Py:   math.gcd(a, b)
来源：http://dali.yonumen.top/Article/details/gtaslthfpg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsnxmfjm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jlsjyb.cn/Article/details/gtssqftowg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gtqwaxoybo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xinyue.icu/Article/details/gtbldhpcns.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj202588.top/Article/details/gtwdmvzlss.html

Ruby: a.gcd(b)
来源：http://dali.316326.xyz/Article/details/gtjqgmsabr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guannengcc.top/Article/details/gteptcahxx.html

[N06] 判断回文字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtnddlwcnc.html

Py:   s == s[::-1]
来源：http://dali.gogol.net.cn/Article/details/gtpojcqzdj.html

PHP:  $s === strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gtrxsnsihg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtbklfgrrn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtvhjjmbke.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.0kj1m.cn/Article/details/gtixynrfhc.html

Go:   // 双指针从两端比较
来源：http://dali.xylfe.cn/Article/details/gtdbdqgume.html

Ruby: s == s.reverse
来源：http://dali.dianchejie.cn/Article/details/gtuapopzzq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gtmtloapas.html

[N07] 两数之和（返回下标）
来源：http://dali.hongshengwenyu.top/Article/details/gtjfsnrmgh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.andypj.xyz/Article/details/gtalviybnl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fzhhl.top/Article/details/gtwzuszkqj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yongpay.top/Article/details/gtzpzpnxuf.html

TS:   // 手写 Map<string, number>
来源：http://dali.hammf.cn/Article/details/gtkzmhtsqq.html

Java: // 手写 HashMap
来源：http://dali.gaohongyu789.top/Article/details/gtvayrsxyd.html

Go:   // 手写 map[int]int
来源：http://dali.yj202588.top/Article/details/gtjtuuecit.html

Ruby: // 手写 Hash
来源：http://dali.sxryk.cn/Article/details/gtniirlzer.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dianchejie.cn/Article/details/gtbkfesmxw.html

[N08] 生成全排列
来源：http://dali.yongpay.top/Article/details/gtwsnzldew.html

Py:   itertools.permutations(arr)
来源：http://dali.smart0.xyz/Article/details/gtcjcggtzj.html

PHP:  // 手写递归交换
来源：http://dali.iojbl.cn/Article/details/gtxwqesxpf.html

JS:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtykyirylx.html

TS:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtjgguukwb.html

Java: // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtirydcjtd.html

Go:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtqufxdpnn.html

Ruby: arr.permutation.to_a
来源：http://dali.ydzc1.top/Article/details/gtweyssebp.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtrpsjeksr.html

[N09] 栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gtmnyvtdkj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shuidangran.top/Article/details/gtpeingiuy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.birdmap.top/Article/details/gtjjxfenkk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtvuojomji.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yvedp.cn/Article/details/gteygkqyhq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gogol.net.cn/Article/details/gthfxfhijb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenjidiqi.icu/Article/details/gtfjmuwojx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtfqvnqwea.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.birdmap.top/Article/details/gthvniwljc.html

[N10] 链表节点定义
来源：http://dali.guannengcc.top/Article/details/gtgwifesju.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jianghu66.top/Article/details/gteqiwnnhj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhixingplan.top/Article/details/gtkjlukbke.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fengsongda.top/Article/details/gtiljcbrop.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.smart0.xyz/Article/details/gtnfocczwd.html

Java: class Node { int v; Node next; }
来源：http://dali.guannengcc.top/Article/details/gtqepzxzqb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.guowangkeji.top/Article/details/gteuswbrld.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.mhx1999.top/Article/details/gtgxdentyh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.kuanghao11.cn/Article/details/gtsopxapvm.html

[N11] 二叉树中序遍历
来源：http://dali.tianlin.xyz/Article/details/gtdrnepbyx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.mhx1999.top/Article/details/gttigrcnbi.html

PHP:  // 手写递归函数
来源：http://dali.316326.xyz/Article/details/gtbhqzqfil.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gtawpmrssk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cheryme.top/Article/details/gtcxtpxfcp.html

Java: // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtbgpoieqm.html

Go:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtefnjgfci.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfaqumkge.html

C#:   // 手写递归
来源：http://dali.xziqi.cn/Article/details/gtbpfhqydb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tanke756.top/Article/details/gtqjjlvgiq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwigxrsf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ivvv.top/Article/details/gtxigsefkr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gtyqexrtwk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gtrkrooccf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gtkncpltag.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.meibo888.top/Article/details/gtzbyenvny.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hnqzz.top/Article/details/gtcwyfhdaa.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dashuyun.cn/Article/details/gtkvalpxhy.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtxhtqgnbf.html

O. 并发与异步
来源：http://dali.chenzaomai.com/Article/details/gtdmkkdtdd.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtrkqpmgmb.html

[O01] 启动一个线程
来源：http://dali.jianghu66.top/Article/details/gthozdzfgt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aibaodan.cn/Article/details/gtjckobwso.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aibaodan.cn/Article/details/gthnufhanp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gotoacloud.top/Article/details/gtpvgmumcg.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwkifodo.html

Java: new Thread(() -> f()).start()
来源：http://dali.hysaishi.cn/Article/details/gtyfxhflhg.html

Go:   go f()
来源：http://dali.wangdashe.top/Article/details/gtgrxkygom.html

Ruby: Thread.new { f }
来源：http://dali.xinyue.icu/Article/details/gtsjfjoyhr.html

C#:   Task.Run(() => F());
来源：http://dali.xuanzx.com/Article/details/gtqyplwdnr.html

[O02] 使用线程池
来源：http://dali.hfpthk.cn/Article/details/gtepomtbpl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigfzy.top/Article/details/gtenaxwyvw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dianchejie.cn/Article/details/gtbusgkvaf.html

JS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gtrecwqywx.html

TS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gtlcqahazo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daria6918.cn/Article/details/gtpsblkoig.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhengqikj.top/Article/details/gtnfkxrfrb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cucudq.cn/Article/details/gtcjstyfcu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.quarkkingdee.top/Article/details/gtytncvxip.html

[O03] 加锁保护共享数据
来源：http://dali.daria6918.cn/Article/details/gtuwxkvdyg.html

Py:   with lock: shared += 1
来源：http://dali.dianchejie.cn/Article/details/gtewfjekuh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cashguo.top/Article/details/gtxuzbsvcz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigfzy.top/Article/details/gthxbejfvw.html

TS:   // 同 JS
来源：http://dali.c1oappe.top/Article/details/gtyntyzmdh.html

Java: synchronized (this) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxsntoqe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gotoacloud.top/Article/details/gthwwatfyf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuetiantiany.cn/Article/details/gtjbxgqmkx.html

C#:   lock (gate) { shared++; }
来源：http://dali.redwolf501.top/Article/details/gtpjeacfqr.html

[O04] 定义异步函数并等待
来源：http://dali.daria6918.cn/Article/details/gtdwygnvet.html

Py:   async def f():⏎    await g()
来源：http://dali.jyoumei.cn/Article/details/gtveqtbuib.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dashuyun.cn/Article/details/gtozdunzdh.html

JS:   async function f() { await g(); }
来源：http://dali.wangdashe.top/Article/details/gttcuvrgzq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gtvxsmczkh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.haohaochexian.top/Article/details/gtsfbjutwd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shuidangran.top/Article/details/gtrznuycja.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jlsjyb.cn/Article/details/gtmdstjsir.html

C#:   async Task F() { await G(); }
来源：http://dali.wangdashe.top/Article/details/gtqxxqxdvn.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhengqikj.top/Article/details/gtnrfrzize.html

Py:   asyncio.gather(*tasks)
来源：http://dali.c1oappe.top/Article/details/gtmsjfdrjb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ydzc1.top/Article/details/gtwouldwoj.html

JS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gtmybzfcuh.html

TS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gtxjlscils.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cashguo.top/Article/details/gtxmtmioar.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ppjwa.cn/Article/details/gtjytzrwfn.html

Ruby: threads.map(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbkzvkbs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.mhx1999.top/Article/details/gtqtuqeqjl.html

[O06] 使用进程池
来源：http://dali.gaohongyu789.top/Article/details/gtjybddajv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sysykeji.top/Article/details/gttrshwyek.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ehwqpu.com/Article/details/gtwrjqxcxm.html

JS:   // child_process / cluster 模块
来源：http://dali.hnqzz.top/Article/details/gtdnfygkkp.html

TS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gtayyexcdf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.haohaochexian.top/Article/details/gtqbzcbjqg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sweek.top/Article/details/gtoagcsstv.html

Ruby: // fork 块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtliykodog.html

C#:   Parallel.For
来源：http://dali.hongshengwenyu.top/Article/details/gtysowbyyp.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtqccrkuxb.html

P. 常用工具函数
来源：http://dali.xinyue.icu/Article/details/gtmsbmfjoy.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtememxvkm.html

[P01] 生成 UUID
来源：http://dali.jqgufenzy.top/Article/details/gtcgvplhkv.html

Py:   str(uuid.uuid4())
来源：http://dali.shuidangran.top/Article/details/gthgjojieb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sufxvd.cn/Article/details/gtlhvnzchi.html

JS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gtrkofkcis.html

TS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtsneievrb.html

Java: UUID.randomUUID().toString()
来源：http://dali.9152youxi.cn/Article/details/gtgaegudzi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jiagoushi.top/Article/details/gtjywayqna.html

Ruby: SecureRandom.uuid
来源：http://dali.316326.xyz/Article/details/gtzkwkrdko.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tanke756.top/Article/details/gthjqpogvh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258.top/Article/details/gtzfzibxwe.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hywenlv.cn/Article/details/gtvzomnagc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtzpyuvsfr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenjidiqi.icu/Article/details/gthpyldpgo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnqzz.top/Article/details/gtxdgxsvtl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cdnleiting.top/Article/details/gthjwysrvi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.svipenyu.cn/Article/details/gtwmvlzwaz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ybcxt.top/Article/details/gttxvxvngh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jyoumei.cn/Article/details/gtcbrfuscb.html

[P03] 生成短随机字符串
来源：http://dali.sxryk.cn/Article/details/gtvbajmhqv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hywenlv.cn/Article/details/gtfzyptnku.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sysykeji.top/Article/details/gtbzbftghs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gtangjlcqr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gtyuzciaag.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daxiang520.top/Article/details/gtkurbbous.html


<!-- 参考信息 -->