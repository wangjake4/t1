代发 wailian999

[K06] 解析 URL 查询串
来源：http://dali.mhx1999.top/Article/details/gt2njdjgykk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gt2gmnelsij.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guowangkeji.top/Article/details/gt2rdynadbn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gt2cecsqdmr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gt2sjysgnqr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj202588.top/Article/details/gt2mrglcdgz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gt2khmbtbls.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gt2kczxnvbk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2sktaqzoj.html

[K07] 进制转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2xxbfpdek.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2umdqelbj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwaulva.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2priweqem.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2qluruyxf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2eyqrxdwg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guannengcc.top/Article/details/gt2oqzcncbr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pmdsxpnw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gt2mrrjfnne.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jyoumei.cn/Article/details/gt2hsdxdilk.html

Py:   pickle.dumps(obj)
来源：http://dali.fengsongda.top/Article/details/gt2xdewtlfl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yvedp.cn/Article/details/gt2xoqwspjz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gt2vpdselto.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gt2hvyvzkeu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.0kj1m.cn/Article/details/gt2bmzdfkao.html

Go:   encoding/gob
来源：http://dali.nanxuanxn.top/Article/details/gt2zalffowv.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2coganhtv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gt2bapcyher.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2kowzuzlr.html

L. 网络请求
来源：http://dali.guowangkeji.top/Article/details/gt2vmtbxmux.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ymqvrwop.html

[L01] 发送 GET 请求
来源：http://dali.ivvv.top/Article/details/gt2nveegcgs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fzhhl.top/Article/details/gt2snxlwqge.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sweek.top/Article/details/gt2czxikbuv.html

JS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gt2pduseiqw.html

TS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gt2ywewirxr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xylfe.cn/Article/details/gt2aqkwzqdu.html

Go:   resp, err := http.Get(url)
来源：http://dali.ivvv.top/Article/details/gt2ibrzbqku.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guannengcc.top/Article/details/gt2sfulsyzs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fgmyoncg.html

[L02] 发送 POST JSON
来源：http://dali.0kj1m.cn/Article/details/gt2avhucfzi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gt2wanssnyt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuanzx.com/Article/details/gt2hrfirbek.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2awpdoomc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gt2xfdecmss.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.havefunace.top/Article/details/gt2vafwhzfc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.quarkkingdee.top/Article/details/gt2kilzxucw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.iojbl.cn/Article/details/gt2fqadbrwj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhoulong.xyz/Article/details/gt2rppgyxyt.html

[L03] 设置自定义请求头
来源：http://dali.yonumen.top/Article/details/gt2qflionwo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ivvv.top/Article/details/gt2rmdkqrfg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2dtptxwkb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daxiang520.top/Article/details/gt2vnjxfpvh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gt2gpzbdtmn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhixingplan.top/Article/details/gt2rimvtfvw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pycfn.com/Article/details/gt2lhrrllgf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hywenlv.cn/Article/details/gt2qeqkogel.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gt2ctbrorrx.html

[L04] 设置超时
来源：http://dali.nanxinkj.top/Article/details/gt2hdraacyq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shzxlz.cn/Article/details/gt2srrtlfdc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sufxvd.cn/Article/details/gt2kpbtawiq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gt2qdlcipuw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gt2srpqmfjb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dianchejie.cn/Article/details/gt2vdwvbitt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yhfqglrn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.feifeiyinyue.top/Article/details/gt2eomeblmg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.c1oappe.top/Article/details/gt2bwsjmgfj.html

[L05] 上传文件（multipart）
来源：http://dali.xuanzx.com/Article/details/gt2bmhrfegk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.smart0.xyz/Article/details/gt2zvnwycyz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2cefzjocr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gt2adnvxsbe.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gt2ezuamosr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.c1oappe.top/Article/details/gt2leggxfmd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sufxvd.cn/Article/details/gt2pufmicsf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.haohaochexian.top/Article/details/gt2vlwdbfqs.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yonumen.top/Article/details/gt2rgvwuefh.html

[L06] 解析响应为 JSON
来源：http://dali.zycfv.cn/Article/details/gt2ameorakt.html

Py:   resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xagwplff.html

PHP:  json_decode($body, true);
来源：http://dali.aibaodan.cn/Article/details/gt2scfkwxbe.html

JS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gt2dmscgqvj.html

TS:   await resp.json()
来源：http://dali.meibo888.top/Article/details/gt2tzoiremb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gt2prurzfhj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.vqdsnc.cn/Article/details/gt2bfcalpbj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ehwqpu.com/Article/details/gt2efxtkiaj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bgzkbapv.html

[L07] 处理 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gt2wgyqyxfj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zycfv.cn/Article/details/gt2znsazvoa.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258.top/Article/details/gt2iffxfcfd.html

JS:   resp.ok;  resp.status
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ytomgpvy.html

TS:   resp.ok;  resp.status
来源：http://dali.nwbrower.top/Article/details/gt2ttwjjtig.html

Java: resp.statusCode()
来源：http://dali.jqgfzy.top/Article/details/gt2zsxnunng.html

Go:   resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gt2umqylcks.html

Ruby: resp.code.to_i
来源：http://dali.tianlin.xyz/Article/details/gt2hxsztylu.html

C#:   (int)resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gt2atazsmmh.html

[L08] 并发请求多个地址
来源：http://dali.iojbl.cn/Article/details/gt2emtpembm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ybcxt.top/Article/details/gt2tqurwkcf.html

PHP:  curl_multi_init() 系列
来源：http://dali.quarkkingdee.top/Article/details/gt2rnmocfdb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gt2bxturgce.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gt2zqgspuvy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.redwolf501.top/Article/details/gt2ykzdggie.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ybcxt.top/Article/details/gt2cmyjnims.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gogol.net.cn/Article/details/gt2yabkmuzc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tian-w.cn/Article/details/gt2aloazrgc.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2dawvossb.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgfzy.top/Article/details/gt2nuqksplw.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2vjiydovg.html

[M01] 读取命令行参数
来源：http://dali.dianchejie.cn/Article/details/gt2dspjpfzd.html

Py:   sys.argv[1:]
来源：http://dali.sysykeji.top/Article/details/gt2kcobttcw.html

PHP:  $argv;  $argc;
来源：http://dali.bjfxy.top/Article/details/gt2ffvdbycj.html

JS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gt2axrimjqm.html

TS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gt2xbkbsijc.html

Java: args 数组（main 方法参数）
来源：http://dali.316326.xyz/Article/details/gt2bjfkrjkx.html

Go:   os.Args[1:]
来源：http://dali.gzhubu.top/Article/details/gt2jedcddvd.html

Ruby: ARGV
来源：http://dali.sysykeji.top/Article/details/gt2ymqkwnum.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gt2riqfvxkl.html

[M02] 读取环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kdoycwnv.html

Py:   os.environ.get("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gt2bljpvbwb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gt2gpwfdeyo.html

JS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gt2iwahbfbw.html

TS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gt2tdyqxpnd.html

Java: System.getenv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2xnzhvxfk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xziqi.cn/Article/details/gt2fzjnnwwz.html

Ruby: ENV["HOME"]
来源：http://dali.vqdsnc.cn/Article/details/gt2addhlyfw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tanke756.top/Article/details/gt2ncjfddos.html

[M03] 执行外部命令
来源：http://dali.ydzc1.top/Article/details/gt2zaiouusq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daria6918.cn/Article/details/gt2ywwlbyys.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hongshengwenyu.top/Article/details/gt2wmufkbxs.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gt2twnyupwm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gt2pyntdxgn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gogol.net.cn/Article/details/gt2ygijqpfz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.haohaochexian.top/Article/details/gt2cuxiwatx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hfpthk.cn/Article/details/gt2ztsqqhyq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guannengcc.top/Article/details/gt2equwhidb.html

[M04] 获取当前工作目录
来源：http://dali.pycfn.com/Article/details/gt2vjbvscfg.html

Py:   os.getcwd()
来源：http://dali.guannengcc.top/Article/details/gt2yyhosrcm.html

PHP:  getcwd();
来源：http://dali.quarkkingdee.top/Article/details/gt2gedafmsg.html

JS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gt2xybeytko.html

TS:   process.cwd()
来源：http://dali.yj20258888.top/Article/details/gt2icbuakfy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.quarkkingdee.top/Article/details/gt2fbatkblc.html

Go:   os.Getwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ndxjcfwm.html

Ruby: Dir.pwd
来源：http://dali.yj20258.top/Article/details/gt2qbfbkdfu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dianchejie.cn/Article/details/gt2yrxmcnqf.html

[M05] 设置退出码
来源：http://dali.meibo888.top/Article/details/gt2uzagedcu.html

Py:   sys.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2exfvyssx.html

PHP:  exit(1);
来源：http://dali.snrcjt.cn/Article/details/gt2iwmxzxsr.html

JS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2mztjljur.html

TS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xlnxajhh.html

Java: System.exit(1)
来源：http://dali.gzhubu.top/Article/details/gt2cfyfhgpx.html

Go:   os.Exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2fwmysybn.html

Ruby: exit 1
来源：http://dali.daria6918.cn/Article/details/gt2qyklwtvc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj202588.top/Article/details/gt2ocvwikbg.html

[M06] 向标准错误输出
来源：http://dali.vqdsnc.cn/Article/details/gt2sijptkgm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ydzc1.top/Article/details/gt2xspnciwo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gzhubu.top/Article/details/gt2ladubquo.html

JS:   console.error("err")
来源：http://dali.haohaochexian.top/Article/details/gt2prhpuuub.html

TS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gt2ejzlhtlg.html

Java: System.err.println("err")
来源：http://dali.kuanghao11.cn/Article/details/gt2hhmbvjkc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ehwqpu.com/Article/details/gt2bywofikm.html

Ruby: warn "err"
来源：http://dali.0kj1m.cn/Article/details/gt2uyxniiuw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sxryk.cn/Article/details/gt2pwtpwffv.html

[M07] 判断是否为主入口
来源：http://dali.9152youxi.cn/Article/details/gt2zzktpxiq.html

Py:   if __name__ == "__main__":
来源：http://dali.0kj1m.cn/Article/details/gt2vlcucpnk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.andypj.xyz/Article/details/gt2prgxmztc.html

JS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gt2atdttdyr.html

TS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gt2emytclmc.html

Java: public static void main(String[] args)
来源：http://dali.cashguo.top/Article/details/gt2igokjdhq.html

Go:   func main()
来源：http://dali.zhengqikj.top/Article/details/gt2osppxwub.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj20258888.top/Article/details/gt2ozecqnjf.html

C#:   static void Main(string[] args)
来源：http://dali.yonumen.top/Article/details/gt2zzhkbyqa.html

[M08] 获取系统与运行时信息
来源：http://dali.bjfxy.top/Article/details/gt2ggaqwkyw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guowangkeji.top/Article/details/gt2nppypxik.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.svipenyu.cn/Article/details/gt2grvuavpa.html

JS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gt2cdbznxsq.html

TS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gt2veyjxrxo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gt2ogskdwjm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhongyouzk.top/Article/details/gt2rbpyouhl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xylfe.cn/Article/details/gt2ezjmanat.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhongyouzk.top/Article/details/gt2pxmirpgg.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tlinudit.html

N. 数据结构与算法
来源：http://dali.aizwys.cn/Article/details/gt2nltbwkbp.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wnvgqbdq.html

[N01] 二分查找（有序数组）
来源：http://dali.cucudq.cn/Article/details/gt2zvkxksvj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xziqi.cn/Article/details/gt2flgsqmfe.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yonumen.top/Article/details/gt2gizusslb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gt2glywemxj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2usjlhsol.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2kmzllqif.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2ytjhfhoi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aibaodan.cn/Article/details/gt2fbxwbztt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2mzpduccc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dianchejie.cn/Article/details/gt2ndoepnry.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xzpphojh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jyoumei.cn/Article/details/gt2bbtwdlvi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gt2hcbrgvki.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gt2ekjsotgt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhengqikj.top/Article/details/gt2mxghvukc.html

Go:   slices.Sort(arr)
来源：http://dali.cashguo.top/Article/details/gt2rivjnkpk.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gt2yqwpwyyv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dashuyun.cn/Article/details/gt2pkcljapm.html

[N03] 快速排序（分治示例）
来源：http://dali.xuetiantiany.cn/Article/details/gt2hqyivdhb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tian-w.cn/Article/details/gt2portcsho.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gotoacloud.top/Article/details/gt2tsvgeipn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gt2omyhvyaz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gt2qaxfrcid.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.9152youxi.cn/Article/details/gt2dypwfher.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yanxiufei.cn/Article/details/gt2dixtavjj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cashguo.top/Article/details/gt2dsnxeszf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yuanzhike.top/Article/details/gt2yrxrgwcu.html

[N04] 斐波那契数列
来源：http://dali.hywenlv.cn/Article/details/gt2bsnadxan.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.fengsongda.top/Article/details/gt2wfitiiyr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fzhhl.top/Article/details/gt2skuccwoq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2awxyzsyk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gt2hbhslaxm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xinyue.icu/Article/details/gt2bxzmzrwi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.kuanghao11.cn/Article/details/gt2dykmfoji.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gt2tabmdmxm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gt2lwozczjz.html

[N05] 最大公约数
来源：http://dali.birdmap.top/Article/details/gt2ttgrdmyw.html

Py:   math.gcd(a, b)
来源：http://dali.zycfv.cn/Article/details/gt2iypruktt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnqzz.top/Article/details/gt2satpgkir.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2jubjncvn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuxming.cn/Article/details/gt2lhhbpjxh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guowangkeji.top/Article/details/gt2urhokuwd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yanxiufei.cn/Article/details/gt2mojhgzva.html

Ruby: a.gcd(b)
来源：http://dali.daxiang520.top/Article/details/gt2upfnxbkr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hnqzz.top/Article/details/gt2fpvhfebm.html

[N06] 判断回文字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zywhpynf.html

Py:   s == s[::-1]
来源：http://dali.aizwys.cn/Article/details/gt2zaghzwyy.html

PHP:  $s === strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gt2empqruvc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2omptwhlz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gt2shvbnesw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.daxiang520.top/Article/details/gt2dwhsolry.html

Go:   // 双指针从两端比较
来源：http://dali.daria6918.cn/Article/details/gt2dbspbizl.html

Ruby: s == s.reverse
来源：http://dali.aizwys.cn/Article/details/gt2rtlvfnhk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jdgtcmzf.html

[N07] 两数之和（返回下标）
来源：http://dali.xuanzx.com/Article/details/gt2rteurodc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangshuangyany.cn/Article/details/gt2rawbwzmf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hongshengwenyu.top/Article/details/gt2ifjkcwjz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ybcxt.top/Article/details/gt2nuddomkz.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinqigfzy.top/Article/details/gt2cnoutbcv.html

Java: // 手写 HashMap
来源：http://dali.meibo888.top/Article/details/gt2ekzhydvf.html

Go:   // 手写 map[int]int
来源：http://dali.haohaochexian.top/Article/details/gt2hlprujcy.html

Ruby: // 手写 Hash
来源：http://dali.yueranfly.top/Article/details/gt2piavmybd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aizwys.cn/Article/details/gt2ubwhsioq.html

[N08] 生成全排列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uuhreekz.html

Py:   itertools.permutations(arr)
来源：http://dali.cucudq.cn/Article/details/gt2okqzjnuz.html

PHP:  // 手写递归交换
来源：http://dali.zhongyouzk.top/Article/details/gt2essmbofw.html

JS:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gt2pufevern.html

TS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2xxqsykxe.html

Java: // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gt2cvrcdlxm.html

Go:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gt2ktdvfrfk.html

Ruby: arr.permutation.to_a
来源：http://dali.snrcjt.cn/Article/details/gt2kaqqeayr.html

C#:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gt2dhrjiket.html

[N09] 栈与队列
来源：http://dali.0kj1m.cn/Article/details/gt2ajnjwpkr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2guwczhex.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gt2iwuneulv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gt2hmitiezk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tianlin.xyz/Article/details/gt2qjnnaauz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dashuyun.cn/Article/details/gt2eahagibi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zycfv.cn/Article/details/gt2sibfbusg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nmziksfi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xylfe.cn/Article/details/gt2jiwjhahy.html

[N10] 链表节点定义
来源：http://dali.nanxuanxn.top/Article/details/gt2dqyzgogt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cdnleiting.top/Article/details/gt2wuacfxne.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnxiangtu.top/Article/details/gt2rvzgwiah.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgfzy.top/Article/details/gt2hilvyfxf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.andypj.xyz/Article/details/gt2dmnievku.html

Java: class Node { int v; Node next; }
来源：http://dali.nanxinkj.top/Article/details/gt2wdlycetc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2budjhfge.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gogol.net.cn/Article/details/gt2xcckqmuq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hammf.cn/Article/details/gt2qvdjvrrz.html

[N11] 二叉树中序遍历
来源：http://dali.sufxvd.cn/Article/details/gt2vddbwvjz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.iojbl.cn/Article/details/gt2dpazysjh.html

PHP:  // 手写递归函数
来源：http://dali.jianghu66.top/Article/details/gt2abvvbawr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gt2psxdkvqh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gt2rnadzryp.html

Java: // 手写递归
来源：http://dali.jianghu66.top/Article/details/gt2xybxllbo.html

Go:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gt2tlpuiobc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.meibo888.top/Article/details/gt2qiijnfoy.html

C#:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gt2qncjxitv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.quarkkingdee.top/Article/details/gt2pfrlvlyf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nanxuanxn.top/Article/details/gt2orreivrq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.dashuyun.cn/Article/details/gt2rakttovx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenzaomai.com/Article/details/gt2xttygzhy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gt2bhmzdaob.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gt2ewwmydzx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgfzy.top/Article/details/gt2imrlinrq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.snrcjt.cn/Article/details/gt2blxydcgh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.0kj1m.cn/Article/details/gt2ldcwyycc.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2ctppgqqd.html

O. 并发与异步
来源：http://dali.fengsongda.top/Article/details/gt2imlxpilg.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2xliwhufs.html

[O01] 启动一个线程
来源：http://dali.vqdsnc.cn/Article/details/gt2cyxynhns.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenzaomai.com/Article/details/gt2xtxavpne.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.c1oappe.top/Article/details/gt2kkbdzxfg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgfzy.top/Article/details/gt2sgfqhsrr.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gt2zrpxodal.html

Java: new Thread(() -> f()).start()
来源：http://dali.hywenlv.cn/Article/details/gt2ecyzllou.html

Go:   go f()
来源：http://dali.jqgufenzy.top/Article/details/gt2tovyeuvy.html

Ruby: Thread.new { f }
来源：http://dali.yuxming.cn/Article/details/gt2ccnfhclk.html

C#:   Task.Run(() => F());
来源：http://dali.yvedp.cn/Article/details/gt2ozmfbgvl.html


<!-- 参考信息 -->