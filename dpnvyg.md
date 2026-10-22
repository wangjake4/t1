代发 wailian999

Go:   resp, err := http.Get(url)
来源：http://dali.iojbl.cn/Article/details/gtkacmxizc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ppjwa.cn/Article/details/gtxfoukxhs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj20258.top/Article/details/gtayucbjja.html

[L02] 发送 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmvbjono.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gtewwjrike.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ppjwa.cn/Article/details/gtixsizzcw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gtkgrqycba.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gtzzkcrfdg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkudotpp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zdqjudy.top/Article/details/gtteqoffxi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.smart0.xyz/Article/details/gtyknuuxhx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fengsongda.top/Article/details/gtvkfddxvh.html

[L03] 设置自定义请求头
来源：http://dali.mhx1999.top/Article/details/gtsfkwkwum.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenjidiqi.icu/Article/details/gtaszywvtv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pycfn.com/Article/details/gtfoqfcpmo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gtjynatszw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gtjfpfhpoh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxozcopt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhoulong.xyz/Article/details/gtxzxsemwz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guannengcc.top/Article/details/gtfdgmpwvh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gtaloiespo.html

[L04] 设置超时
来源：http://dali.yonumen.top/Article/details/gtnkaueggo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.pycfn.com/Article/details/gtpsfaupiw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.quarkkingdee.top/Article/details/gtekkucked.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.haohaochexian.top/Article/details/gtdduetrnu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gtffuzxmbe.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigufen.top/Article/details/gtnpesxwxu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258888.top/Article/details/gthnpodgpf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknjigcyj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tian-w.cn/Article/details/gtfqdnzooc.html

[L05] 上传文件（multipart）
来源：http://dali.hammf.cn/Article/details/gtgncevcma.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gttwyflaun.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.meibo888.top/Article/details/gtkqzzdklh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gtvekqwonj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sxryk.cn/Article/details/gtymxavapv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guannengcc.top/Article/details/gtslqgatfb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ydzc1.top/Article/details/gtbgcyzryk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.birdmap.top/Article/details/gtozhtefeu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtajssdfro.html

[L06] 解析响应为 JSON
来源：http://dali.birdmap.top/Article/details/gtscbuavwn.html

Py:   resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtegpgmhdd.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gtbmhikkgr.html

JS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gtkfaetdea.html

TS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gtwsnbosyl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gtcjcquhor.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zdqjudy.top/Article/details/gtvqvjamno.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aizwys.cn/Article/details/gtkiwriwfi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gtmranydmg.html

[L07] 处理 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gtbkaruhby.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangshuangyany.cn/Article/details/gtfttwykyk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cucudq.cn/Article/details/gtywvwloft.html

JS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gtdjrlpeqi.html

TS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gtdjekfgbf.html

Java: resp.statusCode()
来源：http://dali.xylfe.cn/Article/details/gtqqqzsdwk.html

Go:   resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gtuvxelaqz.html

Ruby: resp.code.to_i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwoaabqm.html

C#:   (int)resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gtkjwmfqhv.html

[L08] 并发请求多个地址
来源：http://dali.wangdashe.top/Article/details/gtucogxacp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tian-w.cn/Article/details/gtrzpmloey.html

PHP:  curl_multi_init() 系列
来源：http://dali.feifeiyinyue.top/Article/details/gtwkpwyxbb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gthwykwjfi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gtpkokmlos.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuanzx.com/Article/details/gtjsxntkxr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xylfe.cn/Article/details/gtjldysmah.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shangyingyoupin.top/Article/details/gtkbytrxdn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj202588.top/Article/details/gtktkvpynv.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtyusgqkvh.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj202588.top/Article/details/gtehhfhyxm.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtrnndzcpp.html

[M01] 读取命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gtcuchhiqe.html

Py:   sys.argv[1:]
来源：http://dali.ivvv.top/Article/details/gtvmtdtgbd.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwkoirny.html

JS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtfeqpluhd.html

TS:   process.argv.slice(2)
来源：http://dali.hnxiangtu.top/Article/details/gtrzlqwvcw.html

Java: args 数组（main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gtjgyerbqg.html

Go:   os.Args[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gtvddjwgoo.html

Ruby: ARGV
来源：http://dali.haohaochexian.top/Article/details/gtlueefqsc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gtuksepaks.html

[M02] 读取环境变量
来源：http://dali.zhengqikj.top/Article/details/gtfqrwvnon.html

Py:   os.environ.get("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtrxfhvdhp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gthwjhigtj.html

JS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gtvxoxwmty.html

TS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtleqgyrvr.html

Java: System.getenv("HOME")
来源：http://dali.yueranfly.top/Article/details/gtxynfjden.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtedmgockb.html

Ruby: ENV["HOME"]
来源：http://dali.c1oappe.top/Article/details/gtflchosjb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ydzc1.top/Article/details/gtlcsqrqfl.html

[M03] 执行外部命令
来源：http://dali.daxiang520.top/Article/details/gthqzripfk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuxming.cn/Article/details/gthbbdqsmt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yonumen.top/Article/details/gtyweqsthq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gtallavsen.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzifqjhlh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shangyingyoupin.top/Article/details/gtefijsjwm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cashguo.top/Article/details/gthtxuvgyg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nanxuanxn.top/Article/details/gtcuwcamis.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fzhhl.top/Article/details/gtancgfhqd.html

[M04] 获取当前工作目录
来源：http://dali.xuanzx.com/Article/details/gtqcnnhtyf.html

Py:   os.getcwd()
来源：http://dali.cucudq.cn/Article/details/gtnzqjtoxp.html

PHP:  getcwd();
来源：http://dali.hywenlv.cn/Article/details/gtqddizyiy.html

JS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtqlnxahnl.html

TS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gtjfgongad.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jianghu66.top/Article/details/gtltorttga.html

Go:   os.Getwd()
来源：http://dali.chenlongwang.top/Article/details/gtwkvfgavr.html

Ruby: Dir.pwd
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvopehou.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dianchejie.cn/Article/details/gtmkvudchg.html

[M05] 设置退出码
来源：http://dali.nanxuanxn.top/Article/details/gtvbfjhqcw.html

Py:   sys.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtmtmwpute.html

PHP:  exit(1);
来源：http://dali.haohaochexian.top/Article/details/gtqzhhpkwk.html

JS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gtzdyxtwul.html

TS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtajzmcjkl.html

Java: System.exit(1)
来源：http://dali.ivvv.top/Article/details/gthpycovjd.html

Go:   os.Exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtwsjgslqt.html

Ruby: exit 1
来源：http://dali.cashguo.top/Article/details/gtqnaoglyp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fengsongda.top/Article/details/gtldedjpwt.html

[M06] 向标准错误输出
来源：http://dali.hammf.cn/Article/details/gtwxklygjh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.c1oappe.top/Article/details/gtnxlruaqq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangdashe.top/Article/details/gtcgnobvjx.html

JS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gtslvznjvg.html

TS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gtyhstoihc.html

Java: System.err.println("err")
来源：http://dali.guannengcc.top/Article/details/gtdjxuglkp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gtagvsklea.html

Ruby: warn "err"
来源：http://dali.sufxvd.cn/Article/details/gthkasnztd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daria6918.cn/Article/details/gtzdzztzyh.html

[M07] 判断是否为主入口
来源：http://dali.nanxinkj.top/Article/details/gtpzajvfyp.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258888.top/Article/details/gtscuekrjo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.andypj.xyz/Article/details/gtexqvvrbg.html

JS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gtgclkvlww.html

TS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gtvpwxfmcc.html

Java: public static void main(String[] args)
来源：http://dali.c1oappe.top/Article/details/gtwwvobhbu.html

Go:   func main()
来源：http://dali.haohaochexian.top/Article/details/gtvgpgpylz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj20258888.top/Article/details/gtsostyaok.html

C#:   static void Main(string[] args)
来源：http://dali.cdnleiting.top/Article/details/gtzcsrqhpc.html

[M08] 获取系统与运行时信息
来源：http://dali.hnxiangtu.top/Article/details/gtrzdngpny.html

Py:   platform.system();  platform.python_version()
来源：http://dali.vqdsnc.cn/Article/details/gtstoltnwd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hongshengwenyu.top/Article/details/gtoqyttqmo.html

JS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtoncburfh.html

TS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujmzinsv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.9152youxi.cn/Article/details/gterrihkxb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yonumen.top/Article/details/gtkcupawzq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hammf.cn/Article/details/gttxxrrchm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gzhubu.top/Article/details/gtbdamdfze.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtqmfydpyd.html

N. 数据结构与算法
来源：http://dali.snrcjt.cn/Article/details/gtvwentehn.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtofretwjw.html

[N01] 二分查找（有序数组）
来源：http://dali.9152youxi.cn/Article/details/gtxvxssdmt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtjvdnibrx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.guowangkeji.top/Article/details/gtlqnhljmw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gtlsxyfxsq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gtebjyppnz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtcbgwcrat.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtpecwswzp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gaohongyu789.top/Article/details/gtyfyjjequ.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtvgpxlvyb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.vqdsnc.cn/Article/details/gtvcuixnbz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gtrssmsgec.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtgzmbchim.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gtuexixswv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezrpodnj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yonumen.top/Article/details/gtoaxrxuar.html

Go:   slices.Sort(arr)
来源：http://dali.zycfv.cn/Article/details/gtgsfmbtyo.html

Ruby: arr.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgppwepu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hywenlv.cn/Article/details/gttcfvgxks.html

[N03] 快速排序（分治示例）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfwznaxpx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.smart0.xyz/Article/details/gthperqabx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yueranfly.top/Article/details/gtovxvoedc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuanzhike.top/Article/details/gtthntasyb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.0kj1m.cn/Article/details/gtzumuwhmw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cdnleiting.top/Article/details/gtnyfsyxud.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgfzy.top/Article/details/gtemskchkk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.aibaodan.cn/Article/details/gtroiknopb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guowangkeji.top/Article/details/gtrjsuqfku.html

[N04] 斐波那契数列
来源：http://dali.zhixingplan.top/Article/details/gtkukmzpfc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gtgxotharx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ydzc1.top/Article/details/gtnbtqxyqt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtyztruxuv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtqcmdlrwv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.316326.xyz/Article/details/gtpspkzwrq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jqgufenzy.top/Article/details/gtuvhxvrjc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gtztokrydo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtwfwffyoc.html

[N05] 最大公约数
来源：http://dali.cdnleiting.top/Article/details/gtrsgpxtey.html

Py:   math.gcd(a, b)
来源：http://dali.sweek.top/Article/details/gtricnnzit.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shuidangran.top/Article/details/gtfqhoktwk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gtodntbjej.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gtxlqqlayv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.mhx1999.top/Article/details/gtfejuqaou.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ivvv.top/Article/details/gteypkfado.html

Ruby: a.gcd(b)
来源：http://dali.nwbrower.top/Article/details/gtxcgsjhou.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xziqi.cn/Article/details/gthxcvpwoj.html

[N06] 判断回文字符串
来源：http://dali.zycfv.cn/Article/details/gtoeynecee.html

Py:   s == s[::-1]
来源：http://dali.birdmap.top/Article/details/gteyznkrdl.html

PHP:  $s === strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtdrojobmf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtprlvffgi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtwtcxopgp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aibaodan.cn/Article/details/gtzijjixzu.html

Go:   // 双指针从两端比较
来源：http://dali.nwbrower.top/Article/details/gtbbnqxudj.html

Ruby: s == s.reverse
来源：http://dali.quarkkingdee.top/Article/details/gtmtvslqhh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yonumen.top/Article/details/gtijdetfip.html

[N07] 两数之和（返回下标）
来源：http://dali.9152youxi.cn/Article/details/gtomkgdfhy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cashguo.top/Article/details/gtfqsalvik.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcsffxay.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zycfv.cn/Article/details/gtnbfpsmec.html

TS:   // 手写 Map<string, number>
来源：http://dali.feifeiyinyue.top/Article/details/gthpwqrons.html

Java: // 手写 HashMap
来源：http://dali.birdmap.top/Article/details/gtmsqkbwrj.html

Go:   // 手写 map[int]int
来源：http://dali.ehwqpu.com/Article/details/gteqrwisrx.html

Ruby: // 手写 Hash
来源：http://dali.redwolf501.top/Article/details/gtiawalqrs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cucudq.cn/Article/details/gteejilzrf.html

[N08] 生成全排列
来源：http://dali.ppjwa.cn/Article/details/gtkxfqsovu.html

Py:   itertools.permutations(arr)
来源：http://dali.ivvv.top/Article/details/gttgqwiihg.html

PHP:  // 手写递归交换
来源：http://dali.dianchejie.cn/Article/details/gtvcwiwhqo.html

JS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtjpeggwha.html

TS:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosuqbhcy.html

Java: // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gttmkpubju.html

Go:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtzozgpnha.html

Ruby: arr.permutation.to_a
来源：http://dali.bjfxy.top/Article/details/gtqolzvarh.html

C#:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtrghvobzr.html

[N09] 栈与队列
来源：http://dali.cqqwz.cn/Article/details/gtxgzfnitj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gotoacloud.top/Article/details/gtuswcimix.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtviabfmua.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtatocmuod.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.vqdsnc.cn/Article/details/gtrfjkqyxa.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hammf.cn/Article/details/gthhtzlbpf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tianlin.xyz/Article/details/gtvhezsebn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258888.top/Article/details/gtgjomfscs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.mhx1999.top/Article/details/gtbnkyiekr.html

[N10] 链表节点定义
来源：http://dali.sufxvd.cn/Article/details/gtbdefbshh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sysykeji.top/Article/details/gtyvjecsbj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cheryme.top/Article/details/gtngtynndc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.pycfn.com/Article/details/gtmagosbbi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.aibaodan.cn/Article/details/gtfmsxvjqr.html

Java: class Node { int v; Node next; }
来源：http://dali.birdmap.top/Article/details/gtbuovxrde.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tianlin.xyz/Article/details/gtjtgmwrdw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nanxuanxn.top/Article/details/gtpfvlgwhz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnehbtklc.html

[N11] 二叉树中序遍历
来源：http://dali.daxiang520.top/Article/details/gtnzbyfuma.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.wangdashe.top/Article/details/gtumyyifdg.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gtzaambjsg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnayyibw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gtwvmpzsgg.html

Java: // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtfejnegrz.html

Go:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtcppgbtjt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.haohaochexian.top/Article/details/gtfgqzfame.html

C#:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gtnuczvnhy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yanxiufei.cn/Article/details/gtleryamnn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aibaodan.cn/Article/details/gtfzacfvrf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxuanxn.top/Article/details/gtctzmttvt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gtiyjvepul.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gtypcpdfze.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gtepicrilt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shangyingyoupin.top/Article/details/gtsdfbfxxs.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dianchejie.cn/Article/details/gtzschlqbx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gtofoywyma.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtajodxxht.html

O. 并发与异步
来源：http://dali.iojbl.cn/Article/details/gtzqjhigap.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtuwmngvlm.html

[O01] 启动一个线程
来源：http://dali.pengpengdd.cyou/Article/details/gtbskdkdwo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jqgufenzy.top/Article/details/gtiipieqci.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuxming.cn/Article/details/gtoqevaery.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.guowangkeji.top/Article/details/gtpkqmldpf.html

TS:   // 同 JS
来源：http://dali.chenzaomai.com/Article/details/gteoaehlxn.html

Java: new Thread(() -> f()).start()
来源：http://dali.sysykeji.top/Article/details/gtcwitvwqc.html

Go:   go f()
来源：http://dali.fengsongda.top/Article/details/gtwtdntvnr.html

Ruby: Thread.new { f }
来源：http://dali.zhiwuduotai.top/Article/details/gtqclvtmzk.html

C#:   Task.Run(() => F());
来源：http://dali.yuanzhike.top/Article/details/gtkvbszyyt.html

[O02] 使用线程池
来源：http://dali.9152youxi.cn/Article/details/gtsmhikqsn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sufxvd.cn/Article/details/gtzhenqfps.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.redwolf501.top/Article/details/gtjkorqxlt.html

JS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gtglbyhppu.html

TS:   // worker_threads 线程池
来源：http://dali.fzhhl.top/Article/details/gtixwpzjwo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.316326.xyz/Article/details/gtbmdpfrrr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ppjwa.cn/Article/details/gtlnhdlzrt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangtech.top/Article/details/gtftpdcxnb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258.top/Article/details/gthjafeztm.html

[O03] 加锁保护共享数据
来源：http://dali.zdqjudy.top/Article/details/gthugfkxtc.html

Py:   with lock: shared += 1
来源：http://dali.meibo888.top/Article/details/gtsziijfln.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhengqikj.top/Article/details/gtatrgulvi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpckmgbv.html

TS:   // 同 JS
来源：http://dali.tian-w.cn/Article/details/gtxopjgadn.html

Java: synchronized (this) { shared++; }
来源：http://dali.cqqwz.cn/Article/details/gtwfmysnts.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukqfdmdd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yanxiufei.cn/Article/details/gtospnohqd.html

C#:   lock (gate) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gtjhjvlgfe.html

[O04] 定义异步函数并等待
来源：http://dali.meibo888.top/Article/details/gtnggsbudi.html

Py:   async def f():⏎    await g()
来源：http://dali.sxryk.cn/Article/details/gtpapnnuvy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenjidiqi.icu/Article/details/gtyrmzyxho.html

JS:   async function f() { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtwypmuffj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.havefunace.top/Article/details/gtqeflpbxe.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigufen.top/Article/details/gtgmkflqzo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jiagoushi.top/Article/details/gtzapwgoxa.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shzxlz.cn/Article/details/gtmfjckzwe.html

C#:   async Task F() { await G(); }
来源：http://dali.cheryme.top/Article/details/gtypctcdsh.html

[O05] 并发执行并等待全部完成
来源：http://dali.yuanzhike.top/Article/details/gtxchbqhwv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgflvbbl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.wangdashe.top/Article/details/gtvvaxrnyq.html

JS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gtetthagey.html

TS:   await Promise.all(tasks)
来源：http://dali.tianlin.xyz/Article/details/gttdrmehos.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gzhubu.top/Article/details/gtnbzmtyiv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hammf.cn/Article/details/gtnlaxgzsv.html

Ruby: threads.map(&:join)
来源：http://dali.shzxlz.cn/Article/details/gtplihlnmf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.quarkkingdee.top/Article/details/gthtfgvprt.html


<!-- 参考信息 -->