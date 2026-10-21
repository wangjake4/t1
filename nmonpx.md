代发 wailian999

[K06] 解析 URL 查询串
来源：http://dali.chenlongwang.top/Article/details/gtjwfzeuzv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.snrcjt.cn/Article/details/gtiwqtierf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.smart0.xyz/Article/details/gtqnjmwnpf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gtbtxchzgs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejnenowr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigufen.top/Article/details/gtcnuodmpl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gtlhqigzjg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtyoqxwfnq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gttoggspgg.html

[K07] 进制转换
来源：http://dali.c1oappe.top/Article/details/gttfnmgpps.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtcibvmnxv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gotoacloud.top/Article/details/gtmehbzmej.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtnpneifwg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtkgfvkvdm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtkezedtgp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hongshengwenyu.top/Article/details/gtbjcthvmg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgihrzut.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtimkvlrlp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.smart0.xyz/Article/details/gtolqybhlu.html

Py:   pickle.dumps(obj)
来源：http://dali.9152youxi.cn/Article/details/gthnyivojp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnqzz.top/Article/details/gtzfcjubjh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gtzdqrafev.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gtydahycog.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guannengcc.top/Article/details/gtrbrmochi.html

Go:   encoding/gob
来源：http://dali.daxiang520.top/Article/details/gtzkrdwkqj.html

Ruby: Marshal.dump(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscjngcvx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gtixifiuei.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtkwmuxpfa.html

L. 网络请求
来源：http://dali.quarkkingdee.top/Article/details/gtfrxmlosc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtzdqbesjm.html

[L01] 发送 GET 请求
来源：http://dali.ydzc1.top/Article/details/gtkzyekbqr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nwbrower.top/Article/details/gtzyvdvrfl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.316326.xyz/Article/details/gtmrggcffx.html

JS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gtcefyzwgh.html

TS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gtgwakemec.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ehwqpu.com/Article/details/gtpkwydjpt.html

Go:   resp, err := http.Get(url)
来源：http://dali.jiagoushi.top/Article/details/gtfglshafa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangdashe.top/Article/details/gtmwkiktgj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pycfn.com/Article/details/gtqzyoedwd.html

[L02] 发送 POST JSON
来源：http://dali.bjfxy.top/Article/details/gtokanfodt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbivmzrf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.meibo888.top/Article/details/gtsriemmww.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gtwoorbwir.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gtbqqanzpz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhengqikj.top/Article/details/gtjpwcedtc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.redwolf501.top/Article/details/gtslesnkmj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hfpthk.cn/Article/details/gtnixyiuxv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shangyingyoupin.top/Article/details/gtktejtgol.html

[L03] 设置自定义请求头
来源：http://dali.0kj1m.cn/Article/details/gtexubdqre.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pengpengdd.cyou/Article/details/gtuszlrdrm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xziqi.cn/Article/details/gtnbhniarg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gtkyxcpbhi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cqqwz.cn/Article/details/gtefjfvtze.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.quarkkingdee.top/Article/details/gtfxxlfvvo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gttytxthtk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenzaomai.com/Article/details/gtwdnhoywz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gtpdfiwmms.html

[L04] 设置超时
来源：http://dali.nanxinkj.top/Article/details/gtalfgczmm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenjidiqi.icu/Article/details/gtsfymqmqw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fengsongda.top/Article/details/gtihaqmzhy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gtduasodcb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gtbomujwum.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gtalcbzptd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.meibo888.top/Article/details/gtkabtrtpt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj202588.top/Article/details/gtnzxcitug.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlwizjkc.html

[L05] 上传文件（multipart）
来源：http://dali.tian-w.cn/Article/details/gtfhttxcmk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgufenzy.top/Article/details/gtoxslgthu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.havefunace.top/Article/details/gtoongqirc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gttptroejy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gtyskoaxte.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zycfv.cn/Article/details/gtxxbzngtq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.feifeiyinyue.top/Article/details/gthymztmbm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gogol.net.cn/Article/details/gtmdusdftu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sxryk.cn/Article/details/gtpbsoqqgb.html

[L06] 解析响应为 JSON
来源：http://dali.zycfv.cn/Article/details/gtrifjjgpt.html

Py:   resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtyxrrwlct.html

PHP:  json_decode($body, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtqprujrje.html

JS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gtpljrsoyp.html

TS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gtzrqdeald.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gttrobrpbz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgfzy.top/Article/details/gtvpredrdh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cqqwz.cn/Article/details/gtmswocend.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yongpay.top/Article/details/gtlkefarcj.html

[L07] 处理 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gtxtpzyhay.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylvbrxbr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yanxiufei.cn/Article/details/gtookenich.html

JS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gtixrkugwd.html

TS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gtgmbkikrb.html

Java: resp.statusCode()
来源：http://dali.hfpthk.cn/Article/details/gtmqpaiqem.html

Go:   resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gtamrzyanw.html

Ruby: resp.code.to_i
来源：http://dali.sysykeji.top/Article/details/gtaqvdhfjk.html

C#:   (int)resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gtrhexvgcc.html

[L08] 并发请求多个地址
来源：http://dali.bjfxy.top/Article/details/gtyfmpkbfn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tianlin.xyz/Article/details/gtxqrqpcyy.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenlongwang.top/Article/details/gthnwbehnc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcnxobfyu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gtehwiyofl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj202588.top/Article/details/gteopbdnci.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.havefunace.top/Article/details/gtnugdxqcf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.iojbl.cn/Article/details/gtfdyhzicf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenlongwang.top/Article/details/gthsxgdnkd.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtahazklbr.html

M. 命令行 / 进程 / 环境
来源：http://dali.shzxlz.cn/Article/details/gtzirocpdz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktysxhwb.html

[M01] 读取命令行参数
来源：http://dali.yj20258888.top/Article/details/gttqjkzovd.html

Py:   sys.argv[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtprsijdnj.html

PHP:  $argv;  $argc;
来源：http://dali.zhongyouzk.top/Article/details/gtitbqmvoy.html

JS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gtdoptbmbv.html

TS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gtjiauuhgq.html

Java: args 数组（main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtzobtrzyc.html

Go:   os.Args[1:]
来源：http://dali.daria6918.cn/Article/details/gtxayjqtav.html

Ruby: ARGV
来源：http://dali.tanke756.top/Article/details/gtievwhand.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gtaolzzguu.html

[M02] 读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gtpvyajeph.html

Py:   os.environ.get("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtkmutsnbh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtcpdkquae.html

JS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gtlbqgsbnu.html

TS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gtzzpwxhiz.html

Java: System.getenv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtnpxhvodq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrubzghgy.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigfzy.top/Article/details/gtfgmnpmup.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gthclqffgt.html

[M03] 执行外部命令
来源：http://dali.jlsjyb.cn/Article/details/gtgkeincrd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yangfankeji.com/Article/details/gtyshvbeso.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guannengcc.top/Article/details/gtuxeimzxw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gtftfsyvio.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gtxrwivomm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgufenzy.top/Article/details/gtpgzenowd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shangyingyoupin.top/Article/details/gthptvgfdp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hfpthk.cn/Article/details/gtcweupkze.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gzhubu.top/Article/details/gtlffcqxko.html

[M04] 获取当前工作目录
来源：http://dali.pycfn.com/Article/details/gtbnowfqnd.html

Py:   os.getcwd()
来源：http://dali.xylfe.cn/Article/details/gtzmepmyta.html

PHP:  getcwd();
来源：http://dali.yj202588.top/Article/details/gttjyicvaq.html

JS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gtwjlgnuxl.html

TS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxyfoomp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zdqjudy.top/Article/details/gtbyujbicb.html

Go:   os.Getwd()
来源：http://dali.xuanzx.com/Article/details/gtjedtjhil.html

Ruby: Dir.pwd
来源：http://dali.cashguo.top/Article/details/gttbvykveb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hywenlv.cn/Article/details/gttjsxjnwb.html

[M05] 设置退出码
来源：http://dali.tanke756.top/Article/details/gttxtjxvco.html

Py:   sys.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtqyyiinzo.html

PHP:  exit(1);
来源：http://dali.chenzaomai.com/Article/details/gtamidycfm.html

JS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtauvtczgm.html

TS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtddickyfa.html

Java: System.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtirqmfwyi.html

Go:   os.Exit(1)
来源：http://dali.sweek.top/Article/details/gtevhdtmam.html

Ruby: exit 1
来源：http://dali.gotoacloud.top/Article/details/gtzgksjied.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.haohaochexian.top/Article/details/gtjykqmkuz.html

[M06] 向标准错误输出
来源：http://dali.shangyingyoupin.top/Article/details/gtdbhkkjac.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gtobbgkgrq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxwifmzv.html

JS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gtejgsjfum.html

TS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gtclqlomob.html

Java: System.err.println("err")
来源：http://dali.zhengqikj.top/Article/details/gtpaugdgvs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqvdiwkb.html

Ruby: warn "err"
来源：http://dali.nanxinkj.top/Article/details/gtfvnptejz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.meibo888.top/Article/details/gtoqpcnfss.html

[M07] 判断是否为主入口
来源：http://dali.zhiwuduotai.top/Article/details/gtkafkpird.html

Py:   if __name__ == "__main__":
来源：http://dali.xinyue.icu/Article/details/gtqdnrpjgc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ydzc1.top/Article/details/gtbjurlakt.html

JS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gtghjmyspe.html

TS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtztapnyvw.html

Java: public static void main(String[] args)
来源：http://dali.sxryk.cn/Article/details/gtwnttdwen.html

Go:   func main()
来源：http://dali.xinyue.icu/Article/details/gtbqcroomr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hfpthk.cn/Article/details/gtbjrcymgs.html

C#:   static void Main(string[] args)
来源：http://dali.yonumen.top/Article/details/gtvzmstnzz.html

[M08] 获取系统与运行时信息
来源：http://dali.xuetiantiany.cn/Article/details/gtfvkuypgb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.vqdsnc.cn/Article/details/gtofjmgjhv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yanxiufei.cn/Article/details/gttjzgyjgu.html

JS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gtqnnvghbd.html

TS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gtlfnwhlma.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.redwolf501.top/Article/details/gtmsqdfgsq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aizwys.cn/Article/details/gtjygjoyid.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.316326.xyz/Article/details/gtbszlbvuo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnxiangtu.top/Article/details/gtltigcqec.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gthaagbbub.html

N. 数据结构与算法
来源：http://dali.cdnleiting.top/Article/details/gtbhkcqste.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtnvcividy.html

[N01] 二分查找（有序数组）
来源：http://dali.daxiang520.top/Article/details/gtqxlwrnxu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtflcmbyeu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtnzsyantr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gtymkgbpmw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtzdytxvpj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gteutwpali.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tanke756.top/Article/details/gtbnwdiltm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.iojbl.cn/Article/details/gtimecirht.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtfegrmcdp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xinyue.icu/Article/details/gtmcvylvvn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gtgybzxbsw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.snrcjt.cn/Article/details/gtiyeijhel.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gtfmxlmxwv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gtnlelestb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258888.top/Article/details/gtqpufzvev.html

Go:   slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gtcgfszjcc.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gtrejuehqy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgufenzy.top/Article/details/gtjqnhwgii.html

[N03] 快速排序（分治示例）
来源：http://dali.hammf.cn/Article/details/gtzdkmctde.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.wangshuangyany.cn/Article/details/gtasdpkqiz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.bjfxy.top/Article/details/gtqjygmdcm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gtysofnuxj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gthzbunsqw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tianlin.xyz/Article/details/gtlakyljel.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoepfaipz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.meibo888.top/Article/details/gtodcfpose.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hywenlv.cn/Article/details/gtshoyqllu.html

[N04] 斐波那契数列
来源：http://dali.shuidangran.top/Article/details/gtnauzqlrm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnxiangtu.top/Article/details/gttavsonmr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yueranfly.top/Article/details/gtfkjwtexb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtbiooyzzp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtneockvby.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gtkjscqhjp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daxiang520.top/Article/details/gtlpswupfg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtlcvermsv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gthxfcxwxb.html

[N05] 最大公约数
来源：http://dali.zhiwuduotai.top/Article/details/gtzlvyqcrz.html

Py:   math.gcd(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtyfohgsnl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtrearhyyw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gzhubu.top/Article/details/gtkuplblis.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmivgktad.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jianghu66.top/Article/details/gtvyhqsaxy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj20258888.top/Article/details/gtgsonwbfi.html

Ruby: a.gcd(b)
来源：http://dali.ybcxt.top/Article/details/gteapjvlco.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuanzhike.top/Article/details/gtyuxiqmie.html

[N06] 判断回文字符串
来源：http://dali.dashuyun.cn/Article/details/gtrgjdscgn.html

Py:   s == s[::-1]
来源：http://dali.hnxiangtu.top/Article/details/gtnrqpitwn.html

PHP:  $s === strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gtfwdufuov.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtrwmahvzm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtfjoecmch.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.haohaochexian.top/Article/details/gtklnorzib.html

Go:   // 双指针从两端比较
来源：http://dali.zhengqikj.top/Article/details/gtbsgnsahw.html

Ruby: s == s.reverse
来源：http://dali.zdqjudy.top/Article/details/gtyzppopuz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gteedjkitv.html

[N07] 两数之和（返回下标）
来源：http://dali.tian-w.cn/Article/details/gtljldjhpn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cucudq.cn/Article/details/gtzowyfoab.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shangyingyoupin.top/Article/details/gtozwuvcgy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.iojbl.cn/Article/details/gtdpkhnmxb.html

TS:   // 手写 Map<string, number>
来源：http://dali.cqqwz.cn/Article/details/gtrtljdzkr.html

Java: // 手写 HashMap
来源：http://dali.snrcjt.cn/Article/details/gtjodutogm.html

Go:   // 手写 map[int]int
来源：http://dali.redwolf501.top/Article/details/gtpympvgeq.html

Ruby: // 手写 Hash
来源：http://dali.meibo888.top/Article/details/gtawjvooql.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pengpengdd.cyou/Article/details/gteievhzbm.html

[N08] 生成全排列
来源：http://dali.havefunace.top/Article/details/gttrtuwbdg.html

Py:   itertools.permutations(arr)
来源：http://dali.yvedp.cn/Article/details/gtqzblqumh.html

PHP:  // 手写递归交换
来源：http://dali.ydzc1.top/Article/details/gtsbrlojwf.html

JS:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtbilcwncw.html

TS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtfiulyfab.html

Java: // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtohuuhzkm.html

Go:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtwbxfofqk.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigfzy.top/Article/details/gtigamoynn.html

C#:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gttakbtcgi.html

[N09] 栈与队列
来源：http://dali.sysykeji.top/Article/details/gtqzuazfwv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yanxiufei.cn/Article/details/gtlxndzadm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gtrkajsihc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gtkomipswz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.kuanghao11.cn/Article/details/gtpsxltkey.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqswimxq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zycfv.cn/Article/details/gtoegdgrvh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtqraduvgb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxinkj.top/Article/details/gttwhhciyo.html

[N10] 链表节点定义
来源：http://dali.hysaishi.cn/Article/details/gtykzvtylm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnckgwjff.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.wangdashe.top/Article/details/gttgwfxfyo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.meibo888.top/Article/details/gtagfjrpqe.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yuxming.cn/Article/details/gtvwptxkhu.html

Java: class Node { int v; Node next; }
来源：http://dali.xinyue.icu/Article/details/gtcovurfld.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yvedp.cn/Article/details/gtspoeqzbc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pengpengdd.cyou/Article/details/gteqfmhkxd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yangfankeji.com/Article/details/gtxkareypf.html

[N11] 二叉树中序遍历
来源：http://dali.hnxiangtu.top/Article/details/gtrxzoibwa.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.mhx1999.top/Article/details/gtxsagnyvj.html

PHP:  // 手写递归函数
来源：http://dali.yuanzhike.top/Article/details/gtoflksecf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gtqhtmalam.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gthlytlewc.html

Java: // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gtrewqyrdu.html

Go:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gtjfifdpip.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sysykeji.top/Article/details/gthnyzmlms.html

C#:   // 手写递归
来源：http://dali.316326.xyz/Article/details/gtmnrurcsh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258888.top/Article/details/gtpplvvdqs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nanxuanxn.top/Article/details/gtscyidwnh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jqgufenzy.top/Article/details/gtzfhqbxba.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gtxxdzgjpe.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gtxoiqcuga.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gtjhuyvvog.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gogol.net.cn/Article/details/gtdawhytmv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jianghu66.top/Article/details/gtkmmlreyo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ppjwa.cn/Article/details/gtmjgtqtdu.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtnwnjdguh.html

O. 并发与异步
来源：http://dali.pycfn.com/Article/details/gtbsnvajfj.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtoflserhl.html

[O01] 启动一个线程
来源：http://dali.hnxiangtu.top/Article/details/gtbxqttztt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxinkj.top/Article/details/gtblwgnaqu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ehwqpu.com/Article/details/gtzmgpnbfa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258888.top/Article/details/gtsofomfda.html

TS:   // 同 JS
来源：http://dali.hysaishi.cn/Article/details/gtqwaogjzh.html

Java: new Thread(() -> f()).start()
来源：http://dali.hongshengwenyu.top/Article/details/gtakthslmq.html

Go:   go f()
来源：http://dali.gotoacloud.top/Article/details/gtbswbunge.html

Ruby: Thread.new { f }
来源：http://dali.yj20258888.top/Article/details/gtlyotycnp.html

C#:   Task.Run(() => F());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvchtfga.html


<!-- 参考信息 -->