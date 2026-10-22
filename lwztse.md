代发 wailian999

L. 网络请求
来源：http://dali.daria6918.cn/Article/details/gtrdkuyobj.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtibcluvyj.html

[L01] 发送 GET 请求
来源：http://dali.sufxvd.cn/Article/details/gtuzizrvns.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.iojbl.cn/Article/details/gtnvrsemyw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhixingplan.top/Article/details/gtvamqctdc.html

JS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gtzbxomxqk.html

TS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gtxrfaurpp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shuidangran.top/Article/details/gtiteshgzk.html

Go:   resp, err := http.Get(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtibrklmzw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgfzy.top/Article/details/gtwukgphmh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtudvceyzc.html

[L02] 发送 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtjircxari.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zycfv.cn/Article/details/gtyhnihscr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.c1oappe.top/Article/details/gtcsmgoauq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gtwvyynesa.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gtsweadokw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hysaishi.cn/Article/details/gtlnnkllro.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgufenzy.top/Article/details/gthlbcobwn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dianchejie.cn/Article/details/gtixfbxnfw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.andypj.xyz/Article/details/gtywnvctci.html

[L03] 设置自定义请求头
来源：http://dali.ivvv.top/Article/details/gtdyjdzxnn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.snrcjt.cn/Article/details/gtfwrnqphn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtzuthctts.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gtjfnxptgc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gtvlfxzwle.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.aibaodan.cn/Article/details/gthwkzfcxx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gtciblqqdg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.bjfxy.top/Article/details/gtfdlrrcth.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gtxtndrlly.html

[L04] 设置超时
来源：http://dali.shanyushiyangtech.top/Article/details/gtomkiujlq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jiagoushi.top/Article/details/gtvhzswtph.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jyoumei.cn/Article/details/gtdlktedjp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gtfmmorzrc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gtinjajokv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dashuyun.cn/Article/details/gtohhftqav.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.c1oappe.top/Article/details/gtwebnhbpn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yanxiufei.cn/Article/details/gtehdhaztl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigufen.top/Article/details/gtwqugthie.html

[L05] 上传文件（multipart）
来源：http://dali.ydzc1.top/Article/details/gtjgevofyh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gogol.net.cn/Article/details/gtozahcuqq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.svipenyu.cn/Article/details/gturqotpix.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gtknnywwkp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jiagoushi.top/Article/details/gtbfbyxgwc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zdqjudy.top/Article/details/gtsmufchey.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hywenlv.cn/Article/details/gtquwneqkk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gaohongyu789.top/Article/details/gtrojsphau.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gzhubu.top/Article/details/gtounusmjr.html

[L06] 解析响应为 JSON
来源：http://dali.daxiang520.top/Article/details/gtpungcfkl.html

Py:   resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtxnooavsy.html

PHP:  json_decode($body, true);
来源：http://dali.zycfv.cn/Article/details/gtwitcyfrk.html

JS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gtmvmvzdix.html

TS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gtnlbzjvss.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guannengcc.top/Article/details/gtlxwymhba.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.mhx1999.top/Article/details/gtjvmzqqme.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258888.top/Article/details/gtpqlcluiu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258888.top/Article/details/gtwkhrkfqu.html

[L07] 处理 HTTP 状态码
来源：http://dali.yvedp.cn/Article/details/gttilqxfgd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.vqdsnc.cn/Article/details/gtmwjjqoii.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sweek.top/Article/details/gttelrqdvm.html

JS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gtllqvtvuv.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gtbjblwtqq.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gtnbzklfou.html

Go:   resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtzbdqpxty.html

Ruby: resp.code.to_i
来源：http://dali.vqdsnc.cn/Article/details/gteebttnne.html

C#:   (int)resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gtmukldmvb.html

[L08] 并发请求多个地址
来源：http://dali.cdnleiting.top/Article/details/gtdbqzdwsr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.vqdsnc.cn/Article/details/gtdtcayndm.html

PHP:  curl_multi_init() 系列
来源：http://dali.gogol.net.cn/Article/details/gtbjumloto.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtmplhgven.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gtmxckxijw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yangfankeji.com/Article/details/gtakeoidfw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gtdosfepfj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gtijvgfygl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cdnleiting.top/Article/details/gtlqczofwa.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtqeabknot.html

M. 命令行 / 进程 / 环境
来源：http://dali.0kj1m.cn/Article/details/gtjnvagbac.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtfakuwbds.html

[M01] 读取命令行参数
来源：http://dali.dashuyun.cn/Article/details/gtnosozvtt.html

Py:   sys.argv[1:]
来源：http://dali.sweek.top/Article/details/gtjneezoly.html

PHP:  $argv;  $argc;
来源：http://dali.ybcxt.top/Article/details/gtsbpfsmol.html

JS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gtackfcjwp.html

TS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtjmrityim.html

Java: args 数组（main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gtxxkrfrhn.html

Go:   os.Args[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtyvkftrva.html

Ruby: ARGV
来源：http://dali.zhongyouzk.top/Article/details/gtdytrctdi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sweek.top/Article/details/gtbeseqkrr.html

[M02] 读取环境变量
来源：http://dali.zdqjudy.top/Article/details/gthttxzthv.html

Py:   os.environ.get("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtlvxrwtuw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gttllmtvxh.html

JS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gtdokjoflp.html

TS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gtncawqdcv.html

Java: System.getenv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtchafbbpr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtqmkvfdhb.html

Ruby: ENV["HOME"]
来源：http://dali.guowangkeji.top/Article/details/gtatbhtucv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gtadbmeywn.html

[M03] 执行外部命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpavefed.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aizwys.cn/Article/details/gtolaqfwtt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ehwqpu.com/Article/details/gtqavfrxeg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjajxbndu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gtunvkcavr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cheryme.top/Article/details/gtyezpsffr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.mhx1999.top/Article/details/gtnpaobwap.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.snrcjt.cn/Article/details/gtxtsbtdcs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yongpay.top/Article/details/gtwzrhmhge.html

[M04] 获取当前工作目录
来源：http://dali.redwolf501.top/Article/details/gtemddhnpl.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gtaawjbvms.html

PHP:  getcwd();
来源：http://dali.ehwqpu.com/Article/details/gthtdgeuhr.html

JS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gtusliuuha.html

TS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtyaxxgmrc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sufxvd.cn/Article/details/gtlfpeggmx.html

Go:   os.Getwd()
来源：http://dali.yueranfly.top/Article/details/gtnzrsijie.html

Ruby: Dir.pwd
来源：http://dali.cashguo.top/Article/details/gtkyhyyutr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pengpengdd.cyou/Article/details/gtbupnlwna.html

[M05] 设置退出码
来源：http://dali.guowangkeji.top/Article/details/gtabflngho.html

Py:   sys.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtddzdbgyi.html

PHP:  exit(1);
来源：http://dali.shuidangran.top/Article/details/gtdjsbugyy.html

JS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtxyoeirzv.html

TS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gtwyweekfj.html

Java: System.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtjlpnwpli.html

Go:   os.Exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtvodgtprt.html

Ruby: exit 1
来源：http://dali.birdmap.top/Article/details/gtfupjwkmy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ivvv.top/Article/details/gtjmwxvgip.html

[M06] 向标准错误输出
来源：http://dali.jqgfzy.top/Article/details/gteksjshkf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpredsgad.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cdnleiting.top/Article/details/gtyxulrqdl.html

JS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gttqippfbe.html

TS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzoztbov.html

Java: System.err.println("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrpkwqqhr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhiwuduotai.top/Article/details/gtrwlfszbp.html

Ruby: warn "err"
来源：http://dali.snrcjt.cn/Article/details/gtkaocbwpt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtxzurresj.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtiqyhuh.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258888.top/Article/details/gtnyrevizu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.c1oappe.top/Article/details/gttwdagxxk.html

JS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gtwgkjvzte.html

TS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gthiprgmhd.html

Java: public static void main(String[] args)
来源：http://dali.ivvv.top/Article/details/gtnygatumf.html

Go:   func main()
来源：http://dali.9152youxi.cn/Article/details/gtjphjlawz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ehwqpu.com/Article/details/gtbakwilmw.html

C#:   static void Main(string[] args)
来源：http://dali.cashguo.top/Article/details/gtvfrqassh.html

[M08] 获取系统与运行时信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvtwlysm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yueranfly.top/Article/details/gtpbjqhugj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwlzuqdm.html

JS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gtqfzxyjky.html

TS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtgblofakq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shuidangran.top/Article/details/gtuwmdmoes.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxinkj.top/Article/details/gtuvbszpyl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnxiangtu.top/Article/details/gtweycxulg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgfzy.top/Article/details/gtywxhgqmm.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtmyykhkyq.html

N. 数据结构与算法
来源：http://dali.meibo888.top/Article/details/gtvcqpbaqy.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gthaplollg.html

[N01] 二分查找（有序数组）
来源：http://dali.vqdsnc.cn/Article/details/gtavsgysze.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tanke756.top/Article/details/gtjchffvhh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtrlzmxvbh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gtbfkqlmdl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gtmugsxing.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtwtwlpdxg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gthtmlkwlz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.vqdsnc.cn/Article/details/gteciwpbjh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtqgydsdwz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnxiangtu.top/Article/details/gtghifnyfg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gttbxrttce.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.smart0.xyz/Article/details/gtrhamdhce.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtyqqmhodj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzcpdsgo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aizwys.cn/Article/details/gtcthirapi.html

Go:   slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gtdhyqlyqw.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gttohjsitn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ybcxt.top/Article/details/gtbpjlxlzq.html

[N03] 快速排序（分治示例）
来源：http://dali.hammf.cn/Article/details/gtikchymli.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.havefunace.top/Article/details/gtrcxxvrbv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.dashuyun.cn/Article/details/gtopygqqkg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gtiygtcvsl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gtkulmogdq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj202588.top/Article/details/gtsbeqzwbq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tian-w.cn/Article/details/gtfhimrxtc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gaohongyu789.top/Article/details/gtfhoztlio.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ydzc1.top/Article/details/gtfhcsdbnw.html

[N04] 斐波那契数列
来源：http://dali.ehwqpu.com/Article/details/gthoeuzgjo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gtzogddgbp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuanzx.com/Article/details/gtbihksjyk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtepjubvoc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtgdkbnxjz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenjidiqi.icu/Article/details/gtpxtjzawy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gogol.net.cn/Article/details/gtghhtnmwk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gtjhfuyldv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gttsfvipgj.html

[N05] 最大公约数
来源：http://dali.jinghuilouyu.cn/Article/details/gthejycmqe.html

Py:   math.gcd(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gtrkljlcxy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pycfn.com/Article/details/gtawrbehsz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gthzuvvvis.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigufen.top/Article/details/gtjtchmtsc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.316326.xyz/Article/details/gtnldzxljn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guowangkeji.top/Article/details/gtnjlzcdle.html

Ruby: a.gcd(b)
来源：http://dali.iojbl.cn/Article/details/gtkjjsbwxv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.birdmap.top/Article/details/gtavrvgpvi.html

[N06] 判断回文字符串
来源：http://dali.yj202588.top/Article/details/gtdyztzawk.html

Py:   s == s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gtztqzvmnu.html

PHP:  $s === strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtbgixeldv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtjpxuifqv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtjqgnyokg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.quarkkingdee.top/Article/details/gtcktedswi.html

Go:   // 双指针从两端比较
来源：http://dali.316326.xyz/Article/details/gtqftcaimx.html

Ruby: s == s.reverse
来源：http://dali.yuanzhike.top/Article/details/gtjrifrzhq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gttlqrtdxr.html

[N07] 两数之和（返回下标）
来源：http://dali.cashguo.top/Article/details/gtcetphmmo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yanxiufei.cn/Article/details/gtbrgwgiyr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxinkj.top/Article/details/gtdkszbldg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhongyouzk.top/Article/details/gtyxcdcppt.html

TS:   // 手写 Map<string, number>
来源：http://dali.sufxvd.cn/Article/details/gtclbojkch.html

Java: // 手写 HashMap
来源：http://dali.gaohongyu789.top/Article/details/gtzxcfffes.html

Go:   // 手写 map[int]int
来源：http://dali.cheryme.top/Article/details/gtuihcnzkd.html

Ruby: // 手写 Hash
来源：http://dali.xinyue.icu/Article/details/gtojsbznwv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dianchejie.cn/Article/details/gtjxqgzyth.html

[N08] 生成全排列
来源：http://dali.aibaodan.cn/Article/details/gtjtqmhfub.html

Py:   itertools.permutations(arr)
来源：http://dali.xuanzx.com/Article/details/gtkceluycy.html

PHP:  // 手写递归交换
来源：http://dali.xuanzx.com/Article/details/gtekelucmr.html

JS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtciqwqzlp.html

TS:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtrdsfthsy.html

Java: // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtkpkjgnlp.html

Go:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtqomxaeeu.html

Ruby: arr.permutation.to_a
来源：http://dali.cashguo.top/Article/details/gtoghbuvak.html

C#:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtcmzxflta.html

[N09] 栈与队列
来源：http://dali.kuanghao11.cn/Article/details/gtdwofappf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jyoumei.cn/Article/details/gtvsxaricm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtusfpyfuc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gtwgpsovrs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hnqzz.top/Article/details/gtbesswnet.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.316326.xyz/Article/details/gtglpxnwfo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aizwys.cn/Article/details/gtxngllwro.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtuznuaxar.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.316326.xyz/Article/details/gtvfklckdm.html

[N10] 链表节点定义
来源：http://dali.havefunace.top/Article/details/gtswsvcmmp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgfzy.top/Article/details/gtyzeuxukl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cheryme.top/Article/details/gtxupejojb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shuidangran.top/Article/details/gtelojmpym.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gtajbezvly.html

Java: class Node { int v; Node next; }
来源：http://dali.gotoacloud.top/Article/details/gtviptiijh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ehwqpu.com/Article/details/gtfkvqcbiz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shangyingyoupin.top/Article/details/gtkpffcvty.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxuanxn.top/Article/details/gtlxdstshp.html

[N11] 二叉树中序遍历
来源：http://dali.quarkkingdee.top/Article/details/gtxlhjywgu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cheryme.top/Article/details/gtuqcvrton.html

PHP:  // 手写递归函数
来源：http://dali.cdnleiting.top/Article/details/gthlwzpsxv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pengpengdd.cyou/Article/details/gtwihbgupv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gtfulfizgh.html

Java: // 手写递归
来源：http://dali.cucudq.cn/Article/details/gtdbaojohb.html

Go:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gtojyevrlh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hysaishi.cn/Article/details/gtcyhjrszy.html

C#:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gtozkcdvpc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cheryme.top/Article/details/gtekvzffcg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hywenlv.cn/Article/details/gtddvlowrk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtldpzyv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gaohongyu789.top/Article/details/gthscqbqin.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gtjzpocqsj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gthmdhxqcd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.iojbl.cn/Article/details/gtymnqmbxi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.haohaochexian.top/Article/details/gthgcypbzf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gtkwkatvvw.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtaibubbqr.html

O. 并发与异步
来源：http://dali.dashuyun.cn/Article/details/gttsfkizmy.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtktgvcrkd.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gtoczmcmrr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuxming.cn/Article/details/gtmhwdkhym.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tianlin.xyz/Article/details/gteokblded.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hywenlv.cn/Article/details/gtohhzheon.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gtcwaxjnoo.html

Java: new Thread(() -> f()).start()
来源：http://dali.tian-w.cn/Article/details/gtneojlkes.html

Go:   go f()
来源：http://dali.tian-w.cn/Article/details/gtjuvcntgd.html

Ruby: Thread.new { f }
来源：http://dali.wangdashe.top/Article/details/gthjbrgsxc.html

C#:   Task.Run(() => F());
来源：http://dali.hnxiangtu.top/Article/details/gtcoqvvrje.html

[O02] 使用线程池
来源：http://dali.ybcxt.top/Article/details/gttamirxzo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.snrcjt.cn/Article/details/gtwdvomufu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daria6918.cn/Article/details/gtulywoydg.html

JS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gtaregfxms.html

TS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gtwiveoglj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daxiang520.top/Article/details/gtstyqlvra.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gogol.net.cn/Article/details/gtqfeexope.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cashguo.top/Article/details/gtfaduttcw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.dianchejie.cn/Article/details/gtpcalxifr.html

[O03] 加锁保护共享数据
来源：http://dali.cashguo.top/Article/details/gtnsmxlbod.html

Py:   with lock: shared += 1
来源：http://dali.nwbrower.top/Article/details/gtiavbpdeb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.daxiang520.top/Article/details/gttenhyvyq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sweek.top/Article/details/gtmdswckgh.html

TS:   // 同 JS
来源：http://dali.fzhhl.top/Article/details/gtpultziha.html

Java: synchronized (this) { shared++; }
来源：http://dali.redwolf501.top/Article/details/gtzjnssyyp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zdqjudy.top/Article/details/gtspxihkuv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shuidangran.top/Article/details/gtgjofxluo.html

C#:   lock (gate) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gtsmcmmibc.html

[O04] 定义异步函数并等待
来源：http://dali.shzxlz.cn/Article/details/gtrmaosqgw.html

Py:   async def f():⏎    await g()
来源：http://dali.316326.xyz/Article/details/gtpsxqtgar.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jlsjyb.cn/Article/details/gtcqfdbqpi.html

JS:   async function f() { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gtnzjtlqpv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xinyue.icu/Article/details/gtaldjophu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dianchejie.cn/Article/details/gtqxrefnfn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yueranfly.top/Article/details/gtzmgzwrkt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yuanzhike.top/Article/details/gtvibiwgpw.html

C#:   async Task F() { await G(); }
来源：http://dali.yuxming.cn/Article/details/gtjprqqpuu.html

[O05] 并发执行并等待全部完成
来源：http://dali.tanke756.top/Article/details/gtekpnatvf.html


<!-- 参考信息 -->