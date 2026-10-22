代发 wailian999

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.meibo888.top/Article/details/gt2cswzarmj.html

JS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gt2gaocbfzu.html

TS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gt2ceixslpd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.svipenyu.cn/Article/details/gt2cxfazqzz.html

Go:   resp, err := http.Get(url)
来源：http://dali.tianlin.xyz/Article/details/gt2gvpfuzwr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jiagoushi.top/Article/details/gt2xzkyixmd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tanke756.top/Article/details/gt2vorugdnm.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnwvspyb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.meibo888.top/Article/details/gt2osuzuozn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tanke756.top/Article/details/gt2royfiwpb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gt2otpdnofm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2edtnejcq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fzhhl.top/Article/details/gt2olmcqaqi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhongyouzk.top/Article/details/gt2forcbemx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sufxvd.cn/Article/details/gt2mgbfaxig.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sysykeji.top/Article/details/gt2pvapmsmr.html

[L03] 设置自定义请求头
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lpgbuaqi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.snrcjt.cn/Article/details/gt2tdhsucje.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgfzy.top/Article/details/gt2gqijtsgx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gt2dkxjwwev.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gt2avaeoqik.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.fengsongda.top/Article/details/gt2ildismao.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gt2zkeahtkr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pengpengdd.cyou/Article/details/gt2qropjtvu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gt2ydkivmjy.html

[L04] 设置超时
来源：http://dali.jlsjyb.cn/Article/details/gt2pvgcnpml.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhengqikj.top/Article/details/gt2jbqaoxye.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnqzz.top/Article/details/gt2pzzajmoh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zycfv.cn/Article/details/gt2ngqsoqhn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2yeeenwgl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nwbrower.top/Article/details/gt2ncehlpnb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ncvsfwdp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnqzz.top/Article/details/gt2quhhcwau.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vzdgxopw.html

[L05] 上传文件（multipart）
来源：http://dali.birdmap.top/Article/details/gt2bsdrdmql.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.meibo888.top/Article/details/gt2xxhvevxz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yvedp.cn/Article/details/gt2ksllyxgf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gt2qivgezgl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gt2niqycpfw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.havefunace.top/Article/details/gt2zlabshdi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hfpthk.cn/Article/details/gt2etgkvzhk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sufxvd.cn/Article/details/gt2wpwrypyz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2qyxaiixt.html

[L06] 解析响应为 JSON
来源：http://dali.ehwqpu.com/Article/details/gt2yftzemlj.html

Py:   resp.json()
来源：http://dali.yonumen.top/Article/details/gt2tdxlszut.html

PHP:  json_decode($body, true);
来源：http://dali.daria6918.cn/Article/details/gt2kibwmhbm.html

JS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gt2nqenqfnb.html

TS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gt2ccwfpmiy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gt2zphhpize.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgufenzy.top/Article/details/gt2ocqijnmq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gotoacloud.top/Article/details/gt2wzybkvwu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aibaodan.cn/Article/details/gt2pxoelpuc.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gt2bcqsxeae.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hfpthk.cn/Article/details/gt2rqyggove.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sweek.top/Article/details/gt2cuhckerv.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2xcracrxi.html

TS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gt2euaqtjkt.html

Java: resp.statusCode()
来源：http://dali.haohaochexian.top/Article/details/gt2bvcajckr.html

Go:   resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gt2zruaokqr.html

Ruby: resp.code.to_i
来源：http://dali.ehwqpu.com/Article/details/gt2aceqczee.html

C#:   (int)resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gt2eaeieypg.html

[L08] 并发请求多个地址
来源：http://dali.chenzaomai.com/Article/details/gt2csjxhixm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sufxvd.cn/Article/details/gt2nipflmen.html

PHP:  curl_multi_init() 系列
来源：http://dali.pycfn.com/Article/details/gt2djelsvzb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dwkjcsue.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gt2nueodmlc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fengsongda.top/Article/details/gt2zttnkvla.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.havefunace.top/Article/details/gt2yhtnjjgl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gt2yupcutmi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sxryk.cn/Article/details/gt2pzblqcif.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2cxgfdski.html

M. 命令行 / 进程 / 环境
来源：http://dali.ydzc1.top/Article/details/gt2geezhwxm.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2tbkrywrm.html

[M01] 读取命令行参数
来源：http://dali.sufxvd.cn/Article/details/gt2dlgjdxsn.html

Py:   sys.argv[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gt2lvizivqr.html

PHP:  $argv;  $argc;
来源：http://dali.zycfv.cn/Article/details/gt2tvjsnyjz.html

JS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gt2qnqykmvw.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gt2kcphnnnx.html

Java: args 数组（main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gt2fslvgzis.html

Go:   os.Args[1:]
来源：http://dali.yonumen.top/Article/details/gt2uoozapur.html

Ruby: ARGV
来源：http://dali.yueranfly.top/Article/details/gt2yyalszcq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gt2kreddaem.html

[M02] 读取环境变量
来源：http://dali.ehwqpu.com/Article/details/gt2qtivnzho.html

Py:   os.environ.get("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2jgaodnka.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gt2iyoqvvnn.html

JS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gt2yatanlbs.html

TS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gt2uuipmlvn.html

Java: System.getenv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gt2srclzqfh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pycfn.com/Article/details/gt2wnqarepy.html

Ruby: ENV["HOME"]
来源：http://dali.hywenlv.cn/Article/details/gt2jgjevcsn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gt2njpmebhm.html

[M03] 执行外部命令
来源：http://dali.cdnleiting.top/Article/details/gt2wltzvpge.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ybcxt.top/Article/details/gt2srsobypc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jyoumei.cn/Article/details/gt2mqadzryl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gt2usjhcpxg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gt2hipqvyxh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258888.top/Article/details/gt2rfbdqnkw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.meibo888.top/Article/details/gt2gacvzhco.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jiagoushi.top/Article/details/gt2muqekrdw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.andypj.xyz/Article/details/gt2vqidvmnp.html

[M04] 获取当前工作目录
来源：http://dali.svipenyu.cn/Article/details/gt2zbujajvj.html

Py:   os.getcwd()
来源：http://dali.snrcjt.cn/Article/details/gt2xgnjheau.html

PHP:  getcwd();
来源：http://dali.sxryk.cn/Article/details/gt2twemeeat.html

JS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2ffvplblj.html

TS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vnacbczs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zycfv.cn/Article/details/gt2uyhdhasv.html

Go:   os.Getwd()
来源：http://dali.svipenyu.cn/Article/details/gt2nzcqhuvx.html

Ruby: Dir.pwd
来源：http://dali.chenjidiqi.icu/Article/details/gt2jaguqcyg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zdqjudy.top/Article/details/gt2dzhpunyi.html

[M05] 设置退出码
来源：http://dali.tianlin.xyz/Article/details/gt2slfhfjsu.html

Py:   sys.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2sysjganp.html

PHP:  exit(1);
来源：http://dali.nanxuanxn.top/Article/details/gt2lykxvrvw.html

JS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2nzmeydbf.html

TS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gt2bvvsoybz.html

Java: System.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2zhvujxtf.html

Go:   os.Exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2spihnavc.html

Ruby: exit 1
来源：http://dali.nanxuanxn.top/Article/details/gt2bhdffnwm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.pycfn.com/Article/details/gt2zdwsoktj.html

[M06] 向标准错误输出
来源：http://dali.yuxming.cn/Article/details/gt2qoutmqsh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hfpthk.cn/Article/details/gt2vottaanz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yongpay.top/Article/details/gt2gwtkejhy.html

JS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gt2bvipkjna.html

TS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gt2hjtwkqpj.html

Java: System.err.println("err")
来源：http://dali.smart0.xyz/Article/details/gt2qqbawdyt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hfpthk.cn/Article/details/gt2ayfwfbcz.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gt2pgyqkogj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gaohongyu789.top/Article/details/gt2kltfzasp.html

[M07] 判断是否为主入口
来源：http://dali.quarkkingdee.top/Article/details/gt2ycncqdtc.html

Py:   if __name__ == "__main__":
来源：http://dali.smart0.xyz/Article/details/gt2fgrjdrvt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gzhubu.top/Article/details/gt2snxrjhvc.html

JS:   require.main === module
来源：http://dali.sweek.top/Article/details/gt2cqpayysl.html

TS:   require.main === module
来源：http://dali.snrcjt.cn/Article/details/gt2opabedlj.html

Java: public static void main(String[] args)
来源：http://dali.tanke756.top/Article/details/gt2wyqwquht.html

Go:   func main()
来源：http://dali.aizwys.cn/Article/details/gt2vwtevnkl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yueranfly.top/Article/details/gt2xasdxwrr.html

C#:   static void Main(string[] args)
来源：http://dali.guowangkeji.top/Article/details/gt2pxfobuxx.html

[M08] 获取系统与运行时信息
来源：http://dali.zhiwuduotai.top/Article/details/gt2cfmxhvdx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.snrcjt.cn/Article/details/gt2dwwgnhwd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xziqi.cn/Article/details/gt2ggthykno.html

JS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gt2scbwypbt.html

TS:   process.platform;  process.version
来源：http://dali.wangdashe.top/Article/details/gt2vvbtfbtc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xylfe.cn/Article/details/gt2lzugpupk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenzaomai.com/Article/details/gt2ggzzafyc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuxming.cn/Article/details/gt2zfuamtin.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yueranfly.top/Article/details/gt2nmqmjmxz.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2enuwjypg.html

N. 数据结构与算法
来源：http://dali.316326.xyz/Article/details/gt2tsmajgep.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2uocpffnb.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ptpgfhqg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2pbgjonug.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yueranfly.top/Article/details/gt2nukjyglu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gt2xnsqyske.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gt2qsjajrwt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2sqxefuuw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2rejlsmjz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuxming.cn/Article/details/gt2lqaqodpi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2lytuamzl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnxiangtu.top/Article/details/gt2hdgewtjz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gt2aczurduc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bachddtg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gt2csrzxxkq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ouydmjyn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.bjfxy.top/Article/details/gt2pwjajecc.html

Go:   slices.Sort(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2ppbafnub.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gt2tmcniary.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tian-w.cn/Article/details/gt2cafcfaqc.html

[N03] 快速排序（分治示例）
来源：http://dali.birdmap.top/Article/details/gt2znqjtlzc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xziqi.cn/Article/details/gt2zcexlylp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shangyingyoupin.top/Article/details/gt2ggknkoem.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gt2rznfthve.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gt2loafxevt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.vqdsnc.cn/Article/details/gt2cuaxkuum.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dianchejie.cn/Article/details/gt2edihckjn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cqqwz.cn/Article/details/gt2vyjwksmy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hfpthk.cn/Article/details/gt2mkcstabt.html

[N04] 斐波那契数列
来源：http://dali.bjfxy.top/Article/details/gt2rumguhvs.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gt2knvedvyx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.bjfxy.top/Article/details/gt2kkqzoopv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gt2dditgjwf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2aslfgtli.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tjqeakxw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yueranfly.top/Article/details/gt2pwagaarh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rwsogner.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gt2iezhaqhz.html

[N05] 最大公约数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wbrjjdbg.html

Py:   math.gcd(a, b)
来源：http://dali.316326.xyz/Article/details/gt2ghfmdkgz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhixingplan.top/Article/details/gt2voekzlut.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gt2gzsmarfg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gt2fxvepwol.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.mhx1999.top/Article/details/gt2htskoszu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yanxiufei.cn/Article/details/gt2cdihbdle.html

Ruby: a.gcd(b)
来源：http://dali.daxiang520.top/Article/details/gt2urlucgun.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.aibaodan.cn/Article/details/gt2ogevqudy.html

[N06] 判断回文字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2ddacsnlc.html

Py:   s == s[::-1]
来源：http://dali.cdnleiting.top/Article/details/gt2acxsshog.html

PHP:  $s === strrev($s);
来源：http://dali.yongpay.top/Article/details/gt2nyondzwk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozydsgef.html

TS:   s === [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2gfwsbkof.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hywenlv.cn/Article/details/gt2ttwqwfig.html

Go:   // 双指针从两端比较
来源：http://dali.sufxvd.cn/Article/details/gt2porntvfh.html

Ruby: s == s.reverse
来源：http://dali.ydzc1.top/Article/details/gt2fvvmhoel.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenlongwang.top/Article/details/gt2fondifep.html

[N07] 两数之和（返回下标）
来源：http://dali.pengpengdd.cyou/Article/details/gt2deusfsbt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gaohongyu789.top/Article/details/gt2ddjetjma.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gogol.net.cn/Article/details/gt2zslqrtpo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenlongwang.top/Article/details/gt2qjjltcsq.html

TS:   // 手写 Map<string, number>
来源：http://dali.gotoacloud.top/Article/details/gt2whqmrehd.html

Java: // 手写 HashMap
来源：http://dali.jlsjyb.cn/Article/details/gt2obbrvfxj.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258888.top/Article/details/gt2yllfqbto.html

Ruby: // 手写 Hash
来源：http://dali.yj20258.top/Article/details/gt2xrrbfmdr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.kuanghao11.cn/Article/details/gt2gtbnoxet.html

[N08] 生成全排列
来源：http://dali.chenjidiqi.icu/Article/details/gt2dkzubstf.html

Py:   itertools.permutations(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2uvmvwowk.html

PHP:  // 手写递归交换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aqjydcma.html

JS:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gt2swqdtwbo.html

TS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gt2odrfunng.html

Java: // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gt2ngmyneen.html

Go:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2qnewfofk.html

Ruby: arr.permutation.to_a
来源：http://dali.pengpengdd.cyou/Article/details/gt2vsnylvsi.html

C#:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2suwrnxvn.html

[N09] 栈与队列
来源：http://dali.nwbrower.top/Article/details/gt2vnsohygu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hfohwpvx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gt2exatjrce.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lanvsait.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhixingplan.top/Article/details/gt2fztfueyf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cucudq.cn/Article/details/gt2cgxhyale.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yangfankeji.com/Article/details/gt2dgfdcrwp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2zrjfmvil.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258.top/Article/details/gt2irlrgwbj.html

[N10] 链表节点定义
来源：http://dali.jqgfzy.top/Article/details/gt2cxyhmfkx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aumzorht.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2pkgdopbp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.andypj.xyz/Article/details/gt2qxpwevuc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.quarkkingdee.top/Article/details/gt2jfhbviju.html

Java: class Node { int v; Node next; }
来源：http://dali.daria6918.cn/Article/details/gt2wexlusvq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ivvv.top/Article/details/gt2pjsqfbiu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.snrcjt.cn/Article/details/gt2afckkkxo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daria6918.cn/Article/details/gt2qjwzcecq.html

[N11] 二叉树中序遍历
来源：http://dali.gotoacloud.top/Article/details/gt2yhkucdir.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.316326.xyz/Article/details/gt2ddwouyve.html

PHP:  // 手写递归函数
来源：http://dali.nwbrower.top/Article/details/gt2xxhhnndx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yvedp.cn/Article/details/gt2ybmcetvy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuanzx.com/Article/details/gt2swuiswtk.html

Java: // 手写递归
来源：http://dali.guannengcc.top/Article/details/gt2vaemmchx.html

Go:   // 手写递归
来源：http://dali.andypj.xyz/Article/details/gt2avmnhjkv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cdnleiting.top/Article/details/gt2tsbrfcly.html

C#:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gt2lenvkwdd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gzhubu.top/Article/details/gt2ciblczcu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fengsongda.top/Article/details/gt2uegrfmsq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cpzsxgbf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gt2nejzucti.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnqzz.top/Article/details/gt2ugwfvzcu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gt2uvpxgexk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.316326.xyz/Article/details/gt2xxlvhqqz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jianghu66.top/Article/details/gt2ayfesjga.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.smart0.xyz/Article/details/gt2xcbktaht.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2cxhjlinq.html

O. 并发与异步
来源：http://dali.nanxinkj.top/Article/details/gt2ryeilmja.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2fzapevkc.html

[O01] 启动一个线程
来源：http://dali.pycfn.com/Article/details/gt2nkfygyrg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxinkj.top/Article/details/gt2fsbwmlja.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenzaomai.com/Article/details/gt2xoxwlarl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tianlin.xyz/Article/details/gt2ltygbqwf.html

TS:   // 同 JS
来源：http://dali.c1oappe.top/Article/details/gt2hmaubsao.html

Java: new Thread(() -> f()).start()
来源：http://dali.bjfxy.top/Article/details/gt2lkgcocwh.html

Go:   go f()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rbgecpdo.html

Ruby: Thread.new { f }
来源：http://dali.aibaodan.cn/Article/details/gt2bwxjhvgb.html

C#:   Task.Run(() => F());
来源：http://dali.yuanzhike.top/Article/details/gt2cxkvyhhz.html

[O02] 使用线程池
来源：http://dali.hywenlv.cn/Article/details/gt2tifwmyov.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aizwys.cn/Article/details/gt2sytfcmme.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.pycfn.com/Article/details/gt2pxpotdzq.html

JS:   // worker_threads 线程池
来源：http://dali.yanxiufei.cn/Article/details/gt2paxqllzu.html

TS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gt2pyirxqud.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hongshengwenyu.top/Article/details/gt2oworihbl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tianlin.xyz/Article/details/gt2hkroostp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.quarkkingdee.top/Article/details/gt2ftjtjtzq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yanxiufei.cn/Article/details/gt2zpxtnpay.html

[O03] 加锁保护共享数据
来源：http://dali.hywenlv.cn/Article/details/gt2abbpfvdn.html

Py:   with lock: shared += 1
来源：http://dali.yvedp.cn/Article/details/gt2skxkbrqh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ppjwa.cn/Article/details/gt2skhaljro.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cdnleiting.top/Article/details/gt2uyahbfks.html

TS:   // 同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gt2tlwugnxs.html

Java: synchronized (this) { shared++; }
来源：http://dali.yonumen.top/Article/details/gt2fmmncyax.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shangyingyoupin.top/Article/details/gt2fovyriem.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgufenzy.top/Article/details/gt2zdbqyqie.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gt2zgkfqkzq.html

[O04] 定义异步函数并等待
来源：http://dali.hysaishi.cn/Article/details/gt2zciapoic.html

Py:   async def f():⏎    await g()
来源：http://dali.dashuyun.cn/Article/details/gt2echyryax.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cdnleiting.top/Article/details/gt2odeuuxys.html

JS:   async function f() { await g(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vgjqrbjb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gt2aodmddsk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sxryk.cn/Article/details/gt2kcrylgxv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hnxiangtu.top/Article/details/gt2stfphetl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shuidangran.top/Article/details/gt2orobdkvj.html

C#:   async Task F() { await G(); }
来源：http://dali.xziqi.cn/Article/details/gt2cmiffgpo.html

[O05] 并发执行并等待全部完成
来源：http://dali.meibo888.top/Article/details/gt2hzmwrfzj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dashuyun.cn/Article/details/gt2hsyvxcgf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.316326.xyz/Article/details/gt2atnzpnyq.html

JS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gt2nmvgtwbd.html

TS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gt2ztbfzchu.html


<!-- 参考信息 -->