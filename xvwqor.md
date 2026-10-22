代发 wailian999

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gt2rehnsrao.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gcwjtbcx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aizwys.cn/Article/details/gt2ilxbsmtv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gt2tqptvixy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gt2rwbhisvg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.pycfn.com/Article/details/gt2rdaivhwk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gt2qjmclwwd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gt2brhmeoxj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xdtfcztp.html

[K07] 进制转换
来源：http://dali.pengpengdd.cyou/Article/details/gt2nyfgmatu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2fdkprvcr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zowrxxuh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gt2qelukpcg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2syiwufsg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2dychpjrv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxinkj.top/Article/details/gt2ihmxrvfn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.meibo888.top/Article/details/gt2ybmjhuzb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2aixhfcrf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zycfv.cn/Article/details/gt2kliivoay.html

Py:   pickle.dumps(obj)
来源：http://dali.guannengcc.top/Article/details/gt2znrqonxy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xlkwcfgs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nwbrower.top/Article/details/gt2pstcxfjq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gt2pmaaecjd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.c1oappe.top/Article/details/gt2kgimrmba.html

Go:   encoding/gob
来源：http://dali.wangshuangyany.cn/Article/details/gt2dorzddib.html

Ruby: Marshal.dump(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2fsxnaogs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gt2nhgegugg.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2pvizujfp.html

L. 网络请求
来源：http://dali.dashuyun.cn/Article/details/gt2tvywyesa.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2qasinnyp.html

[L01] 发送 GET 请求
来源：http://dali.gzhubu.top/Article/details/gt2pflvbzlb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jlsjyb.cn/Article/details/gt2jxznsois.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ijdytzcx.html

JS:   await fetch(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pbpxxwhr.html

TS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gt2hrvomzyo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tianlin.xyz/Article/details/gt2vyxspttz.html

Go:   resp, err := http.Get(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bgoynfrz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zdqjudy.top/Article/details/gt2hgykpgdm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sweek.top/Article/details/gt2tefylubr.html

[L02] 发送 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gt2exglyttj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangdashe.top/Article/details/gt2rrxmuwti.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.quarkkingdee.top/Article/details/gt2lztefmfd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gt2cuvdyhcs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gt2cowutdww.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guowangkeji.top/Article/details/gt2xzswfguq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxuanxn.top/Article/details/gt2sjijdanf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sweek.top/Article/details/gt2gcqkaxkc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hywenlv.cn/Article/details/gt2rgzjmqgg.html

[L03] 设置自定义请求头
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wvavjrnq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhixingplan.top/Article/details/gt2yyfbjdel.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xinyue.icu/Article/details/gt2scwjridj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gt2rkrarnzu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gt2cqrtcahw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daxiang520.top/Article/details/gt2lwblokzm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gt2qzlxomqa.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hfpthk.cn/Article/details/gt2mihuskoh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gt2piulbfeo.html

[L04] 设置超时
来源：http://dali.bjfxy.top/Article/details/gt2vmjmnqre.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xylfe.cn/Article/details/gt2vlrprdgh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cashguo.top/Article/details/gt2siudrkbo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenlongwang.top/Article/details/gt2tryakket.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gt2vxcvlowq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhoulong.xyz/Article/details/gt2glyqwcud.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pengpengdd.cyou/Article/details/gt2xnywrwtb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.andypj.xyz/Article/details/gt2sixzssja.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuanzx.com/Article/details/gt2gchcmlbj.html

[L05] 上传文件（multipart）
来源：http://dali.nanxuanxn.top/Article/details/gt2sabctplc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhongyouzk.top/Article/details/gt2oqenetzj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.vqdsnc.cn/Article/details/gt2vaarvegx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gt2pwsmlzsu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gt2bxbdcdvl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yangfankeji.com/Article/details/gt2lksjojwh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2olsygwea.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.mhx1999.top/Article/details/gt2uuybaqqd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj202588.top/Article/details/gt2jmvjkzyp.html

[L06] 解析响应为 JSON
来源：http://dali.nanxuanxn.top/Article/details/gt2ccriicbb.html

Py:   resp.json()
来源：http://dali.guowangkeji.top/Article/details/gt2ihqqjuno.html

PHP:  json_decode($body, true);
来源：http://dali.andypj.xyz/Article/details/gt2zeunghhz.html

JS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gt2ufvlaukf.html

TS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gt2ohrntjtw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yueranfly.top/Article/details/gt2jgahvxtv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yqfzjyff.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zycfv.cn/Article/details/gt2ovbrqjin.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.haohaochexian.top/Article/details/gt2bzopjixj.html

[L07] 处理 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gt2iaggkbez.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigufen.top/Article/details/gt2mnnrexgc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sweek.top/Article/details/gt2plitwjyz.html

JS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gt2zohipuhh.html

TS:   resp.ok;  resp.status
来源：http://dali.hnxiangtu.top/Article/details/gt2wvejbccd.html

Java: resp.statusCode()
来源：http://dali.yj20258.top/Article/details/gt2zrknrzvb.html

Go:   resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gt2zdqmlpez.html

Ruby: resp.code.to_i
来源：http://dali.dianchejie.cn/Article/details/gt2junkhvpi.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gt2tlwuezcc.html

[L08] 并发请求多个地址
来源：http://dali.yongpay.top/Article/details/gt2dwshxdrz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shzxlz.cn/Article/details/gt2msakbkag.html

PHP:  curl_multi_init() 系列
来源：http://dali.hfpthk.cn/Article/details/gt2lxewtrjy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2hgwtaymh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ofndrwyt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nwbrower.top/Article/details/gt2brngogpc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhoulong.xyz/Article/details/gt2feuylliy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yangfankeji.com/Article/details/gt2akiimtzl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gotoacloud.top/Article/details/gt2tkapgwud.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2neynihnv.html

M. 命令行 / 进程 / 环境
来源：http://dali.cucudq.cn/Article/details/gt2dndgindm.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2bvfygiut.html

[M01] 读取命令行参数
来源：http://dali.smart0.xyz/Article/details/gt2vkyamgqc.html

Py:   sys.argv[1:]
来源：http://dali.meibo888.top/Article/details/gt2kbgrjhwm.html

PHP:  $argv;  $argc;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zyrhkfxc.html

JS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rjivkiqq.html

TS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bwrtggox.html

Java: args 数组（main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gt2rozedwjw.html

Go:   os.Args[1:]
来源：http://dali.ppjwa.cn/Article/details/gt2gwjyzbxy.html

Ruby: ARGV
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zpcauomr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gt2saakwklc.html

[M02] 读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gt2qekyspum.html

Py:   os.environ.get("HOME")
来源：http://dali.wangdashe.top/Article/details/gt2azqfoift.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gt2mnbzhcty.html

JS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gt2kcbtvods.html

TS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gt2tyrkammj.html

Java: System.getenv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kpbfqeds.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2jfhzjitv.html

Ruby: ENV["HOME"]
来源：http://dali.shangyingyoupin.top/Article/details/gt2prywpcih.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.9152youxi.cn/Article/details/gt2xmkuqgcr.html

[M03] 执行外部命令
来源：http://dali.gotoacloud.top/Article/details/gt2rcywmqpl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jiagoushi.top/Article/details/gt2doqgmhjb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dashuyun.cn/Article/details/gt2vjrodkdl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gt2nawwxrwo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gt2pjrneymv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xinyue.icu/Article/details/gt2olidhwow.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shzxlz.cn/Article/details/gt2vogcumfz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sufxvd.cn/Article/details/gt2alduklqq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.redwolf501.top/Article/details/gt2jzvbfmer.html

[M04] 获取当前工作目录
来源：http://dali.meibo888.top/Article/details/gt2oibvbouv.html

Py:   os.getcwd()
来源：http://dali.vqdsnc.cn/Article/details/gt2izlpsuql.html

PHP:  getcwd();
来源：http://dali.aibaodan.cn/Article/details/gt2oeiodfrf.html

JS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gt2yjaxbzdd.html

TS:   process.cwd()
来源：http://dali.gzhubu.top/Article/details/gt2kqchekmx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhiwuduotai.top/Article/details/gt2vpvvtyfw.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2iungmosu.html

Ruby: Dir.pwd
来源：http://dali.xinyue.icu/Article/details/gt2jrwwnpaw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.havefunace.top/Article/details/gt2bxlbukfu.html

[M05] 设置退出码
来源：http://dali.chenlongwang.top/Article/details/gt2ixvnstce.html

Py:   sys.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2kvzmcwgd.html

PHP:  exit(1);
来源：http://dali.tianlin.xyz/Article/details/gt2teownzxm.html

JS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2aenozmnm.html

TS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2urfoibko.html

Java: System.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2numlunqz.html

Go:   os.Exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2frvsldik.html

Ruby: exit 1
来源：http://dali.yj20258.top/Article/details/gt2fcjnrtpu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bbzzpqme.html

[M06] 向标准错误输出
来源：http://dali.hywenlv.cn/Article/details/gt2tvjvvgor.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gtyqnkai.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gogol.net.cn/Article/details/gt2edjoiakt.html

JS:   console.error("err")
来源：http://dali.smart0.xyz/Article/details/gt2kcnhbunz.html

TS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gt2wrsbvasn.html

Java: System.err.println("err")
来源：http://dali.tianlin.xyz/Article/details/gt2ldwoenzb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cheryme.top/Article/details/gt2hvjvoajt.html

Ruby: warn "err"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vhmfxmpx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.0kj1m.cn/Article/details/gt2hpkqymcx.html

[M07] 判断是否为主入口
来源：http://dali.dashuyun.cn/Article/details/gt2glycyiiu.html

Py:   if __name__ == "__main__":
来源：http://dali.zycfv.cn/Article/details/gt2nfiawxro.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qmtbgldp.html

JS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gt2bubvfxpq.html

TS:   require.main === module
来源：http://dali.yonumen.top/Article/details/gt2rbnonblc.html

Java: public static void main(String[] args)
来源：http://dali.snrcjt.cn/Article/details/gt2pgxdhgsw.html

Go:   func main()
来源：http://dali.jiagoushi.top/Article/details/gt2fljhucfk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.svipenyu.cn/Article/details/gt2tkzxrlov.html

C#:   static void Main(string[] args)
来源：http://dali.birdmap.top/Article/details/gt2yjbbkuge.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgufenzy.top/Article/details/gt2fkrbaqal.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigufen.top/Article/details/gt2bpjtrwyl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangdashe.top/Article/details/gt2tdmsabxh.html

JS:   process.platform;  process.version
来源：http://dali.yuxming.cn/Article/details/gt2dxsylnnu.html

TS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gt2qikywrrb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hammf.cn/Article/details/gt2rmzkokbf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sweek.top/Article/details/gt2dqgwfxjx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hsajcjgw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.andypj.xyz/Article/details/gt2qseryudl.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2wbteqium.html

N. 数据结构与算法
来源：http://dali.havefunace.top/Article/details/gt2zkgpvymc.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2situugxz.html

[N01] 二分查找（有序数组）
来源：http://dali.havefunace.top/Article/details/gt2dbtqjouu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2focyepgu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tian-w.cn/Article/details/gt2lppvwaiv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gt2mntcttxd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gt2agqauahw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2yqroxwgi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2olbkszcw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qvsszpcu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gt2xkxbfbzl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.9152youxi.cn/Article/details/gt2pgdsxroa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gt2inpjpbbo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.quarkkingdee.top/Article/details/gt2xstxzjzy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gt2swptyykn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gt2cqegmftl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.smart0.xyz/Article/details/gt2ugbshrwl.html

Go:   slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2kqjqervb.html

Ruby: arr.sort
来源：http://dali.jqgfzy.top/Article/details/gt2qatosnyy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ehwqpu.com/Article/details/gt2txousafl.html

[N03] 快速排序（分治示例）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ffgktnxp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xziqi.cn/Article/details/gt2szhlrvby.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cucudq.cn/Article/details/gt2eutmzzfs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gt2hahkzgeq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guowangkeji.top/Article/details/gt2ayrvipdn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tanke756.top/Article/details/gt2pwavvgpt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ivvv.top/Article/details/gt2sdlnbbel.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj202588.top/Article/details/gt2uvcrxbma.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tanke756.top/Article/details/gt2jiclqnqz.html

[N04] 斐波那契数列
来源：http://dali.jqgufenzy.top/Article/details/gt2cjpfkwxh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gt2kyrkncel.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuxming.cn/Article/details/gt2jszwfmix.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gt2wcgcyboi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gt2oajdigtg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.mhx1999.top/Article/details/gt2mtbhihvc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fxuzlnjw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gt2muqfkpwr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gt2ljzsasjh.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gt2brrmjkhg.html

Py:   math.gcd(a, b)
来源：http://dali.gotoacloud.top/Article/details/gt2kvvzuucq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dianchejie.cn/Article/details/gt2gnbbirul.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.smart0.xyz/Article/details/gt2wsvyrfqd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gt2tgrersgo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.c1oappe.top/Article/details/gt2uybwhzza.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yongpay.top/Article/details/gt2gbzmmute.html

Ruby: a.gcd(b)
来源：http://dali.hammf.cn/Article/details/gt2wadhpjup.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ivvv.top/Article/details/gt2uvweldrx.html

[N06] 判断回文字符串
来源：http://dali.redwolf501.top/Article/details/gt2vxvyjqfb.html

Py:   s == s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2skobcdbh.html

PHP:  $s === strrev($s);
来源：http://dali.xziqi.cn/Article/details/gt2yiikbssj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gt2rdqlccjw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fhiampqw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.redwolf501.top/Article/details/gt2eqpwgtbq.html

Go:   // 双指针从两端比较
来源：http://dali.c1oappe.top/Article/details/gt2ucncjbqs.html

Ruby: s == s.reverse
来源：http://dali.fzhhl.top/Article/details/gt2mpxteyso.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.pycfn.com/Article/details/gt2wyaqsktt.html

[N07] 两数之和（返回下标）
来源：http://dali.sufxvd.cn/Article/details/gt2gatpfvdh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yvedp.cn/Article/details/gt2lxohkjyj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tanke756.top/Article/details/gt2jbpfbjbs.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cheryme.top/Article/details/gt2rbfcqpoc.html

TS:   // 手写 Map<string, number>
来源：http://dali.gaohongyu789.top/Article/details/gt2hwpnpjbn.html

Java: // 手写 HashMap
来源：http://dali.haohaochexian.top/Article/details/gt2lemlfvxh.html

Go:   // 手写 map[int]int
来源：http://dali.vqdsnc.cn/Article/details/gt2qyrjvzyd.html

Ruby: // 手写 Hash
来源：http://dali.svipenyu.cn/Article/details/gt2atymlaau.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nanxinkj.top/Article/details/gt2ttiplypx.html

[N08] 生成全排列
来源：http://dali.ppjwa.cn/Article/details/gt2kbcdmzbq.html

Py:   itertools.permutations(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2hyauwntx.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2arjidksj.html

JS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2mzypezrp.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wuugdgnr.html

Java: // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gt2jdmefsxy.html

Go:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2smdktslr.html

Ruby: arr.permutation.to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tcjtrkjb.html

C#:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gt2ppdikqpo.html

[N09] 栈与队列
来源：http://dali.hnqzz.top/Article/details/gt2htjtvzgs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.smart0.xyz/Article/details/gt2nvrndfhz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.guannengcc.top/Article/details/gt2mbowkqyf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.c1oappe.top/Article/details/gt2oltytyye.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yanxiufei.cn/Article/details/gt2csyelrvy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cheryme.top/Article/details/gt2kcdpkchc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxinkj.top/Article/details/gt2xrxxwoqr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gt2jguxmqmk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gotoacloud.top/Article/details/gt2prlrcrxc.html

[N10] 链表节点定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2saebmgbd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dashuyun.cn/Article/details/gt2dbjsvmjl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.bjfxy.top/Article/details/gt2omtlbaup.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj202588.top/Article/details/gt2nhwlcski.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuanzx.com/Article/details/gt2zxqwmghw.html

Java: class Node { int v; Node next; }
来源：http://dali.tian-w.cn/Article/details/gt2aqahjrby.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hammf.cn/Article/details/gt2ynnnzhhn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tianlin.xyz/Article/details/gt2zpgmeqra.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tagbkyka.html

[N11] 二叉树中序遍历
来源：http://dali.gotoacloud.top/Article/details/gt2auzklnna.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dashuyun.cn/Article/details/gt2cxwnqjag.html

PHP:  // 手写递归函数
来源：http://dali.meibo888.top/Article/details/gt2xyfdzixw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.c1oappe.top/Article/details/gt2uxttddih.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gt2qnrtcxbp.html

Java: // 手写递归
来源：http://dali.sweek.top/Article/details/gt2fvtpzlve.html

Go:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hbaoqmwl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.quarkkingdee.top/Article/details/gt2egmdkovz.html

C#:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gt2hcpvrtpo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.quarkkingdee.top/Article/details/gt2arkvxwmr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daria6918.cn/Article/details/gt2qzgcdqon.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gogol.net.cn/Article/details/gt2dfvdkscg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuetiantiany.cn/Article/details/gt2reerzrcw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2svnmkhwv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gt2xhmyjpjf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zycfv.cn/Article/details/gt2bknvtpan.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yonumen.top/Article/details/gt2fgfhtrar.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gt2zoqiqizj.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2efndfeuu.html

O. 并发与异步
来源：http://dali.zhengqikj.top/Article/details/gt2vtstvios.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2zrqeuvaw.html

[O01] 启动一个线程
来源：http://dali.andypj.xyz/Article/details/gt2whdncetq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ehwqpu.com/Article/details/gt2aieutclo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenlongwang.top/Article/details/gt2nztltdyl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nwbrower.top/Article/details/gt2lipaycxq.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gt2rhcswnmn.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qbhpicrx.html

Go:   go f()
来源：http://dali.shuidangran.top/Article/details/gt2btwdjfxw.html

Ruby: Thread.new { f }
来源：http://dali.shuidangran.top/Article/details/gt2bkycfjmu.html

C#:   Task.Run(() => F());
来源：http://dali.chenlongwang.top/Article/details/gt2ecumwuit.html


<!-- 参考信息 -->