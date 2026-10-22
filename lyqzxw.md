代发 wailian999

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigfzy.top/Article/details/gt2xrjmuepq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dashuyun.cn/Article/details/gt2ewgrolbp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gogol.net.cn/Article/details/gt2ppftrabh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cashguo.top/Article/details/gt2ywgiypsk.html

[L03] 设置自定义请求头
来源：http://dali.meibo888.top/Article/details/gt2njjiiojo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258888.top/Article/details/gt2ymwwsqpv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hywenlv.cn/Article/details/gt2xstatvbo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ehwqpu.com/Article/details/gt2oycgmvku.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gt2vooulfau.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.fzhhl.top/Article/details/gt2ixpmolee.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gt2fufnjnyz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgufenzy.top/Article/details/gt2zlacebfe.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gt2bonrulua.html

[L04] 设置超时
来源：http://dali.9152youxi.cn/Article/details/gt2yramxeqq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhongyouzk.top/Article/details/gt2ftbjduxn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.redwolf501.top/Article/details/gt2dqadswtw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2axibgjqu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gt2cyhkonrh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zycfv.cn/Article/details/gt2jhqaxglb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangshuangyany.cn/Article/details/gt2tbauahom.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zycfv.cn/Article/details/gt2bygazrww.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hywenlv.cn/Article/details/gt2gejavprg.html

[L05] 上传文件（multipart）
来源：http://dali.chenzaomai.com/Article/details/gt2vzsgudpu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ppjwa.cn/Article/details/gt2cbwljysk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.smart0.xyz/Article/details/gt2rgdpaqat.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gt2jtkuvvfa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjhfwhef.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yueranfly.top/Article/details/gt2mmetbtgz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ydzc1.top/Article/details/gt2jtgpvkqe.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.snrcjt.cn/Article/details/gt2mfmndpcb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2otuayspu.html

[L06] 解析响应为 JSON
来源：http://dali.hammf.cn/Article/details/gt2jibuyjxu.html

Py:   resp.json()
来源：http://dali.cdnleiting.top/Article/details/gt2snzclvkb.html

PHP:  json_decode($body, true);
来源：http://dali.hywenlv.cn/Article/details/gt2dylipelt.html

JS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gt2giclmhwm.html

TS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nawqvfla.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yonumen.top/Article/details/gt2ubckedyo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aizwys.cn/Article/details/gt2nsseyvpk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cheryme.top/Article/details/gt2brwisaqw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cqqwz.cn/Article/details/gt2femytbqj.html

[L07] 处理 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gt2uosnpgiw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.redwolf501.top/Article/details/gt2vdafjeip.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yueranfly.top/Article/details/gt2skrhaxnw.html

JS:   resp.ok;  resp.status
来源：http://dali.ehwqpu.com/Article/details/gt2cckxrqnv.html

TS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gt2vjbhasdw.html

Java: resp.statusCode()
来源：http://dali.hnqzz.top/Article/details/gt2bwtaekfb.html

Go:   resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gt2hqluhuih.html

Ruby: resp.code.to_i
来源：http://dali.ybcxt.top/Article/details/gt2eojqblnz.html

C#:   (int)resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gt2cvneeveq.html

[L08] 并发请求多个地址
来源：http://dali.pengpengdd.cyou/Article/details/gt2oirjzsxk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jyoumei.cn/Article/details/gt2videwnlw.html

PHP:  curl_multi_init() 系列
来源：http://dali.hysaishi.cn/Article/details/gt2zmncruff.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gt2xsrxmrbe.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gt2tngdrfyc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sxryk.cn/Article/details/gt2ryxjeruw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ybcxt.top/Article/details/gt2dbfnzygi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.havefunace.top/Article/details/gt2zbvsomnn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhongyouzk.top/Article/details/gt2zadjeesf.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2mixbrmjd.html

M. 命令行 / 进程 / 环境
来源：http://dali.sysykeji.top/Article/details/gt2puoynmen.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2ghhushcw.html

[M01] 读取命令行参数
来源：http://dali.jinqigufen.top/Article/details/gt2znfwgswz.html

Py:   sys.argv[1:]
来源：http://dali.fzhhl.top/Article/details/gt2beogwaow.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkfwvxd.html

JS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gt2nmckrbli.html

TS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wavsfcqy.html

Java: args 数组（main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gt2aejbdtdy.html

Go:   os.Args[1:]
来源：http://dali.aizwys.cn/Article/details/gt2ycrhmcbw.html

Ruby: ARGV
来源：http://dali.nwbrower.top/Article/details/gt2aanuaukl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yongpay.top/Article/details/gt2wgdhznib.html

[M02] 读取环境变量
来源：http://dali.ydzc1.top/Article/details/gt2vpuhdvee.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2ojqsmomw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gt2zfhhckwi.html

JS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gt2iftjjloi.html

TS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gt2ujgjniki.html

Java: System.getenv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gt2nmxkevbu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gt2mkjivrvr.html

Ruby: ENV["HOME"]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hloflcjs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuxming.cn/Article/details/gt2jkjemkad.html

[M03] 执行外部命令
来源：http://dali.nanxuanxn.top/Article/details/gt2ktidrahk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuanzhike.top/Article/details/gt2mwawdiel.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ivvv.top/Article/details/gt2ciexbzqh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gt2felajrjl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gt2pcifgdco.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj202588.top/Article/details/gt2mxtmtair.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fzhhl.top/Article/details/gt2hldfsdgn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigufen.top/Article/details/gt2lpkidxoa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigfzy.top/Article/details/gt2poseumrg.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gt2hbjgxpja.html

Py:   os.getcwd()
来源：http://dali.tanke756.top/Article/details/gt2jfixjnlb.html

PHP:  getcwd();
来源：http://dali.yangfankeji.com/Article/details/gt2yvfuvcoo.html

JS:   process.cwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2qkpvtlnn.html

TS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gt2amufwhax.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangdashe.top/Article/details/gt2iczdebar.html

Go:   os.Getwd()
来源：http://dali.shuidangran.top/Article/details/gt2qfhzawzr.html

Ruby: Dir.pwd
来源：http://dali.chenlongwang.top/Article/details/gt2niqwfvbi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.316326.xyz/Article/details/gt2akrtwogi.html

[M05] 设置退出码
来源：http://dali.kuanghao11.cn/Article/details/gt2fbzczmho.html

Py:   sys.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gt2gaypbjvc.html

PHP:  exit(1);
来源：http://dali.hfpthk.cn/Article/details/gt2zqwkvmlq.html

JS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gt2fzixutaj.html

TS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2mtflqotb.html

Java: System.exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2yfbzlifb.html

Go:   os.Exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2vwxjqnun.html

Ruby: exit 1
来源：http://dali.cdnleiting.top/Article/details/gt2anlyabne.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hywenlv.cn/Article/details/gt2mgfhccdb.html

[M06] 向标准错误输出
来源：http://dali.dianchejie.cn/Article/details/gt2tucmgkln.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gt2egigqdlq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tucjpsev.html

JS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gt2sfpyjqel.html

TS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gt2nnmyeydz.html

Java: System.err.println("err")
来源：http://dali.xziqi.cn/Article/details/gt2mgdfbaig.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258888.top/Article/details/gt2hfqyirpi.html

Ruby: warn "err"
来源：http://dali.shuidangran.top/Article/details/gt2ktslujez.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yvedp.cn/Article/details/gt2vpdjzeeq.html

[M07] 判断是否为主入口
来源：http://dali.sweek.top/Article/details/gt2cvpcpnxz.html

Py:   if __name__ == "__main__":
来源：http://dali.yj202588.top/Article/details/gt2lbphwpif.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ehwqpu.com/Article/details/gt2geehhyfa.html

JS:   require.main === module
来源：http://dali.fzhhl.top/Article/details/gt2ftjgeksz.html

TS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gt2mrzohwnb.html

Java: public static void main(String[] args)
来源：http://dali.ppjwa.cn/Article/details/gt2txtsypfw.html

Go:   func main()
来源：http://dali.xuanzx.com/Article/details/gt2zvmmtklz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.iojbl.cn/Article/details/gt2hcvnzbmc.html

C#:   static void Main(string[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2voeazvdo.html

[M08] 获取系统与运行时信息
来源：http://dali.sxryk.cn/Article/details/gt2awngpjyj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sxryk.cn/Article/details/gt2lwhacuzr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cdnleiting.top/Article/details/gt2mtpwvxnq.html

JS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gt2aryycllw.html

TS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gt2uutcwwia.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dianchejie.cn/Article/details/gt2dpwqgybm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daria6918.cn/Article/details/gt2zmrzkpxt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gt2frvzwffl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hjopnppa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bburnntv.html

N. 数据结构与算法
来源：http://dali.smart0.xyz/Article/details/gt2rhwwyvje.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2mwoirsmc.html

[N01] 二分查找（有序数组）
来源：http://dali.dashuyun.cn/Article/details/gt2hhmmzgnk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2puuwtdds.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hywenlv.cn/Article/details/gt2bszskrss.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qodiocwf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wskvbdnf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gt2mndwttve.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2ylzjijxr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jianghu66.top/Article/details/gt2gutvwrue.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gt2qicvxoop.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.guowangkeji.top/Article/details/gt2ssxtwrec.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gt2jkgypuxy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.kuanghao11.cn/Article/details/gt2gpsnsgxu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gt2reaudkqc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kahcxhsp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guowangkeji.top/Article/details/gt2npbqbcno.html

Go:   slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gt2wwpkuagv.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jbzkmyna.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cashguo.top/Article/details/gt2vjfbkytm.html

[N03] 快速排序（分治示例）
来源：http://dali.chenzaomai.com/Article/details/gt2dxczeroj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yanxiufei.cn/Article/details/gt2oonigzig.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pengpengdd.cyou/Article/details/gt2fsjmbkhq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gt2ourlodsl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tian-w.cn/Article/details/gt2lvvkhbqk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.316326.xyz/Article/details/gt2quegalvo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenzaomai.com/Article/details/gt2nznqnenv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenjidiqi.icu/Article/details/gt2sstwtrjw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.svipenyu.cn/Article/details/gt2akkfwlkm.html

[N04] 斐波那契数列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tkbemebg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.fengsongda.top/Article/details/gt2amxzastv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.guannengcc.top/Article/details/gt2zxrdqxhr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2fvvunuwt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gt2nbvhoklh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gt2wuqtuawm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ppjwa.cn/Article/details/gt2tqzpmuim.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gt2gtdppnls.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gt2szrtgjqf.html

[N05] 最大公约数
来源：http://dali.yuxming.cn/Article/details/gt2tcmtdcsi.html

Py:   math.gcd(a, b)
来源：http://dali.zhixingplan.top/Article/details/gt2acieedrg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xylfe.cn/Article/details/gt2bikyupfe.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gt2nshuufev.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gt2pjnxkdoa.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yyswjiqc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ppjwa.cn/Article/details/gt2fsivsxbq.html

Ruby: a.gcd(b)
来源：http://dali.shuidangran.top/Article/details/gt2frsciyut.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sufxvd.cn/Article/details/gt2vtgchmim.html

[N06] 判断回文字符串
来源：http://dali.wangdashe.top/Article/details/gt2trdufsvg.html

Py:   s == s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gt2nzhnxhvp.html

PHP:  $s === strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2oxistolh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gt2zbalhcmf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gt2uglplejp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sysykeji.top/Article/details/gt2cakdnudx.html

Go:   // 双指针从两端比较
来源：http://dali.yj202588.top/Article/details/gt2jqdevqxy.html

Ruby: s == s.reverse
来源：http://dali.fengsongda.top/Article/details/gt2wlqdxjqw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kdfatgpd.html

[N07] 两数之和（返回下标）
来源：http://dali.jiagoushi.top/Article/details/gt2nzkymbnb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.c1oappe.top/Article/details/gt2dslnfkvs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xziqi.cn/Article/details/gt2ccjhcjpt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daxiang520.top/Article/details/gt2oqdkvtic.html

TS:   // 手写 Map<string, number>
来源：http://dali.sweek.top/Article/details/gt2toplujtm.html

Java: // 手写 HashMap
来源：http://dali.zdqjudy.top/Article/details/gt2xvjijgdl.html

Go:   // 手写 map[int]int
来源：http://dali.ivvv.top/Article/details/gt2mracggxc.html

Ruby: // 手写 Hash
来源：http://dali.yangfankeji.com/Article/details/gt2uidwsmqk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gzhubu.top/Article/details/gt2qdsqrrcu.html

[N08] 生成全排列
来源：http://dali.smart0.xyz/Article/details/gt2falxgcon.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2uljxtedi.html

PHP:  // 手写递归交换
来源：http://dali.nanxuanxn.top/Article/details/gt2brkfvbfl.html

JS:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gt2tzmgvpgs.html

TS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2tfvgknjq.html

Java: // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2esujeuei.html

Go:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gt2duqckzat.html

Ruby: arr.permutation.to_a
来源：http://dali.shzxlz.cn/Article/details/gt2xdygbiep.html

C#:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gt2larnujui.html

[N09] 栈与队列
来源：http://dali.jianghu66.top/Article/details/gt2yqdlnazu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aibaodan.cn/Article/details/gt2vasqivwv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gt2pfweungw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gt2brguirxh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aizwys.cn/Article/details/gt2utyyqjil.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dashuyun.cn/Article/details/gt2xqmsyecq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yueranfly.top/Article/details/gt2kjiebbqc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gt2rvsoxaaq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.iojbl.cn/Article/details/gt2zebdhvzy.html

[N10] 链表节点定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2evlturho.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nanxinkj.top/Article/details/gt2xhzhrwss.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jlsjyb.cn/Article/details/gt2knzlpqgs.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.kuanghao11.cn/Article/details/gt2skzbyuhq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hywenlv.cn/Article/details/gt2sywkaggu.html

Java: class Node { int v; Node next; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2clrciynf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pnronzte.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.snrcjt.cn/Article/details/gt2toovdlpf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jlsjyb.cn/Article/details/gt2iqrsstjn.html

[N11] 二叉树中序遍历
来源：http://dali.iojbl.cn/Article/details/gt2lnnptafp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenlongwang.top/Article/details/gt2xhowlkhr.html

PHP:  // 手写递归函数
来源：http://dali.jianghu66.top/Article/details/gt2zocctrji.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gt2kafzkatn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gt2opyjkfxp.html

Java: // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dnrkqpmc.html

Go:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2msdgalgt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.meibo888.top/Article/details/gt2gwpeuxhx.html

C#:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gt2uimlietn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ybcxt.top/Article/details/gt2hhqixbhp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jianghu66.top/Article/details/gt2jjejedrx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gt2kbqaufei.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gt2vxqhmwne.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gt2zocuyfyg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gt2bslusjnh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhengqikj.top/Article/details/gt2dxytcrbg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhongyouzk.top/Article/details/gt2hnrhvler.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gt2gzgtycxh.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2bbavxfhb.html

O. 并发与异步
来源：http://dali.quarkkingdee.top/Article/details/gt2bdhyrlry.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2deznjcpg.html

[O01] 启动一个线程
来源：http://dali.jiagoushi.top/Article/details/gt2civzdnad.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pengpengdd.cyou/Article/details/gt2pfapikff.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.quarkkingdee.top/Article/details/gt2qkxomarv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jianghu66.top/Article/details/gt2pjeahaep.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gt2vxpjvwsg.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2unkciqwd.html

Go:   go f()
来源：http://dali.gogol.net.cn/Article/details/gt2xdzzogqx.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxkzwia.html

C#:   Task.Run(() => F());
来源：http://dali.zhixingplan.top/Article/details/gt2tqtffwly.html

[O02] 使用线程池
来源：http://dali.hnxiangtu.top/Article/details/gt2pnhsaroo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eyxgkjxr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shangyingyoupin.top/Article/details/gt2fohgpmmj.html

JS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gt2ndbhhprf.html

TS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gt2uopqwywv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.meibo888.top/Article/details/gt2khcnwiyf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtxptgw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wcfxxzjc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xhkpdfph.html

[O03] 加锁保护共享数据
来源：http://dali.mhx1999.top/Article/details/gt2gtiqpmmq.html

Py:   with lock: shared += 1
来源：http://dali.zhixingplan.top/Article/details/gt2hnmvixnq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhongyouzk.top/Article/details/gt2qoohwvez.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shuidangran.top/Article/details/gt2trhzdekw.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2avvxhgjb.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2twgdqfwg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenzaomai.com/Article/details/gt2qbedagwd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jlsjyb.cn/Article/details/gt2extstcjn.html

C#:   lock (gate) { shared++; }
来源：http://dali.aibaodan.cn/Article/details/gt2duvtyyoi.html

[O04] 定义异步函数并等待
来源：http://dali.cqqwz.cn/Article/details/gt2hrnrxzlq.html

Py:   async def f():⏎    await g()
来源：http://dali.mhx1999.top/Article/details/gt2hvxkreaz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.0kj1m.cn/Article/details/gt2jljwtjib.html

JS:   async function f() { await g(); }
来源：http://dali.yueranfly.top/Article/details/gt2athspaep.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ivvv.top/Article/details/gt2vsvhbegw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.snrcjt.cn/Article/details/gt2mllzqbuj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.birdmap.top/Article/details/gt2hohyyyym.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgufenzy.top/Article/details/gt2xwpiaqjt.html

C#:   async Task F() { await G(); }
来源：http://dali.pycfn.com/Article/details/gt2tgogystl.html

[O05] 并发执行并等待全部完成
来源：http://dali.redwolf501.top/Article/details/gt2moytjsnh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shzxlz.cn/Article/details/gt2jikiqfnc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ksvepmom.html

JS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gt2pqqjfzhy.html

TS:   await Promise.all(tasks)
来源：http://dali.jiagoushi.top/Article/details/gt2hrmarpdy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ivvv.top/Article/details/gt2mwmeqpyo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guowangkeji.top/Article/details/gt2uukbajym.html

Ruby: threads.map(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mxqoqkkb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ppjwa.cn/Article/details/gt2boczeiap.html

[O06] 使用进程池
来源：http://dali.shangyingyoupin.top/Article/details/gt2coghzgkx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ydzc1.top/Article/details/gt2amsalwtv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tianlin.xyz/Article/details/gt2dxpjkgxq.html

JS:   // child_process / cluster 模块
来源：http://dali.hysaishi.cn/Article/details/gt2bzhdnxck.html

TS:   // child_process / cluster 模块
来源：http://dali.hammf.cn/Article/details/gt2qhdjypro.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.316326.xyz/Article/details/gt2ascwwjpw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.pengpengdd.cyou/Article/details/gt2rcwijevz.html

Ruby: // fork 块
来源：http://dali.aibaodan.cn/Article/details/gt2pwrrkjtk.html


<!-- 参考信息 -->