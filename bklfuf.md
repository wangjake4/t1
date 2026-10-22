代发 wailian999

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gt2kggtwcwt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhoulong.xyz/Article/details/gt2ppqblmey.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gt2uxgskcqa.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gt2uilxggig.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hywenlv.cn/Article/details/gt2iiwcdktk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cqqwz.cn/Article/details/gt2aenerjrj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dashuyun.cn/Article/details/gt2qatcwoqf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gotoacloud.top/Article/details/gt2ynwzmxjt.html

[L03] 设置自定义请求头
来源：http://dali.c1oappe.top/Article/details/gt2whwspgrq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ybcxt.top/Article/details/gt2orolnoro.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hnqzz.top/Article/details/gt2mlhckyvv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gt2wfvqbsbq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gt2owpsxtom.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gzhubu.top/Article/details/gt2swiblitq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gt2exaubocv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rstsrdnq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gt2ugznzogv.html

[L04] 设置超时
来源：http://dali.dashuyun.cn/Article/details/gt2tltbvkmj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuanzx.com/Article/details/gt2rnbeznqd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jwiktaat.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gt2xaqpbdaa.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gt2vuyiejzu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.svipenyu.cn/Article/details/gt2jooyhwxd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.havefunace.top/Article/details/gt2dzxommxd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shangyingyoupin.top/Article/details/gt2czhznwru.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigfzy.top/Article/details/gt2bcqfthxr.html

[L05] 上传文件（multipart）
来源：http://dali.yanxiufei.cn/Article/details/gt2vwxxyjgt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.birdmap.top/Article/details/gt2snkjwkrt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.iojbl.cn/Article/details/gt2waoodmom.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gt2nliytkgv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cqqwz.cn/Article/details/gt2hsgdlide.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.feifeiyinyue.top/Article/details/gt2uhjlgbfy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hysaishi.cn/Article/details/gt2wtrlcohz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jyoumei.cn/Article/details/gt2denjqeur.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2ojkngyfl.html

[L06] 解析响应为 JSON
来源：http://dali.gotoacloud.top/Article/details/gt2nzvycggz.html

Py:   resp.json()
来源：http://dali.tian-w.cn/Article/details/gt2mtkpkaeb.html

PHP:  json_decode($body, true);
来源：http://dali.vqdsnc.cn/Article/details/gt2zeogtofb.html

JS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2qrulffje.html

TS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gt2skfgdbwg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yueranfly.top/Article/details/gt2cfsusrme.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258888.top/Article/details/gt2qxrqasfk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenzaomai.com/Article/details/gt2njvhgnjx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jiagoushi.top/Article/details/gt2ncuygqtk.html

[L07] 处理 HTTP 状态码
来源：http://dali.gaohongyu789.top/Article/details/gt2nodxfzpi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gzdrjpyp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yueranfly.top/Article/details/gt2vdeqjmuq.html

JS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gt2izefqlql.html

TS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gt2smrnxgpc.html

Java: resp.statusCode()
来源：http://dali.shzxlz.cn/Article/details/gt2tbdmoglm.html

Go:   resp.StatusCode
来源：http://dali.gotoacloud.top/Article/details/gt2qbsczuff.html

Ruby: resp.code.to_i
来源：http://dali.chenjidiqi.icu/Article/details/gt2gwdmvomn.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gt2fuhiahnn.html

[L08] 并发请求多个地址
来源：http://dali.aizwys.cn/Article/details/gt2phdpnpty.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shuidangran.top/Article/details/gt2nlbfjfmi.html

PHP:  curl_multi_init() 系列
来源：http://dali.yvedp.cn/Article/details/gt2zljzuaks.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gt2nrotzxbj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gt2qddfvsal.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guowangkeji.top/Article/details/gt2rbppwhdg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tanke756.top/Article/details/gt2qyyrpmgu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dashuyun.cn/Article/details/gt2dktznajl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xziqi.cn/Article/details/gt2akmjucux.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2fdmyuhaq.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenzaomai.com/Article/details/gt2vihorruj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2zxeauybt.html

[M01] 读取命令行参数
来源：http://dali.ydzc1.top/Article/details/gt2efnyzbci.html

Py:   sys.argv[1:]
来源：http://dali.birdmap.top/Article/details/gt2qkppotcz.html

PHP:  $argv;  $argc;
来源：http://dali.andypj.xyz/Article/details/gt2rroqhqak.html

JS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gt2ovcerejn.html

TS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gt2yclupbve.html

Java: args 数组（main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gt2jbittnks.html

Go:   os.Args[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mcvroipa.html

Ruby: ARGV
来源：http://dali.daxiang520.top/Article/details/gt2ywktyucr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gt2yvddowfr.html

[M02] 读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gt2euiqxcej.html

Py:   os.environ.get("HOME")
来源：http://dali.meibo888.top/Article/details/gt2kfckqwvs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gt2uugxpyeb.html

JS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gt2rdswcfdi.html

TS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gt2clzpwyaa.html

Java: System.getenv("HOME")
来源：http://dali.redwolf501.top/Article/details/gt2rolfgcgn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ypxgzesl.html

Ruby: ENV["HOME"]
来源：http://dali.iojbl.cn/Article/details/gt2btpewujp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.birdmap.top/Article/details/gt2vmzvufdm.html

[M03] 执行外部命令
来源：http://dali.chenzaomai.com/Article/details/gt2cahliizg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ydzc1.top/Article/details/gt2ewjajcze.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.316326.xyz/Article/details/gt2bhrtgbcd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gt2rvxhpkoz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gt2mijpdsha.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.vqdsnc.cn/Article/details/gt2aircqpqb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hywenlv.cn/Article/details/gt2zvshoahu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenjidiqi.icu/Article/details/gt2hakavoqw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gmmgxkam.html

[M04] 获取当前工作目录
来源：http://dali.xuetiantiany.cn/Article/details/gt2uyltttcx.html

Py:   os.getcwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wozpfbzu.html

PHP:  getcwd();
来源：http://dali.xziqi.cn/Article/details/gt2muygkuxx.html

JS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2udeidpiv.html

TS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sdzsvwia.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hnqzz.top/Article/details/gt2vmmlbwav.html

Go:   os.Getwd()
来源：http://dali.birdmap.top/Article/details/gt2iyswixof.html

Ruby: Dir.pwd
来源：http://dali.yuxming.cn/Article/details/gt2yahlsnfx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.havefunace.top/Article/details/gt2optkqebi.html

[M05] 设置退出码
来源：http://dali.jinqigufen.top/Article/details/gt2eervlvwu.html

Py:   sys.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2egykunca.html

PHP:  exit(1);
来源：http://dali.nwbrower.top/Article/details/gt2nqsyzjuc.html

JS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gt2wyrvgtrw.html

TS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2zirfjyyb.html

Java: System.exit(1)
来源：http://dali.gzhubu.top/Article/details/gt2ogvubzym.html

Go:   os.Exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rcpnckgh.html

Ruby: exit 1
来源：http://dali.xylfe.cn/Article/details/gt2ovfyqmfq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yanxiufei.cn/Article/details/gt2iqphezws.html

[M06] 向标准错误输出
来源：http://dali.316326.xyz/Article/details/gt2ydcrcmss.html

Py:   print("err", file=sys.stderr)
来源：http://dali.bjfxy.top/Article/details/gt2gaflhtzw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cdnleiting.top/Article/details/gt2zprojosk.html

JS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gt2uscpfako.html

TS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gt2kdzacdip.html

Java: System.err.println("err")
来源：http://dali.cucudq.cn/Article/details/gt2pgagtuxs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yueranfly.top/Article/details/gt2slbqizlm.html

Ruby: warn "err"
来源：http://dali.zycfv.cn/Article/details/gt2dkjenmbz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxinkj.top/Article/details/gt2omfgkwxr.html

[M07] 判断是否为主入口
来源：http://dali.yueranfly.top/Article/details/gt2otvdngtb.html

Py:   if __name__ == "__main__":
来源：http://dali.yongpay.top/Article/details/gt2vworcdsd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.mhx1999.top/Article/details/gt2etoylziv.html

JS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gt2izjrpflw.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gt2batcfxps.html

Java: public static void main(String[] args)
来源：http://dali.zhoulong.xyz/Article/details/gt2wvzlyijb.html

Go:   func main()
来源：http://dali.tian-w.cn/Article/details/gt2njavjfxk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sxryk.cn/Article/details/gt2mnmxxjkb.html

C#:   static void Main(string[] args)
来源：http://dali.meibo888.top/Article/details/gt2nlpaandm.html

[M08] 获取系统与运行时信息
来源：http://dali.xuetiantiany.cn/Article/details/gt2seshzusy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fzhhl.top/Article/details/gt2lochnahm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxuanxn.top/Article/details/gt2luayintk.html

JS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gt2gczyrzmz.html

TS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gt2diyofzcl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dashuyun.cn/Article/details/gt2nfhhnurw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jianghu66.top/Article/details/gt2cmokwbeg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.bjfxy.top/Article/details/gt2zpzrxnxv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nwbrower.top/Article/details/gt2oioqcbyk.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2owmyndxc.html

N. 数据结构与算法
来源：http://dali.jqgfzy.top/Article/details/gt2qskgljgs.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2otfdscmi.html

[N01] 二分查找（有序数组）
来源：http://dali.0kj1m.cn/Article/details/gt2ilepoicb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2lkeednup.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cashguo.top/Article/details/gt2aqfrxujv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gt2bmdvuddi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gt2dcidifaz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gt2ocvrifaf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2lhzacyxo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ppjwa.cn/Article/details/gt2oetmivgj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2lggtbpta.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.kuanghao11.cn/Article/details/gt2cmikeckj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gt2oyvbhkre.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.redwolf501.top/Article/details/gt2ffljqrjs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gt2yoxfxsmg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2phiffvbm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.meibo888.top/Article/details/gt2jksqaaas.html

Go:   slices.Sort(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2hvxwwjtg.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gt2xgnbtzlw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fengsongda.top/Article/details/gt2lifsxkxf.html

[N03] 快速排序（分治示例）
来源：http://dali.shzxlz.cn/Article/details/gt2yrpsocjd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cucudq.cn/Article/details/gt2pvwhgqvd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.vqdsnc.cn/Article/details/gt2vfusrbfm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gt2fhwhmyrr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gaohongyu789.top/Article/details/gt2ixrihcnm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgufenzy.top/Article/details/gt2weosmkaw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xinyue.icu/Article/details/gt2stdvkdzg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenlongwang.top/Article/details/gt2oqjopxis.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenlongwang.top/Article/details/gt2tapetdmh.html

[N04] 斐波那契数列
来源：http://dali.hongshengwenyu.top/Article/details/gt2kmxrkyzl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gt2cpsufomo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gt2cohbucbb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2yaobtqww.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gt2ebuiknvg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.fengsongda.top/Article/details/gt2gmplrohb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gotoacloud.top/Article/details/gt2lkthpynt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shzxlz.cn/Article/details/gt2tpcrnely.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gt2yjonqcsi.html

[N05] 最大公约数
来源：http://dali.gzhubu.top/Article/details/gt2cnunwgzi.html

Py:   math.gcd(a, b)
来源：http://dali.tian-w.cn/Article/details/gt2doegrvmj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.snrcjt.cn/Article/details/gt2ttspffxg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gt2ihvtygug.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gt2nwvfljgn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yueranfly.top/Article/details/gt2xtzvlfvj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nwbrower.top/Article/details/gt2rlaxxgxu.html

Ruby: a.gcd(b)
来源：http://dali.chenlongwang.top/Article/details/gt2ywuetbbz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dianchejie.cn/Article/details/gt2rlwmjktn.html

[N06] 判断回文字符串
来源：http://dali.birdmap.top/Article/details/gt2iarldspv.html

Py:   s == s[::-1]
来源：http://dali.yonumen.top/Article/details/gt2adgzazvb.html

PHP:  $s === strrev($s);
来源：http://dali.wangdashe.top/Article/details/gt2dmbbobtx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gt2jelbwjpn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gt2njrfadlv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.havefunace.top/Article/details/gt2cdnuxxky.html

Go:   // 双指针从两端比较
来源：http://dali.dashuyun.cn/Article/details/gt2colfwuid.html

Ruby: s == s.reverse
来源：http://dali.gotoacloud.top/Article/details/gt2ruflkvsh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gt2nxqovzmd.html

[N07] 两数之和（返回下标）
来源：http://dali.gzhubu.top/Article/details/gt2ocipyqxg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xziqi.cn/Article/details/gt2zhbxooqm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xylfe.cn/Article/details/gt2enhcqkab.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhongyouzk.top/Article/details/gt2bhazoekc.html

TS:   // 手写 Map<string, number>
来源：http://dali.pengpengdd.cyou/Article/details/gt2kpqjjjlo.html

Java: // 手写 HashMap
来源：http://dali.zhongyouzk.top/Article/details/gt2dnvnhjlb.html

Go:   // 手写 map[int]int
来源：http://dali.xziqi.cn/Article/details/gt2mgnxrhrx.html

Ruby: // 手写 Hash
来源：http://dali.xylfe.cn/Article/details/gt2vfdnusxf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pengpengdd.cyou/Article/details/gt2kaduzjet.html

[N08] 生成全排列
来源：http://dali.jinqigufen.top/Article/details/gt2hhizsxsi.html

Py:   itertools.permutations(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2ztnhrogp.html

PHP:  // 手写递归交换
来源：http://dali.cqqwz.cn/Article/details/gt2hkuqngpe.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2odhlwprb.html

TS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2jtbwrobn.html

Java: // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gt2vrcducha.html

Go:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gt2gjqkquzv.html

Ruby: arr.permutation.to_a
来源：http://dali.kuanghao11.cn/Article/details/gt2rnzhyrof.html

C#:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gt2qsgmdbgf.html

[N09] 栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gt2jsuqfmxf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xinyue.icu/Article/details/gt2peltccvk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lnanyxys.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2duduwzrb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenjidiqi.icu/Article/details/gt2tygreyik.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fengsongda.top/Article/details/gt2bddkxzpb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xuanzx.com/Article/details/gt2qdfcvaaf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2moantdnz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj202588.top/Article/details/gt2kleqdaeu.html

[N10] 链表节点定义
来源：http://dali.smart0.xyz/Article/details/gt2jzmmyscv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhiwuduotai.top/Article/details/gt2bkhreolo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.haohaochexian.top/Article/details/gt2lunpldei.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.dashuyun.cn/Article/details/gt2ctscmuiv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zdqjudy.top/Article/details/gt2mmobwxib.html

Java: class Node { int v; Node next; }
来源：http://dali.andypj.xyz/Article/details/gt2jxgykmtx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.kuanghao11.cn/Article/details/gt2gkpwgmqv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.snrcjt.cn/Article/details/gt2eghgugkf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zdqjudy.top/Article/details/gt2gyoqfkos.html

[N11] 二叉树中序遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ionhensx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shuidangran.top/Article/details/gt2knsawmrq.html

PHP:  // 手写递归函数
来源：http://dali.ivvv.top/Article/details/gt2dqqwduim.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gt2jyhgzkrl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gt2ezbodjah.html

Java: // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gt2ckobovlq.html

Go:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gt2aeswbczt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yangfankeji.com/Article/details/gt2tljcpsbv.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlkjuwo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xylfe.cn/Article/details/gt2rtztzmsn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gotoacloud.top/Article/details/gt2oawczubn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sxryk.cn/Article/details/gt2bqsmchzx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gt2thgggrap.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gt2avxhyvbd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gt2cicwjfyi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yuanzhike.top/Article/details/gt2yxmphigm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.316326.xyz/Article/details/gt2ujvdhehi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gt2qusfqinb.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2ercdcvyx.html

O. 并发与异步
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nqxugmwb.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2nxgxztkg.html

[O01] 启动一个线程
来源：http://dali.xinyue.icu/Article/details/gt2eonjaigg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sxryk.cn/Article/details/gt2ohkmpvnu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2trrluttw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxinkj.top/Article/details/gt2enxhnthj.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gt2aoaxuccz.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lmlwgatn.html

Go:   go f()
来源：http://dali.hywenlv.cn/Article/details/gt2mrckkbdm.html

Ruby: Thread.new { f }
来源：http://dali.jlsjyb.cn/Article/details/gt2eeadghmq.html

C#:   Task.Run(() => F());
来源：http://dali.cashguo.top/Article/details/gt2lxznvifn.html

[O02] 使用线程池
来源：http://dali.zhongyouzk.top/Article/details/gt2owwxrtdi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mzinwfpe.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xylfe.cn/Article/details/gt2ifakqvwr.html

JS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gt2lrjwxvjk.html

TS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uvmnnkhb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tian-w.cn/Article/details/gt2idlwihas.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daria6918.cn/Article/details/gt2oyumyozr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zdqjudy.top/Article/details/gt2afttnvaw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jyoumei.cn/Article/details/gt2mlscgbfg.html

[O03] 加锁保护共享数据
来源：http://dali.nanxinkj.top/Article/details/gt2qfggoccy.html

Py:   with lock: shared += 1
来源：http://dali.9152youxi.cn/Article/details/gt2qgpwwkhh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgfzy.top/Article/details/gt2boobtywn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnxiangtu.top/Article/details/gt2bpmfzulx.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2titayhcr.html

Java: synchronized (this) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gt2wwqbqizj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shuidangran.top/Article/details/gt2qgwpzwsh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuanzx.com/Article/details/gt2znrxopcb.html

C#:   lock (gate) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gt2fhfxpsji.html

[O04] 定义异步函数并等待
来源：http://dali.zhiwuduotai.top/Article/details/gt2rqevatlv.html

Py:   async def f():⏎    await g()
来源：http://dali.ppjwa.cn/Article/details/gt2vqoxfwgm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gogol.net.cn/Article/details/gt2sxbqfjxq.html

JS:   async function f() { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gt2zxkeuppf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zycfv.cn/Article/details/gt2ukbodnfo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ybcxt.top/Article/details/gt2fxnolypw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gotoacloud.top/Article/details/gt2vceaiesb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zdqjudy.top/Article/details/gt2zmdiwnhj.html

C#:   async Task F() { await G(); }
来源：http://dali.andypj.xyz/Article/details/gt2onetirxu.html

[O05] 并发执行并等待全部完成
来源：http://dali.0kj1m.cn/Article/details/gt2nkykqtxu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jyoumei.cn/Article/details/gt2guqworqe.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tianlin.xyz/Article/details/gt2agnejqlz.html

JS:   await Promise.all(tasks)
来源：http://dali.svipenyu.cn/Article/details/gt2jdmmdnob.html

TS:   await Promise.all(tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pldmenmq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ppjwa.cn/Article/details/gt2sazifwwn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nanxinkj.top/Article/details/gt2kcpioumc.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258.top/Article/details/gt2dnxlqrak.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj202588.top/Article/details/gt2cqxcvdwu.html

[O06] 使用进程池
来源：http://dali.yj202588.top/Article/details/gt2jenrjdou.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258.top/Article/details/gt2nxffqvyd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.0kj1m.cn/Article/details/gt2waxplohu.html

JS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gt2dqqznaam.html


<!-- 参考信息 -->