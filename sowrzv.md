代发 wailian999

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgfzy.top/Article/details/gtwkmvtfhz.html

JS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gtsfekuyul.html

TS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gtqfbsrktd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.kuanghao11.cn/Article/details/gtynxuxtil.html

Go:   resp, err := http.Get(url)
来源：http://dali.yangfankeji.com/Article/details/gtpndymhbf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shuidangran.top/Article/details/gtozejpfzm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cdnleiting.top/Article/details/gtchxmlrqq.html

[L02] 发送 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gthnlxmaxx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yvedp.cn/Article/details/gtupblrosb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jyoumei.cn/Article/details/gtwacbdyds.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gtxqdeirws.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gtpxlmrjet.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fzhhl.top/Article/details/gtbhkoxubi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.c1oappe.top/Article/details/gtphkchffj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guowangkeji.top/Article/details/gtcatozemd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yangfankeji.com/Article/details/gtkxjwlmyg.html

[L03] 设置自定义请求头
来源：http://dali.nanxinkj.top/Article/details/gtkbhyfwzm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sysykeji.top/Article/details/gtkscmfgfp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.svipenyu.cn/Article/details/gtqqeebuql.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gttwfsthde.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gthzemvzoc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tian-w.cn/Article/details/gtrjxjraes.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.andypj.xyz/Article/details/gttsgdkrrt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gogol.net.cn/Article/details/gtcvgfvrbt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gthnmoasve.html

[L04] 设置超时
来源：http://dali.tianlin.xyz/Article/details/gtekazljlj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xylfe.cn/Article/details/gtprlgcjcf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.svipenyu.cn/Article/details/gtisewgpdv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gttmpqzkve.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gtehlzdbcg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gtbspvxjxh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhixingplan.top/Article/details/gtpxuzrbyj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.redwolf501.top/Article/details/gttxiywvzv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxuanxn.top/Article/details/gtgpnlqdly.html

[L05] 上传文件（multipart）
来源：http://dali.zhongyouzk.top/Article/details/gtddymndix.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cucudq.cn/Article/details/gteccvlqbm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenzaomai.com/Article/details/gtmhoenjtq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gtqoxcjmud.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gtkubpymkc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ybcxt.top/Article/details/gtjysehypr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuxming.cn/Article/details/gtgxsndbax.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcckmqgig.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtrfbwumwt.html

[L06] 解析响应为 JSON
来源：http://dali.jyoumei.cn/Article/details/gtyhpukhuu.html

Py:   resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtusajazuf.html

PHP:  json_decode($body, true);
来源：http://dali.fengsongda.top/Article/details/gtxksanhzx.html

JS:   await resp.json()
来源：http://dali.smart0.xyz/Article/details/gtvootntwc.html

TS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gtuqlagwkt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.316326.xyz/Article/details/gthdscmqyw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenzaomai.com/Article/details/gtefnkozln.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenzaomai.com/Article/details/gtekvjioee.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cheryme.top/Article/details/gtfckdwkgs.html

[L07] 处理 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gtopleyqwy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hammf.cn/Article/details/gtqhjoamel.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258888.top/Article/details/gtqvfnxjjy.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gtnozxutrq.html

TS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtkvsbmpaj.html

Java: resp.statusCode()
来源：http://dali.0kj1m.cn/Article/details/gtjkfyduel.html

Go:   resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gtnxigggvn.html

Ruby: resp.code.to_i
来源：http://dali.aizwys.cn/Article/details/gtefefvpeh.html

C#:   (int)resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gtxgbtgmaq.html

[L08] 并发请求多个地址
来源：http://dali.xuanzx.com/Article/details/gtjmxtcrzl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gotoacloud.top/Article/details/gttbtcaawl.html

PHP:  curl_multi_init() 系列
来源：http://dali.0kj1m.cn/Article/details/gtnwijinuh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtrlyotzgi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtiicqxnvz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hysaishi.cn/Article/details/gtbwuuaffl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hywenlv.cn/Article/details/gtjzgsckum.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuanzx.com/Article/details/gtdvsisdmp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtxykfgmvv.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtfewgrbey.html

M. 命令行 / 进程 / 环境
来源：http://dali.pengpengdd.cyou/Article/details/gtngprjofi.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtenbhdiuv.html

[M01] 读取命令行参数
来源：http://dali.tianlin.xyz/Article/details/gtgxurdilc.html

Py:   sys.argv[1:]
来源：http://dali.sxryk.cn/Article/details/gtgypsrvdc.html

PHP:  $argv;  $argc;
来源：http://dali.gotoacloud.top/Article/details/gtiuziqzmc.html

JS:   process.argv.slice(2)
来源：http://dali.jqgfzy.top/Article/details/gtaquvvgyz.html

TS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gtwqtrmzll.html

Java: args 数组（main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gtkeayzohc.html

Go:   os.Args[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gtpxzafttf.html

Ruby: ARGV
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyydktml.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sufxvd.cn/Article/details/gtwqdfmujx.html

[M02] 读取环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpglmymv.html

Py:   os.environ.get("HOME")
来源：http://dali.ybcxt.top/Article/details/gtljtumbcf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gtwwycigxe.html

JS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gtpzmyklhq.html

TS:   process.env.HOME
来源：http://dali.tanke756.top/Article/details/gtkvezdvco.html

Java: System.getenv("HOME")
来源：http://dali.daria6918.cn/Article/details/gtrvocpbgg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gttdcnjczo.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gtgylavgso.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtcclubbbk.html

[M03] 执行外部命令
来源：http://dali.tianlin.xyz/Article/details/gttktqwjls.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nwbrower.top/Article/details/gtkxovjbox.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hongshengwenyu.top/Article/details/gtdnhylnuh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gtytvamwwp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gtmxnoijyf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxinkj.top/Article/details/gtbtrqlixe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.havefunace.top/Article/details/gtyawngnjl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pycfn.com/Article/details/gtgxycsghe.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxinkj.top/Article/details/gtczrpziai.html

[M04] 获取当前工作目录
来源：http://dali.quarkkingdee.top/Article/details/gtbjgrdgre.html

Py:   os.getcwd()
来源：http://dali.vqdsnc.cn/Article/details/gtoqewarny.html

PHP:  getcwd();
来源：http://dali.nwbrower.top/Article/details/gtqligftsy.html

JS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtxejbqkdt.html

TS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gtfitxdqfb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jiagoushi.top/Article/details/gtsgfnlqlk.html

Go:   os.Getwd()
来源：http://dali.zhoulong.xyz/Article/details/gtxjctaxyi.html

Ruby: Dir.pwd
来源：http://dali.nanxuanxn.top/Article/details/gtlmeczdhj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgufenzy.top/Article/details/gtyiossyht.html

[M05] 设置退出码
来源：http://dali.xziqi.cn/Article/details/gtakeujlkg.html

Py:   sys.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtmghaosze.html

PHP:  exit(1);
来源：http://dali.ydzc1.top/Article/details/gtabzforso.html

JS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtyoohkana.html

TS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gthpauqjto.html

Java: System.exit(1)
来源：http://dali.yj20258.top/Article/details/gtkwjhvtym.html

Go:   os.Exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtzjdozfkl.html

Ruby: exit 1
来源：http://dali.tianlin.xyz/Article/details/gtowgyjwuo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.mhx1999.top/Article/details/gtcgnijnaq.html

[M06] 向标准错误输出
来源：http://dali.fzhhl.top/Article/details/gtdfrdobes.html

Py:   print("err", file=sys.stderr)
来源：http://dali.kuanghao11.cn/Article/details/gtxladlpaq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cqqwz.cn/Article/details/gtrrhwuoud.html

JS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gthmixhahb.html

TS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gttwzdetgz.html

Java: System.err.println("err")
来源：http://dali.meibo888.top/Article/details/gtfifyldhe.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ybcxt.top/Article/details/gtfsfuwykk.html

Ruby: warn "err"
来源：http://dali.gotoacloud.top/Article/details/gtsbvqsxvl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhoulong.xyz/Article/details/gtakwcgvtf.html

[M07] 判断是否为主入口
来源：http://dali.tianlin.xyz/Article/details/gtwdbqxdyq.html

Py:   if __name__ == "__main__":
来源：http://dali.ivvv.top/Article/details/gtljwkybbi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cucudq.cn/Article/details/gtmqfbweis.html

JS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gtuqgdtlgg.html

TS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfxkuwas.html

Java: public static void main(String[] args)
来源：http://dali.fzhhl.top/Article/details/gtehajnahk.html

Go:   func main()
来源：http://dali.ydzc1.top/Article/details/gtausrxxoe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ydzc1.top/Article/details/gtvyohlhto.html

C#:   static void Main(string[] args)
来源：http://dali.shzxlz.cn/Article/details/gtfjnwhlwg.html

[M08] 获取系统与运行时信息
来源：http://dali.jinqigufen.top/Article/details/gthmsvymdi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhoulong.xyz/Article/details/gtodktugnc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.0kj1m.cn/Article/details/gtqtnhwprk.html

JS:   process.platform;  process.version
来源：http://dali.gogol.net.cn/Article/details/gtsrivdjcf.html

TS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gtwioyblhs.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jyoumei.cn/Article/details/gtsrptdrqo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnqzz.top/Article/details/gtxmoplqmj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gtioxgkleu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yvedp.cn/Article/details/gtgikoooae.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtluquowpi.html

N. 数据结构与算法
来源：http://dali.nanxinkj.top/Article/details/gtdvfudhpx.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtldoyefhd.html

[N01] 二分查找（有序数组）
来源：http://dali.yuanzhike.top/Article/details/gtlwjsswzl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwcjqffp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtuguqqvve.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xziqi.cn/Article/details/gtzwbuqpjs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtkikmiuga.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtamyahuok.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gttbyczyws.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ivvv.top/Article/details/gtxasamzpl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtialvbolw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhengqikj.top/Article/details/gtyhlozpte.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gtorbjimaf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigufen.top/Article/details/gtahbacvls.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytzuibmm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgfzy.top/Article/details/gtjfluxqzl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.mhx1999.top/Article/details/gtvydrwsmp.html

Go:   slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gtxzhugkci.html

Ruby: arr.sort
来源：http://dali.jqgufenzy.top/Article/details/gtxywlfzaq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fengsongda.top/Article/details/gtokoqpsqy.html

[N03] 快速排序（分治示例）
来源：http://dali.havefunace.top/Article/details/gtaaewdwve.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xinyue.icu/Article/details/gtptnpttgw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.meibo888.top/Article/details/gtnebtthrr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gtgkijnghu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gtbtnblrvx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtdfyixeet.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cheryme.top/Article/details/gtnitdkejc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hfpthk.cn/Article/details/gtvwcrxzdb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aizwys.cn/Article/details/gtyvralhnb.html

[N04] 斐波那契数列
来源：http://dali.jinqigufen.top/Article/details/gtgyhuollw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gtnbcijjoh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hywenlv.cn/Article/details/gtsiqrywjl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtsgvjtzri.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtifjjiztx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gtoouefjbx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jianghu66.top/Article/details/gtrenshqal.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtoinqlmtl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtbdvcjhds.html

[N05] 最大公约数
来源：http://dali.dashuyun.cn/Article/details/gtwpvparjc.html

Py:   math.gcd(a, b)
来源：http://dali.pycfn.com/Article/details/gtqzguikql.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ybcxt.top/Article/details/gtkdrbuuln.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gtnxdodotk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtukcdntoo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tanke756.top/Article/details/gtjptilvqs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cqqwz.cn/Article/details/gtmalgtwoh.html

Ruby: a.gcd(b)
来源：http://dali.jinqigufen.top/Article/details/gtjqazjitk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuanzhike.top/Article/details/gtfpgvfixs.html

[N06] 判断回文字符串
来源：http://dali.zdqjudy.top/Article/details/gtwmgqilkf.html

Py:   s == s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gtuywbmqwu.html

PHP:  $s === strrev($s);
来源：http://dali.nwbrower.top/Article/details/gtcezmtdnk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtkjxmudfj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtjchripgh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxuekxhii.html

Go:   // 双指针从两端比较
来源：http://dali.hysaishi.cn/Article/details/gtcvrfhmxh.html

Ruby: s == s.reverse
来源：http://dali.ybcxt.top/Article/details/gtiebsdntt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gtcpvavamv.html

[N07] 两数之和（返回下标）
来源：http://dali.hfpthk.cn/Article/details/gthmldvfhd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gotoacloud.top/Article/details/gteggxvuff.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yuxming.cn/Article/details/gtkpdrophh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgufenzy.top/Article/details/gtiukvdrwk.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenjidiqi.icu/Article/details/gtbgatcmvi.html

Java: // 手写 HashMap
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzltwsgf.html

Go:   // 手写 map[int]int
来源：http://dali.fzhhl.top/Article/details/gtqfmupbjv.html

Ruby: // 手写 Hash
来源：http://dali.mhx1999.top/Article/details/gtcdwfegtm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenjidiqi.icu/Article/details/gtmuhzcuha.html

[N08] 生成全排列
来源：http://dali.jqgfzy.top/Article/details/gtvzqpfnbt.html

Py:   itertools.permutations(arr)
来源：http://dali.fzhhl.top/Article/details/gtphafumdx.html

PHP:  // 手写递归交换
来源：http://dali.chenjidiqi.icu/Article/details/gtinvsnqnb.html

JS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtpkbuxbde.html

TS:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtwpplhjnd.html

Java: // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtakwonedl.html

Go:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gthzwhwyzm.html

Ruby: arr.permutation.to_a
来源：http://dali.wangshuangyany.cn/Article/details/gtcmmrtwhs.html

C#:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gttvoscral.html

[N09] 栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdodatti.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cashguo.top/Article/details/gtjeasuazp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtcrfxinwm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtorofdstn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sufxvd.cn/Article/details/gtpyyitlst.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ydzc1.top/Article/details/gtnxkxprwg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.snrcjt.cn/Article/details/gtmlrcolqn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gtvfuvacxz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.316326.xyz/Article/details/gtizlfzscv.html

[N10] 链表节点定义
来源：http://dali.hywenlv.cn/Article/details/gturugmnfq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.havefunace.top/Article/details/gtpcsplybu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sufxvd.cn/Article/details/gtgpsppsvn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.meibo888.top/Article/details/gtpfaiimhi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.smart0.xyz/Article/details/gtkhjevimt.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgufenzy.top/Article/details/gtrawaizag.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gtvjpzycbl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nwbrower.top/Article/details/gtpwbvgdhc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jianghu66.top/Article/details/gtcftyofwu.html

[N11] 二叉树中序遍历
来源：http://dali.zhongyouzk.top/Article/details/gtrhujkzvv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sufxvd.cn/Article/details/gtfwfzncwb.html

PHP:  // 手写递归函数
来源：http://dali.tanke756.top/Article/details/gtczcgldci.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gtiwzmriwd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gtcxgamexd.html

Java: // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gtsleuxeyo.html

Go:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtauyicpxt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgfzy.top/Article/details/gthlmwmutk.html

C#:   // 手写递归
来源：http://dali.xylfe.cn/Article/details/gtbafhhsgw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.mhx1999.top/Article/details/gtiytfuzol.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gtyiixadfy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnilvvobk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pycfn.com/Article/details/gteiebzdiq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gtlxfmhscm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.smart0.xyz/Article/details/gtkvzjgzii.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ppjwa.cn/Article/details/gtpmfjmkpx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gzhubu.top/Article/details/gtkixzjafy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gthpaaxbkr.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtmxwlcdgb.html

O. 并发与异步
来源：http://dali.ehwqpu.com/Article/details/gtxeyiwyco.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtycfgqple.html

[O01] 启动一个线程
来源：http://dali.hfpthk.cn/Article/details/gtqfyoajro.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xinyue.icu/Article/details/gtehvjiekp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ydzc1.top/Article/details/gtxfxuvrfk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxuozghrp.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gtdhdaqcyl.html

Java: new Thread(() -> f()).start()
来源：http://dali.xziqi.cn/Article/details/gtgysgagyk.html

Go:   go f()
来源：http://dali.sxryk.cn/Article/details/gtjxtnvofq.html

Ruby: Thread.new { f }
来源：http://dali.chenjidiqi.icu/Article/details/gtdunoatss.html

C#:   Task.Run(() => F());
来源：http://dali.shzxlz.cn/Article/details/gtknoxidql.html

[O02] 使用线程池
来源：http://dali.yuanzhike.top/Article/details/gtmxlwvlez.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbiokcic.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.iojbl.cn/Article/details/gtofpijzoc.html

JS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gtfyacwuvs.html

TS:   // worker_threads 线程池
来源：http://dali.ydzc1.top/Article/details/gtyvikblws.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sysykeji.top/Article/details/gthiwlwzuj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.snrcjt.cn/Article/details/gtsmymrdyi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cdnleiting.top/Article/details/gtzsqhqsjb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sxryk.cn/Article/details/gthnkfashc.html

[O03] 加锁保护共享数据
来源：http://dali.shanyushiyangtech.top/Article/details/gtptzhclaq.html

Py:   with lock: shared += 1
来源：http://dali.zhiwuduotai.top/Article/details/gtnkcehtqp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fengsongda.top/Article/details/gtadjredrx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hongshengwenyu.top/Article/details/gttktbnwzs.html

TS:   // 同 JS
来源：http://dali.dashuyun.cn/Article/details/gtzbgoeems.html

Java: synchronized (this) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gtojekzeck.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cashguo.top/Article/details/gtzccobicd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zycfv.cn/Article/details/gtljkwdwna.html

C#:   lock (gate) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gtwcdhfhjh.html

[O04] 定义异步函数并等待
来源：http://dali.ybcxt.top/Article/details/gtyijdqryv.html

Py:   async def f():⏎    await g()
来源：http://dali.hysaishi.cn/Article/details/gtcjioopqr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zdqjudy.top/Article/details/gtiftykted.html

JS:   async function f() { await g(); }
来源：http://dali.jqgufenzy.top/Article/details/gtqhoxxspd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.smart0.xyz/Article/details/gtucbrmyvd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.smart0.xyz/Article/details/gtsubgpjom.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.vqdsnc.cn/Article/details/gtprdirudx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yangfankeji.com/Article/details/gtdfrhebpb.html

C#:   async Task F() { await G(); }
来源：http://dali.andypj.xyz/Article/details/gtfcndtorx.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj202588.top/Article/details/gtxfybygxd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zdqjudy.top/Article/details/gtmmviitmt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pycfn.com/Article/details/gtzptwyltj.html

JS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gtakelyffw.html

TS:   await Promise.all(tasks)
来源：http://dali.xziqi.cn/Article/details/gtyrknhjmh.html


<!-- 参考信息 -->