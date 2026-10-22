代发 wailian999

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.bjfxy.top/Article/details/gteovvhtry.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.haohaochexian.top/Article/details/gtiucllztz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shangyingyoupin.top/Article/details/gtlqfsugei.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.c1oappe.top/Article/details/gthrabniwk.html

[K06] 解析 URL 查询串
来源：http://dali.yueranfly.top/Article/details/gtsvwglxwd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fzhhl.top/Article/details/gtkrbbaxwb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.dashuyun.cn/Article/details/gtlddaufkj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gtcjpweozu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gtuuogmiaq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shzxlz.cn/Article/details/gtlkxvutkp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtfloyduzz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtvijywtua.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtkyqbhzco.html

[K07] 进制转换
来源：http://dali.guannengcc.top/Article/details/gticyokxxo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtkhapvlxa.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.0kj1m.cn/Article/details/gtrxcyxqqt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gteweojpgx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gttpnooskk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtsaglihkh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnqzz.top/Article/details/gtyfnbotkh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhixingplan.top/Article/details/gtbucobaen.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtpfzkmwts.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ppjwa.cn/Article/details/gtergukpoc.html

Py:   pickle.dumps(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtivzakqqx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccngeqfd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gtcltpokws.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gteeahnwud.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhongyouzk.top/Article/details/gtgqkiwsgl.html

Go:   encoding/gob
来源：http://dali.kuanghao11.cn/Article/details/gtdwukgahe.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gturzwurld.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gtljgjzwbf.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtryogxeur.html

L. 网络请求
来源：http://dali.fzhhl.top/Article/details/gtilfpqskx.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtcivbcurh.html

[L01] 发送 GET 请求
来源：http://dali.guannengcc.top/Article/details/gtxpkvxlmt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ydzc1.top/Article/details/gtzvdgjber.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxuanxn.top/Article/details/gtzkgmnsui.html

JS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gtakgrpdab.html

TS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gtricoqohm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwirkghen.html

Go:   resp, err := http.Get(url)
来源：http://dali.haohaochexian.top/Article/details/gtyptaxdpq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.redwolf501.top/Article/details/gtjsnizjnf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.dianchejie.cn/Article/details/gtixlltqsk.html

[L02] 发送 POST JSON
来源：http://dali.xylfe.cn/Article/details/gtnbyxcgbk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gthdexamkm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hongshengwenyu.top/Article/details/gtiffbicci.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gtzrnkmvuq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gtdeumtnrc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cashguo.top/Article/details/gtwacewhuw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gaohongyu789.top/Article/details/gtyospqpmu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sufxvd.cn/Article/details/gtrvlcpqqk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.pengpengdd.cyou/Article/details/gtxllbkfhs.html

[L03] 设置自定义请求头
来源：http://dali.nwbrower.top/Article/details/gtapivztwn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ehwqpu.com/Article/details/gtssozeaij.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cdnleiting.top/Article/details/gtvvfwuabr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gtvwpxgkqf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gtulsgnuiv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.bjfxy.top/Article/details/gtqyfgorwk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gtkqnaumgy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.andypj.xyz/Article/details/gttobkihst.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuceykfwr.html

[L04] 设置超时
来源：http://dali.andypj.xyz/Article/details/gtcffzhwsl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxmbibds.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hysaishi.cn/Article/details/gtpusofixd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gtjihpueds.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gtgkqdyxjr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258.top/Article/details/gtbcyspfmg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hongshengwenyu.top/Article/details/gtiwjalzvx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dianchejie.cn/Article/details/gtusxwjoze.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aibaodan.cn/Article/details/gtcnuqhvug.html

[L05] 上传文件（multipart）
来源：http://dali.svipenyu.cn/Article/details/gtjfgalqjk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cheryme.top/Article/details/gtltnuxamd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cqqwz.cn/Article/details/gtzxougicp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsyelcbnz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gtamlncrcq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shangyingyoupin.top/Article/details/gtlxtancxb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sysykeji.top/Article/details/gtqupnnerj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guannengcc.top/Article/details/gtgxjsywbo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtpwjrgkyw.html

[L06] 解析响应为 JSON
来源：http://dali.aizwys.cn/Article/details/gtjbcbgelx.html

Py:   resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtjtjviqoq.html

PHP:  json_decode($body, true);
来源：http://dali.daria6918.cn/Article/details/gtxpucsvfl.html

JS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gtctyjkvev.html

TS:   await resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtdjohkapp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258888.top/Article/details/gtezcxcuhb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cqqwz.cn/Article/details/gtxeplupgd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnroneru.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hammf.cn/Article/details/gtyhmyxmgn.html

[L07] 处理 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gtmxxtjsgu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cqqwz.cn/Article/details/gtouyucsrt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guannengcc.top/Article/details/gtmlfhxhoy.html

JS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gtdxnujccp.html

TS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gtsyjkfgka.html

Java: resp.statusCode()
来源：http://dali.haohaochexian.top/Article/details/gtuclfzsvd.html

Go:   resp.StatusCode
来源：http://dali.sufxvd.cn/Article/details/gtmmqrwplt.html

Ruby: resp.code.to_i
来源：http://dali.havefunace.top/Article/details/gtcsbwgcwy.html

C#:   (int)resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gtdhksklzc.html

[L08] 并发请求多个地址
来源：http://dali.jinqigufen.top/Article/details/gtsgruncdb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sxryk.cn/Article/details/gtzvggtglt.html

PHP:  curl_multi_init() 系列
来源：http://dali.mhx1999.top/Article/details/gttzzfexvy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gtxnagqzpx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtgrbaxcyf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ybcxt.top/Article/details/gtcutznrda.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sxryk.cn/Article/details/gtiwnbyjnd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sufxvd.cn/Article/details/gtzztbqvqr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuxming.cn/Article/details/gtxaxrdvuc.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtqqxphlzs.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangdashe.top/Article/details/gtqrvkktbw.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gthridkynq.html

[M01] 读取命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gteozisphw.html

Py:   sys.argv[1:]
来源：http://dali.yangfankeji.com/Article/details/gtriavcufa.html

PHP:  $argv;  $argc;
来源：http://dali.jqgfzy.top/Article/details/gtcettobxb.html

JS:   process.argv.slice(2)
来源：http://dali.daxiang520.top/Article/details/gtjpkxonzx.html

TS:   process.argv.slice(2)
来源：http://dali.jqgfzy.top/Article/details/gtmakuyxmz.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqljrodxm.html

Go:   os.Args[1:]
来源：http://dali.dianchejie.cn/Article/details/gtgiwbfihi.html

Ruby: ARGV
来源：http://dali.mhx1999.top/Article/details/gtkbkhchcj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtziejhctx.html

[M02] 读取环境变量
来源：http://dali.yongpay.top/Article/details/gtovcyjfmt.html

Py:   os.environ.get("HOME")
来源：http://dali.fengsongda.top/Article/details/gtbjmnhudp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtnmecxxus.html

JS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gtdowufkpg.html

TS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gtnsanwkeh.html

Java: System.getenv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gttxxxdhit.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtctnisetw.html

Ruby: ENV["HOME"]
来源：http://dali.birdmap.top/Article/details/gtrwgcmvxo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtweoievrq.html

[M03] 执行外部命令
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqrjjvbs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cdnleiting.top/Article/details/gtxapnvscl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.vqdsnc.cn/Article/details/gtkuwgnwhw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gtncctrbxf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gtocugjvaa.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenlongwang.top/Article/details/gtnkcrgqrr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gzhubu.top/Article/details/gtdxsjqdjp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gaohongyu789.top/Article/details/gtmrbtvjxx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigufen.top/Article/details/gtyxxbsakd.html

[M04] 获取当前工作目录
来源：http://dali.xylfe.cn/Article/details/gtydhdtfso.html

Py:   os.getcwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhyunhqf.html

PHP:  getcwd();
来源：http://dali.tian-w.cn/Article/details/gtntlihnns.html

JS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gtetcxuhsg.html

TS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gteuttzvup.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgihwbrcm.html

Go:   os.Getwd()
来源：http://dali.dashuyun.cn/Article/details/gtkmgjrcno.html

Ruby: Dir.pwd
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovgtcjos.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnxiangtu.top/Article/details/gtzmhnqiid.html

[M05] 设置退出码
来源：http://dali.yuanzhike.top/Article/details/gtaveeyqtm.html

Py:   sys.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtzphpykuw.html

PHP:  exit(1);
来源：http://dali.yuxming.cn/Article/details/gtppbwvczh.html

JS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtivvjbspm.html

TS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtiytltnmo.html

Java: System.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtiexvtejz.html

Go:   os.Exit(1)
来源：http://dali.yuxming.cn/Article/details/gtnhvxhxft.html

Ruby: exit 1
来源：http://dali.zhixingplan.top/Article/details/gtrgpdgssf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehvtarjf.html

[M06] 向标准错误输出
来源：http://dali.jqgufenzy.top/Article/details/gtwgfiprvr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258888.top/Article/details/gtnlbnfprn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.birdmap.top/Article/details/gtndwwxykr.html

JS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gtsdsusxdx.html

TS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gtrjkvmlip.html

Java: System.err.println("err")
来源：http://dali.redwolf501.top/Article/details/gtklmweaem.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwloxnkc.html

Ruby: warn "err"
来源：http://dali.gotoacloud.top/Article/details/gtwfsulxmx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sysykeji.top/Article/details/gthkewdnwr.html

[M07] 判断是否为主入口
来源：http://dali.cheryme.top/Article/details/gtxorbbaxk.html

Py:   if __name__ == "__main__":
来源：http://dali.yanxiufei.cn/Article/details/gtqhloslqo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fengsongda.top/Article/details/gtywysqfjc.html

JS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtwvqksrsh.html

TS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzttobfxx.html

Java: public static void main(String[] args)
来源：http://dali.gotoacloud.top/Article/details/gttqlhjwem.html

Go:   func main()
来源：http://dali.tian-w.cn/Article/details/gtghfuycvd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yanxiufei.cn/Article/details/gtvacdvblr.html

C#:   static void Main(string[] args)
来源：http://dali.hywenlv.cn/Article/details/gtbmlsbkwb.html

[M08] 获取系统与运行时信息
来源：http://dali.xylfe.cn/Article/details/gtfwdjoyen.html

Py:   platform.system();  platform.python_version()
来源：http://dali.svipenyu.cn/Article/details/gtuqgezhjb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.9152youxi.cn/Article/details/gthpmvzvae.html

JS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gtfwgywxbv.html

TS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gtkryzeraw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cqqwz.cn/Article/details/gtdmycomoh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guowangkeji.top/Article/details/gtrstojnwx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ybcxt.top/Article/details/gtocolzbeh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplleilwx.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtviukdrcg.html

N. 数据结构与算法
来源：http://dali.zhengqikj.top/Article/details/gtdmhufaeb.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxeereau.html

[N01] 二分查找（有序数组）
来源：http://dali.aibaodan.cn/Article/details/gtahlwtqjo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtdigoksof.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtpaxvmnnd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.svipenyu.cn/Article/details/gtvnaevmjs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtirpthmyg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtgtqbznxr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.smart0.xyz/Article/details/gttfxunrve.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiizbqnlf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gtbkzqzyea.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnxiangtu.top/Article/details/gtaxxqpufa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gtzkbqdphb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.bjfxy.top/Article/details/gtwhaxplgx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gtwxghlyzj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gtyzrcqjgf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjskwbqqr.html

Go:   slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gtfdutufcq.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gtduxfnawh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258.top/Article/details/gtihdtwahs.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigufen.top/Article/details/gtaptxjprw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gogol.net.cn/Article/details/gtqmheterj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangdashe.top/Article/details/gtovfuakpt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gtyayahpac.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gtighindqb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.0kj1m.cn/Article/details/gtltpkqkxh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hfpthk.cn/Article/details/gtekvgkcwo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yuanzhike.top/Article/details/gtqarkuiox.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yvedp.cn/Article/details/gtnopkfxwf.html

[N04] 斐波那契数列
来源：http://dali.sysykeji.top/Article/details/gtlhzmxwju.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.0kj1m.cn/Article/details/gthkhcgstg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gtfrpnxgjk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtyopdikai.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtrzyqvrza.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258888.top/Article/details/gtytldtkam.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenzaomai.com/Article/details/gtgivyghwu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtgrysddfh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtcphbvfbs.html

[N05] 最大公约数
来源：http://dali.gzhubu.top/Article/details/gtfrtvpwvy.html

Py:   math.gcd(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzuhxjaba.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhengqikj.top/Article/details/gtqlzroahs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ppjwa.cn/Article/details/gtxlqvyrza.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtukkienez.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fengsongda.top/Article/details/gticrgfszr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cheryme.top/Article/details/gtjsgjiwoh.html

Ruby: a.gcd(b)
来源：http://dali.yuanzhike.top/Article/details/gtwxlamxbh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwmhobhy.html

[N06] 判断回文字符串
来源：http://dali.chenlongwang.top/Article/details/gtunwzbqjv.html

Py:   s == s[::-1]
来源：http://dali.meibo888.top/Article/details/gtxmcrnyeq.html

PHP:  $s === strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gtjfqsycdc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtnyawqvfq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtscgsomhe.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ehwqpu.com/Article/details/gttvnpmdyl.html

Go:   // 双指针从两端比较
来源：http://dali.fengsongda.top/Article/details/gtlxskrfuh.html

Ruby: s == s.reverse
来源：http://dali.yj202588.top/Article/details/gtphnpeyrd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gtzbiccehk.html

[N07] 两数之和（返回下标）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhmsusqb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.andypj.xyz/Article/details/gtsalrzdjs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pengpengdd.cyou/Article/details/gtxfqleint.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sxryk.cn/Article/details/gtrtzwkcig.html

TS:   // 手写 Map<string, number>
来源：http://dali.sweek.top/Article/details/gtgwqvunvb.html

Java: // 手写 HashMap
来源：http://dali.yuxming.cn/Article/details/gtfihxbqxv.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfmqcqfz.html

Ruby: // 手写 Hash
来源：http://dali.hnxiangtu.top/Article/details/gtofhmynjz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aizwys.cn/Article/details/gtterdtjdk.html

[N08] 生成全排列
来源：http://dali.guannengcc.top/Article/details/gtekjgvcfi.html

Py:   itertools.permutations(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtutfgymvb.html

PHP:  // 手写递归交换
来源：http://dali.cdnleiting.top/Article/details/gtgcbfuhqg.html

JS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtwmyekovr.html

TS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtzjqgbenc.html

Java: // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtuenobget.html

Go:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtjfljgzel.html

Ruby: arr.permutation.to_a
来源：http://dali.redwolf501.top/Article/details/gtovkgxour.html

C#:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtsccedefd.html

[N09] 栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gtvkmbxjws.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jyoumei.cn/Article/details/gtfcdtbfbg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yongpay.top/Article/details/gtwcpbshcm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtamlyrtxl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jlsjyb.cn/Article/details/gtgfawwchk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.iojbl.cn/Article/details/gtpgkgbrhv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hywenlv.cn/Article/details/gtyefkiasq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtrmoqbmch.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jianghu66.top/Article/details/gtqnhrskot.html

[N10] 链表节点定义
来源：http://dali.chenjidiqi.icu/Article/details/gtoumhnuud.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenlongwang.top/Article/details/gtzhuvbjbn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yangfankeji.com/Article/details/gtzxfajzkc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hywenlv.cn/Article/details/gtrygrhmps.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.316326.xyz/Article/details/gttlxkptdv.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxyycvzt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ppjwa.cn/Article/details/gtcemtvvdi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgfzy.top/Article/details/gtlokjuvww.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.haohaochexian.top/Article/details/gtcdbhwomu.html

[N11] 二叉树中序遍历
来源：http://dali.zhoulong.xyz/Article/details/gtchzxibhb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenjidiqi.icu/Article/details/gtirzrbujl.html

PHP:  // 手写递归函数
来源：http://dali.jqgufenzy.top/Article/details/gtawlglqon.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gtcbehaspz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfqbhupy.html

Java: // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gtqolgmznf.html

Go:   // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gtppowaxok.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shuidangran.top/Article/details/gthtojprny.html

C#:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrinmmkap.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yanxiufei.cn/Article/details/gtozsirakf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxhufoxk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hnxiangtu.top/Article/details/gtlrdybqdp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gtbsxyicjx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gtxtnwbrgf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gtmwetlpbv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.redwolf501.top/Article/details/gtkykrhitt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.meibo888.top/Article/details/gtkwklzkbv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gtaedtzivu.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtmjmjroea.html

O. 并发与异步
来源：http://dali.fzhhl.top/Article/details/gtmkwvbasp.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjygqpls.html

[O01] 启动一个线程
来源：http://dali.dianchejie.cn/Article/details/gtvxsshzqb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hywenlv.cn/Article/details/gtzxhgxkhd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zycfv.cn/Article/details/gtefbizsty.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xinyue.icu/Article/details/gttvyudwak.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gtshtkcujh.html


<!-- 参考信息 -->