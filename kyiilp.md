代发 wailian999

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gt2wcosogvq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ppjwa.cn/Article/details/gt2ocmlvyyf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gt2grlnqtkf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gt2mskhugiy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gt2luyidnlt.html

[K07] 进制转换
来源：http://dali.aizwys.cn/Article/details/gt2vposawee.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2zdcnkjkh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenzaomai.com/Article/details/gt2ikyeiijp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2ptoizfgo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2lvbknvgw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gt2hgsrjtdx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jyoumei.cn/Article/details/gt2nehkqgdh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jyoumei.cn/Article/details/gt2xjbsktqx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2qbprfkel.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nwbrower.top/Article/details/gt2eznkqprz.html

Py:   pickle.dumps(obj)
来源：http://dali.hnqzz.top/Article/details/gt2xxbygtec.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhengqikj.top/Article/details/gt2jqnouxhw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gt2goovcngx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gt2hhbxbtmv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258888.top/Article/details/gt2rtcdnveo.html

Go:   encoding/gob
来源：http://dali.yj20258888.top/Article/details/gt2iieonvdd.html

Ruby: Marshal.dump(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rbeiazrp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cjfccfzk.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2kvxxrawx.html

L. 网络请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ryhnbbhx.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2aqwvnter.html

[L01] 发送 GET 请求
来源：http://dali.chenlongwang.top/Article/details/gt2lqvdqvol.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.9152youxi.cn/Article/details/gt2wohdumlc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yangfankeji.com/Article/details/gt2dyvfwwnq.html

JS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gt2pjwosxqy.html

TS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qdlhlonn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yanxiufei.cn/Article/details/gt2kkxgwltg.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhiwuduotai.top/Article/details/gt2edzxisiu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daria6918.cn/Article/details/gt2dxniagpe.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenlongwang.top/Article/details/gt2hiliricg.html

[L02] 发送 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gt2inbtdakv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.havefunace.top/Article/details/gt2vmlmkhss.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shzxlz.cn/Article/details/gt2yzhhajgy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gt2cnnjvioq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xinyue.icu/Article/details/gt2uzgluwro.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aibaodan.cn/Article/details/gt2ondazrib.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ckfmdcij.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cheryme.top/Article/details/gt2jdtismhj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jlsjyb.cn/Article/details/gt2qyvtzwvk.html

[L03] 设置自定义请求头
来源：http://dali.smart0.xyz/Article/details/gt2lhgfqscy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnxiangtu.top/Article/details/gt2bhpcjleg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tian-w.cn/Article/details/gt2tyuchyjs.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gt2etfnpdpd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gt2vmkmcpkr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.feifeiyinyue.top/Article/details/gt2dvutytqm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gt2czlvravc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cdnleiting.top/Article/details/gt2egcjcdht.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gt2gxfdrtzd.html

[L04] 设置超时
来源：http://dali.zhongyouzk.top/Article/details/gt2zqnwqlvn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258888.top/Article/details/gt2bvnftxtn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sxryk.cn/Article/details/gt2hmzkuuyc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2utflhder.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gt2yrsqbnaj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gt2hpfwljek.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hfpthk.cn/Article/details/gt2acxahutc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xinyue.icu/Article/details/gt2fanxmyhg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nwbrower.top/Article/details/gt2viuorjny.html

[L05] 上传文件（multipart）
来源：http://dali.quarkkingdee.top/Article/details/gt2mcyjersb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxinkj.top/Article/details/gt2vrgjhjwl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tdhuvqnn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gt2irhvntas.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gt2ugibzyrs.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2umyuftcs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuanzhike.top/Article/details/gt2ghxojxrz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sufxvd.cn/Article/details/gt2htaesyar.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2ayykmkrd.html

[L06] 解析响应为 JSON
来源：http://dali.jianghu66.top/Article/details/gt2lehnhhmg.html

Py:   resp.json()
来源：http://dali.gzhubu.top/Article/details/gt2radzprim.html

PHP:  json_decode($body, true);
来源：http://dali.cheryme.top/Article/details/gt2wxznrlhp.html

JS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gt2asgnkzrs.html

TS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gt2xhjrjzdh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.birdmap.top/Article/details/gt2aezhkdhw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zdqjudy.top/Article/details/gt2zmfckdco.html

Ruby: JSON.parse(resp.body)
来源：http://dali.0kj1m.cn/Article/details/gt2vnfjfhku.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gt2unjhmzok.html

[L07] 处理 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gt2fmivfdvr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnqzz.top/Article/details/gt2rdptihmo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sysykeji.top/Article/details/gt2zcbqhjxy.html

JS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gt2eluyshyn.html

TS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gt2sfuatekk.html

Java: resp.statusCode()
来源：http://dali.ehwqpu.com/Article/details/gt2epiegatu.html

Go:   resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gt2wjqavhvk.html

Ruby: resp.code.to_i
来源：http://dali.yanxiufei.cn/Article/details/gt2bxnqocpd.html

C#:   (int)resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gt2qvlpymjc.html

[L08] 并发请求多个地址
来源：http://dali.meibo888.top/Article/details/gt2egxifhpm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daxiang520.top/Article/details/gt2qfrbltaz.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258.top/Article/details/gt2tqksvxuj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gt2inbxkety.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gt2lynokqsh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sysykeji.top/Article/details/gt2dsqhtwcc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgfzy.top/Article/details/gt2mqmtrbtn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fzhhl.top/Article/details/gt2rnxrhsvw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aizwys.cn/Article/details/gt2kgscdawt.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2vudypcpk.html

M. 命令行 / 进程 / 环境
来源：http://dali.shangyingyoupin.top/Article/details/gt2mbwurpgu.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2gxtoajhv.html

[M01] 读取命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gt2bestdmba.html

Py:   sys.argv[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gt2cfcbzucn.html

PHP:  $argv;  $argc;
来源：http://dali.cqqwz.cn/Article/details/gt2ofvhajrs.html

JS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gt2gvhrffpo.html

TS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gt2lcponhxt.html

Java: args 数组（main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gt2rhwebrvt.html

Go:   os.Args[1:]
来源：http://dali.haohaochexian.top/Article/details/gt2zyezfiok.html

Ruby: ARGV
来源：http://dali.zycfv.cn/Article/details/gt2aygdxaob.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gt2ytqcuqmt.html

[M02] 读取环境变量
来源：http://dali.yangfankeji.com/Article/details/gt2zscobfbo.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hvdzlsiu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tbajpsqw.html

JS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gt2unnvcylz.html

TS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gt2pmyrsjes.html

Java: System.getenv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gt2azqqeixc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nwbrower.top/Article/details/gt2lpiowthx.html

Ruby: ENV["HOME"]
来源：http://dali.cheryme.top/Article/details/gt2hqmiagtx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gt2igadgutk.html

[M03] 执行外部命令
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rfumngvl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yvedp.cn/Article/details/gt2kvtpiqex.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tian-w.cn/Article/details/gt2wdhqifov.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gt2girggrqf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ehwqpu.com/Article/details/gt2lamponhv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ydzc1.top/Article/details/gt2qawrfoki.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenjidiqi.icu/Article/details/gt2mpkuxlhz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgufenzy.top/Article/details/gt2gcykxnkt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shuidangran.top/Article/details/gt2psdibwsa.html

[M04] 获取当前工作目录
来源：http://dali.ydzc1.top/Article/details/gt2nttfxkki.html

Py:   os.getcwd()
来源：http://dali.xziqi.cn/Article/details/gt2kaztmbkl.html

PHP:  getcwd();
来源：http://dali.hammf.cn/Article/details/gt2dcikmxcd.html

JS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gt2aaopobps.html

TS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gt2bsajsifs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxinkj.top/Article/details/gt2hlzzudkj.html

Go:   os.Getwd()
来源：http://dali.mhx1999.top/Article/details/gt2sepgbogm.html

Ruby: Dir.pwd
来源：http://dali.haohaochexian.top/Article/details/gt2bbwamtwt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgufenzy.top/Article/details/gt2hdikdrrb.html

[M05] 设置退出码
来源：http://dali.sweek.top/Article/details/gt2iuvjedbg.html

Py:   sys.exit(1)
来源：http://dali.fzhhl.top/Article/details/gt2euykzpkj.html

PHP:  exit(1);
来源：http://dali.xuetiantiany.cn/Article/details/gt2xftpsrtw.html

JS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gt2iboqwrrj.html

TS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gt2jbdslzvr.html

Java: System.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2mmeponru.html

Go:   os.Exit(1)
来源：http://dali.sweek.top/Article/details/gt2kuedofpa.html

Ruby: exit 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pdixbdal.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yongpay.top/Article/details/gt2rmwscqds.html

[M06] 向标准错误输出
来源：http://dali.pycfn.com/Article/details/gt2ugclacli.html

Py:   print("err", file=sys.stderr)
来源：http://dali.mhx1999.top/Article/details/gt2ylhjzavx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.svipenyu.cn/Article/details/gt2vczlzmvp.html

JS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gt2geanvulc.html

TS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gt2epfxbvbv.html

Java: System.err.println("err")
来源：http://dali.chenlongwang.top/Article/details/gt2snummpls.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ybcxt.top/Article/details/gt2fhujgbzw.html

Ruby: warn "err"
来源：http://dali.quarkkingdee.top/Article/details/gt2gtvszwgs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgfzy.top/Article/details/gt2fxkjjcfh.html

[M07] 判断是否为主入口
来源：http://dali.dashuyun.cn/Article/details/gt2ostjfeid.html

Py:   if __name__ == "__main__":
来源：http://dali.yuxming.cn/Article/details/gt2xznkrcny.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2qfvjnhwn.html

JS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gt2xwbgmsni.html

TS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gt2hknwwlrs.html

Java: public static void main(String[] args)
来源：http://dali.cdnleiting.top/Article/details/gt2jkivvvex.html

Go:   func main()
来源：http://dali.yj202588.top/Article/details/gt2eaylteec.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.pycfn.com/Article/details/gt2xwwzhtcf.html

C#:   static void Main(string[] args)
来源：http://dali.kuanghao11.cn/Article/details/gt2oicucktw.html

[M08] 获取系统与运行时信息
来源：http://dali.yuxming.cn/Article/details/gt2bctzeprg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqniixdl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gogol.net.cn/Article/details/gt2ruvsrcxu.html

JS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gt2xyhrcfpa.html

TS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gt2dytnkrza.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258.top/Article/details/gt2icckialf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.feifeiyinyue.top/Article/details/gt2umqmilco.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangshuangyany.cn/Article/details/gt2hxluiaqr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.iojbl.cn/Article/details/gt2mzxnigba.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2uvevhfqy.html

N. 数据结构与算法
来源：http://dali.fengsongda.top/Article/details/gt2lxwywsvp.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2dqdvkpvq.html

[N01] 二分查找（有序数组）
来源：http://dali.pycfn.com/Article/details/gt2kjnkkvme.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2vzzwkbue.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.redwolf501.top/Article/details/gt2exramgbp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gt2bsmjfeiy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gt2hsuvkwkf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2jewdeazm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2wtmpcnzv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aibaodan.cn/Article/details/gt2jobwsipb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2dedzbrbh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.snrcjt.cn/Article/details/gt2meyfuaep.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gt2ukawxkgr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yueranfly.top/Article/details/gt2yrjatprn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gt2pexxgune.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2sepulqzj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhongyouzk.top/Article/details/gt2kkmobybv.html

Go:   slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2nqnvlptf.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gt2ugrqvlzg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aizwys.cn/Article/details/gt2yvwhphnp.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxinkj.top/Article/details/gt2yfxjhrki.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhoulong.xyz/Article/details/gt2hcyhkeye.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinqigufen.top/Article/details/gt2ahyianij.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gt2ktbdvesa.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gt2bobaobqe.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ppjwa.cn/Article/details/gt2ijqqsruo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.svipenyu.cn/Article/details/gt2ritdjtuo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tianlin.xyz/Article/details/gt2yhqtjpri.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hammf.cn/Article/details/gt2flchamza.html

[N04] 斐波那契数列
来源：http://dali.gzhubu.top/Article/details/gt2hedzmwis.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gt2snpmabrr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gt2nfyehdvt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gt2xvkmbbuu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2gnyppiso.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gt2mxuuzdiz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zycfv.cn/Article/details/gt2vbpffmvz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gt2gbgbtmqg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gt2olsgiqte.html

[N05] 最大公约数
来源：http://dali.hnxiangtu.top/Article/details/gt2xejuuuig.html

Py:   math.gcd(a, b)
来源：http://dali.haohaochexian.top/Article/details/gt2asriavpn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.0kj1m.cn/Article/details/gt2hjtluqrt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gt2uxpjhenh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gt2bbynlsio.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.bjfxy.top/Article/details/gt2xcaihxzc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jlsjyb.cn/Article/details/gt2rohzepca.html

Ruby: a.gcd(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2qrfcvvmu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigfzy.top/Article/details/gt2kawjtdoq.html

[N06] 判断回文字符串
来源：http://dali.yangfankeji.com/Article/details/gt2iqgjjnso.html

Py:   s == s[::-1]
来源：http://dali.ivvv.top/Article/details/gt2dtpmutmx.html

PHP:  $s === strrev($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2shgjqywn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gt2gsryxxym.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ncvybhjq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sysykeji.top/Article/details/gt2crpmiqxv.html

Go:   // 双指针从两端比较
来源：http://dali.birdmap.top/Article/details/gt2lxedmyzm.html

Ruby: s == s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gt2lpvqxjbb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.wangshuangyany.cn/Article/details/gt2przuyhlg.html

[N07] 两数之和（返回下标）
来源：http://dali.kuanghao11.cn/Article/details/gt2vpfpzgpb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dianchejie.cn/Article/details/gt2drnceqnh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guowangkeji.top/Article/details/gt2fhmjbsnz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yonumen.top/Article/details/gt2gkvuaabu.html

TS:   // 手写 Map<string, number>
来源：http://dali.yonumen.top/Article/details/gt2cxhogqkj.html

Java: // 手写 HashMap
来源：http://dali.0kj1m.cn/Article/details/gt2zyczbuel.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigfzy.top/Article/details/gt2ywzfohat.html

Ruby: // 手写 Hash
来源：http://dali.gogol.net.cn/Article/details/gt2fntrface.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fzhhl.top/Article/details/gt2zoqrhlum.html

[N08] 生成全排列
来源：http://dali.cdnleiting.top/Article/details/gt2piulunij.html

Py:   itertools.permutations(arr)
来源：http://dali.gzhubu.top/Article/details/gt2lnyfxgfj.html

PHP:  // 手写递归交换
来源：http://dali.cucudq.cn/Article/details/gt2mgkihdae.html

JS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gt2katspteu.html

TS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2bwbnhsvs.html

Java: // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gt2kecqxkso.html

Go:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2blktxddi.html

Ruby: arr.permutation.to_a
来源：http://dali.cheryme.top/Article/details/gt2uocnhutd.html

C#:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gt2faqslgaf.html

[N09] 栈与队列
来源：http://dali.havefunace.top/Article/details/gt2uuwrhski.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ehwqpu.com/Article/details/gt2hstmjyjq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj20258888.top/Article/details/gt2cyttglzb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2amrigola.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gogol.net.cn/Article/details/gt2qrjaqvba.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ymjzpkdc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhengqikj.top/Article/details/gt2cflctewb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gt2vayrrhbe.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yvedp.cn/Article/details/gt2bgkhekbq.html

[N10] 链表节点定义
来源：http://dali.0kj1m.cn/Article/details/gt2kqcmsgbe.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yangfankeji.com/Article/details/gt2dafvhfnr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hammf.cn/Article/details/gt2ueipuqik.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigfzy.top/Article/details/gt2ulmxdxgn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ppjwa.cn/Article/details/gt2axvlkkrl.html

Java: class Node { int v; Node next; }
来源：http://dali.chenzaomai.com/Article/details/gt2wvyqtkst.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gogol.net.cn/Article/details/gt2nwdajxps.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.birdmap.top/Article/details/gt2atjcskiu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gogol.net.cn/Article/details/gt2mnujxuvp.html

[N11] 二叉树中序遍历
来源：http://dali.yangfankeji.com/Article/details/gt2vpgohhho.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jlsjyb.cn/Article/details/gt2fqfpdjqm.html

PHP:  // 手写递归函数
来源：http://dali.chenzaomai.com/Article/details/gt2wysdrfmw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gt2ovbfjfue.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sufxvd.cn/Article/details/gt2xbkkgcgf.html

Java: // 手写递归
来源：http://dali.xylfe.cn/Article/details/gt2oetcxiso.html

Go:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gt2pwfppsxf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhiwuduotai.top/Article/details/gt2hygzfyij.html

C#:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gt2oiduoxwj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinqigufen.top/Article/details/gt2xwjxmjfl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.mhx1999.top/Article/details/gt2fkfysfuz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yuxming.cn/Article/details/gt2uzszphel.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hysaishi.cn/Article/details/gt2oiggkcek.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dianchejie.cn/Article/details/gt2gaexrdkv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jlsjyb.cn/Article/details/gt2hhttlkih.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daria6918.cn/Article/details/gt2szfqlwjw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gt2dwnjiljx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258.top/Article/details/gt2miqiygmc.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2pbpxynkk.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2snjcwopr.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2cltgtjeh.html

[O01] 启动一个线程
来源：http://dali.gaohongyu789.top/Article/details/gt2vvirjkly.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2daziqyje.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nwbrower.top/Article/details/gt2gdqxtdkr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xuanzx.com/Article/details/gt2uotfjseq.html

TS:   // 同 JS
来源：http://dali.jqgufenzy.top/Article/details/gt2pssirkvp.html

Java: new Thread(() -> f()).start()
来源：http://dali.ydzc1.top/Article/details/gt2alvdlizl.html

Go:   go f()
来源：http://dali.yanxiufei.cn/Article/details/gt2hplahmpm.html

Ruby: Thread.new { f }
来源：http://dali.jqgufenzy.top/Article/details/gt2bvknsnmx.html

C#:   Task.Run(() => F());
来源：http://dali.wangshuangyany.cn/Article/details/gt2bctjsrvo.html

[O02] 使用线程池
来源：http://dali.nanxuanxn.top/Article/details/gt2yuoolpmt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.andypj.xyz/Article/details/gt2jvkzjcvi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daria6918.cn/Article/details/gt2gyvemhst.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gt2aigaeblw.html


<!-- 参考信息 -->