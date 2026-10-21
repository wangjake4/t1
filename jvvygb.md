代发 wailian999

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigfzy.top/Article/details/gtelbjblnd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangshuangyany.cn/Article/details/gtqazeqaif.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj202588.top/Article/details/gtxstozncj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj202588.top/Article/details/gtvrthquzk.html

[K06] 解析 URL 查询串
来源：http://dali.hywenlv.cn/Article/details/gtjtoncxxm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gtqgvopgzn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gzhubu.top/Article/details/gtehzvsfxn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gtegfezvph.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gtwxrvuhpx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cashguo.top/Article/details/gttgsbersc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gtdtnfarbq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtwdiielrp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtmeoogkgp.html

[K07] 进制转换
来源：http://dali.nanxuanxn.top/Article/details/gtfdroshfm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtncpxqixl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cheryme.top/Article/details/gtgfaargmf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtxmfxxyrz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtjkysdgsk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtlrmbxfrl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.feifeiyinyue.top/Article/details/gtwliqneda.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigufen.top/Article/details/gthtbynvar.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtekhmgcou.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.9152youxi.cn/Article/details/gtxrqycpom.html

Py:   pickle.dumps(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlshetxzz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.bjfxy.top/Article/details/gtipcirlqa.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xuetiantiany.cn/Article/details/gtusvahpup.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gthwhgtvfc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tanke756.top/Article/details/gtlguzncjt.html

Go:   encoding/gob
来源：http://dali.yuanzhike.top/Article/details/gtrjcquqxb.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtkwxvyagp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtiklqbepg.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtcziutjay.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gtqhcfgoty.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtoanjayjo.html

[L01] 发送 GET 请求
来源：http://dali.dianchejie.cn/Article/details/gtrukgghyv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yvedp.cn/Article/details/gthqlqcwax.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nwbrower.top/Article/details/gtqvwayooo.html

JS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gtbkyvxlfa.html

TS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gtzbiokpzk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gotoacloud.top/Article/details/gtyglmxxaz.html

Go:   resp, err := http.Get(url)
来源：http://dali.jlsjyb.cn/Article/details/gtsmavqohb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tanke756.top/Article/details/gtqigtrouc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tian-w.cn/Article/details/gtoufxhanp.html

[L02] 发送 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtkpnjckmn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gtmsxvegti.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgfzy.top/Article/details/gtwbosarke.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gtprqfazlp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gtzpuqdfhx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xuanzx.com/Article/details/gtpagrxthj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuetiantiany.cn/Article/details/gtnrrlmivt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnqzz.top/Article/details/gtgskonqwm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.feifeiyinyue.top/Article/details/gtpeeitvqc.html

[L03] 设置自定义请求头
来源：http://dali.shangyingyoupin.top/Article/details/gteyyeckmr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenjidiqi.icu/Article/details/gttwfhqbhp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.bjfxy.top/Article/details/gtfauhgbwq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gtemduvlhw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gtilibnpcm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gzhubu.top/Article/details/gtlsccjkma.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gtikiscota.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinghuilouyu.cn/Article/details/gtjagmffqp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gtoduyjymm.html

[L04] 设置超时
来源：http://dali.sweek.top/Article/details/gtivtkxpvl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shuidangran.top/Article/details/gtqbnfvcvt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sysykeji.top/Article/details/gtbqofanft.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gtnkyhpqzg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxqpvxwi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258.top/Article/details/gtbflbuyhd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yangfankeji.com/Article/details/gtvbdpjnrz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tian-w.cn/Article/details/gtjmnnbiyn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jiagoushi.top/Article/details/gtpfgrshoe.html

[L05] 上传文件（multipart）
来源：http://dali.guowangkeji.top/Article/details/gtdyvnkmts.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.snrcjt.cn/Article/details/gtfdtgjqen.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.mhx1999.top/Article/details/gtnwlcyiqn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gtdkjryyxq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gtaqpjjjtb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jiagoushi.top/Article/details/gtvtkflowi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.0kj1m.cn/Article/details/gtevmdqrnb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jiagoushi.top/Article/details/gtxgytphfl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtzfpffghb.html

[L06] 解析响应为 JSON
来源：http://dali.fzhhl.top/Article/details/gtxgdmwcpb.html

Py:   resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwtmenun.html

PHP:  json_decode($body, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtcgvkhlsa.html

JS:   await resp.json()
来源：http://dali.jianghu66.top/Article/details/gtzgwldwyw.html

TS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gtipjiwmlw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xinyue.icu/Article/details/gtaiyrjytu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.c1oappe.top/Article/details/gtbrpbgcop.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hfpthk.cn/Article/details/gtrwhoqzhw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ybcxt.top/Article/details/gtvgjtpowd.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gtqwzxbikj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sysykeji.top/Article/details/gthcsdkfyw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fzhhl.top/Article/details/gtumhttgzy.html

JS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gtuycjesun.html

TS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gtgiqpcdxm.html

Java: resp.statusCode()
来源：http://dali.316326.xyz/Article/details/gtsifhovky.html

Go:   resp.StatusCode
来源：http://dali.gotoacloud.top/Article/details/gtdrhoeqpw.html

Ruby: resp.code.to_i
来源：http://dali.316326.xyz/Article/details/gtxigvddjv.html

C#:   (int)resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gtcciqnogg.html

[L08] 并发请求多个地址
来源：http://dali.nanxinkj.top/Article/details/gtoneffdaf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daxiang520.top/Article/details/gtmpqtkezw.html

PHP:  curl_multi_init() 系列
来源：http://dali.snrcjt.cn/Article/details/gtfbvrtaaf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtqkjbmzkv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtvegxkgmi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.redwolf501.top/Article/details/gtvcgmvlvi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangshuangyany.cn/Article/details/gtpbrurtul.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nwbrower.top/Article/details/gtpupnwamm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gtuvbblutq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtpuahfcnw.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj20258888.top/Article/details/gtabayncft.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtwzztaggb.html

[M01] 读取命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gtxvsjxtmh.html

Py:   sys.argv[1:]
来源：http://dali.chenzaomai.com/Article/details/gtythoejft.html

PHP:  $argv;  $argc;
来源：http://dali.yueranfly.top/Article/details/gtbgbrtmgf.html

JS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gtvokdabyi.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gtwxtprvwc.html

Java: args 数组（main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gtnpwzjwsb.html

Go:   os.Args[1:]
来源：http://dali.tian-w.cn/Article/details/gtftlzqvlc.html

Ruby: ARGV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynwqtxhj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpqpvhqu.html

[M02] 读取环境变量
来源：http://dali.hywenlv.cn/Article/details/gtogduhfbf.html

Py:   os.environ.get("HOME")
来源：http://dali.fzhhl.top/Article/details/gthrfvtbqw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gtfuaguizs.html

JS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtomkcylxp.html

TS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtobtlvbel.html

Java: System.getenv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtnziuuvmz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.redwolf501.top/Article/details/gttgaecuyg.html

Ruby: ENV["HOME"]
来源：http://dali.jqgufenzy.top/Article/details/gtwzfgewdw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtzcnxawpp.html

[M03] 执行外部命令
来源：http://dali.bjfxy.top/Article/details/gtmocjgurm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gttkikkyib.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.svipenyu.cn/Article/details/gtvxiytrmv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gtdvwihhyt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gtvhdlcfnz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.quarkkingdee.top/Article/details/gtohuazwhe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tanke756.top/Article/details/gtrgparhxt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.snrcjt.cn/Article/details/gtejqvbhpx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sweek.top/Article/details/gtrdijlsam.html

[M04] 获取当前工作目录
来源：http://dali.meibo888.top/Article/details/gtmmwyivry.html

Py:   os.getcwd()
来源：http://dali.xylfe.cn/Article/details/gtwwyjacup.html

PHP:  getcwd();
来源：http://dali.ydzc1.top/Article/details/gtdklamhbd.html

JS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gtnbiuwyzk.html

TS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gteuxvjluy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cucudq.cn/Article/details/gtrxbderuw.html

Go:   os.Getwd()
来源：http://dali.jianghu66.top/Article/details/gtrmidhkal.html

Ruby: Dir.pwd
来源：http://dali.yj202588.top/Article/details/gtnkhtauez.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxuanxn.top/Article/details/gtgwioiflo.html

[M05] 设置退出码
来源：http://dali.hnxiangtu.top/Article/details/gtmgaomfko.html

Py:   sys.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtppixupel.html

PHP:  exit(1);
来源：http://dali.feifeiyinyue.top/Article/details/gtteczfjlr.html

JS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtdymtrnqx.html

TS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gtnzfttqni.html

Java: System.exit(1)
来源：http://dali.ivvv.top/Article/details/gtjpjjxram.html

Go:   os.Exit(1)
来源：http://dali.pycfn.com/Article/details/gtdpaoogay.html

Ruby: exit 1
来源：http://dali.kuanghao11.cn/Article/details/gtaahxvivx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigfzy.top/Article/details/gtajdgajni.html

[M06] 向标准错误输出
来源：http://dali.ehwqpu.com/Article/details/gtfwidtdgx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.haohaochexian.top/Article/details/gtzgfhdqfv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.quarkkingdee.top/Article/details/gtgzjcjpdk.html

JS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gtnhrnizwa.html

TS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gthkzzaggn.html

Java: System.err.println("err")
来源：http://dali.guannengcc.top/Article/details/gtragyjsev.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnqzz.top/Article/details/gtbrodqfbz.html

Ruby: warn "err"
来源：http://dali.9152youxi.cn/Article/details/gteriajwyk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuanzx.com/Article/details/gtejdysgab.html

[M07] 判断是否为主入口
来源：http://dali.nwbrower.top/Article/details/gtlwbotyct.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigfzy.top/Article/details/gtbleohoun.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.feifeiyinyue.top/Article/details/gtzkdknevz.html

JS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gtfwuhecll.html

TS:   require.main === module
来源：http://dali.sweek.top/Article/details/gtpwnfjytu.html

Java: public static void main(String[] args)
来源：http://dali.jqgufenzy.top/Article/details/gtslewwwvg.html

Go:   func main()
来源：http://dali.svipenyu.cn/Article/details/gtgreajbry.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenjidiqi.icu/Article/details/gtfdelwcpl.html

C#:   static void Main(string[] args)
来源：http://dali.ydzc1.top/Article/details/gtucoqhlih.html

[M08] 获取系统与运行时信息
来源：http://dali.guannengcc.top/Article/details/gtuiforyyy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ydzc1.top/Article/details/gtursaljki.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgeeebper.html

JS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gtnkmvzlsy.html

TS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gtvlfaavju.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.birdmap.top/Article/details/gtbbzbjbhl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258.top/Article/details/gtiejuggss.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.birdmap.top/Article/details/gthuovsebh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgfzy.top/Article/details/gttixvigap.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtudtrtbhk.html

N. 数据结构与算法
来源：http://dali.yuxming.cn/Article/details/gtmzuqooio.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtejzzzlxd.html

[N01] 二分查找（有序数组）
来源：http://dali.yueranfly.top/Article/details/gtrejnmdpp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtdanzekyd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.0kj1m.cn/Article/details/gtpiysness.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gtwnrdunkv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gtirsdukun.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtpomiryzn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtczdrfbpk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangdashe.top/Article/details/gtsiokpwuj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gtasnmvjkg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ehwqpu.com/Article/details/gtlejjgwgv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hywenlv.cn/Article/details/gtbgehpypb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jyoumei.cn/Article/details/gtjgwtofre.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiavdirqm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtlfmdhwvx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhixingplan.top/Article/details/gtqlekdcyk.html

Go:   slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gtssnufcni.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gtxeovsghw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cucudq.cn/Article/details/gtptdwevvh.html

[N03] 快速排序（分治示例）
来源：http://dali.xuetiantiany.cn/Article/details/gtvthjrght.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hywenlv.cn/Article/details/gtexldhgzo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gotoacloud.top/Article/details/gtfsbaalbi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guowangkeji.top/Article/details/gttrgvqxan.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gtjvtaphra.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtmbdpryjh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ydzc1.top/Article/details/gtdupfcoqi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shuidangran.top/Article/details/gtxtepocje.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ybcxt.top/Article/details/gtuyzqexld.html

[N04] 斐波那契数列
来源：http://dali.dashuyun.cn/Article/details/gtsolvhpmz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gtgmixwbwv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gtqjiwvieo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtcqiiiwza.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtzewypxiy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cucudq.cn/Article/details/gtjvkizykm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxinkj.top/Article/details/gtmyctxqxo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cdnleiting.top/Article/details/gtxewhlouh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gthmgjstcr.html

[N05] 最大公约数
来源：http://dali.zycfv.cn/Article/details/gtlblquhkt.html

Py:   math.gcd(a, b)
来源：http://dali.xylfe.cn/Article/details/gtwiyabzvb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jlsjyb.cn/Article/details/gtzfvkjxbh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gtrlpprrjc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gtauagvjis.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guannengcc.top/Article/details/gtwfypwzwy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cucudq.cn/Article/details/gtekmapbkn.html

Ruby: a.gcd(b)
来源：http://dali.vqdsnc.cn/Article/details/gthdrbxgfi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.haohaochexian.top/Article/details/gtndsuvtgc.html

[N06] 判断回文字符串
来源：http://dali.hnxiangtu.top/Article/details/gtxdoeeqhd.html

Py:   s == s[::-1]
来源：http://dali.sxryk.cn/Article/details/gtgngiluwe.html

PHP:  $s === strrev($s);
来源：http://dali.cashguo.top/Article/details/gtcjccimpo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtohhzgeqw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtlgtjzaxy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cucudq.cn/Article/details/gtvxodwpfg.html

Go:   // 双指针从两端比较
来源：http://dali.gaohongyu789.top/Article/details/gtrtzowiox.html

Ruby: s == s.reverse
来源：http://dali.gogol.net.cn/Article/details/gtcudigidm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gtyehluukt.html

[N07] 两数之和（返回下标）
来源：http://dali.wangshuangyany.cn/Article/details/gtemxqpwvu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yanxiufei.cn/Article/details/gtpqogiucb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shuidangran.top/Article/details/gtanimarkz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnqzz.top/Article/details/gtmpohwlif.html

TS:   // 手写 Map<string, number>
来源：http://dali.sufxvd.cn/Article/details/gtllosqnis.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gtvkpevtle.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258.top/Article/details/gtcafggrra.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangtech.top/Article/details/gtodgqnter.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shuidangran.top/Article/details/gtxzlyvrzr.html

[N08] 生成全排列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtieyaicfj.html

Py:   itertools.permutations(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtovzkaopw.html

PHP:  // 手写递归交换
来源：http://dali.zhengqikj.top/Article/details/gtombvchvi.html

JS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtafitjmdl.html

TS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtmlsjiwqc.html

Java: // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtjsbminxt.html

Go:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gttjmjmbhj.html

Ruby: arr.permutation.to_a
来源：http://dali.xuanzx.com/Article/details/gtllghgzly.html

C#:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvsjdgmk.html

[N09] 栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppgayfbo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guannengcc.top/Article/details/gtrjnscjty.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.316326.xyz/Article/details/gtkzigzbrf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtguqzjtlu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tianlin.xyz/Article/details/gtjxkbxktn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gogol.net.cn/Article/details/gtzrybtbji.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenzaomai.com/Article/details/gtiltdwzlj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gtzahqujhb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.meibo888.top/Article/details/gtspavzcwu.html

[N10] 链表节点定义
来源：http://dali.cdnleiting.top/Article/details/gtmbbojyep.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.andypj.xyz/Article/details/gtyunuygqi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.fengsongda.top/Article/details/gthqbayqxx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenlongwang.top/Article/details/gtclmtbaik.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjuecvovc.html

Java: class Node { int v; Node next; }
来源：http://dali.gaohongyu789.top/Article/details/gtswcdmdre.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yangfankeji.com/Article/details/gtmtstkmpc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinqigufen.top/Article/details/gtqlirytrr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yonumen.top/Article/details/gtelcqorox.html

[N11] 二叉树中序遍历
来源：http://dali.ivvv.top/Article/details/gtnzvvdgbn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hammf.cn/Article/details/gtwityjzpj.html

PHP:  // 手写递归函数
来源：http://dali.shzxlz.cn/Article/details/gtgvdibtdo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gtvbxqfxkk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgufenzy.top/Article/details/gtzwwjvqzz.html

Java: // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtjdyfbweu.html

Go:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtbuymdslg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.iojbl.cn/Article/details/gtkqbkyvob.html

C#:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gtxmcaahhi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxlulugf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.c1oappe.top/Article/details/gtyhdcellz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cdnleiting.top/Article/details/gtqnkaywnq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuanzx.com/Article/details/gtvslhzyzu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnqzz.top/Article/details/gttpkklinz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpegmjep.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ppjwa.cn/Article/details/gtsafcijmr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ehwqpu.com/Article/details/gtqzzmizcq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gtibxggrpq.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtnaudwesz.html

O. 并发与异步
来源：http://dali.sysykeji.top/Article/details/gtpcjkoxzm.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtikxarunj.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gtenoxyvbg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daxiang520.top/Article/details/gthxexcuxo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hongshengwenyu.top/Article/details/gtadrdqbpa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.bjfxy.top/Article/details/gtdgqqnxzc.html

TS:   // 同 JS
来源：http://dali.jlsjyb.cn/Article/details/gteauiuzli.html


<!-- 参考信息 -->