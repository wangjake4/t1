代发 wailian999

[K06] 解析 URL 查询串
来源：http://dali.zhoulong.xyz/Article/details/gtnsetahgr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gtqemeezih.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbyjuobg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gtwbcdgbdu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gtuszkeogi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj202588.top/Article/details/gtueofschc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtpochpscx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtlfcrqjsf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gtqdoswjaw.html

[K07] 进制转换
来源：http://dali.jqgfzy.top/Article/details/gtvvqluwld.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.havefunace.top/Article/details/gttfvyzhso.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuanzhike.top/Article/details/gtkmiqctjy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtovoxpgzn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gteyuqtgcf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtdlmgcymj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.c1oappe.top/Article/details/gtwevcdxxd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guannengcc.top/Article/details/gtwegovxty.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtqyypoxvp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbmmybbo.html

Py:   pickle.dumps(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjpqdpiz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.redwolf501.top/Article/details/gtcklbsfva.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gtqxrhxndp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gtsxkflqsd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.haohaochexian.top/Article/details/gtcutevbza.html

Go:   encoding/gob
来源：http://dali.andypj.xyz/Article/details/gtwyybeaef.html

Ruby: Marshal.dump(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtokpjovji.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jianghu66.top/Article/details/gtuoogvtaj.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtrywtnrkn.html

L. 网络请求
来源：http://dali.cdnleiting.top/Article/details/gtyygwkzvp.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtjjoqfmzs.html

[L01] 发送 GET 请求
来源：http://dali.yuanzhike.top/Article/details/gtvqzernsd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdtruqfl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuanzhike.top/Article/details/gtmkfkipzt.html

JS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gtspkvanmz.html

TS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gtspydiwks.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hfpthk.cn/Article/details/gthdldccfp.html

Go:   resp, err := http.Get(url)
来源：http://dali.aibaodan.cn/Article/details/gtidhiwwqk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258.top/Article/details/gtxguhypne.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.havefunace.top/Article/details/gtcaalabei.html

[L02] 发送 POST JSON
来源：http://dali.birdmap.top/Article/details/gtjkdtkrqu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpriglpiy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenzaomai.com/Article/details/gtdyzprjnu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dianchejie.cn/Article/details/gtpqqikmpe.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivqdxhqg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xziqi.cn/Article/details/gtvpkqmoru.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nwbrower.top/Article/details/gtfzvztbmf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigufen.top/Article/details/gtviqzylwz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.c1oappe.top/Article/details/gtmepqlsbj.html

[L03] 设置自定义请求头
来源：http://dali.xuetiantiany.cn/Article/details/gtddrtilji.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pycfn.com/Article/details/gtvtnlnqxx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gaohongyu789.top/Article/details/gtgvoqfkjp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gtgutqoqkx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gtguxwsyux.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenzaomai.com/Article/details/gtapnznukd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gtgmimdyrg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shuidangran.top/Article/details/gtlaximmjz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jlsjyb.cn/Article/details/gtaxnwncyn.html

[L04] 设置超时
来源：http://dali.zhixingplan.top/Article/details/gttluuvphh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dianchejie.cn/Article/details/gtzoifuhpl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gtymkdrcph.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gtqjtkdphk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gtvasljvra.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zycfv.cn/Article/details/gtqxkzvuwa.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xinyue.icu/Article/details/gtyxkduakr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.fzhhl.top/Article/details/gthovgjged.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwenlrepk.html

[L05] 上传文件（multipart）
来源：http://dali.jqgufenzy.top/Article/details/gtfkvmimak.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yongpay.top/Article/details/gtgylunfna.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.havefunace.top/Article/details/gtbasvqspm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gtdqhzfntk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangshuangyany.cn/Article/details/gtbmqueoeu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jiagoushi.top/Article/details/gtzmcxkvzz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hammf.cn/Article/details/gtohhhnnec.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.9152youxi.cn/Article/details/gtlgceutqt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtoizjbynb.html

[L06] 解析响应为 JSON
来源：http://dali.svipenyu.cn/Article/details/gtappsqagt.html

Py:   resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtbjtwrwws.html

PHP:  json_decode($body, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtttzfvasu.html

JS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtprgpgtxn.html

TS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gtiikvnznn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtvafbthnu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgfzy.top/Article/details/gtozxkhbya.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xylfe.cn/Article/details/gtfxvnhyrz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daria6918.cn/Article/details/gthrkkggmo.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gtkueepjyq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258.top/Article/details/gtjpcxbapg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxuanxn.top/Article/details/gtoeqpdhxg.html

JS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gtlobrmmwr.html

TS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gtmwsddsww.html

Java: resp.statusCode()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpdwdrkm.html

Go:   resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gtywthmjzq.html

Ruby: resp.code.to_i
来源：http://dali.yj20258888.top/Article/details/gtsodkrrsw.html

C#:   (int)resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gtfocstspq.html

[L08] 并发请求多个地址
来源：http://dali.0kj1m.cn/Article/details/gtlgbvlybh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shangyingyoupin.top/Article/details/gtntzmdmql.html

PHP:  curl_multi_init() 系列
来源：http://dali.dianchejie.cn/Article/details/gtuyvzrkyv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gttiaulctw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlntoykas.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sysykeji.top/Article/details/gtrtkjcvvl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnqzz.top/Article/details/gthdjaqyvf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gtasxmxfyy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.snrcjt.cn/Article/details/gtnxbavlfj.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtqwayhxku.html

M. 命令行 / 进程 / 环境
来源：http://dali.yuxming.cn/Article/details/gtyzwxqcrq.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtzswqujlv.html

[M01] 读取命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gtylgubinj.html

Py:   sys.argv[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtzaykffqi.html

PHP:  $argv;  $argc;
来源：http://dali.zhoulong.xyz/Article/details/gtlufaufhq.html

JS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gtjrjpoutz.html

TS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gttkalfljv.html

Java: args 数组（main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gtofswsssr.html

Go:   os.Args[1:]
来源：http://dali.jianghu66.top/Article/details/gtuwbvpoza.html

Ruby: ARGV
来源：http://dali.yanxiufei.cn/Article/details/gtpkmndjbh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gtvqecrzma.html

[M02] 读取环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gthpqfindn.html

Py:   os.environ.get("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtcahnhufz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtzjoqzkqc.html

JS:   process.env.HOME
来源：http://dali.jinqigfzy.top/Article/details/gtqlzunnry.html

TS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthlxptsp.html

Java: System.getenv("HOME")
来源：http://dali.316326.xyz/Article/details/gtsvpvjxvk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrsldbbqs.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gtuvbshnys.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hammf.cn/Article/details/gttxuxrqzd.html

[M03] 执行外部命令
来源：http://dali.jinqigufen.top/Article/details/gtuxitfupy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhixingplan.top/Article/details/gtqtewhlwg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aizwys.cn/Article/details/gtfkxfkaqz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gtnzjspfck.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gtphdqhzuw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hammf.cn/Article/details/gtomeylltd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yvedp.cn/Article/details/gtmqrhctkg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhrcrlid.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvcldpsk.html

[M04] 获取当前工作目录
来源：http://dali.jianghu66.top/Article/details/gtvabtksbi.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gtxqlpadvy.html

PHP:  getcwd();
来源：http://dali.bjfxy.top/Article/details/gtdqkapxwo.html

JS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gtlxgiemtx.html

TS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsdxsbmdn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cashguo.top/Article/details/gtclfwlghp.html

Go:   os.Getwd()
来源：http://dali.zhengqikj.top/Article/details/gtnohvhlaa.html

Ruby: Dir.pwd
来源：http://dali.gaohongyu789.top/Article/details/gtmnunabyj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxinkj.top/Article/details/gtufsnhmwz.html

[M05] 设置退出码
来源：http://dali.xziqi.cn/Article/details/gtbtrddwpo.html

Py:   sys.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtkmrjqxrg.html

PHP:  exit(1);
来源：http://dali.kuanghao11.cn/Article/details/gtfcoctlnc.html

JS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtyfhyivjv.html

TS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtcegvrrkh.html

Java: System.exit(1)
来源：http://dali.316326.xyz/Article/details/gtvurakzlc.html

Go:   os.Exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtzuhrzpbu.html

Ruby: exit 1
来源：http://dali.pengpengdd.cyou/Article/details/gtvqhobhoh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwoccdvzv.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjwarwwn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gtprfgflxk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shzxlz.cn/Article/details/gtxknmtwvt.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtkzguapgz.html

TS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gtnldhkfwv.html

Java: System.err.println("err")
来源：http://dali.gaohongyu789.top/Article/details/gtviazophs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258.top/Article/details/gtdzrukjoy.html

Ruby: warn "err"
来源：http://dali.sxryk.cn/Article/details/gtpczchqpq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aibaodan.cn/Article/details/gtfaxotxld.html

[M07] 判断是否为主入口
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjteibtkf.html

Py:   if __name__ == "__main__":
来源：http://dali.yj202588.top/Article/details/gtjwiyiqcx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.316326.xyz/Article/details/gttrncmjpy.html

JS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gtttgnwtds.html

TS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gttsauqsjg.html

Java: public static void main(String[] args)
来源：http://dali.yj20258.top/Article/details/gtqifrajaf.html

Go:   func main()
来源：http://dali.ppjwa.cn/Article/details/gtifybyqih.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cqqwz.cn/Article/details/gtbgcnkhzn.html

C#:   static void Main(string[] args)
来源：http://dali.dashuyun.cn/Article/details/gtnmrnhnqb.html

[M08] 获取系统与运行时信息
来源：http://dali.316326.xyz/Article/details/gtwqqiiahd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.birdmap.top/Article/details/gtgqljizfi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuanzhike.top/Article/details/gtufmgsmqf.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gtvubxllul.html

TS:   process.platform;  process.version
来源：http://dali.yuanzhike.top/Article/details/gtjwklfmml.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.meibo888.top/Article/details/gtwnntnnlw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shzxlz.cn/Article/details/gtordigdph.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hywenlv.cn/Article/details/gtfllnjceg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yongpay.top/Article/details/gtztjbokgs.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtpzbghwpo.html

N. 数据结构与算法
来源：http://dali.ivvv.top/Article/details/gtaqlispda.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gttvxsdofn.html

[N01] 二分查找（有序数组）
来源：http://dali.meibo888.top/Article/details/gtncjsyico.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtyovqlyjc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xinyue.icu/Article/details/gtkopkltpn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.svipenyu.cn/Article/details/gtorsopxij.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvztjgrrc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtaepjtuud.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtqvwbhibh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenzaomai.com/Article/details/gtqhhcvcsx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtqnmqcfia.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gogol.net.cn/Article/details/gtrnyvsuuc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gtguubbkzc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.316326.xyz/Article/details/gtcouwrvpo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gtssljgplx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gtxyhigfbl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jianghu66.top/Article/details/gtuhytwnme.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtbnpzstol.html

Ruby: arr.sort
来源：http://dali.daria6918.cn/Article/details/gtfaoyzdry.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxuanxn.top/Article/details/gtgctecyoa.html

[N03] 快速排序（分治示例）
来源：http://dali.zycfv.cn/Article/details/gtvtinfbqr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrchjecsw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxinkj.top/Article/details/gtzfxfibyi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gtkpxbreas.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gtwvoyubhi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.meibo888.top/Article/details/gtiomylwes.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuanzx.com/Article/details/gtbyprdsmk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.feifeiyinyue.top/Article/details/gtivcqsodx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hywenlv.cn/Article/details/gtuhnelvth.html

[N04] 斐波那契数列
来源：http://dali.fengsongda.top/Article/details/gtpvevmzub.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gtsbreitgj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gtojbxaafi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtdusbongj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtjvfzgfem.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyusfrimp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fzhhl.top/Article/details/gtcknzhjgn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtbjoiwpxd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtfzdgpivg.html

[N05] 最大公约数
来源：http://dali.dashuyun.cn/Article/details/gtprmxbcst.html

Py:   math.gcd(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gttaanzjjf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shuidangran.top/Article/details/gtvscwoeoj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gtudaqwglr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtrblypnao.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yonumen.top/Article/details/gtrgrtxtea.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fzhhl.top/Article/details/gtxjwtitbe.html

Ruby: a.gcd(b)
来源：http://dali.316326.xyz/Article/details/gtbqdzthtg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yonumen.top/Article/details/gtthfartxi.html

[N06] 判断回文字符串
来源：http://dali.andypj.xyz/Article/details/gthqerwrzo.html

Py:   s == s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gtlmploatz.html

PHP:  $s === strrev($s);
来源：http://dali.xinyue.icu/Article/details/gtfcgwzomr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gttpdxmkyx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtiriuaqsu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xinyue.icu/Article/details/gtexzpvtws.html

Go:   // 双指针从两端比较
来源：http://dali.svipenyu.cn/Article/details/gtqfenugkr.html

Ruby: s == s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcosfkjly.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gtauaidixm.html

[N07] 两数之和（返回下标）
来源：http://dali.shuidangran.top/Article/details/gtvireapyd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnqzz.top/Article/details/gtndbcdwip.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhoulong.xyz/Article/details/gtnjdzjdyc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tian-w.cn/Article/details/gtlimikret.html

TS:   // 手写 Map<string, number>
来源：http://dali.iojbl.cn/Article/details/gtkycaeobm.html

Java: // 手写 HashMap
来源：http://dali.chenzaomai.com/Article/details/gtquvrdaca.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnliyqpog.html

Ruby: // 手写 Hash
来源：http://dali.xuetiantiany.cn/Article/details/gtcyczjvoy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gzhubu.top/Article/details/gtuqvuvnzk.html

[N08] 生成全排列
来源：http://dali.zhiwuduotai.top/Article/details/gtateylclq.html

Py:   itertools.permutations(arr)
来源：http://dali.gzhubu.top/Article/details/gtseasbheq.html

PHP:  // 手写递归交换
来源：http://dali.snrcjt.cn/Article/details/gtombklsad.html

JS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtogqrpkac.html

TS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtrkwuqwqc.html

Java: // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtzcshdacx.html

Go:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuxqoeeb.html

Ruby: arr.permutation.to_a
来源：http://dali.havefunace.top/Article/details/gtykveqryz.html

C#:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtrhnomrlv.html

[N09] 栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gttmhoqple.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.dianchejie.cn/Article/details/gtjgzfiwcs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gttiiqwwgh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtpnwhbeit.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xylfe.cn/Article/details/gtoykdudjf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gtspipkpxy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvulglmr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtdixhjgzz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xinyue.icu/Article/details/gtxikdyknb.html

[N10] 链表节点定义
来源：http://dali.jyoumei.cn/Article/details/gtkkfahafe.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ppjwa.cn/Article/details/gtzpovbrvj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.c1oappe.top/Article/details/gtbibgxudq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.havefunace.top/Article/details/gtbnztrazz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cheryme.top/Article/details/gtzfzycwvn.html

Java: class Node { int v; Node next; }
来源：http://dali.xuetiantiany.cn/Article/details/gtigpdefed.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sweek.top/Article/details/gttrkrquqn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cdnleiting.top/Article/details/gtetccqwyi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xylfe.cn/Article/details/gtiuumhvtr.html

[N11] 二叉树中序遍历
来源：http://dali.nanxinkj.top/Article/details/gtfzyptacl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.birdmap.top/Article/details/gtlirctyla.html

PHP:  // 手写递归函数
来源：http://dali.zhoulong.xyz/Article/details/gtpjubnjij.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gtgdukvajo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gtrgaqzees.html

Java: // 手写递归
来源：http://dali.tanke756.top/Article/details/gtaegzsokq.html

Go:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gttfervcqx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sysykeji.top/Article/details/gteqkcflyo.html

C#:   // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gtcthpbuya.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fengsongda.top/Article/details/gtzbgpkhuk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangshuangyany.cn/Article/details/gtdjdxmylp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.0kj1m.cn/Article/details/gtepaoarxu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gtgfmyazpk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dianchejie.cn/Article/details/gtwjfbovpe.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gtvimdwplo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigfzy.top/Article/details/gtenaqahey.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dashuyun.cn/Article/details/gtwsvvowda.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gtvvugamgw.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtvukolgvu.html

O. 并发与异步
来源：http://dali.mhx1999.top/Article/details/gtfphaidyz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtzezcbhrr.html

[O01] 启动一个线程
来源：http://dali.yj202588.top/Article/details/gtzazdeizi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvililyxm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.svipenyu.cn/Article/details/gtaraajhhf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yanxiufei.cn/Article/details/gtjbqrnugz.html

TS:   // 同 JS
来源：http://dali.ybcxt.top/Article/details/gttzlvfsau.html

Java: new Thread(() -> f()).start()
来源：http://dali.sufxvd.cn/Article/details/gtfffhbbho.html

Go:   go f()
来源：http://dali.hywenlv.cn/Article/details/gtclvujtua.html

Ruby: Thread.new { f }
来源：http://dali.fzhhl.top/Article/details/gtlipmstpa.html

C#:   Task.Run(() => F());
来源：http://dali.hfpthk.cn/Article/details/gtavsfzdgt.html


<!-- 参考信息 -->