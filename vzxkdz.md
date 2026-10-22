代发 wailian999

Go:   encoding/gob
来源：http://dali.svipenyu.cn/Article/details/gtkqcytpas.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgfzy.top/Article/details/gtjacmfymw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gtnbjelngm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtwlggcite.html

L. 网络请求
来源：http://dali.cheryme.top/Article/details/gtnzzfxynl.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtwspponhq.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtugzrdafc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfobckyt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.vqdsnc.cn/Article/details/gtaxxwdbaw.html

JS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gtgpyhicro.html

TS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gtumfazxwr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.c1oappe.top/Article/details/gtggxmmyqv.html

Go:   resp, err := http.Get(url)
来源：http://dali.hysaishi.cn/Article/details/gtyunvoqja.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gzhubu.top/Article/details/gtdsgfiwcg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cqqwz.cn/Article/details/gtoyoshxpj.html

[L02] 发送 POST JSON
来源：http://dali.316326.xyz/Article/details/gtdsogmluk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gtzapxtlja.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jlsjyb.cn/Article/details/gtxmzlmjno.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gtvxykwumx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gtddixmyqs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.bjfxy.top/Article/details/gthtxrqtte.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.iojbl.cn/Article/details/gtgxgruqfz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenzaomai.com/Article/details/gtzkrfteko.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sysykeji.top/Article/details/gtymoknfsn.html

[L03] 设置自定义请求头
来源：http://dali.nanxinkj.top/Article/details/gtbefxpzgz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhengqikj.top/Article/details/gtasleyqxu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.birdmap.top/Article/details/gtmayqwmpp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gtckeogvys.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gtvsstrpta.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgufenzy.top/Article/details/gthupqrinh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gterelamei.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zdqjudy.top/Article/details/gtnkqmymia.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gtdbyscjvd.html

[L04] 设置超时
来源：http://dali.yuxming.cn/Article/details/gtclssuoxu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.feifeiyinyue.top/Article/details/gtfrkjzsmr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxinkj.top/Article/details/gttujeqjaw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gtcgqengor.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gtawfnupjx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guowangkeji.top/Article/details/gtrsyboevj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuanzhike.top/Article/details/gtyxjbrjbb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangshuangyany.cn/Article/details/gtkomquing.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sufxvd.cn/Article/details/gtfipaghrn.html

[L05] 上传文件（multipart）
来源：http://dali.meibo888.top/Article/details/gtbrrwgeyv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxinkj.top/Article/details/gtbjpfkmgr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yongpay.top/Article/details/gtcjmdzabz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gtskyvsgyh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gtafglgtkn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.bjfxy.top/Article/details/gtqefnvibq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.meibo888.top/Article/details/gtoeoqsyol.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tianlin.xyz/Article/details/gtkhrjqway.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtexdjjdln.html

[L06] 解析响应为 JSON
来源：http://dali.ydzc1.top/Article/details/gtvdbgdfqb.html

Py:   resp.json()
来源：http://dali.cheryme.top/Article/details/gtazlqfurc.html

PHP:  json_decode($body, true);
来源：http://dali.jlsjyb.cn/Article/details/gtnwnlrisl.html

JS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gteqyfaeox.html

TS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gtjvpnptpb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gtinxtulcs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cucudq.cn/Article/details/gtdcbqdyac.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sweek.top/Article/details/gtblwuwzel.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yonumen.top/Article/details/gtvkkniiie.html

[L07] 处理 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gtpoeriwan.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shzxlz.cn/Article/details/gtvjffbqdj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cashguo.top/Article/details/gtpeetevok.html

JS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gtzrbmssqs.html

TS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gtbdkdwrpg.html

Java: resp.statusCode()
来源：http://dali.tianlin.xyz/Article/details/gtkhcqbkze.html

Go:   resp.StatusCode
来源：http://dali.zhiwuduotai.top/Article/details/gtdpujjypf.html

Ruby: resp.code.to_i
来源：http://dali.yuanzhike.top/Article/details/gtejrzzafa.html

C#:   (int)resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gtnorisupv.html

[L08] 并发请求多个地址
来源：http://dali.jqgufenzy.top/Article/details/gtdyqpwnij.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ybcxt.top/Article/details/gtnemsavhg.html

PHP:  curl_multi_init() 系列
来源：http://dali.daria6918.cn/Article/details/gthlfxhevd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gtnltlfhem.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gteieirkok.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daxiang520.top/Article/details/gtmjhmttys.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ivvv.top/Article/details/gtgxxwzfmm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guannengcc.top/Article/details/gtdcnxgwon.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gtrrdwayuk.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtqzdcswbi.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhiwuduotai.top/Article/details/gtfqptzpdt.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gttcnrsakb.html

[M01] 读取命令行参数
来源：http://dali.dashuyun.cn/Article/details/gtrnfkxoie.html

Py:   sys.argv[1:]
来源：http://dali.xylfe.cn/Article/details/gtefivtsdi.html

PHP:  $argv;  $argc;
来源：http://dali.feifeiyinyue.top/Article/details/gtqpzoiicb.html

JS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gtdujmelua.html

TS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gtwlhawunt.html

Java: args 数组（main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gtwwvuqbnx.html

Go:   os.Args[1:]
来源：http://dali.jyoumei.cn/Article/details/gtnziphnwz.html

Ruby: ARGV
来源：http://dali.hnxiangtu.top/Article/details/gtgtusnavu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gtqllewytp.html

[M02] 读取环境变量
来源：http://dali.hammf.cn/Article/details/gtqphokttf.html

Py:   os.environ.get("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtexcgzqhk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gtsemautfb.html

JS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtxnnlpyzg.html

TS:   process.env.HOME
来源：http://dali.redwolf501.top/Article/details/gtirfaqkgn.html

Java: System.getenv("HOME")
来源：http://dali.ivvv.top/Article/details/gtihorpike.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuanzx.com/Article/details/gthptckhro.html

Ruby: ENV["HOME"]
来源：http://dali.yuxming.cn/Article/details/gtwcaogxog.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtojjxvtmy.html

[M03] 执行外部命令
来源：http://dali.sxryk.cn/Article/details/gtbqxggbin.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtktmrgcxi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlcqbksz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gtmcfxepjm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gteltmtpfw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhixingplan.top/Article/details/gtpzzmifnj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigfzy.top/Article/details/gtmidttzkd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.kuanghao11.cn/Article/details/gtnqtqcosj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yvedp.cn/Article/details/gtmafoofpg.html

[M04] 获取当前工作目录
来源：http://dali.snrcjt.cn/Article/details/gtjyrrjzho.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdfftdip.html

PHP:  getcwd();
来源：http://dali.hnqzz.top/Article/details/gtfuppxfyb.html

JS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gtrrxpwhne.html

TS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gtfsqwetgs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sysykeji.top/Article/details/gtfchpucci.html

Go:   os.Getwd()
来源：http://dali.yj20258.top/Article/details/gtuspeityn.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gtklruiddr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ybcxt.top/Article/details/gtmyzaolcn.html

[M05] 设置退出码
来源：http://dali.zycfv.cn/Article/details/gtajjzrdwa.html

Py:   sys.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtuvadtozx.html

PHP:  exit(1);
来源：http://dali.shangyingyoupin.top/Article/details/gtqgjoqhvd.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnaxlogbh.html

TS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtdmqdweig.html

Java: System.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtxxsmyeyj.html

Go:   os.Exit(1)
来源：http://dali.ybcxt.top/Article/details/gtbyqpmysi.html

Ruby: exit 1
来源：http://dali.shuidangran.top/Article/details/gtngqinvzz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gtiunpcucs.html

[M06] 向标准错误输出
来源：http://dali.zhiwuduotai.top/Article/details/gtwtlpbghy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhengqikj.top/Article/details/gtufrbeduu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuetiantiany.cn/Article/details/gtomuptzsj.html

JS:   console.error("err")
来源：http://dali.sxryk.cn/Article/details/gtbhqwnswp.html

TS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gtcvhdkonq.html

Java: System.err.println("err")
来源：http://dali.hammf.cn/Article/details/gtllwfwyen.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hysaishi.cn/Article/details/gtaagkulwa.html

Ruby: warn "err"
来源：http://dali.sxryk.cn/Article/details/gtdlgwjlvv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jyoumei.cn/Article/details/gtggitokon.html

[M07] 判断是否为主入口
来源：http://dali.ppjwa.cn/Article/details/gtdxcxviqf.html

Py:   if __name__ == "__main__":
来源：http://dali.yuxming.cn/Article/details/gtxepxdtzv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.guowangkeji.top/Article/details/gtogiyybkn.html

JS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gtqjcpqvis.html

TS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gttztqgrkn.html

Java: public static void main(String[] args)
来源：http://dali.xylfe.cn/Article/details/gtxamlkujx.html

Go:   func main()
来源：http://dali.guowangkeji.top/Article/details/gtcmgojzkp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shzxlz.cn/Article/details/gtinfhcuxn.html

C#:   static void Main(string[] args)
来源：http://dali.vqdsnc.cn/Article/details/gtehempvlj.html

[M08] 获取系统与运行时信息
来源：http://dali.haohaochexian.top/Article/details/gtatyeemnw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.svipenyu.cn/Article/details/gtupzwvwjf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hnqzz.top/Article/details/gthvxdfeih.html

JS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gtplskrmyw.html

TS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gtnmyejkxf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tianlin.xyz/Article/details/gtjymyotig.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dianchejie.cn/Article/details/gtorszzdri.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shangyingyoupin.top/Article/details/gtqydbtcgc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guannengcc.top/Article/details/gtbzzspkvv.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtpuyomrec.html

N. 数据结构与算法
来源：http://dali.mhx1999.top/Article/details/gtbtwztkyz.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtafmrxvcn.html

[N01] 二分查找（有序数组）
来源：http://dali.hammf.cn/Article/details/gtqsagfuwo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtlizkniec.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj202588.top/Article/details/gtszdjlofb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gtkvdzgpez.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gtavteiivy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtkdfzukoc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtcdtqzkcn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ybcxt.top/Article/details/gtplzxzbwq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtsvrcsfqa.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yangfankeji.com/Article/details/gtkrikkrml.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gteyolnpsz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmibjcpyt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gtghdakjyt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gtiaziwndu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnxiangtu.top/Article/details/gtkifqoeoe.html

Go:   slices.Sort(arr)
来源：http://dali.jiagoushi.top/Article/details/gtpopvylyh.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gtdmueikas.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ivvv.top/Article/details/gtpyjnxhuq.html

[N03] 快速排序（分治示例）
来源：http://dali.jyoumei.cn/Article/details/gtatxbbbko.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zdqjudy.top/Article/details/gturzlkflg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shzxlz.cn/Article/details/gtweuotudr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gtiziccgdo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gtcaeskbrd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guannengcc.top/Article/details/gtbkrdudlm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zycfv.cn/Article/details/gtfevqgakp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.iojbl.cn/Article/details/gtlxxxiimt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shzxlz.cn/Article/details/gthmnccfla.html

[N04] 斐波那契数列
来源：http://dali.hammf.cn/Article/details/gteyiycbrv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gtmonrdvys.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.birdmap.top/Article/details/gtsohoynqc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtcfyqguot.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gtwfjasduu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gzhubu.top/Article/details/gtxhgfyayp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.316326.xyz/Article/details/gttiucshgx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtiorspyyj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtjakafelr.html

[N05] 最大公约数
来源：http://dali.tanke756.top/Article/details/gtizedpshl.html

Py:   math.gcd(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtxmzpatgm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbusldjba.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shuidangran.top/Article/details/gtqhzwqupk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gtlsylwvss.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenlongwang.top/Article/details/gtkpligoiw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnqzz.top/Article/details/gtpyhazjzp.html

Ruby: a.gcd(b)
来源：http://dali.zhengqikj.top/Article/details/gtsbxgmqqn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hywenlv.cn/Article/details/gtopwsiwjo.html

[N06] 判断回文字符串
来源：http://dali.kuanghao11.cn/Article/details/gtmezqauai.html

Py:   s == s[::-1]
来源：http://dali.andypj.xyz/Article/details/gtophwwclq.html

PHP:  $s === strrev($s);
来源：http://dali.yj202588.top/Article/details/gtthjbrwqh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtwchirezh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtgflxcntd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.andypj.xyz/Article/details/gtirkxvlyv.html

Go:   // 双指针从两端比较
来源：http://dali.hongshengwenyu.top/Article/details/gtapxozfqk.html

Ruby: s == s.reverse
来源：http://dali.cheryme.top/Article/details/gtzffzkybn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gtrswydwyj.html

[N07] 两数之和（返回下标）
来源：http://dali.gogol.net.cn/Article/details/gttcdklcdz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj202588.top/Article/details/gtuqwmyjvk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ivvv.top/Article/details/gtjprwcddi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhiwuduotai.top/Article/details/gthvddnoze.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhixingplan.top/Article/details/gtlnfqzmoq.html

Java: // 手写 HashMap
来源：http://dali.xinyue.icu/Article/details/gtunsarpnz.html

Go:   // 手写 map[int]int
来源：http://dali.zhongyouzk.top/Article/details/gttvmkqkzh.html

Ruby: // 手写 Hash
来源：http://dali.ydzc1.top/Article/details/gtajvkigak.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjdwlyrn.html

[N08] 生成全排列
来源：http://dali.chenzaomai.com/Article/details/gtgujugiqz.html

Py:   itertools.permutations(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtbgalgzyu.html

PHP:  // 手写递归交换
来源：http://dali.ybcxt.top/Article/details/gtxxcgrxxy.html

JS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtltozcivr.html

TS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtyeztqlzm.html

Java: // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gteebdkxhd.html

Go:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtbnuxasuq.html

Ruby: arr.permutation.to_a
来源：http://dali.zhengqikj.top/Article/details/gtrmogixjm.html

C#:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtnavcfcbd.html

[N09] 栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gtbcmfwxor.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenlongwang.top/Article/details/gtxkntekhe.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj20258.top/Article/details/gtawtglyvq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fzhhl.top/Article/details/gtougttmow.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxinkj.top/Article/details/gtykcekptr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daxiang520.top/Article/details/gtgbfwtlyr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ehwqpu.com/Article/details/gtmslydjlv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtwvpgxsht.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ppjwa.cn/Article/details/gtuwfdhpbp.html

[N10] 链表节点定义
来源：http://dali.feifeiyinyue.top/Article/details/gtegiscahm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.quarkkingdee.top/Article/details/gtveiwlcgk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenzaomai.com/Article/details/gtdwcdyhha.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hfpthk.cn/Article/details/gtmgtywlrs.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sysykeji.top/Article/details/gtfehktvau.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgsabcoh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gaohongyu789.top/Article/details/gtzayodhsx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.redwolf501.top/Article/details/gtfgvftcoa.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhmunfrv.html

[N11] 二叉树中序遍历
来源：http://dali.sufxvd.cn/Article/details/gtwhlrpird.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpobeeij.html

PHP:  // 手写递归函数
来源：http://dali.daxiang520.top/Article/details/gtcjhaxpgh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gtuvskwyqn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gtqkpoxvai.html

Java: // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtizzdjhzy.html

Go:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtsvflaegz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yangfankeji.com/Article/details/gtqluestyg.html

C#:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gtmcprctmy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.quarkkingdee.top/Article/details/gtvdnuvezo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nanxinkj.top/Article/details/gtilqqxysw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenlongwang.top/Article/details/gtjbsjkblx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yueranfly.top/Article/details/gtievzzkxm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gtvcqkyydu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gtdavvdgrj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daria6918.cn/Article/details/gtqsubzwis.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.wangdashe.top/Article/details/gtmzktufuj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gtkskxzjrk.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtgypmnwph.html

O. 并发与异步
来源：http://dali.xylfe.cn/Article/details/gtcmyfzbjl.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtlwxauhiy.html

[O01] 启动一个线程
来源：http://dali.jqgufenzy.top/Article/details/gthcnvqqpg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.vqdsnc.cn/Article/details/gtlkjmpffu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnxiangtu.top/Article/details/gthswnpuoa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ybcxt.top/Article/details/gthzzqeqlc.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gtgysfttqp.html

Java: new Thread(() -> f()).start()
来源：http://dali.cdnleiting.top/Article/details/gtjkzaujjm.html

Go:   go f()
来源：http://dali.pycfn.com/Article/details/gtjkpdrpdt.html

Ruby: Thread.new { f }
来源：http://dali.jiagoushi.top/Article/details/gtzjezyera.html

C#:   Task.Run(() => F());
来源：http://dali.ivvv.top/Article/details/gthrujdnrh.html

[O02] 使用线程池
来源：http://dali.yueranfly.top/Article/details/gtmypvpndg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.c1oappe.top/Article/details/gtpambylfv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.feifeiyinyue.top/Article/details/gtkptvnlvd.html

JS:   // worker_threads 线程池
来源：http://dali.pycfn.com/Article/details/gtahzzehjq.html

TS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gtqerstsys.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.andypj.xyz/Article/details/gtxytyfrbv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cheryme.top/Article/details/gtvohdabcv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ydzc1.top/Article/details/gtuxotepqn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnqzz.top/Article/details/gtpgdpgmma.html

[O03] 加锁保护共享数据
来源：http://dali.cdnleiting.top/Article/details/gtyhpkzmhu.html

Py:   with lock: shared += 1
来源：http://dali.birdmap.top/Article/details/gtyxshuigq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gotoacloud.top/Article/details/gtzwxwpzey.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgfzy.top/Article/details/gtnozgvzxn.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gtuorfxjlx.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gtkwqaihfk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.andypj.xyz/Article/details/gtzakziwfj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gtzpbkieuf.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenlongwang.top/Article/details/gtdjgthmql.html

[O04] 定义异步函数并等待
来源：http://dali.ivvv.top/Article/details/gtbqrzlkek.html

Py:   async def f():⏎    await g()
来源：http://dali.xinyue.icu/Article/details/gtoyxwfxpl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tanke756.top/Article/details/gthiojmamk.html

JS:   async function f() { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtejbmrrdb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtdiyducco.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fengsongda.top/Article/details/gtohjjyckt.html


<!-- 参考信息 -->