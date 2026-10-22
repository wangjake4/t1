代发 wailian999

L. 网络请求
来源：http://dali.zhoulong.xyz/Article/details/gtuyizlzev.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtlspyukcu.html

[L01] 发送 GET 请求
来源：http://dali.xuanzx.com/Article/details/gtlnoluzre.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guannengcc.top/Article/details/gtbrzavlil.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jlsjyb.cn/Article/details/gtlitlhvpb.html

JS:   await fetch(url)
来源：http://dali.guannengcc.top/Article/details/gtkamberzp.html

TS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gtlzacjppn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.bjfxy.top/Article/details/gtqcrsdyni.html

Go:   resp, err := http.Get(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtlyubemmk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guowangkeji.top/Article/details/gtngqzcwln.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.haohaochexian.top/Article/details/gtjdklaakx.html

[L02] 发送 POST JSON
来源：http://dali.smart0.xyz/Article/details/gtnonjvpyq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xziqi.cn/Article/details/gtplyfygon.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gaohongyu789.top/Article/details/gtmixapcgi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangdashe.top/Article/details/gtapvpswta.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gtfanihzlc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gotoacloud.top/Article/details/gtxbbuhgtn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangtech.top/Article/details/gtudgakfhy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ivvv.top/Article/details/gtfahxrwty.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtamnqtwcn.html

[L03] 设置自定义请求头
来源：http://dali.gaohongyu789.top/Article/details/gtnljpbigp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fengsongda.top/Article/details/gtkmepkwox.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pycfn.com/Article/details/gtkcahgssg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gtdpvvwmhz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gtuhaloecj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258888.top/Article/details/gtgdqskcab.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gtedbgwivz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgjxzfbu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gtbkherfai.html

[L04] 设置超时
来源：http://dali.zhiwuduotai.top/Article/details/gtbadaziwr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.bjfxy.top/Article/details/gtlwehydnd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daria6918.cn/Article/details/gtosibkdnz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gthyyfhnpr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gtztggnlwz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fengsongda.top/Article/details/gtvlxsldlb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhengqikj.top/Article/details/gtnuqomeun.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuanzhike.top/Article/details/gtaotbivja.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenzaomai.com/Article/details/gttxxrspef.html

[L05] 上传文件（multipart）
来源：http://dali.guowangkeji.top/Article/details/gttqisrzor.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj20258.top/Article/details/gtizvxlxvg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuxming.cn/Article/details/gtlwbrvjpj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gttykdjmjv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gtyrblvvai.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hammf.cn/Article/details/gtzenmlbox.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.haohaochexian.top/Article/details/gtnglllwcj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuanzhike.top/Article/details/gtvqmlqrre.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fzhhl.top/Article/details/gtxmeepjbz.html

[L06] 解析响应为 JSON
来源：http://dali.quarkkingdee.top/Article/details/gtmmavrlco.html

Py:   resp.json()
来源：http://dali.cashguo.top/Article/details/gtaziqwonc.html

PHP:  json_decode($body, true);
来源：http://dali.gzhubu.top/Article/details/gtgdgazxhq.html

JS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gttcrvyvdp.html

TS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gtbjftpdch.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.meibo888.top/Article/details/gtsndwxiyd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgufenzy.top/Article/details/gtcxjxnskm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.haohaochexian.top/Article/details/gttwjinvnn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yanxiufei.cn/Article/details/gtklpjksvx.html

[L07] 处理 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gthtmmjlob.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gotoacloud.top/Article/details/gtbmaqprmu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zdqjudy.top/Article/details/gtdpkhtfgz.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gtnqpufigi.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthhqxxzp.html

Java: resp.statusCode()
来源：http://dali.yongpay.top/Article/details/gthbxoivkv.html

Go:   resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gtpelnhbyq.html

Ruby: resp.code.to_i
来源：http://dali.zdqjudy.top/Article/details/gtwpwjgvcp.html

C#:   (int)resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtdungxxzc.html

[L08] 并发请求多个地址
来源：http://dali.wangshuangyany.cn/Article/details/gtazziegjf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jianghu66.top/Article/details/gtsypmnyck.html

PHP:  curl_multi_init() 系列
来源：http://dali.yongpay.top/Article/details/gtdxrrxrss.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gtlohruqtr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gtvabvogpp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgfzy.top/Article/details/gtszfvvxay.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ydzc1.top/Article/details/gtlnxgjaem.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shzxlz.cn/Article/details/gtzxufbxgz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hammf.cn/Article/details/gtssfotpjb.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtyiisjusi.html

M. 命令行 / 进程 / 环境
来源：http://dali.xziqi.cn/Article/details/gtttwckisg.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtfylafajg.html

[M01] 读取命令行参数
来源：http://dali.tianlin.xyz/Article/details/gtzyngokbz.html

Py:   sys.argv[1:]
来源：http://dali.yj20258888.top/Article/details/gtuimjuzfk.html

PHP:  $argv;  $argc;
来源：http://dali.snrcjt.cn/Article/details/gthigrshfv.html

JS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gtjhshwrxz.html

TS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gthyswgdkv.html

Java: args 数组（main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gtvxxahnqq.html

Go:   os.Args[1:]
来源：http://dali.zycfv.cn/Article/details/gtjsiqtwly.html

Ruby: ARGV
来源：http://dali.0kj1m.cn/Article/details/gtvanbwgfh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gtwjcojiqe.html

[M02] 读取环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtegxnnwud.html

Py:   os.environ.get("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdoqfjax.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gtsfjpqten.html

JS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gtuzxlptyp.html

TS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gtvrmsygjh.html

Java: System.getenv("HOME")
来源：http://dali.yueranfly.top/Article/details/gtnqbhqjrb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guannengcc.top/Article/details/gtbpzlevgm.html

Ruby: ENV["HOME"]
来源：http://dali.pycfn.com/Article/details/gtnlwftzqw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ivvv.top/Article/details/gtaykdwawn.html

[M03] 执行外部命令
来源：http://dali.yvedp.cn/Article/details/gtlxbvocsg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.316326.xyz/Article/details/gtoijhqdmk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnxiangtu.top/Article/details/gtmhnvxlct.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gtbavzhopm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtqwkvxwcx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hammf.cn/Article/details/gtqqcdddxq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ivvv.top/Article/details/gtfkxtxlxl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhixingplan.top/Article/details/gtzpfukjda.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258888.top/Article/details/gthoevbtvl.html

[M04] 获取当前工作目录
来源：http://dali.yuxming.cn/Article/details/gtfigoieps.html

Py:   os.getcwd()
来源：http://dali.chenzaomai.com/Article/details/gthwrhqpws.html

PHP:  getcwd();
来源：http://dali.aibaodan.cn/Article/details/gtbgvghhxm.html

JS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gtlxfyksom.html

TS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gtigtishly.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.kuanghao11.cn/Article/details/gtokrntwjb.html

Go:   os.Getwd()
来源：http://dali.jqgufenzy.top/Article/details/gtvdlssktj.html

Ruby: Dir.pwd
来源：http://dali.xziqi.cn/Article/details/gtsjztbwuu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yongpay.top/Article/details/gtjxnhkpyw.html

[M05] 设置退出码
来源：http://dali.xuetiantiany.cn/Article/details/gtktzkcdrv.html

Py:   sys.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtxocaqjrd.html

PHP:  exit(1);
来源：http://dali.yuxming.cn/Article/details/gtavipfccr.html

JS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtqcmtytmv.html

TS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gthsbxwazz.html

Java: System.exit(1)
来源：http://dali.ivvv.top/Article/details/gtxvmiwlyu.html

Go:   os.Exit(1)
来源：http://dali.aizwys.cn/Article/details/gtmqsrfcqc.html

Ruby: exit 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsanbxym.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylbutlbq.html

[M06] 向标准错误输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtippyskxc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tanke756.top/Article/details/gtwonbupxw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daria6918.cn/Article/details/gttgyjcqbq.html

JS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gtuycnlbsb.html

TS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gtvhbcujvl.html

Java: System.err.println("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtobrlnwdc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.iojbl.cn/Article/details/gtwtoxfsgz.html

Ruby: warn "err"
来源：http://dali.hysaishi.cn/Article/details/gtnhiranht.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cucudq.cn/Article/details/gtnyvrglzk.html

[M07] 判断是否为主入口
来源：http://dali.0kj1m.cn/Article/details/gtrgxhwiba.html

Py:   if __name__ == "__main__":
来源：http://dali.sweek.top/Article/details/gtxeaemwak.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ivvv.top/Article/details/gtyegwgswu.html

JS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gtefvubwjj.html

TS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtmqzrlryd.html

Java: public static void main(String[] args)
来源：http://dali.jianghu66.top/Article/details/gtzrsrldbu.html

Go:   func main()
来源：http://dali.hywenlv.cn/Article/details/gthxccrjej.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aibaodan.cn/Article/details/gtaaaqddby.html

C#:   static void Main(string[] args)
来源：http://dali.ivvv.top/Article/details/gtptczpzjq.html

[M08] 获取系统与运行时信息
来源：http://dali.xylfe.cn/Article/details/gtnjbbgkow.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dashuyun.cn/Article/details/gtmgxborbc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258.top/Article/details/gtyqibemgc.html

JS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gtguorxqgc.html

TS:   process.platform;  process.version
来源：http://dali.sufxvd.cn/Article/details/gtwuamxhio.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jyoumei.cn/Article/details/gtdgjmmovd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sufxvd.cn/Article/details/gtsphsuiln.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.9152youxi.cn/Article/details/gtldwibfwg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yueranfly.top/Article/details/gttfqnideg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtuyxqtqwe.html

N. 数据结构与算法
来源：http://dali.yongpay.top/Article/details/gtvirrfaeh.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gthhifbusr.html

[N01] 二分查找（有序数组）
来源：http://dali.bjfxy.top/Article/details/gtnjovpacn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtweeowvcp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.birdmap.top/Article/details/gtheuqtpxd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gtwberxmnx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gtewcpxxoe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.316326.xyz/Article/details/gtaocqzbyy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtztzmyesz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nwbrower.top/Article/details/gtaxneuiku.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gthowzblhu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.havefunace.top/Article/details/gtujowlgor.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gaohongyu789.top/Article/details/gtnfgrdfaa.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.svipenyu.cn/Article/details/gtdvugdclb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtccloocxg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gtklokxowe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.c1oappe.top/Article/details/gtaxxofqob.html

Go:   slices.Sort(arr)
来源：http://dali.wangdashe.top/Article/details/gtiyxxwind.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gtnbtlovhd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhixingplan.top/Article/details/gtxvtztiwz.html

[N03] 快速排序（分治示例）
来源：http://dali.chenjidiqi.icu/Article/details/gtwzvksvku.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guannengcc.top/Article/details/gtkxiumgpt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sysykeji.top/Article/details/gtlcfzcgay.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gtpvzpolqe.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gtbscyabvi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ehwqpu.com/Article/details/gtafdfnlso.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgfzy.top/Article/details/gttybvsrij.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tanke756.top/Article/details/gtckcajqll.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jiagoushi.top/Article/details/gtcnbavncm.html

[N04] 斐波那契数列
来源：http://dali.bjfxy.top/Article/details/gtuxwctirn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gtdwrzzdyi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gtuwfuyuib.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtjffjakbo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gtlxaapybe.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gtmdgcphqr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbiejkrgo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtwdhxjwxi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtutcwjnwu.html

[N05] 最大公约数
来源：http://dali.shanyushiyangtech.top/Article/details/gtojsyixyq.html

Py:   math.gcd(a, b)
来源：http://dali.yuxming.cn/Article/details/gthipzphcm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.svipenyu.cn/Article/details/gtvmyyllbc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gtsjndpvlu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtdqzgyqmz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujdhgrai.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yueranfly.top/Article/details/gtkfmmxyks.html

Ruby: a.gcd(b)
来源：http://dali.ppjwa.cn/Article/details/gthlpojppg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cqqwz.cn/Article/details/gtcoyjrhwo.html

[N06] 判断回文字符串
来源：http://dali.hywenlv.cn/Article/details/gthtymrssa.html

Py:   s == s[::-1]
来源：http://dali.jyoumei.cn/Article/details/gtdokmghin.html

PHP:  $s === strrev($s);
来源：http://dali.jlsjyb.cn/Article/details/gtxoxauoae.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gtsbftbytg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtcpmvpqvv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tian-w.cn/Article/details/gtpnigtmca.html

Go:   // 双指针从两端比较
来源：http://dali.xuetiantiany.cn/Article/details/gtmaqmymbo.html

Ruby: s == s.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtthdyofzc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gtndatjpdj.html

[N07] 两数之和（返回下标）
来源：http://dali.shanyushiyangtech.top/Article/details/gtvscbfmth.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tianlin.xyz/Article/details/gtrvmglbnf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxinkj.top/Article/details/gtofagvzlb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgufenzy.top/Article/details/gteznwfhjk.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuxming.cn/Article/details/gtzvlqcarf.html

Java: // 手写 HashMap
来源：http://dali.jinghuilouyu.cn/Article/details/gtljboseds.html

Go:   // 手写 map[int]int
来源：http://dali.svipenyu.cn/Article/details/gtfetkwuxg.html

Ruby: // 手写 Hash
来源：http://dali.chenjidiqi.icu/Article/details/gtwgmstyvs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fengsongda.top/Article/details/gtlkbzhyaj.html

[N08] 生成全排列
来源：http://dali.daria6918.cn/Article/details/gttfqtwnnd.html

Py:   itertools.permutations(arr)
来源：http://dali.bjfxy.top/Article/details/gtbrpwqsqy.html

PHP:  // 手写递归交换
来源：http://dali.havefunace.top/Article/details/gtnsxmjief.html

JS:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtxxrxcden.html

TS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdkfuazi.html

Java: // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtkrzdsihe.html

Go:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtifelvyrv.html

Ruby: arr.permutation.to_a
来源：http://dali.redwolf501.top/Article/details/gtnmnlptoz.html

C#:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtyrebvocc.html

[N09] 栈与队列
来源：http://dali.iojbl.cn/Article/details/gtqyngmurz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgfzy.top/Article/details/gtqwbcblmg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtoztksleo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gtsamvahkm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.birdmap.top/Article/details/gtoasbezvj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigufen.top/Article/details/gthxjfbrju.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.havefunace.top/Article/details/gtkkxhjvhj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvlfidqj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sxryk.cn/Article/details/gtreifrify.html

[N10] 链表节点定义
来源：http://dali.chenjidiqi.icu/Article/details/gtmvbmpjeh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hywenlv.cn/Article/details/gtkksrwmrj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hammf.cn/Article/details/gtkfnonwvw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tian-w.cn/Article/details/gtgbxpvkhy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuubflhdn.html

Java: class Node { int v; Node next; }
来源：http://dali.nanxinkj.top/Article/details/gtdupecoyz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jlsjyb.cn/Article/details/gtggnmgvax.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgufenzy.top/Article/details/gtsppniyko.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tian-w.cn/Article/details/gtlirpcrns.html

[N11] 二叉树中序遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhqrkzpp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gtdvuvlhqj.html

PHP:  // 手写递归函数
来源：http://dali.yj202588.top/Article/details/gtbqjcncps.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.redwolf501.top/Article/details/gtarvpqknj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ybcxt.top/Article/details/gtsffubenc.html

Java: // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtekwbzypl.html

Go:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtnhzdlgvs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangshuangyany.cn/Article/details/gtqorxitmr.html

C#:   // 手写递归
来源：http://dali.xziqi.cn/Article/details/gtyxdyeorc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sufxvd.cn/Article/details/gtubvkppwn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hfpthk.cn/Article/details/gtvvpoebkn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.quarkkingdee.top/Article/details/gtvjqlvvou.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gtqwzgpuat.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangshuangyany.cn/Article/details/gtgmlyhika.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gteyhzqucp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ydzc1.top/Article/details/gtmhgvtwny.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj202588.top/Article/details/gteuqvstcg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gtssgusiyg.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtldrkyawv.html

O. 并发与异步
来源：http://dali.0kj1m.cn/Article/details/gtytrdohym.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtewpjpgkk.html

[O01] 启动一个线程
来源：http://dali.jinghuilouyu.cn/Article/details/gtjsexffvc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ppjwa.cn/Article/details/gtcmxelaai.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.fengsongda.top/Article/details/gtaphprlgh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.0kj1m.cn/Article/details/gttmmrdvay.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gtqlxarrue.html

Java: new Thread(() -> f()).start()
来源：http://dali.daxiang520.top/Article/details/gtzbmnphmz.html

Go:   go f()
来源：http://dali.sysykeji.top/Article/details/gtfjwrpmym.html

Ruby: Thread.new { f }
来源：http://dali.fengsongda.top/Article/details/gtmmqxxreo.html

C#:   Task.Run(() => F());
来源：http://dali.redwolf501.top/Article/details/gtwemlukto.html

[O02] 使用线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtshynklpc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gtqdbicfhs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhongyouzk.top/Article/details/gtzjpqbuye.html

JS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gtlfodnxml.html

TS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gtgxdruyzg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ydzc1.top/Article/details/gtsuksaxgq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xuetiantiany.cn/Article/details/gtrmnttchq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenjidiqi.icu/Article/details/gtmmhykjka.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jyoumei.cn/Article/details/gtvxyjqhwj.html

[O03] 加锁保护共享数据
来源：http://dali.xylfe.cn/Article/details/gtmasbcuqa.html

Py:   with lock: shared += 1
来源：http://dali.yongpay.top/Article/details/gtpthleith.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhengqikj.top/Article/details/gtehdwymmz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.mhx1999.top/Article/details/gtilrzttxb.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gtqxyvuhjs.html

Java: synchronized (this) { shared++; }
来源：http://dali.yongpay.top/Article/details/gtltlpxuus.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.feifeiyinyue.top/Article/details/gtxsqavblw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.iojbl.cn/Article/details/gtzzppbhhr.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj202588.top/Article/details/gtdvnhzyrj.html

[O04] 定义异步函数并等待
来源：http://dali.sufxvd.cn/Article/details/gtubehjgaj.html

Py:   async def f():⏎    await g()
来源：http://dali.yj20258888.top/Article/details/gtovouxerb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jiagoushi.top/Article/details/gttoyhloie.html

JS:   async function f() { await g(); }
来源：http://dali.nanxuanxn.top/Article/details/gtuphpffpu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sxryk.cn/Article/details/gtzciwokjt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.bjfxy.top/Article/details/gtgrlgxuuc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.iojbl.cn/Article/details/gtrujhydnf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.feifeiyinyue.top/Article/details/gtwgneeaye.html

C#:   async Task F() { await G(); }
来源：http://dali.sxryk.cn/Article/details/gtjcealkbp.html

[O05] 并发执行并等待全部完成
来源：http://dali.hysaishi.cn/Article/details/gtybhulhjw.html


<!-- 参考信息 -->