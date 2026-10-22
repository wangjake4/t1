代发 wailian999

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cdnleiting.top/Article/details/gt2emwmduos.html

JS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gt2jsqtwtmx.html

TS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gt2qmodhcok.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.quarkkingdee.top/Article/details/gt2zajrnjba.html

Go:   resp, err := http.Get(url)
来源：http://dali.birdmap.top/Article/details/gt2eyfhtjnr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gt2ijtufocx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.andypj.xyz/Article/details/gt2ghjsrxfo.html

[L02] 发送 POST JSON
来源：http://dali.sysykeji.top/Article/details/gt2mogtkphb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tian-w.cn/Article/details/gt2lcswirwh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dashuyun.cn/Article/details/gt2utzznxsy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gt2kulpzcdm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gt2ikwhrvyo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuanzhike.top/Article/details/gt2vswysekn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.feifeiyinyue.top/Article/details/gt2knoglfxx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.haohaochexian.top/Article/details/gt2yixxeeyf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.havefunace.top/Article/details/gt2ppyaukks.html

[L03] 设置自定义请求头
来源：http://dali.fengsongda.top/Article/details/gt2gesjvwxa.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cheryme.top/Article/details/gt2befujhso.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.iojbl.cn/Article/details/gt2okntrdvv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gt2eqogsbuf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gt2kpknqmil.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yonumen.top/Article/details/gt2lfqiyhzl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gt2xdtpllxm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258888.top/Article/details/gt2zmbvfznj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gt2wvonvxlb.html

[L04] 设置超时
来源：http://dali.fzhhl.top/Article/details/gt2bgbqkbhv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gaohongyu789.top/Article/details/gt2xpnfbhkw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.9152youxi.cn/Article/details/gt2xyyyjhzp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gt2bxxdsspk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gt2giodhvvn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dianchejie.cn/Article/details/gt2ezieucgs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sufxvd.cn/Article/details/gt2nbamokvy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ivvv.top/Article/details/gt2uqtpzktr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pengpengdd.cyou/Article/details/gt2wtddvfez.html

[L05] 上传文件（multipart）
来源：http://dali.redwolf501.top/Article/details/gt2ubbjmqrl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pycfn.com/Article/details/gt2xszzdqvu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tianlin.xyz/Article/details/gt2ykzapgxt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gt2umrxurkt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cdnleiting.top/Article/details/gt2neutuhog.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shuidangran.top/Article/details/gt2dtdljxaj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.mhx1999.top/Article/details/gt2jipivvgt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.andypj.xyz/Article/details/gt2hkklizeq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2osokjpla.html

[L06] 解析响应为 JSON
来源：http://dali.ivvv.top/Article/details/gt2fxsynzcb.html

Py:   resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2wvbcxrgi.html

PHP:  json_decode($body, true);
来源：http://dali.fengsongda.top/Article/details/gt2wiojjjlr.html

JS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gt2rnmxmfel.html

TS:   await resp.json()
来源：http://dali.yueranfly.top/Article/details/gt2fobqcbyd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nwbrower.top/Article/details/gt2extemlig.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xziqi.cn/Article/details/gt2mjfsszmv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sysykeji.top/Article/details/gt2aznurstb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sxryk.cn/Article/details/gt2gaekgrvv.html

[L07] 处理 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gt2srzijkvv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.c1oappe.top/Article/details/gt2ssjqhglp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.birdmap.top/Article/details/gt2honmkygf.html

JS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gt2fraebqbq.html

TS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gt2enxhbsfb.html

Java: resp.statusCode()
来源：http://dali.iojbl.cn/Article/details/gt2vwqupqvq.html

Go:   resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gt2prnsnwnx.html

Ruby: resp.code.to_i
来源：http://dali.sysykeji.top/Article/details/gt2tuxwglbd.html

C#:   (int)resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gt2yayjesyv.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrcntuv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xylfe.cn/Article/details/gt2lusnafoh.html

PHP:  curl_multi_init() 系列
来源：http://dali.fengsongda.top/Article/details/gt2bkxtxoae.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gt2obwtsdxs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gt2gsentuia.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2etobdgsx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ppjwa.cn/Article/details/gt2uwulpajj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuxming.cn/Article/details/gt2usiyszfp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.birdmap.top/Article/details/gt2jgthekua.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2wleysxea.html

M. 命令行 / 进程 / 环境
来源：http://dali.yangfankeji.com/Article/details/gt2iybybcaq.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2deezzwcs.html

[M01] 读取命令行参数
来源：http://dali.guowangkeji.top/Article/details/gt2gumxwxye.html

Py:   sys.argv[1:]
来源：http://dali.shzxlz.cn/Article/details/gt2smtyutme.html

PHP:  $argv;  $argc;
来源：http://dali.andypj.xyz/Article/details/gt2vdeshunf.html

JS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gt2izjfhjhg.html

TS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gt2cpprwsdt.html

Java: args 数组（main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gt2hvvmctpa.html

Go:   os.Args[1:]
来源：http://dali.yj20258.top/Article/details/gt2chctlgyu.html

Ruby: ARGV
来源：http://dali.guowangkeji.top/Article/details/gt2cjcsszii.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cashguo.top/Article/details/gt2qxwiwkyz.html

[M02] 读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2nwbxdjcl.html

Py:   os.environ.get("HOME")
来源：http://dali.zycfv.cn/Article/details/gt2hvhhlrgl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gt2odqsytir.html

JS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gt2nssficaw.html

TS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dmrmvmhx.html

Java: System.getenv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gt2fwwzsrad.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tanke756.top/Article/details/gt2swaohgvz.html

Ruby: ENV["HOME"]
来源：http://dali.feifeiyinyue.top/Article/details/gt2tbsemgcx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.redwolf501.top/Article/details/gt2otrbgqrx.html

[M03] 执行外部命令
来源：http://dali.feifeiyinyue.top/Article/details/gt2qmokexym.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tqqnabhz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.316326.xyz/Article/details/gt2xjmhxmzt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gt2sihfdjka.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gt2eqvpdurm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.mhx1999.top/Article/details/gt2kojszeml.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.guannengcc.top/Article/details/gt2nqqfptuc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nshctmjk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.0kj1m.cn/Article/details/gt2dufmtloq.html

[M04] 获取当前工作目录
来源：http://dali.fengsongda.top/Article/details/gt2mrpuiwiz.html

Py:   os.getcwd()
来源：http://dali.svipenyu.cn/Article/details/gt2nofbxcxc.html

PHP:  getcwd();
来源：http://dali.cqqwz.cn/Article/details/gt2quzyckor.html

JS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sfngdysg.html

TS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gt2gxxfusgy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.fzhhl.top/Article/details/gt2kuishhcz.html

Go:   os.Getwd()
来源：http://dali.sweek.top/Article/details/gt2nvtdwsot.html

Ruby: Dir.pwd
来源：http://dali.pycfn.com/Article/details/gt2geoaoymn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nwbrower.top/Article/details/gt2fpjnsjie.html

[M05] 设置退出码
来源：http://dali.316326.xyz/Article/details/gt2basnibzd.html

Py:   sys.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2rmupttro.html

PHP:  exit(1);
来源：http://dali.gzhubu.top/Article/details/gt2xyrlgesr.html

JS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iucztmpk.html

TS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2hahovbub.html

Java: System.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2njnzmnmq.html

Go:   os.Exit(1)
来源：http://dali.nwbrower.top/Article/details/gt2prayvotm.html

Ruby: exit 1
来源：http://dali.cucudq.cn/Article/details/gt2bgvdvcom.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hfpthk.cn/Article/details/gt2kmkuijnx.html

[M06] 向标准错误输出
来源：http://dali.ehwqpu.com/Article/details/gt2kuvhdzih.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nqtsurch.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.redwolf501.top/Article/details/gt2bhuepndj.html

JS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gt2yvfjmztz.html

TS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gt2ggccocrd.html

Java: System.err.println("err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2dhjtakew.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgfzy.top/Article/details/gt2uasscouf.html

Ruby: warn "err"
来源：http://dali.yj20258.top/Article/details/gt2hnmyqhcj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jiagoushi.top/Article/details/gt2nwscpqjp.html

[M07] 判断是否为主入口
来源：http://dali.feifeiyinyue.top/Article/details/gt2jragzmej.html

Py:   if __name__ == "__main__":
来源：http://dali.quarkkingdee.top/Article/details/gt2btzwxulm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhongyouzk.top/Article/details/gt2ctjeeuny.html

JS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gt2rzqpdwzw.html

TS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gt2dkkukiak.html

Java: public static void main(String[] args)
来源：http://dali.yuxming.cn/Article/details/gt2aicvsjyc.html

Go:   func main()
来源：http://dali.sweek.top/Article/details/gt2mqmublcq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.snrcjt.cn/Article/details/gt2ltwqvzoy.html

C#:   static void Main(string[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gt2scyxikcp.html

[M08] 获取系统与运行时信息
来源：http://dali.chenzaomai.com/Article/details/gt2sqksxzpo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yonumen.top/Article/details/gt2osffrvyw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigufen.top/Article/details/gt2xcdclgqw.html

JS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gt2mwnamctj.html

TS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gt2joozrrsi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hammf.cn/Article/details/gt2udeasezr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yonumen.top/Article/details/gt2zdtzivnv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shangyingyoupin.top/Article/details/gt2wcuomcfq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.316326.xyz/Article/details/gt2zndqcvpk.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2ccjqpkrl.html

N. 数据结构与算法
来源：http://dali.hongshengwenyu.top/Article/details/gt2gxdkfnqm.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2imtgrimn.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258.top/Article/details/gt2lbviltor.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2aommmcna.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mfekfaww.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gt2tnsnxxrw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gt2rcddwphe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gt2plksumxu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2ggxatezg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ppjwa.cn/Article/details/gt2arjjecvk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gt2lvzpciuc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangdashe.top/Article/details/gt2jguddpmh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gt2nwvjhmvn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gt2folqthgt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gt2hrfclrqd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gt2xjrhgcwa.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yongpay.top/Article/details/gt2nhwqjouy.html

Go:   slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2jmxtmjyk.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gt2jgfsybum.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zycfv.cn/Article/details/gt2qykxpmkj.html

[N03] 快速排序（分治示例）
来源：http://dali.daxiang520.top/Article/details/gt2igiedxqa.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hammf.cn/Article/details/gt2qxuiiufm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuxming.cn/Article/details/gt2qgpzxjlr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.smart0.xyz/Article/details/gt2popasdac.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gt2gkirlxte.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.pycfn.com/Article/details/gt2slpjgmyl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jyoumei.cn/Article/details/gt2neadgozd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ybcxt.top/Article/details/gt2crbmvyhz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.c1oappe.top/Article/details/gt2tliqfhbf.html

[N04] 斐波那契数列
来源：http://dali.dashuyun.cn/Article/details/gt2xxarxccy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gt2qtyrgrrq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhixingplan.top/Article/details/gt2icpkmumu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gt2qffchkwq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gt2iutacbsa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cashguo.top/Article/details/gt2krivoueu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hfpthk.cn/Article/details/gt2ftpzmppd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2ljkhpzmu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2wevohitc.html

[N05] 最大公约数
来源：http://dali.hammf.cn/Article/details/gt2twrqnwrc.html

Py:   math.gcd(a, b)
来源：http://dali.guannengcc.top/Article/details/gt2qroqivoa.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.svipenyu.cn/Article/details/gt2moktknpm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ivvv.top/Article/details/gt2peozczqe.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdnfacb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hywenlv.cn/Article/details/gt2jkysfrsa.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.9152youxi.cn/Article/details/gt2vbsfgfkq.html

Ruby: a.gcd(b)
来源：http://dali.fengsongda.top/Article/details/gt2alfubvzo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2caarjymi.html

[N06] 判断回文字符串
来源：http://dali.cheryme.top/Article/details/gt2fshcrgae.html

Py:   s == s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gt2fwtqjcyo.html

PHP:  $s === strrev($s);
来源：http://dali.hammf.cn/Article/details/gt2rlugiokk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gt2elsyiqgh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gt2iscieovy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yangfankeji.com/Article/details/gt2qbjhzpdi.html

Go:   // 双指针从两端比较
来源：http://dali.sufxvd.cn/Article/details/gt2pjxogsjd.html

Ruby: s == s.reverse
来源：http://dali.ehwqpu.com/Article/details/gt2dfskkmgb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxoufiw.html

[N07] 两数之和（返回下标）
来源：http://dali.daria6918.cn/Article/details/gt2wvlvpcty.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cdnleiting.top/Article/details/gt2vnknowrp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.havefunace.top/Article/details/gt2oiovwymv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yangfankeji.com/Article/details/gt2iiibnejs.html

TS:   // 手写 Map<string, number>
来源：http://dali.sysykeji.top/Article/details/gt2lclzqlld.html

Java: // 手写 HashMap
来源：http://dali.shangyingyoupin.top/Article/details/gt2eksvlmec.html

Go:   // 手写 map[int]int
来源：http://dali.mhx1999.top/Article/details/gt2ltuzxwgm.html

Ruby: // 手写 Hash
来源：http://dali.gzhubu.top/Article/details/gt2njfkwcfs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jiagoushi.top/Article/details/gt2ncswagea.html

[N08] 生成全排列
来源：http://dali.sxryk.cn/Article/details/gt2yvosohbc.html

Py:   itertools.permutations(arr)
来源：http://dali.nwbrower.top/Article/details/gt2ijsvlbxu.html

PHP:  // 手写递归交换
来源：http://dali.sufxvd.cn/Article/details/gt2fnvnfmbg.html

JS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gt2bhoncubm.html

TS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2fovkyarx.html

Java: // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gt2ubiprlcn.html

Go:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2xtmrmwkb.html

Ruby: arr.permutation.to_a
来源：http://dali.fengsongda.top/Article/details/gt2qmcvapns.html

C#:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2wfdxyvqy.html

[N09] 栈与队列
来源：http://dali.cdnleiting.top/Article/details/gt2yaptohnd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ppjwa.cn/Article/details/gt2lhypcdai.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gt2fncxuysi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gt2jbtpqmkj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.9152youxi.cn/Article/details/gt2hbhldmea.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gt2tyuelihc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aizwys.cn/Article/details/gt2wvmrzvrx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gt2hmasqqdy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yanxiufei.cn/Article/details/gt2fcoisreo.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lhkeuahm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pycfn.com/Article/details/gt2qczemexz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhoulong.xyz/Article/details/gt2stxqltjp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jyoumei.cn/Article/details/gt2vxydprrh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258888.top/Article/details/gt2cgqvbnhq.html

Java: class Node { int v; Node next; }
来源：http://dali.chenzaomai.com/Article/details/gt2ovrdqncj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhixingplan.top/Article/details/gt2qrtwgyyv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.quarkkingdee.top/Article/details/gt2sumxstqr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hammf.cn/Article/details/gt2xwufwutt.html

[N11] 二叉树中序遍历
来源：http://dali.yvedp.cn/Article/details/gt2jjkzqnaj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhongyouzk.top/Article/details/gt2hkmcewcv.html

PHP:  // 手写递归函数
来源：http://dali.shuidangran.top/Article/details/gt2jwewdkle.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuanzx.com/Article/details/gt2rlvrwvug.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gt2rejsjeua.html

Java: // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gt2wrgctmsi.html

Go:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gt2qxyusleh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aibaodan.cn/Article/details/gt2hgrwiqqb.html

C#:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gt2ftqcddgf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ybcxt.top/Article/details/gt2rallrxtz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fzhhl.top/Article/details/gt2idttfnqx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigufen.top/Article/details/gt2uanakvpb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gt2okwritcm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hysaishi.cn/Article/details/gt2yqfhhajm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gt2vcofxnyn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shuidangran.top/Article/details/gt2ufhzsjeb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lylnwsvl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.9152youxi.cn/Article/details/gt2djbniocp.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2elzwblju.html

O. 并发与异步
来源：http://dali.yangfankeji.com/Article/details/gt2avhrmdkc.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2jydqztfd.html

[O01] 启动一个线程
来源：http://dali.hfpthk.cn/Article/details/gt2pesbwpbm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.guannengcc.top/Article/details/gt2zoikpmmj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hywenlv.cn/Article/details/gt2djgwbemg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.316326.xyz/Article/details/gt2nbcrsect.html

TS:   // 同 JS
来源：http://dali.yonumen.top/Article/details/gt2taeijsjg.html

Java: new Thread(() -> f()).start()
来源：http://dali.jianghu66.top/Article/details/gt2jlhrmdxd.html

Go:   go f()
来源：http://dali.zhixingplan.top/Article/details/gt2tpqkrzbt.html

Ruby: Thread.new { f }
来源：http://dali.cashguo.top/Article/details/gt2cdcvfgvp.html

C#:   Task.Run(() => F());
来源：http://dali.yj202588.top/Article/details/gt2saeqwmsa.html

[O02] 使用线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xsmywwsz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cashguo.top/Article/details/gt2ryxbudod.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258888.top/Article/details/gt2wmeaqhmq.html

JS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gt2qguaaikz.html

TS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gt2wsouihxh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guowangkeji.top/Article/details/gt2iwgigbit.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yangfankeji.com/Article/details/gt2fwkgotvc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aibaodan.cn/Article/details/gt2jvvxmcmr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shangyingyoupin.top/Article/details/gt2jpjtmjwd.html

[O03] 加锁保护共享数据
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2azhketev.html

Py:   with lock: shared += 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qidynsez.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinghuilouyu.cn/Article/details/gt2plnqixss.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fzhhl.top/Article/details/gt2qnsggixn.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gt2asrjbdsj.html

Java: synchronized (this) { shared++; }
来源：http://dali.sweek.top/Article/details/gt2yyadvwux.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fzhhl.top/Article/details/gt2reskdscq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shuidangran.top/Article/details/gt2tbjduwjk.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gmqeokfa.html

[O04] 定义异步函数并等待
来源：http://dali.ivvv.top/Article/details/gt2nmrmnqgh.html

Py:   async def f():⏎    await g()
来源：http://dali.kuanghao11.cn/Article/details/gt2bnctmjpl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nwbrower.top/Article/details/gt2engmbalb.html

JS:   async function f() { await g(); }
来源：http://dali.cucudq.cn/Article/details/gt2pgiisqwq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gzhubu.top/Article/details/gt2sgxenjra.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.snrcjt.cn/Article/details/gt2gwklxqpu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yueranfly.top/Article/details/gt2vcuqpcsx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj202588.top/Article/details/gt2gxunyptv.html

C#:   async Task F() { await G(); }
来源：http://dali.yvedp.cn/Article/details/gt2kfifyanv.html

[O05] 并发执行并等待全部完成
来源：http://dali.ydzc1.top/Article/details/gt2ikhkifoo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yuanzhike.top/Article/details/gt2aiwaacjx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.mhx1999.top/Article/details/gt2iigwbnip.html

JS:   await Promise.all(tasks)
来源：http://dali.cashguo.top/Article/details/gt2zalisgua.html

TS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ncbxbtrp.html


<!-- 参考信息 -->