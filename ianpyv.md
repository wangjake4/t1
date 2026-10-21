代发 wailian999

[K06] 解析 URL 查询串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthmjwmnm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gtnpqohnio.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yanxiufei.cn/Article/details/gttpiwuwzi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gtfwitnwuj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gtteoqsyvo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gtttybgnbf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gtmpadtymr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtspbqtqxy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gthtpzvmex.html

[K07] 进制转换
来源：http://dali.vqdsnc.cn/Article/details/gtkvjdswsc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtbvyhgsis.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gotoacloud.top/Article/details/gtjrxoesss.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtqkfzqmiq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtwkqulegv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtrlobsips.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dianchejie.cn/Article/details/gtuzlkizhz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jlsjyb.cn/Article/details/gtfqqcmcuq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtubktiyws.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hysaishi.cn/Article/details/gtxjoekluk.html

Py:   pickle.dumps(obj)
来源：http://dali.sxryk.cn/Article/details/gttbtrnwrb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.iojbl.cn/Article/details/gtmzoecehc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gtylplzhjg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gtopjwysng.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hywenlv.cn/Article/details/gtjvhrcckt.html

Go:   encoding/gob
来源：http://dali.svipenyu.cn/Article/details/gtvmjqedsy.html

Ruby: Marshal.dump(obj)
来源：http://dali.cheryme.top/Article/details/gtxhzdaqkb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cheryme.top/Article/details/gtjtkifuln.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtdcieasve.html

L. 网络请求
来源：http://dali.9152youxi.cn/Article/details/gtemoszwxg.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtxkumbgjt.html

[L01] 发送 GET 请求
来源：http://dali.yvedp.cn/Article/details/gtumebrtsi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ywan-chungtsiang.top/Article/details/gthuuqdtvn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sysykeji.top/Article/details/gtpeihhnij.html

JS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gtxwjdxmny.html

TS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gthcownkah.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenjidiqi.icu/Article/details/gtzindguuy.html

Go:   resp, err := http.Get(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtzmovkdsk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ppjwa.cn/Article/details/gtjdyrborp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yuxming.cn/Article/details/gtbkcleykv.html

[L02] 发送 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gthisvvenv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.snrcjt.cn/Article/details/gtionvquym.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.guannengcc.top/Article/details/gtuipcnytj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gtvufxcwbw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shuidangran.top/Article/details/gtrdefmarv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daria6918.cn/Article/details/gtjwezfuot.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj202588.top/Article/details/gtxkobychs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.snrcjt.cn/Article/details/gtdcjpxjmu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sweek.top/Article/details/gtnyolqtay.html

[L03] 设置自定义请求头
来源：http://dali.dianchejie.cn/Article/details/gtrkvemlqk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cheryme.top/Article/details/gtlxsncuco.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.snrcjt.cn/Article/details/gtbwoizzkh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtiatzybuw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gttbyoccfc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuxming.cn/Article/details/gtiqqiejck.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gtlpyofmfy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.mhx1999.top/Article/details/gtlbmklyph.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gtdvvlxryi.html

[L04] 设置超时
来源：http://dali.cashguo.top/Article/details/gtlwsfcdtb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuppewpwa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenlongwang.top/Article/details/gtzraiaqfb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gthyalzboc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gtuntbemgg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.iojbl.cn/Article/details/gtksbborsl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.iojbl.cn/Article/details/gtyznonjju.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zdqjudy.top/Article/details/gtqmkcssxq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnxiangtu.top/Article/details/gtypsnjvsb.html

[L05] 上传文件（multipart）
来源：http://dali.sufxvd.cn/Article/details/gtqwosfqvq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.vqdsnc.cn/Article/details/gtsjmnwuyt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pycfn.com/Article/details/gtswnghquq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gtbdtmzacw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gtqrunpazw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvpnhekt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cdnleiting.top/Article/details/gtemegrlhi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.havefunace.top/Article/details/gtzcaabzoo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gthkxqksev.html

[L06] 解析响应为 JSON
来源：http://dali.aizwys.cn/Article/details/gtowglxaix.html

Py:   resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gtdvcsgqrs.html

PHP:  json_decode($body, true);
来源：http://dali.xziqi.cn/Article/details/gtsdcwjhaa.html

JS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gtuwyvbpxm.html

TS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtribrldsb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtfprogcmc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.iojbl.cn/Article/details/gtmflmkzaa.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpffeabrm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yueranfly.top/Article/details/gtlvbsokhk.html

[L07] 处理 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gtohxfilng.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.mhx1999.top/Article/details/gtcvzgmgya.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.wangdashe.top/Article/details/gtshqiufib.html

JS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gtwygcrqpo.html

TS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gtbovrmabg.html

Java: resp.statusCode()
来源：http://dali.ydzc1.top/Article/details/gtrkpyvevp.html

Go:   resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gtzegduzqo.html

Ruby: resp.code.to_i
来源：http://dali.gogol.net.cn/Article/details/gtuhkrrnrb.html

C#:   (int)resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gtwizuaujx.html

[L08] 并发请求多个地址
来源：http://dali.jqgfzy.top/Article/details/gtcjgketge.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.havefunace.top/Article/details/gtqqsedooz.html

PHP:  curl_multi_init() 系列
来源：http://dali.yvedp.cn/Article/details/gtndogjqes.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtpkwcsuwt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtiwldkxxa.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cqqwz.cn/Article/details/gtnhemcdeh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangshuangyany.cn/Article/details/gtikqkvfyq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sufxvd.cn/Article/details/gtmlyldumr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihipmtpf.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtqwmihjon.html

M. 命令行 / 进程 / 环境
来源：http://dali.jiagoushi.top/Article/details/gtwkpyaqdv.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gttbbklwfr.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtksbrjrpr.html

Py:   sys.argv[1:]
来源：http://dali.jiagoushi.top/Article/details/gtqllpylzq.html

PHP:  $argv;  $argc;
来源：http://dali.feifeiyinyue.top/Article/details/gtjcysepuc.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gtyzffnetw.html

TS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gtowawpkeu.html

Java: args 数组（main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gtwbzhvkmr.html

Go:   os.Args[1:]
来源：http://dali.zdqjudy.top/Article/details/gtzupysykq.html

Ruby: ARGV
来源：http://dali.cucudq.cn/Article/details/gthtyejljg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258.top/Article/details/gthudefqli.html

[M02] 读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gtmsacrmhh.html

Py:   os.environ.get("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtcdeblipf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gtxcwnxqax.html

JS:   process.env.HOME
来源：http://dali.nwbrower.top/Article/details/gttvauymvb.html

TS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gtudpzvpao.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtqaxgnwmi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daria6918.cn/Article/details/gtvnhwdkai.html

Ruby: ENV["HOME"]
来源：http://dali.xinyue.icu/Article/details/gthmuvhbcp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xylfe.cn/Article/details/gtxcyzenri.html

[M03] 执行外部命令
来源：http://dali.xuanzx.com/Article/details/gtzpjlkalk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.svipenyu.cn/Article/details/gtxwsiqbwt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.316326.xyz/Article/details/gtmaxlshht.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gtgydvykam.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjzkqhwp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnxiangtu.top/Article/details/gtqcywsvpd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.kuanghao11.cn/Article/details/gtfitipxkk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.redwolf501.top/Article/details/gtbuanklrr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xuanzx.com/Article/details/gtuyrjauzh.html

[M04] 获取当前工作目录
来源：http://dali.ybcxt.top/Article/details/gtlrfmwssz.html

Py:   os.getcwd()
来源：http://dali.xylfe.cn/Article/details/gtjirtcfan.html

PHP:  getcwd();
来源：http://dali.yvedp.cn/Article/details/gtkvljxyad.html

JS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwbppwzk.html

TS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtngpeyrmw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigufen.top/Article/details/gtbybowqhh.html

Go:   os.Getwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqohvfbjv.html

Ruby: Dir.pwd
来源：http://dali.zycfv.cn/Article/details/gtjgempfeq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnxiangtu.top/Article/details/gttuyjmjwf.html

[M05] 设置退出码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzmcacrz.html

Py:   sys.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtxsrhbbel.html

PHP:  exit(1);
来源：http://dali.xinyue.icu/Article/details/gtiyydbwcx.html

JS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtlgqdirub.html

TS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gteqocuoej.html

Java: System.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtlnnlaboi.html

Go:   os.Exit(1)
来源：http://dali.gzhubu.top/Article/details/gtjyltylbd.html

Ruby: exit 1
来源：http://dali.guannengcc.top/Article/details/gtoyjbhwmp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenjidiqi.icu/Article/details/gtccgzbwel.html

[M06] 向标准错误输出
来源：http://dali.ivvv.top/Article/details/gtguekzgim.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgfzy.top/Article/details/gtpkejiaop.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.svipenyu.cn/Article/details/gtlnfubwjo.html

JS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gthphkvtru.html

TS:   console.error("err")
来源：http://dali.haohaochexian.top/Article/details/gtrbrzhieb.html

Java: System.err.println("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtmlpywhcx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yangfankeji.com/Article/details/gtbxztiacg.html

Ruby: warn "err"
来源：http://dali.mhx1999.top/Article/details/gtblwzitct.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xinyue.icu/Article/details/gtbqoombqy.html

[M07] 判断是否为主入口
来源：http://dali.yj20258.top/Article/details/gtuulckmik.html

Py:   if __name__ == "__main__":
来源：http://dali.cdnleiting.top/Article/details/gthhhazurc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.meibo888.top/Article/details/gtdunuxgkf.html

JS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkmkzbvp.html

TS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gtrfasqkmq.html

Java: public static void main(String[] args)
来源：http://dali.tanke756.top/Article/details/gtyhwabqpl.html

Go:   func main()
来源：http://dali.316326.xyz/Article/details/gtbomqiwgj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tian-w.cn/Article/details/gtrvitcssq.html

C#:   static void Main(string[] args)
来源：http://dali.316326.xyz/Article/details/gtisiwcayc.html

[M08] 获取系统与运行时信息
来源：http://dali.zhoulong.xyz/Article/details/gtczcgdngq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258.top/Article/details/gtmqdiuyby.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cheryme.top/Article/details/gttvxixdwa.html

JS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gtmjxilynh.html

TS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gtmfkdiyfr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangshuangyany.cn/Article/details/gtwpyeqriq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tanke756.top/Article/details/gtpaenepvt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yangfankeji.com/Article/details/gtloqqjexp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.pycfn.com/Article/details/gtoaxuclbw.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtlszmnyxg.html

N. 数据结构与算法
来源：http://dali.gzhubu.top/Article/details/gtiowrpexg.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gthqputsfj.html

[N01] 二分查找（有序数组）
来源：http://dali.cashguo.top/Article/details/gtsqjpfhqe.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtowlchcap.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtyysocgmo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gtylfrfenm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtcvuxfnqf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtmbngxyom.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtmglavvfv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fengsongda.top/Article/details/gtftvxndsi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jianghu66.top/Article/details/gttpskwxom.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cashguo.top/Article/details/gtprhdexlb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yonumen.top/Article/details/gtxlzvfiry.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenlongwang.top/Article/details/gtcuhuggqv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gtblcggsui.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gtnocowkxb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pycfn.com/Article/details/gtjuxgqbhm.html

Go:   slices.Sort(arr)
来源：http://dali.jqgfzy.top/Article/details/gtxkobhmww.html

Ruby: arr.sort
来源：http://dali.xuetiantiany.cn/Article/details/gtaijpbgmb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangdashe.top/Article/details/gtpuubtrbf.html

[N03] 快速排序（分治示例）
来源：http://dali.wangshuangyany.cn/Article/details/gtypoevenp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gtiaxmztgg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sufxvd.cn/Article/details/gtmzwdczql.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gtcqbexwyi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gtqmfechmk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ehwqpu.com/Article/details/gtmgyxpqqt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuanzhike.top/Article/details/gthzkiwbsq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yongpay.top/Article/details/gtsiogsxlh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenjidiqi.icu/Article/details/gtvlanlkym.html

[N04] 斐波那契数列
来源：http://dali.yuxming.cn/Article/details/gtrrfbpjmz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gtwmitcjow.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258.top/Article/details/gtinacjoak.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtddtkbjrb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtkggluahh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gttujhutye.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.mhx1999.top/Article/details/gtrqpwpzxd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtyqymliap.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtvpjnhvun.html

[N05] 最大公约数
来源：http://dali.yuxming.cn/Article/details/gtlymcmigu.html

Py:   math.gcd(a, b)
来源：http://dali.pycfn.com/Article/details/gtcneanrvb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tian-w.cn/Article/details/gtkfmkwkou.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gtimtyxeqd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gtzxrcdmrm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xinyue.icu/Article/details/gtjjongzem.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.havefunace.top/Article/details/gtegoyeymb.html

Ruby: a.gcd(b)
来源：http://dali.hysaishi.cn/Article/details/gtcyfyejtu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.redwolf501.top/Article/details/gtztawhcyd.html

[N06] 判断回文字符串
来源：http://dali.c1oappe.top/Article/details/gtubnwgpti.html

Py:   s == s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gtojgmhsmk.html

PHP:  $s === strrev($s);
来源：http://dali.birdmap.top/Article/details/gtpmsbakde.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtrkiflnwb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gteyfvrfll.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gaohongyu789.top/Article/details/gtsutnnmva.html

Go:   // 双指针从两端比较
来源：http://dali.pycfn.com/Article/details/gtyiqtovir.html

Ruby: s == s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtvdsrtjyg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gtazkfeonr.html

[N07] 两数之和（返回下标）
来源：http://dali.yvedp.cn/Article/details/gtofqxkeij.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sufxvd.cn/Article/details/gtvqmqpomo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gtpnrzmypw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sweek.top/Article/details/gtvwkqrfzi.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangtech.top/Article/details/gtinkebame.html

Java: // 手写 HashMap
来源：http://dali.gzhubu.top/Article/details/gtlmlavhbg.html

Go:   // 手写 map[int]int
来源：http://dali.xuanzx.com/Article/details/gtelfzsxnp.html

Ruby: // 手写 Hash
来源：http://dali.tanke756.top/Article/details/gtudlmpboa.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daxiang520.top/Article/details/gthyfvitzp.html

[N08] 生成全排列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxywmukrn.html

Py:   itertools.permutations(arr)
来源：http://dali.fengsongda.top/Article/details/gttitthtxv.html

PHP:  // 手写递归交换
来源：http://dali.ppjwa.cn/Article/details/gtqwbqwjqp.html

JS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtfpvujcuf.html

TS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtkgvozehe.html

Java: // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtqfvezyda.html

Go:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtqrdzdfns.html

Ruby: arr.permutation.to_a
来源：http://dali.redwolf501.top/Article/details/gtbujamcud.html

C#:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtaomksvwx.html

[N09] 栈与队列
来源：http://dali.fzhhl.top/Article/details/gtdbtrwcqd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtwzuuraiy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xylfe.cn/Article/details/gtiasjhhco.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gtzvdyylqo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fengsongda.top/Article/details/gtppxfwqkf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuxming.cn/Article/details/gtpysxyjkh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xuetiantiany.cn/Article/details/gtfyaelpem.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gtxbbwjopk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tianlin.xyz/Article/details/gtsbaypqse.html

[N10] 链表节点定义
来源：http://dali.andypj.xyz/Article/details/gtqlculeuj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.0kj1m.cn/Article/details/gtfghqijzy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sysykeji.top/Article/details/gtnnmrjpwe.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jyoumei.cn/Article/details/gtgkekmhdh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cqqwz.cn/Article/details/gtjjilmvlw.html

Java: class Node { int v; Node next; }
来源：http://dali.daxiang520.top/Article/details/gtkkkpyajg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.meibo888.top/Article/details/gtzvcxsutb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhyldfwb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhongyouzk.top/Article/details/gtsbmrmrwa.html

[N11] 二叉树中序遍历
来源：http://dali.snrcjt.cn/Article/details/gtgkbgrabb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yanxiufei.cn/Article/details/gtdbsvsiju.html

PHP:  // 手写递归函数
来源：http://dali.hongshengwenyu.top/Article/details/gtggwslwzz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gtdxtcwkst.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yangfankeji.com/Article/details/gtrzaihxjh.html

Java: // 手写递归
来源：http://dali.birdmap.top/Article/details/gtdcfsmzdw.html

Go:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiodqzxyv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yvedp.cn/Article/details/gtktvxgzcw.html

C#:   // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gttkipyspg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnxiangtu.top/Article/details/gtgcormbpg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gogol.net.cn/Article/details/gtljgzoakv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cheryme.top/Article/details/gtwvbqbdrt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gtmnafrodw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gtuidjdiza.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gtfeglujvi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guannengcc.top/Article/details/gtiukidojb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtihreoljj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxuanxn.top/Article/details/gtypbrpiuv.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtobtgqpxl.html

O. 并发与异步
来源：http://dali.shuidangran.top/Article/details/gteyjpdsnq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtaydjyngc.html

[O01] 启动一个线程
来源：http://dali.xuanzx.com/Article/details/gtguyklmal.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxinkj.top/Article/details/gtijoadckl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.quarkkingdee.top/Article/details/gtqjgmvuhe.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuanzhike.top/Article/details/gtotyavkfw.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gtsqquhvcw.html

Java: new Thread(() -> f()).start()
来源：http://dali.c1oappe.top/Article/details/gtutispith.html

Go:   go f()
来源：http://dali.gaohongyu789.top/Article/details/gtemktshcm.html

Ruby: Thread.new { f }
来源：http://dali.yuanzhike.top/Article/details/gtokybjqao.html

C#:   Task.Run(() => F());
来源：http://dali.yanxiufei.cn/Article/details/gtflbbzdzo.html


<!-- 参考信息 -->