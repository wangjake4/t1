代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtjtmqalxj.html

[K07] 进制转换
来源：http://dali.ppjwa.cn/Article/details/gtwfrnowkk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtdfagalfl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangtech.top/Article/details/gtzclueztr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtdltjlwwl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtszdqyxjd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtjcxiuuuk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewypdwli.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ivvv.top/Article/details/gtxaxiujdc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtwedscnrv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yvedp.cn/Article/details/gtojwmblny.html

Py:   pickle.dumps(obj)
来源：http://dali.tian-w.cn/Article/details/gtstxhizsi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.smart0.xyz/Article/details/gtozesndru.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gtvjkkikmi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gtbatkbsen.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yonumen.top/Article/details/gthtxgypna.html

Go:   encoding/gob
来源：http://dali.sufxvd.cn/Article/details/gtvqirmjaw.html

Ruby: Marshal.dump(obj)
来源：http://dali.gzhubu.top/Article/details/gtgwsmtpbe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tanke756.top/Article/details/gtkcibbpnk.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtkuthzzmn.html

L. 网络请求
来源：http://dali.havefunace.top/Article/details/gtbqmmhmba.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gthjbkknux.html

[L01] 发送 GET 请求
来源：http://dali.hywenlv.cn/Article/details/gtkwwrypts.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.mhx1999.top/Article/details/gteellcble.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhixingplan.top/Article/details/gtpqzkcgoo.html

JS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gtsycekstd.html

TS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gtodgcsbgo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenzaomai.com/Article/details/gtsqszgayv.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnqzz.top/Article/details/gthradndua.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cheryme.top/Article/details/gtalaslioz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gtdvzqndxb.html

[L02] 发送 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gtynuqwlgf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.c1oappe.top/Article/details/gtmyzwxqqi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.bjfxy.top/Article/details/gtxpegtequ.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjepeysv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cashguo.top/Article/details/gtgilxakln.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gaohongyu789.top/Article/details/gtbiowoxzv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpwbahjr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hfpthk.cn/Article/details/gtuslkcpsf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aibaodan.cn/Article/details/gtbypjorct.html

[L03] 设置自定义请求头
来源：http://dali.cheryme.top/Article/details/gtkwytldqw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aizwys.cn/Article/details/gtetllrdrw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tanke756.top/Article/details/gtzfybrpti.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhixingplan.top/Article/details/gtpaunouwl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gtntficokx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gogol.net.cn/Article/details/gtioplosfb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gtfzquxrqu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shanyushiyangtech.top/Article/details/gtzoyoobde.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhoulong.xyz/Article/details/gtbeglyiaj.html

[L04] 设置超时
来源：http://dali.xinyue.icu/Article/details/gtrdhwfpix.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cheryme.top/Article/details/gtfctnsmpd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxuanxn.top/Article/details/gtotmefdcx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gtdwnotpqv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.haohaochexian.top/Article/details/gtxngaqmww.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.vqdsnc.cn/Article/details/gtaiskwtoe.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sysykeji.top/Article/details/gtqjlkdqbi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dashuyun.cn/Article/details/gtmvfvbhhk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jyoumei.cn/Article/details/gtkjjuxgje.html

[L05] 上传文件（multipart）
来源：http://dali.dashuyun.cn/Article/details/gtnmyiaxfg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.meibo888.top/Article/details/gtpqzzeoyw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ppjwa.cn/Article/details/gtyszmpckx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtfsmjcegt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gtoqtwnqgl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shangyingyoupin.top/Article/details/gtmyhcrlec.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sweek.top/Article/details/gthfgxfnxk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jianghu66.top/Article/details/gtbhdolwjv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cheryme.top/Article/details/gtkkbmqoli.html

[L06] 解析响应为 JSON
来源：http://dali.xylfe.cn/Article/details/gttkfiwtzh.html

Py:   resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtefomycjw.html

PHP:  json_decode($body, true);
来源：http://dali.0kj1m.cn/Article/details/gttpwjlyij.html

JS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gtreqslcmc.html

TS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gtsudwagmg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtbmylqnrb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigfzy.top/Article/details/gteaqajtsz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hongshengwenyu.top/Article/details/gtdhqtioix.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nwbrower.top/Article/details/gtbnbiykxr.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtisvqdztk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvyirwgbi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cqqwz.cn/Article/details/gtkylvwikg.html

JS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gtmujfqien.html

TS:   resp.ok;  resp.status
来源：http://dali.yueranfly.top/Article/details/gttugdwfja.html

Java: resp.statusCode()
来源：http://dali.jiagoushi.top/Article/details/gtummjatut.html

Go:   resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gtobypmdxi.html

Ruby: resp.code.to_i
来源：http://dali.hfpthk.cn/Article/details/gtlzariwna.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gtkfzpvwxy.html

[L08] 并发请求多个地址
来源：http://dali.aizwys.cn/Article/details/gtdonxybbr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sweek.top/Article/details/gtbxbysvqq.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnqzz.top/Article/details/gtbdvyqtik.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtshzcoiae.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gtgyynjsot.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinghuilouyu.cn/Article/details/gttkrbfmuq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dianchejie.cn/Article/details/gteeefuwht.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.mhx1999.top/Article/details/gtdhrcmjjk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guowangkeji.top/Article/details/gtgvukgcih.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtbsvqujyv.html

M. 命令行 / 进程 / 环境
来源：http://dali.svipenyu.cn/Article/details/gtfrsvdfms.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtabalcbwf.html

[M01] 读取命令行参数
来源：http://dali.xinyue.icu/Article/details/gtkhetrwbr.html

Py:   sys.argv[1:]
来源：http://dali.ydzc1.top/Article/details/gtqhsepqas.html

PHP:  $argv;  $argc;
来源：http://dali.gaohongyu789.top/Article/details/gtzmhrdhvv.html

JS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gtvuocqscr.html

TS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gtivfgupmz.html

Java: args 数组（main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gtdgrkgmqm.html

Go:   os.Args[1:]
来源：http://dali.guowangkeji.top/Article/details/gttvijtpym.html

Ruby: ARGV
来源：http://dali.fzhhl.top/Article/details/gtngecegcs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gtpgphrsro.html

[M02] 读取环境变量
来源：http://dali.yuxming.cn/Article/details/gtyywzcctp.html

Py:   os.environ.get("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtzneadcnq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhongyouzk.top/Article/details/gtpdntfznn.html

JS:   process.env.HOME
来源：http://dali.316326.xyz/Article/details/gtzuednzbq.html

TS:   process.env.HOME
来源：http://dali.snrcjt.cn/Article/details/gtsfwcnwdf.html

Java: System.getenv("HOME")
来源：http://dali.xziqi.cn/Article/details/gtflhhomzq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtftpuyifv.html

Ruby: ENV["HOME"]
来源：http://dali.zhiwuduotai.top/Article/details/gtiljcdlif.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ydzc1.top/Article/details/gtkppasfxu.html

[M03] 执行外部命令
来源：http://dali.ehwqpu.com/Article/details/gtkhezvqyb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuxming.cn/Article/details/gtzothaise.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ivvv.top/Article/details/gtuomeyjbn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvznhxugz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtdmytrlqy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.c1oappe.top/Article/details/gtltwwkpeg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhoulong.xyz/Article/details/gtjweykxdu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtndfhcr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgfzy.top/Article/details/gtikebuunn.html

[M04] 获取当前工作目录
来源：http://dali.daxiang520.top/Article/details/gteypwudvp.html

Py:   os.getcwd()
来源：http://dali.jqgfzy.top/Article/details/gtsilbzvsw.html

PHP:  getcwd();
来源：http://dali.jqgufenzy.top/Article/details/gtaarlempo.html

JS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtokdikcwn.html

TS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gtkgxdhuyq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuanzhike.top/Article/details/gtimhxpths.html

Go:   os.Getwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbchivgv.html

Ruby: Dir.pwd
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjfxedyz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yueranfly.top/Article/details/gthqhjkgpa.html

[M05] 设置退出码
来源：http://dali.ybcxt.top/Article/details/gtfvhpkpxg.html

Py:   sys.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtjtvdtfdt.html

PHP:  exit(1);
来源：http://dali.shangyingyoupin.top/Article/details/gtjpxthuru.html

JS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgiovnwjb.html

TS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtikidzmji.html

Java: System.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtltegzevt.html

Go:   os.Exit(1)
来源：http://dali.meibo888.top/Article/details/gtndxgsdbo.html

Ruby: exit 1
来源：http://dali.gzhubu.top/Article/details/gtzdyumtry.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yanxiufei.cn/Article/details/gttfaympte.html

[M06] 向标准错误输出
来源：http://dali.0kj1m.cn/Article/details/gtqimiixfz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gtuibxattt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aibaodan.cn/Article/details/gtdsmqhpxs.html

JS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gtvkvbhrzd.html

TS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gtcbypkszj.html

Java: System.err.println("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylguxzmm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxuanxn.top/Article/details/gtyszmggse.html

Ruby: warn "err"
来源：http://dali.chenlongwang.top/Article/details/gthnsuekna.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangdashe.top/Article/details/gtznwilmyp.html

[M07] 判断是否为主入口
来源：http://dali.iojbl.cn/Article/details/gtrlvwhudg.html

Py:   if __name__ == "__main__":
来源：http://dali.gogol.net.cn/Article/details/gtnvuddags.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhongyouzk.top/Article/details/gtacsgukht.html

JS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gtggvhngqk.html

TS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gtqvdohoek.html

Java: public static void main(String[] args)
来源：http://dali.yj202588.top/Article/details/gttwyobeol.html

Go:   func main()
来源：http://dali.jinghuilouyu.cn/Article/details/gtytovqlua.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.c1oappe.top/Article/details/gtegwgbjpk.html

C#:   static void Main(string[] args)
来源：http://dali.pycfn.com/Article/details/gtyylxvdrl.html

[M08] 获取系统与运行时信息
来源：http://dali.pycfn.com/Article/details/gtphmdwalh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yongpay.top/Article/details/gtqdxmqcol.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tian-w.cn/Article/details/gtnxemjsws.html

JS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gtbpgfjnps.html

TS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gtvjnulzez.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.c1oappe.top/Article/details/gtvbxotfpi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yongpay.top/Article/details/gtjdmpqkqh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gotoacloud.top/Article/details/gtbguxmeuc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jyoumei.cn/Article/details/gtwwuxsdgc.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtwxwfpdzk.html

N. 数据结构与算法
来源：http://dali.andypj.xyz/Article/details/gtsdvfylkd.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtwknnroqs.html

[N01] 二分查找（有序数组）
来源：http://dali.haohaochexian.top/Article/details/gtshknceyd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pycfn.com/Article/details/gtepbyvtom.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yongpay.top/Article/details/gtfrwnazcq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtgeqymnvt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtxajckliq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtcmevprzv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtuqmgdrqa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yangfankeji.com/Article/details/gtbhgsmrox.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gtefwsgaia.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tanke756.top/Article/details/gtzaczjenn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gtofnatwba.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.svipenyu.cn/Article/details/gtdqsmdlze.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtaecyvmgx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gtxbstcokw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hywenlv.cn/Article/details/gtmfyxyfne.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtjtiscllr.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gtzhkhzvit.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daria6918.cn/Article/details/gtnooefnwx.html

[N03] 快速排序（分治示例）
来源：http://dali.dianchejie.cn/Article/details/gthcflnhyj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhoulong.xyz/Article/details/gtmtgyztoh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yanxiufei.cn/Article/details/gtkzmvajxq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gtfzlsttqq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gtnxnjzfff.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cashguo.top/Article/details/gtpmrqbdih.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ydzc1.top/Article/details/gtjdbuxpkq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.svipenyu.cn/Article/details/gtgvigaacq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yueranfly.top/Article/details/gtsqlqneto.html

[N04] 斐波那契数列
来源：http://dali.yangfankeji.com/Article/details/gtlaggsioz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtempktgiv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gtwtgsqwkn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gtldpugvbb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gthvyixxsf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.guannengcc.top/Article/details/gtcdylveay.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenlongwang.top/Article/details/gtfdijqhqg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gtbkpjbqkq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gthjeoukew.html

[N05] 最大公约数
来源：http://dali.cqqwz.cn/Article/details/gtcaqugrvs.html

Py:   math.gcd(a, b)
来源：http://dali.birdmap.top/Article/details/gtcenzzvgc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenzaomai.com/Article/details/gtyvmsgmed.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gtqogzkvub.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtpgxhpytp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tanke756.top/Article/details/gtqjynrwcf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.kuanghao11.cn/Article/details/gtyizojkpq.html

Ruby: a.gcd(b)
来源：http://dali.cheryme.top/Article/details/gtxanmmvbe.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.svipenyu.cn/Article/details/gtaypdekpq.html

[N06] 判断回文字符串
来源：http://dali.jiagoushi.top/Article/details/gtskpvfmeb.html

Py:   s == s[::-1]
来源：http://dali.pycfn.com/Article/details/gtmsgamcmp.html

PHP:  $s === strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gtkxcqrsxe.html

JS:   s === [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtslrrfbrq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtejrmlgbm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hywenlv.cn/Article/details/gtqzcfnjmo.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gtirqqcutu.html

Ruby: s == s.reverse
来源：http://dali.aizwys.cn/Article/details/gtakzmfkvf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gtaincvkhj.html

[N07] 两数之和（返回下标）
来源：http://dali.chenlongwang.top/Article/details/gtvpsvikns.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhixingplan.top/Article/details/gtsljrtdgl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.smart0.xyz/Article/details/gtxytgwibj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenzaomai.com/Article/details/gtjupueidr.html

TS:   // 手写 Map<string, number>
来源：http://dali.ehwqpu.com/Article/details/gtojhawqnd.html

Java: // 手写 HashMap
来源：http://dali.shangyingyoupin.top/Article/details/gtkaopkfmo.html

Go:   // 手写 map[int]int
来源：http://dali.hysaishi.cn/Article/details/gtnxmgofhy.html

Ruby: // 手写 Hash
来源：http://dali.jyoumei.cn/Article/details/gtljpqxrbk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.kuanghao11.cn/Article/details/gtrpkpkopx.html

[N08] 生成全排列
来源：http://dali.xuanzx.com/Article/details/gtunwytcob.html

Py:   itertools.permutations(arr)
来源：http://dali.yangfankeji.com/Article/details/gtvbultzpv.html

PHP:  // 手写递归交换
来源：http://dali.andypj.xyz/Article/details/gtvjzyatom.html

JS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtbdnenzhr.html

TS:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtrodecyiw.html

Java: // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlviaxpik.html

Go:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtdkjdpfmh.html

Ruby: arr.permutation.to_a
来源：http://dali.zycfv.cn/Article/details/gttamxvegn.html

C#:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtgfhnuvjc.html

[N09] 栈与队列
来源：http://dali.hnqzz.top/Article/details/gtdzlgnfoc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gogol.net.cn/Article/details/gtcijfyqkt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sweek.top/Article/details/gtltyojfzs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtzcdehhvh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ybcxt.top/Article/details/gtdattseom.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ehwqpu.com/Article/details/gtdiwgpxkn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aizwys.cn/Article/details/gtgvosdxwx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlswnvcsw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gtvmkbmevb.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gtllayjbwq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ivvv.top/Article/details/gtwlgonybo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cdnleiting.top/Article/details/gtpbxcltyr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangshuangyany.cn/Article/details/gturncnghb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhengqikj.top/Article/details/gtmxkexhmj.html

Java: class Node { int v; Node next; }
来源：http://dali.ybcxt.top/Article/details/gtvvcyndvq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.redwolf501.top/Article/details/gtpgbquycq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.haohaochexian.top/Article/details/gtdqrqendi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.c1oappe.top/Article/details/gtjlxlabtx.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigufen.top/Article/details/gtacktbnfq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dianchejie.cn/Article/details/gtuykguikt.html

PHP:  // 手写递归函数
来源：http://dali.andypj.xyz/Article/details/gtraxwrnyi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gtsnvhubhy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjeaoqrx.html

Java: // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtlhqfucbq.html

Go:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtvenzgijc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.havefunace.top/Article/details/gtbqfavbtt.html

C#:   // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gtexcderbn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gttiwpmayc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinghuilouyu.cn/Article/details/gttfusipyh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hnqzz.top/Article/details/gtwmowntnk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gtswmccbph.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sysykeji.top/Article/details/gtepqlxdid.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gtwqalatgv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgvjxfcc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yonumen.top/Article/details/gtxtdtnisy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gtdpffeuhi.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtypbmbalq.html

O. 并发与异步
来源：http://dali.ybcxt.top/Article/details/gtewdprhff.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtsrkuzzcg.html

[O01] 启动一个线程
来源：http://dali.zhiwuduotai.top/Article/details/gtqtgqzegs.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xuanzx.com/Article/details/gtrgebukls.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenzaomai.com/Article/details/gtnzgmublw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.aibaodan.cn/Article/details/gtqukqnsad.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbvekrdq.html

Java: new Thread(() -> f()).start()
来源：http://dali.haohaochexian.top/Article/details/gttuwjafmg.html

Go:   go f()
来源：http://dali.ehwqpu.com/Article/details/gtxjaeupxt.html

Ruby: Thread.new { f }
来源：http://dali.haohaochexian.top/Article/details/gtskdvsibs.html

C#:   Task.Run(() => F());
来源：http://dali.fengsongda.top/Article/details/gtscfvzglk.html

[O02] 使用线程池
来源：http://dali.nwbrower.top/Article/details/gtowglruyi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hysaishi.cn/Article/details/gtvzemtctn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258.top/Article/details/gttsscxfti.html

JS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gtimwodgej.html

TS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gtumasmlkj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sysykeji.top/Article/details/gtklthddso.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jiagoushi.top/Article/details/gtfcueabee.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258888.top/Article/details/gtsauakfdo.html


<!-- 参考信息 -->