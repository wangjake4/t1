代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangdashe.top/Article/details/gtqatjlrrv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtjqirijxi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenlongwang.top/Article/details/gtmaijtqch.html

Py:   pickle.dumps(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtsufmfdky.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jyoumei.cn/Article/details/gttgsrykxm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gtytdhziax.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ppjwa.cn/Article/details/gtvjvdtdbn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jianghu66.top/Article/details/gtsuahnxvi.html

Go:   encoding/gob
来源：http://dali.jinghuilouyu.cn/Article/details/gttamnpggo.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuxming.cn/Article/details/gtalvwbvod.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gtwergyqrc.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtdhhdedvc.html

L. 网络请求
来源：http://dali.ppjwa.cn/Article/details/gtifhchauo.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtunnavkmi.html

[L01] 发送 GET 请求
来源：http://dali.jianghu66.top/Article/details/gtjdddwxgv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tianlin.xyz/Article/details/gtixmvpatp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daria6918.cn/Article/details/gtwgouuhrm.html

JS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gttjblqsth.html

TS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gtgtbpjlma.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shangyingyoupin.top/Article/details/gtcbkqraky.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenzaomai.com/Article/details/gtajndstqk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangdashe.top/Article/details/gtkbkmfugg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqnxbffg.html

[L02] 发送 POST JSON
来源：http://dali.mhx1999.top/Article/details/gtflcaioth.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yongpay.top/Article/details/gtosykfiur.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aibaodan.cn/Article/details/gtheieerbe.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gtefxxggzr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gtcbslnjqv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nanxuanxn.top/Article/details/gtuladgtvj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhiwuduotai.top/Article/details/gtkfqyzhao.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigfzy.top/Article/details/gtttjqfhfq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tian-w.cn/Article/details/gtqvqmyckl.html

[L03] 设置自定义请求头
来源：http://dali.cdnleiting.top/Article/details/gtwulagyzj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zdqjudy.top/Article/details/gtablfmyvv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aizwys.cn/Article/details/gtqjepnjfn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gtcpzdiqmm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gtwqbeibmc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gteksfkokx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gtxsaitfib.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guannengcc.top/Article/details/gthbmxfhvp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangshuangyany.cn/Article/details/gtphxqgfdv.html

[L04] 设置超时
来源：http://dali.zhongyouzk.top/Article/details/gtfvwssoat.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guowangkeji.top/Article/details/gtoftfibbw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.iojbl.cn/Article/details/gttrjrhyej.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tanke756.top/Article/details/gtkvreqzuw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gtsxvbwmyo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gtsvqznhye.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pengpengdd.cyou/Article/details/gtlqxxyjdu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ybcxt.top/Article/details/gtdrfzparf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ybcxt.top/Article/details/gtepcuniqs.html

[L05] 上传文件（multipart）
来源：http://dali.jqgufenzy.top/Article/details/gtteklodjr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenlongwang.top/Article/details/gteggukssz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.quarkkingdee.top/Article/details/gtgpynjthj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexeuitgf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gtvncujdmt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuanzx.com/Article/details/gtfmzejduc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cqqwz.cn/Article/details/gtogknzavb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.c1oappe.top/Article/details/gtyawlnhte.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgfzy.top/Article/details/gttkstivts.html

[L06] 解析响应为 JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtyyiwmulq.html

Py:   resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtadrlslkh.html

PHP:  json_decode($body, true);
来源：http://dali.dianchejie.cn/Article/details/gtzhprmzft.html

JS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtijhirdhp.html

TS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gtfersaqft.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jiagoushi.top/Article/details/gtggpzyvnu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aizwys.cn/Article/details/gtkwaziiaa.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhixingplan.top/Article/details/gtqnyuyzew.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ivvv.top/Article/details/gtjsewsmmf.html

[L07] 处理 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gtwazoyavw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cdnleiting.top/Article/details/gtzuhzxaat.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cheryme.top/Article/details/gtdlnlsavz.html

JS:   resp.ok;  resp.status
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwadqhuj.html

TS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gtupsjpnuk.html

Java: resp.statusCode()
来源：http://dali.zhongyouzk.top/Article/details/gtsiirfcrz.html

Go:   resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gtymyhszgj.html

Ruby: resp.code.to_i
来源：http://dali.sxryk.cn/Article/details/gteytcikpj.html

C#:   (int)resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gtolcdxvao.html

[L08] 并发请求多个地址
来源：http://dali.meibo888.top/Article/details/gtrvvppguh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.pycfn.com/Article/details/gtqkkcgegj.html

PHP:  curl_multi_init() 系列
来源：http://dali.shanyushiyangkeji.top/Article/details/gticbtodfq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gthcboitrl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gtrstkyvlg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.feifeiyinyue.top/Article/details/gtgbslzxce.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shuidangran.top/Article/details/gtifjvflux.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hywenlv.cn/Article/details/gtqewdymew.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cheryme.top/Article/details/gtvwzlsozs.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gthcnjnuus.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhiwuduotai.top/Article/details/gtasjadlbb.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtfbqngqhi.html

[M01] 读取命令行参数
来源：http://dali.ppjwa.cn/Article/details/gtlwupldiz.html

Py:   sys.argv[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtjeuajwfw.html

PHP:  $argv;  $argc;
来源：http://dali.316326.xyz/Article/details/gtlszbgoll.html

JS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gtsavzxmec.html

TS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gtvljhlxdd.html

Java: args 数组（main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gtrwjbzsgm.html

Go:   os.Args[1:]
来源：http://dali.xuanzx.com/Article/details/gtfrtdikzc.html

Ruby: ARGV
来源：http://dali.shuidangran.top/Article/details/gtxzubhkct.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gtxepcikvj.html

[M02] 读取环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtwfjxizhh.html

Py:   os.environ.get("HOME")
来源：http://dali.nwbrower.top/Article/details/gtpkjwmvts.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtfwlhmpka.html

JS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gtxxwuwayr.html

TS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gtohkrjavl.html

Java: System.getenv("HOME")
来源：http://dali.wangdashe.top/Article/details/gtvhbfjjmv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtircruvco.html

Ruby: ENV["HOME"]
来源：http://dali.cashguo.top/Article/details/gtesdamaqw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tian-w.cn/Article/details/gtlnkdkvxa.html

[M03] 执行外部命令
来源：http://dali.ppjwa.cn/Article/details/gtqsygleyh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.0kj1m.cn/Article/details/gtihxjrmlz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258888.top/Article/details/gtjbdvcxuh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtxuwxeoid.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gtvyjfqzkt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ivvv.top/Article/details/gtfquoqykm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmuneemlg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.iojbl.cn/Article/details/gtszngcfun.html

C#:   Process.Start("ls", "-l");
来源：http://dali.bjfxy.top/Article/details/gtaiamsilr.html

[M04] 获取当前工作目录
来源：http://dali.nwbrower.top/Article/details/gtgvmmngbr.html

Py:   os.getcwd()
来源：http://dali.xylfe.cn/Article/details/gtcwjozquw.html

PHP:  getcwd();
来源：http://dali.jqgufenzy.top/Article/details/gthrsxeeoy.html

JS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrkdsycj.html

TS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gtghjvlmqg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ppjwa.cn/Article/details/gtpzaquwvm.html

Go:   os.Getwd()
来源：http://dali.gotoacloud.top/Article/details/gtmrhowtak.html

Ruby: Dir.pwd
来源：http://dali.iojbl.cn/Article/details/gtukprucuc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkyymlrid.html

[M05] 设置退出码
来源：http://dali.nanxinkj.top/Article/details/gtaxrxapkz.html

Py:   sys.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtgwxrtarc.html

PHP:  exit(1);
来源：http://dali.jqgufenzy.top/Article/details/gtfqywrfzd.html

JS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtvwrvmwbd.html

TS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gthakkbkdn.html

Java: System.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtsoqtbtue.html

Go:   os.Exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtbtmlxrry.html

Ruby: exit 1
来源：http://dali.ppjwa.cn/Article/details/gtapvqmdpf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigufen.top/Article/details/gtslxnlozx.html

[M06] 向标准错误输出
来源：http://dali.nanxuanxn.top/Article/details/gtigvvzrdx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gtpjvnlgek.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cdnleiting.top/Article/details/gtkdojxjfc.html

JS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gthxlypbsc.html

TS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gtmvorsows.html

Java: System.err.println("err")
来源：http://dali.hnqzz.top/Article/details/gtztyildwr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jianghu66.top/Article/details/gtkbxnjxop.html

Ruby: warn "err"
来源：http://dali.hnxiangtu.top/Article/details/gtiexsrpqo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jianghu66.top/Article/details/gtqjmjueao.html

[M07] 判断是否为主入口
来源：http://dali.yuanzhike.top/Article/details/gteshqypfs.html

Py:   if __name__ == "__main__":
来源：http://dali.zhoulong.xyz/Article/details/gtdwdrxajl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvanyzjo.html

JS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gtqwbyiqpu.html

TS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gtvznabbnw.html

Java: public static void main(String[] args)
来源：http://dali.redwolf501.top/Article/details/gtewwfprdb.html

Go:   func main()
来源：http://dali.havefunace.top/Article/details/gtmhowpuzq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgufenzy.top/Article/details/gtspjkqbot.html

C#:   static void Main(string[] args)
来源：http://dali.wangdashe.top/Article/details/gtailaivjp.html

[M08] 获取系统与运行时信息
来源：http://dali.yj202588.top/Article/details/gthvcnlufv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhengqikj.top/Article/details/gtjeqkvzxv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.haohaochexian.top/Article/details/gtuxqqlhzx.html

JS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gtfqwxxpni.html

TS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gtlktwiytw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.svipenyu.cn/Article/details/gtocxwguzj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhoulong.xyz/Article/details/gtdyqkhbtd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ppjwa.cn/Article/details/gtdevuetug.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.snrcjt.cn/Article/details/gtxjdcuies.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtdtfsulsv.html

N. 数据结构与算法
来源：http://dali.ivvv.top/Article/details/gtopafppqg.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtnryoxfus.html

[N01] 二分查找（有序数组）
来源：http://dali.snrcjt.cn/Article/details/gtocscnhbt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj202588.top/Article/details/gtxekgakaz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtffuvusrx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gtumfxrpvd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtafphpmki.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtczmvscqr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtkstssqfe.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenzaomai.com/Article/details/gtlyqaatmq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.316326.xyz/Article/details/gtbcngkeqt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangshuangyany.cn/Article/details/gtdrypkeab.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.9152youxi.cn/Article/details/gtqzgswefy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtfohyrveh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gtlpmbgmis.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gtmhwwtumj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pycfn.com/Article/details/gtgvyxwact.html

Go:   slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtwwgooaxf.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gtneujsynu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gogol.net.cn/Article/details/gtmelewila.html

[N03] 快速排序（分治示例）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyuxmfgzw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuetiantiany.cn/Article/details/gtsujgkewj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.smart0.xyz/Article/details/gtxarqywhg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gtcfwltzlc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gtjdhjqvev.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xinyue.icu/Article/details/gtoahelapy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgflwhag.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.havefunace.top/Article/details/gtgudlufbj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yueranfly.top/Article/details/gtjsbtuspr.html

[N04] 斐波那契数列
来源：http://dali.zhengqikj.top/Article/details/gtshvkhchp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gtbckqzxtw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.redwolf501.top/Article/details/gtczdkvtrq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gttvkfsiqm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdqfjvla.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ivvv.top/Article/details/gttmgphbhr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.vqdsnc.cn/Article/details/gtfthjmxin.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtrhtzcqfb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gtbbjjunjq.html

[N05] 最大公约数
来源：http://dali.shuidangran.top/Article/details/gtthmquyln.html

Py:   math.gcd(a, b)
来源：http://dali.wangdashe.top/Article/details/gtgaqixsyn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cashguo.top/Article/details/gtuoizwwtt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxinkj.top/Article/details/gtmneseyym.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtgpdhqihe.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.0kj1m.cn/Article/details/gtzgfidmxm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sufxvd.cn/Article/details/gtdsfqoyco.html

Ruby: a.gcd(b)
来源：http://dali.sxryk.cn/Article/details/gtrofumfgx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yvedp.cn/Article/details/gtdvgffmal.html

[N06] 判断回文字符串
来源：http://dali.tian-w.cn/Article/details/gtwlmqjhdf.html

Py:   s == s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gtyzhgablp.html

PHP:  $s === strrev($s);
来源：http://dali.meibo888.top/Article/details/gtrfkpdctf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtrhjkqpoh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtkfuirorh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shzxlz.cn/Article/details/gtwsfpxvxe.html

Go:   // 双指针从两端比较
来源：http://dali.jyoumei.cn/Article/details/gtsdefdwny.html

Ruby: s == s.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvgzwmkv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gtmlvkqvsf.html

[N07] 两数之和（返回下标）
来源：http://dali.sweek.top/Article/details/gtbjdmdtcz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangshuangyany.cn/Article/details/gthbwpnzgz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hongshengwenyu.top/Article/details/gtcymkdsph.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.feifeiyinyue.top/Article/details/gthrkozbft.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhongyouzk.top/Article/details/gtukzuaqsk.html

Java: // 手写 HashMap
来源：http://dali.hammf.cn/Article/details/gtewklzbcj.html

Go:   // 手写 map[int]int
来源：http://dali.wangshuangyany.cn/Article/details/gtxgcbdbds.html

Ruby: // 手写 Hash
来源：http://dali.jiagoushi.top/Article/details/gtljqkfvvb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gogol.net.cn/Article/details/gtvqdvdrow.html

[N08] 生成全排列
来源：http://dali.gotoacloud.top/Article/details/gtwkclomnm.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtdqsrfrxr.html

PHP:  // 手写递归交换
来源：http://dali.guowangkeji.top/Article/details/gttheeumvu.html

JS:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtcndzocpd.html

TS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcvbuxjc.html

Java: // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtlmojwkho.html

Go:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtgkeylues.html

Ruby: arr.permutation.to_a
来源：http://dali.kuanghao11.cn/Article/details/gtkdawjyil.html

C#:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtrdqbaylx.html

[N09] 栈与队列
来源：http://dali.jinqigufen.top/Article/details/gtpdcgeycc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtentdbikr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gtzjcazaly.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtxktofkda.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nwbrower.top/Article/details/gtwpiwcjla.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sysykeji.top/Article/details/gtjmlkqfww.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jyoumei.cn/Article/details/gtcbhzjmvk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtlwdhmhcl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhoulong.xyz/Article/details/gtuwlalzwp.html

[N10] 链表节点定义
来源：http://dali.xuetiantiany.cn/Article/details/gthdfclpdd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sysykeji.top/Article/details/gtbrtwthmo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhiwuduotai.top/Article/details/gtppeemonx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.quarkkingdee.top/Article/details/gtdkvyooqo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tianlin.xyz/Article/details/gtpjpnagfm.html

Java: class Node { int v; Node next; }
来源：http://dali.c1oappe.top/Article/details/gtqsclqpbp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigfzy.top/Article/details/gtnllfukqf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pengpengdd.cyou/Article/details/gtyirikorn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258888.top/Article/details/gtxbtnfkcs.html

[N11] 二叉树中序遍历
来源：http://dali.jqgfzy.top/Article/details/gtzfyscauj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.andypj.xyz/Article/details/gtsygeubmv.html

PHP:  // 手写递归函数
来源：http://dali.yangfankeji.com/Article/details/gtkhcgnhjn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.smart0.xyz/Article/details/gtqahsapnn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgufenzy.top/Article/details/gttvbbkbsa.html

Java: // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtnkgdmxel.html

Go:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gtusiqhqlz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sxryk.cn/Article/details/gtofzkyimu.html

C#:   // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmtbymre.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinqigfzy.top/Article/details/gtcwqjrkpa.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.meibo888.top/Article/details/gtbdmwkqlm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.wangshuangyany.cn/Article/details/gtfugdqofa.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gtmwbwqfhh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gtfvpwhyfl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gthzfbwtqn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gogol.net.cn/Article/details/gtsylogcpl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shzxlz.cn/Article/details/gtsjisfpkp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shzxlz.cn/Article/details/gtlfmxijgw.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gteiqyixrq.html

O. 并发与异步
来源：http://dali.ivvv.top/Article/details/gtzigddpfm.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtfkckfnnl.html

[O01] 启动一个线程
来源：http://dali.yanxiufei.cn/Article/details/gtuemkqtxh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jlsjyb.cn/Article/details/gtauxdyvpy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aibaodan.cn/Article/details/gthnmksubf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhiwuduotai.top/Article/details/gtxydmcqqm.html

TS:   // 同 JS
来源：http://dali.sysykeji.top/Article/details/gtcmwzzmtf.html

Java: new Thread(() -> f()).start()
来源：http://dali.guowangkeji.top/Article/details/gtuxbfgmsb.html

Go:   go f()
来源：http://dali.zhiwuduotai.top/Article/details/gtncfynhai.html

Ruby: Thread.new { f }
来源：http://dali.zhoulong.xyz/Article/details/gtddguhysv.html

C#:   Task.Run(() => F());
来源：http://dali.dashuyun.cn/Article/details/gtihsdovhn.html

[O02] 使用线程池
来源：http://dali.andypj.xyz/Article/details/gtirmabwrm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jlsjyb.cn/Article/details/gtdcifwwlf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.pycfn.com/Article/details/gtpwmitvyq.html

JS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gtimvwrmoc.html

TS:   // worker_threads 线程池
来源：http://dali.haohaochexian.top/Article/details/gtzwhumlgp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cdnleiting.top/Article/details/gtlphitlpp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shzxlz.cn/Article/details/gtynazmhgg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hammf.cn/Article/details/gtwaokoyqm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrcjenpy.html

[O03] 加锁保护共享数据
来源：http://dali.ehwqpu.com/Article/details/gtoogndhgo.html

Py:   with lock: shared += 1
来源：http://dali.wangshuangyany.cn/Article/details/gtnqekfpwh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guannengcc.top/Article/details/gtpmsowvrr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhongyouzk.top/Article/details/gtlldrzqro.html

TS:   // 同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjsykhjm.html

Java: synchronized (this) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gtkplekrhg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.feifeiyinyue.top/Article/details/gtfkhsfwzr.html


<!-- 参考信息 -->