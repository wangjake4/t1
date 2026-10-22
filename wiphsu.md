代发 wailian999

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gt2mxchdxuw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.quarkkingdee.top/Article/details/gt2qrrujlei.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gt2irhursag.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dianchejie.cn/Article/details/gt2hwyokyiv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.feifeiyinyue.top/Article/details/gt2zzwgezif.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.feifeiyinyue.top/Article/details/gt2gxmivhxr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2euawkevt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jianghu66.top/Article/details/gt2mbnwtlbj.html

[L03] 设置自定义请求头
来源：http://dali.jinqigufen.top/Article/details/gt2xvkrcllf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hongshengwenyu.top/Article/details/gt2efxhasjs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guannengcc.top/Article/details/gt2vubqlott.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gt2eiauqlgh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gt2tkamwpcw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cashguo.top/Article/details/gt2daoznnqr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hkyrxxya.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yonumen.top/Article/details/gt2xzjxgefx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gt2frfgmrop.html

[L04] 设置超时
来源：http://dali.zdqjudy.top/Article/details/gt2jvviytuk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.daxiang520.top/Article/details/gt2vdaaicck.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xinyue.icu/Article/details/gt2roubzvoy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2xvezaxzv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gt2fwxaylvk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.bjfxy.top/Article/details/gt2dregpope.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.haohaochexian.top/Article/details/gt2ifvyvuaj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dashuyun.cn/Article/details/gt2djfkaqpt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenzaomai.com/Article/details/gt2phusxyun.html

[L05] 上传文件（multipart）
来源：http://dali.shangyingyoupin.top/Article/details/gt2idxxbves.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ppjwa.cn/Article/details/gt2yhagqdyk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sxryk.cn/Article/details/gt2eksecgtt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gt2zqnypevk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uexugcla.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.quarkkingdee.top/Article/details/gt2guzgmfwr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuanzhike.top/Article/details/gt2urrfquyy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigufen.top/Article/details/gt2gfaudzso.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rgfltjhv.html

[L06] 解析响应为 JSON
来源：http://dali.xuanzx.com/Article/details/gt2ilkdsiof.html

Py:   resp.json()
来源：http://dali.xuanzx.com/Article/details/gt2bfcvtuqu.html

PHP:  json_decode($body, true);
来源：http://dali.chenlongwang.top/Article/details/gt2qmzaobnq.html

JS:   await resp.json()
来源：http://dali.chenlongwang.top/Article/details/gt2egtorzmp.html

TS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gt2uczyskwa.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sysykeji.top/Article/details/gt2kfkuzlhf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hywenlv.cn/Article/details/gt2ykvhqqxu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jneyzdni.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.kuanghao11.cn/Article/details/gt2hgglffcc.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gt2nauzubib.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yanxiufei.cn/Article/details/gt2vlcdqjiz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sxryk.cn/Article/details/gt2jdninljd.html

JS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gt2sravwpgs.html

TS:   resp.ok;  resp.status
来源：http://dali.hnqzz.top/Article/details/gt2bnzdlvec.html

Java: resp.statusCode()
来源：http://dali.fzhhl.top/Article/details/gt2nkxatavr.html

Go:   resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gt2brznvuwj.html

Ruby: resp.code.to_i
来源：http://dali.jianghu66.top/Article/details/gt2brghvina.html

C#:   (int)resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gt2thccosah.html

[L08] 并发请求多个地址
来源：http://dali.ivvv.top/Article/details/gt2bnfhryhh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hywenlv.cn/Article/details/gt2sfpjtpmz.html

PHP:  curl_multi_init() 系列
来源：http://dali.yonumen.top/Article/details/gt2jypylcck.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gt2imwwsmbe.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gt2bwqiflnd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yueranfly.top/Article/details/gt2guwwpbfy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigufen.top/Article/details/gt2tiyvckuw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhengqikj.top/Article/details/gt2iujwvwmt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guannengcc.top/Article/details/gt2iigviegi.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2shdzjtje.html

M. 命令行 / 进程 / 环境
来源：http://dali.sxryk.cn/Article/details/gt2ftewlvbz.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2ounxjshr.html

[M01] 读取命令行参数
来源：http://dali.sysykeji.top/Article/details/gt2dqpvoibq.html

Py:   sys.argv[1:]
来源：http://dali.xinyue.icu/Article/details/gt2nmksjixr.html

PHP:  $argv;  $argc;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zcnsiywz.html

JS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjxxdnaf.html

TS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gt2diufvdcf.html

Java: args 数组（main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gt2oqkkwula.html

Go:   os.Args[1:]
来源：http://dali.fzhhl.top/Article/details/gt2btlhugyu.html

Ruby: ARGV
来源：http://dali.yueranfly.top/Article/details/gt2zbejcsvn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fzhhl.top/Article/details/gt2tnojvwgd.html

[M02] 读取环境变量
来源：http://dali.c1oappe.top/Article/details/gt2ofxvmqkn.html

Py:   os.environ.get("HOME")
来源：http://dali.birdmap.top/Article/details/gt2jqvwaplb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.meibo888.top/Article/details/gt2ddrkafti.html

JS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gt2pfxrarrj.html

TS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gt2hzhqwgqs.html

Java: System.getenv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gt2aohkkznx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sxryk.cn/Article/details/gt2uhhxnjak.html

Ruby: ENV["HOME"]
来源：http://dali.svipenyu.cn/Article/details/gt2ekmtqhnt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gt2nqttiisk.html

[M03] 执行外部命令
来源：http://dali.jlsjyb.cn/Article/details/gt2czqksvdn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvjxbcnc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jiagoushi.top/Article/details/gt2ygfblfze.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gt2jzgskhvn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gt2jmgonoyc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.redwolf501.top/Article/details/gt2qnrltxhc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aibaodan.cn/Article/details/gt2laoksykp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.andypj.xyz/Article/details/gt2sjelcpnd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2krftehhw.html

[M04] 获取当前工作目录
来源：http://dali.fzhhl.top/Article/details/gt2wlaznioa.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oapgzrvd.html

PHP:  getcwd();
来源：http://dali.daxiang520.top/Article/details/gt2erysebsx.html

JS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gt2ndlpcrgc.html

TS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gt2odpudzcn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuanzx.com/Article/details/gt2ifdklvdt.html

Go:   os.Getwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2jnsesqrr.html

Ruby: Dir.pwd
来源：http://dali.wangdashe.top/Article/details/gt2iswniuhs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fzhhl.top/Article/details/gt2dlleezsp.html

[M05] 设置退出码
来源：http://dali.chenzaomai.com/Article/details/gt2quieifzo.html

Py:   sys.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2gupuwzkz.html

PHP:  exit(1);
来源：http://dali.9152youxi.cn/Article/details/gt2idcqbzsl.html

JS:   process.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2znaulupp.html

TS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2xugkcwzc.html

Java: System.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2nbdlcsef.html

Go:   os.Exit(1)
来源：http://dali.guowangkeji.top/Article/details/gt2mebnjpsv.html

Ruby: exit 1
来源：http://dali.yvedp.cn/Article/details/gt2sxwxaumi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhoulong.xyz/Article/details/gt2fkewrqpp.html

[M06] 向标准错误输出
来源：http://dali.zhongyouzk.top/Article/details/gt2brgnxpht.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gt2bnzxjdyr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhongyouzk.top/Article/details/gt2zjftflzn.html

JS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gt2usrhhlne.html

TS:   console.error("err")
来源：http://dali.nanxinkj.top/Article/details/gt2pqhhlwer.html

Java: System.err.println("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zyzhhbju.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.316326.xyz/Article/details/gt2mnhulxxt.html

Ruby: warn "err"
来源：http://dali.gzhubu.top/Article/details/gt2plqnwhvz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pycfn.com/Article/details/gt2sphjpgjp.html

[M07] 判断是否为主入口
来源：http://dali.gogol.net.cn/Article/details/gt2rncblfyj.html

Py:   if __name__ == "__main__":
来源：http://dali.316326.xyz/Article/details/gt2rimtvskf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnxiangtu.top/Article/details/gt2upphtabs.html

JS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gt2afxmqlnr.html

TS:   require.main === module
来源：http://dali.havefunace.top/Article/details/gt2jvdvdzea.html

Java: public static void main(String[] args)
来源：http://dali.cucudq.cn/Article/details/gt2oyannjlm.html

Go:   func main()
来源：http://dali.nanxinkj.top/Article/details/gt2mwprnwhm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dashuyun.cn/Article/details/gt2azwpfnqr.html

C#:   static void Main(string[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tctgrubz.html

[M08] 获取系统与运行时信息
来源：http://dali.smart0.xyz/Article/details/gt2eqtlltgn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yanxiufei.cn/Article/details/gt2lblfplyg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxinkj.top/Article/details/gt2wtrfcmtl.html

JS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gt2dgkemdpd.html

TS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gt2dxmxxena.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.havefunace.top/Article/details/gt2fajtkxfv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.meibo888.top/Article/details/gt2kjkezoke.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.havefunace.top/Article/details/gt2ygmceeod.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fengsongda.top/Article/details/gt2mjbitgpe.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2lxgfpaqr.html

N. 数据结构与算法
来源：http://dali.tanke756.top/Article/details/gt2spwbcpui.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2sgqvdjgn.html

[N01] 二分查找（有序数组）
来源：http://dali.ybcxt.top/Article/details/gt2veivahef.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2vecmtzow.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.9152youxi.cn/Article/details/gt2abehykir.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gt2lrredlmd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gt2nnifcozz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2xgfmtcwv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2uxqrlwuq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jianghu66.top/Article/details/gt2mehqckgd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2thyvbvfi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jbxzjtwy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xylfe.cn/Article/details/gt2asedzknx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.havefunace.top/Article/details/gt2lidpxmwf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gt2oufpnnoq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gt2njulkgvl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.9152youxi.cn/Article/details/gt2qemrglmu.html

Go:   slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2urzysldn.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qhiozoll.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yuxming.cn/Article/details/gt2dqcjdqni.html

[N03] 快速排序（分治示例）
来源：http://dali.smart0.xyz/Article/details/gt2eyecxbrc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhengqikj.top/Article/details/gt2banmghgv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhiwuduotai.top/Article/details/gt2wwwrvsyn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gt2udvmsazi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gt2xmkvfgyd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnqzz.top/Article/details/gt2iccbeqpc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuanzhike.top/Article/details/gt2yotoggpf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rglhjxwd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hywenlv.cn/Article/details/gt2gkinxtuy.html

[N04] 斐波那契数列
来源：http://dali.fzhhl.top/Article/details/gt2qpazcuiq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gt2ivfbrskn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cashguo.top/Article/details/gt2vvxxlvnj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gt2qmsyclof.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gt2qqpwryxq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jyoumei.cn/Article/details/gt2ugwnuddu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sweek.top/Article/details/gt2ijskkoru.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ehwqpu.com/Article/details/gt2vuyplapk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sweek.top/Article/details/gt2bpzceawl.html

[N05] 最大公约数
来源：http://dali.gogol.net.cn/Article/details/gt2xszjpfih.html

Py:   math.gcd(a, b)
来源：http://dali.gogol.net.cn/Article/details/gt2cbelosnr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.smart0.xyz/Article/details/gt2pcszfvjr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gt2yqeuhxte.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gt2uqscxmxm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ybflpvan.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.svipenyu.cn/Article/details/gt2xsyihxma.html

Ruby: a.gcd(b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2exzyjtip.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fengsongda.top/Article/details/gt2uqbqorfl.html

[N06] 判断回文字符串
来源：http://dali.daxiang520.top/Article/details/gt2bgvfllvn.html

Py:   s == s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gt2mtcomytk.html

PHP:  $s === strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2zxpthjpa.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ojbjghcz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gt2hrwauggo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xylfe.cn/Article/details/gt2njaquhif.html

Go:   // 双指针从两端比较
来源：http://dali.yvedp.cn/Article/details/gt2jvwkwwyu.html

Ruby: s == s.reverse
来源：http://dali.zhixingplan.top/Article/details/gt2xqtqccnl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gt2vntgqjcq.html

[N07] 两数之和（返回下标）
来源：http://dali.jinqigfzy.top/Article/details/gt2zdoodfbh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qmjqbfxr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yonumen.top/Article/details/gt2kmkymiir.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daxiang520.top/Article/details/gt2zdmdkcpo.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258888.top/Article/details/gt2uxufgdpt.html

Java: // 手写 HashMap
来源：http://dali.bjfxy.top/Article/details/gt2gkzqeypa.html

Go:   // 手写 map[int]int
来源：http://dali.smart0.xyz/Article/details/gt2ajuxbanw.html

Ruby: // 手写 Hash
来源：http://dali.guowangkeji.top/Article/details/gt2ojtzlbqs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jyoumei.cn/Article/details/gt2zysimlfc.html

[N08] 生成全排列
来源：http://dali.fzhhl.top/Article/details/gt2mlhutcxr.html

Py:   itertools.permutations(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2eyxvcsha.html

PHP:  // 手写递归交换
来源：http://dali.tianlin.xyz/Article/details/gt2moghcslh.html

JS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gt2emgrjlla.html

TS:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gt2rrkypkmw.html

Java: // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2djvubuub.html

Go:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2mzsoqikc.html

Ruby: arr.permutation.to_a
来源：http://dali.sufxvd.cn/Article/details/gt2zhlhsnnq.html

C#:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gt2vlxbhtov.html

[N09] 栈与队列
来源：http://dali.hammf.cn/Article/details/gt2ylcwnbdn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.andypj.xyz/Article/details/gt2dsexlsbu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gzhubu.top/Article/details/gt2tyegwjlr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fzhhl.top/Article/details/gt2vicjlnsr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tanke756.top/Article/details/gt2afqmyjmu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.9152youxi.cn/Article/details/gt2zvvxqhfw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigfzy.top/Article/details/gt2tkgjtkij.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gt2jzskvbhw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xinyue.icu/Article/details/gt2zzyfbyxq.html

[N10] 链表节点定义
来源：http://dali.ehwqpu.com/Article/details/gt2hafjkhhu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sxryk.cn/Article/details/gt2qnofayts.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nwbrower.top/Article/details/gt2sftrheav.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sufxvd.cn/Article/details/gt2teghszqp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yanxiufei.cn/Article/details/gt2rdhqdjhi.html

Java: class Node { int v; Node next; }
来源：http://dali.yvedp.cn/Article/details/gt2cijidpyw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.dashuyun.cn/Article/details/gt2nzlcwvez.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shzxlz.cn/Article/details/gt2lwpfkxkp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.c1oappe.top/Article/details/gt2uamgqbvt.html

[N11] 二叉树中序遍历
来源：http://dali.jqgfzy.top/Article/details/gt2tmvxqivc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenzaomai.com/Article/details/gt2hvnfwybn.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gt2cgijudlf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gt2newyajge.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cheryme.top/Article/details/gt2ghlwlyfm.html

Java: // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gt2alrmjhvy.html

Go:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gt2yneoxarc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.dianchejie.cn/Article/details/gt2zgedqmbj.html

C#:   // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gt2wwwcfklp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.snrcjt.cn/Article/details/gt2jvjdmxke.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xylfe.cn/Article/details/gt2aiccihkx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jsuguzal.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gt2bkebicyx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zwenoqlu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jyoumei.cn/Article/details/gt2ytnbuejv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj202588.top/Article/details/gt2heyvohea.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.meibo888.top/Article/details/gt2rqyfjhza.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gt2omkcqtsx.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2wydcoghp.html

O. 并发与异步
来源：http://dali.gogol.net.cn/Article/details/gt2sstiuhmm.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2upaiewyk.html

[O01] 启动一个线程
来源：http://dali.yangfankeji.com/Article/details/gt2wxlgmxpc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xziqi.cn/Article/details/gt2odmpirxf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cqqwz.cn/Article/details/gt2pkvntyca.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daria6918.cn/Article/details/gt2banfexmv.html

TS:   // 同 JS
来源：http://dali.daria6918.cn/Article/details/gt2nohlkllt.html

Java: new Thread(() -> f()).start()
来源：http://dali.xuetiantiany.cn/Article/details/gt2npqtvlnp.html

Go:   go f()
来源：http://dali.xylfe.cn/Article/details/gt2ycfopzmq.html

Ruby: Thread.new { f }
来源：http://dali.gotoacloud.top/Article/details/gt2ficeezgn.html

C#:   Task.Run(() => F());
来源：http://dali.pengpengdd.cyou/Article/details/gt2hrctwfzr.html

[O02] 使用线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zjaekurb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sgpjwzhe.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ivvv.top/Article/details/gt2urmakxwf.html

JS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gt2kqohtwjj.html

TS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gt2gmyxlrqp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jianghu66.top/Article/details/gt2ttbhaccg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenlongwang.top/Article/details/gt2aplssvwa.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fzhhl.top/Article/details/gt2cbzfbdsa.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhiwuduotai.top/Article/details/gt2rhbrvfsq.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigufen.top/Article/details/gt2zaufopzg.html

Py:   with lock: shared += 1
来源：http://dali.chenzaomai.com/Article/details/gt2gjrbsrcw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuanzhike.top/Article/details/gt2oiqkksae.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yangfankeji.com/Article/details/gt2afzdvmme.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gt2rjitserz.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mkggjgci.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ehwqpu.com/Article/details/gt2jbtpbfco.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.316326.xyz/Article/details/gt2jhraklmj.html

C#:   lock (gate) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gt2lftqbdfh.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigfzy.top/Article/details/gt2mmexquvs.html

Py:   async def f():⏎    await g()
来源：http://dali.meibo888.top/Article/details/gt2jwsdisqf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jlsjyb.cn/Article/details/gt2fmdwheij.html

JS:   async function f() { await g(); }
来源：http://dali.yvedp.cn/Article/details/gt2zrekcjkm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hdsvcjzo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenzaomai.com/Article/details/gt2qgvhldqt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hnxiangtu.top/Article/details/gt2erpvdmgr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cqqwz.cn/Article/details/gt2albzofex.html

C#:   async Task F() { await G(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2kmkllpeq.html

[O05] 并发执行并等待全部完成
来源：http://dali.smart0.xyz/Article/details/gt2usszwdlf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.haohaochexian.top/Article/details/gt2krwsdzoz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yuanzhike.top/Article/details/gt2mxjycatp.html

JS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gt2apnrcvqi.html

TS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gt2ioiuobfq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnqzz.top/Article/details/gt2lnfkmogb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fzhhl.top/Article/details/gt2twazcmcq.html

Ruby: threads.map(&:join)
来源：http://dali.hammf.cn/Article/details/gt2ebmpajvx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.c1oappe.top/Article/details/gt2fuqayafp.html

[O06] 使用进程池
来源：http://dali.wangdashe.top/Article/details/gt2zoniosmz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yvedp.cn/Article/details/gt2xvtriddd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cqqwz.cn/Article/details/gt2douuwono.html

JS:   // child_process / cluster 模块
来源：http://dali.guannengcc.top/Article/details/gt2jifqqwup.html


<!-- 参考信息 -->