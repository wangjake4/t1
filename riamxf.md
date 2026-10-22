代发 wailian999

[K06] 解析 URL 查询串
来源：http://dali.jqgfzy.top/Article/details/gtpqkhwddh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daria6918.cn/Article/details/gtubsglwas.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.9152youxi.cn/Article/details/gtxtjwwwba.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gtkofxtakd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gtxfedrpou.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplcyjfvi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gtvdjwaype.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtiarttgoz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gtaxxsmvnv.html

[K07] 进制转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvrnfjfd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtxxqnamkm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aizwys.cn/Article/details/gthvlmhptm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gthefpzxyv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtjhcmxqsq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtyzueoyzq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guowangkeji.top/Article/details/gtrgvvzenh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xinyue.icu/Article/details/gtatcpqyyj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtlgcchyqb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ivvv.top/Article/details/gtszsypmnl.html

Py:   pickle.dumps(obj)
来源：http://dali.zhixingplan.top/Article/details/gtjieokwmo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.bjfxy.top/Article/details/gthsxxoaxf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yuxming.cn/Article/details/gtibzyxtua.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gttcppnpog.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigufen.top/Article/details/gtrucsllsi.html

Go:   encoding/gob
来源：http://dali.zhiwuduotai.top/Article/details/gthcdkviga.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuanzx.com/Article/details/gttvsrtppe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gtztpqnnds.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtgzyugpwb.html

L. 网络请求
来源：http://dali.tian-w.cn/Article/details/gtcxxblvqi.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtragcmklc.html

[L01] 发送 GET 请求
来源：http://dali.chenjidiqi.icu/Article/details/gtdsmrnunw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jyoumei.cn/Article/details/gtbixfswcw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pycfn.com/Article/details/gtspryttyk.html

JS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gtfcrkrwkg.html

TS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gtvtxnmavf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hfpthk.cn/Article/details/gtzcudnzoe.html

Go:   resp, err := http.Get(url)
来源：http://dali.gaohongyu789.top/Article/details/gtslrffeth.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gaohongyu789.top/Article/details/gttaxbhxxn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhixingplan.top/Article/details/gtlixfxfkv.html

[L02] 发送 POST JSON
来源：http://dali.ehwqpu.com/Article/details/gtgsryvjfh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpeiydhen.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cucudq.cn/Article/details/gtrgbxsnmk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gtpmcaaytr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtqzfwbvpx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigufen.top/Article/details/gtscxyyxgd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangtech.top/Article/details/gthiilimhy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hfpthk.cn/Article/details/gtmxbeuyjb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guannengcc.top/Article/details/gtnewgviqy.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvporqseg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhiwuduotai.top/Article/details/gtcljhrrcg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hywenlv.cn/Article/details/gturdhrdtx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gtzebotvbf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gtupdufkvf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jianghu66.top/Article/details/gtsqdwpsdx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gtuhsyqpxv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.haohaochexian.top/Article/details/gtyhwcanhl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gtpdyesjus.html

[L04] 设置超时
来源：http://dali.xuetiantiany.cn/Article/details/gtbxdplaut.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuanzx.com/Article/details/gtnabzsubs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxinkj.top/Article/details/gtbtnzduop.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gtnjemojsz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gtmofrszdx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cqqwz.cn/Article/details/gtqxzulcfh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cucudq.cn/Article/details/gtavvyavck.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsouwzpz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlardsnp.html

[L05] 上传文件（multipart）
来源：http://dali.zhixingplan.top/Article/details/gthkwdmzvc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cdnleiting.top/Article/details/gtykwvqpgm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.smart0.xyz/Article/details/gtcsmezyus.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gtvngianek.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gtwhrmcocw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.havefunace.top/Article/details/gtfjhcurah.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sysykeji.top/Article/details/gtumagvfqo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.quarkkingdee.top/Article/details/gtmdrkpuya.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtawnnfpur.html

[L06] 解析响应为 JSON
来源：http://dali.vqdsnc.cn/Article/details/gtllevyanw.html

Py:   resp.json()
来源：http://dali.fengsongda.top/Article/details/gtkbnhbfvq.html

PHP:  json_decode($body, true);
来源：http://dali.316326.xyz/Article/details/gtamyfmdix.html

JS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gtrgftcuej.html

TS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gthspbboba.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zdqjudy.top/Article/details/gtjoseexpc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jiagoushi.top/Article/details/gtxxwqpork.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cqqwz.cn/Article/details/gtmcvfczpn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sxryk.cn/Article/details/gtczspswps.html

[L07] 处理 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gtlyjrtyaz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cheryme.top/Article/details/gtmjkntldu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jlsjyb.cn/Article/details/gthnbplnmz.html

JS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gtfrkntaye.html

TS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gtfnqxvwbt.html

Java: resp.statusCode()
来源：http://dali.zhiwuduotai.top/Article/details/gtocemyehs.html

Go:   resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gtarypjodv.html

Ruby: resp.code.to_i
来源：http://dali.hysaishi.cn/Article/details/gthteklbzx.html

C#:   (int)resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gtaiptsztu.html

[L08] 并发请求多个地址
来源：http://dali.sxryk.cn/Article/details/gtnopdaxkl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnxiangtu.top/Article/details/gteuhcpfoe.html

PHP:  curl_multi_init() 系列
来源：http://dali.bjfxy.top/Article/details/gtjaqathcq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gtspnefafi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gtjscswcaq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhixingplan.top/Article/details/gtluffzplm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnxiangtu.top/Article/details/gtphyynynl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuanzhike.top/Article/details/gtacesogxv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fengsongda.top/Article/details/gtjsiqgcoe.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtlevolmtv.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigufen.top/Article/details/gtummzxlir.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtffefuyxl.html

[M01] 读取命令行参数
来源：http://dali.yangfankeji.com/Article/details/gtruqcwrhs.html

Py:   sys.argv[1:]
来源：http://dali.0kj1m.cn/Article/details/gtklxrkuxc.html

PHP:  $argv;  $argc;
来源：http://dali.zycfv.cn/Article/details/gtqiakeima.html

JS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtaxdfdwby.html

TS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gtifzebdoy.html

Java: args 数组（main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gtexiknnty.html

Go:   os.Args[1:]
来源：http://dali.tianlin.xyz/Article/details/gtqaxbbwiq.html

Ruby: ARGV
来源：http://dali.hongshengwenyu.top/Article/details/gteqkdzzlw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pycfn.com/Article/details/gtzcjlwcur.html

[M02] 读取环境变量
来源：http://dali.xuanzx.com/Article/details/gtsqqyjozf.html

Py:   os.environ.get("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtqhptflhu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.aizwys.cn/Article/details/gtpittzeup.html

JS:   process.env.HOME
来源：http://dali.yj202588.top/Article/details/gtgghgszjl.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gtsxuvbjoe.html

Java: System.getenv("HOME")
来源：http://dali.sweek.top/Article/details/gtfkzjhrrn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtvtlkidfn.html

Ruby: ENV["HOME"]
来源：http://dali.daria6918.cn/Article/details/gtgsiixfdn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xylfe.cn/Article/details/gtjgwkmqpg.html

[M03] 执行外部命令
来源：http://dali.gaohongyu789.top/Article/details/gteflcleyc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ybcxt.top/Article/details/gtzwwjhpbk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hfpthk.cn/Article/details/gtsnefunvr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gtuwxlnusc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gtbjrlxgnx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hammf.cn/Article/details/gtgtxwnkbu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ydzc1.top/Article/details/gtdvlgscxh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aizwys.cn/Article/details/gtqhqzfmsf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuanzhike.top/Article/details/gtgoalxcnk.html

[M04] 获取当前工作目录
来源：http://dali.tanke756.top/Article/details/gtawwarbkp.html

Py:   os.getcwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckzmdzxd.html

PHP:  getcwd();
来源：http://dali.pycfn.com/Article/details/gtxizwcnyv.html

JS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gtqdkbzwiv.html

TS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gtuseslvsb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yueranfly.top/Article/details/gtzddoojuz.html

Go:   os.Getwd()
来源：http://dali.dianchejie.cn/Article/details/gtfdeddkvy.html

Ruby: Dir.pwd
来源：http://dali.ehwqpu.com/Article/details/gtpopstezq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihcvqvru.html

[M05] 设置退出码
来源：http://dali.nanxinkj.top/Article/details/gtgajcnfjz.html

Py:   sys.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfplbvque.html

PHP:  exit(1);
来源：http://dali.chenlongwang.top/Article/details/gtchaappgq.html

JS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtkpiexknh.html

TS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtcmuqzukh.html

Java: System.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtgkeypoqu.html

Go:   os.Exit(1)
来源：http://dali.iojbl.cn/Article/details/gtitchlgrb.html

Ruby: exit 1
来源：http://dali.birdmap.top/Article/details/gtyorxtnut.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ivvv.top/Article/details/gtdjkczdnm.html

[M06] 向标准错误输出
来源：http://dali.pengpengdd.cyou/Article/details/gtnzewyogt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gtgsmdgkad.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guannengcc.top/Article/details/gteumzeibx.html

JS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gtfrygvwld.html

TS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gtmtfcqdib.html

Java: System.err.println("err")
来源：http://dali.ehwqpu.com/Article/details/gtpdryfkko.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nwbrower.top/Article/details/gtcsgvqqzz.html

Ruby: warn "err"
来源：http://dali.dashuyun.cn/Article/details/gtwmrzezcs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtfmwgryua.html

[M07] 判断是否为主入口
来源：http://dali.gotoacloud.top/Article/details/gtswwwoinc.html

Py:   if __name__ == "__main__":
来源：http://dali.iojbl.cn/Article/details/gtzuiomddj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aibaodan.cn/Article/details/gtcwlzffux.html

JS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gtiuxivkks.html

TS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gtxpckwmuo.html

Java: public static void main(String[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjuxlhmx.html

Go:   func main()
来源：http://dali.shzxlz.cn/Article/details/gtwtjrsihz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hammf.cn/Article/details/gtmqsboszh.html

C#:   static void Main(string[] args)
来源：http://dali.316326.xyz/Article/details/gtngffqxqj.html

[M08] 获取系统与运行时信息
来源：http://dali.ppjwa.cn/Article/details/gtmlsyhexn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hysaishi.cn/Article/details/gtwcpnokmt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.9152youxi.cn/Article/details/gtummkjjyg.html

JS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gtzpnfypro.html

TS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gtdusgdnkz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuxming.cn/Article/details/gtqboguwya.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxinkj.top/Article/details/gtehtfpbyh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sxryk.cn/Article/details/gtdrspcfmb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.smart0.xyz/Article/details/gtbmxyorpc.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtrfkpmicm.html

N. 数据结构与算法
来源：http://dali.smart0.xyz/Article/details/gtexgpdkwl.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtytcdpytb.html

[N01] 二分查找（有序数组）
来源：http://dali.guowangkeji.top/Article/details/gtzpptlaaq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtmvaicknk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cheryme.top/Article/details/gtktpcybhp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gtlbcmrjes.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtboaneuyw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtfniasmds.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtiizpioyf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aibaodan.cn/Article/details/gtmxelxqlg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtthpkqmzi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xinyue.icu/Article/details/gttyupswyb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.meibo888.top/Article/details/gticsjsmud.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtgmdhedte.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gtdigzgzbj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtpyzvbasu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yueranfly.top/Article/details/gtivvugixw.html

Go:   slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gtuvpjtmhx.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gtkbjkyqzm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangdashe.top/Article/details/gtglkzoooq.html

[N03] 快速排序（分治示例）
来源：http://dali.quarkkingdee.top/Article/details/gtwtzncmci.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuanzx.com/Article/details/gtwvmqqqkc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinqigfzy.top/Article/details/gtgbnxlpzl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gtiiytfhep.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gtrgscbhva.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cdnleiting.top/Article/details/gtwkvfhhtg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gzhubu.top/Article/details/gtlhpaoerq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.andypj.xyz/Article/details/gtqjsmydnp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkavmtut.html

[N04] 斐波那契数列
来源：http://dali.hysaishi.cn/Article/details/gteaparimy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gtbnldcgrj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj202588.top/Article/details/gtesneebtb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtbflyspxv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gtffkgwwiy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hammf.cn/Article/details/gtziquqghk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daxiang520.top/Article/details/gtsemesbmx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gtwddtscsz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gtizehezfb.html

[N05] 最大公约数
来源：http://dali.wangdashe.top/Article/details/gtdqepszjm.html

Py:   math.gcd(a, b)
来源：http://dali.tian-w.cn/Article/details/gtmyxcbjbt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsiriyuar.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gtfeeegrkw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkemdtsn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ehwqpu.com/Article/details/gtlgpvgona.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nwbrower.top/Article/details/gtrpvgrthz.html

Ruby: a.gcd(b)
来源：http://dali.nwbrower.top/Article/details/gtzccudvja.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.haohaochexian.top/Article/details/gtjeydeikk.html

[N06] 判断回文字符串
来源：http://dali.c1oappe.top/Article/details/gtwnsgblmp.html

Py:   s == s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gtdmoirtxi.html

PHP:  $s === strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtfmlvaxdo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtczfsrgpl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtbavatbpn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gteogawzor.html

Go:   // 双指针从两端比较
来源：http://dali.kuanghao11.cn/Article/details/gteceveezt.html

Ruby: s == s.reverse
来源：http://dali.snrcjt.cn/Article/details/gtmvmrbzyw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gtklnumtjd.html

[N07] 两数之和（返回下标）
来源：http://dali.jlsjyb.cn/Article/details/gtpitpzvky.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.vqdsnc.cn/Article/details/gtetkqphbg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hammf.cn/Article/details/gtiyppbhcz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.redwolf501.top/Article/details/gtvpkfzzem.html

TS:   // 手写 Map<string, number>
来源：http://dali.gzhubu.top/Article/details/gtpdbysisa.html

Java: // 手写 HashMap
来源：http://dali.zhoulong.xyz/Article/details/gtxgvuzqnd.html

Go:   // 手写 map[int]int
来源：http://dali.cqqwz.cn/Article/details/gtfyjufhcx.html

Ruby: // 手写 Hash
来源：http://dali.c1oappe.top/Article/details/gtqzmobfdj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gotoacloud.top/Article/details/gtwjfvjmtf.html

[N08] 生成全排列
来源：http://dali.shangyingyoupin.top/Article/details/gtvsyjgfsl.html

Py:   itertools.permutations(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtctqvcisy.html

PHP:  // 手写递归交换
来源：http://dali.zhixingplan.top/Article/details/gtrlrsgzuc.html

JS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtcxyuqjif.html

TS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtnklhurxk.html

Java: // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtjipuxvlu.html

Go:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtkolqqwcc.html

Ruby: arr.permutation.to_a
来源：http://dali.shangyingyoupin.top/Article/details/gtypfdpizj.html

C#:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtiidoaxxk.html

[N09] 栈与队列
来源：http://dali.yvedp.cn/Article/details/gtnghjprhw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.316326.xyz/Article/details/gtoynjzkxl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gtyngbfraf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gtgbxnsccy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhengqikj.top/Article/details/gtsngkikbq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj202588.top/Article/details/gtiqtipqlt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.iojbl.cn/Article/details/gtsldmrmbl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtvghhqtpq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dianchejie.cn/Article/details/gtvulnwbql.html

[N10] 链表节点定义
来源：http://dali.daxiang520.top/Article/details/gttnheapxt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gotoacloud.top/Article/details/gtbfxfknxk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhongyouzk.top/Article/details/gtnkzfbtgp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fzhhl.top/Article/details/gtaapnsxlz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gaohongyu789.top/Article/details/gtiqewputx.html

Java: class Node { int v; Node next; }
来源：http://dali.9152youxi.cn/Article/details/gttspxbpwy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hongshengwenyu.top/Article/details/gtyigseguq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhixingplan.top/Article/details/gtulyskfny.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yanxiufei.cn/Article/details/gtaicgfyvc.html

[N11] 二叉树中序遍历
来源：http://dali.chenzaomai.com/Article/details/gtzbndiqet.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gaohongyu789.top/Article/details/gtcupvorfw.html

PHP:  // 手写递归函数
来源：http://dali.guannengcc.top/Article/details/gtgztxoqnh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gtkxpqpjpz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gtlypcgupu.html

Java: // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtocurqwyq.html

Go:   // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtfdajqirg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pengpengdd.cyou/Article/details/gtsmzuhtlo.html

C#:   // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gtammnfmgc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jianghu66.top/Article/details/gtramxfrnz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xuetiantiany.cn/Article/details/gtgmtxobkl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cucudq.cn/Article/details/gtcnpyfuox.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuanzx.com/Article/details/gtlldsmwsg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gtxamhlrnj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gtwtqghtym.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.kuanghao11.cn/Article/details/gtsjlmucjr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zycfv.cn/Article/details/gtgcmwhhlp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gtdsfjyvpf.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtsvnqbkrw.html

O. 并发与异步
来源：http://dali.ppjwa.cn/Article/details/gtltelfqev.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcnnucgda.html

[O01] 启动一个线程
来源：http://dali.cqqwz.cn/Article/details/gtitxyeqrs.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.iojbl.cn/Article/details/gtfpkhaaeo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.quarkkingdee.top/Article/details/gtzqukjykd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenlongwang.top/Article/details/gtkiopqwqy.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gtjuwgjgyn.html

Java: new Thread(() -> f()).start()
来源：http://dali.nanxinkj.top/Article/details/gtxfzzcbjj.html

Go:   go f()
来源：http://dali.snrcjt.cn/Article/details/gtdgylhkvv.html

Ruby: Thread.new { f }
来源：http://dali.nanxinkj.top/Article/details/gtxeryjtpm.html

C#:   Task.Run(() => F());
来源：http://dali.yonumen.top/Article/details/gtlguxxmwt.html


<!-- 参考信息 -->