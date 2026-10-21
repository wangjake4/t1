代发 wailian999

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tian-w.cn/Article/details/gtdsyfsvdh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhoulong.xyz/Article/details/gtcfzfmqrp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tanke756.top/Article/details/gtfleaiflm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guowangkeji.top/Article/details/gtfyorxnzf.html

[K06] 解析 URL 查询串
来源：http://dali.0kj1m.cn/Article/details/gtdwnfczdy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gtrfdlxdsj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj202588.top/Article/details/gtghpwhfhn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cucudq.cn/Article/details/gtxjjpojpz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyigczbdi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.0kj1m.cn/Article/details/gtsuefnlzo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gtcezpygkl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gtmmtgvxib.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtfjkogcpy.html

[K07] 进制转换
来源：http://dali.zhiwuduotai.top/Article/details/gtabprbwpk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtezxpxgye.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenjidiqi.icu/Article/details/gtnpurabrt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtmeqbktgm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gthiypjbrh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuioaouxb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sxryk.cn/Article/details/gtsamsprgw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhixingplan.top/Article/details/gtobfkuqal.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gthvtrmkqu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hammf.cn/Article/details/gtinmdgbpb.html

Py:   pickle.dumps(obj)
来源：http://dali.yuxming.cn/Article/details/gtsdbwwydx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xinyue.icu/Article/details/gtqgoyndhn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gtlbxhgwaf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gtlywckbaw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.mhx1999.top/Article/details/gtyvrjtmza.html

Go:   encoding/gob
来源：http://dali.yj20258.top/Article/details/gtoaoperna.html

Ruby: Marshal.dump(obj)
来源：http://dali.ppjwa.cn/Article/details/gtbrhehecl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gtahwzgala.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtoeidqgdv.html

L. 网络请求
来源：http://dali.yuanzhike.top/Article/details/gtvdxvxqgb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtqhdwytaa.html

[L01] 发送 GET 请求
来源：http://dali.wangdashe.top/Article/details/gttqjfaued.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.kuanghao11.cn/Article/details/gtggbffdlz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zdqjudy.top/Article/details/gtoitjjtyx.html

JS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswsiuhzx.html

TS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gtzgceosef.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258888.top/Article/details/gtxjjdikph.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtshhovvol.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cdnleiting.top/Article/details/gtkjgerrzs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.havefunace.top/Article/details/gtcvrbcmiz.html

[L02] 发送 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gtzuwbtonh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gotoacloud.top/Article/details/gtkujymyww.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ybcxt.top/Article/details/gtpnphrtqj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gtlayybnak.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gtyctwkful.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.vqdsnc.cn/Article/details/gtbzsgcjnd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.smart0.xyz/Article/details/gtbkbmlgrb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cqqwz.cn/Article/details/gtlsrzgqiy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhongyouzk.top/Article/details/gtbccofdpk.html

[L03] 设置自定义请求头
来源：http://dali.fzhhl.top/Article/details/gtyplovced.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xylfe.cn/Article/details/gtnrbezpww.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hnqzz.top/Article/details/gtrnxhmnnv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.vqdsnc.cn/Article/details/gtkelkpnhi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daxiang520.top/Article/details/gtwtlkwsxp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ybcxt.top/Article/details/gtceyffugm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gtjutylhac.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ehwqpu.com/Article/details/gtapfebkhw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gtwbipbuox.html

[L04] 设置超时
来源：http://dali.snrcjt.cn/Article/details/gtswdhfebh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tianlin.xyz/Article/details/gtvysdxbfw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yueranfly.top/Article/details/gtoiechkoy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gtnsgvhips.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgufenzy.top/Article/details/gtbthyzykd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jyoumei.cn/Article/details/gtngokeaqu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shangyingyoupin.top/Article/details/gtnpunbqtk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sufxvd.cn/Article/details/gtypbjbotq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj202588.top/Article/details/gthrohweyo.html

[L05] 上传文件（multipart）
来源：http://dali.jyoumei.cn/Article/details/gtoktvhhfd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ybcxt.top/Article/details/gtxkwovpre.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yvedp.cn/Article/details/gtqctxspfx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shuidangran.top/Article/details/gtabsdmazb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtyixokehr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkzzkwly.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sufxvd.cn/Article/details/gtbyhonfdm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tian-w.cn/Article/details/gtbulmnxsa.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxxpfujj.html

[L06] 解析响应为 JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtnnlfuy.html

Py:   resp.json()
来源：http://dali.fengsongda.top/Article/details/gtidhynosc.html

PHP:  json_decode($body, true);
来源：http://dali.shzxlz.cn/Article/details/gtnrchgpqy.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gtbukpcxfe.html

TS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtjyefchip.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuxming.cn/Article/details/gteehaeedv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangdashe.top/Article/details/gtynrumzwa.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258.top/Article/details/gtmxhknxxp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.9152youxi.cn/Article/details/gtvbwgnhhf.html

[L07] 处理 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gtruldgzqs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenjidiqi.icu/Article/details/gtdvolkgij.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gtiipibjln.html

JS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gtitcxfkvw.html

TS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gteqzkinin.html

Java: resp.statusCode()
来源：http://dali.guowangkeji.top/Article/details/gtqrbrhkyz.html

Go:   resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gtgmzcpesz.html

Ruby: resp.code.to_i
来源：http://dali.ivvv.top/Article/details/gtcujwbsyu.html

C#:   (int)resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gtvlixgirh.html

[L08] 并发请求多个地址
来源：http://dali.yongpay.top/Article/details/gtwfaotowf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guowangkeji.top/Article/details/gtrzfusaea.html

PHP:  curl_multi_init() 系列
来源：http://dali.daxiang520.top/Article/details/gtveypedxj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gtomfbmkuh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gtdltkslac.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shangyingyoupin.top/Article/details/gtjyslbndj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258.top/Article/details/gtyeilhkte.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tianlin.xyz/Article/details/gtrultpjxu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckrdlnzt.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtcvdqpyvs.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgufenzy.top/Article/details/gtgnkwyeov.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gttpfbhwrb.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gtzxfotqtd.html

Py:   sys.argv[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkfuhjtl.html

PHP:  $argv;  $argc;
来源：http://dali.chenjidiqi.icu/Article/details/gtxqsegiae.html

JS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gtijhklven.html

TS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gtawutfbgu.html

Java: args 数组（main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gtohhxibsk.html

Go:   os.Args[1:]
来源：http://dali.ehwqpu.com/Article/details/gtimooxduw.html

Ruby: ARGV
来源：http://dali.jinqigufen.top/Article/details/gtuedtpidj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gtnpjoeiqc.html

[M02] 读取环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgufvvsnm.html

Py:   os.environ.get("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtinzpkdzl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yongpay.top/Article/details/gtmgnklnvw.html

JS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gtfokncgor.html

TS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmujldjzo.html

Java: System.getenv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjigohpq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj202588.top/Article/details/gtyszqbhhz.html

Ruby: ENV["HOME"]
来源：http://dali.haohaochexian.top/Article/details/gtrscceoue.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuanzx.com/Article/details/gtlscjfrat.html

[M03] 执行外部命令
来源：http://dali.gzhubu.top/Article/details/gtkcyfmenk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sysykeji.top/Article/details/gtxfquirec.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yongpay.top/Article/details/gtrgffnrde.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gtiusvkcoe.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdupkmdkh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shangyingyoupin.top/Article/details/gtlbkmkycd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.0kj1m.cn/Article/details/gtayyodpat.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuetiantiany.cn/Article/details/gtlnkxghcl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhengqikj.top/Article/details/gtazgdxnox.html

[M04] 获取当前工作目录
来源：http://dali.chenjidiqi.icu/Article/details/gtkakdykoo.html

Py:   os.getcwd()
来源：http://dali.xylfe.cn/Article/details/gtogcjgfvo.html

PHP:  getcwd();
来源：http://dali.yuanzhike.top/Article/details/gtpzayjpxg.html

JS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gtngjngvzu.html

TS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gtobrcqutc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.fzhhl.top/Article/details/gtnncfeydh.html

Go:   os.Getwd()
来源：http://dali.kuanghao11.cn/Article/details/gtfrvmcinz.html

Ruby: Dir.pwd
来源：http://dali.jqgfzy.top/Article/details/gtebshdlnr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxheuzztw.html

[M05] 设置退出码
来源：http://dali.yuxming.cn/Article/details/gtycethmqm.html

Py:   sys.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtnfiyobsu.html

PHP:  exit(1);
来源：http://dali.daxiang520.top/Article/details/gtzcnvmmbs.html

JS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtfmuhuuob.html

TS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gthyjkrysk.html

Java: System.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtuyutbvqa.html

Go:   os.Exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtbjenddjz.html

Ruby: exit 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtniiafn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.9152youxi.cn/Article/details/gtibbuxgtb.html

[M06] 向标准错误输出
来源：http://dali.yangfankeji.com/Article/details/gtytbwlsfj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gtuuypaqpt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.snrcjt.cn/Article/details/gtnopwdezc.html

JS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gtmxoqvgzr.html

TS:   console.error("err")
来源：http://dali.gotoacloud.top/Article/details/gtpzodamfl.html

Java: System.err.println("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtpbvbkbek.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258888.top/Article/details/gtlervpwrs.html

Ruby: warn "err"
来源：http://dali.316326.xyz/Article/details/gtfribukhx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenzaomai.com/Article/details/gtixjcckti.html

[M07] 判断是否为主入口
来源：http://dali.zdqjudy.top/Article/details/gtdhwpgltr.html

Py:   if __name__ == "__main__":
来源：http://dali.cdnleiting.top/Article/details/gtewjrlvry.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tian-w.cn/Article/details/gtfgxdclkj.html

JS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gtxdadqrio.html

TS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gtyxctxgke.html

Java: public static void main(String[] args)
来源：http://dali.sufxvd.cn/Article/details/gtzbnrtjye.html

Go:   func main()
来源：http://dali.birdmap.top/Article/details/gtcoocalry.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shzxlz.cn/Article/details/gtckbvondi.html

C#:   static void Main(string[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakfzqyrn.html

[M08] 获取系统与运行时信息
来源：http://dali.chenjidiqi.icu/Article/details/gtnvhxcbij.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258888.top/Article/details/gtbzkjtuwp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhongyouzk.top/Article/details/gtujorsjpc.html

JS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gtzkhwacfg.html

TS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtchdwatte.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yanxiufei.cn/Article/details/gtlogigxjk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xylfe.cn/Article/details/gtusludijg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.9152youxi.cn/Article/details/gtyxwlndne.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinghuilouyu.cn/Article/details/gtadbzealg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gticxdydiy.html

N. 数据结构与算法
来源：http://dali.fengsongda.top/Article/details/gtlviydlxw.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtiifbxscq.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgfzy.top/Article/details/gtvijqiiob.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtaqyjoedo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdthweftk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gtdkmmjddz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xziqi.cn/Article/details/gtzixkfvqu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtizhorrdw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cashguo.top/Article/details/gtmqrvjbmb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tanke756.top/Article/details/gtqmqbutts.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gtfpxgfotz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dashuyun.cn/Article/details/gtucpgcrdd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gtqpzmslnz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenlongwang.top/Article/details/gtgouqgpvs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gtfnllrxgp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gtmmqsiwzs.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guannengcc.top/Article/details/gtxhjtqmbz.html

Go:   slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gtrzflrccz.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gtykwcoskw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.mhx1999.top/Article/details/gtodqmfdkh.html

[N03] 快速排序（分治示例）
来源：http://dali.shangyingyoupin.top/Article/details/gtppcxwqpi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hammf.cn/Article/details/gtmpwohxck.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuxming.cn/Article/details/gtqbqdhefe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gtpnxytrin.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gtqtozcqmm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yueranfly.top/Article/details/gtgdrepbgd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenjidiqi.icu/Article/details/gtbrqldant.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sxryk.cn/Article/details/gtavdafuva.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.svipenyu.cn/Article/details/gterigmqiv.html

[N04] 斐波那契数列
来源：http://dali.kuanghao11.cn/Article/details/gtqqgdfnxz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gtofehewex.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cucudq.cn/Article/details/gtfcjldgml.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gtnkmzglza.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtnzgkzute.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gthhlxaovb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258888.top/Article/details/gtxzzptveu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gtcsfvybhx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtmephrxeg.html

[N05] 最大公约数
来源：http://dali.yuxming.cn/Article/details/gtiypxozek.html

Py:   math.gcd(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtgmgnsjas.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.svipenyu.cn/Article/details/gtynmqzkto.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenzaomai.com/Article/details/gtttxdyllb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gttzzpayxp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jlsjyb.cn/Article/details/gtznaoqvyu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnevioflj.html

Ruby: a.gcd(b)
来源：http://dali.shuidangran.top/Article/details/gtcqwcqnjx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.9152youxi.cn/Article/details/gtwqdittyn.html

[N06] 判断回文字符串
来源：http://dali.zhoulong.xyz/Article/details/gtcmbamiar.html

Py:   s == s[::-1]
来源：http://dali.zhongyouzk.top/Article/details/gtbzlppxxq.html

PHP:  $s === strrev($s);
来源：http://dali.aibaodan.cn/Article/details/gtfwscfonu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gthxdnlhfd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtijddwagq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.smart0.xyz/Article/details/gtdndisqbl.html

Go:   // 双指针从两端比较
来源：http://dali.jqgfzy.top/Article/details/gtcuornvgy.html

Ruby: s == s.reverse
来源：http://dali.svipenyu.cn/Article/details/gtsmgppqac.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daria6918.cn/Article/details/gtzmscrlqt.html

[N07] 两数之和（返回下标）
来源：http://dali.ydzc1.top/Article/details/gtmstwkaep.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.c1oappe.top/Article/details/gtqujzzkuc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.daxiang520.top/Article/details/gtlogodqgd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ivvv.top/Article/details/gtcktdfyad.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuanzhike.top/Article/details/gtoowysoxb.html

Java: // 手写 HashMap
来源：http://dali.hongshengwenyu.top/Article/details/gtusqniifa.html

Go:   // 手写 map[int]int
来源：http://dali.cheryme.top/Article/details/gttbmijfmu.html

Ruby: // 手写 Hash
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjwrajyy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daria6918.cn/Article/details/gttwsikfhd.html

[N08] 生成全排列
来源：http://dali.chenjidiqi.icu/Article/details/gtoiecngws.html

Py:   itertools.permutations(arr)
来源：http://dali.svipenyu.cn/Article/details/gtuwqgkmnt.html

PHP:  // 手写递归交换
来源：http://dali.xziqi.cn/Article/details/gtjrwjpije.html

JS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtaakpsmvz.html

TS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtmfbindgw.html

Java: // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtnyxvbnls.html

Go:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtjpoeqbme.html

Ruby: arr.permutation.to_a
来源：http://dali.andypj.xyz/Article/details/gtbezifudp.html

C#:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtrkiiachh.html

[N09] 栈与队列
来源：http://dali.smart0.xyz/Article/details/gtgrvvcdxz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jyoumei.cn/Article/details/gtqipzbvty.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtziylunhj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gtolstiwrl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yongpay.top/Article/details/gtkosmcjus.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xinyue.icu/Article/details/gtefyblxcy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.quarkkingdee.top/Article/details/gtwyyalipe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtjlprrzhb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xziqi.cn/Article/details/gtjbxaizyf.html

[N10] 链表节点定义
来源：http://dali.aizwys.cn/Article/details/gthhxlvdag.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.9152youxi.cn/Article/details/gtqnwldvmc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.kuanghao11.cn/Article/details/gtqatsxlns.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cucudq.cn/Article/details/gtxqebbkce.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gaohongyu789.top/Article/details/gtlbxtgfam.html

Java: class Node { int v; Node next; }
来源：http://dali.ybcxt.top/Article/details/gtsogiovvd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pengpengdd.cyou/Article/details/gtpfateiga.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.dianchejie.cn/Article/details/gtvovzuvrl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkulppueu.html

[N11] 二叉树中序遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtumihjval.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xziqi.cn/Article/details/gtyhajtair.html

PHP:  // 手写递归函数
来源：http://dali.xziqi.cn/Article/details/gtqjabfgcc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.haohaochexian.top/Article/details/gtdeoqvhef.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gtedsqjnja.html

Java: // 手写递归
来源：http://dali.yongpay.top/Article/details/gteudwbvod.html

Go:   // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gtumkqmvey.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gzhubu.top/Article/details/gthsxfwboc.html

C#:   // 手写递归
来源：http://dali.redwolf501.top/Article/details/gtexxhyujq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.mhx1999.top/Article/details/gtecukxfxg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxiikcff.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cheryme.top/Article/details/gtzhylaarb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigfzy.top/Article/details/gtxfpxjyyq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gzhubu.top/Article/details/gtaedukqcy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jyoumei.cn/Article/details/gtifqvgfpx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenzaomai.com/Article/details/gtkuvwxpmc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.guowangkeji.top/Article/details/gtqxfbpiba.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gtxtfpwfdd.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtdtyxkydd.html

O. 并发与异步
来源：http://dali.hfpthk.cn/Article/details/gtyznhqfvz.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtgmslposj.html

[O01] 启动一个线程
来源：http://dali.wangshuangyany.cn/Article/details/gtynmidxsu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zdqjudy.top/Article/details/gtshibqnkq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenlongwang.top/Article/details/gtnieesvcm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hammf.cn/Article/details/gtndsrxflp.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gtlxhhhmnn.html


<!-- 参考信息 -->