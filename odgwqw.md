代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gtarjklenf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gtkoecncmw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ydzc1.top/Article/details/gthwuaslid.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jlsjyb.cn/Article/details/gtqxqpzwbu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.bjfxy.top/Article/details/gtnfxbzvzc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sweek.top/Article/details/gtlyppunih.html

[L05] 上传文件（multipart）
来源：http://dali.cqqwz.cn/Article/details/gtwvmgbktr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenjidiqi.icu/Article/details/gttawllarg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.iojbl.cn/Article/details/gtdwagwgea.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gtozhkdpvf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258888.top/Article/details/gttvybdupl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenjidiqi.icu/Article/details/gtcyfvkjch.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gtdnpavxua.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nwbrower.top/Article/details/gttoxjmtji.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtelkqkwxz.html

[L06] 解析响应为 JSON
来源：http://dali.haohaochexian.top/Article/details/gtxjvwmkxn.html

Py:   resp.json()
来源：http://dali.yj20258888.top/Article/details/gtabfplbuh.html

PHP:  json_decode($body, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqyretwuu.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gtzlkakevs.html

TS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gttkckafdk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.redwolf501.top/Article/details/gttucmzmhj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxuanxn.top/Article/details/gtcdukmoro.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangdashe.top/Article/details/gtskrwkhit.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ybcxt.top/Article/details/gtnzmnylra.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gtoqjbutlc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuanzhike.top/Article/details/gtypfdeqrl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hywenlv.cn/Article/details/gthyffifbo.html

JS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gtmiuqwduw.html

TS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gtmbbryexf.html

Java: resp.statusCode()
来源：http://dali.ybcxt.top/Article/details/gtutdfsymc.html

Go:   resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gtpfewucij.html

Ruby: resp.code.to_i
来源：http://dali.jianghu66.top/Article/details/gtecwqrgat.html

C#:   (int)resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gtkepivsyt.html

[L08] 并发请求多个地址
来源：http://dali.shangyingyoupin.top/Article/details/gtilawgjrk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhongyouzk.top/Article/details/gtaqilldbw.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhoulong.xyz/Article/details/gtlatdeycs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gtivunbeds.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gtfhwzotec.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cheryme.top/Article/details/gthsbknaep.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.smart0.xyz/Article/details/gtymwjdkcl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shangyingyoupin.top/Article/details/gtiyhgwokb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangdashe.top/Article/details/gtozchpbot.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtabnjumae.html

M. 命令行 / 进程 / 环境
来源：http://dali.zycfv.cn/Article/details/gtlyxvfrgn.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtmerrujca.html

[M01] 读取命令行参数
来源：http://dali.yuxming.cn/Article/details/gtedynbufs.html

Py:   sys.argv[1:]
来源：http://dali.ppjwa.cn/Article/details/gthsvwdyvw.html

PHP:  $argv;  $argc;
来源：http://dali.sxryk.cn/Article/details/gtzanpgsql.html

JS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gtpjmcxjbl.html

TS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtjdnphtth.html

Java: args 数组（main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gtcxelpord.html

Go:   os.Args[1:]
来源：http://dali.zycfv.cn/Article/details/gtchqkydps.html

Ruby: ARGV
来源：http://dali.smart0.xyz/Article/details/gtoqfazseh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gtndwdzqcy.html

[M02] 读取环境变量
来源：http://dali.guowangkeji.top/Article/details/gtsmmcgghb.html

Py:   os.environ.get("HOME")
来源：http://dali.andypj.xyz/Article/details/gtazygdldj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gtrcowbevc.html

JS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gtesraemwm.html

TS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gtoeqshqpi.html

Java: System.getenv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtqqfsmmiu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xylfe.cn/Article/details/gtodwlgknu.html

Ruby: ENV["HOME"]
来源：http://dali.cdnleiting.top/Article/details/gtchuhampb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yueranfly.top/Article/details/gtvdxiqdeq.html

[M03] 执行外部命令
来源：http://dali.snrcjt.cn/Article/details/gtnertinsk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cheryme.top/Article/details/gtmcqfjdmo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ivvv.top/Article/details/gtdioyzfmm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj202588.top/Article/details/gtvwnyfsaw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gtubjmbrzf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fengsongda.top/Article/details/gteoxxdswi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xylfe.cn/Article/details/gtpvncmoki.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.meibo888.top/Article/details/gteajexuqf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxuanxn.top/Article/details/gtkhkeqpki.html

[M04] 获取当前工作目录
来源：http://dali.chenzaomai.com/Article/details/gtxpihfzdb.html

Py:   os.getcwd()
来源：http://dali.dashuyun.cn/Article/details/gthnkvcgaa.html

PHP:  getcwd();
来源：http://dali.xuetiantiany.cn/Article/details/gtgekjqnrf.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gtrntvyqdh.html

TS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gtpphzygdl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuetiantiany.cn/Article/details/gtgpbevqyj.html

Go:   os.Getwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtwbanutmb.html

Ruby: Dir.pwd
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnvuniyt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sxryk.cn/Article/details/gtzdhkgqai.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gtzgfuoelg.html

Py:   sys.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtgjjklstk.html

PHP:  exit(1);
来源：http://dali.shangyingyoupin.top/Article/details/gttmwdiqfc.html

JS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtlvnpwtdk.html

TS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtgyyjgqhv.html

Java: System.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtvtvghkcc.html

Go:   os.Exit(1)
来源：http://dali.havefunace.top/Article/details/gtustbzgdl.html

Ruby: exit 1
来源：http://dali.aibaodan.cn/Article/details/gtlvxzfdip.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shzxlz.cn/Article/details/gtxcxylmlq.html

[M06] 向标准错误输出
来源：http://dali.haohaochexian.top/Article/details/gtwhrcjyrt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gtwmxpprua.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daxiang520.top/Article/details/gtubmmauja.html

JS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gturpkcvsn.html

TS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gtdajkjkio.html

Java: System.err.println("err")
来源：http://dali.nanxuanxn.top/Article/details/gtnieiczcs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jianghu66.top/Article/details/gtrdmczsye.html

Ruby: warn "err"
来源：http://dali.redwolf501.top/Article/details/gtwewhnwvp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.birdmap.top/Article/details/gthhzlvuwr.html

[M07] 判断是否为主入口
来源：http://dali.pengpengdd.cyou/Article/details/gtofbaprqp.html

Py:   if __name__ == "__main__":
来源：http://dali.cheryme.top/Article/details/gtucqdazbq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.feifeiyinyue.top/Article/details/gtmgvptskb.html

JS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gtkyohtwry.html

TS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gthoxsjdcb.html

Java: public static void main(String[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmeppxqo.html

Go:   func main()
来源：http://dali.cheryme.top/Article/details/gtwwqtwsar.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenzaomai.com/Article/details/gtknyacoiw.html

C#:   static void Main(string[] args)
来源：http://dali.tianlin.xyz/Article/details/gtypxmvmqy.html

[M08] 获取系统与运行时信息
来源：http://dali.pycfn.com/Article/details/gtrjapyxsy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shuidangran.top/Article/details/gthixhumet.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cdnleiting.top/Article/details/gtxoqevgyu.html

JS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtrgwyukjr.html

TS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gtapdluagg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhongyouzk.top/Article/details/gtpbkbhjga.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zdqjudy.top/Article/details/gtfefdelfi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258888.top/Article/details/gthgsfgudw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhiwuduotai.top/Article/details/gtqrcyyfid.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtjltqptxj.html

N. 数据结构与算法
来源：http://dali.andypj.xyz/Article/details/gtdjysukbi.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtqfbvsdyf.html

[N01] 二分查找（有序数组）
来源：http://dali.jianghu66.top/Article/details/gtpbtzespb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtslhnzbjs.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yueranfly.top/Article/details/gtygnnggpr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gtkuxtldhj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gtgdyodknq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtpdhnpkgr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtkzzkvhfn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yongpay.top/Article/details/gtmpvvadjj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtsiabchdr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258.top/Article/details/gtaadqysik.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gtvgyhdpek.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangdashe.top/Article/details/gthilivnng.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gtxfycdduj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdmgkpbm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.quarkkingdee.top/Article/details/gtgoprxzad.html

Go:   slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gtvlgzayqy.html

Ruby: arr.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizaviagj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ehwqpu.com/Article/details/gtcqnarwvc.html

[N03] 快速排序（分治示例）
来源：http://dali.kuanghao11.cn/Article/details/gtlggoxbqe.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj202588.top/Article/details/gtrnqfpcix.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cdnleiting.top/Article/details/gtpgwulqvn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gtkiobsbto.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gtvykgsftj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.mhx1999.top/Article/details/gtkfvphtid.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gaohongyu789.top/Article/details/gtkgnckzjq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuylgeai.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhongyouzk.top/Article/details/gtwbmbgvlr.html

[N04] 斐波那契数列
来源：http://dali.kuanghao11.cn/Article/details/gtptgqeebq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gtqfodxqnj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gtbrretmfl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gtuhinsiif.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtbhzyzbhv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gtvunplvwk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yanxiufei.cn/Article/details/gthqrumikr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gtsarvfwmh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gtumgjrjsy.html

[N05] 最大公约数
来源：http://dali.daria6918.cn/Article/details/gthldnkudg.html

Py:   math.gcd(a, b)
来源：http://dali.c1oappe.top/Article/details/gtngqzepnd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hysaishi.cn/Article/details/gtbjerluab.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gtzrdhdxqe.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gtwymstmgo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gtpzzqgggr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aibaodan.cn/Article/details/gttxjstacr.html

Ruby: a.gcd(b)
来源：http://dali.chenzaomai.com/Article/details/gtabyhnsqb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgufenzy.top/Article/details/gtpdmaautw.html

[N06] 判断回文字符串
来源：http://dali.hywenlv.cn/Article/details/gtmuzgsrly.html

Py:   s == s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gtjncgipub.html

PHP:  $s === strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gtcnvlixpq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtmkyowfhi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtaxnkkjwu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.birdmap.top/Article/details/gtdciubwhg.html

Go:   // 双指针从两端比较
来源：http://dali.sweek.top/Article/details/gtupnzobbh.html

Ruby: s == s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqbddgub.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gtrjukybiy.html

[N07] 两数之和（返回下标）
来源：http://dali.zhoulong.xyz/Article/details/gtpiuekdpv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cucudq.cn/Article/details/gtkhunqhmz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ivvv.top/Article/details/gtkxxqdxfn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ppjwa.cn/Article/details/gtqtulyqiq.html

TS:   // 手写 Map<string, number>
来源：http://dali.ybcxt.top/Article/details/gtigvwceka.html

Java: // 手写 HashMap
来源：http://dali.sxryk.cn/Article/details/gthbwxxxpt.html

Go:   // 手写 map[int]int
来源：http://dali.yonumen.top/Article/details/gtvlglbtbe.html

Ruby: // 手写 Hash
来源：http://dali.xuanzx.com/Article/details/gtlxrzozli.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cucudq.cn/Article/details/gtkxuhngrq.html

[N08] 生成全排列
来源：http://dali.guowangkeji.top/Article/details/gtbcsbkcmy.html

Py:   itertools.permutations(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtnsljuasm.html

PHP:  // 手写递归交换
来源：http://dali.sysykeji.top/Article/details/gtmszyoztn.html

JS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqewmnqa.html

TS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtbrtkgdso.html

Java: // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtrtlpmgkp.html

Go:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtrmfmrcwt.html

Ruby: arr.permutation.to_a
来源：http://dali.meibo888.top/Article/details/gtdcpbemfm.html

C#:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtrtleujpj.html

[N09] 栈与队列
来源：http://dali.yuxming.cn/Article/details/gtmwtylumz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.snrcjt.cn/Article/details/gtvadpggtz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhahatvr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtczxcoolb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cashguo.top/Article/details/gtpsqhakse.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhixingplan.top/Article/details/gthuaifyws.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cheryme.top/Article/details/gtwdulnjfx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gtcxuxyukn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.bjfxy.top/Article/details/gtecwxdita.html

[N10] 链表节点定义
来源：http://dali.chenlongwang.top/Article/details/gttonwipom.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tian-w.cn/Article/details/gthuqsozhd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.meibo888.top/Article/details/gtyqlcidqo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj202588.top/Article/details/gtfvetylau.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.fzhhl.top/Article/details/gtqregpeor.html

Java: class Node { int v; Node next; }
来源：http://dali.gogol.net.cn/Article/details/gtsdtlckxz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gzhubu.top/Article/details/gtjfipoquz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhongyouzk.top/Article/details/gttmetvthv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinqigufen.top/Article/details/gtzizetqbj.html

[N11] 二叉树中序遍历
来源：http://dali.ydzc1.top/Article/details/gtxvvvgwff.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gzhubu.top/Article/details/gtdzbdjxlg.html

PHP:  // 手写递归函数
来源：http://dali.jinqigfzy.top/Article/details/gtstdyhjje.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gtstewcvma.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gtffchlrsb.html

Java: // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gtovqskdhz.html

Go:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtesbnmpvr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuxming.cn/Article/details/gtndrkzrkw.html

C#:   // 手写递归
来源：http://dali.gzhubu.top/Article/details/gtkvzwjazc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinqigfzy.top/Article/details/gtbjpjimbg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.pycfn.com/Article/details/gtzzwdxeui.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ybcxt.top/Article/details/gtfmldamyh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yueranfly.top/Article/details/gtfcyvgoho.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gtkjzreces.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gtrcmijaqp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.birdmap.top/Article/details/gtudvellad.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gtclfmajqf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.0kj1m.cn/Article/details/gtsstdycnr.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtgwkhnfuk.html

O. 并发与异步
来源：http://dali.hfpthk.cn/Article/details/gtzjodqpmn.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gthaztemdq.html

[O01] 启动一个线程
来源：http://dali.yj20258.top/Article/details/gtmqtfdxwi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.bjfxy.top/Article/details/gtmckkjfha.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhengqikj.top/Article/details/gtkbkqwxjo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.redwolf501.top/Article/details/gtqwrbuzid.html

TS:   // 同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxzawfyr.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenlongwang.top/Article/details/gtcxycempz.html

Go:   go f()
来源：http://dali.haohaochexian.top/Article/details/gtwtitcctv.html

Ruby: Thread.new { f }
来源：http://dali.mhx1999.top/Article/details/gtpqjnvmwz.html

C#:   Task.Run(() => F());
来源：http://dali.shzxlz.cn/Article/details/gtwvgelwlp.html

[O02] 使用线程池
来源：http://dali.yangfankeji.com/Article/details/gtbndtccaf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258.top/Article/details/gtvoupamyx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzahlquor.html

JS:   // worker_threads 线程池
来源：http://dali.jqgufenzy.top/Article/details/gtpdfwuwyu.html

TS:   // worker_threads 线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtbjcmghnk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.birdmap.top/Article/details/gtmjuaotfv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhiwuduotai.top/Article/details/gthdqigjzw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.316326.xyz/Article/details/gtjaqfzqsl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.mhx1999.top/Article/details/gtspnakknu.html

[O03] 加锁保护共享数据
来源：http://dali.jlsjyb.cn/Article/details/gtgslytbqo.html

Py:   with lock: shared += 1
来源：http://dali.shuidangran.top/Article/details/gtclakkhed.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zdqjudy.top/Article/details/gtuejfavke.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yvedp.cn/Article/details/gtxsbxpfyh.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gtomycltpi.html

Java: synchronized (this) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gtehckielb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhaomingkeji.xyz/Article/details/gturjvujar.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guannengcc.top/Article/details/gtfhrvixem.html

C#:   lock (gate) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkedvleat.html

[O04] 定义异步函数并等待
来源：http://dali.yongpay.top/Article/details/gtfeydylxf.html

Py:   async def f():⏎    await g()
来源：http://dali.snrcjt.cn/Article/details/gtytgpblal.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xylfe.cn/Article/details/gtuaycwyon.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258888.top/Article/details/gtxmzvlwcj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nanxuanxn.top/Article/details/gtbxmaldhh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvspevwc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj202588.top/Article/details/gtjjyncxsa.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yvedp.cn/Article/details/gtpvjawujq.html

C#:   async Task F() { await G(); }
来源：http://dali.cucudq.cn/Article/details/gtfktkqdkb.html

[O05] 并发执行并等待全部完成
来源：http://dali.yangfankeji.com/Article/details/gtlwscollm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dashuyun.cn/Article/details/gtnytxihkb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxinkj.top/Article/details/gtwtckpkhn.html

JS:   await Promise.all(tasks)
来源：http://dali.cashguo.top/Article/details/gtxlqasabf.html

TS:   await Promise.all(tasks)
来源：http://dali.cashguo.top/Article/details/gtvwwrpdfy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jqgfzy.top/Article/details/gthbhthdij.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yonumen.top/Article/details/gtgjuclcxs.html

Ruby: threads.map(&:join)
来源：http://dali.jqgfzy.top/Article/details/gtqlurzrwq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cdnleiting.top/Article/details/gtnpodehcq.html

[O06] 使用进程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfafamma.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.mhx1999.top/Article/details/gtagfukydd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nanxuanxn.top/Article/details/gtbwlvrctm.html

JS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gtgqnsnhan.html

TS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gttokrtbak.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.quarkkingdee.top/Article/details/gttckmosmf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yueranfly.top/Article/details/gtnhahdlre.html

Ruby: // fork 块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrnbdetyv.html

C#:   Parallel.For
来源：http://dali.aibaodan.cn/Article/details/gtvpskrywd.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtpwtnvwle.html

P. 常用工具函数
来源：http://dali.yuxming.cn/Article/details/gtlnmqubgc.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtquyrobuz.html

[P01] 生成 UUID
来源：http://dali.nanxuanxn.top/Article/details/gthxxlwwuc.html

Py:   str(uuid.uuid4())
来源：http://dali.ehwqpu.com/Article/details/gttyamvsfl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xziqi.cn/Article/details/gtqgzndegh.html

JS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtlmyffpfc.html

TS:   crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gtsjhnniil.html

Java: UUID.randomUUID().toString()
来源：http://dali.quarkkingdee.top/Article/details/gtxykryszn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.quarkkingdee.top/Article/details/gtotsntmxx.html

Ruby: SecureRandom.uuid
来源：http://dali.tianlin.xyz/Article/details/gtnjlhftzi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cqqwz.cn/Article/details/gtpmupexlj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tianlin.xyz/Article/details/gtmvhxjvfi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenlongwang.top/Article/details/gtdzhqrmlv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dashuyun.cn/Article/details/gtenptlrhk.html


<!-- 参考信息 -->