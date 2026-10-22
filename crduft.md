代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gt2dpegolwt.html

[L04] 设置超时
来源：http://dali.dianchejie.cn/Article/details/gt2vtyhzswr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jykwxtgv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shzxlz.cn/Article/details/gt2auzmlueh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gt2uwdvgqbr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gt2ifcylbzy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nwbrower.top/Article/details/gt2eenzrnaz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhoulong.xyz/Article/details/gt2yaimetis.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tvcvzthg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fengsongda.top/Article/details/gt2zfoxgomc.html

[L05] 上传文件（multipart）
来源：http://dali.yueranfly.top/Article/details/gt2nqqjxxdu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnxiangtu.top/Article/details/gt2qcpxnikj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guowangkeji.top/Article/details/gt2lxhfcivr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2vtudkgha.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.0kj1m.cn/Article/details/gt2cbyoppwz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnqzz.top/Article/details/gt2vtwtmnse.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sysykeji.top/Article/details/gt2xacrwbtp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hfpthk.cn/Article/details/gt2uvbcukbt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ivvv.top/Article/details/gt2rmkogams.html

[L06] 解析响应为 JSON
来源：http://dali.ybcxt.top/Article/details/gt2vbtsggmo.html

Py:   resp.json()
来源：http://dali.chenzaomai.com/Article/details/gt2yagcieac.html

PHP:  json_decode($body, true);
来源：http://dali.jyoumei.cn/Article/details/gt2idhpdmad.html

JS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gt2vmckyhnx.html

TS:   await resp.json()
来源：http://dali.zdqjudy.top/Article/details/gt2vzifefhj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dqdpftvc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qdhsurct.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuetiantiany.cn/Article/details/gt2admvfaif.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cheryme.top/Article/details/gt2xrnsaqdd.html

[L07] 处理 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gt2bucujcag.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.aizwys.cn/Article/details/gt2evihsgvw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nwbrower.top/Article/details/gt2kevgtytl.html

JS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gt2gtyeyvbl.html

TS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gt2xenaozpv.html

Java: resp.statusCode()
来源：http://dali.haohaochexian.top/Article/details/gt2zrngtnxi.html

Go:   resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ucrntcdt.html

Ruby: resp.code.to_i
来源：http://dali.cucudq.cn/Article/details/gt2sbqsnspr.html

C#:   (int)resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gt2jdtuekvm.html

[L08] 并发请求多个地址
来源：http://dali.daria6918.cn/Article/details/gt2fqxqbmrg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinqigfzy.top/Article/details/gt2ntzvbcfx.html

PHP:  curl_multi_init() 系列
来源：http://dali.tianlin.xyz/Article/details/gt2ljabmnty.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gt2uwhbmcrh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gt2nehthzoc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shzxlz.cn/Article/details/gt2hbddqicm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.haohaochexian.top/Article/details/gt2ewzkvevg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jyoumei.cn/Article/details/gt2euajbuxy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yueranfly.top/Article/details/gt2pultfxcn.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2raoaixdx.html

M. 命令行 / 进程 / 环境
来源：http://dali.yanxiufei.cn/Article/details/gt2oeaxvyxw.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2nnvknscp.html

[M01] 读取命令行参数
来源：http://dali.yj20258888.top/Article/details/gt2raasrznu.html

Py:   sys.argv[1:]
来源：http://dali.cqqwz.cn/Article/details/gt2pbjqwkrf.html

PHP:  $argv;  $argc;
来源：http://dali.ivvv.top/Article/details/gt2dejyvrdw.html

JS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gt2xfxbnbjd.html

TS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gt2kuzkafsj.html

Java: args 数组（main 方法参数）
来源：http://dali.zhiwuduotai.top/Article/details/gt2aekgwpvq.html

Go:   os.Args[1:]
来源：http://dali.aibaodan.cn/Article/details/gt2llqmwnhq.html

Ruby: ARGV
来源：http://dali.dashuyun.cn/Article/details/gt2kphbqykj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gt2gvmbwxyv.html

[M02] 读取环境变量
来源：http://dali.fzhhl.top/Article/details/gt2frqertsb.html

Py:   os.environ.get("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gt2rpcbixpu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gt2inngwqzj.html

JS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gt2jjsarldj.html

TS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gt2bezlsdmj.html

Java: System.getenv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gt2telsowzv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oalunojo.html

Ruby: ENV["HOME"]
来源：http://dali.bjfxy.top/Article/details/gt2zikhxmvp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hdhbhkat.html

[M03] 执行外部命令
来源：http://dali.hnxiangtu.top/Article/details/gt2ggwczspo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cqqwz.cn/Article/details/gt2gmiixztd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cdnleiting.top/Article/details/gt2hiwpndua.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.9152youxi.cn/Article/details/gt2fxffooct.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gt2xszedtvl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gaohongyu789.top/Article/details/gt2lghddocf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuxming.cn/Article/details/gt2ahsfhhrv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pengpengdd.cyou/Article/details/gt2qoetrmjr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbehrey.html

[M04] 获取当前工作目录
来源：http://dali.c1oappe.top/Article/details/gt2tuububej.html

Py:   os.getcwd()
来源：http://dali.aibaodan.cn/Article/details/gt2xwewjzns.html

PHP:  getcwd();
来源：http://dali.hnxiangtu.top/Article/details/gt2kdsckndx.html

JS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gt2kvqtsmpg.html

TS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gt2cfxbexnd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pycfn.com/Article/details/gt2bekxtyyc.html

Go:   os.Getwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dmxukdvw.html

Ruby: Dir.pwd
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bmtqeijp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yonumen.top/Article/details/gt2anaqpqzo.html

[M05] 设置退出码
来源：http://dali.tanke756.top/Article/details/gt2fhgaykjc.html

Py:   sys.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2thicacar.html

PHP:  exit(1);
来源：http://dali.sweek.top/Article/details/gt2hmjbzztf.html

JS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2znuifirw.html

TS:   process.exit(1)
来源：http://dali.316326.xyz/Article/details/gt2tnsetjej.html

Java: System.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gt2ijbmuabd.html

Go:   os.Exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2ftenxubd.html

Ruby: exit 1
来源：http://dali.jqgfzy.top/Article/details/gt2kmsqhhmw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhoulong.xyz/Article/details/gt2pmzfmjzn.html

[M06] 向标准错误输出
来源：http://dali.jqgufenzy.top/Article/details/gt2oiexptxa.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhengqikj.top/Article/details/gt2ggjzfeyn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dfzlazly.html

JS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gt2cradtzry.html

TS:   console.error("err")
来源：http://dali.nwbrower.top/Article/details/gt2fomyaqbk.html

Java: System.err.println("err")
来源：http://dali.andypj.xyz/Article/details/gt2xscvqmnc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxuanxn.top/Article/details/gt2bgsolsyx.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gt2ycwbjsae.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.svipenyu.cn/Article/details/gt2xxwzutzd.html

[M07] 判断是否为主入口
来源：http://dali.zycfv.cn/Article/details/gt2hilrlrxf.html

Py:   if __name__ == "__main__":
来源：http://dali.zhiwuduotai.top/Article/details/gt2drzhuusm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuanzx.com/Article/details/gt2yvpjsmqx.html

JS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gt2rfzvgbbh.html

TS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gt2cauzbkkd.html

Java: public static void main(String[] args)
来源：http://dali.jinqigfzy.top/Article/details/gt2yzvuadvr.html

Go:   func main()
来源：http://dali.tanke756.top/Article/details/gt2pqqahppn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xziqi.cn/Article/details/gt2qalgdrws.html

C#:   static void Main(string[] args)
来源：http://dali.cheryme.top/Article/details/gt2jwjluatl.html

[M08] 获取系统与运行时信息
来源：http://dali.pengpengdd.cyou/Article/details/gt2srgahmgr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.kuanghao11.cn/Article/details/gt2xtxweywf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jyoumei.cn/Article/details/gt2bqzhghwq.html

JS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gt2lbxttldf.html

TS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gt2vksfrnic.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pengpengdd.cyou/Article/details/gt2iwmmvnvf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ppjwa.cn/Article/details/gt2dhjctsvy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gzhubu.top/Article/details/gt2xiiisxji.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxuanxn.top/Article/details/gt2dclqotvq.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2hatdybjt.html

N. 数据结构与算法
来源：http://dali.jlsjyb.cn/Article/details/gt2txouinbx.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2ekqavaey.html

[N01] 二分查找（有序数组）
来源：http://dali.andypj.xyz/Article/details/gt2eummcebm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2clksdwde.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gzhubu.top/Article/details/gt2xbblbpel.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gt2oxqudnia.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wwldrmha.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2oupyzpcq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2tsuvvqbl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.pengpengdd.cyou/Article/details/gt2usnubyum.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gt2umoyjmrm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hysaishi.cn/Article/details/gt2auvxyvwq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yueranfly.top/Article/details/gt2ixnophgi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cashguo.top/Article/details/gt2nhxzpvzf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gt2wnnylcnk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gt2bsiiesuf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.bjfxy.top/Article/details/gt2mojlbtwr.html

Go:   slices.Sort(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2npetsmtp.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gt2sxyuuqme.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.pengpengdd.cyou/Article/details/gt2wtjnyoyl.html

[N03] 快速排序（分治示例）
来源：http://dali.redwolf501.top/Article/details/gt2gxlxucaf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuetiantiany.cn/Article/details/gt2lqwuskvy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhiwuduotai.top/Article/details/gt2nulvubxm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ofsjnuto.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gt2qburxcwx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gzhubu.top/Article/details/gt2ckdfgzlc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daxiang520.top/Article/details/gt2yszkxjhi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sufxvd.cn/Article/details/gt2kxolayof.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigufen.top/Article/details/gt2pggagbtg.html

[N04] 斐波那契数列
来源：http://dali.chenlongwang.top/Article/details/gt2ypouaixw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daxiang520.top/Article/details/gt2lxgfeonu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fengsongda.top/Article/details/gt2zegjqabi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2zvfqhspi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2pamxggjj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.c1oappe.top/Article/details/gt2tqzvqbdd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bgapgigk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gt2avmyueey.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gt2cvubfjjh.html

[N05] 最大公约数
来源：http://dali.smart0.xyz/Article/details/gt2hxcgskpi.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sdfmtgus.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuanzhike.top/Article/details/gt2blayjeuv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fnnadqcz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gt2lfgscugb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dashuyun.cn/Article/details/gt2huuhznbn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pptztwup.html

Ruby: a.gcd(b)
来源：http://dali.yangfankeji.com/Article/details/gt2oahfvnrt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.haohaochexian.top/Article/details/gt2mfbakkxy.html

[N06] 判断回文字符串
来源：http://dali.birdmap.top/Article/details/gt2qcwopalz.html

Py:   s == s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gt2qzrhbtdv.html

PHP:  $s === strrev($s);
来源：http://dali.cashguo.top/Article/details/gt2dboilwjh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gt2hwjcwqgz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2ivyvwrzz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnqzz.top/Article/details/gt2yhzkshsv.html

Go:   // 双指针从两端比较
来源：http://dali.cashguo.top/Article/details/gt2tjxqqwqt.html

Ruby: s == s.reverse
来源：http://dali.yangfankeji.com/Article/details/gt2mpljqckc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.dianchejie.cn/Article/details/gt2swimokzs.html

[N07] 两数之和（返回下标）
来源：http://dali.hammf.cn/Article/details/gt2psafylqk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ybcxt.top/Article/details/gt2tlobvibi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.havefunace.top/Article/details/gt2owlqgvxr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yongpay.top/Article/details/gt2sxjtjxya.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenzaomai.com/Article/details/gt2xrbxayyw.html

Java: // 手写 HashMap
来源：http://dali.sysykeji.top/Article/details/gt2mlaxkjir.html

Go:   // 手写 map[int]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vxagqzho.html

Ruby: // 手写 Hash
来源：http://dali.zhiwuduotai.top/Article/details/gt2etycpqzm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zdqjudy.top/Article/details/gt2ktvvcgtd.html

[N08] 生成全排列
来源：http://dali.ivvv.top/Article/details/gt2yjtgddnh.html

Py:   itertools.permutations(arr)
来源：http://dali.havefunace.top/Article/details/gt2jrxnmihm.html

PHP:  // 手写递归交换
来源：http://dali.vqdsnc.cn/Article/details/gt2ermddwbv.html

JS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gt2odrrcgxl.html

TS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gt2efvuxpqo.html

Java: // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gt2yqfennbs.html

Go:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gt2lnhrvsag.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigfzy.top/Article/details/gt2psglobpv.html

C#:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2smgrjfyk.html

[N09] 栈与队列
来源：http://dali.nanxinkj.top/Article/details/gt2aubwlkqx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fzhhl.top/Article/details/gt2qhjwqygy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yvedp.cn/Article/details/gt2zgktexyv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gt2twtghuom.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.pycfn.com/Article/details/gt2yfzlsunr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eyzlzefz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jyoumei.cn/Article/details/gt2xcexfvvk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gt2fjowaace.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wixbpquj.html

[N10] 链表节点定义
来源：http://dali.9152youxi.cn/Article/details/gt2ycjoytxp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhongyouzk.top/Article/details/gt2tfvjtalf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yangfankeji.com/Article/details/gt2yzrchpvq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tanke756.top/Article/details/gt2nzpdavsc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuanzx.com/Article/details/gt2uhcwwxjs.html

Java: class Node { int v; Node next; }
来源：http://dali.shuidangran.top/Article/details/gt2afsiosbg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jiagoushi.top/Article/details/gt2txqfgksz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jlsjyb.cn/Article/details/gt2qzduduij.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.wangdashe.top/Article/details/gt2wlgpkqxc.html

[N11] 二叉树中序遍历
来源：http://dali.ybcxt.top/Article/details/gt2rmlblbfg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hysaishi.cn/Article/details/gt2uhsrgllq.html

PHP:  // 手写递归函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pwfoorce.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shuidangran.top/Article/details/gt2gbsbdxtj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangshuangyany.cn/Article/details/gt2pohfnspa.html

Java: // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gt2qqceylic.html

Go:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gt2xcgrpaid.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yueranfly.top/Article/details/gt2uwzevxpc.html

C#:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gt2fnchyaww.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.feifeiyinyue.top/Article/details/gt2ncvrckbk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xylfe.cn/Article/details/gt2addpahez.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shangyingyoupin.top/Article/details/gt2izayllet.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gt2kfbespes.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhengqikj.top/Article/details/gt2rucfwknt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gt2ybiqcimb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxuanxn.top/Article/details/gt2kdprobbf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sweek.top/Article/details/gt2xrhotkpt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gt2dfkmtyvr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2bqtumhzf.html

O. 并发与异步
来源：http://dali.shuidangran.top/Article/details/gt2ydligeca.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2rnccakzb.html

[O01] 启动一个线程
来源：http://dali.shuidangran.top/Article/details/gt2pepwgrpe.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tian-w.cn/Article/details/gt2mihstgfx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guowangkeji.top/Article/details/gt2nertpboi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.mhx1999.top/Article/details/gt2btalehgh.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gt2kmexosnq.html

Java: new Thread(() -> f()).start()
来源：http://dali.feifeiyinyue.top/Article/details/gt2mtacrhgs.html

Go:   go f()
来源：http://dali.jqgufenzy.top/Article/details/gt2ceabfzru.html

Ruby: Thread.new { f }
来源：http://dali.svipenyu.cn/Article/details/gt2xoixmuir.html

C#:   Task.Run(() => F());
来源：http://dali.feifeiyinyue.top/Article/details/gt2whqnktel.html

[O02] 使用线程池
来源：http://dali.haohaochexian.top/Article/details/gt2zhqvzgih.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nwbrower.top/Article/details/gt2wghufdqw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.0kj1m.cn/Article/details/gt2wzyhabic.html

JS:   // worker_threads 线程池
来源：http://dali.vqdsnc.cn/Article/details/gt2ccokyumc.html

TS:   // worker_threads 线程池
来源：http://dali.cashguo.top/Article/details/gt2dfynprbv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guannengcc.top/Article/details/gt2dpdqmsdd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rmpqosjo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yiksfkbt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhongyouzk.top/Article/details/gt2askxkcqe.html

[O03] 加锁保护共享数据
来源：http://dali.gotoacloud.top/Article/details/gt2rvtlvblw.html

Py:   with lock: shared += 1
来源：http://dali.jqgufenzy.top/Article/details/gt2mrypzrwe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.c1oappe.top/Article/details/gt2goyrdrix.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gogol.net.cn/Article/details/gt2cbrfeext.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gt2eakxfraj.html

Java: synchronized (this) { shared++; }
来源：http://dali.hfpthk.cn/Article/details/gt2svlvkjwb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yonumen.top/Article/details/gt2roydnqsf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sweek.top/Article/details/gt2xqxoibzm.html

C#:   lock (gate) { shared++; }
来源：http://dali.birdmap.top/Article/details/gt2tjzlcxls.html

[O04] 定义异步函数并等待
来源：http://dali.dashuyun.cn/Article/details/gt2eycvofjo.html

Py:   async def f():⏎    await g()
来源：http://dali.ybcxt.top/Article/details/gt2qxlffldz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.fzhhl.top/Article/details/gt2wqvxpgzh.html

JS:   async function f() { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gt2jllmgrhi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnqzz.top/Article/details/gt2rombwlzg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hnxiangtu.top/Article/details/gt2asspcgyf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2brkxhvvv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shzxlz.cn/Article/details/gt2ncpznrsu.html

C#:   async Task F() { await G(); }
来源：http://dali.daria6918.cn/Article/details/gt2plpppwtz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhongyouzk.top/Article/details/gt2zekjpiiq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nanxuanxn.top/Article/details/gt2jtrbxjwe.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pycfn.com/Article/details/gt2qrsizzdj.html

JS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gt2ofzabwjp.html

TS:   await Promise.all(tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nmvnrwsa.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.9152youxi.cn/Article/details/gt2clwcwsfe.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhiwuduotai.top/Article/details/gt2gpiftbmn.html

Ruby: threads.map(&:join)
来源：http://dali.zhixingplan.top/Article/details/gt2bzvewrli.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj202588.top/Article/details/gt2exfchqfr.html

[O06] 使用进程池
来源：http://dali.yj202588.top/Article/details/gt2ajfusqww.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sysykeji.top/Article/details/gt2wznppjmr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.quarkkingdee.top/Article/details/gt2lkjtwrap.html

JS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gt2nstbvpso.html

TS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pstwihji.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuanzx.com/Article/details/gt2zzyfongf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhixingplan.top/Article/details/gt2dbgjglef.html

Ruby: // fork 块
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zdgwbhrk.html

C#:   Parallel.For
来源：http://dali.pycfn.com/Article/details/gt2ugbmfkln.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2qwuvpkrd.html

P. 常用工具函数
来源：http://dali.jlsjyb.cn/Article/details/gt2ndfacoow.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2tydgfmcu.html

[P01] 生成 UUID
来源：http://dali.yj20258.top/Article/details/gt2hduuplzs.html

Py:   str(uuid.uuid4())
来源：http://dali.yuxming.cn/Article/details/gt2ybzlwvrh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.mhx1999.top/Article/details/gt2tewlpgzi.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qprxpvsu.html

TS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gt2faexavzt.html

Java: UUID.randomUUID().toString()
来源：http://dali.zycfv.cn/Article/details/gt2cnrixqnx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gzhubu.top/Article/details/gt2cenqbani.html

Ruby: SecureRandom.uuid
来源：http://dali.sysykeji.top/Article/details/gt2qrsoshwa.html


<!-- 参考信息 -->