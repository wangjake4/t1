代发 wailian999

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nwbrower.top/Article/details/gtptlvphme.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nwbrower.top/Article/details/gtrfavabpo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aizwys.cn/Article/details/gtsmzrznam.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shuidangran.top/Article/details/gtlzryfmiq.html

[K06] 解析 URL 查询串
来源：http://dali.shzxlz.cn/Article/details/gtwfsuovth.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hammf.cn/Article/details/gtdbkranbi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.c1oappe.top/Article/details/gtrwadkrgb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gtididtrrw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gtqtnlrtqb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ivvv.top/Article/details/gtzymcgyar.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtixmljynm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelpajrhm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtkccbfcgo.html

[K07] 进制转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohtxjobg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtpcmpusnc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tian-w.cn/Article/details/gthzkqagwu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtanpvrjkz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtcbpzwvgo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtxwzdjxfp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.316326.xyz/Article/details/gtrudksnfy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shangyingyoupin.top/Article/details/gtgaguznxk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtqatvejpm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daxiang520.top/Article/details/gtuxljurga.html

Py:   pickle.dumps(obj)
来源：http://dali.tianlin.xyz/Article/details/gtvsyavtco.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj202588.top/Article/details/gtpomjhwjo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gtigekzved.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtlgqnphnl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cucudq.cn/Article/details/gtxmipdhfe.html

Go:   encoding/gob
来源：http://dali.hysaishi.cn/Article/details/gtffstmavt.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvpwyioab.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gtxagtubkl.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gttncjuifs.html

L. 网络请求
来源：http://dali.zhixingplan.top/Article/details/gtxxikwrje.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtaiiieqxt.html

[L01] 发送 GET 请求
来源：http://dali.hammf.cn/Article/details/gtxsssonsj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shangyingyoupin.top/Article/details/gtxkyvznym.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.316326.xyz/Article/details/gtkxlotlre.html

JS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gtelpmjysk.html

TS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gtdkwsatpl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hfpthk.cn/Article/details/gtigzupxbc.html

Go:   resp, err := http.Get(url)
来源：http://dali.birdmap.top/Article/details/gtslflespu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigfzy.top/Article/details/gtuwxfzpmp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.kuanghao11.cn/Article/details/gtejaeowoc.html

[L02] 发送 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gtnfkypxsu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daxiang520.top/Article/details/gtyzzromee.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuxming.cn/Article/details/gtgqprdrbw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gtijvzcceu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gtjbirhtwb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.mhx1999.top/Article/details/gtqgduqffy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.smart0.xyz/Article/details/gtzpjqnnmc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.kuanghao11.cn/Article/details/gtlgyopoub.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtriukktrl.html

[L03] 设置自定义请求头
来源：http://dali.cheryme.top/Article/details/gtwiqzmgyw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj202588.top/Article/details/gtqqaxohsh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.mhx1999.top/Article/details/gtogurtmoa.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gtctplcwpl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ehwqpu.com/Article/details/gtevmentei.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shangyingyoupin.top/Article/details/gtqthygeva.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gtnsljvlsi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.iojbl.cn/Article/details/gtdmdxwjnf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtqfpvjbmz.html

[L04] 设置超时
来源：http://dali.0kj1m.cn/Article/details/gtlbcaidyk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yvedp.cn/Article/details/gtueejcpns.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.meibo888.top/Article/details/gtrzsnovqr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gtqezraxlr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gtawruiqjm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hfpthk.cn/Article/details/gtqcyqwrgn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhongyouzk.top/Article/details/gtmbbfrkch.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxylntuq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.kuanghao11.cn/Article/details/gtbesbdhoo.html

[L05] 上传文件（multipart）
来源：http://dali.jlsjyb.cn/Article/details/gtnmgpdmxt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.bjfxy.top/Article/details/gtlmkvfjhg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.kuanghao11.cn/Article/details/gtieopgqqn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gtcohtvwjs.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gtvvybaimu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhengqikj.top/Article/details/gtpfpgitqg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yonumen.top/Article/details/gtrqnztyrb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xziqi.cn/Article/details/gtwrnehfcv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aizwys.cn/Article/details/gtisznidny.html

[L06] 解析响应为 JSON
来源：http://dali.bjfxy.top/Article/details/gtucqbyjsw.html

Py:   resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtgbggilsd.html

PHP:  json_decode($body, true);
来源：http://dali.zhongyouzk.top/Article/details/gtqgibmpbo.html

JS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtbyzoujaj.html

TS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gtgbbetdro.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtaynabwwj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.feifeiyinyue.top/Article/details/gtlbyqxrep.html

Ruby: JSON.parse(resp.body)
来源：http://dali.andypj.xyz/Article/details/gtvodwbfcq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jyoumei.cn/Article/details/gtjcntcavc.html

[L07] 处理 HTTP 状态码
来源：http://dali.ydzc1.top/Article/details/gtonmwoogp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhixingplan.top/Article/details/gtsxujjrae.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yvedp.cn/Article/details/gtfjrtdevp.html

JS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gthcyvwahx.html

TS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gtntxydkzy.html

Java: resp.statusCode()
来源：http://dali.xinyue.icu/Article/details/gtdmyluzrh.html

Go:   resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gtiagryrpv.html

Ruby: resp.code.to_i
来源：http://dali.zhixingplan.top/Article/details/gtauetxgfj.html

C#:   (int)resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gtedifwwdr.html

[L08] 并发请求多个地址
来源：http://dali.aibaodan.cn/Article/details/gtpjvzmfvl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hongshengwenyu.top/Article/details/gtglgfyjub.html

PHP:  curl_multi_init() 系列
来源：http://dali.dianchejie.cn/Article/details/gthmzheogn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gtfajlilaa.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtbfdmzsgr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sufxvd.cn/Article/details/gtpsitjlrz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zdqjudy.top/Article/details/gtcfawfkli.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj202588.top/Article/details/gtxzuqdqga.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zycfv.cn/Article/details/gtosrrsdts.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtntcbgplq.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj20258.top/Article/details/gtdpdnauhc.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtpidmdvpe.html

[M01] 读取命令行参数
来源：http://dali.daria6918.cn/Article/details/gtuqjgoeof.html

Py:   sys.argv[1:]
来源：http://dali.shzxlz.cn/Article/details/gtwkhfqjme.html

PHP:  $argv;  $argc;
来源：http://dali.vqdsnc.cn/Article/details/gtebsndeaq.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtlzwqluca.html

TS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gtxyuwnjla.html

Java: args 数组（main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gteelsfdwu.html

Go:   os.Args[1:]
来源：http://dali.tanke756.top/Article/details/gthrqlgalv.html

Ruby: ARGV
来源：http://dali.fengsongda.top/Article/details/gthentaowt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gtfqopewaz.html

[M02] 读取环境变量
来源：http://dali.zhoulong.xyz/Article/details/gtqcxmhisc.html

Py:   os.environ.get("HOME")
来源：http://dali.zycfv.cn/Article/details/gtlorkeagq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqulgkwm.html

JS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gtfokzovaz.html

TS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gtzyxfohpn.html

Java: System.getenv("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfaxohaqi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtkwfdfvdl.html

Ruby: ENV["HOME"]
来源：http://dali.jqgufenzy.top/Article/details/gthgzebjbf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gthjlsiern.html

[M03] 执行外部命令
来源：http://dali.hywenlv.cn/Article/details/gtrzvzhtib.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxuanxn.top/Article/details/gtvpwqqnzh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhoulong.xyz/Article/details/gtnzoivaip.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gtaifvoaco.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gteelhojpn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hongshengwenyu.top/Article/details/gtwoxemqfd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.guowangkeji.top/Article/details/gtlgzzkdxx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aibaodan.cn/Article/details/gtcyfmncqg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xinyue.icu/Article/details/gtzmkerjek.html

[M04] 获取当前工作目录
来源：http://dali.xylfe.cn/Article/details/gtamgvteme.html

Py:   os.getcwd()
来源：http://dali.jinqigufen.top/Article/details/gtceqrznky.html

PHP:  getcwd();
来源：http://dali.andypj.xyz/Article/details/gthfpoqoxx.html

JS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gttxmtspjf.html

TS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gtfzgyaunn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sysykeji.top/Article/details/gtykpnsfvi.html

Go:   os.Getwd()
来源：http://dali.hysaishi.cn/Article/details/gtitdveqxo.html

Ruby: Dir.pwd
来源：http://dali.cheryme.top/Article/details/gtvhlhctml.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjdtawzy.html

[M05] 设置退出码
来源：http://dali.vqdsnc.cn/Article/details/gtleqcyqlz.html

Py:   sys.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtvyysrrtp.html

PHP:  exit(1);
来源：http://dali.yangfankeji.com/Article/details/gtiyphqsvp.html

JS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtzgyvmpas.html

TS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gttywvneje.html

Java: System.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtogqxhgry.html

Go:   os.Exit(1)
来源：http://dali.ydzc1.top/Article/details/gthxxyjkqd.html

Ruby: exit 1
来源：http://dali.zhongyouzk.top/Article/details/gtzapvkyaf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yanxiufei.cn/Article/details/gtbkipqwdw.html

[M06] 向标准错误输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldcwafos.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangtech.top/Article/details/gttbclrnuh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guannengcc.top/Article/details/gtueapnqrq.html

JS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gtigspdwbh.html

TS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gtqohbbhlt.html

Java: System.err.println("err")
来源：http://dali.yj20258888.top/Article/details/gtxselavdh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sysykeji.top/Article/details/gterykvqab.html

Ruby: warn "err"
来源：http://dali.andypj.xyz/Article/details/gtvzlczxlp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gotoacloud.top/Article/details/gtevdtswsb.html

[M07] 判断是否为主入口
来源：http://dali.gotoacloud.top/Article/details/gtngysjkuv.html

Py:   if __name__ == "__main__":
来源：http://dali.ppjwa.cn/Article/details/gtggecfcls.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuetiantiany.cn/Article/details/gtgcdhxtgw.html

JS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gtgaolxqpg.html

TS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtorxhpnsi.html

Java: public static void main(String[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbejlwkmv.html

Go:   func main()
来源：http://dali.guowangkeji.top/Article/details/gtzkefjfdo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yanxiufei.cn/Article/details/gtsscqxpuj.html

C#:   static void Main(string[] args)
来源：http://dali.hfpthk.cn/Article/details/gtiqehtgke.html

[M08] 获取系统与运行时信息
来源：http://dali.kuanghao11.cn/Article/details/gtbgwqcogz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.aizwys.cn/Article/details/gtpaukylmk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.feifeiyinyue.top/Article/details/gtwbqfsgdm.html

JS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtssmrbrxr.html

TS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtmrnkijgc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yueranfly.top/Article/details/gtpcnaldyo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sysykeji.top/Article/details/gtvogoagdd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hongshengwenyu.top/Article/details/gtjcaevsxn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cdnleiting.top/Article/details/gtfxwoeftd.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtwjpstgci.html

N. 数据结构与算法
来源：http://dali.jqgufenzy.top/Article/details/gttczmfbnc.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtunmstpxw.html

[N01] 二分查找（有序数组）
来源：http://dali.guannengcc.top/Article/details/gtjlcaxbjy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtmnwhyllb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ivvv.top/Article/details/gtghrhvcnk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtkwlvvccp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtosocdsur.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gttdycjcxa.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtafgbewee.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrrupdgwu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtvwcoxivf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ehwqpu.com/Article/details/gtunwadwyg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfbjaoqm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.vqdsnc.cn/Article/details/gtvxgarxuu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gtambvkoee.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gttmzxucls.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhengqikj.top/Article/details/gtvaksszhy.html

Go:   slices.Sort(arr)
来源：http://dali.jqgufenzy.top/Article/details/gthrrswysj.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gtbxiffzmr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.andypj.xyz/Article/details/gtldetvnyq.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxinkj.top/Article/details/gtyjhadygm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.svipenyu.cn/Article/details/gthunbeysl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yonumen.top/Article/details/gtucltucmf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gtnatocybk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gteqyjuppt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fengsongda.top/Article/details/gtivtxynit.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.bjfxy.top/Article/details/gtwgwbbhfw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hywenlv.cn/Article/details/gtxxicwoje.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.birdmap.top/Article/details/gtilpxjdly.html

[N04] 斐波那契数列
来源：http://dali.cashguo.top/Article/details/gttfuajzpp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gthafhiyyo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.wangdashe.top/Article/details/gtktrwtvys.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gtgnxhhyov.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gtxmmcldgd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sweek.top/Article/details/gtvvslurmp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daxiang520.top/Article/details/gttxqzqzni.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gttxwrxwqy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtegoyhduh.html

[N05] 最大公约数
来源：http://dali.xylfe.cn/Article/details/gtpbwlqluy.html

Py:   math.gcd(a, b)
来源：http://dali.yuxming.cn/Article/details/gtvuxulnzx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sysykeji.top/Article/details/gtryqkvfgd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.c1oappe.top/Article/details/gtkfrdczma.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gtfcdjhrwb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258888.top/Article/details/gtylrbsqcf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dianchejie.cn/Article/details/gtggppzjwu.html

Ruby: a.gcd(b)
来源：http://dali.ehwqpu.com/Article/details/gtqnkxsggi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hongshengwenyu.top/Article/details/gtemljjorm.html

[N06] 判断回文字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswoncgww.html

Py:   s == s[::-1]
来源：http://dali.gogol.net.cn/Article/details/gtqlojhxhu.html

PHP:  $s === strrev($s);
来源：http://dali.hnqzz.top/Article/details/gtzgphigff.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtglqijtmy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtquvxxoyf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnevrenn.html

Go:   // 双指针从两端比较
来源：http://dali.vqdsnc.cn/Article/details/gtjxolconj.html

Ruby: s == s.reverse
来源：http://dali.yuanzhike.top/Article/details/gtzvqzrlwe.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gtqpyezwvd.html

[N07] 两数之和（返回下标）
来源：http://dali.pycfn.com/Article/details/gtznrvdrie.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sufxvd.cn/Article/details/gtfecsbdpk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.haohaochexian.top/Article/details/gtshluoziu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jiagoushi.top/Article/details/gtvpvmloab.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtryryxipv.html

Java: // 手写 HashMap
来源：http://dali.hywenlv.cn/Article/details/gtdmtnfahy.html

Go:   // 手写 map[int]int
来源：http://dali.shangyingyoupin.top/Article/details/gtmghlrjbp.html

Ruby: // 手写 Hash
来源：http://dali.gogol.net.cn/Article/details/gtttjdtkji.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.c1oappe.top/Article/details/gtpguqfdre.html

[N08] 生成全排列
来源：http://dali.0kj1m.cn/Article/details/gttcvyfkln.html

Py:   itertools.permutations(arr)
来源：http://dali.chenlongwang.top/Article/details/gtpruhyznc.html

PHP:  // 手写递归交换
来源：http://dali.bjfxy.top/Article/details/gtuypeyipn.html

JS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtgbgcbszj.html

TS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtfwrinymo.html

Java: // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtflgkiqoq.html

Go:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtbjnjmedo.html

Ruby: arr.permutation.to_a
来源：http://dali.zdqjudy.top/Article/details/gtxcrhquzx.html

C#:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtwputcyuu.html

[N09] 栈与队列
来源：http://dali.svipenyu.cn/Article/details/gthzjjqmyc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.bjfxy.top/Article/details/gtyqopojjv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtajrgmcqw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gtsejbxmtk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ydzc1.top/Article/details/gtqnvielqv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gtmoerydzv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjahjwvx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gtxkzwhqxy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yangfankeji.com/Article/details/gtpzsjpqwg.html

[N10] 链表节点定义
来源：http://dali.jqgfzy.top/Article/details/gtambbdilv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlmtxrdq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.daria6918.cn/Article/details/gtswetogai.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtxjjgjkpr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258.top/Article/details/gtnqaeezfy.html

Java: class Node { int v; Node next; }
来源：http://dali.jyoumei.cn/Article/details/gtdhxqzeeo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hammf.cn/Article/details/gtfijixxow.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shuidangran.top/Article/details/gtiepdbthc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258.top/Article/details/gtviftxgip.html

[N11] 二叉树中序遍历
来源：http://dali.sxryk.cn/Article/details/gtdhchkkdn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenlongwang.top/Article/details/gtzpkxkuln.html

PHP:  // 手写递归函数
来源：http://dali.gzhubu.top/Article/details/gtlahgnwqz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gtlnwkjslr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dashuyun.cn/Article/details/gtbimagzad.html

Java: // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtrlafeaso.html

Go:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtqbxboiau.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgfzy.top/Article/details/gtfhdrypxg.html

C#:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gtgccdplmd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aizwys.cn/Article/details/gtdpejwycp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhiwuduotai.top/Article/details/gtgmrhnsgx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jiagoushi.top/Article/details/gtbalatkyy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gtnbhqocyt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gtohoxfqdp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gtkgbxjpif.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tanke756.top/Article/details/gtjsmjilxp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sysykeji.top/Article/details/gthqdwfctr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gtmljrrglw.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gttfkrxcdp.html

O. 并发与异步
来源：http://dali.hnqzz.top/Article/details/gtbdcgtrpi.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtyaghwsnd.html

[O01] 启动一个线程
来源：http://dali.nanxuanxn.top/Article/details/gtjdnnnyfl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cucudq.cn/Article/details/gtusezowxc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cqqwz.cn/Article/details/gtpyodiyas.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xziqi.cn/Article/details/gttzhsuvnq.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gtxubthifz.html


<!-- 参考信息 -->