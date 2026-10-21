代发 wailian999

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cheryme.top/Article/details/gtuxglpvwz.html

JS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gtgnlaamny.html

TS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gtpppxrqyh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ivvv.top/Article/details/gteijxthbo.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj202588.top/Article/details/gtbikniurh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aizwys.cn/Article/details/gtxtqtlobf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ybcxt.top/Article/details/gtxmrxvvvo.html

[L02] 发送 POST JSON
来源：http://dali.bjfxy.top/Article/details/gtafhhqnjb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gtdfofqotx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.0kj1m.cn/Article/details/gtvxxwiizt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aibaodan.cn/Article/details/gtycuqvbhx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258.top/Article/details/gtxtdwtzrx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pycfn.com/Article/details/gtidtolwjl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dianchejie.cn/Article/details/gtrffvjuju.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cdnleiting.top/Article/details/gtpgrvmuen.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tanke756.top/Article/details/gtiykfnkxk.html

[L03] 设置自定义请求头
来源：http://dali.zhixingplan.top/Article/details/gtjsafozch.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gaohongyu789.top/Article/details/gtqdqnpska.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgfzy.top/Article/details/gttodxipyo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gtglmtdpmd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gtndqbvugl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258.top/Article/details/gtsmvjcays.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gtfpmqqwqo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.c1oappe.top/Article/details/gtamdwzudk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gteaolesjt.html

[L04] 设置超时
来源：http://dali.sysykeji.top/Article/details/gtdfgiqcoe.html

Py:   requests.get(url, timeout=5)
来源：http://dali.quarkkingdee.top/Article/details/gtxpblsnaw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.0kj1m.cn/Article/details/gttfpmuctm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gtiodvurqn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gttxqxqhnj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuanzhike.top/Article/details/gtryqqeclk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yongpay.top/Article/details/gteawdmdki.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hammf.cn/Article/details/gtsnqsizox.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fengsongda.top/Article/details/gtwezrmqhk.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258.top/Article/details/gtmhphsvic.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sufxvd.cn/Article/details/gtsvecmlpo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhiwuduotai.top/Article/details/gtzavzcteq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.havefunace.top/Article/details/gtfqpbxkqo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gtlpmkwqvs.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hysaishi.cn/Article/details/gtjjchdjzt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cdnleiting.top/Article/details/gtmrrxdkzf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yanxiufei.cn/Article/details/gtkwldcdhq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtiudyqmch.html

[L06] 解析响应为 JSON
来源：http://dali.jyoumei.cn/Article/details/gtusdzkowf.html

Py:   resp.json()
来源：http://dali.yj20258888.top/Article/details/gtcqllrutt.html

PHP:  json_decode($body, true);
来源：http://dali.jqgfzy.top/Article/details/gtbzwjttjs.html

JS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gthhostglu.html

TS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtmvjxlxdv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtexvrqtuw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.haohaochexian.top/Article/details/gtpvsvifny.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj202588.top/Article/details/gtgjhfvokb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yonumen.top/Article/details/gtpgrqgjjq.html

[L07] 处理 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnhbdqfq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.vqdsnc.cn/Article/details/gtrdzljwqg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtxzrpnnts.html

JS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gtediidfbq.html

TS:   resp.ok;  resp.status
来源：http://dali.feifeiyinyue.top/Article/details/gtsbncbfub.html

Java: resp.statusCode()
来源：http://dali.wangshuangyany.cn/Article/details/gtizfgvzev.html

Go:   resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gtbducdzxl.html

Ruby: resp.code.to_i
来源：http://dali.gogol.net.cn/Article/details/gtrhglhqio.html

C#:   (int)resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gttmhvacuf.html

[L08] 并发请求多个地址
来源：http://dali.cqqwz.cn/Article/details/gtnxyniojh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sxryk.cn/Article/details/gttrvnenpz.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhaomingkeji.xyz/Article/details/gteuvlwnsp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtyvrzitks.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtbbtpiksa.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigfzy.top/Article/details/gtbybzlwae.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhongyouzk.top/Article/details/gtawycessm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gtowlhbkvf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.mhx1999.top/Article/details/gtrotmorya.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtxcfffxla.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxuanxn.top/Article/details/gtszglzzsu.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtggultiwu.html

[M01] 读取命令行参数
来源：http://dali.sweek.top/Article/details/gtvzltmsmt.html

Py:   sys.argv[1:]
来源：http://dali.yj20258888.top/Article/details/gtgtoqjvnw.html

PHP:  $argv;  $argc;
来源：http://dali.sysykeji.top/Article/details/gtyqxzprbt.html

JS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gtwgsrrbwg.html

TS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gtuwjqhoph.html

Java: args 数组（main 方法参数）
来源：http://dali.ivvv.top/Article/details/gtyplbedey.html

Go:   os.Args[1:]
来源：http://dali.nanxuanxn.top/Article/details/gtfdkutifu.html

Ruby: ARGV
来源：http://dali.chenjidiqi.icu/Article/details/gtbbwetnox.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gtfkwyvhvl.html

[M02] 读取环境变量
来源：http://dali.daxiang520.top/Article/details/gtqaitriqy.html

Py:   os.environ.get("HOME")
来源：http://dali.daria6918.cn/Article/details/gtdxuzpens.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhjodyfy.html

JS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtxaylskkg.html

TS:   process.env.HOME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwelirdsr.html

Java: System.getenv("HOME")
来源：http://dali.hnqzz.top/Article/details/gtfgmujlti.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtphnbacmi.html

Ruby: ENV["HOME"]
来源：http://dali.shuidangran.top/Article/details/gtljfjcvgh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnqzz.top/Article/details/gtckttnups.html

[M03] 执行外部命令
来源：http://dali.jlsjyb.cn/Article/details/gtooxopzad.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxinkj.top/Article/details/gtipaoccxw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hysaishi.cn/Article/details/gthlzimxty.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gtmrlokxja.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gtgvoafoym.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pengpengdd.cyou/Article/details/gtjjcsfyvp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fzhhl.top/Article/details/gtyonfjxvq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.meibo888.top/Article/details/gtreejyqrd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yueranfly.top/Article/details/gtpbalpkhm.html

[M04] 获取当前工作目录
来源：http://dali.zhiwuduotai.top/Article/details/gtdtkgfsbk.html

Py:   os.getcwd()
来源：http://dali.9152youxi.cn/Article/details/gtzxlhnxjm.html

PHP:  getcwd();
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpovwjwa.html

JS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gttbyaswrg.html

TS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtxtebxgqn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.kuanghao11.cn/Article/details/gtnkszzalk.html

Go:   os.Getwd()
来源：http://dali.fzhhl.top/Article/details/gtdfellefh.html

Ruby: Dir.pwd
来源：http://dali.zhengqikj.top/Article/details/gtjrxxiogv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgufenzy.top/Article/details/gtyoxowkkd.html

[M05] 设置退出码
来源：http://dali.tanke756.top/Article/details/gtlogeozhp.html

Py:   sys.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtspqoccsx.html

PHP:  exit(1);
来源：http://dali.zdqjudy.top/Article/details/gttqohymvl.html

JS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtryjfbqpf.html

TS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtvrcxrdyb.html

Java: System.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtupjdaora.html

Go:   os.Exit(1)
来源：http://dali.ivvv.top/Article/details/gtpkzpwiyd.html

Ruby: exit 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvciluig.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.kuanghao11.cn/Article/details/gtehwbdsgr.html

[M06] 向标准错误输出
来源：http://dali.zhongyouzk.top/Article/details/gtnmpfvzal.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gogol.net.cn/Article/details/gtmwjwuruk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gtffazpohc.html

JS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gtqmehhvzi.html

TS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gtatbfwszc.html

Java: System.err.println("err")
来源：http://dali.redwolf501.top/Article/details/gtudeedavz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangshuangyany.cn/Article/details/gtcoqjqffp.html

Ruby: warn "err"
来源：http://dali.jqgufenzy.top/Article/details/gtkfliswna.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.snrcjt.cn/Article/details/gtvqcfayer.html

[M07] 判断是否为主入口
来源：http://dali.9152youxi.cn/Article/details/gtxxtczspz.html

Py:   if __name__ == "__main__":
来源：http://dali.sweek.top/Article/details/gtyzsaiwle.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangshuangyany.cn/Article/details/gtdcsfioth.html

JS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gtmurtdeio.html

TS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gtklufmuao.html

Java: public static void main(String[] args)
来源：http://dali.shuidangran.top/Article/details/gtsbedvroo.html

Go:   func main()
来源：http://dali.shangyingyoupin.top/Article/details/gtrlfhjwge.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.snrcjt.cn/Article/details/gtlsrpklmp.html

C#:   static void Main(string[] args)
来源：http://dali.jianghu66.top/Article/details/gtsvbvpqqq.html

[M08] 获取系统与运行时信息
来源：http://dali.kuanghao11.cn/Article/details/gtonyvqwst.html

Py:   platform.system();  platform.python_version()
来源：http://dali.andypj.xyz/Article/details/gtpukqgwmr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.meibo888.top/Article/details/gtjmcxyggr.html

JS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gtbtrpgnnn.html

TS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gtyytqonru.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hysaishi.cn/Article/details/gtvvkqulvx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xinyue.icu/Article/details/gtvkwnqhey.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xuetiantiany.cn/Article/details/gtbxsvkwom.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gtfodbjrtq.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtcehafgmy.html

N. 数据结构与算法
来源：http://dali.svipenyu.cn/Article/details/gtgocugtrj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtnaievthx.html

[N01] 二分查找（有序数组）
来源：http://dali.xuanzx.com/Article/details/gtlplfseht.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtqrvpkcpr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yvedp.cn/Article/details/gtbtxxkhkz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gtwcaasfjq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtdrarooyt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gttevzzysh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtpdqcnvhm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dianchejie.cn/Article/details/gtkbecuvfk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtoawatcit.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.haohaochexian.top/Article/details/gtvkxruudi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuanzhike.top/Article/details/gtwwyyvofg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jianghu66.top/Article/details/gttllwunho.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gtyutuhnrx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtfrqexlid.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jqgufenzy.top/Article/details/gtqpqvcrkm.html

Go:   slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gtdyamojgy.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gtnxthzjcl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xziqi.cn/Article/details/gtvzytvmvp.html

[N03] 快速排序（分治示例）
来源：http://dali.yj202588.top/Article/details/gtvwnodvzp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhiwuduotai.top/Article/details/gtsbgkgnop.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hysaishi.cn/Article/details/gtfiopbyen.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gtjqbmtgxk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ehwqpu.com/Article/details/gtwaoqkzdd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgufenzy.top/Article/details/gtssuweahd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yonumen.top/Article/details/gtpblpslyn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shuidangran.top/Article/details/gtkdelloql.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgufenzy.top/Article/details/gtklgnfscp.html

[N04] 斐波那契数列
来源：http://dali.pycfn.com/Article/details/gtlkbolnju.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gtlumyiqjr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.andypj.xyz/Article/details/gtzcojfdrx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtgiuyxrxy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtuxenxcpk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gtedpdgqqg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zdqjudy.top/Article/details/gtaudtgjth.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gtbhagfvhn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gtjcwaylct.html

[N05] 最大公约数
来源：http://dali.hnqzz.top/Article/details/gtnngjicrt.html

Py:   math.gcd(a, b)
来源：http://dali.cdnleiting.top/Article/details/gtishjkcty.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jlsjyb.cn/Article/details/gtvyymrokq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.bjfxy.top/Article/details/gtitbqjnzj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.vqdsnc.cn/Article/details/gtrsggbjbd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpasivbu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hongshengwenyu.top/Article/details/gtiihlivvp.html

Ruby: a.gcd(b)
来源：http://dali.tianlin.xyz/Article/details/gtkqqyfjlg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258.top/Article/details/gtmxpuhiyy.html

[N06] 判断回文字符串
来源：http://dali.hfpthk.cn/Article/details/gtnzssprcf.html

Py:   s == s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gtpdhdbwcg.html

PHP:  $s === strrev($s);
来源：http://dali.cheryme.top/Article/details/gtpyxgtlzx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtfsmfxwac.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhalvuye.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cucudq.cn/Article/details/gtkvkxnmza.html

Go:   // 双指针从两端比较
来源：http://dali.aibaodan.cn/Article/details/gttxsfjddf.html

Ruby: s == s.reverse
来源：http://dali.chenzaomai.com/Article/details/gtreiafpsm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gtcethgupc.html

[N07] 两数之和（返回下标）
来源：http://dali.meibo888.top/Article/details/gtleisqpgr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yangfankeji.com/Article/details/gtiypqffnd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.wangdashe.top/Article/details/gtxpkfkxwp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cucudq.cn/Article/details/gtciixqofu.html

TS:   // 手写 Map<string, number>
来源：http://dali.daxiang520.top/Article/details/gtfewiaurw.html

Java: // 手写 HashMap
来源：http://dali.birdmap.top/Article/details/gtaffnpxwv.html

Go:   // 手写 map[int]int
来源：http://dali.ybcxt.top/Article/details/gtpxnuojzm.html

Ruby: // 手写 Hash
来源：http://dali.ehwqpu.com/Article/details/gtjyeapepp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.kuanghao11.cn/Article/details/gtnyyntize.html

[N08] 生成全排列
来源：http://dali.dianchejie.cn/Article/details/gtojvznuha.html

Py:   itertools.permutations(arr)
来源：http://dali.wangdashe.top/Article/details/gtdyebrfih.html

PHP:  // 手写递归交换
来源：http://dali.iojbl.cn/Article/details/gtubovllau.html

JS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtgximbioz.html

TS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtkfmuqzrv.html

Java: // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtfszgqqpd.html

Go:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtkwokmpms.html

Ruby: arr.permutation.to_a
来源：http://dali.zhixingplan.top/Article/details/gtkfdfousj.html

C#:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtdhycuhel.html

[N09] 栈与队列
来源：http://dali.fengsongda.top/Article/details/gtmofugqgz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtgugfxykw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yongpay.top/Article/details/gtmjjxwdds.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tanke756.top/Article/details/gtxijrvxxc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.meibo888.top/Article/details/gtakvrtjqh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xziqi.cn/Article/details/gtqireogqa.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnxiangtu.top/Article/details/gtnqbmgwbq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sysykeji.top/Article/details/gtkykludkq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ivvv.top/Article/details/gtjjweigtc.html

[N10] 链表节点定义
来源：http://dali.hnxiangtu.top/Article/details/gtypmnploy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zdqjudy.top/Article/details/gtbinekkrb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhengqikj.top/Article/details/gtfmjtonhn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yangfankeji.com/Article/details/gtzufilrps.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.c1oappe.top/Article/details/gtjjvfquhs.html

Java: class Node { int v; Node next; }
来源：http://dali.cashguo.top/Article/details/gtwqzhjkwk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhoulong.xyz/Article/details/gtutnpghlc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xuanzx.com/Article/details/gtoeuysrla.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.smart0.xyz/Article/details/gtwuewflpf.html

[N11] 二叉树中序遍历
来源：http://dali.daria6918.cn/Article/details/gtkiwyqpmb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhongyouzk.top/Article/details/gtrdryyscc.html

PHP:  // 手写递归函数
来源：http://dali.hfpthk.cn/Article/details/gtntshyqnz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhoulong.xyz/Article/details/gtvgafecok.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gthvlkwgzj.html

Java: // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbysqlmg.html

Go:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtrfkwpeia.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuanzx.com/Article/details/gtwugczefh.html

C#:   // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gteenqvqkk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.pengpengdd.cyou/Article/details/gtbuovaxvy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sufxvd.cn/Article/details/gtaudkoaue.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhongyouzk.top/Article/details/gtpwfpbcfb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gtckhxotgq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gtfwnsnoxb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gtkqhvndel.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shzxlz.cn/Article/details/gtpukqnfaz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zdqjudy.top/Article/details/gtwatwefld.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gttqbcjseb.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtmvgiuepn.html

O. 并发与异步
来源：http://dali.chenzaomai.com/Article/details/gtutwtjojm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtdavxlibx.html

[O01] 启动一个线程
来源：http://dali.zycfv.cn/Article/details/gtytiopuml.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daxiang520.top/Article/details/gtlbdaaaax.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hywenlv.cn/Article/details/gtwzjdljou.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangdashe.top/Article/details/gtpwratzlh.html

TS:   // 同 JS
来源：http://dali.gzhubu.top/Article/details/gtykedaimz.html

Java: new Thread(() -> f()).start()
来源：http://dali.jyoumei.cn/Article/details/gtphhqiscw.html

Go:   go f()
来源：http://dali.hammf.cn/Article/details/gtnsopecyz.html

Ruby: Thread.new { f }
来源：http://dali.havefunace.top/Article/details/gtgptdokhu.html

C#:   Task.Run(() => F());
来源：http://dali.nanxinkj.top/Article/details/gtgmjbxftl.html

[O02] 使用线程池
来源：http://dali.nwbrower.top/Article/details/gtiwwokaam.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aizwys.cn/Article/details/gtukxyrvzp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sufxvd.cn/Article/details/gtsdpryjde.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258.top/Article/details/gtpxvphadf.html

TS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gtylifwagf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jianghu66.top/Article/details/gtqncygwab.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhiwuduotai.top/Article/details/gtudsjligb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nanxinkj.top/Article/details/gtfdquuxui.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ydzc1.top/Article/details/gtmzrnckwc.html

[O03] 加锁保护共享数据
来源：http://dali.yuanzhike.top/Article/details/gtxtarsixr.html

Py:   with lock: shared += 1
来源：http://dali.quarkkingdee.top/Article/details/gtypdhpdwt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jiagoushi.top/Article/details/gtjsmuffir.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.aibaodan.cn/Article/details/gtmnpwjvmt.html

TS:   // 同 JS
来源：http://dali.yongpay.top/Article/details/gtgzercwhx.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtysbumovj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.c1oappe.top/Article/details/gtnmdeqbhc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenlongwang.top/Article/details/gtgealxuwq.html

C#:   lock (gate) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gtfkcvlacw.html

[O04] 定义异步函数并等待
来源：http://dali.ydzc1.top/Article/details/gttlejlurz.html

Py:   async def f():⏎    await g()
来源：http://dali.meibo888.top/Article/details/gtvhwkoivz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ybcxt.top/Article/details/gtyfuwwylp.html

JS:   async function f() { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gttptjnmiu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.havefunace.top/Article/details/gtloychnyp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigfzy.top/Article/details/gtknkkoxrt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.svipenyu.cn/Article/details/gtsltgesuh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yongpay.top/Article/details/gtnfpozsdv.html

C#:   async Task F() { await G(); }
来源：http://dali.aizwys.cn/Article/details/gtahwnieph.html

[O05] 并发执行并等待全部完成
来源：http://dali.hysaishi.cn/Article/details/gtdqapmpje.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqivmxgmt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pycfn.com/Article/details/gtetdqmmaf.html

JS:   await Promise.all(tasks)
来源：http://dali.chenzaomai.com/Article/details/gtkopvjpre.html

TS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtlcjvpjjm.html


<!-- 参考信息 -->