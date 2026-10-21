代发 wailian999

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.dianchejie.cn/Article/details/gtamaxknko.html

JS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbjqxffc.html

TS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gtwmxpzibl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jlsjyb.cn/Article/details/gtjvpzejtl.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhengqikj.top/Article/details/gtfjvhjbqk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenjidiqi.icu/Article/details/gtsptdkjda.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgfzy.top/Article/details/gtsxnwrnpe.html

[L02] 发送 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gtbylpasbm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuanzx.com/Article/details/gtcwivblej.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenzaomai.com/Article/details/gtoksjyolq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gtntxtuhsd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gtrqachymo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.bjfxy.top/Article/details/gtmmchpiwm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jianghu66.top/Article/details/gtberlmeci.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhengqikj.top/Article/details/gtxknfyrgj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.mhx1999.top/Article/details/gtfrnrdndp.html

[L03] 设置自定义请求头
来源：http://dali.yongpay.top/Article/details/gtiskdpreh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenjidiqi.icu/Article/details/gtaltfkxay.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guowangkeji.top/Article/details/gtimmojxqf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gtdxeuqnwr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gtyelnuxay.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.wangdashe.top/Article/details/gtozpaeyft.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.andypj.xyz/Article/details/gtuxzcuysv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gtcqmwhcyr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xziqi.cn/Article/details/gtvgqdodtb.html

[L04] 设置超时
来源：http://dali.cqqwz.cn/Article/details/gtrcvkecrs.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuanzx.com/Article/details/gtmprotbaa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sysykeji.top/Article/details/gtgdnfoxxf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gttjgcsdyy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gteacznrsu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yvedp.cn/Article/details/gtsvhvtgbt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangdashe.top/Article/details/gtklakmypb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuxming.cn/Article/details/gtjtnecbgx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.andypj.xyz/Article/details/gtjcwjvbsp.html

[L05] 上传文件（multipart）
来源：http://dali.cqqwz.cn/Article/details/gtvvsitfpj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.0kj1m.cn/Article/details/gtlnaqlbuq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangshuangyany.cn/Article/details/gtipcmglbi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cdnleiting.top/Article/details/gtpjehbsnz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gtpxvkzzal.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj202588.top/Article/details/gtuaqracim.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cucudq.cn/Article/details/gtvajafhsh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tian-w.cn/Article/details/gtkezbeagj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tanke756.top/Article/details/gtzutgqdjd.html

[L06] 解析响应为 JSON
来源：http://dali.zhixingplan.top/Article/details/gtangazcqj.html

Py:   resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gtggxmtxvr.html

PHP:  json_decode($body, true);
来源：http://dali.quarkkingdee.top/Article/details/gtjwhdllew.html

JS:   await resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtjfhocdmd.html

TS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtlgwbtesd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zycfv.cn/Article/details/gtsipxoitt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ppjwa.cn/Article/details/gtilwfuftn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.pengpengdd.cyou/Article/details/gtnoqbchos.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccjhpryb.html

[L07] 处理 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gtqewokoiw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sufxvd.cn/Article/details/gtiiqirlgb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cheryme.top/Article/details/gtsiabrqou.html

JS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gtlwgfqrea.html

TS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gtezdtlmic.html

Java: resp.statusCode()
来源：http://dali.feifeiyinyue.top/Article/details/gtmheeyqda.html

Go:   resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gtfyzucxzp.html

Ruby: resp.code.to_i
来源：http://dali.fzhhl.top/Article/details/gtnuaugopz.html

C#:   (int)resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gtovbabyxu.html

[L08] 并发请求多个地址
来源：http://dali.tian-w.cn/Article/details/gtgdvaqyrf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuxming.cn/Article/details/gtdgkqvkwk.html

PHP:  curl_multi_init() 系列
来源：http://dali.cheryme.top/Article/details/gtcqhtkpyl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtaaghklcy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gtsdfoizwx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhiwuduotai.top/Article/details/gtijrncxxc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gtrospmhpg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258.top/Article/details/gtxzvaqkyo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.9152youxi.cn/Article/details/gtszcklgre.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtruyhtxke.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangdashe.top/Article/details/gtrnutexus.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtrspzkjus.html

[M01] 读取命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gtofykuwre.html

Py:   sys.argv[1:]
来源：http://dali.0kj1m.cn/Article/details/gtbibnnnen.html

PHP:  $argv;  $argc;
来源：http://dali.nwbrower.top/Article/details/gtehlmxmwi.html

JS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gtwujojhxt.html

TS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gtfqntucgt.html

Java: args 数组（main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gtzkrnplma.html

Go:   os.Args[1:]
来源：http://dali.gogol.net.cn/Article/details/gtuvzlipdp.html

Ruby: ARGV
来源：http://dali.tian-w.cn/Article/details/gtegmdzlzx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gtllpmsfaq.html

[M02] 读取环境变量
来源：http://dali.fzhhl.top/Article/details/gtppfithce.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtqkmpfcsb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gtjovccqnc.html

JS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gtpgsvdold.html

TS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gtbjzwczvm.html

Java: System.getenv("HOME")
来源：http://dali.cheryme.top/Article/details/gtbmxfllpy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtngsvcagf.html

Ruby: ENV["HOME"]
来源：http://dali.wangshuangyany.cn/Article/details/gtjqolxsrn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtratdrbzz.html

[M03] 执行外部命令
来源：http://dali.yj20258888.top/Article/details/gtqoclpset.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.redwolf501.top/Article/details/gtnwllnfpw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zdqjudy.top/Article/details/gtiqovmlhz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gtdbqcrkaw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ehwqpu.com/Article/details/gtgajaflwk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.havefunace.top/Article/details/gtlwbqkogu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daria6918.cn/Article/details/gtqtlgnvwu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenjidiqi.icu/Article/details/gtsutmvhag.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cheryme.top/Article/details/gtzstvnjfa.html

[M04] 获取当前工作目录
来源：http://dali.zhengqikj.top/Article/details/gttyoatsae.html

Py:   os.getcwd()
来源：http://dali.xylfe.cn/Article/details/gtvkkkcxgx.html

PHP:  getcwd();
来源：http://dali.shuidangran.top/Article/details/gtqvefcrzp.html

JS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gtzamquylk.html

TS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtvbvbyggs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.vqdsnc.cn/Article/details/gtdjesiibm.html

Go:   os.Getwd()
来源：http://dali.fzhhl.top/Article/details/gthxzmhdub.html

Ruby: Dir.pwd
来源：http://dali.jyoumei.cn/Article/details/gtsyndodqx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zdqjudy.top/Article/details/gtnzuwqqzm.html

[M05] 设置退出码
来源：http://dali.316326.xyz/Article/details/gttvaiaavk.html

Py:   sys.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtgxtmbpdw.html

PHP:  exit(1);
来源：http://dali.daxiang520.top/Article/details/gtextacvyx.html

JS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gttvkswgwt.html

TS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtoomenjmm.html

Java: System.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtsdnaryab.html

Go:   os.Exit(1)
来源：http://dali.hammf.cn/Article/details/gtpcjguwsp.html

Ruby: exit 1
来源：http://dali.tanke756.top/Article/details/gtxxicexbf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sxryk.cn/Article/details/gtgmhqhqrb.html

[M06] 向标准错误输出
来源：http://dali.sufxvd.cn/Article/details/gtkbudyezp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gtlilztfjh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnqzz.top/Article/details/gtwwuiuayz.html

JS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gtqovphbwf.html

TS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gtrjebpjyo.html

Java: System.err.println("err")
来源：http://dali.hnqzz.top/Article/details/gtmuxlpahk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gtkpktglbn.html

Ruby: warn "err"
来源：http://dali.ydzc1.top/Article/details/gtsfzulknp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj202588.top/Article/details/gtsdhtqcpu.html

[M07] 判断是否为主入口
来源：http://dali.9152youxi.cn/Article/details/gtebkkqhpj.html

Py:   if __name__ == "__main__":
来源：http://dali.cqqwz.cn/Article/details/gtybtgfiqs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hfpthk.cn/Article/details/gttarnmqpq.html

JS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gthljqgkbh.html

TS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gtcvittkaa.html

Java: public static void main(String[] args)
来源：http://dali.gogol.net.cn/Article/details/gtekdggxut.html

Go:   func main()
来源：http://dali.shuidangran.top/Article/details/gthjgphtko.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hysaishi.cn/Article/details/gtqywvakkv.html

C#:   static void Main(string[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gtvcrvhmya.html

[M08] 获取系统与运行时信息
来源：http://dali.yongpay.top/Article/details/gtknmqjkbd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ydzc1.top/Article/details/gtjzakwsnf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yangfankeji.com/Article/details/gttpcnkpav.html

JS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gtnkzduuny.html

TS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtxknzened.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.316326.xyz/Article/details/gtidruhuho.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnxiangtu.top/Article/details/gtumksglmd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zycfv.cn/Article/details/gtwvxgicmv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ybcxt.top/Article/details/gtofbqfsux.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtfcnonrnl.html

N. 数据结构与算法
来源：http://dali.xylfe.cn/Article/details/gtwuozespf.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtzbnlfshs.html

[N01] 二分查找（有序数组）
来源：http://dali.andypj.xyz/Article/details/gtmsbaokca.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ybcxt.top/Article/details/gttuubbwwb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gttdiefksn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtgntwfqbw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gtsyflqnhw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtsjxrigdl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtreqvbmkj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258.top/Article/details/gtdbvjxbrc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtcimxqjle.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.vqdsnc.cn/Article/details/gtjswvtyfx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gtlfoqseau.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtmddvyoei.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gtfjkghzio.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtmsezjgca.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.iojbl.cn/Article/details/gtnrnetawa.html

Go:   slices.Sort(arr)
来源：http://dali.0kj1m.cn/Article/details/gtidualzme.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gtafftoevp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ybcxt.top/Article/details/gtzrnphpnl.html

[N03] 快速排序（分治示例）
来源：http://dali.tian-w.cn/Article/details/gtrmolifel.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.dianchejie.cn/Article/details/gtzrvcbhzd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yonumen.top/Article/details/gtkwarnpjz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gtmrwdmalh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gtrehhuomk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yonumen.top/Article/details/gtvsfojijw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ehwqpu.com/Article/details/gttikxtfms.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cashguo.top/Article/details/gtknztlzhm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yanxiufei.cn/Article/details/gtxthzbsgh.html

[N04] 斐波那契数列
来源：http://dali.pengpengdd.cyou/Article/details/gtqqbeiahq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gtqyiweait.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnqzz.top/Article/details/gtyfrflekm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gtblpokocq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtgqokyxhs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuanzx.com/Article/details/gtczhpnkpk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhongyouzk.top/Article/details/gtbvdywidv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gtktrsofzd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gtpbgaggif.html

[N05] 最大公约数
来源：http://dali.wangshuangyany.cn/Article/details/gtyqxzzost.html

Py:   math.gcd(a, b)
来源：http://dali.havefunace.top/Article/details/gtgjgdlzne.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.havefunace.top/Article/details/gtchrgppxt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gtyobnyurf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gtlcgapckh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guowangkeji.top/Article/details/gtlriwrddl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhiwuduotai.top/Article/details/gtjubcnnhp.html

Ruby: a.gcd(b)
来源：http://dali.meibo888.top/Article/details/gtoikuxood.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jiagoushi.top/Article/details/gthbmnvqvm.html

[N06] 判断回文字符串
来源：http://dali.sxryk.cn/Article/details/gtddavauir.html

Py:   s == s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcrkcmkh.html

PHP:  $s === strrev($s);
来源：http://dali.bjfxy.top/Article/details/gtgpgemjdi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtwfgzseta.html

TS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gttgvyteyt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shzxlz.cn/Article/details/gttplvcpex.html

Go:   // 双指针从两端比较
来源：http://dali.xuanzx.com/Article/details/gtumbgprdp.html

Ruby: s == s.reverse
来源：http://dali.kuanghao11.cn/Article/details/gtdkpcphti.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gtqvzxazds.html

[N07] 两数之和（返回下标）
来源：http://dali.kuanghao11.cn/Article/details/gtubhhrfzl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigbkoenz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnqzz.top/Article/details/gttsygngqo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.quarkkingdee.top/Article/details/gtjahijgsa.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangdashe.top/Article/details/gtpjdzxtwi.html

Java: // 手写 HashMap
来源：http://dali.fengsongda.top/Article/details/gtshbczwlw.html

Go:   // 手写 map[int]int
来源：http://dali.pengpengdd.cyou/Article/details/gtglnnarbc.html

Ruby: // 手写 Hash
来源：http://dali.aibaodan.cn/Article/details/gtmvgmtyuy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj20258888.top/Article/details/gtcbyljjmb.html

[N08] 生成全排列
来源：http://dali.nwbrower.top/Article/details/gtgszkifcu.html

Py:   itertools.permutations(arr)
来源：http://dali.yj20258.top/Article/details/gtjlwemqxo.html

PHP:  // 手写递归交换
来源：http://dali.hnqzz.top/Article/details/gtarngjedb.html

JS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtfuhrxpxr.html

TS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtoytgnfgg.html

Java: // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtzbpqbvxl.html

Go:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gthgcfugll.html

Ruby: arr.permutation.to_a
来源：http://dali.ivvv.top/Article/details/gtwjpzntxt.html

C#:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtfbpgohed.html

[N09] 栈与队列
来源：http://dali.daxiang520.top/Article/details/gtxhctrsmi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yueranfly.top/Article/details/gtnuqrkxmk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jianghu66.top/Article/details/gtgtdloiua.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoukhramv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sufxvd.cn/Article/details/gtgiandlxm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cqqwz.cn/Article/details/gtdmcqbjgl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jianghu66.top/Article/details/gtymsqlkze.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gtbcezqvbc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywzlueym.html

[N10] 链表节点定义
来源：http://dali.xinyue.icu/Article/details/gtrxhlnrax.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yuxming.cn/Article/details/gtaqthuxwy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.mhx1999.top/Article/details/gtzqdbvtuf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtgfahoviw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangdashe.top/Article/details/gtidgymdob.html

Java: class Node { int v; Node next; }
来源：http://dali.daria6918.cn/Article/details/gtlxfwtdsi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hywenlv.cn/Article/details/gtgobuhaea.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.vqdsnc.cn/Article/details/gtzukvbpgk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gogol.net.cn/Article/details/gtmsukxfer.html

[N11] 二叉树中序遍历
来源：http://dali.yueranfly.top/Article/details/gtzquizwqk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.c1oappe.top/Article/details/gtqbbtvxoq.html

PHP:  // 手写递归函数
来源：http://dali.yj20258.top/Article/details/gtmpdsrdpc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cashguo.top/Article/details/gtpiskunqv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gtpvlkrqaq.html

Java: // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gtrkoypxuz.html

Go:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtwyubxwkv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.andypj.xyz/Article/details/gtpvksfesh.html

C#:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gttjrlfuay.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aibaodan.cn/Article/details/gtihhsyzle.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hywenlv.cn/Article/details/gtrnbjikzy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.svipenyu.cn/Article/details/gtxltenvkz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtcdwrqplq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shangyingyoupin.top/Article/details/gthshtbard.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gthighypto.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.fzhhl.top/Article/details/gtgrlxeicn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfewwtgxm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.redwolf501.top/Article/details/gtvlgvjdvr.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtzdivkjts.html

O. 并发与异步
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpatxsohh.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtrpbqfplq.html

[O01] 启动一个线程
来源：http://dali.daxiang520.top/Article/details/gtkbcygdmy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xziqi.cn/Article/details/gtocrrpdye.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ehwqpu.com/Article/details/gtypvppxxm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.mhx1999.top/Article/details/gtdactltej.html

TS:   // 同 JS
来源：http://dali.hysaishi.cn/Article/details/gtdmnhezss.html

Java: new Thread(() -> f()).start()
来源：http://dali.yongpay.top/Article/details/gtcmxvgnkv.html

Go:   go f()
来源：http://dali.haohaochexian.top/Article/details/gtlvgzmwom.html

Ruby: Thread.new { f }
来源：http://dali.ydzc1.top/Article/details/gttfwrxrhb.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258.top/Article/details/gtbteyfigz.html

[O02] 使用线程池
来源：http://dali.ybcxt.top/Article/details/gtpchhercx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.dashuyun.cn/Article/details/gtboxgjpnk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.andypj.xyz/Article/details/gtsddlnbfk.html

JS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gtcloydqrg.html

TS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gtfxjnulwl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xylfe.cn/Article/details/gtaytkxybi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenlongwang.top/Article/details/gtffybfocu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.iojbl.cn/Article/details/gtlicfoytz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.316326.xyz/Article/details/gtiebyttuj.html

[O03] 加锁保护共享数据
来源：http://dali.yuanzhike.top/Article/details/gthjklqypd.html

Py:   with lock: shared += 1
来源：http://dali.redwolf501.top/Article/details/gtldwxfqrg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cucudq.cn/Article/details/gtcorzkifa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hywenlv.cn/Article/details/gtyrvbjrao.html

TS:   // 同 JS
来源：http://dali.haohaochexian.top/Article/details/gtgadtrbnx.html

Java: synchronized (this) { shared++; }
来源：http://dali.cqqwz.cn/Article/details/gtzlcxtgft.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yanxiufei.cn/Article/details/gtkmslsbxx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daria6918.cn/Article/details/gtgcsdftey.html

C#:   lock (gate) { shared++; }
来源：http://dali.tanke756.top/Article/details/gtaknflrxb.html

[O04] 定义异步函数并等待
来源：http://dali.tanke756.top/Article/details/gtnewydscl.html

Py:   async def f():⏎    await g()
来源：http://dali.tanke756.top/Article/details/gtbsykvphi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenzaomai.com/Article/details/gtuatqjygn.html

JS:   async function f() { await g(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtebpnqmal.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.daria6918.cn/Article/details/gtvstdfyop.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenzaomai.com/Article/details/gtcgkwoiyq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gaohongyu789.top/Article/details/gtiknamuaz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdspqtib.html

C#:   async Task F() { await G(); }
来源：http://dali.yvedp.cn/Article/details/gtgqecgnqa.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenzaomai.com/Article/details/gttypuzibo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnqzz.top/Article/details/gtkwtajjep.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jqgufenzy.top/Article/details/gtwqndgxll.html

JS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gtkqmmmhcj.html

TS:   await Promise.all(tasks)
来源：http://dali.jqgufenzy.top/Article/details/gtjzotzecw.html


<!-- 参考信息 -->