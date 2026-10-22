代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gt2qeapfche.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2adfrjcyw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xziqi.cn/Article/details/gt2ojsczwhc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.316326.xyz/Article/details/gt2yznwbsud.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mjruzvfc.html

[L04] 设置超时
来源：http://dali.hysaishi.cn/Article/details/gt2pdsaihic.html

Py:   requests.get(url, timeout=5)
来源：http://dali.9152youxi.cn/Article/details/gt2sdowifrf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hfpthk.cn/Article/details/gt2ymsdtkbo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gt2hlgxbsnr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gt2czztisxt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gotoacloud.top/Article/details/gt2ezzdlmue.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cucudq.cn/Article/details/gt2dvugsvtd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jianghu66.top/Article/details/gt2twlhvdaw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhengqikj.top/Article/details/gt2ommubrcl.html

[L05] 上传文件（multipart）
来源：http://dali.jyoumei.cn/Article/details/gt2uqhqgmkp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fzhhl.top/Article/details/gt2tfmbptrr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cucudq.cn/Article/details/gt2qyiuntcb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gt2tvsydaiw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xylfe.cn/Article/details/gt2spaenpwp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sysykeji.top/Article/details/gt2wiycfkuc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aizwys.cn/Article/details/gt2qsgmsvxy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yueranfly.top/Article/details/gt2asfjbnbv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2spfakkcg.html

[L06] 解析响应为 JSON
来源：http://dali.pengpengdd.cyou/Article/details/gt2okncipsd.html

Py:   resp.json()
来源：http://dali.smart0.xyz/Article/details/gt2rkpswwyb.html

PHP:  json_decode($body, true);
来源：http://dali.zhengqikj.top/Article/details/gt2phmiehrc.html

JS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gt2myvdtttg.html

TS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gt2tvmpcfuo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qdrnqiwr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yonumen.top/Article/details/gt2oszsywsb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.havefunace.top/Article/details/gt2gudyhwgg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hywenlv.cn/Article/details/gt2nfobtclg.html

[L07] 处理 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gt2knctlwes.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.mhx1999.top/Article/details/gt2hrrguxfn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuxming.cn/Article/details/gt2huifovjy.html

JS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gt2ciqrdhzi.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gt2ceshhntb.html

Java: resp.statusCode()
来源：http://dali.316326.xyz/Article/details/gt2rzflsiqz.html

Go:   resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gt2tqftjfwy.html

Ruby: resp.code.to_i
来源：http://dali.pycfn.com/Article/details/gt2ufskuncr.html

C#:   (int)resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gt2bgrcxwtm.html

[L08] 并发请求多个地址
来源：http://dali.shuidangran.top/Article/details/gt2cmxfltyd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgfzy.top/Article/details/gt2gujvszix.html

PHP:  curl_multi_init() 系列
来源：http://dali.aizwys.cn/Article/details/gt2eerbwbmq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gt2nqarqvpg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gt2sujuatag.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuxming.cn/Article/details/gt2lpfhnoeq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.meibo888.top/Article/details/gt2cszedioh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenlongwang.top/Article/details/gt2urppfmln.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ivvv.top/Article/details/gt2mgghgxmm.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2dzmpxldg.html

M. 命令行 / 进程 / 环境
来源：http://dali.9152youxi.cn/Article/details/gt2zgcnjlje.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2tlphatcl.html

[M01] 读取命令行参数
来源：http://dali.tanke756.top/Article/details/gt2csycmnlf.html

Py:   sys.argv[1:]
来源：http://dali.gzhubu.top/Article/details/gt2legrvkbv.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigufen.top/Article/details/gt2clddlglo.html

JS:   process.argv.slice(2)
来源：http://dali.xinyue.icu/Article/details/gt2duzupded.html

TS:   process.argv.slice(2)
来源：http://dali.redwolf501.top/Article/details/gt2hsaiwpfd.html

Java: args 数组（main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gt2fgqgcfzv.html

Go:   os.Args[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2qtzctacp.html

Ruby: ARGV
来源：http://dali.vqdsnc.cn/Article/details/gt2wwceavkf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gt2hemwrgok.html

[M02] 读取环境变量
来源：http://dali.guowangkeji.top/Article/details/gt2pjtpwstz.html

Py:   os.environ.get("HOME")
来源：http://dali.aizwys.cn/Article/details/gt2tvnekhmj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.aizwys.cn/Article/details/gt2cwrftaei.html

JS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gt2xgyuusal.html

TS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gt2ssuekztw.html

Java: System.getenv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gt2ijzsdeko.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2galtyvay.html

Ruby: ENV["HOME"]
来源：http://dali.zhengqikj.top/Article/details/gt2tzaxxvlu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gt2uvmwddsj.html

[M03] 执行外部命令
来源：http://dali.cdnleiting.top/Article/details/gt2ypzfgcwj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.316326.xyz/Article/details/gt2yljaxibk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhengqikj.top/Article/details/gt2uxgycssw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gt2ohrqlvfr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhengqikj.top/Article/details/gt2cjapbyjd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mdfxtyza.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2izrlrkgg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.quarkkingdee.top/Article/details/gt2kphvctxt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.snrcjt.cn/Article/details/gt2zwpnzllu.html

[M04] 获取当前工作目录
来源：http://dali.gogol.net.cn/Article/details/gt2vqcvtvlb.html

Py:   os.getcwd()
来源：http://dali.jlsjyb.cn/Article/details/gt2evdyqnbc.html

PHP:  getcwd();
来源：http://dali.hnqzz.top/Article/details/gt2drxtauxp.html

JS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gt2eoqazghg.html

TS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gt2udkaljrs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgufenzy.top/Article/details/gt2oeeicemw.html

Go:   os.Getwd()
来源：http://dali.chenjidiqi.icu/Article/details/gt2inibdxxf.html

Ruby: Dir.pwd
来源：http://dali.nanxuanxn.top/Article/details/gt2hqnhkqgn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuxming.cn/Article/details/gt2fpgoiuwf.html

[M05] 设置退出码
来源：http://dali.cheryme.top/Article/details/gt2xfsctohu.html

Py:   sys.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2zktbevdc.html

PHP:  exit(1);
来源：http://dali.chenlongwang.top/Article/details/gt2azodkhjw.html

JS:   process.exit(1)
来源：http://dali.316326.xyz/Article/details/gt2sdlgxtbq.html

TS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2iwisfazq.html

Java: System.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2cbjnskfx.html

Go:   os.Exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2psmryuzq.html

Ruby: exit 1
来源：http://dali.cucudq.cn/Article/details/gt2nitqmayx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhixingplan.top/Article/details/gt2jkehbhsv.html

[M06] 向标准错误输出
来源：http://dali.yangfankeji.com/Article/details/gt2csmossly.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gt2ixkfqrmh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shzxlz.cn/Article/details/gt2xhsvsdoi.html

JS:   console.error("err")
来源：http://dali.yangfankeji.com/Article/details/gt2xfsnfuhw.html

TS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gt2xfaapfrl.html

Java: System.err.println("err")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tqtcgyva.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxinkj.top/Article/details/gt2tdzcaiyn.html

Ruby: warn "err"
来源：http://dali.jlsjyb.cn/Article/details/gt2kwcdgcle.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gogol.net.cn/Article/details/gt2auqbltbl.html

[M07] 判断是否为主入口
来源：http://dali.smart0.xyz/Article/details/gt2nqdhowov.html

Py:   if __name__ == "__main__":
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xalomqem.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhoulong.xyz/Article/details/gt2xcworvsm.html

JS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gt2wcrtxnpq.html

TS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gt2axlqlmsv.html

Java: public static void main(String[] args)
来源：http://dali.hysaishi.cn/Article/details/gt2xvbsukkn.html

Go:   func main()
来源：http://dali.havefunace.top/Article/details/gt2orolxzaa.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuxming.cn/Article/details/gt2oshqvxoy.html

C#:   static void Main(string[] args)
来源：http://dali.fengsongda.top/Article/details/gt2kwoznfec.html

[M08] 获取系统与运行时信息
来源：http://dali.svipenyu.cn/Article/details/gt2zusifkpd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jianghu66.top/Article/details/gt2otgoexop.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dianchejie.cn/Article/details/gt2gzotwalg.html

JS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gt2kizzvpnb.html

TS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gt2nxqhbvtk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj202588.top/Article/details/gt2hevailmn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigfzy.top/Article/details/gt2bphxzioh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shuidangran.top/Article/details/gt2tzmdlrcc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dozvjdwo.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2xoslmbyc.html

N. 数据结构与算法
来源：http://dali.cdnleiting.top/Article/details/gt2ufdsffdi.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2auupbmmu.html

[N01] 二分查找（有序数组）
来源：http://dali.0kj1m.cn/Article/details/gt2xtrbutjh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2nnfjgtbj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nwbrower.top/Article/details/gt2fwfceust.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ompqnxsn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gt2xsukajbw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2ficeqtes.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2caqeplre.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shzxlz.cn/Article/details/gt2bowclvcq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2rgsfzvns.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gotoacloud.top/Article/details/gt2hsrppyhb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gt2jgazaqru.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.0kj1m.cn/Article/details/gt2czbaphta.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gt2gezpairk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mybqdxxk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yvedp.cn/Article/details/gt2waqdalwq.html

Go:   slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2ynncqrsg.html

Ruby: arr.sort
来源：http://dali.dianchejie.cn/Article/details/gt2fqoamrve.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxuanxn.top/Article/details/gt2aypwvdkb.html

[N03] 快速排序（分治示例）
来源：http://dali.shangyingyoupin.top/Article/details/gt2mrhkqiyg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yueranfly.top/Article/details/gt2potvtwuj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hywenlv.cn/Article/details/gt2lerfedwy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gt2hrxggerc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gt2pvgbjjqr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nwbrower.top/Article/details/gt2oxjjlvau.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jiagoushi.top/Article/details/gt2psnihgef.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258888.top/Article/details/gt2wbtgezfk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ydzc1.top/Article/details/gt2ccwsyqvr.html

[N04] 斐波那契数列
来源：http://dali.zhixingplan.top/Article/details/gt2wuaxhnck.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gt2ahqltoej.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uarjnqbs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2kqcmhrmz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gt2mzlwwyys.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gt2ncafyvqz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258888.top/Article/details/gt2yakystvp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gt2ewdiqehk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gt2jriibjsw.html

[N05] 最大公约数
来源：http://dali.havefunace.top/Article/details/gt2ymbvqepm.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbwakid.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yangfankeji.com/Article/details/gt2stabteir.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuxming.cn/Article/details/gt2kqxawcje.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ppjwa.cn/Article/details/gt2nxkxmclf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.birdmap.top/Article/details/gt2yahyarto.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdfkeyg.html

Ruby: a.gcd(b)
来源：http://dali.ivvv.top/Article/details/gt2bctuyufk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tanke756.top/Article/details/gt2mjfcrpdh.html

[N06] 判断回文字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2sksoxeps.html

Py:   s == s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gt2yysjurva.html

PHP:  $s === strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2gvgvvjbw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2krkylvln.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gt2nutxgawh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hfpthk.cn/Article/details/gt2naeyhykw.html

Go:   // 双指针从两端比较
来源：http://dali.yvedp.cn/Article/details/gt2qqsdqroy.html

Ruby: s == s.reverse
来源：http://dali.xuanzx.com/Article/details/gt2ryhecyed.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gt2qnsfatoc.html

[N07] 两数之和（返回下标）
来源：http://dali.zhixingplan.top/Article/details/gt2lnfzbkip.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aizwys.cn/Article/details/gt2sixdbnql.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guowangkeji.top/Article/details/gt2akyxzret.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nanxuanxn.top/Article/details/gt2iouwplyy.html

TS:   // 手写 Map<string, number>
来源：http://dali.smart0.xyz/Article/details/gt2vcqmddnn.html

Java: // 手写 HashMap
来源：http://dali.svipenyu.cn/Article/details/gt2jimckdpk.html

Go:   // 手写 map[int]int
来源：http://dali.daxiang520.top/Article/details/gt2udrhhnfp.html

Ruby: // 手写 Hash
来源：http://dali.tian-w.cn/Article/details/gt2nwultfuv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhiwuduotai.top/Article/details/gt2hcrjizrr.html

[N08] 生成全排列
来源：http://dali.kuanghao11.cn/Article/details/gt2jijzqcfz.html

Py:   itertools.permutations(arr)
来源：http://dali.havefunace.top/Article/details/gt2jcylejdc.html

PHP:  // 手写递归交换
来源：http://dali.shzxlz.cn/Article/details/gt2azxullaj.html

JS:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gt2cklkrlzk.html

TS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gt2iobenosy.html

Java: // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gt2hinzkqqm.html

Go:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gt2vnhmemww.html

Ruby: arr.permutation.to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mifutpbo.html

C#:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gt2mfiukzap.html

[N09] 栈与队列
来源：http://dali.gogol.net.cn/Article/details/gt2qgggebvj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2eofxntpb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ydzc1.top/Article/details/gt2lxoehazo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gt2jodkjhej.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hnqzz.top/Article/details/gt2mthabapc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.svipenyu.cn/Article/details/gt2rleqrkgj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aibaodan.cn/Article/details/gt2lqkdwbby.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gt2soqfzsrq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tian-w.cn/Article/details/gt2jckgrbkg.html

[N10] 链表节点定义
来源：http://dali.yongpay.top/Article/details/gt2uhamfmyb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zdqjudy.top/Article/details/gt2mdqvarwm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.bjfxy.top/Article/details/gt2fvbwhmty.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cashguo.top/Article/details/gt2cgirudbm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.havefunace.top/Article/details/gt2cplzttuh.html

Java: class Node { int v; Node next; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2lrjzpghx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sysykeji.top/Article/details/gt2ydwestbh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gotoacloud.top/Article/details/gt2axtrivop.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgufenzy.top/Article/details/gt2qjlpeswm.html

[N11] 二叉树中序遍历
来源：http://dali.aizwys.cn/Article/details/gt2dzinozli.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cheryme.top/Article/details/gt2tqcqmmuj.html

PHP:  // 手写递归函数
来源：http://dali.9152youxi.cn/Article/details/gt2tibwezlf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gt2sbpawmqf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shzxlz.cn/Article/details/gt2netgvqhb.html

Java: // 手写递归
来源：http://dali.cashguo.top/Article/details/gt2ibhwlduf.html

Go:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gt2deytnwxx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangdashe.top/Article/details/gt2vveofyhc.html

C#:   // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2xsgunhbd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.andypj.xyz/Article/details/gt2ptnuwoyf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yanxiufei.cn/Article/details/gt2nwenrjtc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jlsjyb.cn/Article/details/gt2pmglnmjv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tjxxefgs.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gt2chspdsuh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gt2zueeyvuu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.316326.xyz/Article/details/gt2jmloeyix.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hammf.cn/Article/details/gt2hrzpzahn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.redwolf501.top/Article/details/gt2wzsjhjfx.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2bjyiyrfa.html

O. 并发与异步
来源：http://dali.tianlin.xyz/Article/details/gt2ujneyhle.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2aptytcvl.html

[O01] 启动一个线程
来源：http://dali.zhongyouzk.top/Article/details/gt2dmjcdzci.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cashguo.top/Article/details/gt2advaklau.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2enlzqbgi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pxmriwor.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gt2srddxxcu.html

Java: new Thread(() -> f()).start()
来源：http://dali.ivvv.top/Article/details/gt2nqgnldir.html

Go:   go f()
来源：http://dali.iojbl.cn/Article/details/gt2lqkqglwd.html

Ruby: Thread.new { f }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ozxnrxtq.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigufen.top/Article/details/gt2gxfivffx.html

[O02] 使用线程池
来源：http://dali.hfpthk.cn/Article/details/gt2jjwenjdb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ydzc1.top/Article/details/gt2ddrvjvut.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shuidangran.top/Article/details/gt2fojkjmpp.html

JS:   // worker_threads 线程池
来源：http://dali.redwolf501.top/Article/details/gt2yiczeljk.html

TS:   // worker_threads 线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zchmjkcv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nipancly.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gzhubu.top/Article/details/gt2evdacucf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.birdmap.top/Article/details/gt2nlzljhjx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhiwuduotai.top/Article/details/gt2zgsdptjt.html

[O03] 加锁保护共享数据
来源：http://dali.mhx1999.top/Article/details/gt2qgvmrfkp.html

Py:   with lock: shared += 1
来源：http://dali.fzhhl.top/Article/details/gt2jewpmlta.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuxming.cn/Article/details/gt2vxifsdtg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.iojbl.cn/Article/details/gt2hygmpdkd.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gt2quhvmrsf.html

Java: synchronized (this) { shared++; }
来源：http://dali.9152youxi.cn/Article/details/gt2qgqlwjkm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shzxlz.cn/Article/details/gt2lxilnixu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2echvcewy.html

C#:   lock (gate) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gt2pwymxlxr.html

[O04] 定义异步函数并等待
来源：http://dali.zhongyouzk.top/Article/details/gt2okmmhadt.html

Py:   async def f():⏎    await g()
来源：http://dali.0kj1m.cn/Article/details/gt2pygovfik.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yonumen.top/Article/details/gt2pmpcnsbj.html

JS:   async function f() { await g(); }
来源：http://dali.316326.xyz/Article/details/gt2sejpxfsl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jianghu66.top/Article/details/gt2jgnpgysm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sysykeji.top/Article/details/gt2eqrdmqsk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tianlin.xyz/Article/details/gt2fubcdmgo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.mhx1999.top/Article/details/gt2oaxrhfbm.html

C#:   async Task F() { await G(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2gswgbdkh.html

[O05] 并发执行并等待全部完成
来源：http://dali.yanxiufei.cn/Article/details/gt2uwhnegdk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zfpfiyko.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ppjwa.cn/Article/details/gt2ympiikyx.html

JS:   await Promise.all(tasks)
来源：http://dali.cashguo.top/Article/details/gt2zpfnwjyu.html

TS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gt2xpjgboaq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hysaishi.cn/Article/details/gt2mlwyseuc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.quarkkingdee.top/Article/details/gt2gmusuykb.html

Ruby: threads.map(&:join)
来源：http://dali.xuanzx.com/Article/details/gt2oxcvzekp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.iojbl.cn/Article/details/gt2fqwqttch.html

[O06] 使用进程池
来源：http://dali.guannengcc.top/Article/details/gt2xwialazd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgfzy.top/Article/details/gt2grfopxxd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tanke756.top/Article/details/gt2ffmbtzot.html

JS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gt2fwnatved.html

TS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gt2fibhdckp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xinyue.icu/Article/details/gt2bdxsnxui.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xuetiantiany.cn/Article/details/gt2jyyldmkn.html

Ruby: // fork 块
来源：http://dali.shuidangran.top/Article/details/gt2fkvbmzdz.html

C#:   Parallel.For
来源：http://dali.kuanghao11.cn/Article/details/gt2rbzmxfap.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2clvmqhkg.html

P. 常用工具函数
来源：http://dali.cqqwz.cn/Article/details/gt2dxrxugcv.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2bqhtkgjb.html

[P01] 生成 UUID
来源：http://dali.guannengcc.top/Article/details/gt2oudwpndo.html

Py:   str(uuid.uuid4())
来源：http://dali.ydzc1.top/Article/details/gt2mqjcflap.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gtcqqtip.html

JS:   crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gt2lizchxuk.html


<!-- 参考信息 -->