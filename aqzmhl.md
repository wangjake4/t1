代发 wailian999

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtzpmrwkbo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fzhhl.top/Article/details/gtfrxralwg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtsstkvelx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gtbgaclabs.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtaynehhwz.html

[K07] 进制转换
来源：http://dali.sufxvd.cn/Article/details/gtctcuzmmf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtdppvoqgk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hfpthk.cn/Article/details/gtighnbktg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtfbnktsug.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtzkuwpynt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtumadweuo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.9152youxi.cn/Article/details/gtapjkdjnv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gaohongyu789.top/Article/details/gtujlqsaqw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gteswqsuzb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hysaishi.cn/Article/details/gtksisvldx.html

Py:   pickle.dumps(obj)
来源：http://dali.snrcjt.cn/Article/details/gtocjmrhhe.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.quarkkingdee.top/Article/details/gtevxedghd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gtfjwdvvjh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gtcotkhmjz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuuwtaugk.html

Go:   encoding/gob
来源：http://dali.vqdsnc.cn/Article/details/gttssqtvhj.html

Ruby: Marshal.dump(obj)
来源：http://dali.tianlin.xyz/Article/details/gtzwxtbvyt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gtbzvkpguu.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtlbphtvip.html

L. 网络请求
来源：http://dali.hongshengwenyu.top/Article/details/gthrdxuesn.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gttpheqmps.html

[L01] 发送 GET 请求
来源：http://dali.fzhhl.top/Article/details/gtxsmwwlgf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tian-w.cn/Article/details/gtimlwrqph.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ehwqpu.com/Article/details/gtcxjnizjc.html

JS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtmhxgemny.html

TS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gtmqwnjrsh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnqzz.top/Article/details/gtegpgmbub.html

Go:   resp, err := http.Get(url)
来源：http://dali.fzhhl.top/Article/details/gtwhdtcpfk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cashguo.top/Article/details/gtqmrexhhr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhengqikj.top/Article/details/gtqavgiehr.html

[L02] 发送 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gtrjjkuluz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuanzx.com/Article/details/gtnnpgxsfa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jianghu66.top/Article/details/gtpizlwgzh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gtbtjkeogw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gtmfknduow.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.kuanghao11.cn/Article/details/gtlgnaujvu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nwbrower.top/Article/details/gtoeukktly.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangtech.top/Article/details/gtijmdysah.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guannengcc.top/Article/details/gtvnqcbxqa.html

[L03] 设置自定义请求头
来源：http://dali.zhoulong.xyz/Article/details/gtlayfkkul.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgfzy.top/Article/details/gtdvcsfadd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jiagoushi.top/Article/details/gtkrtmcuwy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gtjlhdwyld.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtyzfpkooj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jyoumei.cn/Article/details/gtvryzssqe.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gtxluljyrv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxydgszc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gtkuaszmqu.html

[L04] 设置超时
来源：http://dali.xuanzx.com/Article/details/gtgllzdbim.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxinkj.top/Article/details/gtfnexctoc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jyoumei.cn/Article/details/gtytpyspnn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gtlqsrwynt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gtnarewrpk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenlongwang.top/Article/details/gthkwnbiea.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guowangkeji.top/Article/details/gtstayasjw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.svipenyu.cn/Article/details/gtktuytsdb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.mhx1999.top/Article/details/gtxctfimsx.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigfzy.top/Article/details/gtwixgbmtt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cheryme.top/Article/details/gtrbxbwpmz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhixingplan.top/Article/details/gtropixtnm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gtaqtyhfow.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gtnsaqzcby.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zdqjudy.top/Article/details/gtuvbllxac.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenjidiqi.icu/Article/details/gtesvchehj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.birdmap.top/Article/details/gtbadumart.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtszkrsokj.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehcuydki.html

Py:   resp.json()
来源：http://dali.snrcjt.cn/Article/details/gteevucqir.html

PHP:  json_decode($body, true);
来源：http://dali.gotoacloud.top/Article/details/gtmnhflhfa.html

JS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtnrrcppth.html

TS:   await resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gtyskumntl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.mhx1999.top/Article/details/gtkwbwioek.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.birdmap.top/Article/details/gtnxhyvawf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yueranfly.top/Article/details/gtgbkixcod.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.mhx1999.top/Article/details/gtulovynni.html

[L07] 处理 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gttlmvangi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tian-w.cn/Article/details/gtfixuvfgy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhengqikj.top/Article/details/gtgmhesjcg.html

JS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gtkjhdangm.html

TS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gthahcwdxh.html

Java: resp.statusCode()
来源：http://dali.iojbl.cn/Article/details/gtcypdzxmm.html

Go:   resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtmsjcvdkm.html

Ruby: resp.code.to_i
来源：http://dali.yonumen.top/Article/details/gtphriugfm.html

C#:   (int)resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gtnvbbcpbw.html

[L08] 并发请求多个地址
来源：http://dali.zdqjudy.top/Article/details/gtwazeeygr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sxryk.cn/Article/details/gtjbxqhcdn.html

PHP:  curl_multi_init() 系列
来源：http://dali.dashuyun.cn/Article/details/gtqcvqizpa.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gttnqdwksh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtjaiixzes.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxuanxn.top/Article/details/gtmqwrtlcg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.c1oappe.top/Article/details/gtdwpykizy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jyoumei.cn/Article/details/gtjlyhvgqg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxinkj.top/Article/details/gtovstsqox.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtnzfogldb.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjtisipv.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtrszpvjcn.html

[M01] 读取命令行参数
来源：http://dali.snrcjt.cn/Article/details/gttmsphjgj.html

Py:   sys.argv[1:]
来源：http://dali.gotoacloud.top/Article/details/gtfholmxxe.html

PHP:  $argv;  $argc;
来源：http://dali.hfpthk.cn/Article/details/gtsxbadzkq.html

JS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gteqcmvrop.html

TS:   process.argv.slice(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtjunfjrpq.html

Java: args 数组（main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtlmjvayav.html

Go:   os.Args[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuyyafwhn.html

Ruby: ARGV
来源：http://dali.ydzc1.top/Article/details/gtfotpnhho.html

C#:   args 数组（Main 方法参数）
来源：http://dali.meibo888.top/Article/details/gtnvppeedn.html

[M02] 读取环境变量
来源：http://dali.guowangkeji.top/Article/details/gtpbwnetfk.html

Py:   os.environ.get("HOME")
来源：http://dali.hammf.cn/Article/details/gtmxwkhriw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gtrxwapknf.html

JS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gtdgbjtflv.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gtecrxuzpa.html

Java: System.getenv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtnvmgxwno.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sysykeji.top/Article/details/gtlgjweoqv.html

Ruby: ENV["HOME"]
来源：http://dali.cdnleiting.top/Article/details/gtyeghknde.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtvctfihdl.html

[M03] 执行外部命令
来源：http://dali.haohaochexian.top/Article/details/gtoxgagrog.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclgsjxzm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenlongwang.top/Article/details/gtaaxugpnu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtwtbsmkdb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sufxvd.cn/Article/details/gtonssmrmk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cheryme.top/Article/details/gtwchtqhha.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xylfe.cn/Article/details/gtorfryiss.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sxryk.cn/Article/details/gtrlfezztb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhengqikj.top/Article/details/gtgszregtb.html

[M04] 获取当前工作目录
来源：http://dali.ehwqpu.com/Article/details/gtomfopjhq.html

Py:   os.getcwd()
来源：http://dali.tanke756.top/Article/details/gtauqppaaf.html

PHP:  getcwd();
来源：http://dali.ehwqpu.com/Article/details/gthabinlfb.html

JS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gtsrytutln.html

TS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gtpilozyhr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zycfv.cn/Article/details/gteqawcagl.html

Go:   os.Getwd()
来源：http://dali.9152youxi.cn/Article/details/gtxmjocpkw.html

Ruby: Dir.pwd
来源：http://dali.zdqjudy.top/Article/details/gtsxwamdcl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuxming.cn/Article/details/gtkinrhkpo.html

[M05] 设置退出码
来源：http://dali.dianchejie.cn/Article/details/gtupaqeexj.html

Py:   sys.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtatdjfscn.html

PHP:  exit(1);
来源：http://dali.sysykeji.top/Article/details/gtvvkaektr.html

JS:   process.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndrnkmhs.html

TS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtjjzeogoh.html

Java: System.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtaelmekip.html

Go:   os.Exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtrunkpadq.html

Ruby: exit 1
来源：http://dali.ydzc1.top/Article/details/gttxnibqiq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.feifeiyinyue.top/Article/details/gtsttngvft.html

[M06] 向标准错误输出
来源：http://dali.yongpay.top/Article/details/gtpvbghsid.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj202588.top/Article/details/gthfyziivs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jlsjyb.cn/Article/details/gtyxzpzydh.html

JS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gtkpokxcfp.html

TS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gtlpnarpxl.html

Java: System.err.println("err")
来源：http://dali.cucudq.cn/Article/details/gtilyronze.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hongshengwenyu.top/Article/details/gtoyyhyfvg.html

Ruby: warn "err"
来源：http://dali.shanyushiyangtech.top/Article/details/gtggswmjck.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.havefunace.top/Article/details/gtmegxjwvw.html

[M07] 判断是否为主入口
来源：http://dali.gaohongyu789.top/Article/details/gtzbdozpcy.html

Py:   if __name__ == "__main__":
来源：http://dali.guannengcc.top/Article/details/gtdwpwyguh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhoulong.xyz/Article/details/gtwkfiprta.html

JS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gtzeuhgtbt.html

TS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlahzyviq.html

Java: public static void main(String[] args)
来源：http://dali.snrcjt.cn/Article/details/gternlqoum.html

Go:   func main()
来源：http://dali.zhiwuduotai.top/Article/details/gtxjxklxjn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgfzy.top/Article/details/gtmdnakigw.html

C#:   static void Main(string[] args)
来源：http://dali.ehwqpu.com/Article/details/gtbojfpbgv.html

[M08] 获取系统与运行时信息
来源：http://dali.havefunace.top/Article/details/gtpoyjnbni.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hongshengwenyu.top/Article/details/gtwbordizv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuanzhike.top/Article/details/gtzgupglge.html

JS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gtzlydqxvm.html

TS:   process.platform;  process.version
来源：http://dali.zhixingplan.top/Article/details/gtwucbbqot.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxuanxn.top/Article/details/gtpnhxggps.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdulrwyu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hysaishi.cn/Article/details/gtsycfivmi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangshuangyany.cn/Article/details/gtaqokytrm.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtdcasktib.html

N. 数据结构与算法
来源：http://dali.andypj.xyz/Article/details/gtsiyvxvtg.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtvabllliq.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gtqlcfvids.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrevwznr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xziqi.cn/Article/details/gtezpuctkt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gttpwdwyid.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtroowripb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cheryme.top/Article/details/gttubsvnhv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtvbpcbrfh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gaohongyu789.top/Article/details/gtjqcwjdpa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gthywwnhri.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daxiang520.top/Article/details/gtmyrxaheh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gthwsnbupe.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzzqnoqs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gtjkurzsjl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtzvxrexxm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daxiang520.top/Article/details/gtpsvxghay.html

Go:   slices.Sort(arr)
来源：http://dali.xylfe.cn/Article/details/gtkvnabltv.html

Ruby: arr.sort
来源：http://dali.hfpthk.cn/Article/details/gtuckcdapy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shzxlz.cn/Article/details/gtbdkzpwrz.html

[N03] 快速排序（分治示例）
来源：http://dali.haohaochexian.top/Article/details/gthbunoort.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzjpjfke.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pengpengdd.cyou/Article/details/gtmoucppyt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gtyrbkrvun.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gtktyvrdzf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.andypj.xyz/Article/details/gtrpsmuocb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yanxiufei.cn/Article/details/gtpfoynqef.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tian-w.cn/Article/details/gtzuzfqyqa.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sufxvd.cn/Article/details/gtulvxheql.html

[N04] 斐波那契数列
来源：http://dali.sxryk.cn/Article/details/gtvvaupgjx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gtezaenask.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtckzdmxxg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtfcmpfqjk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gtflbuizez.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj202588.top/Article/details/gtbiricoiz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jlsjyb.cn/Article/details/gtadndltkh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gtpcdmvsep.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtfqrracyd.html

[N05] 最大公约数
来源：http://dali.svipenyu.cn/Article/details/gtrskausmt.html

Py:   math.gcd(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gttczaizne.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gthezjbppp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxuanxn.top/Article/details/gtinsdmrvl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ydzc1.top/Article/details/gtikpiattp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gotoacloud.top/Article/details/gtlirsaphi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqewbpisc.html

Ruby: a.gcd(b)
来源：http://dali.nanxuanxn.top/Article/details/gtnnjsvnli.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhengqikj.top/Article/details/gtabwcwrmi.html

[N06] 判断回文字符串
来源：http://dali.tanke756.top/Article/details/gtrhjyryxv.html

Py:   s == s[::-1]
来源：http://dali.andypj.xyz/Article/details/gtdqxyijxo.html

PHP:  $s === strrev($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtesbbghzp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gthfthkyhe.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtacysmykc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yonumen.top/Article/details/gtwnnsdjwz.html

Go:   // 双指针从两端比较
来源：http://dali.9152youxi.cn/Article/details/gtprvdhfbl.html

Ruby: s == s.reverse
来源：http://dali.zhengqikj.top/Article/details/gtthxxzxkh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gtumwwknjw.html

[N07] 两数之和（返回下标）
来源：http://dali.sweek.top/Article/details/gtfhiemyil.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbmybjdh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shzxlz.cn/Article/details/gttdaxypbe.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hongshengwenyu.top/Article/details/gtlrxukgey.html

TS:   // 手写 Map<string, number>
来源：http://dali.hywenlv.cn/Article/details/gtmwcgnosf.html

Java: // 手写 HashMap
来源：http://dali.shangyingyoupin.top/Article/details/gtebnfhdit.html

Go:   // 手写 map[int]int
来源：http://dali.hongshengwenyu.top/Article/details/gtcbeomrky.html

Ruby: // 手写 Hash
来源：http://dali.sweek.top/Article/details/gtdregocet.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tanke756.top/Article/details/gtbyycahup.html

[N08] 生成全排列
来源：http://dali.pengpengdd.cyou/Article/details/gtqwuumwst.html

Py:   itertools.permutations(arr)
来源：http://dali.haohaochexian.top/Article/details/gtqsvqcwwh.html

PHP:  // 手写递归交换
来源：http://dali.9152youxi.cn/Article/details/gtpzrxcqzv.html

JS:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtpkjtflfc.html

TS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtqpdornhj.html

Java: // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtgsyczphi.html

Go:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtmziosozc.html

Ruby: arr.permutation.to_a
来源：http://dali.redwolf501.top/Article/details/gtvqvicayy.html

C#:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtyaqbyfts.html

[N09] 栈与队列
来源：http://dali.jinqigufen.top/Article/details/gtevlwfouw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cheryme.top/Article/details/gtqqhxtgze.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gtgkaqfwev.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gtghcbywfn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.feifeiyinyue.top/Article/details/gtdrnvewvw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gtimaimjns.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jqgufenzy.top/Article/details/gtbtjoxkso.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtrtobgbmp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcadiolq.html

[N10] 链表节点定义
来源：http://dali.cdnleiting.top/Article/details/gtcapgkawx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.9152youxi.cn/Article/details/gtxwzbsfjw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.daria6918.cn/Article/details/gtbyrgzqxt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ehwqpu.com/Article/details/gttdhelhzp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.andypj.xyz/Article/details/gtfersqgmo.html

Java: class Node { int v; Node next; }
来源：http://dali.yuxming.cn/Article/details/gtamgnfvxm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hfpthk.cn/Article/details/gteserzvwb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.0kj1m.cn/Article/details/gtksjvzurq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgfzy.top/Article/details/gttkjujutr.html

[N11] 二叉树中序遍历
来源：http://dali.haohaochexian.top/Article/details/gtmrcklhkj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj202588.top/Article/details/gttkvjsywg.html

PHP:  // 手写递归函数
来源：http://dali.ehwqpu.com/Article/details/gtvrwwupqz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ehwqpu.com/Article/details/gtukmppsxe.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gtzbumjsar.html

Java: // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gtffmxcpvw.html

Go:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gtfgyvpdgy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.svipenyu.cn/Article/details/gtvnbykcyu.html

C#:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtsyoedlwl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj202588.top/Article/details/gtlppiynac.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sufxvd.cn/Article/details/gtlpantzna.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbcldfub.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gtietwhobq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sweek.top/Article/details/gttnuqursg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gaohongyu789.top/Article/details/gtpetecxpm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhiwuduotai.top/Article/details/gtavaovuht.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zycfv.cn/Article/details/gtsmekwfns.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gtbdfchcas.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtrenalcwm.html

O. 并发与异步
来源：http://dali.feifeiyinyue.top/Article/details/gtpsriepxb.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtscwxbjor.html

[O01] 启动一个线程
来源：http://dali.hammf.cn/Article/details/gtlfhuyjqb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhoulong.xyz/Article/details/gtpprgbwll.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.haohaochexian.top/Article/details/gtvcjkytoz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sxryk.cn/Article/details/gtzjsjihnh.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gtqnfwiond.html

Java: new Thread(() -> f()).start()
来源：http://dali.shangyingyoupin.top/Article/details/gtkvxqxofw.html

Go:   go f()
来源：http://dali.shangyingyoupin.top/Article/details/gtypnibuvy.html

Ruby: Thread.new { f }
来源：http://dali.pycfn.com/Article/details/gtggtzkukk.html

C#:   Task.Run(() => F());
来源：http://dali.fzhhl.top/Article/details/gtwuasvumu.html

[O02] 使用线程池
来源：http://dali.jlsjyb.cn/Article/details/gtbkjlemsq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.smart0.xyz/Article/details/gtoovvzxhm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtythusgda.html

JS:   // worker_threads 线程池
来源：http://dali.zdqjudy.top/Article/details/gtszonhuxh.html


<!-- 参考信息 -->