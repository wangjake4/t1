代发 wailian999

L. 网络请求
来源：http://dali.cashguo.top/Article/details/gtmliklyuq.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtmlumyrwh.html

[L01] 发送 GET 请求
来源：http://dali.sufxvd.cn/Article/details/gtrmwbjsgk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.svipenyu.cn/Article/details/gtfiqlidgo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258888.top/Article/details/gtlyavcztt.html

JS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gtruuiqype.html

TS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gtbechtvzs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daxiang520.top/Article/details/gtagbyeeuv.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenzaomai.com/Article/details/gtncqidmlg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guowangkeji.top/Article/details/gtrofpvhdd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hysaishi.cn/Article/details/gtiposufht.html

[L02] 发送 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gtejinkpju.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gtvwjvprul.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.mhx1999.top/Article/details/gthzfzxtll.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gtuhakaatf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gtxskccgve.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedfiuccz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pycfn.com/Article/details/gtrekreryv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cqqwz.cn/Article/details/gtnogkloxl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuxming.cn/Article/details/gtkgxmkowk.html

[L03] 设置自定义请求头
来源：http://dali.ppjwa.cn/Article/details/gtpahtoqur.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zycfv.cn/Article/details/gtgkwyoqes.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtjuriocxo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gtbmvstsab.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gtdrgzljod.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shuidangran.top/Article/details/gtldxrkjid.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daxiang520.top/Article/details/gtixapssac.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgufenzy.top/Article/details/gtxpwuozei.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzlrxina.html

[L04] 设置超时
来源：http://dali.cqqwz.cn/Article/details/gtgyknahhq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yonumen.top/Article/details/gtosbniodv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258.top/Article/details/gtqhjdbeti.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gtefafwexq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gtiqezjtze.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yvedp.cn/Article/details/gtrxzurllf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cashguo.top/Article/details/gtocyclupa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zdqjudy.top/Article/details/gtfyjybuqf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cheryme.top/Article/details/gtcrarqzhl.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gtlhggbpix.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daria6918.cn/Article/details/gtigzbelfw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.snrcjt.cn/Article/details/gtillkshew.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gtnjxukxpa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gtocxiqzlc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenjidiqi.icu/Article/details/gtdzcideks.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yueranfly.top/Article/details/gtzbczlcmn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.wangshuangyany.cn/Article/details/gtbgtzhiea.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cucudq.cn/Article/details/gtfnewcnpy.html

[L06] 解析响应为 JSON
来源：http://dali.jiagoushi.top/Article/details/gtszbopiup.html

Py:   resp.json()
来源：http://dali.fzhhl.top/Article/details/gtpwazvziw.html

PHP:  json_decode($body, true);
来源：http://dali.tianlin.xyz/Article/details/gtzeqorqsc.html

JS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtgnnjympf.html

TS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gtixmqkihx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yongpay.top/Article/details/gtqeukoucf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gotoacloud.top/Article/details/gtlllrvkyj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hammf.cn/Article/details/gtletmkjry.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.birdmap.top/Article/details/gtbhmpuvjd.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gttagjryxd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tanke756.top/Article/details/gtglxmadgo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sxryk.cn/Article/details/gtsxmxrwqo.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gtaezdtwwl.html

TS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gtxspqjeol.html

Java: resp.statusCode()
来源：http://dali.feifeiyinyue.top/Article/details/gtkgqsfbwt.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqwykvhi.html

Ruby: resp.code.to_i
来源：http://dali.xziqi.cn/Article/details/gtxjqbiimt.html

C#:   (int)resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gtkhsscfpk.html

[L08] 并发请求多个地址
来源：http://dali.hfpthk.cn/Article/details/gtbzoyswtu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.meibo888.top/Article/details/gtoszamzkv.html

PHP:  curl_multi_init() 系列
来源：http://dali.ydzc1.top/Article/details/gtvuojdwvy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gtsxjtndau.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gtckspneyc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gtnjroyuuj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.mhx1999.top/Article/details/gtvatgdogg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hywenlv.cn/Article/details/gtwukqepaa.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258888.top/Article/details/gtekcqgeah.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtmmmzowxv.html

M. 命令行 / 进程 / 环境
来源：http://dali.xinyue.icu/Article/details/gthiyolsif.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtihepedjo.html

[M01] 读取命令行参数
来源：http://dali.wangdashe.top/Article/details/gtbvnlcnsw.html

Py:   sys.argv[1:]
来源：http://dali.daria6918.cn/Article/details/gtckicgywg.html

PHP:  $argv;  $argc;
来源：http://dali.dianchejie.cn/Article/details/gtxlbgiwgu.html

JS:   process.argv.slice(2)
来源：http://dali.xinyue.icu/Article/details/gtjjancfdp.html

TS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gtczngncka.html

Java: args 数组（main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gtkyjasjey.html

Go:   os.Args[1:]
来源：http://dali.xuanzx.com/Article/details/gtabgujnyg.html

Ruby: ARGV
来源：http://dali.yanxiufei.cn/Article/details/gtlmgswwjr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtsfzcarlj.html

[M02] 读取环境变量
来源：http://dali.c1oappe.top/Article/details/gtgqqfaxvg.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghmrpuyj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj202588.top/Article/details/gtsnzeloud.html

JS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gtvlroqqhz.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiinnvcve.html

Java: System.getenv("HOME")
来源：http://dali.hnqzz.top/Article/details/gtrukuvhvj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.smart0.xyz/Article/details/gtvkyjyytn.html

Ruby: ENV["HOME"]
来源：http://dali.mhx1999.top/Article/details/gtxeaytiwo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtzjxhkeru.html

[M03] 执行外部命令
来源：http://dali.ybcxt.top/Article/details/gtqzksbjex.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258.top/Article/details/gtrscdncaj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenlongwang.top/Article/details/gtrrknvllz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gtehkijanl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gthujjgems.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrrqkakqe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shzxlz.cn/Article/details/gtiqsdauiy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zdqjudy.top/Article/details/gtqnpfwqsx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hywenlv.cn/Article/details/gtmbhkighd.html

[M04] 获取当前工作目录
来源：http://dali.cheryme.top/Article/details/gtdslscfeo.html

Py:   os.getcwd()
来源：http://dali.yonumen.top/Article/details/gtwcezeyap.html

PHP:  getcwd();
来源：http://dali.chenlongwang.top/Article/details/gtwhjfjngg.html

JS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gtaiumqnyx.html

TS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gtbatarmcu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xziqi.cn/Article/details/gtiyyytyld.html

Go:   os.Getwd()
来源：http://dali.iojbl.cn/Article/details/gtqjvujued.html

Ruby: Dir.pwd
来源：http://dali.hfpthk.cn/Article/details/gtohntyewc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hfpthk.cn/Article/details/gtqymnqnio.html

[M05] 设置退出码
来源：http://dali.birdmap.top/Article/details/gtrhjmrikc.html

Py:   sys.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtrnlqmbyo.html

PHP:  exit(1);
来源：http://dali.guowangkeji.top/Article/details/gtacftafmh.html

JS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtxrctufza.html

TS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtxcdmsdba.html

Java: System.exit(1)
来源：http://dali.ybcxt.top/Article/details/gteiqnvzjo.html

Go:   os.Exit(1)
来源：http://dali.birdmap.top/Article/details/gtextgfsct.html

Ruby: exit 1
来源：http://dali.gotoacloud.top/Article/details/gtjvlhmzkk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guannengcc.top/Article/details/gtwsptdolj.html

[M06] 向标准错误输出
来源：http://dali.aizwys.cn/Article/details/gtaojqwoyz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenjidiqi.icu/Article/details/gtypphgrfz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sweek.top/Article/details/gtafjxeubb.html

JS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gtlfdjjuqz.html

TS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gtslvayofp.html

Java: System.err.println("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkffywof.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ivvv.top/Article/details/gtiykxxkrz.html

Ruby: warn "err"
来源：http://dali.gzhubu.top/Article/details/gtocptgnzl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gaohongyu789.top/Article/details/gtvdpkshqb.html

[M07] 判断是否为主入口
来源：http://dali.yj202588.top/Article/details/gtlkmqfqrz.html

Py:   if __name__ == "__main__":
来源：http://dali.hysaishi.cn/Article/details/gtjbuucbjt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gtnusjdjll.html

JS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gtyeiwvpbq.html

TS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gttsyrbcpq.html

Java: public static void main(String[] args)
来源：http://dali.xylfe.cn/Article/details/gtnjczqynz.html

Go:   func main()
来源：http://dali.gotoacloud.top/Article/details/gtfuqmzspv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.pengpengdd.cyou/Article/details/gtdqfzrlnt.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigfzy.top/Article/details/gtumrvyhli.html

[M08] 获取系统与运行时信息
来源：http://dali.cdnleiting.top/Article/details/gtfwscuwus.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shzxlz.cn/Article/details/gtxwtzjsvx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gzhubu.top/Article/details/gtosvydkid.html

JS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gtvtutzkwp.html

TS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gtuusaqztk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cheryme.top/Article/details/gtqkzlflen.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yongpay.top/Article/details/gtmlpkohbh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hysaishi.cn/Article/details/gtyfegecfj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhoulong.xyz/Article/details/gtlkxfszzf.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtxqtpdqvj.html

N. 数据结构与算法
来源：http://dali.yonumen.top/Article/details/gtcuudolrp.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtyqnkvpqo.html

[N01] 二分查找（有序数组）
来源：http://dali.xuanzx.com/Article/details/gtrcdhbhqi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tanke756.top/Article/details/gttvptvmzo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.c1oappe.top/Article/details/gtwdfzczyl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gtgcmgheob.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gtrohgvbow.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtnngjlgyz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtnnkjarea.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shuidangran.top/Article/details/gtdrypnwwz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtsursdhyn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xinyue.icu/Article/details/gtywielpit.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yueranfly.top/Article/details/gtjiaylrxe.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxinkj.top/Article/details/gtqhshwyzm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gtjjmntugu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtegrlkaal.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dashuyun.cn/Article/details/gtauegkuef.html

Go:   slices.Sort(arr)
来源：http://dali.cucudq.cn/Article/details/gtlbdtwsnd.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gtaysdozha.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxuanxn.top/Article/details/gtawjglehs.html

[N03] 快速排序（分治示例）
来源：http://dali.yvedp.cn/Article/details/gtvkrvjtna.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ivvv.top/Article/details/gtamzwolhb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangdashe.top/Article/details/gtkhfdqhoy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jianghu66.top/Article/details/gtpnfaafqg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gtlkbvizak.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gotoacloud.top/Article/details/gtpceakpzz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgufenzy.top/Article/details/gtdrioxnrl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tanke756.top/Article/details/gtxdzxfgbh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.birdmap.top/Article/details/gtqefdxpho.html

[N04] 斐波那契数列
来源：http://dali.jqgufenzy.top/Article/details/gtdyjfrgab.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gthflhqgrz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hysaishi.cn/Article/details/gtpqmsezxe.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtofxagngg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtywnpfljy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.havefunace.top/Article/details/gtszouwvtj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cucudq.cn/Article/details/gtqpvqlkij.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gtrkwehppw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdofsulmd.html

[N05] 最大公约数
来源：http://dali.zycfv.cn/Article/details/gtcjepmtzq.html

Py:   math.gcd(a, b)
来源：http://dali.yuxming.cn/Article/details/gtfvjysooj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gaohongyu789.top/Article/details/gttuflcdtt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pycfn.com/Article/details/gtemcqpafb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gttzvnmnwa.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cashguo.top/Article/details/gtsoqpxnmd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgfzy.top/Article/details/gtnfbngltq.html

Ruby: a.gcd(b)
来源：http://dali.hnqzz.top/Article/details/gtalmvtwou.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnchtqga.html

[N06] 判断回文字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlilbtsmz.html

Py:   s == s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gtjunsaavg.html

PHP:  $s === strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtvfwvqvgh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtqcqufhpj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gttewawlww.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhongyouzk.top/Article/details/gteaeqxmmh.html

Go:   // 双指针从两端比较
来源：http://dali.pycfn.com/Article/details/gtwygesozf.html

Ruby: s == s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxusxyfa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gttvajqmdj.html

[N07] 两数之和（返回下标）
来源：http://dali.zdqjudy.top/Article/details/gtiahjmfbu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zdqjudy.top/Article/details/gtonmbpgon.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shangyingyoupin.top/Article/details/gtygwmxdhd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhongyouzk.top/Article/details/gtdywbuuvj.html

TS:   // 手写 Map<string, number>
来源：http://dali.cqqwz.cn/Article/details/gtyslzogzh.html

Java: // 手写 HashMap
来源：http://dali.cashguo.top/Article/details/gtufghvvuq.html

Go:   // 手写 map[int]int
来源：http://dali.xziqi.cn/Article/details/gttxbibkae.html

Ruby: // 手写 Hash
来源：http://dali.shzxlz.cn/Article/details/gtidrdritu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aizwys.cn/Article/details/gtkhaqqfnc.html

[N08] 生成全排列
来源：http://dali.cqqwz.cn/Article/details/gtjlghaqrr.html

Py:   itertools.permutations(arr)
来源：http://dali.yangfankeji.com/Article/details/gtftyqhywo.html

PHP:  // 手写递归交换
来源：http://dali.chenzaomai.com/Article/details/gtspmbfwhg.html

JS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtvmjdjyfz.html

TS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtqvfmwrjb.html

Java: // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtrndkmbos.html

Go:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtmpfwmfsv.html

Ruby: arr.permutation.to_a
来源：http://dali.guowangkeji.top/Article/details/gtbtpdqcxe.html

C#:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtkucjomjf.html

[N09] 栈与队列
来源：http://dali.chenzaomai.com/Article/details/gtoktceyhi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.meibo888.top/Article/details/gtovdilpeb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangdashe.top/Article/details/gtvzraqpfo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtlrrtajux.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dianchejie.cn/Article/details/gtvyqijuvk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nwbrower.top/Article/details/gtgdkkaprl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jyoumei.cn/Article/details/gttgflekwc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gtxuqxuszj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.fzhhl.top/Article/details/gtcsmcwtqr.html

[N10] 链表节点定义
来源：http://dali.shuidangran.top/Article/details/gtorlnuavv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.c1oappe.top/Article/details/gtfypyyhdg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.pycfn.com/Article/details/gtialjkvey.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbbcpjrx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxuanxn.top/Article/details/gtwvucvooj.html

Java: class Node { int v; Node next; }
来源：http://dali.ybcxt.top/Article/details/gtrozlxrjg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.meibo888.top/Article/details/gtkwmlsewo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nanxinkj.top/Article/details/gtxtyrepby.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.meibo888.top/Article/details/gtrcvirdap.html

[N11] 二叉树中序遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtlgteswff.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigfzy.top/Article/details/gtxiqddddf.html

PHP:  // 手写递归函数
来源：http://dali.shangyingyoupin.top/Article/details/gtuqsryhzw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gttpsfkwlb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gthmjcetet.html

Java: // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gtjwrdnkpn.html

Go:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gtuhahnimn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuanzhike.top/Article/details/gtntwrbbvp.html

C#:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtcmauuznz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ppjwa.cn/Article/details/gtxzoatsgv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ppjwa.cn/Article/details/gttnsanwcb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.kuanghao11.cn/Article/details/gtyyviotmg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gtslerdusc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gtvtmiyhec.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gtpeimqbhg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenzaomai.com/Article/details/gtzthegscj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ehwqpu.com/Article/details/gthuczndqc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gtwvuwnfsl.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtzhlxvlfv.html

O. 并发与异步
来源：http://dali.hywenlv.cn/Article/details/gtuablcjhu.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuynoykbf.html

[O01] 启动一个线程
来源：http://dali.yj20258.top/Article/details/gtkngphaqe.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yvedp.cn/Article/details/gtbbiglros.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shangyingyoupin.top/Article/details/gtiuvkpaqz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.feifeiyinyue.top/Article/details/gtaawyekdm.html

TS:   // 同 JS
来源：http://dali.sxryk.cn/Article/details/gtctglvlti.html

Java: new Thread(() -> f()).start()
来源：http://dali.daria6918.cn/Article/details/gtmwpizbwu.html

Go:   go f()
来源：http://dali.wangshuangyany.cn/Article/details/gtbnqkltxl.html

Ruby: Thread.new { f }
来源：http://dali.ivvv.top/Article/details/gtkxbnxmky.html

C#:   Task.Run(() => F());
来源：http://dali.yuanzhike.top/Article/details/gtlgbasbzr.html

[O02] 使用线程池
来源：http://dali.nwbrower.top/Article/details/gtzzyxnces.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.vqdsnc.cn/Article/details/gtqvkmxbam.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nwbrower.top/Article/details/gtnebyrvna.html

JS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gtvvncnozs.html

TS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gtkfqjlwrm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.fzhhl.top/Article/details/gtcqtngdyt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.andypj.xyz/Article/details/gtrwelaujk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sxryk.cn/Article/details/gtnipaxvkd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258888.top/Article/details/gtthygxmvg.html

[O03] 加锁保护共享数据
来源：http://dali.haohaochexian.top/Article/details/gtdlcqppcb.html

Py:   with lock: shared += 1
来源：http://dali.9152youxi.cn/Article/details/gtshnqxbdy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hysaishi.cn/Article/details/gtbaomkrmd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.meibo888.top/Article/details/gtbqpqanka.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gtvgfzwhbh.html

Java: synchronized (this) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gtndgopvge.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yanxiufei.cn/Article/details/gtqxcxwgym.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jiagoushi.top/Article/details/gtwpzcdfbx.html

C#:   lock (gate) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvcyqxuo.html

[O04] 定义异步函数并等待
来源：http://dali.redwolf501.top/Article/details/gthkltbjef.html

Py:   async def f():⏎    await g()
来源：http://dali.zhongyouzk.top/Article/details/gtmywfpwbi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhoulong.xyz/Article/details/gtnorizbmz.html

JS:   async function f() { await g(); }
来源：http://dali.jyoumei.cn/Article/details/gtvaxqsqdj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258.top/Article/details/gtskpwmbsy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zdqjudy.top/Article/details/gtudxxbrpx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.feifeiyinyue.top/Article/details/gturnxrwgq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigfzy.top/Article/details/gtrtyjrlxg.html

C#:   async Task F() { await G(); }
来源：http://dali.cucudq.cn/Article/details/gtayozxiyv.html

[O05] 并发执行并等待全部完成
来源：http://dali.cdnleiting.top/Article/details/gtevjodiov.html


<!-- 参考信息 -->