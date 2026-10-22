代发 wailian999

Py:   requests.post(url, json={"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gt2vpqhdxcm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhengqikj.top/Article/details/gt2udoesuzc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gt2omdffefy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gt2qkhlqfel.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ehwqpu.com/Article/details/gt2bkgqfyyx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.9152youxi.cn/Article/details/gt2lbiusdge.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sxryk.cn/Article/details/gt2revnjbbh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cashguo.top/Article/details/gt2qxqyprth.html

[L03] 设置自定义请求头
来源：http://dali.hfpthk.cn/Article/details/gt2mippnipb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sweek.top/Article/details/gt2qgxgyztp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2cgbptxtt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gt2jhovcuns.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gt2aninhdgd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gotoacloud.top/Article/details/gt2mgcbeizp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gt2ioejbmow.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.iojbl.cn/Article/details/gt2hwfqnpqd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gt2csvexmwx.html

[L04] 设置超时
来源：http://dali.yj20258888.top/Article/details/gt2zyhyzuek.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinqigufen.top/Article/details/gt2gvnhcoox.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hfpthk.cn/Article/details/gt2fnushkvp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gt2ncpautzd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gt2hzrpfiep.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuxming.cn/Article/details/gt2ktndsppp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuanzx.com/Article/details/gt2rrcwdfkm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sxryk.cn/Article/details/gt2mczrannh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gt2zeijhthd.html

[L05] 上传文件（multipart）
来源：http://dali.jqgufenzy.top/Article/details/gt2eenfkoal.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cucudq.cn/Article/details/gt2wgmgrtei.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yangfankeji.com/Article/details/gt2qvhmlpwh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gt2kbuqpkwt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uyzjsiuk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.quarkkingdee.top/Article/details/gt2inghbkhv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2lywlzqtu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cdnleiting.top/Article/details/gt2gfaxqmif.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sweek.top/Article/details/gt2ynycbhtg.html

[L06] 解析响应为 JSON
来源：http://dali.0kj1m.cn/Article/details/gt2cquxopmp.html

Py:   resp.json()
来源：http://dali.zdqjudy.top/Article/details/gt2tvyeoung.html

PHP:  json_decode($body, true);
来源：http://dali.havefunace.top/Article/details/gt2cesggjno.html

JS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gt2fyulmagy.html

TS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gt2irjvgras.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qxvanarp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hywenlv.cn/Article/details/gt2guekityp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuanzhike.top/Article/details/gt2khbnobfl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.smart0.xyz/Article/details/gt2oomxsuon.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gt2ywwnnocz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zycfv.cn/Article/details/gt2njkpoelc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2papikory.html

JS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gt2kvbbowwk.html

TS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gt2aahhnjob.html

Java: resp.statusCode()
来源：http://dali.cqqwz.cn/Article/details/gt2yitrcuey.html

Go:   resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tkcejojf.html

Ruby: resp.code.to_i
来源：http://dali.bjfxy.top/Article/details/gt2gpmpzxhd.html

C#:   (int)resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gt2lxmivakm.html

[L08] 并发请求多个地址
来源：http://dali.yanxiufei.cn/Article/details/gt2uqjdffnf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.birdmap.top/Article/details/gt2ndxqfgen.html

PHP:  curl_multi_init() 系列
来源：http://dali.yvedp.cn/Article/details/gt2vwlwrunb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gt2hpcpfbuq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gt2qorhmtof.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnxiangtu.top/Article/details/gt2ekpmbnfw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shuidangran.top/Article/details/gt2qgaiejcu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jyoumei.cn/Article/details/gt2sgfjusct.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhixingplan.top/Article/details/gt2kklzwjgi.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2euzorjnh.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhengqikj.top/Article/details/gt2emzjardl.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2bvqwtamu.html

[M01] 读取命令行参数
来源：http://dali.yongpay.top/Article/details/gt2jdmkxbev.html

Py:   sys.argv[1:]
来源：http://dali.shzxlz.cn/Article/details/gt2dapcfsmr.html

PHP:  $argv;  $argc;
来源：http://dali.gogol.net.cn/Article/details/gt2nrghfxxc.html

JS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gt2zvcolkxd.html

TS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gt2jpmssppi.html

Java: args 数组（main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gt2elxxvyol.html

Go:   os.Args[1:]
来源：http://dali.ehwqpu.com/Article/details/gt2gofjfvmx.html

Ruby: ARGV
来源：http://dali.cqqwz.cn/Article/details/gt2ltheikxm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gt2gvkglaxm.html

[M02] 读取环境变量
来源：http://dali.c1oappe.top/Article/details/gt2ztwyafez.html

Py:   os.environ.get("HOME")
来源：http://dali.dashuyun.cn/Article/details/gt2hrdvanki.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hammf.cn/Article/details/gt2pxovvuop.html

JS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gt2xszkjgid.html

TS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gt2mmqrpugh.html

Java: System.getenv("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2inmesiph.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuxming.cn/Article/details/gt2rukmcpxp.html

Ruby: ENV["HOME"]
来源：http://dali.quarkkingdee.top/Article/details/gt2lxibfumy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2nwdbyoce.html

[M03] 执行外部命令
来源：http://dali.iojbl.cn/Article/details/gt2ctsieohv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.feifeiyinyue.top/Article/details/gt2onnsnpgj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ehwqpu.com/Article/details/gt2zstbrtsl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigufen.top/Article/details/gt2kanzxehp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gt2ezlrvnaq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ezeiohkj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.quarkkingdee.top/Article/details/gt2qpqylaqs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shzxlz.cn/Article/details/gt2bpriudnj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guannengcc.top/Article/details/gt2vlnlytlf.html

[M04] 获取当前工作目录
来源：http://dali.xziqi.cn/Article/details/gt2earswxoj.html

Py:   os.getcwd()
来源：http://dali.nwbrower.top/Article/details/gt2oyfrscyx.html

PHP:  getcwd();
来源：http://dali.guowangkeji.top/Article/details/gt2igorrxkp.html

JS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gt2caplhmne.html

TS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gt2dcawdhns.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.andypj.xyz/Article/details/gt2omapqxrb.html

Go:   os.Getwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eifnjoxl.html

Ruby: Dir.pwd
来源：http://dali.shzxlz.cn/Article/details/gt2azkvlkcd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yueranfly.top/Article/details/gt2gqztekeb.html

[M05] 设置退出码
来源：http://dali.daria6918.cn/Article/details/gt2viyoacuj.html

Py:   sys.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2ojhplpyi.html

PHP:  exit(1);
来源：http://dali.zhiwuduotai.top/Article/details/gt2wyojsvtm.html

JS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2skiifwhv.html

TS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2mhfasrvs.html

Java: System.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2ddtvoiiu.html

Go:   os.Exit(1)
来源：http://dali.cheryme.top/Article/details/gt2xmwrqxhx.html

Ruby: exit 1
来源：http://dali.vqdsnc.cn/Article/details/gt2pcfwwqcs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.pengpengdd.cyou/Article/details/gt2mucjbndj.html

[M06] 向标准错误输出
来源：http://dali.aibaodan.cn/Article/details/gt2aqokqawt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gt2kggkfyrb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sweek.top/Article/details/gt2iszegmxy.html

JS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gt2dbmvcfvn.html

TS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gt2jaadldbp.html

Java: System.err.println("err")
来源：http://dali.ehwqpu.com/Article/details/gt2civeqkqg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.andypj.xyz/Article/details/gt2dllwzkux.html

Ruby: warn "err"
来源：http://dali.316326.xyz/Article/details/gt2zanqnbtz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2biygoobe.html

[M07] 判断是否为主入口
来源：http://dali.zhoulong.xyz/Article/details/gt2rtokvodw.html

Py:   if __name__ == "__main__":
来源：http://dali.haohaochexian.top/Article/details/gt2psrepnzd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pycfn.com/Article/details/gt2dgpvddpb.html

JS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gt2cfrijxbl.html

TS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gt2zlgmcocc.html

Java: public static void main(String[] args)
来源：http://dali.dianchejie.cn/Article/details/gt2yfdbnaqd.html

Go:   func main()
来源：http://dali.shangyingyoupin.top/Article/details/gt2hathbjja.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yvedp.cn/Article/details/gt2kbdtamuh.html

C#:   static void Main(string[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ghewbefq.html

[M08] 获取系统与运行时信息
来源：http://dali.yanxiufei.cn/Article/details/gt2scdbyygk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.birdmap.top/Article/details/gt2jkkbeqdv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.andypj.xyz/Article/details/gt2lkimgzub.html

JS:   process.platform;  process.version
来源：http://dali.ivvv.top/Article/details/gt2wcrgnzzl.html

TS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gt2vjyugppl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.feifeiyinyue.top/Article/details/gt2pkenycyr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuanzhike.top/Article/details/gt2trhjqoza.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hfpthk.cn/Article/details/gt2lkqaixzw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cheryme.top/Article/details/gt2dqscshoe.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2agkaxdkb.html

N. 数据结构与算法
来源：http://dali.cucudq.cn/Article/details/gt2rbpqlrvl.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2rqrhvxjn.html

[N01] 二分查找（有序数组）
来源：http://dali.hongshengwenyu.top/Article/details/gt2rmkojtkk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2hvtvovpi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gt2agqnewtv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gt2aitukyzt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gt2tnicmape.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gt2qftctduk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2yvddldme.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gvnleisg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tzjfvaaj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yvedp.cn/Article/details/gt2qxqihrjg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gt2qdhgkvsb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gt2llsqxwzn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gt2thrkzylc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gt2qwchqfrm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pddtymvo.html

Go:   slices.Sort(arr)
来源：http://dali.hammf.cn/Article/details/gt2zkdkpcmo.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gt2fjsauufc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ryfvxhva.html

[N03] 快速排序（分治示例）
来源：http://dali.xylfe.cn/Article/details/gt2ftqufdmb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jvlpcmnh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.kuanghao11.cn/Article/details/gt2nepoujqs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fengsongda.top/Article/details/gt2mjugqjny.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gt2xpzrzetg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hongshengwenyu.top/Article/details/gt2nutdtyoj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.meibo888.top/Article/details/gt2zspkuyga.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jlsjyb.cn/Article/details/gt2hifokprd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cqqwz.cn/Article/details/gt2dntnemsg.html

[N04] 斐波那契数列
来源：http://dali.birdmap.top/Article/details/gt2tyrswlpj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gt2ypennwdj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmdcndni.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gt2qaypsria.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mmxqvvgh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aizwys.cn/Article/details/gt2mvzjwymu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zwghgdup.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wwezgnum.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2fkfdowkt.html

[N05] 最大公约数
来源：http://dali.tian-w.cn/Article/details/gt2vezbiama.html

Py:   math.gcd(a, b)
来源：http://dali.xziqi.cn/Article/details/gt2qisirtmm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hysaishi.cn/Article/details/gt2xpjelynm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gt2gncvipbs.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gt2ohkwpsei.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.meibo888.top/Article/details/gt2gjprtqyp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cheryme.top/Article/details/gt2adhpjyzx.html

Ruby: a.gcd(b)
来源：http://dali.snrcjt.cn/Article/details/gt2kmukwccr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenlongwang.top/Article/details/gt2ywrgovct.html

[N06] 判断回文字符串
来源：http://dali.andypj.xyz/Article/details/gt2gnhvsolh.html

Py:   s == s[::-1]
来源：http://dali.sweek.top/Article/details/gt2oxxnepxw.html

PHP:  $s === strrev($s);
来源：http://dali.xylfe.cn/Article/details/gt2oqcxoiqw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gt2hkeyfxgh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gt2kvowowwj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hysaishi.cn/Article/details/gt2zxrqfsgz.html

Go:   // 双指针从两端比较
来源：http://dali.nanxinkj.top/Article/details/gt2fxxwqtmh.html

Ruby: s == s.reverse
来源：http://dali.yvedp.cn/Article/details/gt2tqgdkeof.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gt2hsrcwcxl.html

[N07] 两数之和（返回下标）
来源：http://dali.feifeiyinyue.top/Article/details/gt2nnrcezmj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.snrcjt.cn/Article/details/gt2untswpgt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.aibaodan.cn/Article/details/gt2knwguwhw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.havefunace.top/Article/details/gt2eqmreopb.html

TS:   // 手写 Map<string, number>
来源：http://dali.quarkkingdee.top/Article/details/gt2hladjkgv.html

Java: // 手写 HashMap
来源：http://dali.kuanghao11.cn/Article/details/gt2abpetult.html

Go:   // 手写 map[int]int
来源：http://dali.smart0.xyz/Article/details/gt2klulitxv.html

Ruby: // 手写 Hash
来源：http://dali.havefunace.top/Article/details/gt2mgjjpwit.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sxbvruhv.html

[N08] 生成全排列
来源：http://dali.pengpengdd.cyou/Article/details/gt2reoiqpnk.html

Py:   itertools.permutations(arr)
来源：http://dali.316326.xyz/Article/details/gt2wfjpusmr.html

PHP:  // 手写递归交换
来源：http://dali.ppjwa.cn/Article/details/gt2swsetdfr.html

JS:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gt2rbtngobl.html

TS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gt2vdsvxzrz.html

Java: // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gt2qxszjrqz.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2afzhqkwo.html

Ruby: arr.permutation.to_a
来源：http://dali.dianchejie.cn/Article/details/gt2xuubdlbl.html

C#:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2efljejfv.html

[N09] 栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2epggbhof.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenlongwang.top/Article/details/gt2humiuriz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nwbrower.top/Article/details/gt2pidnqgaq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gt2yliqtawo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gaohongyu789.top/Article/details/gt2hbfyomlf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guannengcc.top/Article/details/gt2lxmzemvv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fengsongda.top/Article/details/gt2mdmrgpii.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yxfjrhmr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj202588.top/Article/details/gt2kvfdcxlt.html

[N10] 链表节点定义
来源：http://dali.wangdashe.top/Article/details/gt2xwcvvulv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhengqikj.top/Article/details/gt2iojjhgmr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zdqjudy.top/Article/details/gt2cyjrccdo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bowbgxjz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hammf.cn/Article/details/gt2helmvcwl.html

Java: class Node { int v; Node next; }
来源：http://dali.c1oappe.top/Article/details/gt2xvdkzcjp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jyoumei.cn/Article/details/gt2iwdodviy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenlongwang.top/Article/details/gt2xwvzdysz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2dbyowksk.html

[N11] 二叉树中序遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2txtimegz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.wangshuangyany.cn/Article/details/gt2qsvtotxj.html

PHP:  // 手写递归函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2ndymvynb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gt2ckqajgmr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2auyuxlrx.html

Java: // 手写递归
来源：http://dali.redwolf501.top/Article/details/gt2vdbyfhvo.html

Go:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gt2jlqmucfr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.9152youxi.cn/Article/details/gt2ohkdixkg.html

C#:   // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2ooaurfcp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yonumen.top/Article/details/gt2zomxlniu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cheryme.top/Article/details/gt2ladbzemm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigfzy.top/Article/details/gt2qvkfxhvy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gt2lrbxvlme.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhixingplan.top/Article/details/gt2klbligvs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gt2jxtgjini.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shuidangran.top/Article/details/gt2pfgzevxr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.kuanghao11.cn/Article/details/gt2icsijbcz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gt2ysjtbsiv.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2jdsbiesq.html

O. 并发与异步
来源：http://dali.ybcxt.top/Article/details/gt2qbtpxsie.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qpiihucz.html

[O01] 启动一个线程
来源：http://dali.nanxinkj.top/Article/details/gt2jeohmhsq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yj20258888.top/Article/details/gt2jaliixzu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2iqhwzaio.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.redwolf501.top/Article/details/gt2iekloupz.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gt2bykrmwiw.html

Java: new Thread(() -> f()).start()
来源：http://dali.daria6918.cn/Article/details/gt2oshfcfqg.html

Go:   go f()
来源：http://dali.yanxiufei.cn/Article/details/gt2helzbnqb.html

Ruby: Thread.new { f }
来源：http://dali.ybcxt.top/Article/details/gt2bnjsmsdt.html

C#:   Task.Run(() => F());
来源：http://dali.andypj.xyz/Article/details/gt2dkbuasbd.html

[O02] 使用线程池
来源：http://dali.ehwqpu.com/Article/details/gt2efphmyak.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yangfankeji.com/Article/details/gt2asmspqwe.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.smart0.xyz/Article/details/gt2udxnoqef.html

JS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gt2rneuekcn.html

TS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gt2quictmbu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yteakzgw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cqqwz.cn/Article/details/gt2lmdblxta.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pengpengdd.cyou/Article/details/gt2xbzbiibu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgfzy.top/Article/details/gt2zgzhjucv.html

[O03] 加锁保护共享数据
来源：http://dali.nanxinkj.top/Article/details/gt2rdaictyv.html

Py:   with lock: shared += 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2cvcyifah.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jiagoushi.top/Article/details/gt2ufwvnlix.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xuetiantiany.cn/Article/details/gt2uxjeqnfn.html

TS:   // 同 JS
来源：http://dali.tian-w.cn/Article/details/gt2mcqqqycr.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxuanxn.top/Article/details/gt2tcbphilb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.quarkkingdee.top/Article/details/gt2qqeugnif.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guannengcc.top/Article/details/gt2ybnygift.html

C#:   lock (gate) { shared++; }
来源：http://dali.hywenlv.cn/Article/details/gt2mrtivani.html

[O04] 定义异步函数并等待
来源：http://dali.wangdashe.top/Article/details/gt2dyxckozz.html

Py:   async def f():⏎    await g()
来源：http://dali.shuidangran.top/Article/details/gt2uupewxjh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sxryk.cn/Article/details/gt2sdjbscde.html

JS:   async function f() { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gt2vvmqelat.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2blglcwdz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hongshengwenyu.top/Article/details/gt2rcnvlegw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cucudq.cn/Article/details/gt2fxmzlyjd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.feifeiyinyue.top/Article/details/gt2njofqdji.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2scoecwoj.html

[O05] 并发执行并等待全部完成
来源：http://dali.iojbl.cn/Article/details/gt2npipxgxf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rirrvren.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yangfankeji.com/Article/details/gt2jbtwoiom.html

JS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gt2hqagnnpt.html

TS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gt2jvelvsbe.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj202588.top/Article/details/gt2lsblmkqs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jianghu66.top/Article/details/gt2derhwgjm.html

Ruby: threads.map(&:join)
来源：http://dali.sufxvd.cn/Article/details/gt2kezrtvtg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jxtreegf.html

[O06] 使用进程池
来源：http://dali.feifeiyinyue.top/Article/details/gt2rmwvxgzi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.redwolf501.top/Article/details/gt2vnzckljb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj202588.top/Article/details/gt2medopnbj.html

JS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jjnnctwg.html


<!-- 参考信息 -->