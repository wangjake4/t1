代发 wailian999

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hysaishi.cn/Article/details/gtvswvrljk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.quarkkingdee.top/Article/details/gtuuzpxpwt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gtzpzkjmzt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gtzjrolyip.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gtqtmucfcx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinghuilouyu.cn/Article/details/gtldyzbglb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gtjfmsspiz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hnxiangtu.top/Article/details/gtpfjcckdp.html

[L03] 设置自定义请求头
来源：http://dali.svipenyu.cn/Article/details/gtlukshbii.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnxiangtu.top/Article/details/gtdqfneact.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xziqi.cn/Article/details/gtduwlmkqc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoicfhrkj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gtsauuoqir.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuanzx.com/Article/details/gtirkzjzrm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gtastyurvy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenzaomai.com/Article/details/gtqhuftjig.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gtlpbxofhz.html

[L04] 设置超时
来源：http://dali.fengsongda.top/Article/details/gtznndyojh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.andypj.xyz/Article/details/gtlpyreglo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigufen.top/Article/details/gtezssuplc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gtrszuhrts.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gtupwzrkcb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ivvv.top/Article/details/gttnnhpkab.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gtgevitylr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.9152youxi.cn/Article/details/gtglkvrsxu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzboeniq.html

[L05] 上传文件（multipart）
来源：http://dali.yvedp.cn/Article/details/gtxzeelwtd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hysaishi.cn/Article/details/gtgqkjwkvm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zdqjudy.top/Article/details/gtsgkmhjqo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjvvykrh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gtnusmvept.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlaptpvc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhixingplan.top/Article/details/gtcxjmmsyf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.feifeiyinyue.top/Article/details/gtvoeujsbf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtwwipkzcz.html

[L06] 解析响应为 JSON
来源：http://dali.redwolf501.top/Article/details/gtkjrslsbf.html

Py:   resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzorjxcrm.html

PHP:  json_decode($body, true);
来源：http://dali.kuanghao11.cn/Article/details/gttdpadvpz.html

JS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gtihlevzzr.html

TS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gtzxqiwmjm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfonmpaie.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tian-w.cn/Article/details/gtnmueowxj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.haohaochexian.top/Article/details/gtzqjnwbtp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gzhubu.top/Article/details/gtebcqukkk.html

[L07] 处理 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gtlcuszckn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovziifth.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cqqwz.cn/Article/details/gtcodhcajx.html

JS:   resp.ok;  resp.status
来源：http://dali.xuetiantiany.cn/Article/details/gteambbwzc.html

TS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtxijomsqv.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gtevkrhurh.html

Go:   resp.StatusCode
来源：http://dali.aibaodan.cn/Article/details/gtendpmtks.html

Ruby: resp.code.to_i
来源：http://dali.tanke756.top/Article/details/gtacxaivjy.html

C#:   (int)resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gtosdmgrtq.html

[L08] 并发请求多个地址
来源：http://dali.xylfe.cn/Article/details/gtggmfynnf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ppjwa.cn/Article/details/gtiblbswsr.html

PHP:  curl_multi_init() 系列
来源：http://dali.ppjwa.cn/Article/details/gtncloiiix.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gtfjlwoetb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gtbtbtiiyf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shuidangran.top/Article/details/gthvrgrxju.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhiwuduotai.top/Article/details/gtyxyawtzi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sysykeji.top/Article/details/gtdnseeyhc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.andypj.xyz/Article/details/gtrwbmioay.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gttyvuyooy.html

M. 命令行 / 进程 / 环境
来源：http://dali.xuetiantiany.cn/Article/details/gteolcyffm.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtiaetkaxd.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gtyiwtfdeh.html

Py:   sys.argv[1:]
来源：http://dali.sufxvd.cn/Article/details/gtferfxpjr.html

PHP:  $argv;  $argc;
来源：http://dali.yanxiufei.cn/Article/details/gtlbwyazps.html

JS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtwyjfarzg.html

TS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gtondkpodo.html

Java: args 数组（main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gtijhonzwp.html

Go:   os.Args[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbprofwj.html

Ruby: ARGV
来源：http://dali.yj20258888.top/Article/details/gtrbtfpupq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtujmazldh.html

[M02] 读取环境变量
来源：http://dali.yj20258888.top/Article/details/gtuodsnhyz.html

Py:   os.environ.get("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzgsrmeo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gtdggnclrp.html

JS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gtphlvtbca.html

TS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtbyvyrdkh.html

Java: System.getenv("HOME")
来源：http://dali.redwolf501.top/Article/details/gtmyqivjbq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pycfn.com/Article/details/gtyvosxumz.html

Ruby: ENV["HOME"]
来源：http://dali.wangshuangyany.cn/Article/details/gtnfalpkqm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtvrwccdsa.html

[M03] 执行外部命令
来源：http://dali.jinqigfzy.top/Article/details/gtdxvdmnog.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnxiangtu.top/Article/details/gtzflwifen.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.svipenyu.cn/Article/details/gtbujscisr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtpoccwgsi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gtdxfizsje.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ybcxt.top/Article/details/gtxjmgzwbz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxinkj.top/Article/details/gtptikesly.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guannengcc.top/Article/details/gtlqticjsh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pengpengdd.cyou/Article/details/gtcdsszlzf.html

[M04] 获取当前工作目录
来源：http://dali.sweek.top/Article/details/gtuvrzibpy.html

Py:   os.getcwd()
来源：http://dali.yuxming.cn/Article/details/gtslsjwgzn.html

PHP:  getcwd();
来源：http://dali.pengpengdd.cyou/Article/details/gttevpweec.html

JS:   process.cwd()
来源：http://dali.daria6918.cn/Article/details/gthqcwznzf.html

TS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gtndahjjws.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shangyingyoupin.top/Article/details/gtidhzzxun.html

Go:   os.Getwd()
来源：http://dali.hysaishi.cn/Article/details/gtuxxbrgel.html

Ruby: Dir.pwd
来源：http://dali.tanke756.top/Article/details/gtqdajfzpc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ppjwa.cn/Article/details/gtpcoyzssu.html

[M05] 设置退出码
来源：http://dali.shuidangran.top/Article/details/gtlwkabshj.html

Py:   sys.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtdxwkglji.html

PHP:  exit(1);
来源：http://dali.svipenyu.cn/Article/details/gtyzfojwdt.html

JS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtjlqvnuhg.html

TS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtefoevygn.html

Java: System.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtirwlxugk.html

Go:   os.Exit(1)
来源：http://dali.meibo888.top/Article/details/gtexzlpzab.html

Ruby: exit 1
来源：http://dali.fengsongda.top/Article/details/gteskgkvvk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.redwolf501.top/Article/details/gtrurzfzfr.html

[M06] 向标准错误输出
来源：http://dali.tanke756.top/Article/details/gtszmixeee.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hongshengwenyu.top/Article/details/gtlaeeehpe.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqofoynfk.html

JS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gtgqobtvsd.html

TS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gtzfmlmmvn.html

Java: System.err.println("err")
来源：http://dali.sufxvd.cn/Article/details/gtubxzceke.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgufenzy.top/Article/details/gtktdkacmd.html

Ruby: warn "err"
来源：http://dali.yj202588.top/Article/details/gthoenzaiv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aizwys.cn/Article/details/gtyhkexxmo.html

[M07] 判断是否为主入口
来源：http://dali.sysykeji.top/Article/details/gttouxekmo.html

Py:   if __name__ == "__main__":
来源：http://dali.hnqzz.top/Article/details/gtodvpejcd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.snrcjt.cn/Article/details/gtjvkczozw.html

JS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnwqvkek.html

TS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gtcnjzlztp.html

Java: public static void main(String[] args)
来源：http://dali.tianlin.xyz/Article/details/gtczzksdnq.html

Go:   func main()
来源：http://dali.chenjidiqi.icu/Article/details/gtopvrvaps.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.mhx1999.top/Article/details/gtquxdvmfx.html

C#:   static void Main(string[] args)
来源：http://dali.yj202588.top/Article/details/gthlrrmcpp.html

[M08] 获取系统与运行时信息
来源：http://dali.shangyingyoupin.top/Article/details/gtpvzgkgrc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nanxuanxn.top/Article/details/gtduvjdilg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigufen.top/Article/details/gtdcnmitim.html

JS:   process.platform;  process.version
来源：http://dali.zhixingplan.top/Article/details/gtbjepxdiw.html

TS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gtigoxegxw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dashuyun.cn/Article/details/gtqcausstq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pengpengdd.cyou/Article/details/gteznzvdnm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guowangkeji.top/Article/details/gtcuwfcbgb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.havefunace.top/Article/details/gtaukkgckz.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtsoqodfyz.html

N. 数据结构与算法
来源：http://dali.iojbl.cn/Article/details/gtjznoltyv.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtrsdrzssc.html

[N01] 二分查找（有序数组）
来源：http://dali.quarkkingdee.top/Article/details/gtbnzimtfx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtdoejesab.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtvikbpqwq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhrpkuww.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gtkazeymbj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtealupnkl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtioxrfpyf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuanzx.com/Article/details/gtgqykxeer.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtzfprcipz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ivvv.top/Article/details/gtrtfhhdye.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gtzktxdnsl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.c1oappe.top/Article/details/gtsngenmtz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gtezvfgqvr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.redwolf501.top/Article/details/gttpnkgyjm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zycfv.cn/Article/details/gtvlblvzhc.html

Go:   slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gtdatyjprx.html

Ruby: arr.sort
来源：http://dali.daria6918.cn/Article/details/gtdhrkilom.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj202588.top/Article/details/gtqsdlxvjb.html

[N03] 快速排序（分治示例）
来源：http://dali.ppjwa.cn/Article/details/gtjajpzamj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aibaodan.cn/Article/details/gtpjzrezyw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuetiantiany.cn/Article/details/gtdrhxajsq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gtbnjrnkvk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gttjxuddnd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.pengpengdd.cyou/Article/details/gtusazxnoi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dianchejie.cn/Article/details/gtsahspbip.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmoygoeyu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yueranfly.top/Article/details/gtnhwwszey.html

[N04] 斐波那契数列
来源：http://dali.nanxinkj.top/Article/details/gtpgptdlai.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gtydpdxxad.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dashuyun.cn/Article/details/gtmygoyuaf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gtytlhzzim.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtcdtnxppz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangdashe.top/Article/details/gtttvuxuyu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jlsjyb.cn/Article/details/gtyxlgrdqw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gtrptepwsp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gtgqwgvajx.html

[N05] 最大公约数
来源：http://dali.hnqzz.top/Article/details/gtoqfodecq.html

Py:   math.gcd(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gthbhjjbwi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hywenlv.cn/Article/details/gteiugtiyp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gttsmwrksu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gthzitebwx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cdnleiting.top/Article/details/gtmrrtzwjn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhoulong.xyz/Article/details/gtnczgrclo.html

Ruby: a.gcd(b)
来源：http://dali.smart0.xyz/Article/details/gtbrfymsbv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fengsongda.top/Article/details/gtuuokqtlj.html

[N06] 判断回文字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtzegwuayq.html

Py:   s == s[::-1]
来源：http://dali.mhx1999.top/Article/details/gtipkoibtm.html

PHP:  $s === strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtpsuqwrcs.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gttdhedgbs.html

TS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtfnikwive.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangshuangyany.cn/Article/details/gtwqmyzuxy.html

Go:   // 双指针从两端比较
来源：http://dali.yonumen.top/Article/details/gtcpdimuhu.html

Ruby: s == s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtozufkcan.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gtdmepbazb.html

[N07] 两数之和（返回下标）
来源：http://dali.hnxiangtu.top/Article/details/gtrerzjjke.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guannengcc.top/Article/details/gtocgbahta.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.chenzaomai.com/Article/details/gtkiyuogcp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cqqwz.cn/Article/details/gtfelrxkld.html

TS:   // 手写 Map<string, number>
来源：http://dali.meibo888.top/Article/details/gtuaczftrm.html

Java: // 手写 HashMap
来源：http://dali.smart0.xyz/Article/details/gtxyqrhgzg.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpcatjtu.html

Ruby: // 手写 Hash
来源：http://dali.yongpay.top/Article/details/gtqomratne.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hfpthk.cn/Article/details/gtaamtxgpk.html

[N08] 生成全排列
来源：http://dali.aizwys.cn/Article/details/gtckufxrbx.html

Py:   itertools.permutations(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyklypvjk.html

PHP:  // 手写递归交换
来源：http://dali.quarkkingdee.top/Article/details/gtkdbdlgaw.html

JS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtxjdfdugu.html

TS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtgvpzetjg.html

Java: // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtcneyhlvr.html

Go:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtjskocgyd.html

Ruby: arr.permutation.to_a
来源：http://dali.yuxming.cn/Article/details/gtwygzdpph.html

C#:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtkwlqytkj.html

[N09] 栈与队列
来源：http://dali.sxryk.cn/Article/details/gtwhuruvoj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jiagoushi.top/Article/details/gttpqhywxe.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gtxhbqxjbv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gtjtjurrec.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.pycfn.com/Article/details/gtuvfbzkyb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cqqwz.cn/Article/details/gtfojrsipq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gogol.net.cn/Article/details/gtqifweuua.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtzmtpzfnk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258.top/Article/details/gterxjhaca.html

[N10] 链表节点定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixqaidyu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.haohaochexian.top/Article/details/gttnywsukp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.smart0.xyz/Article/details/gtwrkkidfg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.dianchejie.cn/Article/details/gtyszfzbqc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ppjwa.cn/Article/details/gtyarsiyav.html

Java: class Node { int v; Node next; }
来源：http://dali.dashuyun.cn/Article/details/gtpraiptjw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gtgmwiwtjl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoujyecjv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yongpay.top/Article/details/gtumuikkhj.html

[N11] 二叉树中序遍历
来源：http://dali.hysaishi.cn/Article/details/gtbmwejhwj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daria6918.cn/Article/details/gtrxgicfnw.html

PHP:  // 手写递归函数
来源：http://dali.mhx1999.top/Article/details/gtxdjvxycx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gtxvnujugu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gtimdlyrzp.html

Java: // 手写递归
来源：http://dali.cashguo.top/Article/details/gtfuiqgiin.html

Go:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcbcinso.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guowangkeji.top/Article/details/gtbiamvflv.html

C#:   // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gtdvqvwwub.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhixingplan.top/Article/details/gtwlafowtc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cucudq.cn/Article/details/gtrvxtuoaw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.guowangkeji.top/Article/details/gtxccqtdap.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gtyhmsqcwi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gtwxyseehl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gtpmtaioid.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gotoacloud.top/Article/details/gtxdvzqvql.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.guannengcc.top/Article/details/gtpwjpolqn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.smart0.xyz/Article/details/gtgbxrqmqu.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gteenphxem.html

O. 并发与异步
来源：http://dali.jiagoushi.top/Article/details/gtqhnvgxzv.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtczbwnxrx.html

[O01] 启动一个线程
来源：http://dali.ydzc1.top/Article/details/gtwfvrhzbp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gzhubu.top/Article/details/gthztvbiyo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hfpthk.cn/Article/details/gtlksjjjla.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.mhx1999.top/Article/details/gtumadekfs.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gthiaaxvjc.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhoulong.xyz/Article/details/gtlltogxdp.html

Go:   go f()
来源：http://dali.smart0.xyz/Article/details/gtqhabbfep.html

Ruby: Thread.new { f }
来源：http://dali.hammf.cn/Article/details/gtdkxibkle.html

C#:   Task.Run(() => F());
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbjgwzmu.html

[O02] 使用线程池
来源：http://dali.tianlin.xyz/Article/details/gtrtveqvys.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ydzc1.top/Article/details/gtersjpxwv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guannengcc.top/Article/details/gtopeodfks.html

JS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gtszyzvyxn.html

TS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gtdykgfcvo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.smart0.xyz/Article/details/gtlufrwrgi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cashguo.top/Article/details/gtkfldyzll.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.mhx1999.top/Article/details/gtyfanxcbh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ybcxt.top/Article/details/gtbazxfrfc.html

[O03] 加锁保护共享数据
来源：http://dali.daxiang520.top/Article/details/gtphmfeyto.html

Py:   with lock: shared += 1
来源：http://dali.havefunace.top/Article/details/gthqnznwvk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hysaishi.cn/Article/details/gtrmiqhetl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gtkbhntqfs.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gtfmhsazyb.html

Java: synchronized (this) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gtnukbdzzr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkejvwgiy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gogol.net.cn/Article/details/gthmfqvifh.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj202588.top/Article/details/gtxtovzvcq.html

[O04] 定义异步函数并等待
来源：http://dali.yonumen.top/Article/details/gttayzpjqe.html

Py:   async def f():⏎    await g()
来源：http://dali.xuetiantiany.cn/Article/details/gtrtfnxosj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.smart0.xyz/Article/details/gtbuothpvu.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258.top/Article/details/gtpxhlqfqh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ybcxt.top/Article/details/gttmprecsp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangdashe.top/Article/details/gtlqcloafh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.redwolf501.top/Article/details/gtxthdhtjh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daxiang520.top/Article/details/gtmdsjxepc.html

C#:   async Task F() { await G(); }
来源：http://dali.sweek.top/Article/details/gtucssaygd.html

[O05] 并发执行并等待全部完成
来源：http://dali.c1oappe.top/Article/details/gthfoopgju.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ivvv.top/Article/details/gttewzbqqj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gtxudtawde.html

JS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gtmfzdcvow.html

TS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gtikxbenkw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hysaishi.cn/Article/details/gtrzrstrgt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yanxiufei.cn/Article/details/gtlvqadhvm.html

Ruby: threads.map(&:join)
来源：http://dali.sweek.top/Article/details/gthafouqbc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gterpdqezs.html

[O06] 使用进程池
来源：http://dali.snrcjt.cn/Article/details/gtybcsqzvd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xziqi.cn/Article/details/gtgdimurex.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.aizwys.cn/Article/details/gtnejlzmhj.html

JS:   // child_process / cluster 模块
来源：http://dali.sufxvd.cn/Article/details/gtlqvrthde.html


<!-- 参考信息 -->