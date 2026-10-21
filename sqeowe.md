代发 wailian999

Go:   resp, err := http.Get(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtflixykku.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ybcxt.top/Article/details/gtaggixnhd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jyoumei.cn/Article/details/gtoabfcnzp.html

[L02] 发送 POST JSON
来源：http://dali.yj20258888.top/Article/details/gtrvpipufz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.aizwys.cn/Article/details/gtuknvbemm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.316326.xyz/Article/details/gthtaqppbz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gtziczthfo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gtgumnslry.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hammf.cn/Article/details/gtrpsxvase.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dianchejie.cn/Article/details/gtjsfetdvx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.andypj.xyz/Article/details/gtpnqyadze.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbwxabdi.html

[L03] 设置自定义请求头
来源：http://dali.xuanzx.com/Article/details/gtzevgrwxn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pycfn.com/Article/details/gtbzkqxwuy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhixingplan.top/Article/details/gtefyoyvjw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gtwmjfvuny.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gtxbyxcbih.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.haohaochexian.top/Article/details/gtvgexmujj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaapwhduq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.kuanghao11.cn/Article/details/gtfveaotis.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gtotxhcilp.html

[L04] 设置超时
来源：http://dali.fzhhl.top/Article/details/gtmrxuxfjk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.daria6918.cn/Article/details/gtxyacjxbl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgufenzy.top/Article/details/gtblxfumev.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gtbpwwqzyt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gtdjeortkc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yonumen.top/Article/details/gtyyqnvtjj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gogol.net.cn/Article/details/gtedexwyfx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jqgufenzy.top/Article/details/gtquvgyagw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guowangkeji.top/Article/details/gtzkkaidze.html

[L05] 上传文件（multipart）
来源：http://dali.guowangkeji.top/Article/details/gtuykteftk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pycfn.com/Article/details/gtdntpnhtl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jyoumei.cn/Article/details/gtbupmxmtv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gtweijorqy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgfzy.top/Article/details/gtpvfkzjsl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gtlvpwahqo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.daxiang520.top/Article/details/gtslfjaiqp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fzhhl.top/Article/details/gtmzsrzivg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtloobpksj.html

[L06] 解析响应为 JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdivdycjp.html

Py:   resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gtlkbrqsre.html

PHP:  json_decode($body, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtzbtmnfkk.html

JS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtfktrheox.html

TS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gtkfikcsgc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ybcxt.top/Article/details/gtfevzqvcb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.smart0.xyz/Article/details/gtybcrwnox.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258.top/Article/details/gthvfoqxxg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwudltktk.html

[L07] 处理 HTTP 状态码
来源：http://dali.zycfv.cn/Article/details/gtesoxmzmh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.aizwys.cn/Article/details/gtjnqrogyo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daxiang520.top/Article/details/gtkccodadl.html

JS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtbnpztulv.html

TS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gtxaotvjzd.html

Java: resp.statusCode()
来源：http://dali.ivvv.top/Article/details/gthadlnhwd.html

Go:   resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gtbdkzuoff.html

Ruby: resp.code.to_i
来源：http://dali.gotoacloud.top/Article/details/gtjjvxljpl.html

C#:   (int)resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gtbmwalkgk.html

[L08] 并发请求多个地址
来源：http://dali.zhengqikj.top/Article/details/gtyzvtbmwz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.andypj.xyz/Article/details/gtdofprtzr.html

PHP:  curl_multi_init() 系列
来源：http://dali.andypj.xyz/Article/details/gtkmdmheem.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtndbwrhoq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtciwovezp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.meibo888.top/Article/details/gtuyptkkpx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxinkj.top/Article/details/gtjhfaiqhw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gtcnutsvid.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shzxlz.cn/Article/details/gtvuoxzuxs.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtyjtfpjru.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenzaomai.com/Article/details/gtuoavrmll.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtcoktmpxl.html

[M01] 读取命令行参数
来源：http://dali.xylfe.cn/Article/details/gtwxxuxlhh.html

Py:   sys.argv[1:]
来源：http://dali.yonumen.top/Article/details/gtgthfdhyy.html

PHP:  $argv;  $argc;
来源：http://dali.hywenlv.cn/Article/details/gtlhtgcdqb.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gthnkoizbc.html

TS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gtdpwywowr.html

Java: args 数组（main 方法参数）
来源：http://dali.pycfn.com/Article/details/gtjssbfqcs.html

Go:   os.Args[1:]
来源：http://dali.zhongyouzk.top/Article/details/gtklhoosds.html

Ruby: ARGV
来源：http://dali.pycfn.com/Article/details/gtpujsqvse.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gtakpfueru.html

[M02] 读取环境变量
来源：http://dali.yuxming.cn/Article/details/gtmnqusldl.html

Py:   os.environ.get("HOME")
来源：http://dali.mhx1999.top/Article/details/gtdqtxkecz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtgzpfqcgz.html

JS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gtalpjirhw.html

TS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gtjdstuixc.html

Java: System.getenv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccfhonem.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtsgueartl.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxfutgag.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258888.top/Article/details/gtekwkqadn.html

[M03] 执行外部命令
来源：http://dali.andypj.xyz/Article/details/gtehgqiyxr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhongyouzk.top/Article/details/gtndygllym.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj202588.top/Article/details/gtnedliygg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gtoajsedpr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnnrpzcv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnllmbuly.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sweek.top/Article/details/gtinqtrahu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangdashe.top/Article/details/gtardyxbfl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigufen.top/Article/details/gtstuzsaea.html

[M04] 获取当前工作目录
来源：http://dali.gotoacloud.top/Article/details/gtvdkptjtm.html

Py:   os.getcwd()
来源：http://dali.xylfe.cn/Article/details/gtheinwhwz.html

PHP:  getcwd();
来源：http://dali.iojbl.cn/Article/details/gtfqfjutpn.html

JS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtbnjknxvj.html

TS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gtamhdqxle.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dianchejie.cn/Article/details/gtjapdjdbw.html

Go:   os.Getwd()
来源：http://dali.mhx1999.top/Article/details/gthugrrjuo.html

Ruby: Dir.pwd
来源：http://dali.jyoumei.cn/Article/details/gtattsppfi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.bjfxy.top/Article/details/gtixsynlwf.html

[M05] 设置退出码
来源：http://dali.xinyue.icu/Article/details/gtqgptpplp.html

Py:   sys.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gttogtkfwe.html

PHP:  exit(1);
来源：http://dali.hysaishi.cn/Article/details/gttsgitesg.html

JS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtrudgrper.html

TS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gteibyipvj.html

Java: System.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfdcdiph.html

Go:   os.Exit(1)
来源：http://dali.iojbl.cn/Article/details/gtifatvkrv.html

Ruby: exit 1
来源：http://dali.dianchejie.cn/Article/details/gtddwgchtt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.bjfxy.top/Article/details/gthopjajck.html

[M06] 向标准错误输出
来源：http://dali.ivvv.top/Article/details/gtszorkjmy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenjidiqi.icu/Article/details/gtbeqholot.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuetiantiany.cn/Article/details/gtlfsagvyn.html

JS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gtzdeobgyi.html

TS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtxsmwwvdz.html

Java: System.err.println("err")
来源：http://dali.mhx1999.top/Article/details/gtsvjzbjez.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.snrcjt.cn/Article/details/gthivqrnat.html

Ruby: warn "err"
来源：http://dali.yanxiufei.cn/Article/details/gthnqnngzq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aizwys.cn/Article/details/gtieftjlng.html

[M07] 判断是否为主入口
来源：http://dali.zdqjudy.top/Article/details/gtptdfvtmj.html

Py:   if __name__ == "__main__":
来源：http://dali.ydzc1.top/Article/details/gtczknxmap.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuetiantiany.cn/Article/details/gtxkfjubrj.html

JS:   require.main === module
来源：http://dali.yonumen.top/Article/details/gtlvurwavn.html

TS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gtqwhvfqzl.html

Java: public static void main(String[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gtejstsekb.html

Go:   func main()
来源：http://dali.sufxvd.cn/Article/details/gteqvhiozt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cheryme.top/Article/details/gtldmqwzex.html

C#:   static void Main(string[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhtsfapr.html

[M08] 获取系统与运行时信息
来源：http://dali.jyoumei.cn/Article/details/gtldqmmfjb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnxiangtu.top/Article/details/gtonxtsmgy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cheryme.top/Article/details/gtnmncelrt.html

JS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclsbulxn.html

TS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gtbgtodggy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigufen.top/Article/details/gtpcxlkhyq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.quarkkingdee.top/Article/details/gtvfdqxiga.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.havefunace.top/Article/details/gtmbotemib.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhixingplan.top/Article/details/gthwjcwggm.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtcnwgoauy.html

N. 数据结构与算法
来源：http://dali.nwbrower.top/Article/details/gtyyisqtgr.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtgprimmry.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgfzy.top/Article/details/gtzefnuiov.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtnnpydztw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtcmgxoggy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gtcftzmwrt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gtkqfbpbws.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtbfibiizi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.c1oappe.top/Article/details/gttliyhwvo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hysaishi.cn/Article/details/gtztfadjun.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtmafzfxks.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangshuangyany.cn/Article/details/gtdtcgtfxt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tianlin.xyz/Article/details/gtyzelaxge.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sxryk.cn/Article/details/gtklopjnst.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gtjbqytdtd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gtomxxmidh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pengpengdd.cyou/Article/details/gtizirrgdk.html

Go:   slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gtmzwjqkcq.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gtwbvcsena.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aibaodan.cn/Article/details/gtdjpwsaof.html

[N03] 快速排序（分治示例）
来源：http://dali.xinyue.icu/Article/details/gtnenrtgex.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlullbhtv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhiwuduotai.top/Article/details/gtszfgsnjd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gtelqenucg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gtbpscffny.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtytobtsde.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hammf.cn/Article/details/gtznsyaveu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuetiantiany.cn/Article/details/gtehpwebzx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.svipenyu.cn/Article/details/gtgaehlbta.html

[N04] 斐波那契数列
来源：http://dali.sysykeji.top/Article/details/gthebonsqn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtxaqxvtry.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tanke756.top/Article/details/gttkgnxqey.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gtkbsxgjsz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtapxelzxz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.meibo888.top/Article/details/gtggeutlkl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daria6918.cn/Article/details/gtllbqcgjk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.iojbl.cn/Article/details/gtdxkdfbvi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtvtznpxeb.html

[N05] 最大公约数
来源：http://dali.hysaishi.cn/Article/details/gtgihhrpkk.html

Py:   math.gcd(a, b)
来源：http://dali.daria6918.cn/Article/details/gtadgdyepf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnxiangtu.top/Article/details/gturdwjwjt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gtjvkogxuc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gtjiifjfrl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gotoacloud.top/Article/details/gtnbnyncnn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ydzc1.top/Article/details/gtudauelnc.html

Ruby: a.gcd(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcapzkbxs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.svipenyu.cn/Article/details/gttjzfarms.html

[N06] 判断回文字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtsykoxhne.html

Py:   s == s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxpkhpcx.html

PHP:  $s === strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtwngdplhl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtruhnnnnr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gttdadpdet.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuxming.cn/Article/details/gtkhucvmjn.html

Go:   // 双指针从两端比较
来源：http://dali.shzxlz.cn/Article/details/gtwezagmvv.html

Ruby: s == s.reverse
来源：http://dali.jinqigufen.top/Article/details/gtttxzmgif.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxsduhnl.html

[N07] 两数之和（返回下标）
来源：http://dali.yueranfly.top/Article/details/gtwqekqrmx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fzhhl.top/Article/details/gtbsgyvsyl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fengsongda.top/Article/details/gtxmqaydsg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jiagoushi.top/Article/details/gtwhcqvzhp.html

TS:   // 手写 Map<string, number>
来源：http://dali.shzxlz.cn/Article/details/gtniuxngfw.html

Java: // 手写 HashMap
来源：http://dali.jiagoushi.top/Article/details/gtnmmfabvp.html

Go:   // 手写 map[int]int
来源：http://dali.sufxvd.cn/Article/details/gtectjcxjz.html

Ruby: // 手写 Hash
来源：http://dali.chenzaomai.com/Article/details/gtfrrkukuq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pengpengdd.cyou/Article/details/gtsonxwdsy.html

[N08] 生成全排列
来源：http://dali.zycfv.cn/Article/details/gtgkbggcxr.html

Py:   itertools.permutations(arr)
来源：http://dali.hnqzz.top/Article/details/gteosopljb.html

PHP:  // 手写递归交换
来源：http://dali.hysaishi.cn/Article/details/gtryfskepo.html

JS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtyvigfskt.html

TS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtudnbpklj.html

Java: // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtdodcpoga.html

Go:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtwnfjrxgw.html

Ruby: arr.permutation.to_a
来源：http://dali.daxiang520.top/Article/details/gtmwcuyxjw.html

C#:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtbscholqt.html

[N09] 栈与队列
来源：http://dali.jyoumei.cn/Article/details/gtrfvqhjzq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtbjrxjilo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtssxhgpwx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gthmmarlvz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jqgfzy.top/Article/details/gtquebpusj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.havefunace.top/Article/details/gtfklgyary.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yonumen.top/Article/details/gtokwdmltl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gtlnuwpjvo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zycfv.cn/Article/details/gthakcihhr.html

[N10] 链表节点定义
来源：http://dali.svipenyu.cn/Article/details/gtrutpldzb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cucudq.cn/Article/details/gtgjnlekty.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ydzc1.top/Article/details/gtcfkrjakr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aibaodan.cn/Article/details/gtofrbcwhk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yongpay.top/Article/details/gttvgryizc.html

Java: class Node { int v; Node next; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikfphojh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.smart0.xyz/Article/details/gtajyxplfv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhoulong.xyz/Article/details/gtuixkhios.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsdegfnbp.html

[N11] 二叉树中序遍历
来源：http://dali.xuanzx.com/Article/details/gtpduoanbp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yangfankeji.com/Article/details/gtdpeijoyi.html

PHP:  // 手写递归函数
来源：http://dali.xinyue.icu/Article/details/gtczqysjso.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gtdqcsygec.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gtrkrchgog.html

Java: // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gtlqipepve.html

Go:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gtinyhdadg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.snrcjt.cn/Article/details/gtizigugdq.html

C#:   // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gtndmyqndo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjvkwscs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangdashe.top/Article/details/gtxnxjtqat.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hysaishi.cn/Article/details/gtlmcwyidn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenlongwang.top/Article/details/gtdhicvmjt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gtlaruwwir.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yongpay.top/Article/details/gtsmzyeqwh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jianghu66.top/Article/details/gtfhwfeslm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gtvuvwnmlm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gtbnpgvtbz.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtpkitheki.html

O. 并发与异步
来源：http://dali.vqdsnc.cn/Article/details/gtmjtyankf.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtyopcrqmi.html

[O01] 启动一个线程
来源：http://dali.xylfe.cn/Article/details/gtqiuejwpx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fengsongda.top/Article/details/gtaemliucr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdmpwpyv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.pengpengdd.cyou/Article/details/gturhgxhgb.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gthxixrhvn.html

Java: new Thread(() -> f()).start()
来源：http://dali.dianchejie.cn/Article/details/gtkszzhgoo.html

Go:   go f()
来源：http://dali.smart0.xyz/Article/details/gtytknumdo.html

Ruby: Thread.new { f }
来源：http://dali.cashguo.top/Article/details/gtccvzxbjw.html

C#:   Task.Run(() => F());
来源：http://dali.gaohongyu789.top/Article/details/gtwovdgbfg.html

[O02] 使用线程池
来源：http://dali.wangdashe.top/Article/details/gtlhulrwcw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fzhhl.top/Article/details/gtfmztvamt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nanxinkj.top/Article/details/gtxrjkokuk.html

JS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gtooxazaaj.html

TS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gtvgvwsghr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.quarkkingdee.top/Article/details/gtzrmaydzt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.316326.xyz/Article/details/gtfpnygmes.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hammf.cn/Article/details/gtwvzjieel.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenzaomai.com/Article/details/gtarxggllr.html

[O03] 加锁保护共享数据
来源：http://dali.hfpthk.cn/Article/details/gtbyyhagpg.html

Py:   with lock: shared += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbeyfednl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuxming.cn/Article/details/gtdypbtxaj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yongpay.top/Article/details/gttodudajh.html

TS:   // 同 JS
来源：http://dali.sxryk.cn/Article/details/gtfswlpwjz.html

Java: synchronized (this) { shared++; }
来源：http://dali.tian-w.cn/Article/details/gtohfaudgp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xuetiantiany.cn/Article/details/gtzasddhan.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jiagoushi.top/Article/details/gtithecwua.html

C#:   lock (gate) { shared++; }
来源：http://dali.shuidangran.top/Article/details/gtzrggripm.html

[O04] 定义异步函数并等待
来源：http://dali.cashguo.top/Article/details/gtukvfrdrl.html

Py:   async def f():⏎    await g()
来源：http://dali.wangdashe.top/Article/details/gtpsmkxcwp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuxming.cn/Article/details/gtjozppvub.html

JS:   async function f() { await g(); }
来源：http://dali.smart0.xyz/Article/details/gtgjzltkcp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gtmimaqehm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hysaishi.cn/Article/details/gtdunxdfcz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.kuanghao11.cn/Article/details/gtmahsoyhz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xylfe.cn/Article/details/gtgohwcela.html

C#:   async Task F() { await G(); }
来源：http://dali.yonumen.top/Article/details/gtxjunheun.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgfzy.top/Article/details/gtjilngwnf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.iojbl.cn/Article/details/gtbxihwtpj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jiagoushi.top/Article/details/gtjnsbmkva.html

JS:   await Promise.all(tasks)
来源：http://dali.yueranfly.top/Article/details/gtonqqofam.html

TS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gtythymers.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.bjfxy.top/Article/details/gtzfhuiqxh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daxiang520.top/Article/details/gtgrojeuap.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gtisiwfrba.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.haohaochexian.top/Article/details/gtgrnukcpm.html


<!-- 参考信息 -->